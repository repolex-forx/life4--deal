# Repolex Knowledge Graph of life4/deal

RDF knowledge graph data for [life4/deal](https://github.com/life4/deal), parsed by [repolex](https://repolex.ai).

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
rlex download life4/deal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 751c0a7ebdf8527c8231b15038e4656d2a6a75c6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 751c0a7ebdf8527c8231b15038e4656d2a6a75c6
│           └── chunk-001.nq.gz
└── blob
    ├── 00478722206a6681877e15a84d3d56659ae3c60b.nq.gz
    ├── 019b5e8a3cba8c1a9a971849e6f4b177ee8d5491.nq.gz
    ├── 032ea1c2ca975af83f63006a0075411c73cd5044.nq.gz
    ├── 03a15fefcf73d4eb21f5a38ad19111d52f71b23d.nq.gz
    ├── 0451c510058c6cd00815603de5fad6117bf0771d.nq.gz
    ├── 048fbcc891f4ffc13b2e1b2ddf7233f3bc026dcf.nq.gz
    ├── 04a401c0286149c061a691399855e5036e89daa5.nq.gz
    ├── 054fd14caa5c103bff2b3c48833e5b5e78b445e8.nq.gz
    ├── 0550fba78c104014da78d1661c529a09cd9b0c05.nq.gz
    ├── 058cc7be2c34b6da902600fa2c2f54f514969989.nq.gz
    ├── 062edb6df19d96a58af7f45e62d29ed28def36c6.nq.gz
    ├── 06666f33992e25cd6dc3ac1a0a2e6d916bc2851a.nq.gz
    ├── 080ba4f79bd22af506f1b1f46833e6e8f5b55557.nq.gz
    ├── 082a4890867b18a0a32894177278bda7e8111db1.nq.gz
    ├── 088ccd9062711268031683cb4a4b116502dc6843.nq.gz
    ├── 08aa8df35f533df3509fcd29c533b35efdba49ba.nq.gz
    ├── 099cd1d7e822049195a1a62d816941cd0607a3d2.nq.gz
    ├── 0b20f90cdb9bdd84fe5cda89f1ec214f979cfc58.nq.gz
    ├── 0b53ffd7bd3ac8bf25aa628019f5b0bf60381ae5.nq.gz
    ├── 0b576676fc90df5a724c7718ebe44a753f78de95.nq.gz
    ├── 0bcbac9504b2ec4ab032c17a823f505ea7957076.nq.gz
    ├── 0c0a7f25f1a04940f083884423ac8e8cd2df93ae.nq.gz
    ├── 0c391682224083831564f862963b2e4c63398a71.nq.gz
    ├── 0dd69af2524ca5be5a221f325f0cc2a9464d99b7.nq.gz
    ├── 0ee95334b5b877f866dbb8fb75e86bd73adaeb1d.nq.gz
    ├── 0f85acc0c011d410071fb948842ad73b4a7125f6.nq.gz
    ├── 10aa5cc844b16908b4f76cdf0a8d71829705f337.nq.gz
    ├── 10fd66aef586c37349bda21a659f4c498c99e549.nq.gz
    ├── 110069987abf2904c233aa6ea37500a275fc10de.nq.gz
    ├── 1130d1541a9ca3465200714e2291f8da439c83ca.nq.gz
    ├── 12bfb80b4ca82c83b517439967aa2ec9dccece9f.nq.gz
    ├── 13188c745ae88851481e2a027e4fedbc1f69cd26.nq.gz
    ├── 135d50e25d514e85e9d37ccc004df8194f8680b7.nq.gz
    ├── 147e7f905b1fdc3d7713f764118b52565c02dda4.nq.gz
    ├── 14e74fe4b76f0a0c906ecac39a666a5984a2b60f.nq.gz
    ├── 151042002e5c2a755c2b42588073e79d158ce844.nq.gz
    ├── 1582094bf9f316fe3a6462e509303530e734c8fe.nq.gz
    ├── 164e01152547d7c04333d4422d71ffde5e593be6.nq.gz
    ├── 17a5fd093f2b27443c79c11461ebce3429a15dbe.nq.gz
    ├── 17b51277a91570a5040d6a53b2ee888d1f1d8cea.nq.gz
    ├── 17c98fab48f586b85a4a8aaca79d0b6553bf88be.nq.gz
    ├── 18007c1ea67df38b1eb1cb873a4fff63f812f2a5.nq.gz
    ├── 1847758b718b441e9c45d3250781a3be24d32b6b.nq.gz
    ├── 18b9fdb309d3907b1fb836e8a8fa5c6854cb3789.nq.gz
    ├── 18bbc0d271f0cd13a752c3f9ba539d67347adcac.nq.gz
    ├── 1a049a140a464d37a9ae33624d0890c72324bbbc.nq.gz
    ├── 1a1362bc65723e5f29a277b91d3d4c6347c95d49.nq.gz
    ├── 1b8fa6aa6e4835e87acc96007592bcb39792d103.nq.gz
    ├── 1bbcc20c4e2e15383be16d32600d975c112315bc.nq.gz
    ├── 1bc67c4d432dd9e9371d1a331783d192c61bc406.nq.gz
    ├── 1c0c180ebfa32cea7578510bd32c2b507b194c15.nq.gz
    ├── 1cffa01c7260a9e1fa2dae6a3168d72676fefd61.nq.gz
    ├── 1d8d244be2b76bcff300ded9e37fac74592f1339.nq.gz
    ├── 1e84e9cc338b470f37ce6736f5953e022a3499ae.nq.gz
    ├── 1ec9c132f05d1d80dfeb43adcc13c55135ad2796.nq.gz
    ├── 1f2f8b4065b38a31f4e13db93a6814efe0524b7c.nq.gz
    ├── 1f4652e89fd420e7a9a7f84404198fff83d2ce95.nq.gz
    ├── 1f99b0227afcfedcdb78a25363e5ca0b92b6a2ab.nq.gz
    ├── 201de5e9617f8d87c547c971ca72f72000919f00.nq.gz
    ├── 214707adf0444652523aad902d41242ecfec2138.nq.gz
    ├── 2164680d9547f837a6cb65bd9c45201ab058ffb2.nq.gz
    ├── 223d8a3e2985debc194e1a5d00d989cc406541cd.nq.gz
    ├── 22d93c3b15967dbfd1ce7f6037d5f9ef9662bff8.nq.gz
    ├── 2457545937b53ed1656e7e3cb4b1162e55de597b.nq.gz
    ├── 24b5961da26c5d6651a9bdc5d7c89187c800dcb6.nq.gz
    ├── 251b577edb57b75aad7459933b6d5a00a2732cf7.nq.gz
    ├── 279c0eab28ae7ab3049c75312f5558e3362dea49.nq.gz
    ├── 2822bb50e65465f111d3c5b6002e7e5dea55f17e.nq.gz
    ├── 28e882bfeb7f9e671510f26513ec7e610a689266.nq.gz
    ├── 292e9be326d863c32c2f3ee34b47f0d33071902e.nq.gz
    ├── 2a9bc1dce3e3b50a40abac7add0b4d5dccf49b0c.nq.gz
    ├── 2aa04791476add7db34f4f2c26dbde75a61f2e3b.nq.gz
    ├── 2ad040a455cec24fad39deabbb65182b68507acc.nq.gz
    ├── 2b2c0a8dc6d947147701075f34b35bd4d42084dd.nq.gz
    ├── 2c20728ae03764d95412901d22b3e7994536f673.nq.gz
    ├── 2c7d6f83a5b8e54e0ecbfb93c1752d8305052f92.nq.gz
    ├── 2cd38f7b151c8ffba6a17f6ad8e000b2e305f485.nq.gz
    ├── 2d7d7b3aaaa12f249ff2103d29d5f4cab0ec822b.nq.gz
    ├── 2db294910bedcc195cda24aa6222c5b9bbbf9484.nq.gz
    ├── 2e42398e989d874aaa03018a4090423544620104.nq.gz
    ├── 2eb8e69e29b6926901c93893d539b89961dbfed6.nq.gz
    ├── 2f2595bb20d9780eb95ab0b24a31d1b10460344e.nq.gz
    ├── 2f779bacdb091708d3510873fcd2ef8b03e4225e.nq.gz
    ├── 2fb0277b0634a595fa500308324ed490efc4ba05.nq.gz
    ├── 2fc77acd1d4599585fd1791a8f66b49ce4ba5c4e.nq.gz
    ├── 2fcb4b8cd29518e0ea60e2f5bbc954267ff0e116.nq.gz
    ├── 30087da3f4c78a0687e3d8352c3c6361731ec22f.nq.gz
    ├── 30a4e65576f63c8a389d883ac20e9f716b982bf5.nq.gz
    ├── 31109ce5541309329704197693e06ac688d238dd.nq.gz
    ├── 31a9ab1c6128a576e7ebcdc525b22e82064c63b8.nq.gz
    ├── 31f0b335793bb5d69c61a0dbc7d4746c11a6dbc8.nq.gz
    ├── 323fda56abba9c68668c8cb2fe5d1e19c9d66422.nq.gz
    ├── 326bfff0c29327fae4276338652034ab6ec667ac.nq.gz
    ├── 327133a4fb517ae60904145ca66fcfe266104f4b.nq.gz
    ├── 328186ad1333b34259d3bffc5ff99a7bd634b744.nq.gz
    ├── 3287e4f36037d9c37258a2b159a45344f08de902.nq.gz
    ├── 33662fa963b80bf43e181b3f75919ecf860d7532.nq.gz
    ├── 3380a5035b34e3101c5556a3f7250f41874e6805.nq.gz
    ├── 339f7f6096425c03969e522fd2d592c044ca716b.nq.gz
    ├── 33afd66c2806bce8ed30b5c74f6fe0a79abcdb24.nq.gz
    ├── 33ca5eb73b8c8d7d0c67049c4856000225d1a51d.nq.gz
    ├── 342709dd7680944043a62de5a245c82ff659a8c5.nq.gz
    ├── 347f49998e67e42186016435b131a16d01e4832e.nq.gz
    ├── 351b47ffd26269e6db4f46b5ac12970f7a33fa8a.nq.gz
    ├── 35b5ba2f9ec376398fac26c66946ad03bfad1bc2.nq.gz
    ├── 36135ba9732ba3c3d618d3776e2a9c3044edca10.nq.gz
    ├── 36178263363aa38ce8ed891ed7f0bf66e00b187b.nq.gz
    ├── 363a4cdda7688d7d5436d3aa7c227dfdd42cb554.nq.gz
    ├── 3714fb581e8a2802cf3930613ffc775eddedd3ad.nq.gz
    ├── 37c59bbbb564dfd6e686cb3dcc381e2d22973789.nq.gz
    ├── 37d68d94fc6e4909e5276c7f98761c13f3bd1f76.nq.gz
    ├── 3829d2ca59c816ccf9201b2af904734a89eb0449.nq.gz
    ├── 38476fb62ed0ff3dde870b021aef5822678bb537.nq.gz
    ├── 38c337afb6a7c276db22644c885b95bf892fbb7e.nq.gz
    ├── 38e211e0887466d3e75c72705b0b8d4465e8d89f.nq.gz
    ├── 397379f4540b647e8cfc18b47d2945dc988bac6e.nq.gz
    ├── 3a239ddf67e5d4e36d8dbe39b34087e0a8027c3b.nq.gz
    ├── 3b0c1c490cca4de7c6928315bc35aa3343fe6ab0.nq.gz
    ├── 3b1c3394ce918c56e10c856f4e7ffdcd1398cea2.nq.gz
    ├── 3b5ae0871425e7059ce90ed7c00c3dbed418e57c.nq.gz
    ├── 3ccb2f66e3fe600ee495ceb652f5a94cb03027f0.nq.gz
    ├── 3d3a9941cf4218f377f1a340e9b8013af81965cd.nq.gz
    ├── 3d59ca341bd67e023be9844d264cfb405425534b.nq.gz
    ├── 3e5d57470260907a4a17e37aac95704400496a7b.nq.gz
    ├── 3ee61f060933a812cd9e92c1852c32176aa6514e.nq.gz
    ├── 3f0283b9ec3fe98b53f7fedae55659f4642269d0.nq.gz
    ├── 3fb3fbfa536cf55708d3c643d6a1c9caa64b0eb1.nq.gz
    ├── 40051dff49bc0372b9fb7cd9604ee3a9befb875d.nq.gz
    ├── 404dc19113421d24d7bf3b3104123b65e556239d.nq.gz
    ├── 40c9bc3c33ad5206e1180ac78aa708bed2157f42.nq.gz
    ├── 40f08c30d322a38d825ed17eaa16e490c917ece1.nq.gz
    ├── 411c035ba445454a7e4ae7a48ef30dfacd199f2d.nq.gz
    ├── 414576547f56bdc683cd3184d51b43caaffa3861.nq.gz
    ├── 41e3f0b30427bc08100cda56ff3ba5d4da87ca3c.nq.gz
    ├── 424caebd0a3b8859d73c7434ec21d2b62e13e4ca.nq.gz
    ├── 429744d9195a17c2cafb10104e1591719dd5e142.nq.gz
    ├── 43c8089a12099f1cbd33193039c87e01801f5135.nq.gz
    ├── 43edbe280b3356711dbdfe86d573fff6e26ff702.nq.gz
    ├── 44034f495916fb53ea58bc7ba521c6eb3fa81782.nq.gz
    ├── 46ad66fa45bec764a5809703cda760e4c1b3d790.nq.gz
    ├── 47001d571f10c4987583c7ed5dfc2a3f7032ec4b.nq.gz
    ├── 47405bba15846882a45b0dfd0f646cdc8aff06f5.nq.gz
    ├── 480885f1e4ede594584977de4b0f32efaa7e675b.nq.gz
    ├── 485ded52f21f57ef7a01342d374f94b56813826f.nq.gz
    ├── 496a04ae110c451f949ca5f2a9d3d3bcb36155c6.nq.gz
    ├── 4a3a5269f82a9400285b8cf90fb512051ceb33d7.nq.gz
    ├── 4aa0f3773599cd21c679cf9c400a9c29231353a2.nq.gz
    ├── 4aad5f64cab76800809059b35eb26737e4257bd4.nq.gz
    ├── 4b083869d7028945f200b71d889acee7a0757e50.nq.gz
    ├── 4c9e48e10c31059726fac2264969a04bd3023aab.nq.gz
    ├── 4d084db3ab630a1b58edc4bcb573901cd08c113c.nq.gz
    ├── 4ec298932ad74f063cd84e2cdfb4fdffc51572b2.nq.gz
    ├── 4ed19e77cf47d8c3f115688b7f406e91a671b766.nq.gz
    ├── 5002a6327ec07138b93bdaaa3d35fc135586c4ad.nq.gz
    ├── 50eef91e45ede06c49477354d8d5cfd8836d92d9.nq.gz
    ├── 5106998791cf823d45eb435e79aebc0b107c352c.nq.gz
    ├── 51135c32feddbaa13bfc11876f27a23dda9bc555.nq.gz
    ├── 512c8de0c56f5158d61a590bc4935b7acf93c7b9.nq.gz
    ├── 514c7b25c8fc5a45a91e0443a812eeda62f3f98a.nq.gz
    ├── 516180d728be5c6b8c9a16303a77f6baa252719c.nq.gz
    ├── 51649c6a075f6a26b9f27a8a00493096a80932a4.nq.gz
    ├── 51db7e92b55920829d683f4cfa549ece3622f5d6.nq.gz
    ├── 521d1a1f574911cd9f8220e370820d9d37dbbb8a.nq.gz
    ├── 526ed5c8c94ea4c6c78d060c1943db3f40c1110c.nq.gz
    ├── 52fdda5ba670aef7358177ccb9a3fe7ce918ea6c.nq.gz
    ├── 533d13b39e563f09738e73877641507b3c21ecb6.nq.gz
    ├── 53dff1d259a308a2e16ca254d4f0db344e862f90.nq.gz
    ├── 54199882f81caae1a7141bae3ce683995ca75012.nq.gz
    ├── 54c6600d05f45557df9f515724a334ec22eab30c.nq.gz
    ├── 555a9711ebcab1127f22a3840419224276aa4399.nq.gz
    ├── 556a950d33efff33c6477f39b303cf62feed8e80.nq.gz
    ├── 55819c1e6f5a6b800a5b105c1ea1fa8c969a4aa1.nq.gz
    ├── 55c6ee7d0618e89bf449ac6b4d7e9d2f847a660e.nq.gz
    ├── 55e458ab84b3512d598985d741a03f7c85d1209d.nq.gz
    ├── 561570718757caee6db94ac948a3f0876be75e1e.nq.gz
    ├── 56405d8600eceed3a98b7a12194b5bdbe491de19.nq.gz
    ├── 5677e32492bbcaa024ac2416fa3eaca34633b1ec.nq.gz
    ├── 576367a5be2e1c3c811985476073e9ef174ed568.nq.gz
    ├── 5770d18c100d602f985ea551f47274f385867f21.nq.gz
    ├── 577f9bb38736d499a431f928f030682d0508728f.nq.gz
    ├── 57b8ef1991f27585a42745d05a83035848744fd5.nq.gz
    ├── 57e5b88384908d3112ec9adef36b8df53cee138d.nq.gz
    ├── 58daca9504ab91578fa47c7cacb3908795eb160f.nq.gz
    ├── 59406c79a78663deeaf7c17865b6c141e42bcd0b.nq.gz
    ├── 5a8124af3222c7cf19b07deb62782af428e75e13.nq.gz
    ├── 5b6305e0fdead4bb31217a8cca6a34367f78f080.nq.gz
    ├── 5b673f0847c19558a36c66ab196190d73ac699e0.nq.gz
    ├── 5bfc14bb6e4d1749279bd436f4abc11e57439006.nq.gz
    ├── 5c630be2da4fb40c843d26c0dc5a8ec23d15dc0e.nq.gz
    ├── 5cb3f3ce8f0e756aa3fb3a8f79df15b3efd4c293.nq.gz
    ├── 5d1f0af01adf5e0b521ee2a0b506b0d61c3359e4.nq.gz
    ├── 5d90dd033ca66ef3a53ad463d8661bb1971cbd45.nq.gz
    ├── 5da19e48e258a1709a784db347b77efcfe64aa13.nq.gz
    ├── 5dcf84cd3d642a49c2e2837b47b7ed0e62187468.nq.gz
    ├── 5f4ff9e0ca6a01293e243b87d8ecb0ca8caa1f60.nq.gz
    ├── 5f64a3a6441446ef9a5205397bf99f3fcd8b5808.nq.gz
    ├── 5fa36ec844e0bdff6c4e6c9276fef3bc33998fca.nq.gz
    └── 5fad7e5ecefe2beafdca586c791d08065aff6287.nq.gz

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

[life4/deal](https://github.com/life4/deal)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
