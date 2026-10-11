# Repolex Knowledge Graph of python-trio/trio-owfs

RDF knowledge graph data for [python-trio/trio-owfs](https://github.com/python-trio/trio-owfs), parsed by [repolex](https://repolex.ai).

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
rlex download python-trio/trio-owfs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 694a7d89265d78af6080978f01b86ec1fd32c9f9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 694a7d89265d78af6080978f01b86ec1fd32c9f9
│           └── chunk-001.nq.gz
├── blob
│   ├── 00253c41265e614fd2e5c76e159848c99479d98e.nq.gz
│   ├── 05d0525a3edfb0d2891d781f536269b874795597.nq.gz
│   ├── 063a9079413e0ce860b3c83eadb38ff2c27fafc8.nq.gz
│   ├── 1a53a0678b1bc6e2253a5e13dba73b4e30caf860.nq.gz
│   ├── 25c242d092c14d4c87754e9f12dc6305de212d7d.nq.gz
│   ├── 25c3ba4743af91d90f136fbd0385703bc7da7666.nq.gz
│   ├── 291bfeaa3b207e4173c50080f22cfb473363ee5a.nq.gz
│   ├── 293680e37a49373f549d159e917117b68c2924f7.nq.gz
│   ├── 31c3c9c64f1aae3314c1d3266f259da6ec444ed7.nq.gz
│   ├── 394378beddba7d4aaad4e7983ff47ca4d2c42b07.nq.gz
│   ├── 441920b747b34b0ea3d06e69a9fcb2cb873dd0c9.nq.gz
│   ├── 48ad84adbdea8b8fc55c3ba211a5f3ef2599e35c.nq.gz
│   ├── 48e120abf1f60723565edd0528b74292c5c1ccce.nq.gz
│   ├── 494b82094c4066cb5663c7411764103302659893.nq.gz
│   ├── 4edd4b18b3f9a2893c3d0a37e5e747a5f09cebe7.nq.gz
│   ├── 51f3442917839f8e0f0cccb52b3c10968ad0779e.nq.gz
│   ├── 521e9b96a7aea4a2e6bbdefdf26c31eb1bce06be.nq.gz
│   ├── 528c8b8d054ada32d3fe5925b6ff7dfced4d1fbf.nq.gz
│   ├── 5abe3231d618633532c6516fdaaa8f70e87dff35.nq.gz
│   ├── 6087eb63ba482d712d0a5ace016810e666901d65.nq.gz
│   ├── 60e773753140fd0d6a13112728bbcfbb86b42992.nq.gz
│   ├── 66f2b301eb4893bf236d0516dc100b8c61be07ba.nq.gz
│   ├── 6ce6071a941f44a5ca5209639c282d37cbbb4b24.nq.gz
│   ├── 74edb9084c2f3ea73e2911b465eb2760383d08fb.nq.gz
│   ├── 79e9f684b8cfc5288f02bdbbc9f80f084aaf1a28.nq.gz
│   ├── 7ab64d611109973a47c826b50b6b92d032063f8c.nq.gz
│   ├── 8320dbe9fd53b4db10905c086a6cecda75fee85b.nq.gz
│   ├── 89c26257ec3587ae7e8f2f22439d7d1d23dd473a.nq.gz
│   ├── 9006d88c87b9880832f3da31f6363b64a9d0d776.nq.gz
│   ├── 9913b9e166c2872c965f3a3260385dc414121cf9.nq.gz
│   ├── 9b6866a5bd950ca599a792615a16f2ffeaf1080d.nq.gz
│   ├── a00e4f377116c131ed5a3f9af68d62f6df103392.nq.gz
│   ├── a2082905f1c6d1be42c4287a332215a5443b6389.nq.gz
│   ├── a3cc397b433f373a1cd48e1d42f2756730635ab0.nq.gz
│   ├── aee18be4cf8303c4aeb5b4fd8c3e9867914ffbe4.nq.gz
│   ├── b8bb97185926d7daed314609753173945ed4ff1a.nq.gz
│   ├── b9ec784d61393949c3a867a1e1e6508482eaf0ee.nq.gz
│   ├── c29fcd1b967e87fe2b0eb9167bc41edbf5fcee66.nq.gz
│   ├── c92c059ac18aaaeb6e06a453fc40fdeb865b205f.nq.gz
│   ├── ca4bb52c17161b2d88309f64eb759250b04b72c6.nq.gz
│   ├── ceb27fb356881f8da1bf1003d1548acc0ec6cc17.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── da8a923444bbe735db33b094f0a5421129f8688e.nq.gz
│   ├── dd3b0cef7cc03b39a98d2d8d4a0739d810b4afad.nq.gz
│   ├── de0a8a73370dcc1c407147f90819bb0aba86dc8d.nq.gz
│   ├── e66e949f0e91dbae4b2b5d7ef73335f6a6932599.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── f531f3c6b25f183ae2ac4374138779fb6eae3ec9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 694a7d89265d78af6080978f01b86ec1fd32c9f9.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 55 files
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

[python-trio/trio-owfs](https://github.com/python-trio/trio-owfs)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
