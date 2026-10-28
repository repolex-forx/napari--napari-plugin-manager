# Repolex Knowledge Graph of napari/napari-plugin-manager

RDF knowledge graph data for [napari/napari-plugin-manager](https://github.com/napari/napari-plugin-manager), parsed by [repolex](https://repolex.ai).

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
rlex download napari/napari-plugin-manager
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 97739a8ca99f27bf866af76b584c3b9bdde58278
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 97739a8ca99f27bf866af76b584c3b9bdde58278
│           └── chunk-001.nq.gz
├── blob
│   ├── 059f7fc572a16d9cc1a70244daa3eb12489e5160.nq.gz
│   ├── 0c7bc9f3ada30f9d0b8150dcd835d99c37376c77.nq.gz
│   ├── 0d7b8e03528af9583a7a6d22d83ca73fa9bf9ace.nq.gz
│   ├── 1034e3e5caf9abaf48fa7d21168c2209361c5968.nq.gz
│   ├── 11d7edca8e837c02a6a4ecbb95919c0af4d2e52d.nq.gz
│   ├── 1590f0f2330d56ce4ffe6aba9b7856b5d0140dff.nq.gz
│   ├── 17fc9cd133ed5a717bbb157c44eb43ada676e493.nq.gz
│   ├── 1e19583f54d2a63cec8b1a929815ada5d3d3301a.nq.gz
│   ├── 20f2fb040095364ded201296c42e661b862d0d91.nq.gz
│   ├── 22ff3ebe05ca02e334cceabda1a9eaff80df83f3.nq.gz
│   ├── 23a670ff5ae53bfc50b8fcc8b36dedad33eea26b.nq.gz
│   ├── 29dff400f469ce9d8ef46dc826e338acda9003b1.nq.gz
│   ├── 2b7ec11228f174fe0496b9127864a672d8e8ad87.nq.gz
│   ├── 31f4f5cc91483ab1a95918bf4e372304fa912655.nq.gz
│   ├── 323642b01e1b7197017c0e17e8263efde1bea125.nq.gz
│   ├── 3480a0ef0f48f16120e1ef6309cd3f016e2ef8aa.nq.gz
│   ├── 3ca850f20acba2bceca0d8967b83b7868a08abbe.nq.gz
│   ├── 451bedaec21ea36474276ced4ad7260227f5b227.nq.gz
│   ├── 50e4e316a9d4bfac377b248fde7938a7d6288fae.nq.gz
│   ├── 51544de258e9b977f1a319e3d26168d4b65a1c79.nq.gz
│   ├── 540560d8666110d3cfe690a0d627dc5f544a80cb.nq.gz
│   ├── 595eac5e0cb595b5de15b17e9ccf94c637db30fc.nq.gz
│   ├── 5ba1f69d71faf7ac27dd6cd619562df0ddb7fbbd.nq.gz
│   ├── 7120e739eb1f492efe39d637176bb8ef362398ee.nq.gz
│   ├── 736ee20849af2f250d266a209ae48d3b9728e510.nq.gz
│   ├── 82b3e40a7a9afe5922b61b96e2a4364d4a83effd.nq.gz
│   ├── 88b21dd18b189a55be207090c9013f0ee07fe0a1.nq.gz
│   ├── 9ad5cbcf5210ece69b9b4d05aa0cc0b8d1edd2b0.nq.gz
│   ├── a419410235268b77b94d6476a28de8bba9f5f14a.nq.gz
│   ├── a4f876258a53354ee4ddb639d14fcc8d5ce20b80.nq.gz
│   ├── b0f91a557f2611cd1ee473bdc0421832d8814f68.nq.gz
│   ├── bdebd723746a2deb879018bc1aa6b54a265e7fe8.nq.gz
│   ├── bf24eda1cbe8d729bf79dd1d265ab28855999c78.nq.gz
│   ├── ca44497dfc342e94e559eee2c2eeb5922a7328c5.nq.gz
│   ├── cba076639b46e511ca8a1783fcf6e887bb46ad64.nq.gz
│   ├── d41e02aa049b66d70e03cc57dbc3751ee0a1be87.nq.gz
│   ├── dcac5079e5a384a8332e8ead68d28c8e9b77d14d.nq.gz
│   ├── df0b85f4016d460b907f0044d27f918766e51a41.nq.gz
│   ├── e2ddcc2cd9b74104e0e146ac7785d63453647394.nq.gz
│   ├── e5cc606e885ac776af88662f601d37c8d37b7d4d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e824627844879ea9d76046b77837884db942ee77.nq.gz
│   ├── f7956638f9b89bc3eecbf2fbd273b43e21f556c2.nq.gz
│   └── fc2b8ced1076270592f8f5f14b84614991b0d158.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 97739a8ca99f27bf866af76b584c3b9bdde58278.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[napari/napari-plugin-manager](https://github.com/napari/napari-plugin-manager)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
