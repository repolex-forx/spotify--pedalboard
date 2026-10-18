# Repolex Knowledge Graph of spotify/pedalboard

RDF knowledge graph data for [spotify/pedalboard](https://github.com/spotify/pedalboard), parsed by [repolex](https://repolex.ai).

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
rlex download spotify/pedalboard
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 05e8f0b3c4851e77485d7e842dc0355b44106471
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 05e8f0b3c4851e77485d7e842dc0355b44106471
│           └── chunk-001.nq.gz
└── blob
    ├── 0047400c3cf106190e7d861a5a342f033c147011.nq.gz
    ├── 00c12fa1a0fe269f917920a354137b5b3c8902f9.nq.gz
    ├── 00de79c016719f6027c4e6ce65c2c83a487a4e64.nq.gz
    ├── 00f1fbcc7759ca6c1933a09fb109e4f6ba5044ca.nq.gz
    ├── 011f1f452b7926f878a16ff0a21bd6fccb7ec1be.nq.gz
    ├── 020488c3e67b80d37ed1267dc68f714e67984c0a.nq.gz
    ├── 04564d97ec23fca351f5aa3cdbac2b96518d1356.nq.gz
    ├── 05fc51c96206575c7374aad4501dc57d7456f0fb.nq.gz
    ├── 05fe2e5cf98632831d07133a890a233dc39c6bbb.nq.gz
    ├── 068613188c0b4240a8836b76eacd67dbef0fa4e5.nq.gz
    ├── 06a9b0c2748f7fb018abb6b7325479b30b519b3a.nq.gz
    ├── 06ba91ced7039c80ed3efc23ca0cfcbbd4842efc.nq.gz
    ├── 077df765e40c27c3facb23fb2e77e4ffe244dbb5.nq.gz
    ├── 078542bd49b3a8e97b3d289558ceb91a4b70f229.nq.gz
    ├── 07cd3ff4064b61b7867a9abef2c54ba5b01b3115.nq.gz
    ├── 081a6c03e3380abc1c8e8caf5b1066ec733f3e35.nq.gz
    ├── 088ca3e09296e8de4bddcd12c8e27e6375dd8cc5.nq.gz
    ├── 089e950cdcf8c9c744b03815175dcf0ed260e786.nq.gz
    ├── 0963707fc93a7a1e26ddeb355f701cf7d33ebf33.nq.gz
    ├── 097d4b51f4b4624741f2bf67ba880ea66e1c3f1f.nq.gz
    ├── 09df3e2f03361c625ed1cd108a141dd53d73765f.nq.gz
    ├── 0a067ac5d0ed0ef33d36506ec0e53301025f2873.nq.gz
    ├── 0a8c024e9513e8978d46eda09754b83fc0bd5353.nq.gz
    ├── 0aad7aa04f8b132268d7affccdcc40e028aa628e.nq.gz
    ├── 0aeef6ed21cb54a480db53b864f160ee420eb4d8.nq.gz
    ├── 0aef2a073a929bf9a0281dded635d8e47b979974.nq.gz
    ├── 0b05fd7bcf8f853c4703df5f14858ecceb52502a.nq.gz
    ├── 0b71fb67b655f55e3a440017e360c5600632656f.nq.gz
    ├── 0b8510ec95b322a56f61a0ae7fc80cd567c385a3.nq.gz
    ├── 0ca5aaaecb554aa9c98ca8b6022dd6af1e598c1b.nq.gz
    ├── 0ca86d65e41cb9650e37d3d37b9bb6ccff638ebf.nq.gz
    ├── 0cc468621ae3b19004c5f25417591cdc1e66438f.nq.gz
    ├── 0ccd974f9695266f5d7b090e82c0021c10cc7f28.nq.gz
    ├── 0e34556fbcfd85c94e0b817f03cb0609d6085c0e.nq.gz
    ├── 0e8cd84c6078a0dfca328ec118b9b18dd1886bf7.nq.gz
    ├── 0f18e1920afe54aef7969c227f9d3b0b0f93aa1f.nq.gz
    ├── 0f459ad471bb46849c34769007b37f46842e1c33.nq.gz
    ├── 101e8c140d34b816e04ef7b19d6ea5fc0fcb0236.nq.gz
    ├── 108fbfd8d2d581ff575c578f319d415491b99550.nq.gz
    ├── 10abcdfeb3aa5c908a782e6666d522e6fff2f85e.nq.gz
    ├── 110edaf7f422c47b7de401884031af1e319b1abe.nq.gz
    ├── 114f68ddfebf6a3a8e21969f0e7a5a7471292d2d.nq.gz
    ├── 11cfa44c545e0354ab6859d5c1708ecb84e4e4c1.nq.gz
    ├── 11da942165992e73de83d8d99eac12e50f28254a.nq.gz
    ├── 12447f577140b218de8eb3a0b12d972490c27066.nq.gz
    ├── 12a622edf372feeb47f3e7e2417b2d275224232f.nq.gz
    ├── 12cdfc0c0062331b7f70db72ccca5085a0ec2e7b.nq.gz
    ├── 147f79be748c09517aad9d1805da82c51e0313b7.nq.gz
    ├── 148be7908fdf3c8ee4953fe267365ce183c7d763.nq.gz
    ├── 14acbcf0af1e98f3773fe912fb58b63aa8066a5f.nq.gz
    ├── 14ef27fce078bc4d1578e5b37062a83d33df14b0.nq.gz
    ├── 153320155427992bcebebe7caa27ab817b3d9304.nq.gz
    ├── 1564e5a9ab35b2c33aa20a3ddb09c8088e11bb88.nq.gz
    ├── 15ed9584d74a95f73929fcfe7f6034865f165972.nq.gz
    ├── 1611a3cff99db1503e07b7ce83d5475f69116499.nq.gz
    ├── 1645fc151f6ff2900addc811f119e7c90b9d575f.nq.gz
    ├── 1654ab5046c006bec0632a82a6fdd3a90857b4f4.nq.gz
    ├── 16ddc1eb87cdc13cd7ccf80021656c3b4c1f4ea7.nq.gz
    ├── 172cb83d2c846a146d8b03874ea2b5ca3b569ee4.nq.gz
    ├── 17b4e7fc8ea442e52336113ca22d140920ab4fea.nq.gz
    ├── 18ffa143e19cc56c65fd3093e5951847bfaa9e3a.nq.gz
    ├── 1986c5d8f51a486c3e96c8771d4feeaed1abfb59.nq.gz
    ├── 19a9cf67e42da04b2df57f43afbb667e231ff176.nq.gz
    ├── 19b33a8250d7a3b747f52d3069a42a8865d9427f.nq.gz
    ├── 19d5b6869b5edafa8d2eb89463eb65d9d6d50b97.nq.gz
    ├── 1ae2e0d0d948901863e588ef74168359c2480e03.nq.gz
    ├── 1b62f4d6e2882f9c6b96e02bc973ebeef234c99f.nq.gz
    ├── 1b8745d4bc925f524198ffc9d6530feb7f89eddc.nq.gz
    ├── 1c63608369a39d85228a16defc1414cf0119f952.nq.gz
    ├── 1c7d87e49f00822e73a6bcad01c74014baf403db.nq.gz
    ├── 1cf9ac12b1c4985355dcbf5eec8015a6dfa56983.nq.gz
    ├── 1db3c4883b16ebdadafdbc39e516a9ea2c8766fc.nq.gz
    ├── 1e2be9f9754d8c518596007eafc80ae83e530ec2.nq.gz
    ├── 1e8cdfc78ec6d0b8baac220abc77f7d3c0d964f9.nq.gz
    ├── 1f3f62a9b9792912238f109f2515a13d65250e9f.nq.gz
    ├── 1faebe47d2071c35bb7d4066c961a14b2a91572b.nq.gz
    ├── 1fbf436703d384ee3acf7e45942720bb6819784e.nq.gz
    ├── 20903b6cbdf5fe2ffafcd14d81f573b0424ee26e.nq.gz
    ├── 20bcdd4ea034bb63f9b3d8702161f59e6447bde1.nq.gz
    ├── 2126ad3ebc5aeb8266fa898fef87137757b8abd1.nq.gz
    ├── 21b26e311615ce7fa36c1f93ace8c3e77c27ad6b.nq.gz
    ├── 235fe8fcae27e8324226b3cd002f3b1e7e8109c6.nq.gz
    ├── 2362f878088cb8f4e650f408cc7c712011c1e550.nq.gz
    ├── 23c5b25155057e1ce3373b1085016d60091904c4.nq.gz
    ├── 23f28d423ebe14c3449bcd60ddf4b52b862e6c60.nq.gz
    ├── 23f76a0a1cbd98c1de5809355ac96a7318ddf71e.nq.gz
    ├── 243702b695f076ef6ddd4530bb872d80b1d213e1.nq.gz
    ├── 252617168ccdcdc7f4f1c6393ee004c767af525b.nq.gz
    ├── 2578e1a41a8f168d1995b7d4995b08d3f0ee1a2f.nq.gz
    ├── 260ee3292f1ed13bcbaeb5fcc733db23b37062d5.nq.gz
    ├── 26c747d0aae31271470e9b47460a8530dfdf0fc7.nq.gz
    ├── 26dbd12fec083d8846a6a00197a588113d6c1cc4.nq.gz
    ├── 2701b92f6e4ea398e0665ae4362d3de5a60a829f.nq.gz
    ├── 278646e02e19bbcac92526817515ba278dd1ce36.nq.gz
    ├── 27c805bfd9e55d22800ab83fe80979364fb6ac2f.nq.gz
    ├── 27f389f2237f0a66a9152a7938448aef13873ac0.nq.gz
    ├── 27fa32987967f1f530708277d307c4e80bc9f701.nq.gz
    ├── 28b1e337ab5e52ee1c0ad3c271e712c65cf65787.nq.gz
    ├── 296d534a041e15e185f32b4733872785e8999075.nq.gz
    ├── 298a9128ed85059469185083b7e14905d272f3a6.nq.gz
    ├── 2a2827aeae0990e7bc1cdea7ec9e0b2fc738cae0.nq.gz
    ├── 2a36785b0d7acbb0c09e0170b0ac37137f716fdf.nq.gz
    ├── 2a4f0c36cbee6a9a72b296ec568496f590793bc5.nq.gz
    ├── 2a86ef0c2ea77ab0af969036337ff39f13948ade.nq.gz
    ├── 2aa8eecbb515e96cda797471007fc4e6cb520dcb.nq.gz
    ├── 2b6069a373428e09ef8fb66d3ebb41b4cb3a7f8f.nq.gz
    ├── 2b67746baefe1393640b9c152357a7e901a07ea7.nq.gz
    ├── 2baaf5cfcc57534f71b7d4e75c975d5783d3b748.nq.gz
    ├── 2c6fd0ee8bca924ed3c39d8bb7f7ecff7a92e5e8.nq.gz
    ├── 2c73d936164280de785ce9c5d1921f4f30293754.nq.gz
    ├── 2ce26419bb27ee37a7421dd2e52a831b7abe78ac.nq.gz
    ├── 2d1162c7e8628f59db50d2b0dc3218baef967d40.nq.gz
    ├── 2d912f2d26632245f8d7e3f607916b37c74de8d0.nq.gz
    ├── 2fedddd40932c22dc490e026a5afc181ebd333fd.nq.gz
    ├── 30a3e09eb544eec78e6d3487638e210521dc0131.nq.gz
    ├── 312d4198292b43a21b71baa09c985b67f2d3f328.nq.gz
    ├── 315d74474f20039c631a4ffdd37af7fccdf72144.nq.gz
    ├── 318cd7c8baf45b4acb4e9a39eb40100da63b919e.nq.gz
    ├── 327e400ff3454f42bbd8db1e4b79ece028659ccc.nq.gz
    ├── 3283731ec0cbdc3dedf4fb1955b287e6706db23e.nq.gz
    ├── 328c0676681670b2d138260c2cef6973ee54a15f.nq.gz
    ├── 32a75b9737ba3c88b1391c7263368040631f0c06.nq.gz
    ├── 339482d4e2eb1b2f3383ac85e8457c7480bbd472.nq.gz
    ├── 33b52fa0b4b1acd73d932583385f182481288c60.nq.gz
    ├── 340130c90d367c7de2a1ec2a42ac5a12eecafcf3.nq.gz
    ├── 344cf8f566801c1e3e1b22f9e6d80f623a350c87.nq.gz
    ├── 34a7ed6ccba11f6260d489d257332af13661bb3f.nq.gz
    ├── 35eea34d2fe535066ccd1c232d070a8ea8311283.nq.gz
    ├── 362016e92a443d57ab20fc0f543e7e5fc3bd4281.nq.gz
    ├── 36649c3d3cfebc7893bd46fefa5cb2f1f9b0173d.nq.gz
    ├── 36c333eb71a6941777ece4df63d33d5550702c21.nq.gz
    ├── 37a434b7b37cf33e6a34609a3d1ae34824c745ff.nq.gz
    ├── 3970329cd33e1d55d0d87962326f2297bd8d19a6.nq.gz
    ├── 3cb22346d103c5a05b961690549705cc99045e2e.nq.gz
    ├── 3cd24de6a0e68310565abc5d159b3a602e259b8d.nq.gz
    ├── 3cdcf067c3b3d0c6f5f36e36c7daaa2cdc7ff6b9.nq.gz
    ├── 3dfa81a57bab34037130d2f9ac6a98ad8ed8b805.nq.gz
    ├── 3f7234e22faeebef64755edd525f31633f8db402.nq.gz
    ├── 3fc26987a5f02ca48752c2effcd08ae12c8e423a.nq.gz
    ├── 400407725d937af9b661da411fe57423de873ceb.nq.gz
    ├── 401447b5514c38ffb75c402eaaa84202562287a3.nq.gz
    ├── 401732ce78b232f18dc32314837e03ae5876b47c.nq.gz
    ├── 40a1c1402c3a51b364b825bb471cebf8a2f87736.nq.gz
    ├── 40f364705b4ebc38e7c0eef86847da9e12e639bb.nq.gz
    ├── 411c28a2a06881e4521e9267e9dac91116ce0234.nq.gz
    ├── 418ee7d9a77c8b7c9b1cdc77dc924c21e0d3f35d.nq.gz
    ├── 41a459f823dad9fab41390d5c4de6fd0929f48ee.nq.gz
    ├── 43c4ee445e120fde41f3108c8c6b19e21f363ed6.nq.gz
    ├── 44237f1a755d24a3032b890e86d71281e347cb26.nq.gz
    ├── 4428660507b84d6b6650309f38ec1ea98cad9b32.nq.gz
    ├── 45c265671e79832f58d1f7e61bef083fd3e260ed.nq.gz
    ├── 45e99277273bf29114750dd4180e85ea07481432.nq.gz
    ├── 46ad6944d9e35d8690acd9436499da66129597c6.nq.gz
    ├── 471b8994633e8fcf0abd3241c742fbda950ec436.nq.gz
    ├── 481caab9c21c0aea95f8ebb4cd9aef7e78d1a907.nq.gz
    ├── 490553520586c8a6530ec66d214f363b8ad8d3db.nq.gz
    ├── 497f7b39d32568027c07b54eb5ae2c57d8076bb7.nq.gz
    ├── 4997b08e42b1201a5b8e35c6f572e624f2056ec6.nq.gz
    ├── 49b3974628f89dc87ab0e85e2cce8700f4e44ccb.nq.gz
    ├── 4aed421bd0104b7504e213f64edbdab9879b8f39.nq.gz
    ├── 4af4d553de19f94fae9ce25f1a9683dbee00c170.nq.gz
    ├── 4bdb1e5c11eef8caeb0ae388ce5eced1815e2a7f.nq.gz
    ├── 4c757abfa091b875ffca799f6618c199cc15106f.nq.gz
    ├── 4c786fc77b439ac80c818642c4cc224a8545002c.nq.gz
    ├── 4d22a192ebbeea7a067eb5803e0f4ceb9477adc1.nq.gz
    ├── 4d879dcf1ccaff79a162f95d18870104dd5ef342.nq.gz
    ├── 4f831533c8d76927614cdb610c6420371b467ecf.nq.gz
    ├── 5012c31063e91ba98098987e46073ebf11a6ac93.nq.gz
    ├── 503cb76602969238c42a39a749f1e62b4c9d1b12.nq.gz
    ├── 510cb7472b311f1845cc7bb6fc4da6217a79c276.nq.gz
    ├── 511b63ea3d270a5262ae01df97b4839e48ba8cde.nq.gz
    ├── 51322657a175b1a35b0ff2255afbc208b3135541.nq.gz
    ├── 52806f852f2d219f70dc6a50cc60c9f4fff657da.nq.gz
    ├── 52a5f9d43bc25889e90b98b004abb2ef7485cc04.nq.gz
    ├── 52d3ec3a40e8728e8f89d3e24f8e5bfff26f6c86.nq.gz
    ├── 53dfd9b5666321a03e9482d1fc4de4896cc28728.nq.gz
    ├── 54b5fc3e2ec8fcd2202d66cc67ce27ddf1e967a4.nq.gz
    ├── 573977f3b77ef933e08c67b62cdb737f705f2e18.nq.gz
    ├── 57f9cced1bb7627b680be312a4633bf7e1fd6476.nq.gz
    ├── 582e4b5d6f31095cd182f9652698a18bd3b166ef.nq.gz
    ├── 58b3f6bc633f6548f1a8ba3e2a727aeab867d287.nq.gz
    ├── 58e3c11eb7d3ac17b7aced2c9e0a5439216183fa.nq.gz
    ├── 58eb2aecb8c822907817de1f01e27d65ad2f543e.nq.gz
    ├── 595c34e911d04d3d500b89ff442ac25330023942.nq.gz
    ├── 59868eae0f85fbf3053dc7d06c0c9e203495f6c7.nq.gz
    ├── 5cc16646999feed6ccd28c2f5f5de813edc3fd16.nq.gz
    ├── 5d57044b7211c9323257604fb28466783d568b52.nq.gz
    ├── 5d78ee1c56de0845e714983eab0bb598449605d0.nq.gz
    ├── 5e12ded6e4603265875cec339a1ce8323edcc290.nq.gz
    ├── 5ef9a3e4df9f8dc85d3b23d3a47fec6a78d33d0c.nq.gz
    ├── 606d37477581c85cfcab5f6860a048164e88424a.nq.gz
    ├── 61d8f0570dadc19d9a9196ad8c087b269bf392b1.nq.gz
    ├── 6269a9ae67d2c1a3f3f1249e2f304d27324006ed.nq.gz
    ├── 6298d3c365d1c671a6d4f9295de0668e95bc8c79.nq.gz
    ├── 62d1541d993293ca1a030778e51c9589d0f1d76c.nq.gz
    ├── 6368eebd5f842cae2f401a84e8f378621227072a.nq.gz
    ├── 64171f9c6d0c746b06af495eef78074a45d9e5e3.nq.gz
    └── 644559698d963178c2cef75e724e0aa50e621ec2.nq.gz

7 directories, 200 files
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

[spotify/pedalboard](https://github.com/spotify/pedalboard)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
