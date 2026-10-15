# Repolex Knowledge Graph of jrief/django-admin-sortable2

RDF knowledge graph data for [jrief/django-admin-sortable2](https://github.com/jrief/django-admin-sortable2), parsed by [repolex](https://repolex.ai).

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
rlex download jrief/django-admin-sortable2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 899402aa0aac301d27dc1c16116dc7c067bf4461
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 899402aa0aac301d27dc1c16116dc7c067bf4461
│           └── chunk-001.nq.gz
├── blob
│   ├── 024ef1c18eca7ca59e0ad9f06358702b4358a419.nq.gz
│   ├── 0cacf59b0804c90d6868c5ce4a459d356d7824a5.nq.gz
│   ├── 0d284923cefe2437f5df413ea12e4200b453fa18.nq.gz
│   ├── 150ed89bba6151bb9854fbbd4f6a256f5d427a3c.nq.gz
│   ├── 152a9fa61e52605229b7458c286c5df09d7941c6.nq.gz
│   ├── 1afc4ad7f89a9a48feeda809eb12079b4cc20b2a.nq.gz
│   ├── 1b86aefd539d7bb140dc1dc2acf18702207d9c55.nq.gz
│   ├── 1c4ddd355acf91ffdc9a59285cdcc006d183a087.nq.gz
│   ├── 1db44344ed794825da69e73234f8053af9c69d57.nq.gz
│   ├── 203656b844885aebe9f18d84b8fb1663f073a92f.nq.gz
│   ├── 2798acc3d0c3e2a636b351e1592f3c801cc592eb.nq.gz
│   ├── 291f40cd52cf47cfd5c3341fa57b230c844fe56f.nq.gz
│   ├── 325187417d280e6669c95a6f82a3e9dab91749af.nq.gz
│   ├── 349805503eaaf09da809f354f39e9cc8fc6d36d2.nq.gz
│   ├── 375b0dbf485a3f8ec968525ad51964a0675eb447.nq.gz
│   ├── 44750ba0d4edf629b35ec2036b0d2d5632db0f4b.nq.gz
│   ├── 45759448d2d27ee996131a141d77d1419e8f6ea6.nq.gz
│   ├── 4bab67559de7279909129e166874f7a2683a79d3.nq.gz
│   ├── 4daa83fcf3ff78b39574b92bb78d8db6e17458fc.nq.gz
│   ├── 525bccbdbfe1dd7c9af1146957e6d5971c0d8e89.nq.gz
│   ├── 53bcb495c8261c87d6aa41dc21d792e4f86e4a78.nq.gz
│   ├── 545b6eeb53ff559189b9c40e75f6a21bc0d52703.nq.gz
│   ├── 549b5f341a3fee513253139127e991e5a7312570.nq.gz
│   ├── 55a57bf10c34d9e85fa23a460850ed79011ca797.nq.gz
│   ├── 55e54dadcfb7747ea8ab7da7bfa790646091fcc2.nq.gz
│   ├── 5b54c37da623152d390b192862c5849965dc243a.nq.gz
│   ├── 5b7f1299bd30f8c25721062916c704ac9baa9f30.nq.gz
│   ├── 6c54ce0d50e7704d4c4c6d3fccf8f549c72dd3be.nq.gz
│   ├── 7409bdfd8d0f19b98813ab1ac2bdcf2d99add1b4.nq.gz
│   ├── 775cdfe5ad0119e7eb044375835afe607d6b3a7b.nq.gz
│   ├── 7b888e6f1120295d95fb5130d17e6148257a2e4e.nq.gz
│   ├── 8184c40b1c2871375feb7115a3c52a94c84c7545.nq.gz
│   ├── 82fd0afc1d904a06c2813c73e3c8a7780ccaa2cd.nq.gz
│   ├── 83e1ce892585ece95a98a840bc165f2f0d0c4314.nq.gz
│   ├── 84ed9bf3d71c973606be6fb59a5d75b406bca9f6.nq.gz
│   ├── 86f4a63501cd3538ac0270b5a4b60012ac6b42d4.nq.gz
│   ├── 90b05c2b07cd2f59cb3fca4eca792dc803b7718d.nq.gz
│   ├── 93829bc7949de8c07334acfcdef3454ae0ddf4e6.nq.gz
│   ├── 94fbf065c96e92a65723e51b97cb1c8973accc6a.nq.gz
│   ├── 98c5469d9989481e975c85c1295357d15b713eff.nq.gz
│   ├── 9a4d628f8ffc0a07a6947a5d18c326e846508d57.nq.gz
│   ├── 9b02e47e72ef7c6f6717fc134c6b18245a04e305.nq.gz
│   ├── 9e509e95bed23cae312ed89a6853b66b8cb15122.nq.gz
│   ├── 9e8e81dfb36e0c021718d9076f4f70ddd86dbbae.nq.gz
│   ├── a0a989f3e3b93595715dc431093f851f46c21637.nq.gz
│   ├── a4908b56f30b2d6c51a1bec1b0c1044ffa112ac7.nq.gz
│   ├── a4d6c4bdb50767f33dbe5ff1d56aeaaaf13c4664.nq.gz
│   ├── a75de055ae2da5df8e3b27ea8b1da55dfbbedda6.nq.gz
│   ├── a7cce2e599c083ba0a7ca2a98c23611c73061866.nq.gz
│   ├── a80a18cd00fbce06855ee2767b46a54a6472288b.nq.gz
│   ├── a8e197d39ad711ae561952e2125612492c682eb1.nq.gz
│   ├── b87f7c731dfa4410912653522175f7de90d02fc9.nq.gz
│   ├── bb681f9d0f73cf169351c1376d640fac8aac7f39.nq.gz
│   ├── bb6f7c2baa3c9650f861cd9d028a4020b86cb5db.nq.gz
│   ├── c278daf07dff821b8e5af2a1aca3e4f87f0db1ab.nq.gz
│   ├── cc7bc5eb2cb193a842e1f441df4b2933a81b7945.nq.gz
│   ├── cdf09831e281ad588f99d02c4d9ce793a7e6fce7.nq.gz
│   ├── cff6236e4f2058a97748925efb106675fb479248.nq.gz
│   ├── d290e612bc24ebf7373ba8811352b8811ad23ae7.nq.gz
│   ├── d59814ae6ae7ce45040e4eb393b5b52146f6f3a6.nq.gz
│   ├── d870fa31125d802eadb91a7653838ee8b517aaf5.nq.gz
│   ├── dd0d040a32365c8cff27b13927d578b25c5a0a81.nq.gz
│   ├── e08218c875ecfd742f89b05f4679019ea5318fc2.nq.gz
│   ├── e13fd6467413220e9c0b3be5e9966b8f2e977699.nq.gz
│   ├── e5faf1b16135c72a68e918fb22b2ad0f41a8bb0f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e79ff11c0ffcc9f38d07fac678e49a973393788e.nq.gz
│   ├── e8563fb4ba6bdb0eb3e8541f55a3b88693ecf5dc.nq.gz
│   ├── ec1db13d985df01d0d3e8f55b462f8f814b2c387.nq.gz
│   ├── ecf6e9e03b8cb0157a4a0ed63f774f66bbb279ba.nq.gz
│   ├── ee0ba5dff7e28ccecc53281030ea66c53a94600d.nq.gz
│   ├── f179c661ab599fceb96a9b5fd1e2e62a32494441.nq.gz
│   ├── f5d5a821de0c7e93435ad01a7184185768f913f7.nq.gz
│   ├── f6845998965c5fc9f0b0b6d514c1123badf142d8.nq.gz
│   ├── f78f80f1f0e176e7cce247c4e0474833de8d1ed5.nq.gz
│   ├── fa98fbf272d5140fc60bf5e5887bfc0ad99633ee.nq.gz
│   ├── facb4e615aa68e881bc6accc71c8405176968c5d.nq.gz
│   ├── fba1c034baf0f0460e51c5beceab8fe16c7bde97.nq.gz
│   └── fece59e49279c4a3698bd4c294bf3767b2948d12.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 899402aa0aac301d27dc1c16116dc7c067bf4461.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[jrief/django-admin-sortable2](https://github.com/jrief/django-admin-sortable2)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
