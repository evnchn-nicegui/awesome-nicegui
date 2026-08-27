# Awesome NiceGUI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources, tools, talks, and real-world projects built with [NiceGUI](https://nicegui.io) — the Python framework that lets any browser be the frontend of your Python code.

> <sub>Seeded by an automated pass; every link was verified to reference the NiceGUI framework at curation time. Far from exhaustive — corrections, additions, and pruning via PR welcome (see [Contributing](#contributing)).</sub>

## Contents

- [Official](#official)
- [Articles & Tutorials](#articles--tutorials)
- [Talks & Podcasts](#talks--podcasts)
- [Tools & Extensions](#tools--extensions)
- [Component Libraries & Extensions](#component-libraries--extensions)
- [Starters & Templates](#starters--templates)
- [Projects & Apps](#projects--apps)
- [Robotics & Hardware](#robotics--hardware)
- [Research & Academia](#research--academia)
- [Accessibility & Niche](#accessibility--niche)
- [Related / Alternatives](#related--alternatives)
- [Help Wanted](#help-wanted)

## Official

- [NiceGUI](https://github.com/zauberzeug/nicegui) - The framework itself, by [Zauberzeug](https://zauberzeug.com) (⭐ 15.9k).
- [Documentation & live examples](https://nicegui.io/documentation) - Official docs, runnable in the browser.
- [PyPI package](https://pypi.org/project/nicegui/) - `pip install nicegui`.
- [Discord](https://discord.gg/TEpFeAaF4f) - Community chat.
- [Reddit r/nicegui](https://www.reddit.com/r/nicegui/) - Community subreddit.

## Articles & Tutorials

- [NiceGUI: Awesome Python Dynamic Websites For The Web Dev Impaired!](https://www.feoh.org/posts/nicegui-awesome-dynamic-websites-for-people-who-write-ugly-html.html) - A frontend-averse Python dev's enthusiastic intro.
- [Building Integrated Web Applications with FastAPI and NiceGUI](https://jaehyeon.me/blog/2025-11-19-fastapi-nicegui-template/) - A from-scratch RBAC + CRUD template.
- [How to Deploy NiceGUI Apps with Docker on Sliplane](https://dev.to/code42cate/how-to-deploy-nicegui-apps-with-docker-on-sliplane-38c8) - Practical containerized-deploy walkthrough.
- [NiceGUIを使ったPython GUIアプリの作成と配布](https://qiita.com/masushin/items/018224b52e89f463776c) - 🇯🇵 Packaging & distributing a NiceGUI app to an executable (rye + PyInstaller gotchas).
- [NiceGUI 中文版本文档 (Chinese reference docs)](https://github.com/syejing/nicegui-reference-cn) - 🇨🇳 A community Chinese-language translation of the NiceGUI documentation (⭐ 120+).
- [nicegui.cn 中文社区](https://nicegui.cn/) - 🇨🇳 A community Chinese-language docs and learning portal for the NiceGUI framework.
- [NiceGUI 中文入门教程 (Chinese beginner's guide)](https://github.com/python-and-novella/chinese_guide_of_nicegui_for_beginner) - 🇨🇳 A from-zero Chinese tutorial covering setup, controls, layout, and styling (⭐ 40+).
- [Pythonだけで本格Web UIを書く時代 ─ NiceGUI 3.0のススメ](https://note.com/shibats/n/n0bf209c44140) - 🇯🇵 An overview of NiceGUI 3.0's Vue-3 rewrite, routing, and theming ("Python で書く Vue.js").
- [Streamlit から脱却したい：NiceGUI と Reflex を実装比較](https://zenn.dev/kenseinosaka/articles/33451331179c89) - 🇯🇵 Implements the same app in NiceGUI vs Reflex as Streamlit alternatives.
- [NiceGUI と OpenCV を組み合わせたい](https://qiita.com/Kazuhito/items/76d39895b5f96a3f7314) - 🇯🇵 Real-time OpenCV webcam streaming into a NiceGUI interactive image.

## Talks & Podcasts

- [Inventing Python's Nicest UI Framework](https://www.youtube.com/watch?v=D5DnLgeObq4) - Falko Schindler at PyCon Ireland 2023; the design ethos.
- [Building an A/B Testing Framework with NiceGUI](https://www.youtube.com/watch?v=i4T-Vb34W1c) - A real internal-tooling use case, PyData Berlin / PyCon DE 2025.
- [Talk Python #525: NiceGUI Goes 3.0](https://talkpython.fm/episodes/show/525/nicegui-goes-3.0) - Maintainers Rodja Trappe & Falko Schindler on the 3.0 release.
- [Python Bytes #329](https://pythonbytes.fm/episodes/show/329/creating-very-old-python-code) - Early coverage; "good for micro web apps, dashboards, robotics, smart home".

## Tools & Extensions

- [NiceGUI for VS Code](https://marketplace.visualstudio.com/items?itemName=DaelonSuzuka.nicegui) - Editor language support for the NiceGUI framework, by Daelon Suzuka ([source](https://github.com/DaelonSuzuka/nicegui-vscode)).
- [ngws](https://github.com/BlankAdventure/ngws) - A NiceGUI ↔ WebSerial bridge: a remote server reaches the browser client's own USB serial ports.
- [NiceVibes](https://github.com/Alyxion/nice-vibes) - Guidance and rules for teaching AI agents to build NiceGUI applications well.
- [OpenRun](https://github.com/openrundev/openrun) - Declaratively deploy NiceGUI apps on a single node or Kubernetes; handles container builds, zero-downtime rolling deploys, OIDC/SAML access control with RBAC, and scale-to-zero.
- [EasyOIDC](https://github.com/jpmanson/EasyOIDC) - OpenID Connect (OIDC) authentication with a dedicated NiceGUI integration (`pip install easyoidc[nicegui]`).
- [nicegui-command-palette](https://github.com/DaelonSuzuka/nicegui-command-palette) - A VS Code/Sublime-style command palette you can embed in NiceGUI apps, by Daelon Suzuka.

## Component Libraries & Extensions

- [ex4nicegui](https://github.com/CrystalWindSnake/ex4nicegui) - Extension library adding reactive / data-responsive components on top of NiceGUI (⭐ 200+).
- [nicegui-highcharts](https://github.com/zauberzeug/nicegui-highcharts) - Official Highcharts integration element, by Zauberzeug.
- [nicegui-toolkit](https://github.com/CrystalWindSnake/nicegui-toolkit) - Helper toolkit for NiceGUI development.
- [nicegui-tabulator](https://github.com/CrystalWindSnake/nicegui-tabulator) - Interactive tables for NiceGUI via the Tabulator library.
- [nicegui_widgets](https://github.com/WolfgangFahl/nicegui_widgets) - A collection of reusable NiceGUI widgets.
- [nicegui-react](https://github.com/puntorigen/nicegui-react) - Embed React components inside NiceGUI apps.
- [nicegui-codemirror](https://github.com/volltin/nicegui-codemirror) - A CodeMirror-based code editor element for NiceGUI.
- [nicegui-pdf](https://github.com/peerdavid/nicegui-pdf) - A pip-installable PDF viewer component (pdf.js) with two-way page and selected-text binding.
- [nodegraph-editor-nicegui](https://github.com/123swk123/nodegraph-editor-nicegui) - A Vue-flow-based node-graph editor component for NiceGUI (⭐ 25).

## Starters & Templates

- [nicegui-component-based](https://github.com/frycodelab/nicegui-component-based) - A modular, component-structured NiceGUI project template (⭐ 170+).
- [nicegui-fastapi-template](https://github.com/jaehyeon-kim/nicegui-fastapi-template) - Full-stack NiceGUI + FastAPI starter template.
- [nicegui-tailwind-layout](https://github.com/EasyDevv/nicegui-tailwind-layout) - Responsive layout templates for NiceGUI apps.
- [nicegui-template](https://github.com/zauberzeug/nicegui-template) - The official Copier scaffold for a basic NiceGUI project, by Zauberzeug.

## Projects & Apps

- [Beaverhabits](https://github.com/daya0576/beaverhabits) - Self-hosted habit tracker (⭐ 1.8k).
- [WireGUI](https://github.com/bartei/wiregui) - A Firezone-inspired WireGuard VPN server with a web UI (⭐ 50+).
- [supremebot](https://github.com/saccofrancesco/supremebot) - Cross-platform Supreme streetwear drop sniper (NiceGUI + Playwright).
- [kurup](https://github.com/davistdaniel/kurup) - Database-free local markdown note-taking app with live preview.
- [fastapi-forge](https://github.com/mslaursen/fastapi-forge) - A visual FastAPI project generator whose project designer is built with NiceGUI (⭐ 160+).
- [ReNovel-AI](https://github.com/BiranSama/ReNovel-AI) - 🇨🇳 A local AI novel-editing workbench (RAG long-term memory, card-based streaming editor) with a NiceGUI UI (⭐ 140+).
- [desto](https://github.com/kalfasyan/desto) - A web dashboard and CLI to manage Python and shell scripts running in tmux sessions (⭐ 100+).
- [WLEDVideoSync](https://github.com/zak-45/WLEDVideoSync) - Casts video, images, and camera feeds to WLED/E1.31/ArtNet/DDP 2D LED matrices via a NiceGUI interface (⭐ 60+).
- [Aignostics Launchpad](https://github.com/aignostics/python-sdk) - A computational-pathology company's desktop app (`nicegui[native]`) for its platform, shipped alongside its Python SDK.
- [DrawMode](https://modebit.ai) - A collaborative AI diagramming workbench for web and desktop, built with NiceGUI and open-source JS libraries (closed-source; [desktop builds](https://github.com/ModeBit-AI/drawmode-releases)).

## Robotics & Hardware

- [RoSys](https://github.com/zauberzeug/rosys) - An all-Python robotics framework ("like ROS, but based on NiceGUI"); the engine under Zauberzeug's field robots.
- [Field Friend dev kit](https://github.com/zauberzeug/feldfreund_devkit_ros) - An AI autonomous field-weeding farm robot, operated entirely from a browser.

## Research & Academia

- [NiceWebRL](https://github.com/KempnerInstitute/nicewebrl) - Browser-based human-subject reinforcement-learning experiments in pure Python (Harvard Kempner Institute; ⭐ 80+). Paper: [arXiv:2508.15693](https://arxiv.org/abs/2508.15693).
- [CARIS](https://arxiv.org/abs/2604.12258) - A privacy-preserving agentic framework for clinical research, with a NiceGUI frontend (Seoul National Univ. Hospital + Harvard/MGH).
- [OTTER](https://arxiv.org/abs/2509.05405) - Open mulTiwavelength Transient Event Repository, an astronomy data portal ([live](https://otter.idies.jhu.edu/); Johns Hopkins).
- [Cross-environment Cooperation Enables Zero-shot Multi-agent Coordination](https://arxiv.org/abs/2504.12714) - Uses NiceGUI for the human-vs-AI Overcooked study interface.

## Accessibility & Niche

- [StudentDataGUI](https://github.com/mrhunsaker/StudentDataGUI) - A Teacher-of-the-Visually-Impaired's tool for tracking Braille & Abacus skill progress.

## Related / Alternatives

For honest context — NiceGUI is most often discovered by people comparing Python web-UI options:

- [Streamlit](https://streamlit.io) - Data-app focused; the most common framework people migrate _from_.
- [Reflex](https://reflex.dev) - Compiles Python to a React frontend.
- [Gradio](https://www.gradio.app) - ML-demo focused.
- [FastHTML](https://fastht.ml) - HTML-over-the-wire in Python.
- [Flet](https://flet.dev) - Flutter-based Python UI.

## Help Wanted

This is a seed. Known gaps a human (or future PR) should close: more non-English video coverage (the Chinese Bilibili tutorial communities are active but hard to verify automatically, so they are still under-represented here), more production case studies and company adoptions, and a recurring pass to drop anything stale, low-quality, or no longer maintained.

## Contributing

Contributions welcome — especially corrections. Please read the [contribution guidelines](contributing.md) first.

---

<sub>Seeded by [Claude Code](https://claude.com/claude-code) (Opus 4.7) using the [**chengyu-skills**](https://github.com/evnchn-agentic/chengyu-skills) methodology — Chinese idioms as agent skills: 抛磚引玉 (_throw a brick to attract jade_) to seed this list, and 亡羊補牢 (_repair the fence after losing a sheep_) to re-fetch and verify every single link. Inclusion is not endorsement.</sub>
