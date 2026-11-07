# Repolex Knowledge Graph of ansible-collections/netapp.um_info

RDF knowledge graph data for [ansible-collections/netapp.um_info](https://github.com/ansible-collections/netapp.um_info), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/netapp.um_info
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e9dc232958dc7ffbc03e1f29a99bd088ea2ec5f5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e9dc232958dc7ffbc03e1f29a99bd088ea2ec5f5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0790f109af6c05a4918095bbd2b69961cc1979fe.nq.gz
│   ├── 0972cd2e8e58d51f20c6b0d23d8f89154c7ac076.nq.gz
│   ├── 099213226a425f4e076aafcc1f9273ca7a43a187.nq.gz
│   ├── 0d0699cc9cde0a31ddcd0d983a2054bc46e99286.nq.gz
│   ├── 10a34cfdf3c0454d033e757cc6baf7cdba2e1196.nq.gz
│   ├── 126b4b9cdd5ac61b12127e37f44166f4f3982956.nq.gz
│   ├── 163a599349c48df40921bb7f2c517f76f6b66dd7.nq.gz
│   ├── 1d3ef3f86003ee9848c07add37b5ad4476be6fc2.nq.gz
│   ├── 2722e9ef6fb13ed97411c8171cce4e1c24a6607e.nq.gz
│   ├── 27e81ec2eae43d079cbd4abeaa7cb49e33898310.nq.gz
│   ├── 2eafd508f6e9b4f63ed90da01c03d273be8b7d53.nq.gz
│   ├── 3005fe0cb40f97d169ae6df5432d8b29b4db21fd.nq.gz
│   ├── 315d71a13ac11b7e0753da3145332074a289e519.nq.gz
│   ├── 39d5818c914fe780ff78d63923d55ce327b33aad.nq.gz
│   ├── 4c8a267fb6ee10dcd35ce63f4ac6ab4d89f8eb39.nq.gz
│   ├── 546ebfe7a23b08ef2004165106807568e999a9ce.nq.gz
│   ├── 60baa7a48ce26c80e09fccb7064924a35093ba7c.nq.gz
│   ├── 663bd1f6a2ae02f29df59fb4963c17934034f731.nq.gz
│   ├── 684e9aac9e8fb47e880fe41446ad55e2a8b28672.nq.gz
│   ├── 6b4b660a0627a7e4d86ac70d8e522d86796d52f0.nq.gz
│   ├── 71c8753559471e5071a9449891a3fc81f63ac987.nq.gz
│   ├── 73a20cf8c240972154f2e3f34bbd7079373da0d3.nq.gz
│   ├── 75f9b4e465b3dded12716e417912e78c5501a881.nq.gz
│   ├── 7e82f90c91095fb684df3e9e9088de47d34f8b57.nq.gz
│   ├── 824f55f1e8ff6204034e9454c0e34e93ce8aae5e.nq.gz
│   ├── 836a4b1b2451794fbc44aba2c463fd90e85fea15.nq.gz
│   ├── 9294078a2c55a708068e32644e45487d02562da4.nq.gz
│   ├── 94a9ed024d3859793618152ea559a168bbcbb5e2.nq.gz
│   ├── 9a885ffc026725d3d5f00dc506ed124b3cc1b87d.nq.gz
│   ├── 9d2479484fbc4b6a6a5fe5cebb7ebdb620f425c3.nq.gz
│   ├── a39ec8cc2aeaa84bc731ca1a3cc0c2b65b79af12.nq.gz
│   ├── b754473a9959db13bde4c9a0077880918087784d.nq.gz
│   ├── c2ee0282f466025bea27657aab0b50378a2bc820.nq.gz
│   ├── c394d663ee594a0d7a2a00dd01b6df68dfe5d2c5.nq.gz
│   ├── c3c7f122423c214e5df5850a4afc73861aaaa39a.nq.gz
│   ├── c4939adb84bb818c5b4140deca556c0b924e73a6.nq.gz
│   ├── c5d56b307f221fb1ba2cbab293967ba9b43799ff.nq.gz
│   ├── d67e87aa9864c99f684641f01f55a16bd3b499be.nq.gz
│   ├── dd7cef452d6a38d11c12dea9f3be60d8c620dc04.nq.gz
│   ├── e5769d1f1ba3c5d4dab8ab7fd81f4640bc752803.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6fbe3828ab97a91b19273b9709080633da4fc32.nq.gz
│   ├── f3b95800e0627821465e347b05f27e5b8d3936bc.nq.gz
│   └── f5d538d11142ed99257fd2c03e1987ef1933f4f9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e9dc232958dc7ffbc03e1f29a99bd088ea2ec5f5.nq.gz
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

[ansible-collections/netapp.um_info](https://github.com/ansible-collections/netapp.um_info)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
