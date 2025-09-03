# {{T}} Typelate

Thank you for navigating to **Typelate** — hypermedia power tools for professional Go developers.

I build libraries that make maintaining HTML-driven web apps safer and easier.
If you care about strong types, safe refactoring, and hypermedia as an application architecture, you’re in the right place.

✨ What is Typelate?
Building production Go systems, the same pain points kept surfacing:

- How do you test HTML endpoints in a way that’s antifragile and easy to extend?
- How do you refactor templates safely, catching type errors before they hit runtime?
- How do you connect routes, templates, and domain logic without boilerplate or reflection?

The repositories in the Typelate organization solve these problems.
Typelate software is a set of tools for Gophers who want to build hypermedia-driven applications (HDAs) with confidence.

## 📦 Core Projects

### [**dom**](https://github.com/typelate/dom)
*A Go implementation of the Document Object Model (DOM).*

- Provides DOM-like APIs for working with HTML in Go.
- Useful for **behavior-driven testing** of HTML responses.
- Long battle-tested in real-world projects.

👉 Use `dom` to **inspect and assert on HTML** without regex hacks.

### [**muxt**](https://github.com/typelate/muxt)
*Code generation for hypermedia routes.*

- Scans `.gohtml` templates for route definitions and **generates Go handlers**.
- Eliminates boilerplate by mapping **routes → templates → Go methods**.
- Optional integration with `check` for **template type-checking**.
- Generates **plain, standard-library Go code** — no frameworks or hidden magic.

👉 Use `muxt` when you want **type-safe, maintainable hypermedia routing**.

## 🔗 How They Fit Together

The Typelate ecosystem is designed so the tools **stand alone** but work best together:

- **`muxt`** generates routes and glue code from your templates.
- **`dom`** helps you test the HTML your app actually returns.

Together, they form a workflow that lets you **ship Go web apps with confidence** — without leaving the comfort of the standard library.

While not required, I also use the following dependencies and I know these additional tools work well with `muxt` and `dom`:
- https://github.com/stretchr/testify - for test assertions
- https://docs.sqlc.dev - for type-safe database interactions
- https://github.com/maxbrunsfeld/counterfeiter - for test double generation
- https://htmx.org - for more engaging user interface functionality

## Roadmap

I intend to add more tools for observability, integration testing (chromedp wrapper), and plenty of working examples.

For updates:
- [Follow Typelate on GitHub](https://github.com/typelate)
- [Connect with Christopher Hunter on LinkedIn](https://linkedin.com/in/crhntr)
