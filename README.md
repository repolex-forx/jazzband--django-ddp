# Repolex Knowledge Graph of jazzband/django-ddp

RDF knowledge graph data for [jazzband/django-ddp](https://github.com/jazzband/django-ddp), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-ddp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e1954b06fe140346acea43582515991685e4e01
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1e1954b06fe140346acea43582515991685e4e01
│           └── chunk-001.nq.gz
├── blob
│   ├── 04f53cc2d6005852e2533d287d7dc5e7bf87f162.nq.gz
│   ├── 05a79270d7c396ff694c853506dd86a5a8a78f93.nq.gz
│   ├── 0ec6ef4f3ba8a9fb5689fce8188b3946da33ea45.nq.gz
│   ├── 10d00ca837a57905c29435ab39135505ade875ad.nq.gz
│   ├── 19b5cbe8b92287af722eb00fd718569ce7dd1363.nq.gz
│   ├── 2508c59b261de905c64f95578b3341401942652d.nq.gz
│   ├── 28c52e138d876f2c031ab9e047333d471f79031a.nq.gz
│   ├── 2b4f81bf494da1eb11b363cb02b437dcb23db453.nq.gz
│   ├── 2ec0b95f7c36c15ffece8fde53e85d2ee341c218.nq.gz
│   ├── 3247443f9eccd1431d0361146d9043093c1d665c.nq.gz
│   ├── 3286ae10e1aa46ba1b7a321a3aaae2b75218155e.nq.gz
│   ├── 34fc58968ad65762b3af9d78cd35cb0d44c23d8a.nq.gz
│   ├── 3547d3487cf3c72bfac28bd9c62ebd67591d9928.nq.gz
│   ├── 39d6b25dbd02978b4dd087ac51ea514b6fa81199.nq.gz
│   ├── 40830374235df1c19661a2901b7ca73cc9499f3d.nq.gz
│   ├── 40a8d86ab4550e9a25fd9c20780fe20d03647bfa.nq.gz
│   ├── 419b103bc9cdc903ff7930da1f7fbe82fb0bacef.nq.gz
│   ├── 470ffa6f63deec60d598217dc70fc3c100e309c5.nq.gz
│   ├── 4b0bd4262f3e7a9f1eb09df06cc4e1d9739484da.nq.gz
│   ├── 4dc0eb5d42e682268541a989e2b6b1347cf99b5f.nq.gz
│   ├── 4fbec5408b052724de29f9bcdbf25f750b47e813.nq.gz
│   ├── 51b84bc0a3bbab42208cecee104999a4a08b3eff.nq.gz
│   ├── 58e50fd32c0d60f50de5253dca559e1b1ea2ff73.nq.gz
│   ├── 5e9ef8769a070d6ad3af7d9ab8dc1707155565fc.nq.gz
│   ├── 61ee31323076ac79f19aa4731f73cc7fe0db72a7.nq.gz
│   ├── 62c49593e7f4af377ef7be6ff56cbe6c1c28beb0.nq.gz
│   ├── 648a7cab9eb8154fed621c4830ca5377852b18b4.nq.gz
│   ├── 6583844fd8bd620effdcd185e90cf50eca31b3b9.nq.gz
│   ├── 67009cec3bf1764b45803c46cb3124c329d3a82f.nq.gz
│   ├── 6f2b3d6fb4139865f51a623649e5c762c524317b.nq.gz
│   ├── 712ef798f5150b1c3b385614f5227fb06118775a.nq.gz
│   ├── 74de31704b7951dc50fa60ea42bff1f9630fd080.nq.gz
│   ├── 78a7f9901ac365a4326e5cddfd52f865964efe0f.nq.gz
│   ├── 7a314e69bbafafd0974bbd961862303e49995bc3.nq.gz
│   ├── 8f2b441ce5c14046cf9eeb8a6f271fe1089281b1.nq.gz
│   ├── 9192f7baa9f0114d6ceddf9c04e1646ec2a3bae0.nq.gz
│   ├── 91d2282c95ca35920a8131b60c0d55e2143fc954.nq.gz
│   ├── 940512f0c18e6a8ad9d647891e50913f8c4511a0.nq.gz
│   ├── 94580059253bcd5a52502886ba80bf2ea8bc79a6.nq.gz
│   ├── 947e99ebf567990afe2b76efe9ec6a5b3421f823.nq.gz
│   ├── 9a8d4c6337308e4ee0aefa2a6f302cd240d9b2ab.nq.gz
│   ├── 9e1cb92c65e17e8c2c722049b799b648810b2108.nq.gz
│   ├── 9f5e780dc20685bebf5e3478ce7f1c2295e85ac1.nq.gz
│   ├── a01ed035fe49d49413802fd85bba410c5c84162d.nq.gz
│   ├── a045855eab704cec70c45f90ae5f74732b72291a.nq.gz
│   ├── a0de59db90dc5b3f0b2bba0f0d3be233763c826f.nq.gz
│   ├── a4b6997483fc27d5fc3c8b7a253a773be017039a.nq.gz
│   ├── a7a5657b234df2f5145b7dcf9b144dc1c61cb324.nq.gz
│   ├── ac186dde0c9a8f0c744ac14db1da92f7c403815f.nq.gz
│   ├── b4d04d892aa8023a57508a17ac22e96972292ba1.nq.gz
│   ├── b6f1a704cce9a70f6a9c3737e64ef17de17077c2.nq.gz
│   ├── b8c4abd05c471702b0a9c5e09ae2ab0a7662116b.nq.gz
│   ├── bade6b90ad65882b87b85a23e30d7498357c50a7.nq.gz
│   ├── c41cec0d543f9820219c0c3c5befcbed2ed36490.nq.gz
│   ├── c493424a085a4fc107d53c7a6f85db517df47bc3.nq.gz
│   ├── c7adc86ff4d6d6e0884f8b5fe46d379dd8a4e6fb.nq.gz
│   ├── c91f6ab261dcc328257e8df462b212cfab1b53ee.nq.gz
│   ├── cc4a95c9d87def6438546da62478ed1f4a3584cc.nq.gz
│   ├── cca37260ae15989a5d0be2ed8b73412487e13010.nq.gz
│   ├── ccb3468abc42bc7fcb0893ef90d56160ec6604a9.nq.gz
│   ├── d579c7a674a95fd5a638a0040b153d4847253c24.nq.gz
│   ├── d8475899b616a3350359702fd1aa38b8fef8968a.nq.gz
│   ├── dcf69453b29c920681393028b57d139f638faae5.nq.gz
│   ├── dd8d12ca56b03f70907e7d6e283e59b1eda93d7e.nq.gz
│   ├── dea83e10d263d9ea0e72a9d2debfa3fcaa6505c5.nq.gz
│   ├── e233d239e2f065aeec0ac3aa931ad988ec63053f.nq.gz
│   ├── e3799b7c69f2b8cfa1c2cf8a98860e807d3d35fe.nq.gz
│   ├── e3eac98f8b0816e9b61c15d17ee8612bf4c55a3d.nq.gz
│   ├── e4116d4b832d065f8a1841b39081a60b2e8a4ebd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e81c998e08df16965eea4d77829e2a4774086096.nq.gz
│   ├── ed5e77ec5d74a2acc63539d4690c747b502b1b2a.nq.gz
│   ├── ef670917ab301f99c92840922c3beaaecbde18e5.nq.gz
│   ├── efeba1b50c759324cbdaafd7da6c31b030bf9600.nq.gz
│   └── f8db5a6ded0b5cc8c723e98ccd793cb005df974a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1e1954b06fe140346acea43582515991685e4e01.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[jazzband/django-ddp](https://github.com/jazzband/django-ddp)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
