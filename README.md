# Naftali Caplan

Computer Science student at Northeastern University. I build full-stack applications and developer tooling, with a focus on clean data models and backend architecture.

---

## Projects

### ADR Manager — TC Annotation Layer
**VS Code Extension · TypeScript · Open Source**

Contributor to a VS Code extension for managing Architectural Decision Records (MADRs). Owned the Technical Credit annotation data layer for the CS 4530 Summer School intensive.

**My contribution — Track B: TC Data Model & Storage**
- Designed the `TcAnnotation` TypeScript interface and all enum types (`TcCategory`, `TcSignal`, `TcStatus`) as the shared schema across the full team
- Built `parseTcFromYaml()` and `serializeTcToYaml()` — the read/write layer that automatically extracts and persists TC annotation fields from YAML frontmatter on every parse and save
- Implemented mode-aware serialisation: pro-only fields are gated behind professional editor mode
- Built `validateTcAnnotation()` — validates all 6 TC field types with per-field error messages, used by the UI layer
- Added schema versioning (`tc-schema-version`) and real-world compatibility testing against JabRef's ADR corpus
- 78 tests passing across 4 test suites

**Stack:** TypeScript · js-yaml · ANTLR4 · Jest · VS Code Extension API

[View Repository](https://github.com/OwenSweetman/SummerSchool_MADR)

---

### CookYourBooks
**Full-Stack Desktop App · Java · JavaFX · CS 3100**

Recipe management application built in a team of 4. Full-stack contribution across UI and backend logic.

**My contribution**
- Recipe editing — end-to-end implementation of the edit flow, including form validation and persistence
- Step-through mode — built the feature allowing users to walk through recipe instructions one step at a time
- Timer function — integrated a per-step countdown timer into the step-through flow

**Stack:** Java · JavaFX · MVVM Architecture

---

## Skills

**Languages:** TypeScript · Java · JavaScript

**Tools & Frameworks:** VS Code Extension API · JavaFX · Node.js · Jest · Git

**Concepts:** Data modelling · YAML parsing · Test-driven development · MVVM · Open source contribution

---

## Contact

caplan.naf@northeastern.edu · [GitHub](https://github.com/NaftaliCaplan)
