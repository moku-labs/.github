# moku

**A micro-kernel for TypeScript apps, and the frameworks built on it.**

The table is written by a workflow every 15 minutes, from `moku-release fleet` of [`@moku-labs/ci`](https://github.com/moku-labs/ci).

<!-- fleet:start -->
| Repo | CI | Release | Tag | npm | Not released | PRs | Old pins |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ai](https://github.com/moku-labs/ai) | [🟢](https://github.com/moku-labs/ai/actions) | [🟢](https://github.com/moku-labs/ai/actions/workflows/publish.yml) | [v0.16.8](https://github.com/moku-labs/ai/releases/tag/v0.16.8) | 0.16.8 | 0 | [0](https://github.com/moku-labs/ai/pulls) | — |
| [ci](https://github.com/moku-labs/ci) | [🟢](https://github.com/moku-labs/ci/actions) | [🟢](https://github.com/moku-labs/ci/actions/workflows/publish.yml) | [v1.5.7](https://github.com/moku-labs/ci/releases/tag/v1.5.7) | 1.5.7 | 0 | [0](https://github.com/moku-labs/ci/pulls) | — |
| [claude](https://github.com/moku-labs/claude) | [🟢](https://github.com/moku-labs/claude/actions) | — | — | — | — | [0](https://github.com/moku-labs/claude/pulls) | — |
| [common](https://github.com/moku-labs/common) | [🟢](https://github.com/moku-labs/common/actions) | [🟢](https://github.com/moku-labs/common/actions/workflows/publish.yml) | [v0.3.10](https://github.com/moku-labs/common/releases/tag/v0.3.10) | 0.3.10 | 0 | [0](https://github.com/moku-labs/common/pulls) | — |
| [core](https://github.com/moku-labs/core) | [🟢](https://github.com/moku-labs/core/actions) | [🟢](https://github.com/moku-labs/core/actions/workflows/publish.yml) | [v1.7.6](https://github.com/moku-labs/core/releases/tag/v1.7.6) | 1.7.6 | 0 | [0](https://github.com/moku-labs/core/pulls) | — |
| [demos](https://github.com/moku-labs/demos) | [🟢](https://github.com/moku-labs/demos/actions) | — | — | — | — | [1 (1 red)](https://github.com/moku-labs/demos/pulls) | — |
| [editor](https://github.com/moku-labs/editor) | [🟢](https://github.com/moku-labs/editor/actions) | [🟢](https://github.com/moku-labs/editor/actions/workflows/publish.yml) | [v0.10.11](https://github.com/moku-labs/editor/releases/tag/v0.10.11) | 0.10.11 | 0 | [1](https://github.com/moku-labs/editor/pulls) | game 0.14.12 |
| [game](https://github.com/moku-labs/game) | [🟢](https://github.com/moku-labs/game/actions) | [🟢](https://github.com/moku-labs/game/actions/workflows/publish.yml) | [v0.15.0](https://github.com/moku-labs/game/releases/tag/v0.15.0) | 0.15.0 | 0 | [0](https://github.com/moku-labs/game/pulls) | — |
| [native](https://github.com/moku-labs/native) | [🟢](https://github.com/moku-labs/native/actions) | [🟢](https://github.com/moku-labs/native/actions/workflows/publish.yml) | [v0.3.9](https://github.com/moku-labs/native/releases/tag/v0.3.9) | 0.3.9 | 0 | [0](https://github.com/moku-labs/native/pulls) | — |
| [room](https://github.com/moku-labs/room) | [🟢](https://github.com/moku-labs/room/actions) | [🟢](https://github.com/moku-labs/room/actions/workflows/publish.yml) | [v0.8.9](https://github.com/moku-labs/room/releases/tag/v0.8.9) | 0.8.9 | 0 | [0](https://github.com/moku-labs/room/pulls) | — |
| [system](https://github.com/moku-labs/system) | [🟢](https://github.com/moku-labs/system/actions) | [🟢](https://github.com/moku-labs/system/actions/workflows/publish.yml) | [v0.3.7](https://github.com/moku-labs/system/releases/tag/v0.3.7) | 0.3.7 | 0 | [0](https://github.com/moku-labs/system/pulls) | — |
| [web](https://github.com/moku-labs/web) | [🟢](https://github.com/moku-labs/web/actions) | [🟢](https://github.com/moku-labs/web/actions/workflows/publish.yml) | [v2.4.10](https://github.com/moku-labs/web/releases/tag/v2.4.10) | 2.4.10 | 0 | [0](https://github.com/moku-labs/web/pulls) | — |
| [worker](https://github.com/moku-labs/worker) | [🟢](https://github.com/moku-labs/worker/actions) | [🟢](https://github.com/moku-labs/worker/actions/workflows/publish.yml) | [v0.20.9](https://github.com/moku-labs/worker/releases/tag/v0.20.9) | 0.20.9 | 0 | [0](https://github.com/moku-labs/worker/pulls) | — |

Nothing waits.

<details>
<summary>Toolchain: 22 shared tools, 10 on more than one version, 20 behind npm</summary>

| Tool | Accepted | npm | Used by | Not on it |
| --- | --- | --- | --- | --- |
| @arethetypeswrong/cli | 0.18.3 | 0.18.5 | 9 | core 0.18.2 |
| @arethetypeswrong/core | 0.18.3 | 0.18.5 | 9 | core 0.18.2 |
| @biomejs/biome | 2.4.16 | 2.5.15 | 11 | core 2.4.2 |
| @cloudflare/workers-types | 4.20260621.1 | 5.20261016.1 | 2 | worker 4.20260617.1 |
| @playwright/test | 1.63.0 | 1.64.1 | 2 | room 1.61.0 |
| @types/bun | 1.4.2 | 1.4.3 | 11 | ci 1.3.14 |
| eslint | 9.39.3 | 10.12.0 | 11 | core 9 |
| globals | 17.4.0 | 17.13.0 | 11 | core 17.3.0 |
| happy-dom | 20.14.5 | 21.0.3 | 2 | web 20.9.0 |
| publint | 0.3.21 | 0.3.25 | 11 | core 0.3.17 |
| @vitest/coverage-istanbul | 4.0.18 | 5.0.5 | 11 | — |
| bun | 1.4.3 | 1.4.3 | 10 | — |
| eslint-config-biome | 2.1.3 | 2.1.3 | 11 | — |
| eslint-plugin-jsdoc | 62.6.0 | 65.3.6 | 11 | — |
| eslint-plugin-sonarjs | 4.0.0 | 4.2.2 | 11 | — |
| eslint-plugin-unicorn | 63.0.0 | 78.0.0 | 11 | — |
| jiti | 2.6.1 | 2.7.0 | 11 | — |
| lefthook | 2.1.1 | 2.2.2 | 10 | — |
| tsdown | 0.22.1 | 0.23.1 | 11 | — |
| typescript | 6.0.3 | 7.0.2 | 11 | — |
| typescript-eslint | 8.58.0 | 8.71.2 | 11 | — |
| vitest | 4.0.18 | 5.0.5 | 11 | — |

</details>

<details>
<summary>Runtime dependencies: 10 behind npm</summary>

| Package | Repo | Version | npm |
| --- | --- | --- | --- |
| @shikijs/rehype | web | 3.22.0 | 4.5.0 |
| better-sqlite3 | ai | 12.11.1 | 13.0.3 |
| feed | web | 5.2.0 | 6.0.0 |
| immer | game | 11.1.18 | 11.1.21 |
| maxrects-packer | game | 2.7.3 | 3.0.0 |
| openai | ai | ^6.45.0 | 7.34.0 |
| p-limit | web | 6.2.0 | 7.3.3 |
| preact | editor | 10.29.8 | 11.0.1 |
| satori | web | 0.19.1 | 0.62.0 |
| shiki | web | 3.22.0 | 4.5.0 |

</details>
<!-- fleet:end -->
