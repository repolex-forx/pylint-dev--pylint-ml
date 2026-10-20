# Repolex Knowledge Graph of pylint-dev/pylint-ml

RDF knowledge graph data for [pylint-dev/pylint-ml](https://github.com/pylint-dev/pylint-ml), parsed by [repolex](https://repolex.ai).

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
rlex download pylint-dev/pylint-ml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d46da888309464f7f4b7396a00667e5c2cd6d1ef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d46da888309464f7f4b7396a00667e5c2cd6d1ef
│           └── chunk-001.nq.gz
├── blob
│   ├── 0bd3592f6a36c3653c191191f709e4fd6b6eb8a3.nq.gz
│   ├── 13b382f3548ba416e63abd93aaf2e52b5e06e2bc.nq.gz
│   ├── 1bb871b30ba0e19ed631a7c327e33b7e582d1c31.nq.gz
│   ├── 1bec24b5de82424bcc2e9aabdc4f5e5194ab106e.nq.gz
│   ├── 20ed03421b7a57bf3e922d8bf7e7221d482a1285.nq.gz
│   ├── 232d9bfe78e230d6e81a8fe5309e006f4b5f8ff1.nq.gz
│   ├── 2d542036650bc9ab5bd7b10def7f96facabdc685.nq.gz
│   ├── 2dc53ca34ca78153451a0c01f67518ec2e81ac36.nq.gz
│   ├── 3427f1bdf84f9ece47b225986b4abdaee3ba3899.nq.gz
│   ├── 37875f6108ac5bb1d2c81fdbd3a50f6bd02bf8d1.nq.gz
│   ├── 3efee908c00e3eb4be4f54fecb66f61efd85915a.nq.gz
│   ├── 3f3e480744dc6bb609bf13bbbb65a526bff91686.nq.gz
│   ├── 40b8d52cb22a1505369508dc46df3d06062bc4c7.nq.gz
│   ├── 43cf26a6bee1111ef104f90ff4442279aac3cf56.nq.gz
│   ├── 48197ddeedb824cca5993e6c5d4124825bbc3907.nq.gz
│   ├── 4a1a7adf14234f832affcdb65f6a5baf505c838f.nq.gz
│   ├── 4dbf5d4479cc0527617dc1b40adc2c36f39d724c.nq.gz
│   ├── 558df807f1c2bf809eecea885429be39c2b10ab8.nq.gz
│   ├── 5a51c1ea2a948c5739064c9bf588ed13473c6e9c.nq.gz
│   ├── 6191d2e0d451b1522022602626e5a8f9e6fcc02b.nq.gz
│   ├── 62d538a2af6289767f52828fec5e6edaa5d3ef3c.nq.gz
│   ├── 6c3c64a3c5522672406ae29e24483ab81feee6b2.nq.gz
│   ├── 6c8120522c695eebfa983bea01ca93bc043ab1f1.nq.gz
│   ├── 6cfe8ca0b2de6467e8c0a792dbe19798ff2008ee.nq.gz
│   ├── 721a75e940fee34c0d8918b8a3f7a92a53eb6d59.nq.gz
│   ├── 73fdbd1ef762fbc03d3c8aca83e26749819284c3.nq.gz
│   ├── 75d6b4a342b24d673a54e91d97aca4d4abb25beb.nq.gz
│   ├── 7c20be8c008fac81184bff475576b7cfc81c8925.nq.gz
│   ├── 85f22b7a11af2c1825a3f77a8bfa4cd0c89d0e1f.nq.gz
│   ├── 8e5e3e2a6b983f24f1f7bf7fdb537005f44c5d57.nq.gz
│   ├── 955656f4018a7446af36587836a894affebb8cd2.nq.gz
│   ├── 961296568b76746c348d7a4be8fbf8cefe0d13d1.nq.gz
│   ├── 99d2b0c25b81d32fb82d3a98586d56822d67eae8.nq.gz
│   ├── 9b9464e5bc0586b50c102d89e9dc3910f93ff8a9.nq.gz
│   ├── a09f2c497a721e6a8f71887e696b608ad729380c.nq.gz
│   ├── a0aaf2d3fec3115479b45ae3ac6883a9af5e9320.nq.gz
│   ├── a519ca8a3e01afb8bf3aa04632ac415f2d427eb1.nq.gz
│   ├── a6bce472858b0669b6afa3249f726078935a6b2e.nq.gz
│   ├── aafe587c848249a2e1bc0c6c176015c67f53fbc2.nq.gz
│   ├── b1d5b42bf0d043e61ec03a8f201ce3b0e7071d11.nq.gz
│   ├── b738f76d31d2f1e7cafaa2574fd5e81ecfd055d1.nq.gz
│   ├── c1eded614e1bc3380a4f93dafcacbedbcbbea2e4.nq.gz
│   ├── c76d928139b7d737802b61fca1528b8826cd0f78.nq.gz
│   ├── c9a334f7834a1a457a53d31639048888e0855257.nq.gz
│   ├── c9ef15256b17e163c22ba2fc7f1a0539cde4bf03.nq.gz
│   ├── d19fbfe8c2817dcb74126e75802d3ae611f7d972.nq.gz
│   ├── d7b121ff5c59765e48556bc31059505924f74471.nq.gz
│   ├── dafac6898c4aae9794ae02c78d359849e4c88aa1.nq.gz
│   ├── e045e834735f3e70fc42d27d5fb899d20b9c5d12.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec1ae81c472549a0061f5eaa9e58973c3bb02dcf.nq.gz
│   ├── f01b811a5ba300dcce273e235d8b396a325f277a.nq.gz
│   ├── f0fb020e66746ba1b84a6ce3c25f6656a9c4df52.nq.gz
│   ├── f2ed64b6799218b0373579497e3563521e47c5c9.nq.gz
│   └── fc8febf7b8f588e887908fe9282f53a2f817447e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d46da888309464f7f4b7396a00667e5c2cd6d1ef.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[pylint-dev/pylint-ml](https://github.com/pylint-dev/pylint-ml)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
