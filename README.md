# Repolex Knowledge Graph of asimov-platform/asimov.sh

RDF knowledge graph data for [asimov-platform/asimov.sh](https://github.com/asimov-platform/asimov.sh), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download asimov-platform/asimov.sh
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 96acd5623340362715df766bbdac6a0093bc77a2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 96acd5623340362715df766bbdac6a0093bc77a2.nq.gz
│   └── repolex
│       └── 96acd5623340362715df766bbdac6a0093bc77a2
│           └── chunk-001.nq.gz
├── blob
│   ├── 007039771d9241c16d074d69aa1d837a81871a3a.nq.gz
│   ├── 023296cf63690f6ceb2e7420619d8e707adf3097.nq.gz
│   ├── 025fefc41fc0e8781fcb53bea8c4255c88e79f42.nq.gz
│   ├── 0a567a19a8034614f964883b8995849a0d69dea5.nq.gz
│   ├── 150bb5883bf562ef7f2358caa0bb179acd0b640c.nq.gz
│   ├── 1eb349fbbe059edaebcaabda670968510da95926.nq.gz
│   ├── 25e3bc63e55bdd38c2013069bbbb8f4b95a3d323.nq.gz
│   ├── 28b65ef1493bbb26edc7bfd55f5f86e7f2d3fbf9.nq.gz
│   ├── 2aba6198bdbad807eb6aac18badaa4c14b52a16a.nq.gz
│   ├── 2bd5a0a98a36cc08ada88b804d3be047e6aa5b8a.nq.gz
│   ├── 3377ef2c51233f1f5aa9c90fde5d94add35fbc28.nq.gz
│   ├── 374c78ed484e00b923052a48a291935ba7dc8a29.nq.gz
│   ├── 3867a0feb3616f828a6477be653751da85dca637.nq.gz
│   ├── 3e425a0ccc266a4ff6668cc40314d2dbc2a3e68c.nq.gz
│   ├── 4078e7476a2eaf5705d327b5c9d459c234c01652.nq.gz
│   ├── 40d2bb5155ebb38e363a8f2aca291a6377a5ef15.nq.gz
│   ├── 40e8db2019ce8fd7dfe058d006ae058dcfc6970b.nq.gz
│   ├── 478bd0ae0343087a86a0715c0f7818e9b508fe95.nq.gz
│   ├── 49079c23f7878ea7afa1d9c096e25d3d401ef808.nq.gz
│   ├── 4d8441e328c825cac264181c72346a6a2bdf7d88.nq.gz
│   ├── 55bf3cc224641727ec19f56b33df506254aa5323.nq.gz
│   ├── 5699437905d5e1d99f367f262b99380e5ed7f28d.nq.gz
│   ├── 5b58bdf9eef3fd7ec9051954d0de171a351bb775.nq.gz
│   ├── 60acdd3f2155f5dd93b14f4b3bbedd1057ca76ef.nq.gz
│   ├── 62b251a05589fe6276e5202b1522bbf118aaf9ee.nq.gz
│   ├── 63dc9d6b077c49db1b157ed9c677a200b84e72e3.nq.gz
│   ├── 64f59fc4e1436c659572d8175b5db0de9fa08c0d.nq.gz
│   ├── 6562bcbb8ab96e6800a4dcb41bed4ebb413bcbe2.nq.gz
│   ├── 6894a1006952f97494eb1e7b16474e7966aad759.nq.gz
│   ├── 731c7fe9c091037a5a19a1540f296e95598695cc.nq.gz
│   ├── 74d890346f9f84c19d063ee58cae8b55079703d6.nq.gz
│   ├── 7ebb855b9477e546f0acea1f628fc5d65ce916d5.nq.gz
│   ├── 80ef420edfc115b4f4922ec33080b5816721e6e7.nq.gz
│   ├── 814763b0063d7baa75bd20450a7dda7ab770fa8d.nq.gz
│   ├── 88a659fb81dbab57b5a3d1848ef90ef3c24e78e2.nq.gz
│   ├── 8c8dc9f068f4561adaf071c14dbdc07e7e327ef4.nq.gz
│   ├── 8fbe19146dbe0e82c125626e686e2d99795ddc9a.nq.gz
│   ├── 914acdf2ef0c2600cc21ce9ad4f5fe5a246ed04e.nq.gz
│   ├── 94eea1993bd050c12ae69536b2bc13756b7d918e.nq.gz
│   ├── 9c69355db411dec75627f0ca4a842cc4be671c09.nq.gz
│   ├── 9feb65497f4af7ece0193d7b3fa93d125fa92b2c.nq.gz
│   ├── a2b56c9cca1612e88888336c45bf68099632c978.nq.gz
│   ├── a547bf36d8d11a4f89c59c144f24795749086dd1.nq.gz
│   ├── a8e9d836663db586e2af89b061e545eb074005b9.nq.gz
│   ├── ab7bb71cd2270df7e042150160c73b14455c8917.nq.gz
│   ├── b30fb4b71b1569000665b2702b3b6038b58cc3bf.nq.gz
│   ├── b32a718edae00dd8a1fc2bf8f4c64d3423344ae9.nq.gz
│   ├── b8aad061b2b1d678fdf5ce458fcd14151dbeadad.nq.gz
│   ├── c1534060df9067967af3dd6468551162d9e40a31.nq.gz
│   ├── c6e11400a0bca70d8dfc6b41c595b34d8a462e6a.nq.gz
│   ├── cb41088c6ce36da796adae458494a8794dd36c56.nq.gz
│   ├── cbbd4883d2dbb9d90fcee7ea690f883441827c71.nq.gz
│   ├── d216d349759582f359c9997bd12e4a66a13410f9.nq.gz
│   ├── d586327b801290d36b913a78b482324d5788b0ac.nq.gz
│   ├── dbf7b0b14e168d7ddf358dac545257bfd2b2a1d3.nq.gz
│   ├── e063768b4401a633b40b31a5098a45cbe0aec067.nq.gz
│   ├── e275fd419b3854f9f95b985ff1cb980fa2c25d20.nq.gz
│   ├── e620745b5c28bd3e1ba55dc5229f88caa206b970.nq.gz
│   ├── eda7addcbaabb0f11c9a1531e51d2de5a63e1c54.nq.gz
│   ├── ef07d3224241ae61aad6e07504d2f794d8970652.nq.gz
│   ├── f3da3b30c35b0c1b0d8d19283086daacd0ea389a.nq.gz
│   ├── f981524cf3d6fe7855330ad921fcb93f2cec05b8.nq.gz
│   ├── fbc38887d704cd55259969f2fe2fb6bf7db02f0a.nq.gz
│   └── fc69abb76615770f54660ba75c0f5c49b17cf82f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 96acd5623340362715df766bbdac6a0093bc77a2.nq.gz
├── filetree
│   └── 96acd5623340362715df766bbdac6a0093bc77a2.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 73 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[asimov-platform/asimov.sh](https://github.com/asimov-platform/asimov.sh)

---
*Parsed on 2026-09-27 by [repolex](https://repolex.ai)*
