# Repolex Knowledge Graph of actix/actix-net

RDF knowledge graph data for [actix/actix-net](https://github.com/actix/actix-net), parsed by [repolex](https://repolex.ai).

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
rlex download actix/actix-net
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ebf8d7fa3481d02503812fb1c4061ae987060e30
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ebf8d7fa3481d02503812fb1c4061ae987060e30.nq.gz
│   └── repolex
│       └── ebf8d7fa3481d02503812fb1c4061ae987060e30
│           └── chunk-001.nq.gz
├── blob
│   ├── 0f80296aefc55b2e3f2eab32707ce1fb3fb07a1f.nq.gz
│   ├── 159aacea2eefc4eeffd865bee3df1064e5c18d6e.nq.gz
│   ├── 24d20b15dd8ccd10991d52edfc34342d69b58d9a.nq.gz
│   ├── 28196fee0c730a6ebbbc32e430c34224f5f3e87a.nq.gz
│   ├── 2bc3992c8736e152e2361d3388d4f5a229e2a12f.nq.gz
│   ├── 330aacaec7bac5be0c5bb865b5ef161ed237579f.nq.gz
│   ├── 3813d85ec37a6b815e041dd4a482acf29134bba8.nq.gz
│   ├── 3c6961a0f7f3a1763163125d1fded8a8e20df6b8.nq.gz
│   ├── 3c92ee54cbe9197ee050e578029d753ffbf8e688.nq.gz
│   ├── 4240d062ce2d590608bcf008e5603810e7b0b210.nq.gz
│   ├── 42d0755ddf0e07e8607326a14bd73702f5286f5c.nq.gz
│   ├── 437dfacaf60217f878d5093ede68abe82ce9a403.nq.gz
│   ├── 539ce4977b8f9752f62295c6824f1b0f7242a1af.nq.gz
│   ├── 55f6c8c2199c8b93ef2d0f936ae9a817d6740a7b.nq.gz
│   ├── 56d3fd95ac6f7e7c10f6692361af03b5af508180.nq.gz
│   ├── 599b28c0d6fcb92753fad53eb97ed6d4c40bdad4.nq.gz
│   ├── 5b08f4415ef8659f6628fd8a50dfd8d2f27d8ef1.nq.gz
│   ├── 5ee0892d4b569fa207a4781d982d2541eaa84a77.nq.gz
│   ├── 62e3aac7190a6eeade53364527b5d67bcc05eaac.nq.gz
│   ├── 63cb01141cc574f677604b4e3cedcbd92701f099.nq.gz
│   ├── 69cd6bd687a53ff2893c47a5b105fe1e08a06060.nq.gz
│   ├── 6bef7c05a09855e105816e003122b0e2424b5033.nq.gz
│   ├── 6cdf2d16c78a774af64136f8eb409c4cf041cef5.nq.gz
│   ├── 6ee82a8c1afdb3e3ce7748b4b8f1ae0b249be70c.nq.gz
│   ├── 6fba8f92a8f8a0188e2f73d998e89a1543d0c5dc.nq.gz
│   ├── 759d717eadcdaae38c5c7e81f48f686d96e9f580.nq.gz
│   ├── 7674cdf538c2433c19e61d80323c2138d17fdb5b.nq.gz
│   ├── 767e9fde62a6c46e78d82fc066e1e42aed7fe9b4.nq.gz
│   ├── 7b9e2cd9ce27aa35740c5ca3f04e1c7c9be05d9b.nq.gz
│   ├── 855c6aac5d29f5fb8c7a5148a3eeeeb90a18b692.nq.gz
│   ├── 8b8890b5564ce6887ac88fc36da413bec83e10a9.nq.gz
│   ├── 8d159ba23152cbadd69f079be4a5528e630e19fb.nq.gz
│   ├── 906ee615cd5452a6ab19020a7ca4e872185d694d.nq.gz
│   ├── 9161775c65d829922f2aae5bc8257d720c7194bb.nq.gz
│   ├── 98398c2493cb5d6f5d3ac633d150ea96eb39c68f.nq.gz
│   ├── aac387c64450db4ccec3c0ccbe354fa382e0a8c0.nq.gz
│   ├── ae4881e7548bd60142f94f58a79e2eb842ee1729.nq.gz
│   ├── b94589276b1f660652caf9b364cff2edb47fbef8.nq.gz
│   ├── c226310b94a073191a1044a747fe00d2d100c603.nq.gz
│   ├── c23c39f12e2a526885948fcc9dda97f0b5a53f4d.nq.gz
│   ├── c316a7405c20c0f83721a988517400be200c78cb.nq.gz
│   ├── d7523bf0f59ef430a6dec1f8b5670c9184c36a25.nq.gz
│   ├── e244f3e460714476f798c9def3760f875adf9058.nq.gz
│   ├── e44a1d2d9c315736768273d5fa9ff5c2a3e638de.nq.gz
│   ├── e6129d29b8d95c6b78ee987d7b16919bd767b9af.nq.gz
│   ├── e6a251a798c16b7eb3e607120dd2fd886f28ec69.nq.gz
│   ├── e81ca642948e02a14d1e5b68b7cf9bb0bc62aae9.nq.gz
│   ├── ec3fd0b44f36d444cccc1e228ed41bd5ade84697.nq.gz
│   ├── efc6b3d527681eb536ccbfb168f14af9ee0fa4dd.nq.gz
│   ├── f31b6d76e064bc5e7d1c89c8ce7408a66429b454.nq.gz
│   ├── f60cc6c7166cd71da06d1f2867bdf1566a3e5ecc.nq.gz
│   └── f8de562770a59ded6112ba4c1c15e42f24daaac9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── ebf8d7fa3481d02503812fb1c4061ae987060e30.nq.gz
├── filetree
│   └── ebf8d7fa3481d02503812fb1c4061ae987060e30.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 62 files
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

[actix/actix-net](https://github.com/actix/actix-net)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
