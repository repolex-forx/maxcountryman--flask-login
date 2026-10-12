# Repolex Knowledge Graph of maxcountryman/flask-login

RDF knowledge graph data for [maxcountryman/flask-login](https://github.com/maxcountryman/flask-login), parsed by [repolex](https://repolex.ai).

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
rlex download maxcountryman/flask-login
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c8bba84b9ba6768e878317fc46c54bd13fa1ac07
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c8bba84b9ba6768e878317fc46c54bd13fa1ac07
│           └── chunk-001.nq.gz
├── blob
│   ├── 04463812d8c9852f8b999e62b7fdbd6fd345c302.nq.gz
│   ├── 0786894ad8f6709b1192a8603fd983c11f1c6959.nq.gz
│   ├── 0b3a71bbee1a6ad2b3f049f30f8f97004d769367.nq.gz
│   ├── 0ee0a2def2dec80c9660494ff1a2c919e1dbb05f.nq.gz
│   ├── 286f85b2c3eab4ce137f4889924ce489be5661c9.nq.gz
│   ├── 3514dce1debdb460aa1ddea321dcbde2bee95483.nq.gz
│   ├── 35b530eafd4251a2a845cbbb2e738c357714989e.nq.gz
│   ├── 3ef203c860d474caeedb1160d522a6fe43772786.nq.gz
│   ├── 4643666d3c8cdaa388406d2eecefca96713086b4.nq.gz
│   ├── 5196b2053d0c2e2a6a23f1d7edb16dc907786818.nq.gz
│   ├── 5c61a62ea9b6b73f5e42930419e645b1e9b20013.nq.gz
│   ├── 5cd37bd2c2800c13266924d5df031c0c326d149f.nq.gz
│   ├── 69025910f4682f84775f74615b79f994676f5c40.nq.gz
│   ├── 69a87af5db708a9beff8f093f7c10d07204c8126.nq.gz
│   ├── 6a0f3d7cc2f3fa13efd604a067e9d94cca996bbb.nq.gz
│   ├── 73fe7583ad0e79f25c961c101332225cc0a45c78.nq.gz
│   ├── 782b177e5c212536c2ecc49482f0e3550d4338f1.nq.gz
│   ├── 7cce06bf7ca133f1d4d1be12e5a9083c64fc153f.nq.gz
│   ├── 882c390092c9494865a1ba59ee87b415672bdeef.nq.gz
│   ├── 8abe153847235529e47766d52cbbdec4d1bf0846.nq.gz
│   ├── 8bcb4d7ca69d4a1a8a87679be45ce900f9b7d255.nq.gz
│   ├── 90fa34bedce247df8a71223a7d6a0960d037ac0f.nq.gz
│   ├── a3540fce7c6c08a04deb7d3f31662b1802fdb8be.nq.gz
│   ├── b3700df14e857f87fbbe07c9b5e4752ccbac3e4d.nq.gz
│   ├── be2a8bf6ab7541aca05035cbaa03497b7007b6d8.nq.gz
│   ├── c262399a749d46a507f086631132ae89a4be81a0.nq.gz
│   ├── c46459056b99aa1d1fabebb8c156bb23fb2d77f4.nq.gz
│   ├── c6737ce5efc30f7647d6219f6472e63dac036ef8.nq.gz
│   ├── c854000e463615a20638c98638d510917c944462.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d76f16752ce6e4f2e2f17a0e1df469871223112f.nq.gz
│   ├── d8b17cf9e0391d9c86439bf2e16d86871705c6e1.nq.gz
│   ├── dc1312ab09ca6fb0267dee6b28a38e69c253631a.nq.gz
│   ├── dcce13d8e3118739144f42adfe3188d419567d43.nq.gz
│   ├── dd237cb21f7d6d0ffc9ca575f4737d5941b5e435.nq.gz
│   ├── dd84ea7824f11be1eeda22377549cbc1aec7f980.nq.gz
│   ├── dda81758b7afbf62226c07bca9393098e813157e.nq.gz
│   ├── e9769c2557ae9be0ec076538ded2a593099a2e48.nq.gz
│   ├── ea0dca01ad13c6e54912ae330887b93595be98aa.nq.gz
│   ├── ec066d51fd8e8a6db9fff5b8153b2c94893c1781.nq.gz
│   └── fac683e7c3d50a920ee31bc2b7f68c034a88f295.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c8bba84b9ba6768e878317fc46c54bd13fa1ac07.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 49 files
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

[maxcountryman/flask-login](https://github.com/maxcountryman/flask-login)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
