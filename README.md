# Awesome NiceGUI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources, tools, talks, and real-world projects built with [NiceGUI](https://nicegui.io) — the Python framework that lets any browser be the frontend of your Python code.

> [!NOTE]
> **This list is agent-curated.** It was seeded by an AI agent (Claude Code, Opus 4.7) on 2026-05-25 as a deliberately rough first pass — a [_brick thrown to attract jade_](https://en.wiktionary.org/wiki/%E6%8B%8B%E7%A3%9A%E5%BC%95%E7%8E%89). Every link below was fetched and confirmed to genuinely reference the NiceGUI **framework** (not the plain-English phrase "nice GUI") at curation time, but the selection is **not yet human-reviewed**, is far from exhaustive, and may contain mistakes or go stale. Corrections, additions, and ruthless pruning via PR are very welcome — see [Contributing](#contributing).

## Contents

- [Official](#official)
- [Articles & Tutorials](#articles--tutorials)
- [Talks & Podcasts](#talks--podcasts)
- [Tools & Extensions](#tools--extensions)
- [Projects & Apps](#projects--apps)
- [Robotics & Hardware](#robotics--hardware)
- [Research & Academia](#research--academia)
- [Accessibility & Niche](#accessibility--niche)
- [Related / Alternatives](#related--alternatives)
- [Help Wanted](#help-wanted)
- [Contributing](#contributing)

## Official

- [NiceGUI](https://github.com/zauberzeug/nicegui) — The framework itself, by [Zauberzeug](https://zauberzeug.com) (⭐ 15.8k).
- [Documentation & live examples](https://nicegui.io/documentation) — Official docs, runnable in the browser.
- [PyPI package](https://pypi.org/project/nicegui/) — `pip install nicegui`.
- [Discord](https://discord.gg/TEpFeAaF4f) — Community chat.
- [Reddit r/nicegui](https://www.reddit.com/r/nicegui/) — Community subreddit.

## Articles & Tutorials

- [NiceGUI: Awesome Python Dynamic Websites For The Web Dev Impaired!](https://www.feoh.org/posts/nicegui-awesome-dynamic-websites-for-people-who-write-ugly-html.html) — A frontend-averse Python dev's enthusiastic intro.
- [Building Integrated Web Applications with FastAPI and NiceGUI](https://jaehyeon.me/blog/2025-11-19-fastapi-nicegui-template/) — A from-scratch RBAC + CRUD template.
- [How to Deploy NiceGUI Apps with Docker on Sliplane](https://dev.to/code42cate/how-to-deploy-nicegui-apps-with-docker-on-sliplane-38c8) — Practical containerized-deploy walkthrough.
- [NiceGUIを使ったPython GUIアプリの作成と配布](https://qiita.com/masushin/items/018224b52e89f463776c) 🇯🇵 — Packaging & distributing a NiceGUI app to an executable (rye + PyInstaller gotchas).

## Talks & Podcasts

- [Inventing Python's Nicest UI Framework](https://www.youtube.com/watch?v=D5DnLgeObq4) — Falko Schindler at PyCon Ireland 2023; the design ethos.
- [Building an A/B Testing Framework with NiceGUI](https://www.youtube.com/watch?v=i4T-Vb34W1c) — A real internal-tooling use case, PyData Berlin / PyCon DE 2025.
- [Talk Python #525: NiceGUI Goes 3.0](https://talkpython.fm/episodes/show/525/nicegui-goes-3.0) — Maintainers Rodja Trappe & Falko Schindler on the 3.0 release.
- [Python Bytes #329](https://pythonbytes.fm/episodes/show/329/creating-very-old-python-code) — Early coverage; "good for micro web apps, dashboards, robotics, smart home".

## Tools & Extensions

- [ngws](https://github.com/BlankAdventure/ngws) — A NiceGUI ↔ WebSerial bridge: a remote server reaches the browser client's own USB serial ports.

## Projects & Apps

- [Beaverhabits](https://github.com/daya0576/beaverhabits) — Self-hosted habit tracker (⭐ 1.8k).
- [WireGUI](https://github.com/bartei/wiregui) — A Firezone-inspired WireGuard VPN server with a web UI (⭐ 50+).
- [supremebot](https://github.com/saccofrancesco/supremebot) — Cross-platform Supreme streetwear drop sniper (NiceGUI + Playwright).
- [kurup](https://github.com/davistdaniel/kurup) — Database-free local markdown note-taking app with live preview.

## Robotics & Hardware

- [RoSys](https://github.com/zauberzeug/rosys) — An all-Python robotics framework ("like ROS, but based on NiceGUI"); the engine under Zauberzeug's field robots.
- [Field Friend dev kit](https://github.com/zauberzeug/feldfreund_devkit_ros) — An AI autonomous field-weeding farm robot, operated entirely from a browser.

## Research & Academia

- [NiceWebRL](https://github.com/KempnerInstitute/nicewebrl) — Browser-based human-subject reinforcement-learning experiments in pure Python (Harvard Kempner Institute; ⭐ 80+). Paper: [arXiv:2508.15693](https://arxiv.org/abs/2508.15693).
- [CARIS](https://arxiv.org/abs/2604.12258) — A privacy-preserving agentic framework for clinical research, with a NiceGUI frontend (Seoul National Univ. Hospital + Harvard/MGH).
- [OTTER](https://arxiv.org/abs/2509.05405) — Open mulTiwavelength Transient Event Repository, an astronomy data portal ([live](https://otter.idies.jhu.edu/); Johns Hopkins).
- [Cross-environment Cooperation Enables Zero-shot Multi-agent Coordination](https://arxiv.org/abs/2504.12714) — Uses NiceGUI for the human-vs-AI Overcooked study interface.

## Accessibility & Niche

- [StudentDataGUI](https://github.com/mrhunsaker/StudentDataGUI) — A Teacher-of-the-Visually-Impaired's tool for tracking Braille & Abacus skill progress.

## Related / Alternatives

For honest context — NiceGUI is most often discovered by people comparing Python web-UI options:

- [Streamlit](https://streamlit.io) — Data-app focused; the most common framework people migrate _from_.
- [Reflex](https://reflex.dev) — Compiles Python to a React frontend.
- [Gradio](https://www.gradio.app) — ML-demo focused.
- [FastHTML](https://fastht.ml) — HTML-over-the-wire in Python.
- [Flet](https://flet.dev) — Flutter-based Python UI.

## Help Wanted

This is a seed. Known gaps a human (or future PR) should close:

- **An unofficial NiceGUI VS Code extension** reportedly exists (mentioned in an HN comment — "search 'nicegui' in the marketplace"), but a verified Marketplace link is needed before listing it.
- More **non-English resources** — there's a thriving Japanese (Qiita/Zenn) community and a Chinese one (Bilibili, [nicegui.cn](https://nicegui.cn)) under-represented here.
- **Component libraries / plugins** that extend NiceGUI.
- **Production case studies** and company adoptions.
- A pass to drop anything stale, low-quality, or no longer maintained.

## Contributing

PRs welcome — especially corrections. Please:

1. Keep entries to one line: `- [Name](url) — short, factual description.`
2. **Verify the project actually uses the NiceGUI framework** (not just the words "nice GUI") before adding it.
3. Prefer canonical links (the project's repo or site) over blog reposts.
4. Group entries under the right section; keep them roughly ordered by relevance/popularity.

---

<sub>Seeded by [Claude Code](https://claude.com/claude-code) (Opus 4.7) and pending human review. Inclusion is not endorsement.</sub>
