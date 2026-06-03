# Hi, I'm Naftali(Tali) Caplan

Computer Science student at **Northeastern University**. I build full-stack applications, developer tools, and am looking into expanding into other projects. I really enjoy design phases and getting to shape an application before the code, and then once programing works I enjoy working more backend and developing data layers.

---

## Projects

### 🔧 ADR Manager — TC Annotation Layer
> VS Code Extension · TypeScript · Open Source · CS 4530

Contributed to an open-source VS Code extension for managing Architectural Decision Records (MADRs). As part of a 5-person intensive, I owned the data layer that every other track depended on.

**What I built:**
- Designed the `TcAnnotation` TypeScript interface and all enum types (`TcCategory`, `TcSignal`, `TcStatus`) as the shared schema used by the whole team
- Built `parseTcFromYaml()` and `serializeTcToYaml()` — reads and writes TC annotation fields from YAML frontmatter automatically on every parse and save, without touching any other YAML keys
- Implemented mode-aware serialisation: pro-only fields (`tc-status`, `tc-related`) are locked behind professional editor mode
- Built `validateTcAnnotation()` — validates all 6 TC field types with per-field error messages consumed by the UI layer
- Added `tc-schema-version` stamping for future migration support and real-world compatibility testing against JabRef's 60-file ADR corpus
- Fixed all test fixture incompatibilities introduced by the MADR 2.x → 4.0 grammar migration
- **78 tests passing** across 4 test suites (parser, validator, real-repo compatibility, utils)

**Stack:** `TypeScript` `js-yaml` `ANTLR4` `Jest` `VS Code Extension API`

[View Repository →](https://github.com/OwenSweetman/SummerSchool_MADR)

---

### 🍳 CookYourBooks
> Full-Stack Desktop App · Java · JavaFX · CS 3100

Recipe management application built in a 4-person team. Includes recipe storage, ingredient scaling, collection management, and a cook mode with step-by-step instructions to lead you through.

**What I built:**
- **Live timer** — designed and implemented the timer as a first-class instruction field: editable in the recipe editor, persisted in the data model, and can be started, and paused, and displayed as a live countdown during cook mode
- **Cook mode UI** — built the step-through interface with active timer integration, letting users step through recipe instructions one at a time
- **Recipe editor** — full-stack implementation of the edit flow including GUI form state and persistence layer

**Stack:** `Java` `JavaFX` `MVVM` `Gradle`

[View Repository →](https://github.com/NaftaliCaplan/cook-your-books)

---

## Skills

| Languages | Tools & Frameworks | Concepts |
|---|---|---|
| TypeScript | VS Code Extension API | Data modelling |
| Java | JavaFX | Test-driven development |
| JavaScript | Node.js · Jest | YAML parsing |
| | Git | MVVM architecture |
| | Gradle | Open source contribution |

---

## Currently

- Finishing the TC annotation project
- Building out this portfolio
- Begining Design of Colorblind Cook Assistant

---

## Contact

📧 caplan.naf@northeastern.edu &nbsp;·&nbsp; [GitHub](https://github.com/NaftaliCaplan)
