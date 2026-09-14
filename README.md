# Repolex Knowledge Graph of handlebars-lang/handlebars.js

RDF knowledge graph data for [handlebars-lang/handlebars.js](https://github.com/handlebars-lang/handlebars.js), parsed by [repolex](https://repolex.ai).

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
lexq download handlebars-lang/handlebars.js
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dce542c9a660048d31f0981ac8a45c08b919bddb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── dce542c9a660048d31f0981ac8a45c08b919bddb.nq.gz
│   └── repolex
│       └── dce542c9a660048d31f0981ac8a45c08b919bddb
│           └── chunk-001.nq.gz
└── blob
    ├── 00095006ad5f706a9e85293b111a56b25c99da59.nq.gz
    ├── 01575a38ac6e2824ff1395b915c43cd81f5dcbea.nq.gz
    ├── 024aaae60f2ebbd964d31d97c21f0f5964a85f69.nq.gz
    ├── 029a25fba04d4380e1e2fab6618d31b383a2d826.nq.gz
    ├── 02f5be7b51578e7cdfaa7020eaaf4dd29c1fd0a5.nq.gz
    ├── 033e7b1768000096658cf1b04e04b19b693ca71a.nq.gz
    ├── 054e96cb810f65aa3fc62dd369fe7b40a2d961d0.nq.gz
    ├── 055562b771d889b4792b5b44fe4681fbfce48f2d.nq.gz
    ├── 06f26f3e6d64e4548a2cc903ac2d84c457c7b895.nq.gz
    ├── 076b25a8e865931da83cb619473cf79b9c9680f3.nq.gz
    ├── 084c070ad05c75c06c96f7639b83e189f3383f7a.nq.gz
    ├── 091f1b9158b52271934c203a0eec567b5275c0f2.nq.gz
    ├── 09cc7fdfdbc42dff81ae2c839e8257e2fa6c81e3.nq.gz
    ├── 0a6e4402425df4a6388e56f096e0150398beafac.nq.gz
    ├── 0ac38990e751ada6a71dca977cdf3bacd88560ac.nq.gz
    ├── 0d5105eb73794b7ab88a7c30502977d10a836f45.nq.gz
    ├── 111275852b7ec3a09f482196936b694df3337f89.nq.gz
    ├── 12d60c645504714ced0c6010f301af56d55a85c5.nq.gz
    ├── 14dd6176f6c7710d62efc44335e55e8d7f070457.nq.gz
    ├── 160b500b54017bc950c0d0c7bad70f7054fa5f67.nq.gz
    ├── 181b36e34353ea08fcc91e9463cc38f14f1e1599.nq.gz
    ├── 18807a7cd3d6c99070a03481407bcb4807034fef.nq.gz
    ├── 19b4e8c802ff5f51266fb8d33c4a53a0ad482c68.nq.gz
    ├── 1d1cd09c87464917ac25fef68921f55d35b63e8f.nq.gz
    ├── 1e003040a38f6a38a44672f39f105c1babfdb295.nq.gz
    ├── 1f4146ae014099a69e7a59b114e08a5d276d1d03.nq.gz
    ├── 20360570f6d972f759aa7c18c7a9df0a74b38bd1.nq.gz
    ├── 207aed30c5aadc2f76247e59333bfe6336fb9d28.nq.gz
    ├── 21b93aab91080a2867a5aa1202dd408c1996bf66.nq.gz
    ├── 252b8c267b097a66d8e753d69025d382b45fbc02.nq.gz
    ├── 265877f88fd6f72dd8cc38f4bdc5151fb9d94d67.nq.gz
    ├── 27033a1d5fd355cb8d830bd1c50cefdec7ceeb3c.nq.gz
    ├── 2795025c89ee79752e4510b0d1522d6a1a30bd0e.nq.gz
    ├── 28541b7767523a578de3c78211746b41f9f69f01.nq.gz
    ├── 2929870d9ee3d39fc94a7512db20c1bfda595098.nq.gz
    ├── 29d65b0339418516df0406b3c66c0f0dd505b604.nq.gz
    ├── 2aa7e39ffaab912c6566665dfe24d03ccd2f1376.nq.gz
    ├── 2ac72935856568fa2feea4a88e1981f48bc85fb3.nq.gz
    ├── 2bec356fe48c63011547bf455572de2a6819c12f.nq.gz
    ├── 2d54945c863607e6bf6161fb3327ee9fbf029fde.nq.gz
    ├── 2e4a1ff4d46f229ca9d622be733ea15173d9912b.nq.gz
    ├── 306207cd2af7dcf5c5cf66930caf03554352f7bd.nq.gz
    ├── 3071b22a4517a9dade6891ef1201f8fc841dc624.nq.gz
    ├── 336f1e6278e4dd3e9e44eeb33066c9297d9ba57e.nq.gz
    ├── 33bd2b11a88be606b16dccb6cd4b8e7dbd0e8781.nq.gz
    ├── 33f1a4492df744c66c9c1c338ae051e038786542.nq.gz
    ├── 344096aebce79fca56c6864fd6481371a38527ee.nq.gz
    ├── 370e157ec446315e68ecbf4d9f6d3fbe84940245.nq.gz
    ├── 3725e471c29bbc3f8bd71c416a6424b082531089.nq.gz
    ├── 39c522cad77f64831135186d13419cacdf78bbfb.nq.gz
    ├── 3a8ec2b3fbf30c606a1cdd6ca08b82d3f907791b.nq.gz
    ├── 3c4051cdf53e8212f8175dc0c469f1a94eab8cf5.nq.gz
    ├── 3d05b54489410a1ccd0033f510ffc1ebc407b9b2.nq.gz
    ├── 407b52c016777c154f534a7f132079f6625ba376.nq.gz
    ├── 41774b73af854f3b1bb4c8d901b5daad8a0c742f.nq.gz
    ├── 42198d829d6c5765a99d7e4ce81ad6f4a8f8c10c.nq.gz
    ├── 42fb55b48075b496495d0a7f30b6df1162fef883.nq.gz
    ├── 43e91d8d981222769038d3be5009de11452d978d.nq.gz
    ├── 44ee1223cb6c1ac0d38c5b44a4b03c8f7cb5fc56.nq.gz
    ├── 462b046f5d7c0c716ece6dac20699b1ea399b2eb.nq.gz
    ├── 46801942191f9607197c219e32e8a1c8aba9c4e5.nq.gz
    ├── 46c9cbe7c1e4013c29e3fe933100ef81fbc1cc23.nq.gz
    ├── 49655fa17ca1723642ed1b6db939f6e41b9f1d0b.nq.gz
    ├── 4a595344569f77e6645cabf9a1d45c44323349de.nq.gz
    ├── 4c5bfb516a79bf4a826ab3d0a2ee8165954d3f2a.nq.gz
    ├── 4c7afb70631beb9b94b7eb4294ddd3e456446afa.nq.gz
    ├── 4cb969d66d631d4bc2efddd88799a14b47f2d557.nq.gz
    ├── 4d9d5806f9ef816482de3000e1d7b8d8dfe1ea70.nq.gz
    ├── 4f3f8bfceea7d931d5abf59a34222cc830b45abc.nq.gz
    ├── 506a733f492935bceda80b1f44a53a5905e6e764.nq.gz
    ├── 511d366753c0b9aa70b3e0fe6e186f906106bd10.nq.gz
    ├── 5166d58d66e3d5fd226487a5ecbeb5624ba994c7.nq.gz
    ├── 5392fa30813af4cb160659167c6c9e03feab8e95.nq.gz
    ├── 545a479cbe753f42612e4deffd56a92eb94e2ba3.nq.gz
    ├── 548d7141938da1f36e7bf9e2a2de23db1c385024.nq.gz
    ├── 55241ecb7ebe018a5c2d7e477f9f2b46f4ee0d5c.nq.gz
    ├── 5620aba321d9909afd1545fb1ff82f4c93f3a83c.nq.gz
    ├── 56e9c3ad1ce6de8beb631f45b4506e478f07cc9d.nq.gz
    ├── 578738a89096bbadfed0d5503a3a9e863b42c248.nq.gz
    ├── 58aaae2861ffc83e4d3b00421adbe586d4851acb.nq.gz
    ├── 58dfab042e1a055be99f7d3a3d0dee089abed6a2.nq.gz
    ├── 5bbf7ee33f15fd7e86b836c529c93412f0f0fc73.nq.gz
    ├── 5c9e44a18c0737de15a9496c0e815f31aebee110.nq.gz
    ├── 6002c0ce25d82f7e595021da7741f4266f20b99b.nq.gz
    ├── 604aeb2c09fe3c7ece8c8136a4de80142bcf713b.nq.gz
    ├── 642a9ab0695330749095dfd69d003d8294f78c8c.nq.gz
    ├── 6593a6b7d17edc5b9996d96cd9386e057fdf0d44.nq.gz
    ├── 659b53041b4e3b12017b76d09addd8d87b0ec7e8.nq.gz
    ├── 65cb33b71b7ddb4b08d2370265d3784919f45be8.nq.gz
    ├── 6b0cbdca683cdb9b3b35418e415367d0f24a8123.nq.gz
    ├── 6b0e94a74aeff839316229f8dff35b947846c049.nq.gz
    ├── 6c1ec732b271abb15773124c7ed04040e0274ade.nq.gz
    ├── 6e4aa20d6a7a31d1f4f791dfe1000cddf8094049.nq.gz
    ├── 6fa43b23cbce6d7f3684a4969be31c63248c0bcf.nq.gz
    ├── 736bd420102282a9f4fefaaa3e85d5f0e5554bbb.nq.gz
    ├── 74ab9d47b924c7d1f2737ce072e95dd6e0982ea6.nq.gz
    ├── 76bb01f1245f15f6a6a0a848f3560129e6454714.nq.gz
    ├── 7749121d388ffe77d3e9ae2747bc48e05da0f6d8.nq.gz
    ├── 788f9c05d1d39df5afb1281dd2c8576575d6a311.nq.gz
    ├── 79a9d7dfaafffff8f3e5828aab705ec187a182f6.nq.gz
    ├── 7ce7d70a1361df9cdb591863a591e0a831e92ee5.nq.gz
    ├── 7db6839838e3bd7b50a6ec8049a30452e12f31a0.nq.gz
    ├── 7dcde29e8f057d1f6c3a5a58132871a15d3b6bdc.nq.gz
    ├── 7e698a389fffded6260ff4e22a38fd56df156840.nq.gz
    ├── 80fb704a65ec82f8f6f0d5a40c2ff1a352bbd642.nq.gz
    ├── 825de237c11b0f57d6ec53619b73a382c7282dab.nq.gz
    ├── 834f4afe2104104f1d7b044f164929e0e6dccbcf.nq.gz
    ├── 83c53dad07686713f2825be493e74f450ae1c052.nq.gz
    ├── 86d4634d2a2a83a6382d3a4a3b5a3b718faa6fc2.nq.gz
    ├── 89546a8b8428ee3315116c8d4502de1bbc1ef959.nq.gz
    ├── 896c6a226fb2881ffe01c913077970a7b577d1fe.nq.gz
    ├── 8ad9a2415392d58c5b3ce1466db58e0ff3d81d8c.nq.gz
    ├── 8b1a14d8c88c4f53e56c5a0f2765eed0a503fc27.nq.gz
    ├── 8b4ea99fe5afbbf7711e5c655ff7be6ef6a10c5a.nq.gz
    ├── 8c0da5026d1f3dfde5d8bb6ba544cea58de9e488.nq.gz
    ├── 8c901b5f9b17e8163c6be7675430b5e85cd98bfe.nq.gz
    ├── 8e48fab5e5e094b33fbd52667c8e2b586d4d0086.nq.gz
    ├── 8f806f344923b342ceee93ba779b02170724dd38.nq.gz
    ├── 8f817ff48dadd8e8cc05829c4585e71e0b56b3a3.nq.gz
    ├── 91ef1da5920f986acd6fd7d663a25ae0ed56c928.nq.gz
    ├── 963eab9726e15b92150f0eb6935d171028419b80.nq.gz
    ├── 995469e0f08e6e081db8bc34869435504a15945f.nq.gz
    ├── 99b5bf785cd422d74f7755b1c4f03015b794e97b.nq.gz
    ├── 99b95069311e14c0ee48c76edca34d0f15876c4c.nq.gz
    ├── 9ad8f077534d2f878874047b5ded7e6516f12dd4.nq.gz
    ├── 9aeea9b97bebaaadefc73fe5090123b37bf59a03.nq.gz
    ├── 9c3af95fcbb417482da254b3d0a842198fc4f24a.nq.gz
    ├── 9c49f0cbd40c09fcdea4ed3efe78406db6bdd8cf.nq.gz
    ├── 9e425872f23f459042a7d4579b202306fef248ed.nq.gz
    ├── 9e9c9a16732240e3f13084f5fd644c3269436e1c.nq.gz
    ├── 9fa26f6b74333b7361810d44fcc3a9f778b1b8f0.nq.gz
    ├── a122f4d6ed26d1b8fea877fe65e8bbad7defcc6f.nq.gz
    ├── a484bf6b0186709c4a4e8fd2e4b949e9ac806f5f.nq.gz
    ├── a718ea388595619dd6af34a2e0c323d0735a79dd.nq.gz
    ├── a9ad6413d1ca5685cb98789f4c861046354b43b7.nq.gz
    ├── ab0d73646ec557184f233e08aee5e1314cee1f09.nq.gz
    ├── ad6e812aa5c82a322e5d825a7dfaa8623d465775.nq.gz
    ├── b1bb05e0ad1607bf09e459b43646eba2f69ae6fd.nq.gz
    ├── b2fdc00bcede7ff93c380ed3b18bcca86e63512f.nq.gz
    ├── b4014bb83ad14f6e78c93551a158514715f93a9e.nq.gz
    ├── b412c8c058c926b74ca498de8919ed340c8f7bb2.nq.gz
    ├── b7ffe711952f194a7f1f4e0655dda64e024d1d27.nq.gz
    ├── b9d48d491d5b6b6f5a183e1493fcd5ee788713d2.nq.gz
    ├── ba89d1fd76a22f37e56dd91f5fe5197302e4e850.nq.gz
    ├── ba9dc505b88129c87f226aa42ac99e48cbaef46b.nq.gz
    ├── bbf3bb81a384f1f0d7ae20b700ec9a6e8f81121d.nq.gz
    ├── bc411b250faaf61f2e71f10646f91d2f5efe34f5.nq.gz
    ├── bc9b0eaf4fc9155aa0d1e966720857139c5ffdff.nq.gz
    ├── bd4a58c9d6f26aae4b3b77183c8891dd9765ea88.nq.gz
    ├── bde617326bc3207130d59b3f3c3174a40927bdc8.nq.gz
    ├── bebb6ee0ed1b7f7070482d798d3e386c9df104d0.nq.gz
    ├── bef804d1ec199ec7b6e4fc9514065748d012858c.nq.gz
    ├── c11473844e54d8fb433575ba24105163d73c4e86.nq.gz
    ├── c4b9a27b75d8f398e70c55e7b164e32e6cc7c785.nq.gz
    ├── c4f8fc781a6b435b6aae20633f2b81eb73a0dbf2.nq.gz
    ├── c4f995657c4cd73e23b9b75cc26647b363937457.nq.gz
    ├── c5dc4271fcbe194aea8ad7c011c05c026f80f7fd.nq.gz
    ├── c61aa0f81ebc852a75390c9cb3ed6669b95e41da.nq.gz
    ├── c6fc8d8d9f39d079fc0828a5f750f955a8859a43.nq.gz
    ├── c73c050af2059b852d406de05ad5d1e3743a574a.nq.gz
    ├── c99cdf64405dd849d1ad1cad9d5dbeca14babe48.nq.gz
    ├── c9e965691f4f0dd764ff25ed34561e57ccbd8464.nq.gz
    ├── cab04c61a7b39367d865727ad62259bdead00004.nq.gz
    ├── cb00a651aeabfb0600092d9efa464fd9ead2d1a4.nq.gz
    ├── cb443f57d0c61713205c1c5317d7d238c53daed8.nq.gz
    ├── cd0f88b0f2c660863f03f8fd3c9a3b9181ed611a.nq.gz
    ├── ce3c32a7407d2b9f7a0bc4151a649dce90eb7d4e.nq.gz
    ├── d23f28ed68420d94c6844f8932101286a76de6aa.nq.gz
    ├── d29a179145ba1c7c12104529dc220633b4e1c317.nq.gz
    ├── d43a01e504a3a66adf10488586f43a86a3ff67f4.nq.gz
    ├── d51f2f1b9f1def94e36ab765e7fafaafd5c301d4.nq.gz
    ├── d77629a5210b951af9b2fe56ed6f05e745b8e50e.nq.gz
    ├── d8730b6c7da9cdbe4e1a24bbdfbb95923dde4dbb.nq.gz
    ├── d9d5e8a962bd91094db42fe3f29fc734f490371b.nq.gz
    ├── d9ed04116ee2643291db063b154245b7695b3ee3.nq.gz
    ├── dabf8043e6311fae0569c550fae528832bc7f285.nq.gz
    ├── ddf07a6fedd55953f13d55f9b0d3a076eb3d928f.nq.gz
    ├── df092267d80e69239593846021f75d880324c462.nq.gz
    ├── e087806cdf5fb76f5a2fb528023638ff28a21e17.nq.gz
    ├── e1e16f6c2963192b4d5162c2a7d269d27c0e02ec.nq.gz
    ├── e55ad83c93bae476b195ecb89d7c3fb2412a0ead.nq.gz
    ├── e5ab9c5817d45b74d27e04769d4dd2e13bf2ea17.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7b2355ac2ae5686f722e2d36b29e7f9579e5239.nq.gz
    ├── eb1cf1a90cf06b4018ba674b0d4a777248895b76.nq.gz
    ├── ed16660387e2a66208112f19bde22ff14141e4c6.nq.gz
    ├── ed2dc8c56fc29d16ee2c4bc07d97a346f04f0b75.nq.gz
    ├── eddc10dcd1249910d7e62089df3bc22cf7c120b5.nq.gz
    ├── eeda54e2459c452e9d607f8c8201fabe5eff2dc5.nq.gz
    ├── f156554283260ed2797035ad77e04c33ce5c8500.nq.gz
    ├── f473863aef0b453b57ba7d604fb5b31db21c8f3f.nq.gz
    ├── f4a4e3e4fe0b3bb44df3317877287612c08b51ba.nq.gz
    ├── f516eb2b4f7c7c89bb82492ce1bf7629b1a6a399.nq.gz
    ├── f534490ecbfa33ed391ba0f5844c1e5807171ec9.nq.gz
    ├── f73d845f8fc3502efdb90ac283ba3899714a0133.nq.gz
    ├── f74c83962a3a6a9f6bed4b8417ec002f98d72b38.nq.gz
    └── f826d95a1119d7b8fd2c828a5df6811905d47773.nq.gz

8 directories, 200 files
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

[handlebars-lang/handlebars.js](https://github.com/handlebars-lang/handlebars.js)

---
*Parsed on 2026-09-14 by [repolex](https://repolex.ai)*
