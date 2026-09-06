# Huzaifa Abdul Rehman

**Software Engineer · Backend & Reliable Systems · Applied AI/ML**

*Independent researcher in quantum-inspired optimization for recommender systems*

BS Computer Science student at FAST NUCES in Karachi, Pakistan. Graduating in 2027.

I build backend and AI systems and contribute fixes to production open-source projects.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

## Open source

**Merged**

| Change | What it fixed | Language |
| --- | --- | --- |
| <a href="https://github.com/NVIDIA/warp/pull/1879"><img src="https://github.com/NVIDIA.png?size=64" width="32" height="32" align="center" alt="NVIDIA"> NVIDIA/warp#1879</a> | Fixed FEM shape optimization using a copied scalar buffer instead of a zero-copy view; added a regression test proving that vertices move | Python |
| <a href="https://github.com/huggingface/candle/pull/3931"><img src="https://github.com/huggingface.png?size=64" width="32" height="32" align="center" alt="Hugging Face"> Hugging Face/candle#3931</a> | Ported four audio decoders to Symphonia 0.6, restoring the feature-gated Whisper and audio example builds | Rust |
| <a href="https://github.com/rust-lang/compiler-builtins/pull/1304"><img src="https://github.com/rust-lang.png?size=64" width="32" height="32" align="center" alt="Rust"> Rust/compiler-builtins#1304</a> | Removed the deleted `abi_unadjusted` feature gate that broke `compiler-builtins` on current nightly | Rust |
| <a href="https://github.com/google/pprof/pull/1023"><img src="https://github.com/google.png?size=64" width="32" height="32" align="center" alt="Google"> Google/pprof#1023</a> | `pprof -web` and `weblist` silently opened nothing on Windows when the temp path contained a space, because `start` read the path as a window title | Go |
| <a href="https://github.com/google/pprof/pull/1025"><img src="https://github.com/google.png?size=64" width="32" height="32" align="center" alt="Google"> Google/pprof#1025</a> | `-tools` and `PPROF_TOOLS` were split at the Windows drive letter, so an absolute path was filed under a tool named `C` and never searched | Go |
| <a href="https://github.com/getsentry/sentry-native/pull/1987"><img src="https://github.com/getsentry.png?size=64" width="32" height="32" align="center" alt="Sentry"> Sentry/sentry-native#1987</a> | Public interface for supplying a custom HTTP transport client | C |
| <a href="https://github.com/getsentry/sentry-native/pull/1911"><img src="https://github.com/getsentry.png?size=64" width="32" height="32" align="center" alt="Sentry"> Sentry/sentry-native#1911</a> | Configurable Windows minidump flags, with crash-context propagation and tests | C |
| <a href="https://github.com/microsoft/vscode-cpptools/pull/14592"><img src="https://github.com/microsoft.png?size=64" width="32" height="32" align="center" alt="Microsoft"> Microsoft/vscode-cpptools#14592</a> | Portable `ps` arguments so the remote process picker works off Linux | TypeScript |
| <a href="https://github.com/elastic/eui/pull/9841"><img src="https://github.com/elastic.png?size=64" width="32" height="32" align="center" alt="Elastic"> Elastic/eui#9841</a> | Migrated `EuiFilterSelectItem` to a function component with behaviour preserved | React |
| <a href="https://github.com/oppia/oppia/pull/26888"><img src="https://github.com/oppia.png?size=64" width="32" height="32" align="center" alt="Oppia"> Oppia/oppia#26888</a> | Migrated the community library acceptance suite from Puppeteer to Playwright | TypeScript |

**In review**

| Change | What it fixes | Language |
| --- | --- | --- |
| <a href="https://github.com/facebook/hermes/pull/2160"><img src="https://github.com/facebook.png?size=64" width="32" height="32" align="center" alt="Meta"> Meta/hermes#2160</a> | Single-node AST replacement in hermes-parser was O(n²); made it O(1) | JavaScript |
| <a href="https://github.com/rust-lang/compiler-builtins/pull/1239"><img src="https://github.com/rust-lang.png?size=64" width="32" height="32" align="center" alt="Rust"> Rust/compiler-builtins#1239</a> | Preserves the NaN sign bit through soft-float addition | Rust |
| <a href="https://github.com/openai/openai-agents-js/pull/1776"><img src="https://github.com/openai.png?size=64" width="32" height="32" align="center" alt="OpenAI"> OpenAI/openai-agents-js#1776</a> | Spawns pnpm without the Windows `.cmd` shim | TypeScript |
| <a href="https://github.com/anthropics/claude-code-action/pull/1755"><img src="https://github.com/anthropics.png?size=64" width="32" height="32" align="center" alt="Anthropic"> Anthropic/claude-code-action#1755</a> | Runs git against the checkout instead of the ambient working directory | TypeScript |

## Projects

- **[Driver Drowsiness Detection](https://github.com/HuzaifaAbdulRehman/driver-drowsiness-detection)**. MobileNetV2 eye-state classifier with MediaPipe landmarks, 97.3% on the MRL Eye dataset. Python, TensorFlow, OpenCV.
- **[Electrolux EMS](https://github.com/HuzaifaAbdulRehman/Electrolux-EMS)**. Electricity distribution management: billing, usage, service requests, database-backed auth. Next.js, TypeScript, MySQL, Drizzle.
- **[FAST Academic Hub](https://github.com/HuzaifaAbdulRehman/fast-academic-hub)**. Offline-first attendance planner that models planned absences. React, Vite, PWA.
- **[Dijkstra + ML Routing](https://github.com/HuzaifaAbdulRehman/dijkstra-ml-routing-optimization)**. Route planning combining a custom Dijkstra implementation with XGBoost over OpenStreetMap networks. Python, NetworkX, OSMnx.

## Independent research

- **[Feasible Rerank](https://github.com/HuzaifaAbdulRehman/feasible-rerank)**. Tested QUBO recommendation reranking across eight benchmarks, found that standard penalty-encoded cardinality can silently defeat annealers, and built two constraint-aware alternatives.
- **[Budget Tune](https://github.com/HuzaifaAbdulRehman/budget-tune)**. Compared BOCS and FMQA-based QUBO search with strong classical hyperparameter optimization at equal measured CPU-seconds on a 5,052-cell benchmark. The quantum-inspired methods did not beat TPE.
- **[Green Rerank](https://github.com/HuzaifaAbdulRehman/green-rerank)**. Measured training and serving costs by pipeline stage. Fairness reranking consumed 82-98% of per-request serving cost, while classical apportionment matched the QUBO's exposure parity at a fraction of the cost.

## Contact

[LinkedIn](https://www.linkedin.com/in/huzaifa-abdul-rehman-701732289/)
