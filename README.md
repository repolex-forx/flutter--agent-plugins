# Repolex Knowledge Graph of flutter/agent-plugins

RDF knowledge graph data for [flutter/agent-plugins](https://github.com/flutter/agent-plugins), parsed by [repolex](https://repolex.ai).

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
rlex download flutter/agent-plugins
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b7d5a0be4195b82fe073620fb52f594b0809eacf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b7d5a0be4195b82fe073620fb52f594b0809eacf
│           └── chunk-001.nq.gz
├── blob
│   ├── 0180c2a7b1d99be57f2c4eee5f9317d906dadbdc.nq.gz
│   ├── 01ac7ac645a7f6f66603cb1c78a2a28dba3a5d32.nq.gz
│   ├── 0684713f198b3942d4416f40a6c4bb77cde58a61.nq.gz
│   ├── 0b4b851ceb575dd175e608d5bcec3b0685744f0e.nq.gz
│   ├── 0dec8bd275fc5a1032abaaea7082fd4b7d9d7b3a.nq.gz
│   ├── 0df99dea70c48334296bd7ff8e108b04f43db0bf.nq.gz
│   ├── 13ba91c54f875aca5676729257a57d9c545a1cb3.nq.gz
│   ├── 14009f4e07c18d0a3762942fa54d5225ee563d95.nq.gz
│   ├── 160454305f007fa0fe023d57bcc0a5b4f8936212.nq.gz
│   ├── 1a7db85158aaeced4d6f702d73acfd6f37d712a1.nq.gz
│   ├── 1b89d605edb7f7fe86dcefacc3c411aea224fe76.nq.gz
│   ├── 1da6da39b0c550135447d2a047f48383abfe0a0e.nq.gz
│   ├── 272031181bc8d8598c934a14b1d12cf08c7aa1bc.nq.gz
│   ├── 27ca6546684accbc8f96091d0b992f6f43a16d15.nq.gz
│   ├── 293acb8418a1949b41154b9c067634a31fc4ca53.nq.gz
│   ├── 3266dc0fb7a4aa60e833b7b70e19028ff236d5e0.nq.gz
│   ├── 32e9b6e66e2bb62db37784323dcecdad4f9db55c.nq.gz
│   ├── 343419488898b641dbfecd73d8f15a67e4f6802b.nq.gz
│   ├── 34dfee4944ae1f975faeba96887cf6bdd737b1e0.nq.gz
│   ├── 356ccf36e809a3bbc4d27aecef794f5eba4ff344.nq.gz
│   ├── 364cbcc4044050e8e782c19f17f40d538d41f421.nq.gz
│   ├── 37f87868c24c0ff7a34343df09088cd85320b96e.nq.gz
│   ├── 3804a3c1d9fd2b88ee1ddc74716799cf2cd770c1.nq.gz
│   ├── 397b4a7624e35fa60563a9c03b1213d93f7b6546.nq.gz
│   ├── 3b5aa186514efb44f3eb60ab952fca99131f0ba3.nq.gz
│   ├── 3c61f9b655c3a528c9bb7c0324b74e3fa44e007b.nq.gz
│   ├── 3daf8944c0ff9c537eef4d9943f9139cd9853b6c.nq.gz
│   ├── 4057a7b789337a6d0de0719cf3bc91ac2578240a.nq.gz
│   ├── 41fa32fe2878b7deefd1aa9bee58a1d55f2d9d22.nq.gz
│   ├── 473129c52f67bc4031916c58dfc5f50d2cb4ab66.nq.gz
│   ├── 48f8a621d2e17b1f2576ad82746eed39e77f59ec.nq.gz
│   ├── 4b2f28b8a3700f0fa71783456d97f072d56fd3e0.nq.gz
│   ├── 4bb3ff41c2e8c9f3e0083ba8c1676cd362ab4a07.nq.gz
│   ├── 4cea1d2650bb310bd34bf4bb3a7d945a746c8d9f.nq.gz
│   ├── 4f759480340ff1b59198286027d201ab4539e776.nq.gz
│   ├── 517d9154aa77214a103d75bc5672856f9b3a6226.nq.gz
│   ├── 52ca0ad7a140a40953ec415bae446a06f82a6960.nq.gz
│   ├── 5f9fe324099a296237fa25fe7a65bbc6d176c64b.nq.gz
│   ├── 60902f1aa3156fa0c8e28df5448864dd5cc6c014.nq.gz
│   ├── 60dad77533dc0a98b7f4a8363ac1b56d589d353a.nq.gz
│   ├── 6435685ad7151bf8fc2f3932cc279e317e0b8b32.nq.gz
│   ├── 6475eb21ac240276f8dc8ac528f65393b5073ade.nq.gz
│   ├── 69fc4f6813680affa1a5d040c3a30837ff16b3c0.nq.gz
│   ├── 6aa722eeed5a19430abfbfcf3f523b7a71b2a253.nq.gz
│   ├── 6dad6ad7a0b0913acbfe14f2090b58b358d14a68.nq.gz
│   ├── 72bd2993648c9e130436a8cb4acaec144bc399e5.nq.gz
│   ├── 7612948756281ff046147e206268134a3b66be11.nq.gz
│   ├── 791994b12280e5734479079bd6255fa705e983c5.nq.gz
│   ├── 7e0601879f6d8ec8ac00ae3bd86f28543edb82c3.nq.gz
│   ├── 80b70ee6f8e6b5eab1b5abc669ef78d9de01a7a5.nq.gz
│   ├── 89db1321486d7997dc4fca7b6c4b397618fb6b7a.nq.gz
│   ├── 8d4f43f9cbab229ff645ffa2298ef59cd8744455.nq.gz
│   ├── 983ea46a46f5154364279ae6525b195ea39e5c1d.nq.gz
│   ├── 98dbcea010edf5d88cf125d01c1059d50525787d.nq.gz
│   ├── 9a7ffdc5a79c14ad2e3d8dab6e257a28cfa40e3d.nq.gz
│   ├── 9b795fddc4ef58ac4cd7a3fb0041285752006a64.nq.gz
│   ├── 9f8f7dbcbeb55c4993a1cb251890687886d11a9d.nq.gz
│   ├── 9f92eab3a167340b8ff65bb776a597bf2c3ad185.nq.gz
│   ├── a274533b804133674c2946d32c098a97f37ffbc9.nq.gz
│   ├── a4921a529000ddbfa6c98360dbc0b68f11fc4d4a.nq.gz
│   ├── a731482837e368be670f2817b553c916eb9e791c.nq.gz
│   ├── a9b4f153215673d446206d5a21f7fe19c7ea37be.nq.gz
│   ├── acad25545504e0e6305b9ee3cfdaa587048a48cb.nq.gz
│   ├── b029377573651e40068f5df1fb0caead950345f7.nq.gz
│   ├── b0445a0ce7cd2ef53010b0a344df643299e241de.nq.gz
│   ├── b287e6bd4487bb0cb671b0091e316009e260d632.nq.gz
│   ├── b62a077fcd4d0eba476f47542c2e807c65154edb.nq.gz
│   ├── b640fb1f0151d7b7623b33fa6579f0a5b8d5195f.nq.gz
│   ├── b85bfd7e82e30ac676d2140ddb436bfebd0992cb.nq.gz
│   ├── ba960fe3e328e04291475cd742bcc49abc3b2c13.nq.gz
│   ├── bb60468d6448259b1708a2c34a01f43e77529437.nq.gz
│   ├── bd893f44ce125fa996dce30db8ec3b84faa4ad09.nq.gz
│   ├── c02a83c61e21fed28158ff5638be1f96d910cdfa.nq.gz
│   ├── c26977ba9ffeb1625355a8e9abb1a794f8c7d4c7.nq.gz
│   ├── c5d055debaadf6708223b8e6e5bb9ca002ccb172.nq.gz
│   ├── c749c942216af03319f75c646cdb631e9484f507.nq.gz
│   ├── c888b42c94118e953a48f82bdf6a8a5eba025b52.nq.gz
│   ├── ca6bf1b4db87820efb2bd9c0981a29d179487d3d.nq.gz
│   ├── d1f8ce48a09c9fd70d3677dd339150b1431d06fa.nq.gz
│   ├── d272605ce4079026c26bcf4e3ac23239d8a50c44.nq.gz
│   ├── d3dd4596da225df783e1816c658125206566902b.nq.gz
│   ├── d47a04e91b8d89a7f9459073a06e90e7074c9a51.nq.gz
│   ├── d4ed13b2d17b6542fe2d437f7e1910d135e56b34.nq.gz
│   ├── d7b58629f1850f91791f7ac5db588386ffa13843.nq.gz
│   ├── da7e78ec1c220cd0aedf7ad36424c9398034f375.nq.gz
│   ├── daab92075fcc9f8e519c064c8ffa6e4a9caba8e0.nq.gz
│   ├── dbefcf5d4d1feff8a8bf9118a673c875ef1b5ae1.nq.gz
│   ├── ddfa247cab130eb04595dd4cd9ad78c08caca009.nq.gz
│   ├── dfa4a87dce1c68e402213deee6ee6f8535fb7797.nq.gz
│   ├── e2d833a21a2f48fdb6a3e150a8c6f8887a7b893d.nq.gz
│   ├── e531ee1ec1e34934cc81277c27a7324e108cfcee.nq.gz
│   ├── e5fc042aa237954f5291b86d455c8b675204664e.nq.gz
│   ├── f055e473d5f32ed4384138db36209a3aaab20271.nq.gz
│   ├── f17ec760885a9a3bca9eba53ab10b3391c3c60a0.nq.gz
│   ├── f1d927ad2392eae45e218e423aa6fde0f07bae89.nq.gz
│   ├── f5d36250536d6738cf70ee2ddce5aa570ab9ee92.nq.gz
│   ├── f8c23f6059ffa33e2ef99068b55e8e4fe1db8bf7.nq.gz
│   ├── fa3a52148ce504906fb54741a98521829f2c849d.nq.gz
│   ├── fb3be41704868aebd3210d23426580cd3aaf33b3.nq.gz
│   ├── fbcec2afe990114460c568378f7de548a171f407.nq.gz
│   ├── fcd6d8b5e365f586155dd64e85e5044ac603a894.nq.gz
│   ├── fde16134674af312d283db4398df5e5a5005c437.nq.gz
│   └── ff3f022dc8cf92c05d78a8cb49e7783436718d36.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b7d5a0be4195b82fe073620fb52f594b0809eacf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 111 files
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

[flutter/agent-plugins](https://github.com/flutter/agent-plugins)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
