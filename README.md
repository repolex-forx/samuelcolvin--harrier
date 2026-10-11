# Repolex Knowledge Graph of samuelcolvin/harrier

RDF knowledge graph data for [samuelcolvin/harrier](https://github.com/samuelcolvin/harrier), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/harrier
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dde44eef0fc5aa84e874e49bee25f9cf9ace8269
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dde44eef0fc5aa84e874e49bee25f9cf9ace8269
│           └── chunk-001.nq.gz
├── blob
│   ├── 006d20624012c9a56e8b08d805e5fb3d17de9adc.nq.gz
│   ├── 02034b56d88d7bc73d00bed91f6338a7b0d218aa.nq.gz
│   ├── 06bbc41a8749151e47f1083f3ef73e56d187cb14.nq.gz
│   ├── 0beed915a20dbdb488abac0a111352eaa2c14e12.nq.gz
│   ├── 0c31a23386ce8fe59561801c6219cfcbb6e06140.nq.gz
│   ├── 11605e4aac379a77301e8f6d04a7991a60ade9fe.nq.gz
│   ├── 13e9d86d11e5beb1c5a25dd15b1c8325569e347b.nq.gz
│   ├── 166292fb829e02fbe3df476c2a603b635a603530.nq.gz
│   ├── 182a1a3f734fc1b7d712c68b04c29bad9460d6cd.nq.gz
│   ├── 187ec5aa18e3b05e078eb0b8644f6d42cc584d4c.nq.gz
│   ├── 197983f8ecc4b52462abb1135508353b7c85d5d9.nq.gz
│   ├── 25901b3580cfae5c3e0bca7aa9d51c91f0f2b3c6.nq.gz
│   ├── 2743e5e5ea990b04bd67f9b34e3588376c825b76.nq.gz
│   ├── 2fc1bb4a8a397bd44a5358ed2d6a1b952367a162.nq.gz
│   ├── 36caaab672ad3ad62976bafe2449421db50866e3.nq.gz
│   ├── 373b4cbb5d14cebf3bc5730f91660dcd62bd885b.nq.gz
│   ├── 41182f0d05f1bdc6d87d994466b32a70f1cae2f8.nq.gz
│   ├── 43783fc3d670548abb1ba3e278f90e820245db50.nq.gz
│   ├── 470c144d71acdcb530aba989160eb328b25f843a.nq.gz
│   ├── 4ae4a9af79242ce38c161287d23bfec0c6691f1a.nq.gz
│   ├── 51ec87bff590723d61232cfdc3701e2f565cecbe.nq.gz
│   ├── 54249703dbb88f6179dc9197f7f4acaacd39da9d.nq.gz
│   ├── 5a88294e15e39bb8655a6034d55a365309121798.nq.gz
│   ├── 5aecc916b9eebf3b9bc86cc1a97199fe4a037743.nq.gz
│   ├── 5ce0d3c9721dbe6d794cdbe6f6edb71aa0f08a69.nq.gz
│   ├── 5ec904df4dd69101badf105c265272edd0ba1d86.nq.gz
│   ├── 6211ed85f8a2fc3f749070cf86ddc7344e32fb94.nq.gz
│   ├── 64b26dbff7c159b5b7150e75002b107bfad3f720.nq.gz
│   ├── 65b4d5a6ec52d11daa0ad2f736a94249cdd4e04c.nq.gz
│   ├── 6aa8b82bdce8c78a555dd852247c776cca30c96f.nq.gz
│   ├── 6e1b3cb3edd54ba800ef5fddd54f6813f863f672.nq.gz
│   ├── 70c3ca9ed0cff0455d5592c2b9051aac092c8dba.nq.gz
│   ├── 7750a193694a1ebf2596ec6373e48986d7fa2c05.nq.gz
│   ├── 7b07b81abf6cbe1b8cfd91c84d2735646a81c608.nq.gz
│   ├── 7e98fbc29c4465c4784c6fed4f90eae7f407dcb9.nq.gz
│   ├── 811e0aecf55fb1ed9bfa6f36eb65975f53a27fe0.nq.gz
│   ├── 90a105e3a6a02146d6b3718ce61bf35469d7e6b7.nq.gz
│   ├── 9b8be11fc2916b3ab6602c90f441bfe87f580fe3.nq.gz
│   ├── a7f3f8c9ccf280f352158f0065bfc55568066cd3.nq.gz
│   ├── a8092e5cef8fde7f33eeeb8fca290fb4f8161fb3.nq.gz
│   ├── b35c6947dfa79297f9e74de44286c54469399f74.nq.gz
│   ├── b7bb02dae335df09807ab800900df41621cc83ee.nq.gz
│   ├── b841d134c3d6b295db81e08b9f0d0565a95f7943.nq.gz
│   ├── bd73432dc909b0a6faf2813a511cb48a886396ef.nq.gz
│   ├── cc1923a40b1a5e8c7fbdb8f9f6c6bbe26c35604b.nq.gz
│   ├── d79a99a2de875a8dfc47340c4694d3e295ff3345.nq.gz
│   ├── de5d6ce8a02881ada1f7c651a92bac248a1f5863.nq.gz
│   ├── e0745edd1e193f45f34fba266d88a26f1b5ed1ad.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eca6f89250bb23276c578436030e3cf98f25ec65.nq.gz
│   ├── ecb9938219ce20925ae8c18ba1c00259767ce321.nq.gz
│   ├── f4a6f779bc72a92d5d4b3e5293b99128112cc795.nq.gz
│   ├── f8856868554981d5eefe4374da59e659679b9e9b.nq.gz
│   ├── f9102e87f4b7508d4a5aba7533989af9e5b1921a.nq.gz
│   ├── fd2b9ea9c86f14f5df9b07b7570fc60ec2b185b8.nq.gz
│   └── fdaf72147d7c49717f400144ea6da872c1821199.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dde44eef0fc5aa84e874e49bee25f9cf9ace8269.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[samuelcolvin/harrier](https://github.com/samuelcolvin/harrier)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
