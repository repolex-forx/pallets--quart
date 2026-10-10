# Repolex Knowledge Graph of pallets/quart

RDF knowledge graph data for [pallets/quart](https://github.com/pallets/quart), parsed by [repolex](https://repolex.ai).

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
rlex download pallets/quart
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 29d339c87f9efd1ba5268666e2404530fe078911
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 29d339c87f9efd1ba5268666e2404530fe078911
│           └── chunk-001.nq.gz
├── blob
│   ├── 01aee1b59ecb8ef372dde3c3e1c6cb422bddc09a.nq.gz
│   ├── 0353fe73b89c78cf1814e021a5e693a517984904.nq.gz
│   ├── 0814f6cd01718aec9a0e834051eb59c914479184.nq.gz
│   ├── 088d0976a4683f1255ab566a554b18c05f3f606a.nq.gz
│   ├── 092f39d530829741b9ae17af97fca21e4731c67d.nq.gz
│   ├── 093c6546a09311b9471450e4d57a127e8d263ab4.nq.gz
│   ├── 0bec6474520ecd7f8b51a639b8c4c97774074b94.nq.gz
│   ├── 0d853d3cbe9fc9a46890ec062cf67e4aacea4fb5.nq.gz
│   ├── 0d86aaf41c5edb29cda19afe86fc9c77fa331cfc.nq.gz
│   ├── 104166ef51ed28967bddf5fde28ebf84cf9e5111.nq.gz
│   ├── 130b0e6b2fa9ece72318dc8b5087a505faefb1f0.nq.gz
│   ├── 1b1b32b1239a1239f4aa7e940a8c04d42bac586a.nq.gz
│   ├── 1ba0d09282f523e03be644a076bfc9c842a9c4f5.nq.gz
│   ├── 1bc32a2ed6a96e862cce33cbf529f4fac01ceba2.nq.gz
│   ├── 1c016bcec1d8484e1103516836dff28c7e0bb1bf.nq.gz
│   ├── 1c850e21b5b721d9a0b899eff442daee2fc828c3.nq.gz
│   ├── 1d619b620eb8d6617e290e202fa2383fc76434f9.nq.gz
│   ├── 1d787430d35ccb9074a1c50d6ee70b0c1c777e04.nq.gz
│   ├── 1dd37aa43c9d71c2297f07d849299ed439b3fbe6.nq.gz
│   ├── 206c189e29333e4aa207e9e61114613d8bc229ab.nq.gz
│   ├── 20d2dcfe7f23c19f5edcd218c7d36d4f3c0c1062.nq.gz
│   ├── 224a2c6ac8be262669803b737e79e81c46ba7730.nq.gz
│   ├── 2fc693817b3cdb27feb96fefc81012c670a09c3b.nq.gz
│   ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
│   ├── 3008f57909eba56aaecd6addf365583e3cb491ac.nq.gz
│   ├── 3092aa089537bfc10ba2a6fefadd445ed8b3bd17.nq.gz
│   ├── 319cbbc41f78042ee108b1d4e8be1ad3c99f9285.nq.gz
│   ├── 33ede9d58218b0a2940cdd511fe09a5316781348.nq.gz
│   ├── 354a8caefb4bc6b9e86c83c901a7ff437b505750.nq.gz
│   ├── 35597c2eddf0cd0476e100a55c38f8930233c26a.nq.gz
│   ├── 3567cd6aa970896066f27c8db2764b68a0c584c9.nq.gz
│   ├── 3697e7c327ee5f36df89b1c91d53c3ece8a6688f.nq.gz
│   ├── 379c689118288b23d4a73e638ec000e5417f3e7e.nq.gz
│   ├── 3e661fa23c964a5cc6912178498ab0b442477e45.nq.gz
│   ├── 3ee9ee90c20b53add6cb8562797e3f6066c52b58.nq.gz
│   ├── 3f9875cde02497d05744084f637364d540968d53.nq.gz
│   ├── 413783700775c8cb5d7236ffd51869e47e2e3f21.nq.gz
│   ├── 41ce6759d076dac3269abba0d7142f8a0d69fc81.nq.gz
│   ├── 42a7f759cd165ddfa54f3d423375fb413fea0045.nq.gz
│   ├── 453f9685357f1ed8d0fddbb6233e336f1b929cf2.nq.gz
│   ├── 45dc5800de5fbd52445214ac4164c35d96a13d27.nq.gz
│   ├── 48e01316ec6965f833aff581c1538bc97cbf07fe.nq.gz
│   ├── 496fcb8b26abed928ff6341fcae543ccb76f55aa.nq.gz
│   ├── 4ca3107956f479942a6f8be016ea8a54654e4ca0.nq.gz
│   ├── 4e878f43d89fb405c5d2c68d3812eb94219c8792.nq.gz
│   ├── 4ffdab5878e995d1ab62b8bfe881abd5e16f5178.nq.gz
│   ├── 50a7cf6e4ec9df6622263bace83f5648fa92c76f.nq.gz
│   ├── 50b767aac8fb9624d0d834397dbeecb73dfe6f76.nq.gz
│   ├── 5671b2c9f7780ba63313ab1e70751fb2a79988e8.nq.gz
│   ├── 587f8cbbfb696de2539b93693e40ef59b6494adb.nq.gz
│   ├── 58b884e356352cc80485107c8b8d58afd2648e10.nq.gz
│   ├── 591c3faa67cfea8e561153fe20e8a1cf9c28d203.nq.gz
│   ├── 5a196190d5584523e3dc90d067b856537ed2225e.nq.gz
│   ├── 5b1ce33f57ef5371f13ea40c46f3918bd63c1a2d.nq.gz
│   ├── 5f522c22204b689033f69e581c007bc1e1d73774.nq.gz
│   ├── 600db78306d387e42b2a03514dbfc28fb6bcfdd6.nq.gz
│   ├── 6040a977eb929fff2ab6f64c46d8ae9dad45c6bc.nq.gz
│   ├── 6115931055ef2f898c0d4133447558686d485df7.nq.gz
│   ├── 61b0704f453c1a670c7f63b4b40551c0efbd6d40.nq.gz
│   ├── 639a1050676c4e7fec71854c7cc48a6cec293463.nq.gz
│   ├── 647ed03358bbd26a7bf77ed8d2ba87d640b7c068.nq.gz
│   ├── 667f7e951c6b5e68bbacb481f57a4639153b937e.nq.gz
│   ├── 66f7c5a13e788437a51a32b7ebe056e95917a3d7.nq.gz
│   ├── 69daa1c6178705758b9eb26a1ea3e404b1f634fc.nq.gz
│   ├── 6c2fa3a5841f84c1a6e0fedaa205a6226ca11a87.nq.gz
│   ├── 6eb2c67e131f3e4884e6b6dcdb5fde5ba2b9c30c.nq.gz
│   ├── 6f172638bade73ada7bc0cd7e5d0fbe8ece6dbaf.nq.gz
│   ├── 6f3e14fefb964e1fa4b6838e0abb2790688ac989.nq.gz
│   ├── 704ad03b5ae775301c9a34d7a3c0244a13ae0927.nq.gz
│   ├── 709de0ea6118975c0a6cdbc2f72d2d8dd676e75d.nq.gz
│   ├── 71939f0a393194c98ea92e27f161d29ea81387db.nq.gz
│   ├── 749dd6ce6cf7c838b97eae78d3af8e3c4513099d.nq.gz
│   ├── 78bfae6a407c4035e125e35390f92bc1d00da4d9.nq.gz
│   ├── 7c272c40e9b3652f87c2fb665b2696d3a3b0126a.nq.gz
│   ├── 7f629cfb2df5ca7f705b7daff841a2e5cc54e290.nq.gz
│   ├── 8004a69e9fc7fd760e95083a3561258611a08bca.nq.gz
│   ├── 823a66e4a03d57a07445f8661b166decc6ad2841.nq.gz
│   ├── 880f769d351d4a0ea7b8c1a3358f1f8d69a2d8c2.nq.gz
│   ├── 894694f667c3b7c17c9afa394c6010fbb2ce8625.nq.gz
│   ├── 8ae0d32685c8cf728850f2a25368b7eaa537032e.nq.gz
│   ├── 8cb7c59c2406c48c3a43c6bda711a0a5eb78ae94.nq.gz
│   ├── 8db0f7efbc4b436f5f89c4428d62aa61cd81e4dc.nq.gz
│   ├── 8ebeebf21f1012e56d7e5e066f43c06ea06fbdb2.nq.gz
│   ├── 8f29ce5cee88d7a025867b765472148f069ed71e.nq.gz
│   ├── 8f54d68d5d910fd56d428c37f201623011ee3157.nq.gz
│   ├── 90253637ef1525735f22f2b14775157ab49dee04.nq.gz
│   ├── 90c35daa4dec581fe5ecf1224cfa7f739914b8dd.nq.gz
│   ├── 9258a64f14c158e68e5afa71ff14904e29e68f00.nq.gz
│   ├── 9282b66de8c44e82739fb27a15159e522017da00.nq.gz
│   ├── 94e30aee512e0b2a83b77863d5fff42a5f94b7b6.nq.gz
│   ├── 95cd12974f2340f235b93cbbacd2a466c1d93df7.nq.gz
│   ├── 9756599e2b61650fb087a192d0a568c98c178342.nq.gz
│   ├── 9858b713770fe1b0fbcb63712880269e4329a4ff.nq.gz
│   ├── 988a1b725c29c41ce19f1495a3bfcba0a7ab157c.nq.gz
│   ├── 9b280bdb5fc4d772dd97009242826e913aad621c.nq.gz
│   ├── 9bf8ee38ee4dc0cd98fb325197bb29ed31107789.nq.gz
│   ├── 9d80a01e570b2b0022294318ffeb49ccb1484cc0.nq.gz
│   ├── 9f57948cca0f39c6063312fc9bbc4f8e6bd121fc.nq.gz
│   ├── a0c1e7d8f286ac1749d863b8ce0e9cebf117f2e6.nq.gz
│   ├── a1ed0726dbbc1f3cfe019cb6fdd570d48763bc44.nq.gz
│   ├── a2cac241756dd5228ca722e6edb8362d4986984a.nq.gz
│   ├── a4a085d00c664768b8570037257753ad864e00dc.nq.gz
│   ├── a54ec9894bf43fb68c6b79472a18b82948aea44b.nq.gz
│   ├── a655b88482879b87bc534aaacd7f7351a993dbe1.nq.gz
│   ├── a765adf18fa20d7f02cb5cde1524ffdbd6ffa616.nq.gz
│   ├── a7e883cb02dd61c2ba67a6cce9bd8cc897e91a52.nq.gz
│   ├── ac980ffa8db8ddb50bbef2bf7efe42a35c8e376e.nq.gz
│   ├── ad12809f7bc0d5cd9910c9d03c7afaeb98a4e253.nq.gz
│   ├── addd596da91f84f4980c4706d23d227cebaacecc.nq.gz
│   ├── ade03576a329977fe3ef4350ea774a6382cd208b.nq.gz
│   ├── af9a914d6aa1bf7bc9b1bd6cf3286a0efc659cfa.nq.gz
│   ├── b2bb7f224a1798848cc9f14dae2c4111e76a4e2e.nq.gz
│   ├── b2f69eb20dbdec3ed537201923da843048d14e41.nq.gz
│   ├── b3338d69945ace8adef32b6958e2668090580696.nq.gz
│   ├── b63a42887370c64089e0f25c12e17d90cf319ba8.nq.gz
│   ├── bb2e42c60052838aa70d738ec098f57678dead4e.nq.gz
│   ├── bc4492049b171266cdf3807030a93fb58349b400.nq.gz
│   ├── bc66bd16a81e1bc0d49cc6dce842f418130e75c6.nq.gz
│   ├── be4f010874b8316703b0af90676f5c3cb23f1144.nq.gz
│   ├── bf712b269571cf58ddd826bf7dd98b6db4dc030f.nq.gz
│   ├── c06cbd0eb853adec112410f6a80875a0a0b1ab53.nq.gz
│   ├── c203b5c67319f05f15abc56b41a16fc0f7b00303.nq.gz
│   ├── c208b17f8ebecd5636dbe4ae8dc5514a69e47caa.nq.gz
│   ├── c58be49a6419deb84b05449da11664d29a610757.nq.gz
│   ├── c5e85f22011a8621a64a8fb27487d9f2c7db4ac7.nq.gz
│   ├── c851d2ac7eadf5c3c1394e896938f63063eeea1a.nq.gz
│   ├── c88e19ded71f0807b770ebde526857ca786d28b8.nq.gz
│   ├── ca66fc77509b8131d19c4066c0466b39bc792235.nq.gz
│   ├── cb29c3055e934d01c0a8404e664b367460beb956.nq.gz
│   ├── cc7c19f83e3bb209279253fecb6b8400a96fe2d6.nq.gz
│   ├── ccbcdc70ccd352a7f03e4f9cb72303de2668d219.nq.gz
│   ├── d176e67e15e4f0ae6b1ef7c8f442b1dcece6bfa9.nq.gz
│   ├── d29c3c5cee2dd33d1db24ced014b39d87929e8a9.nq.gz
│   ├── d6a218024ce39fb910afaaa432800b3e26e5f7b1.nq.gz
│   ├── d868dc571440ea1d6bed4c5f3c64da5485a3caf5.nq.gz
│   ├── d89d16db99c0df3e0c57fe999e5505a8269602f1.nq.gz
│   ├── d8baa12610201e9fdbc3d0470ddc2424f455ae65.nq.gz
│   ├── dec8b8464cb0b21e0873110a45e9a2db048d451b.nq.gz
│   ├── e22d07a8a3e033b098313cca729fbbdf2cf2733e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f3e27334c63986000e40b454edae8ca0834cf1.nq.gz
│   ├── ead10c86195a92728ddfc88b1af725ba56e8785d.nq.gz
│   ├── ed85ab962ec57e2a05481e9af6ee62e2b8788698.nq.gz
│   ├── eda8c518a76e6d8e02e166c2cf2eaec3a8a1bb09.nq.gz
│   ├── f1fef6b1af298964c2a6fee292eb79e966894e09.nq.gz
│   ├── f2e1b8869f97ea3bc6965e1b50e1e84385bfea3c.nq.gz
│   ├── f4cf0ecb1b894f0aad614a1860cf2ea9b79e76aa.nq.gz
│   ├── f531fe8bc36be087802d0a81387ebc2342a8d656.nq.gz
│   ├── f5642f79f21d872f010979dcf6f0c4a415acc19d.nq.gz
│   ├── f56f4f554571d8f1b8b392909742c5d10672107e.nq.gz
│   ├── f6653c3589f57823085535c09379a21fdf8281ad.nq.gz
│   ├── f79d5e812bef6054cdc7982e72b3a235053c4890.nq.gz
│   ├── f7a61af7b39d94fc217965a07bc73a7f3c144fb4.nq.gz
│   ├── f9afbb18b1adf34cba372b30cce4f8e2f34ed182.nq.gz
│   ├── fd23b7b44637b020db210efcc6fead83df4ada62.nq.gz
│   ├── fe0a7c8260e6b671d02ae56ba1963bcba7958a06.nq.gz
│   └── ff1fc6e777f24a0aa1a15ff7fb5072e4ac2a14ac.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 29d339c87f9efd1ba5268666e2404530fe078911.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 165 files
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

[pallets/quart](https://github.com/pallets/quart)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
