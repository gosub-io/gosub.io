---
title: "The advantages of modularity in Gosub"
metatitle: "Because we can't plan for everything ahead of time"
description: "The Gosub engine is designed as a modular system, allowing us to add new features and components without rewriting the entire engine."
date: 2026-07-22
author: "Joshua Thijssen"
---

One of the major advantages of the Gosub engine is its modularity. New features and components can be added without having to rewrite the entire engine.

This is especially important in a rapidly changing environment, where new requirements and use cases can appear at any time. We simply do not know everything the engine will need to support in the future. By keeping its components as independent and interchangeable as possible, we can adapt without having to redesign large parts of the system.

Gosub currently supports multiple rendering backends. We are working with Skia, Cairo, and Vello, each of which uses a different mechanism to display content on the screen.

As an experiment, we decided to add something completely different: a textual rendering backend that outputs a webpage directly to a terminal or text console.

Curious about how difficult such a backend would be to implement, we started building one. The answer turned out to be: surprisingly easy.

Because of the modular architecture of the Gosub engine, we could implement the textual backend without making significant changes to the existing rendering code. We created a new module that implements the required interfaces, and the engine was able to use it in the same way as the graphical backends.

The implementation is still very limited. Some of the functionality it would need does not exist in Gosub yet. For example, we do not currently have the keyboard event handling required to interact with the page from the terminal.

What we can already do, however, is render text with the correct foreground and background colors. Headings and other styled elements can be represented, and borders could be rendered using terminal characters, although they do not always translate particularly well to a text-based display.

Images are another matter. A traditional terminal cannot display them in the same way as a graphical window, so they are currently omitted. In the future, they could be represented through alternative text, placeholders, or one of the image protocols supported by some modern terminals.

The experiment is still small, but it demonstrates why modularity matters.

It allows us to explore ideas that we did not anticipate when the engine was first designed. A text browser powered by the same Gosub engine as a graphical browser could open up entirely new use cases.

It could provide a lightweight browsing environment for terminals and remote systems. It could be useful for developers who want to inspect, test, or debug page rendering without starting a graphical interface. It could also contribute to accessibility work, especially when combined with a semantic representation of the document and support for assistive technologies.

A textual renderer is only one example. The larger point is that we cannot plan for every future requirement. What we can do is build an engine that leaves enough room for ideas we have not thought of yet.

That is the real advantage of modularity.
