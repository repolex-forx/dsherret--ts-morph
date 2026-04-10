# Repolex Knowledge Graph of dsherret/ts-morph

RDF knowledge graph data for [dsherret/ts-morph](https://github.com/dsherret/ts-morph), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download dsherret/ts-morph
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 686189cd860707bd96947156187310372eb7a85d
│   │   │   └── chunk-001.nq.gz
│   │   └── 873a2b351f4cb5ab5cebc77ec1dd88192f54ca22
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 686189cd860707bd96947156187310372eb7a85d.nq.gz
│   │   └── 873a2b351f4cb5ab5cebc77ec1dd88192f54ca22.nq.gz
│   └── repolex
│       └── 873a2b351f4cb5ab5cebc77ec1dd88192f54ca22
│           └── chunk-001.nq.gz
└── blob
    ├── 00293e08dd48a0899f586b4f5436aa47679e2ef4.nq.gz
    ├── 0049be922cd4f3a1a7206e70b86de6de28a61e79.nq.gz
    ├── 0071878596f48a97a8c835d673c09813aa1d16ad.nq.gz
    ├── 0089609011efc5b4bbe7eab118aed6457b6cd99c.nq.gz
    ├── 00d2d1202c7d4a2a1a7a39507b06498a1f22415d.nq.gz
    ├── 0129d60aaec50675b4ffa23a008c0f53ad3bcc44.nq.gz
    ├── 019f6124560a8b4ebddc77e982fe58bc828d460b.nq.gz
    ├── 01ed01a36244a5c9aa8d5613c8476ad3311b0801.nq.gz
    ├── 020d4cfa7f8f4cf9f4f8f6beb1db189ce75b0a06.nq.gz
    ├── 024497f5014b87e72fe6bf8437d446e5a42a480e.nq.gz
    ├── 027095ecb25946ff5cf6837ff3c164bfa04ca28f.nq.gz
    ├── 02b8ecb50605a40ca5ebae96da58710d157be1b3.nq.gz
    ├── 030d8db372d04897b65113f306f729d2c04483a2.nq.gz
    ├── 033f059a3830329688c20cda5c556c62bde4182c.nq.gz
    ├── 03578df4703b0633ef243494759b291338b91c9e.nq.gz
    ├── 038c3e0979b91a51e2cb43554bb570d4e04cbca2.nq.gz
    ├── 039e104b6a6ca5a8dbef77993cd1e8d3f7497912.nq.gz
    ├── 03b571d133aa761609c64d0a643595d4d0d1f451.nq.gz
    ├── 03d8ded080551944b65043bf530386e6b30a20f1.nq.gz
    ├── 0406671bb7170a998a011d50dbf43902284af25a.nq.gz
    ├── 0410b2ede033caeee7a3ef73128c9391624012cb.nq.gz
    ├── 0434010ed4ff4f6291717182f1bd44600f40f995.nq.gz
    ├── 04649f26b6f95795681bc325a874957d58b0731a.nq.gz
    ├── 04943e66d6669e7fba3a43252da1464bea1f1823.nq.gz
    ├── 04da4a9416b07b737c0e0ce6b748c82b8b71b1ce.nq.gz
    ├── 04eb26cc84129b493526290cdc4cd37bd18dc37b.nq.gz
    ├── 054d9a18d2949872cd845aae89175917b663deda.nq.gz
    ├── 0577cb1a2d2f9db2c86cb373c0820e9474b4083d.nq.gz
    ├── 057e2cd5612a511f10fde64bd93801218f712ad6.nq.gz
    ├── 05a399c786c8d8d1041fc319187635d490a07d31.nq.gz
    ├── 05afe16d2e1301dc58a0d55cd128c7a9b53e7069.nq.gz
    ├── 05cd596f326e5071ed2df0adae4267c9bd6be90f.nq.gz
    ├── 05f0786961f2c33d60b8a53047119e7b1c4537c1.nq.gz
    ├── 06c911ef2578bcdf28ee87d3622a7efea9a6beca.nq.gz
    ├── 06fd9770fe57eeb1ebf6f8c4177ddc0903421d82.nq.gz
    ├── 0707fcaa416f4a3bb7c8b91d38e00f7f2bc6027d.nq.gz
    ├── 07604f63aa95dc18f10337704f8cc56f80e3f509.nq.gz
    ├── 076654c71a1fc0fe37f4f3edee95711fd49a282d.nq.gz
    ├── 077c57ae6a07c8401554d9254e3ad4b4046f5d57.nq.gz
    ├── 07b26ffe14b23ee74652780a3913d20fe6732c6f.nq.gz
    ├── 07de69460432e2949e607416093d26677fe96af0.nq.gz
    ├── 082b2433be522f73990c10e8ef9ab351bda6dcc7.nq.gz
    ├── 08696a8fe18e17a54daac19e7d51b502794276fc.nq.gz
    ├── 08b788484d5a431fd8dda5988082b3561892cb7d.nq.gz
    ├── 092dc4533eb33561979d2ddf22ffdd8755d4ac8c.nq.gz
    ├── 093d32eda7d94aeac730598f862b6c484217d351.nq.gz
    ├── 0953d5e1308303b86bc70d7aa74efdeccd29f302.nq.gz
    ├── 09a6e743c2024f7ca0a07e64654836b8c46897c6.nq.gz
    ├── 0a81b73a59b8fdb699b53e92e28e94ed5a6e70df.nq.gz
    ├── 0b5074328015996907b5e10619a709b0325c2d7a.nq.gz
    ├── 0b66dd871532f88a51cd83c49e1343eaecd72ca8.nq.gz
    ├── 0b8341b6f08a588bbaccb84480e324612b426e31.nq.gz
    ├── 0b83bcab826674f9a6a3282d50bf6879942cc1a8.nq.gz
    ├── 0bfbb6057fe2939f5c7b9d8ec47423e71c422bd4.nq.gz
    ├── 0c1c50e4fb2481ac049402375617903d56b37126.nq.gz
    ├── 0c246d2fe0d7febd5cb594f69cbb5160d59b703b.nq.gz
    ├── 0c997050f32b885c6105ab16fa3efffae2a41232.nq.gz
    ├── 0d19e8edced7bb7898dc4d7abec315248809a2c7.nq.gz
    ├── 0d75b0b6b2d5aa0bd6adeb8dd29fd04ad199865b.nq.gz
    ├── 0d84ab03b696c9229f283c10145b183639864cfc.nq.gz
    ├── 0d8a23f497956eacf80dd4902bb29e2ea3dc7dc4.nq.gz
    ├── 0d8c45bc6929e45660f93031801e075da89200b7.nq.gz
    ├── 0d96c5f2f6a12efb8cdeeddbd8864c64dc64f800.nq.gz
    ├── 0da80367492562ebaa1e9219ea6491321a5c703f.nq.gz
    ├── 0dc9004aa72a28e90005d17f4a4556ebc9e0fc3d.nq.gz
    ├── 0e70ccf2a19024f2d25800a22c164b074d3a72c5.nq.gz
    ├── 0f17968da7cccc5d58d8686dc2f2ccc07fee3619.nq.gz
    ├── 0f6bac27abcf320dddcbb294b2bbf9d39174c3f9.nq.gz
    ├── 0f6e732e95b407a7a53541d132fa347f94b318ea.nq.gz
    ├── 0fc4ccd19217351f15ea0c6ebe849c0b02bc2b8a.nq.gz
    ├── 105d348c9f67340dc8d8b9b979ef1a8fb762013b.nq.gz
    ├── 109491eab3c5cd91f38577f7f6a6516b598eb564.nq.gz
    ├── 10fbde1b230b084ca199e9138295bb49236db4aa.nq.gz
    ├── 123db0b6d1f20a1d7c5afa57f61d96fe006828ba.nq.gz
    ├── 1257c2c11adbae343c50293e98b4094d29c517e3.nq.gz
    ├── 125ade8b131daceb2227c8c114510196527508a3.nq.gz
    ├── 127b9cfde90d7452784bfaf2a19d6f8ea26e316a.nq.gz
    ├── 12de1a7aecf3999934b0659d81f0d236e964c1cb.nq.gz
    ├── 12ea5013c9dd6b5533dd7a0dad9ea41e6997b5e8.nq.gz
    ├── 12eaf1c7f086607b25c0b556647787a6440ea8eb.nq.gz
    ├── 13142dcad63dd00ef0a778de1b7d667dd3216f21.nq.gz
    ├── 131e07fef4be52e1c35691f25a4ef1c6da6c23f0.nq.gz
    ├── 1320bf023c5b1e9f174811a542b56d26bae5746d.nq.gz
    ├── 1350d8b21e6da5e2bdf09f163bd2aa2b945e2d3a.nq.gz
    ├── 13b560db9397314ab09d1c9410c01d114ba65ea6.nq.gz
    ├── 13d471c04375a4c100323e46c10b5aa7556a9bd9.nq.gz
    ├── 140e5b945d70dc6162e310a55f4834d29f94f95e.nq.gz
    ├── 146f87be43256591230b4b3f352a3a05e4b76e0b.nq.gz
    ├── 1478dafd8ecdf6888164a13ebbfc3356c0ee9c2e.nq.gz
    ├── 150202fae3ddbbb2cd0f0cd0b33b1461f795c2af.nq.gz
    ├── 15430af1ac74aa0635a5e4cd99e5493b32fb5897.nq.gz
    ├── 15b0bc6025192a2d1e7d712b91a37950aceb3b69.nq.gz
    ├── 15b31bfe6c9ef1a441dc93f17e05baab4f5fdd03.nq.gz
    ├── 15d63e8b8f1c0b805df0e860b7a86e575383e9c9.nq.gz
    ├── 160c16cfadbedcb76e7712803d915e3f950f8d97.nq.gz
    ├── 16103f51acba782b866cbef31594e1d5e59a658b.nq.gz
    ├── 172436256da4d9a1e9f252e9a98aa666c8719260.nq.gz
    ├── 17348dabf18df3411867bbe2f4a4d891273efba6.nq.gz
    ├── 178ca4be337f0755582b730d038a4557000b4fef.nq.gz
    ├── 1827454f52cba20ff0617d3bfd1f335b32256a6c.nq.gz
    ├── 188eae36f6289fe803432bf6de4832e7d395ea97.nq.gz
    ├── 1897152e71958ed4ba7826552e6fe81e8265c8e1.nq.gz
    ├── 18f684bd3cfa2495c24385d8064c66ec9a64d606.nq.gz
    ├── 19ad5dbfbd255dde449caedd63d4294621db69a0.nq.gz
    ├── 19bda2bb76ce5a27eebaea70812294a7cb585693.nq.gz
    ├── 19e440ebc3eb3dae608956ebe8b95338260ae6cf.nq.gz
    ├── 1a2907be4255cebe39a23ae0bf2d421c93979839.nq.gz
    ├── 1a4280e9fa5e7a0de79db57b3ca9a0ed67b199de.nq.gz
    ├── 1a5f6d0c817c40d54d9dbb702e42bfa0d29ee5b6.nq.gz
    ├── 1aa0c7a159aaf46650862075be0150e8a3513441.nq.gz
    ├── 1ae9b51a691463abd569a795a32480b7eec33f1f.nq.gz
    ├── 1b0160147e640d56bced4acfffdbb11f2e0cc270.nq.gz
    ├── 1b1c45d682d4b989d4738d46407b408615c1a74f.nq.gz
    ├── 1b1cfc15d190f4ec5f6b1794ad8da9ea45fa0a44.nq.gz
    ├── 1ba50a616b7c371e96b5f85bc177f5557bc69763.nq.gz
    ├── 1c263878ff4e273dbeed0b93444055fc75ccfa69.nq.gz
    ├── 1c31e4ee4e792c2f44f18d7d592c2843e7166f39.nq.gz
    ├── 1c4cbbeb0c9f457d871d8bb02f57b40ef20b9c4a.nq.gz
    ├── 1ca2b861ca9a40e76df82609f4da92ae499882a1.nq.gz
    ├── 1cf0edad5bd77bf170f8775393a64b1e1c986fd3.nq.gz
    ├── 1d3e7900d360a8823450f0963f55e97e9d81b631.nq.gz
    ├── 1df3b28b8a2980d263b49799944f0b569748ad29.nq.gz
    ├── 1e99c0bcb7deab58338a7d0f3fbab2a9a164d87a.nq.gz
    ├── 1ed2ee9a1412f932a5698b0b4c0019db5afeba86.nq.gz
    ├── 1ee702fc51b830671f69a07ebf0c82d75b19672a.nq.gz
    ├── 1f04bcaa66fc4f6bf65a2d0b98ed8f910e7811bf.nq.gz
    ├── 1f4290552bbd12fa22b4381ed91259eff41ed543.nq.gz
    ├── 1f4ca6f6b3a5b9c1d29730f222ecd09d75eb2a57.nq.gz
    ├── 1f841cd4e3c24eedd1feeed880e03037327a673b.nq.gz
    ├── 1fcb8930f5db762d7946930985ffc5966bec9659.nq.gz
    ├── 1fe6f9b2b87c5e2e2b32a3766752363bcdc980e1.nq.gz
    ├── 204ca5c902b5d08eed02b41bea08bc73ace30596.nq.gz
    ├── 2051d45596ba4ce7211454a6dace7168e4a59bc4.nq.gz
    ├── 2067b301990166c4ca36a7c5acb139426cef1156.nq.gz
    ├── 207d0e3ff20f150d040e7fac0a7e05e9b88f2051.nq.gz
    ├── 20b4683ac641c3f37ff133d42de8fba46fc452d5.nq.gz
    ├── 212e580c882c7777da16379ed8129380eaacbad9.nq.gz
    ├── 21551360de8f319b6c83c05d4b6613e0b25b1309.nq.gz
    ├── 21a0401e57902753082c049e760fbcaad7510635.nq.gz
    ├── 21c3cb4578b64591c3b51d081288f33baa316c10.nq.gz
    ├── 21cd480b506c59e7a389547b83d5d88870128c95.nq.gz
    ├── 21f5f551eb18e634fb66d0f2ef91a21491e1cf46.nq.gz
    ├── 2200a599fefb83d90cf99544d5306cc2c18d6ae4.nq.gz
    ├── 220462d272dd021dcfef674a491965b6175968c0.nq.gz
    ├── 224f1320239dcf591b03b50705c0a97683ab2c04.nq.gz
    ├── 22e08fb8a2c88008b6023f9cfd33c3efd606094d.nq.gz
    ├── 23956cc78bb5ba0b666fc8b7537d5c204a28f92f.nq.gz
    ├── 23ae8304347997a87f1dd6c0b606575cea208436.nq.gz
    ├── 23be89f209f6b71758a54777fdd816beda80c2c6.nq.gz
    ├── 23ca8d5a442da4422d17928d1b96520d7305f5cf.nq.gz
    ├── 23dff69fb940883be948bb1f5f88e34511b64fa1.nq.gz
    ├── 23eccddbe81b0685510b5898126c570a156428b8.nq.gz
    ├── 242e1b109a40d9088a6802a61416cfddaf4ffadf.nq.gz
    ├── 2478169efb7dacefd6259fae0d16ef487ae8f55d.nq.gz
    ├── 249ae84a0080c3dc22a1e38a057b782dd0d9a9d8.nq.gz
    ├── 25535f5d6b415316366eb7b460f7182371f08743.nq.gz
    ├── 2558875028c9544e61613f99403e4813e851e6a8.nq.gz
    ├── 25731982914e24b45379f580fb9b243df14e111d.nq.gz
    ├── 265db80c16a3da7bf2bbc40f600a0163100d5538.nq.gz
    ├── 266c1de7ea4d4a26ee8d54469509e99dd9d4f531.nq.gz
    ├── 26abffdb78840729fb094f833ce17fe523d3dcbf.nq.gz
    ├── 26e01a0ee15b88a04534586b2c6f802326bf333e.nq.gz
    ├── 270b3ce252f11cc1944d1c0d3c16d6cb8d3c72b8.nq.gz
    ├── 271b854b1fdaeb4ef10facf81d1184c04c49e2ec.nq.gz
    ├── 275bcc10623800cb2daf5f1bf2cd1e4672e2b43d.nq.gz
    ├── 27686ad2e59ae97fd0143d8e1a0e68f30aa3c272.nq.gz
    ├── 278eb8bcc58dc27953bdac18524c6b5dc72e80ec.nq.gz
    ├── 27c2c7dd015e848f4fdc5b55914aa03ffd7f30aa.nq.gz
    ├── 280f51667fcbfc2de8193ac76ebc38b32cdff7f3.nq.gz
    ├── 28656f05ce4763aa0d05296fa79c37a9f2dc5982.nq.gz
    ├── 286a26f37217cc3e97070e1d2464c4f6d179d8d6.nq.gz
    ├── 28e00ca39dd60725c261ef25c4fffda6656c0fad.nq.gz
    ├── 28e93b49e80fdd2bc4d4cf712263ad4d7f278c79.nq.gz
    ├── 293eb78b0acbdbb5bd2ffbaf096225f09fa8ff8f.nq.gz
    ├── 2953f1b445c29848d71ed1dc83df7e0b13664129.nq.gz
    ├── 29ad0153d83de1f97fe71654a15ff96956e3dd90.nq.gz
    ├── 2a0183bf4fe9d5a0bf3a7decade2764f8cde504c.nq.gz
    ├── 2a20cf9319eea81d1761b3ed68a4aeb56b390bfe.nq.gz
    ├── 2a266992fc1fbcd8318f8062c683ebea7b368a38.nq.gz
    ├── 2a477ea74795fb123ce482dc7d04feea842da1fa.nq.gz
    ├── 2a4b3ad8ea5ca82f7dc7aee0e0724e66ec66f1b6.nq.gz
    ├── 2a72b276b90a34b6037b265590afa5e31171572a.nq.gz
    ├── 2a95c30eabc5f2da03c3f0ded892d13c4dc6d1ff.nq.gz
    ├── 2ad35cf3c69ac62c46c4636eca3a122d30cfee34.nq.gz
    ├── 2bc0d3bb6bd43d7e6e8ece5c30962902d8e110f9.nq.gz
    ├── 2be8180c9e1a803176137420cb877fa21f8383cf.nq.gz
    ├── 2bf10d0ee6bd18a000c98d009dc18c04e7dd3e5a.nq.gz
    ├── 2c0dc80635c0cd583183eef34dd0c8b52a814213.nq.gz
    ├── 2d55fcb1d4fbf1f9798b638230aec693006541dd.nq.gz
    ├── 2d5a289329b929079cc82b017f8633ce0061c130.nq.gz
    ├── 2e2dd95ad2554ad72459c25471bf38f3f072a06e.nq.gz
    ├── 2e666b1c9c103ce0b958dbefa1a472abac51c265.nq.gz
    ├── 2e7cfa5f8468b3dbde59369c9b757039cacaed44.nq.gz
    ├── 2eb162b3b57a7ff35340e761692cd7c1c1d485a9.nq.gz
    └── 2ef93833e5de325c2598ac93963e7e8d2f446a20.nq.gz

9 directories, 200 files
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

## Source repository

[dsherret/ts-morph](https://github.com/dsherret/ts-morph)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
