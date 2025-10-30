Typelate is a set of open-source Go packages and utilities for developers building hypermedia-driven applications (HDAs). It addresses a common problem in web development: modern stacks often separate frontend and backend in ways that increase accidental complexity. Engineers spend more time navigating state abstractions and microservices than delivering features. Typelate publishes tools that reduce this friction, letting you reason about your application end-to-end with clarity.

## Core Repositories

### Muxt

[Muxt](https://github.com/typelate/muxt) provides a structured workflow for defining templates, routes, and domain logic. It enforces patterns that reduce boilerplate, simplify refactoring, and help teams ship features quickly without fragile abstractions. Muxt lets you focus on behavior rather than plumbing, reducing the hidden costs that arise from mismatched frontend/backend architectures.

### DOM

[DOM](https://github.com/typelate/dom) implements the Document Object Model in Go, enabling behavior-driven testing of HTML endpoints. Instead of brittle tests that mirror convoluted frontend logic, DOM allows you to reason about rendered output directly, aligning tests with user experience. This makes refactoring safer and accelerates development cycles.

## Philosophy

Typelate tools aim to minimize the engineering overhead imposed by modern web architecture. They help teams:

* Reduce maintenance costs by keeping dependencies minimal.
* Expand application scope safely by making data flow explicit.
* Accelerate development by providing tools that reflect real workflows.
* Avoid accidental complexity from API gateways, convoluted runtime behavior, and other overengineered patterns.

In short, Typelate helps engineers ship Go web apps with confidence, focusing on meaningful work rather than plumming through convoluted layers required by modern software stacks.

## Complimentary Tools

Muxt and DOM integrate well with these libraries:

* [HTMX](https://htmx.org) — interactive frontend behavior
* [stretchr/testify](https://github.com/stretchr/testify) — test assertions
* [sqlc](https://docs.sqlc.dev) — type-safe database queries
* [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) — test double generation

Together, they form a workflow that lets you ship Go web apps efficiently, staying close to the standard library.

## Roadmap

Future software development includes observability tools, web standards-based cache controls, a chromedp-based integration testing wrapper, and additional practical examples. Upcoming content will include video and written tutorials and essays.

For updates:

* [Follow Typelate on GitHub](https://github.com/typelate)
* [Connect with Christopher Hunter on LinkedIn](https://linkedin.com/in/crhntr)
