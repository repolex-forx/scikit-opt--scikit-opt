# Repolex Knowledge Graph of scikit-opt/scikit-opt

RDF knowledge graph data for [scikit-opt/scikit-opt](https://github.com/scikit-opt/scikit-opt), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-opt/scikit-opt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dbbb41ad5ce671f90dc4d6b97c7ecdffa187715f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dbbb41ad5ce671f90dc4d6b97c7ecdffa187715f
│           └── chunk-001.nq.gz
├── blob
│   ├── 011bb8b302e79849a4b92a01b1cfbd12e018c03a.nq.gz
│   ├── 0288fd71284ddcd943e4c544decd5e2f97a7af2b.nq.gz
│   ├── 0467701eab4abb81d2884acc19885193a83d30a5.nq.gz
│   ├── 0d927dcb4f70ce0efbfd4a7e54f9f0703d7e2e56.nq.gz
│   ├── 0e4979406998f89116ec274e3ac669f9bac14703.nq.gz
│   ├── 0fdca29680e9d360af53388ea6a8255ce499a678.nq.gz
│   ├── 110d4542187f99327266e861cff23f440ce587bb.nq.gz
│   ├── 14ae8d7058a8e84ddee3776faf7e0d102118753c.nq.gz
│   ├── 1fce04bd13b084df63a583b1c20fa978a88a694f.nq.gz
│   ├── 21d3ccf683dafe0c96326ea657522230c09be968.nq.gz
│   ├── 21f913728e1622f01853cca898247d4fc8a38b6e.nq.gz
│   ├── 2876140a631abc9c5f3eae4986417064e0f9ae9b.nq.gz
│   ├── 2a5326ee31dc3ccc8b1d79fc7a12d5f4c803e15d.nq.gz
│   ├── 2f9cde9adae4960c0ba081c54e5a3725b43e6a51.nq.gz
│   ├── 3566ac83b44df561c21f4770d1da68db18ab898d.nq.gz
│   ├── 39d14ffe8ec9ed908108fff020dbd1c5319eb493.nq.gz
│   ├── 40393664bbf9063a55fe24be7a88ffe3d27fe6b8.nq.gz
│   ├── 40e8014419542666994d105b71252d8d5a906f61.nq.gz
│   ├── 46b3768f7e64c474bc5073b05ebddf1c0ec87b8b.nq.gz
│   ├── 4aca0acbb2d64ffcdd2d5fa866f52e46eaa5c1a9.nq.gz
│   ├── 4f3facd490a3cff4fb6183e053a78a4becaa8c63.nq.gz
│   ├── 50868c729fb98ecb3b5c5466fa75a9528654ff14.nq.gz
│   ├── 50dfd75f93b20692c03a0460bd4ec8629c67efd5.nq.gz
│   ├── 54feb548ec59577e33142cc5467643f5f87baf67.nq.gz
│   ├── 67114de48ae58db1bbfaf9a7ecda67c207a2d843.nq.gz
│   ├── 70f2b195f2512ccc929457f192c832fae8c57eb9.nq.gz
│   ├── 7175c07ee8f2fa20f7d5059aa9de08ac3639daf9.nq.gz
│   ├── 72d4f56dcc5a4b01d0d59ef6c9c3bd852d25e62f.nq.gz
│   ├── 748ed35befc4808c7b19f7ab0bc15352ee02ef86.nq.gz
│   ├── 75207456c1afd1d04c62a34e8064d1c81850f844.nq.gz
│   ├── 798afc4b3bf77bc32dfa802f96b3016d6fc1fdbf.nq.gz
│   ├── 7bf93d068ea25cc2fe44ba4b4c4e5b1544e7fa18.nq.gz
│   ├── 7d072d66de4e49315aa2483e03afbcede9ba2109.nq.gz
│   ├── 7ecb85bb19a8a1e4710e6b41316d0555087cb28f.nq.gz
│   ├── 7fd6bff7fb0d5cc18e6045b02312560fb62de057.nq.gz
│   ├── 8171ffd56add07fa00a49018c05e33d191cf4dd7.nq.gz
│   ├── 81dd9175f5defc2396c2048d46d8645b0e2e9da8.nq.gz
│   ├── 85f5862470f707b67573cf29f60a760d8ca0470f.nq.gz
│   ├── 868abebf6f32ce3a12bb406d509609f23a2f0542.nq.gz
│   ├── 8aabe7dd229b458cebec4b864373e3a7d8aa0b59.nq.gz
│   ├── 8e26dea2fb500f8c349678ef8ce81ac6fab43f7d.nq.gz
│   ├── 8f055d9b58fdca32064ffa1e2953cdbc7d539f6a.nq.gz
│   ├── 90a8a5ff4524d257b34b630dd200dfa1c71991d3.nq.gz
│   ├── 94d2b121e260c8e03575954c0f43719721e827ba.nq.gz
│   ├── 9593c5fb447e495abcde7c9754a2f723e1ab324a.nq.gz
│   ├── 9c277612b4db94711fb289bde18a86cc577fd12b.nq.gz
│   ├── a77540fdeee6851e3f066925d4ac8a943b9607cf.nq.gz
│   ├── aab72c946c746f49875d2c7717f8146d506182c6.nq.gz
│   ├── b0b340e0181e4dcd18e968082d8f0de28c7c73b9.nq.gz
│   ├── b6cc9cd0fd0420c0d58b506397b483d88161e2f4.nq.gz
│   ├── b754fdb83b4aaf2fce8f4668ce8514865bdbc555.nq.gz
│   ├── b7a9cde50628310241ebfba9df5b670b3c75e8db.nq.gz
│   ├── b8b864b6d16406773633be3550590aebdc5026c3.nq.gz
│   ├── b901f9cc02aa16938bf269ac526f85821568e5f6.nq.gz
│   ├── b965f165df08148396b2b63b12d00e5393793f91.nq.gz
│   ├── c2b5b051cf57b78aff32e803344e5d439d4e23f1.nq.gz
│   ├── c7a3140824b3a4c70c859e207a41f5b48a310b2b.nq.gz
│   ├── cb3d1065d12bd5522d4d03ba00fbac85d755d998.nq.gz
│   ├── cded29022d99e39575bd5301259124f21164da60.nq.gz
│   ├── cf0f27062a3e44b41b9b3123963eb928226cf5fb.nq.gz
│   ├── d41728ec16478fb749dbaa262106d0472a9d13bb.nq.gz
│   ├── d812a1df3fe6e177b77fc1776a750faa3a2acd86.nq.gz
│   ├── d8ca929a37ba584ef6062d188984da72018cfb47.nq.gz
│   ├── d966ae00a9fe60b645ba0988f709a700e18160ce.nq.gz
│   ├── d97cd4d563a942bc05609ad076d2b2a35852339d.nq.gz
│   ├── e1952cfc437b8b3146f8e3aa7dfe8107e8a271bb.nq.gz
│   ├── e2b028c0fbe22d33d27cb018278a2c21586c32c5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e1c660af0a222af40599b669f6c441216a1133.nq.gz
│   ├── ec30d8273ed7597555d1c47fef1cf3078ad42826.nq.gz
│   ├── ee4de496fd3d5c7a133ee38e836f6d7171adc760.nq.gz
│   ├── f3609016fc449e708bfbe0cf51710eb94a8c1c09.nq.gz
│   ├── f463c1b0e35344f34de9e8ec3dd52b2cc6d2b921.nq.gz
│   ├── fdbc04a2bad422356a736486f8f5ec111028a896.nq.gz
│   └── ff642aed8060e8964c4340f7937145fdca8c5e55.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dbbb41ad5ce671f90dc4d6b97c7ecdffa187715f.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 82 files
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

[scikit-opt/scikit-opt](https://github.com/scikit-opt/scikit-opt)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
