# Huzaifa Abdul Rehman

BS Computer Science at FAST NUCES, Karachi. Graduating 2027.

I spend most of my time fixing real bugs in other people's codebases: systems code in C and Go,
frontend and tooling in TypeScript. A lot of what I find is Windows-only, because I develop on
Windows and most contributors do not.

![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)

## Open source

**Merged**

| Change | What it fixed | Language |
| --- | --- | --- |
| [google/pprof#1023](https://github.com/google/pprof/pull/1023) | `pprof -web` and `weblist` silently opened nothing on Windows when the temp path contained a space, because `start` read the path as a window title | Go |
| [google/pprof#1025](https://github.com/google/pprof/pull/1025) | `-tools` and `PPROF_TOOLS` were split at the Windows drive letter, so an absolute path was filed under a tool named `C` and never searched | Go |
| [getsentry/sentry-native#1987](https://github.com/getsentry/sentry-native/pull/1987) | Public interface for supplying a custom HTTP transport client | C |
| [getsentry/sentry-native#1911](https://github.com/getsentry/sentry-native/pull/1911) | Configurable Windows minidump flags, with crash-context propagation and tests | C |
| [microsoft/vscode-cpptools#14592](https://github.com/microsoft/vscode-cpptools/pull/14592) | Portable `ps` arguments so the remote process picker works off Linux | TypeScript |
| [elastic/eui#9841](https://github.com/elastic/eui/pull/9841) | Migrated `EuiFilterSelectItem` to a function component with behaviour preserved | React |
| [oppia/oppia#26888](https://github.com/oppia/oppia/pull/26888) | Migrated the community library acceptance suite from Puppeteer to Playwright | TypeScript |

**In review**

| Change | What it fixes | Language |
| --- | --- | --- |
| [facebook/hermes#2160](https://github.com/facebook/hermes/pull/2160) | Single-node AST replacement in hermes-parser was O(n²); made it O(1) | JavaScript |
| [rust-lang/compiler-builtins#1239](https://github.com/rust-lang/compiler-builtins/pull/1239) | Preserves the NaN sign bit through soft-float addition | Rust |
| [NVIDIA/warp#1879](https://github.com/NVIDIA/warp/pull/1879) | FEM shape optimization was not moving vertices | Python |
| [openai/openai-agents-js#1776](https://github.com/openai/openai-agents-js/pull/1776) | Spawns pnpm without the Windows `.cmd` shim | TypeScript |
| [anthropics/claude-code-action#1755](https://github.com/anthropics/claude-code-action/pull/1755) | Runs git against the checkout instead of the ambient working directory | TypeScript |

## Projects

- **[Driver Drowsiness Detection](https://github.com/HuzaifaAbdulRehman/driver-drowsiness-detection)** — MobileNetV2 eye-state classifier with MediaPipe landmarks, 97.3% on the MRL Eye dataset. Python, TensorFlow, OpenCV.
- **[Electrolux EMS](https://github.com/HuzaifaAbdulRehman/Electrolux-EMS)** — Electricity distribution management: billing, usage, service requests, database-backed auth. Next.js, TypeScript, MySQL, Drizzle.
- **[FAST Academic Hub](https://github.com/HuzaifaAbdulRehman/fast-academic-hub)** — Offline-first attendance planner that models planned absences. React, Vite, PWA.
- **[Dijkstra + ML Routing](https://github.com/HuzaifaAbdulRehman/dijkstra-ml-routing-optimization)** — Route planning combining a custom Dijkstra implementation with XGBoost over OpenStreetMap networks. Python, NetworkX, OSMnx.

## Contact

[LinkedIn](https://www.linkedin.com/in/huzaifa-abdul-rehman-701732289/) · Open to internships and junior engineering roles.
