# Repolex Knowledge Graph of huggingface/paperswithcode

RDF knowledge graph data for [huggingface/paperswithcode](https://github.com/huggingface/paperswithcode), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/paperswithcode
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 875014151b3864e5f97c626b2f8c794c86e30b04
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 875014151b3864e5f97c626b2f8c794c86e30b04
│           └── chunk-001.nq.gz
└── blob
    ├── 01793927f245e9043982b76d423b7dca9de0560b.nq.gz
    ├── 021aec61380379d70e8addad9b878e5bf2297451.nq.gz
    ├── 025d085d497d8eac70dd5c14917e2b2e8199f5cf.nq.gz
    ├── 028da4a165c44b0d4567f13e9bf102c0d59ac6e1.nq.gz
    ├── 047c92f6e2212473dc436020afed689527076d44.nq.gz
    ├── 058573efef908f82440db201591306df2e36e249.nq.gz
    ├── 05f3015513606f1701b9531507692b7adcce1728.nq.gz
    ├── 063ef26034456b7ab1198c82449c9f65716f002f.nq.gz
    ├── 068fd6f8a034e5650b7f5f40083d49b7c2287b7c.nq.gz
    ├── 0882593d43d0d019ed27d0479bb733d002f62654.nq.gz
    ├── 0895e4ecf4784960e087db7bec3989fb5304c39f.nq.gz
    ├── 091e35a2e3e396d7b02b5a92993261505be42c71.nq.gz
    ├── 095c7663845299465d327839eaadde5c9a7ef8d5.nq.gz
    ├── 0aee998bdaca2c55d19498ab4ca03c80e9ba5c79.nq.gz
    ├── 0bde3d1e9ae8a3833602f1df7acf5e76e8ff9d5f.nq.gz
    ├── 0bf71b1faa029f1d214d037812dc0d6c7851c300.nq.gz
    ├── 0c44a74e5316293ae4c7976607816d97de1f251d.nq.gz
    ├── 0cbc183afe18ec8597b6d23f601fdfc714f3e6cd.nq.gz
    ├── 0cfa736f7b3367edfd84c8aa57d2c462f9bc7f96.nq.gz
    ├── 0dfd6eb29da9b09f240258bcbceef42e105de63b.nq.gz
    ├── 0f837f8a03ca9af7587061db4c84a6aac50f4e19.nq.gz
    ├── 0f86b0a24aef554bb03eedbd91ab5f4f59cc6e2a.nq.gz
    ├── 106c1ee174c28a87f9afcfd4e72088ad11335bdc.nq.gz
    ├── 1195ec9c1a5cd58c2a19f54ccee8284a08f54ddb.nq.gz
    ├── 12e18ce5910b73b90c6b9deaf472bd2d1f1ff5b3.nq.gz
    ├── 12f01fa0ac9f1116448ce29901f16034a7edc85e.nq.gz
    ├── 13cbd595f4658f3b62bddee0f89b9cc284565a06.nq.gz
    ├── 13d1ff22059f160d7e9d0b80cc4885edd98f4dfb.nq.gz
    ├── 13e1ad8db7a3617d5ed758454db47a8541001a8b.nq.gz
    ├── 143c8e1c26b8e6894ee6e365646ec987fb204095.nq.gz
    ├── 1491d356be9e393dd42ea8166d146798e61d6d69.nq.gz
    ├── 1506ffffe91cd3cebb436fdaccbfc29b18c842fb.nq.gz
    ├── 158cdb66b972122dbe3fcd65c9fbf7ef6fd3dde1.nq.gz
    ├── 15bf4bcb9762d2abd73e5dc1e37913a2e9937c83.nq.gz
    ├── 1684b02fdea4fc8cb621d20b79ef9be070ab6dca.nq.gz
    ├── 1749cb85597216fb0e8ddf5e7353042266135a94.nq.gz
    ├── 179f147bc947f98c8fdbb6372addcdb996c21aa6.nq.gz
    ├── 17ec6de438c105922b6f313c1b0801171caf91b0.nq.gz
    ├── 1859bcc4cc0ca1f619175ec8c93d5cc2f71dc03b.nq.gz
    ├── 186317c4ba14269d6be4cccf750d1db61e6f8ad3.nq.gz
    ├── 18a24ee6aaf9dbaed085d80d2e65fab1da229bb9.nq.gz
    ├── 18fa445d5c8ad18be5834bdb74da3bbc04c21583.nq.gz
    ├── 195ee280bb80f7d38052712aaaf51166d7aa39d4.nq.gz
    ├── 1989ba381fc30e01823e5bb19e1bff4a2a51094e.nq.gz
    ├── 19afed4ebca683389feed71eaf1ae73248e42bb6.nq.gz
    ├── 1a40d4dcf3b649db451e4e2939851a7a0df42ec2.nq.gz
    ├── 1a47a73b425af2494bf94d0b1fbdab7f19981845.nq.gz
    ├── 1bb51157574d16cb8c2d191da0514126b078622d.nq.gz
    ├── 1bc5c41bcfea7fb56dd8bb20f7750c6f7014e42b.nq.gz
    ├── 1d66db2f8c986b2193bca703fd82ee18f4a750bf.nq.gz
    ├── 1de7595865597841fef5961956d3b6f4f3fca530.nq.gz
    ├── 1e2d0207b6703850e7a32c0e9e60c72991a5ab82.nq.gz
    ├── 1e7c1a8caa71e6ce44ecaab5d6dbbb36731115d7.nq.gz
    ├── 201208d01e1c68e1562e32eac81c61ec68b2c8f9.nq.gz
    ├── 219d8f039089a0b874fcf259bed7b4898987f086.nq.gz
    ├── 21a8c3f6888b677d3b8f856d962ded523725959b.nq.gz
    ├── 21c1c854b4e3566fb82e5747f01378da19fe32a2.nq.gz
    ├── 2259ef212d677e331c6ba5beeb7a92e2794aa76a.nq.gz
    ├── 23bd246ed9da76ddf60d977ed3d43aff709832e7.nq.gz
    ├── 24541393611fded4239f5c4aea7407c5707b0b8f.nq.gz
    ├── 2554d5894d5aee27d41ed19715f54f0627b6f095.nq.gz
    ├── 26bbc9bd38e5372e00d1737b6105a84885a4f1cb.nq.gz
    ├── 288b7817cafe07f0c0491621fb588ee8ca394459.nq.gz
    ├── 28c4ccab0821be291c24a0ceff84ff282ad75afe.nq.gz
    ├── 28f3ee5ced783084fd129636f0351a3b6b3e8c02.nq.gz
    ├── 295945c7146da9facc1b6e5779d3719e9eef79ca.nq.gz
    ├── 29969b0f401d8345046058c137b388459b33cc09.nq.gz
    ├── 29e023a161da3c71ba44ca64050789faf0a003f1.nq.gz
    ├── 2a5c57fa30db0dbf81d7ce2215881ab73cfb8a95.nq.gz
    ├── 2a6d57c78cbefd52befe1e032241eb9334718618.nq.gz
    ├── 2aae48b346ab5996d4155028ff4ba56e23c5e896.nq.gz
    ├── 2b35ba41202f8974daed71621fb73a1ca2275a36.nq.gz
    ├── 2b572354e120c35994747974a76047537002adc5.nq.gz
    ├── 2b5d506b47a8010a09480cd3ca4de2bb5c9c8aff.nq.gz
    ├── 2b633597cfd8138844825c98713d15bba0b2be8d.nq.gz
    ├── 2b725e7772d770fa229f3ab71dd5e8ad5e4c7889.nq.gz
    ├── 2bad95de216314a647a6d77018190b818b9d6aa8.nq.gz
    ├── 2bd10f201432771c0f97319ecfb939a891b13ad0.nq.gz
    ├── 2f0ddaf611c4053f4f154dd89bdd201300f12d01.nq.gz
    ├── 2f1b193317da42fd2873003913993be30db4e0cf.nq.gz
    ├── 2f703b9e7306e231df85fa18c37c2738c7ef87a0.nq.gz
    ├── 2f89812aaa3993829d164b8507c67e84f00b53e3.nq.gz
    ├── 2fe44ef54793e5e60fae5bada765b3964a9a8b12.nq.gz
    ├── 304281107e97ec4c5d53e1d480fdc270363355a0.nq.gz
    ├── 30c842fdf60675ee0051ef24a6f3686bc25c3d6a.nq.gz
    ├── 30dc916b3b145a52307211f07a7efdbd0cd0bbfc.nq.gz
    ├── 31032172d99f470ac94c61769b1b5134f4108ea8.nq.gz
    ├── 31086d4b3ad4025851781ca316e5d9bcb8c0239b.nq.gz
    ├── 313b60e6b2fdb22284b7fdc9988f4e8cc9fdc3af.nq.gz
    ├── 3288ebb7d21a1b783e9f8b8e74f526146131bb4c.nq.gz
    ├── 331d7c2bf6b9734872c13fd765e6fd4659a24de1.nq.gz
    ├── 33dbb19935ff5fe67762b563d24d17e1ead77dd4.nq.gz
    ├── 33eb6494944366da4cfd8b0b7c636ceee0293cd3.nq.gz
    ├── 34a69c5f615c1d094493e47c426c71c39ad5fd05.nq.gz
    ├── 34e960121969ca231765b1183914dc8a8161b1f3.nq.gz
    ├── 351e54dcc90dfc89ae1c262350d3eb89273f4dd9.nq.gz
    ├── 368e430e1bc652907af916aca7ad7b585dff095b.nq.gz
    ├── 378fa540ca982b0e074aeab513632005d18cf10c.nq.gz
    ├── 38027495dcb5df7df1619fc09489a672b43b048e.nq.gz
    ├── 382ae98618f31fc523087a144c6dc9c3238b9bbb.nq.gz
    ├── 38dc87997527e9debb7b710d3d35f1e2e7f954ea.nq.gz
    ├── 38e8ac9e94fc5a65ee8a849b7bb12bdb73a16057.nq.gz
    ├── 39c5699e1b036468a7e8319d4dc866f5788bd29a.nq.gz
    ├── 3ae247db6eccf64b39987e64fcc55220bc01baf6.nq.gz
    ├── 3b65993780fbd0d745e317f2908a95eae2e116b3.nq.gz
    ├── 3b659d1404abc03efe375fd17d349b708f1e6c66.nq.gz
    ├── 3c51c22701427f8af2917b5a29f02e2c65df48a0.nq.gz
    ├── 3c5724e53041028613289521e8b154ecbd81610e.nq.gz
    ├── 3ca9078e9f83f2108e8eeab291166c56746bdbdc.nq.gz
    ├── 3cc120a957fe702d6bdb9368370aff1808ba5661.nq.gz
    ├── 3d10bccd7e29adfabb06e97c110603b803ac5c90.nq.gz
    ├── 3d6d091b4054d6a0bd596ef4fc0e13b99ad92925.nq.gz
    ├── 3da6d7b5a2e18d6541e4f1ebae95cc225107253b.nq.gz
    ├── 3dc49bbe96fa8701439f4a9a0f666f556a498f92.nq.gz
    ├── 3f5527cc6c3f6a22380f8e5d2f178c83612c1056.nq.gz
    ├── 3f94a98e44949a3c000e93f8d4c7c13589891147.nq.gz
    ├── 3faa03154739d1b79d2b80ebeacadad524aba2e2.nq.gz
    ├── 3feda24b336ee61016b3fb0f152e1b0a17b0acfe.nq.gz
    ├── 40df0ec50deac6cb8039f9cdbc5a3da17b0f720a.nq.gz
    ├── 411ede456eea1bb9c1859fe178699ebc0948f93d.nq.gz
    ├── 42321220d417ddd25bfa27e6f567f98d77bd927f.nq.gz
    ├── 42439b3f79302df2bffd2d812873ebba7fb7c890.nq.gz
    ├── 4257e46e7a7a022c6fb814123447c91992ea0107.nq.gz
    ├── 43e85f7c670c2ee71c9d281fe3b7a970669034fa.nq.gz
    ├── 45679ae0da4f5f0679a7fde57d81432a46bced68.nq.gz
    ├── 458f5348f7e42d45b31370c56142989cea5e1bd0.nq.gz
    ├── 46278777dcb315c6e43bac4644c7533e9e50ce87.nq.gz
    ├── 464e75a24a9dc7be42d2b5f33cd8d34d1653b0ea.nq.gz
    ├── 471350cb1140d80ed5269d14b0a5973f792a07b7.nq.gz
    ├── 477b7019f34ae7c98dc55494db15304ea9930abb.nq.gz
    ├── 4780af7b844a634192c7b21ec96098f87d4f4248.nq.gz
    ├── 47a1408529ccdcac64c8bef70eaa869cb5c32658.nq.gz
    ├── 48152335ad9c05b3a18ed5752cd3f743c5aedff6.nq.gz
    ├── 4827e4527847c1ec776e6af60cd2a73f6baed314.nq.gz
    ├── 4871ce157c4c012001e2f287dd21ea35e8c54b49.nq.gz
    ├── 488883d26045b8a6b3a0943b17239d57336dcac2.nq.gz
    ├── 48c5f9f1a696009c6317181c67d4317e39a9e6a0.nq.gz
    ├── 4a8f127e562503be6a0d0d6836aeb1551e3660cb.nq.gz
    ├── 4c581f888ab66a0375e9c3f4c78612e45769ce03.nq.gz
    ├── 4d2b467fcca8a2ff108427cc5051079dff2b558a.nq.gz
    ├── 4df103d4aeaf978a268538f74ab70ca1a6b9d059.nq.gz
    ├── 4e5f291065cb3981888f6669a604091de15b9e87.nq.gz
    ├── 4ee14ad9ffe5413381c61c0920a99b1e6545b3fc.nq.gz
    ├── 4f1568da549cd864c70c62fc9a0735eb2c836f4c.nq.gz
    ├── 4f1695fa91bcf15c18d2ec7b7ab58eb7b086ff58.nq.gz
    ├── 4f4c5d84361c8ef76cb744c46faf2da59c8a3b60.nq.gz
    ├── 4f9d4ec8108c5026809d8afc7f753c0a8f9fb14d.nq.gz
    ├── 50464edfa485817defdef4bdd32563b341ca552a.nq.gz
    ├── 50a358a811e94254efd823d244007b2aeb39efc7.nq.gz
    ├── 50caa3483b76377834a207ad1e5ceaeb763f1061.nq.gz
    ├── 51ff799f161d6b11cd603e00766d2fbaedcc602f.nq.gz
    ├── 529c0dc9c1748d34a870a81819e4bd847f7bc7a2.nq.gz
    ├── 52e7b3797517e54077d2ef20f40d2a00bb5947b4.nq.gz
    ├── 53492ba263f794f053e5cb9ea3c261b2dda47f4c.nq.gz
    ├── 537f4859e05acca3655850852478a0196c5fe631.nq.gz
    ├── 53e2193947275ef5addec1aa7e342e4bc0fb5ee3.nq.gz
    ├── 558ab05c0a9a8bb062ef4c51823d4d76c3acf7c4.nq.gz
    ├── 55dabea71ec6f56f089063fdeef567e5e2fb1a37.nq.gz
    ├── 55f6612058444ba0b0d0ff5054a0fd0b421e4318.nq.gz
    ├── 5628db0108c03748c61015e149fe69f23530a1b9.nq.gz
    ├── 563b45b23c43f581327cdd94e570248d0c7b84d1.nq.gz
    ├── 56b0dc5ce9a0cf5645fba612b156857710a9e904.nq.gz
    ├── 59092ced3becef756f9a72a66604531deba63582.nq.gz
    ├── 592d971c0d5b782a061164c8e763d0cfe1f1bdd9.nq.gz
    ├── 5ae6580bc3cb4a4e278756acdaf95ffb31ca96ee.nq.gz
    ├── 5b0a699ed72e2c7a6a1ae8c3dff710cfc5c78ac6.nq.gz
    ├── 5baab3885b73fd4e5f282f5b43ebf53293f3e0ff.nq.gz
    ├── 5ca3beffe416e4536d1d4913cb8eea9764e2dcfd.nq.gz
    ├── 5cb30090bba10f0efd2362d07f35c2f0dda12184.nq.gz
    ├── 5d97596afdbc91820c543293c8f90923e9c0c64c.nq.gz
    ├── 5e6e20e3c61d38e421ee975fa481e82c36bdd339.nq.gz
    ├── 5f58ce8c745b516070466c211f4d67b0da8bffb1.nq.gz
    ├── 5f7fc9b0eab6e80b7f83993c89d9cf1c697331ae.nq.gz
    ├── 5f8e13e0cbd36610f534248a8fc0d4b46448f1ad.nq.gz
    ├── 6025c96b93ab46dc2ad7e88b2cbe5b431c0a0fe3.nq.gz
    ├── 60f808c058ea2858a1a5fe7215aff94676416a42.nq.gz
    ├── 616825967f8b68fc255256fb405de66ae882c940.nq.gz
    ├── 628c844aa47bf916374f4364b8e98a71b979fbf5.nq.gz
    ├── 63246a920592a56e0df93ddcc6dd804d2422c772.nq.gz
    ├── 632e02c9c0f208395b386c5c3c9b929121377dac.nq.gz
    ├── 634bb8c33fe320379dea43c0dc19861ea8b312d0.nq.gz
    ├── 637450b209bd61e353101dc442c5b51ab37d31c4.nq.gz
    ├── 63d9e65d71283acdfe2153a91143644a61eeb078.nq.gz
    ├── 645c31702ef5ef4c2b750287e850d3c92de28cbb.nq.gz
    ├── 646c3cbe24e94a49b341359a3c48716f1d8c8341.nq.gz
    ├── 64aef1b853988fd5f3fadfd0a1f21b31d95be247.nq.gz
    ├── 64af0cab65433628038dc3d874bfae8aeca63364.nq.gz
    ├── 64f32f3adfbf2901d42194735955090cfec3fa82.nq.gz
    ├── 6509c2986141f2e54b6b1c00e88867c1ae519844.nq.gz
    ├── 65b3a402dbd09b8e83f9d637c6b553875189085c.nq.gz
    ├── 65bb147580c5a84ebb671fd46ce4cab373f0de09.nq.gz
    ├── 65c249748fc1552532068f0a191450933bdc7a90.nq.gz
    ├── 66566fc87bbab8c24af780d70f1bb2260148272e.nq.gz
    ├── 6750b7f124be311f4f34fea041b9f1b38014c3d6.nq.gz
    ├── 679e3916dedcce1d1377eaeb74e88b20488e02b2.nq.gz
    ├── 6844b4cc16544bfb1b4a3fcc1f21232b748e32c9.nq.gz
    ├── 69358bb2aeaf349ccd6de245abfdb48f03c30726.nq.gz
    └── 696a3ee8ac8fa591f997953ec52df90d00c4b0bf.nq.gz

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

[huggingface/paperswithcode](https://github.com/huggingface/paperswithcode)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
