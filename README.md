# Software developer building practical tools

I build practical desktop applications, local APIs, and automation tools. My main project work is in **C#/.NET, Python, and TypeScript** (React and Angular); my open-source work also spans **Go, Java, Kotlin, and Rust**.

## Selected projects

- [Roblox Animator Desktop](https://github.com/TheIrvin/Roblox_Animation) — **Tauri 2, Rust, React, TypeScript**; an MIT-licensed local animation editor with a Roblox Studio plugin, samples, and Windows installers.
- [Video Pipeline](https://github.com/TheIrvin/Generador_Video_PipeLine) — **Python, FastAPI, OpenCV, NumPy**; an MIT-licensed local API that transfers visible motion from a guide video onto a still image, persists job history, and reports jobs interrupted by a restart.
- [Subtitle Editor](https://github.com/TheIrvin/Subtitulador-de-videos-en-Espanol-e-Ingles-9-16) — **Python, FastAPI, Electron, React, Vite**; an MIT-licensed desktop workflow for transcribing, editing, and exporting bilingual vertical videos.
- [Pipeline Workflows](https://github.com/TheIrvin/PipeLine_Workflows) — **Python, Docker, n8n, SQLite**; an MIT-licensed self-hosted content workflow with a local approval dashboard.
- [FileToMarkdown](https://github.com/TheIrvin/FileToMarkdown) — **C#, ASP.NET Core, Python, SQLite**; an MIT-licensed local app with a responsive document workspace for converting files, searching a private library, and reviewing cited answers.
- [Angular REST Product Catalog](https://github.com/TheIrvin/Web_Services_REST) — **Angular 22, TypeScript, Vitest, JSON Server**; an MIT-licensed local CRUD app with a documented API setup, a real UI screenshot, and six HTTP service tests.

## Open-source contributions

- [Cartograph #25](https://github.com/pacman-cli/Cartograph/pull/25) and [#49](https://github.com/pacman-cli/Cartograph/pull/49) — documented public API and remaining public types, and clarified behavior descriptions; Java 17 tests and zero-warning Javadoc checks passed. **Both merged.**
- [uniOS #25](https://github.com/unionyxx/uniOS/pull/25) — added visible status feedback before the network settings app starts DHCP renewal. **Merged.**
- [CodePrism #68](https://github.com/knight22-21/CodePrism/pull/68) — rejected option-like Git diff ranges and added CLI regression tests. **Merged.**
- [CodePrism #71](https://github.com/knight22-21/CodePrism/pull/71) — reject unknown `--languages` values instead of silently indexing with a broader language set; added regression coverage. **Merged.**
- [LOKI #11](https://github.com/Elabsurdo984/loki-agent/pull/11) — discard a failed user turn when every provider attempt fails, with a regression test. **Merged.**
- [drawpyo #141](https://github.com/MerrimanInd/drawpyo/pull/141) — added configurable group factories to `TreeDiagram`, including a default and custom-factory tests. **Merged.**

### In review

- [go-collections #269](https://github.com/pickeringtech/go-collections/pull/269) — wrote a usage guide for Go preprocessing tools and linked it from the package indexes. Local package tests pass; CI is waiting for maintainer approval of the workflow run, and review is pending.
- [semantic-policy #115](https://github.com/semanticpolicy/semantic-policy/pull/115) — added CLI validation and regression tests for empty input paths in a .NET evaluation tool. Local build and tests pass; CI is waiting for maintainer approval of the workflow run, and review is pending.
- [groq-pr-reviewer-net #8](https://github.com/danhpaiva/groq-pr-reviewer-net/pull/8) — added `--lang` support for six review languages with localized headings and fallback tests; all 11 local tests pass. No CI checks or maintainer review have been reported.
- [compose-hardware-insets #27](https://github.com/damson/compose-hardware-insets/pull/27) — added tested Kotlin/Compose alignments for horizontal screen edges; the maintainer verified the gate on current `develop`, while GitHub's check for the rebased fork awaits approval.

- [ledger-core #32](https://github.com/softvasco/ledger-core/pull/32) — added architecture tests for Domain dependencies and Application boundaries. Build passes cleanly; Domain and Application suites pass (96 tests total); CI and CodeQL are waiting for maintainer approval of their workflow runs, and review is pending.

I value focused changes, tests that capture the behavior, and clear notes about what has and has not been verified.
