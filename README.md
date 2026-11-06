# GTE — Generative Typography Environment

**GTE** is an integrated ecosystem for generative typography, built on top of OpenType and guided by the calligraphic logic of each script. 

> 📜 Read the full vision in the [GTE Manifesto](./docs/GTE-Manifesto.md).

## Ecosystem Architecture

GTE is not just a tool; it is an ecosystem composed of integrated components:

1. **FFB (Font Feature Builder):** The font construction engine.
   👉 [Read the FFB Documentation](./docs/ffb/README.md)
2. **JustyKhatt:** The typographic analysis and execution engine (DOM layer).
   👉 [Read JustyKhatt Documentation](./justykhatt/README.md)

## Font Naming Convention

All typefaces generated within the GTE ecosystem carry the **`AF-` (Adaptive Font)** prefix (e.g., `AF-Abnoos`). This indicates full compatibility with JustyKhatt for DOM-level typographic orchestration. 

## Documentation Directory

- 📜 [GTE Manifesto](./docs/GTE-Manifesto.md)
- 🏗️ [Architecture Overview](./docs/ARCHITECTURE.md)
- 🛠️ [FFB Documentation (Formerly the main README)](./docs/ffb/README.md)
- 📄 [FFB Research Article (Skeletons, Marks, and Anchors)](./docs/articles/FFB-Article.md)
- 📘 [FFB Specification](./docs/ffb/spec.md)
- 🇮🇷 [FFB User Guide (Persian)](./docs/ffb/user-guide.fa.md)

## License
AGPL-3.0
