<p align="center"><strong>English</strong> · <a href="README.zh-CN.md">简体中文</a></p>

<p align="center"><img src="assets/hero.svg" alt="TIKAZ Presentation Workflows for Codex" width="100%" /></p>

<h1 align="center">TIKAZ Presentation Workflows for Codex</h1>
<p align="center"><strong>Narrative-first HTML, PPTX, and editorial web decks with page contracts and rendered QA.</strong></p>
<p align="center"><a href="https://github.com/TIKAZI/TIKAZ-Codex-Presentation/actions/workflows/validate.yml"><img src="https://github.com/TIKAZI/TIKAZ-Codex-Presentation/actions/workflows/validate.yml/badge.svg" alt="Validate" /></a> <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-f4c95d.svg" alt="MIT" /></a> <img src="https://img.shields.io/badge/version-0.8.0-F59E0B.svg" alt="0.8.0" /></p>
<p align="center"><a href="https://github.com/TIKAZI/TIKAZ-AI-Skills">← Explore all seven TIKAZ AI Skills for Codex suites</a></p>

<p align="center"><img src="assets/proof-strip.svg" alt="Four verified core advantages" width="100%" /></p>

---

## ✨ One suite, ready to install

This repository is the independently installable **presentation** distribution from [TIKAZ AI Skills for Codex](https://github.com/TIKAZI/TIKAZ-AI-Skills). The monorepo is the canonical development source; this repository is automatically synchronized and optimized for people who need only this workflow.

Designed, integrated, refactored, and continuously maintained by **TIKAZ**; community contributions are welcome. This is an independent project, not an OpenAI-official repository.

This repository is an automatically synchronized distribution of the canonical [TIKAZ-AI-Skills](https://github.com/TIKAZI/TIKAZ-AI-Skills) monorepo. Cross-suite issues and source changes belong in the canonical repository.

## 🧩 What makes it different

- **Choose exactly one output builder for each final deck**
- **Every slide receives a claim, evidence, visual job, and speaker intent**
- **Rendered overflow, media licensing, and final artifact integrity are completion gates**

## 📦 Install

Clone or download this repository, then copy the repository folder into the Skill directory supported by your Codex environment. The root `SKILL.md` is the suite orchestrator; child folders are focused Skills that can also be installed separately.

```bash
git clone https://github.com/TIKAZI/TIKAZ-Codex-Presentation.git
```

## 🧩 Use one Skill independently

Every Skill below has its own promise, installation command, example, execution contract, limits, and bilingual project page:

- [`html-deck-builder`](https://tikazi.github.io/TIKAZ-AI-Skills/skills/html-deck-builder/index.html)
- [`magazine-web-deck`](https://tikazi.github.io/TIKAZ-AI-Skills/skills/magazine-web-deck/index.html)
- [`powerpoint-deck-builder`](https://tikazi.github.io/TIKAZ-AI-Skills/skills/powerpoint-deck-builder/index.html)
- [`presentation`](https://tikazi.github.io/TIKAZ-AI-Skills/skills/presentation/index.html)

## 🚀 Try it

```text
Choose HTML or PPTX for this talk, write page contracts, and render representative pages before completing the deck.
```

```text
Create an editable PowerPoint from this brief and inspect every dense slide for overflow and collisions.
```

```text
Turn this essay into a single-file editorial web deck with restrained motion and offline verification.
```

## 🔄 How the suite works

Read [SKILL.md](SKILL.md) for the owning workflow, [references/routing.md](references/routing.md) for specialist routing, and [references/output-contract.md](references/output-contract.md) for the verified handoff. Optional tools are detected at runtime; local login state or machine-specific software is never promised as universally available.

## 🗂️ Repository structure

```text
./
├─ SKILL.md                 # suite orchestrator
├─ agents/                  # Codex UI metadata
├─ references/              # routing and output contract
├─ <child-skill>/           # independently installable specialists
├─ DISTRIBUTION.yml         # canonical source and sync metadata
└─ scripts/                 # deterministic validation
```

## ⚖️ Canonical source and contributions

Development, source review, and cross-suite architecture live in [TIKAZ-AI-Skills](https://github.com/TIKAZI/TIKAZ-AI-Skills). This distribution synchronizes from `suites/presentation` every week and can also be refreshed manually through GitHub Actions.

Source modes, observed licenses, and concrete TIKAZ contributions are recorded in [SOURCES.yml](SOURCES.yml) and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). TIKAZ-authored files are released under the [MIT License](LICENSE).

## 🌐 Explore the TIKAZ workflow family

[🏠 AI Skills](https://github.com/TIKAZI/TIKAZ-AI-Skills) · [⚡ Context Economy](https://github.com/TIKAZI/TIKAZ-Codex-Context-Economy) · [🎨 Frontend Design](https://github.com/TIKAZI/TIKAZ-Codex-Frontend-Design) · [🎬 Video Intelligence](https://github.com/TIKAZI/TIKAZ-Codex-Video-Intelligence) · [🛠️ Engineering](https://github.com/TIKAZI/TIKAZ-Codex-Engineering) · [🔬 Research](https://github.com/TIKAZI/TIKAZ-Codex-Knowledge-Research) · [📽️ Presentation](https://github.com/TIKAZI/TIKAZ-Codex-Presentation) · [🖼️ Visual Content](https://github.com/TIKAZI/TIKAZ-Codex-Visual-Content)
