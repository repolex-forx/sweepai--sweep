# Repolex Knowledge Graph of sweepai/sweep

RDF knowledge graph data for [sweepai/sweep](https://github.com/sweepai/sweep), parsed by [repolex](https://repolex.ai).

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
rlex download sweepai/sweep
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a8b8b67bda4f89faac9314d34e7c7d5a64f76046
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a8b8b67bda4f89faac9314d34e7c7d5a64f76046
│           └── chunk-001.nq.gz
└── blob
    ├── 001ef68f798ffe1879fd48ee50fc04ca19862065.nq.gz
    ├── 00c30bc05c7b31737d686e6d6752a450eaf7838f.nq.gz
    ├── 00d4b0d22570a7b53094c8956d41de4945f63753.nq.gz
    ├── 00ec63dd956009503e205fda73d8a1191679999a.nq.gz
    ├── 0105d9a4ba207b88b16f2f08e31807214636f5ce.nq.gz
    ├── 013e481ec0d04289ece34256ab0979d4853a3bdd.nq.gz
    ├── 0177c9b64c67009ff8e19ec2f95bb88574a63db0.nq.gz
    ├── 01c93609dafe406fd044fa2097dcc6c2a3ddbf01.nq.gz
    ├── 021b15ae9ebb10b6e88ffba57df8893dc99798fd.nq.gz
    ├── 023b77ecb98d62a8b419097122c365eebca68460.nq.gz
    ├── 02d12d23749e943689b5e67b0a8ac53cde6b02f8.nq.gz
    ├── 02dd46c70e80d028fd84cabd131460b88b81241a.nq.gz
    ├── 02e4254378e9785f013be7cc8d94a8229dcbcbb7.nq.gz
    ├── 031927063e9ef2db724901f4e7e665c0c073da76.nq.gz
    ├── 0324798a9b4d929d30f72b6f01a1de28dd726468.nq.gz
    ├── 043dc9539f1ac0d617bfab6dd572203e7dc493b1.nq.gz
    ├── 05199d68a777d076cfc37243122373010d82d6e4.nq.gz
    ├── 05fe02330d2dbaad5fd757f95301cd709ae2a3d9.nq.gz
    ├── 061ebd9a9057a6b57be2538d36997045389a9ebd.nq.gz
    ├── 072fc311b9e077af1dc5b3c63c40fdd72085ff15.nq.gz
    ├── 07be232fd7fdd233f0b7f4e14854a3416f967cba.nq.gz
    ├── 07caab8622dcaec76da19ed1940b73102536af13.nq.gz
    ├── 086f68460f975cfc2d9ce92a19a6f673050a5ebe.nq.gz
    ├── 0950f1a8a45149b521501b37df46316d06c472e0.nq.gz
    ├── 0965e7153921b94071b66fc888c61199d0837cfa.nq.gz
    ├── 09e967285d1b9d8f6b485ade121f36119e355349.nq.gz
    ├── 0a3ce9d9b267d7ca740b52f303df205e92c0a656.nq.gz
    ├── 0a5550a07fd25c23d2bc1379ff369e160bc448e3.nq.gz
    ├── 0a5ee6d08cc66620ec4667300df794939a1a8077.nq.gz
    ├── 0b534c4a093ffb1aeb8e8f80bf56ed24b4c971b0.nq.gz
    ├── 0b77e81a014b0b1309cc0d2e09a6a279e6c3da1e.nq.gz
    ├── 0bc6e509dfdb6b04fc3dbcba08b6e014fc6f4bfe.nq.gz
    ├── 0ceed33b4ce29a81cfc3bc2aff6a4b15dfab5789.nq.gz
    ├── 0cfa95234a5686b0991cdbb1d636d9753b963c03.nq.gz
    ├── 0d67f12cba3e05ef8a6fe20adfea9dfdef0f394d.nq.gz
    ├── 0e8db4e6e461e49e2f311f81a1711f06e97577ac.nq.gz
    ├── 0ec79708ab32c7d28e30925eacba7605fc3bb269.nq.gz
    ├── 0f7db648e2f73b90d31c09a503d15f59e552ba81.nq.gz
    ├── 10bbc950885072035ba7eb04a95266ca51bbd263.nq.gz
    ├── 110abad40e61ffee6fc45591bcb44fa58393457f.nq.gz
    ├── 11909b9dede074d479b7f07fad43455bc6be1f23.nq.gz
    ├── 120d87a0a7442ad6f5b2192b58f4f353147d3bce.nq.gz
    ├── 12de88b47ece556a976288a4b85babd2d4df2922.nq.gz
    ├── 140064f9991b1ff9b2483a36df41cdf07dcafb3c.nq.gz
    ├── 142171512a2c7b4c2ec2c70fc5d8fdc689892e30.nq.gz
    ├── 1443e9d1c9bee93f002f08752502546aba15604e.nq.gz
    ├── 1576725d42deae8c580e742be66b24e09f82e64b.nq.gz
    ├── 161b499a2762c684052dcafb6cdd8f81c18cb4a3.nq.gz
    ├── 162cd4003968618a855f1810fc3263c3a05a46a5.nq.gz
    ├── 16b1b2d7e4ce830c911b62945115901bb5fd8a0e.nq.gz
    ├── 1903cfa79d0aa4bdc138a01d1c317b2be2ed40b2.nq.gz
    ├── 1984db2076191824e399e799c3890524595dfa0f.nq.gz
    ├── 19cd23f17fe03cc5fc5f246f279e3dd913cb6084.nq.gz
    ├── 1a418310291650d1c8df257f9738dba849e642a5.nq.gz
    ├── 1a69fd2a450afc3bf47e08b22c149190df0ffdb4.nq.gz
    ├── 1b44ee4be251cdfcccc5e3cbc336d764369e3b57.nq.gz
    ├── 1ba8fe49b5e6aaf295b18a88dca30bf488060c59.nq.gz
    ├── 1bbaed5a8d19486d84c39193d51be0e5b72f37b2.nq.gz
    ├── 1c37b4ee433e28a305a25cc16d07b63771718ec1.nq.gz
    ├── 1d3680ceb703b2c75a1fcb49e8b3ba3673a3a902.nq.gz
    ├── 1e1e6b269f8065086ebc5b6ddc94f8ffb56ed5c2.nq.gz
    ├── 1e4a0f3ee79ab3ea8348b6661725652476b159fa.nq.gz
    ├── 1ef41e1a31bc67e05670117030129f7483ae76cc.nq.gz
    ├── 1ef6a66f1a14c0558a0c2d051e53ccd9b1bc61ce.nq.gz
    ├── 1f1f1fc8903a1973ecae153385cc2e2f767b94f3.nq.gz
    ├── 1f562e69697c04b11eb650f1b19b732deadbffbf.nq.gz
    ├── 1f884fc9506fed272c6a3af0ea9db330ba05dc5b.nq.gz
    ├── 1f9f13cbd12441a45f3db0569fe4fd8f92baf039.nq.gz
    ├── 1fa993326d44906cb233b156eb6d784a412409c1.nq.gz
    ├── 201de231f9b0fdaa3117169f2c81a1e2238d6654.nq.gz
    ├── 216e028933ce2c4d9a8b18146bfee6180206f0e9.nq.gz
    ├── 2197677e9dbf86b6d7c8c0394dce77aa7838e8ed.nq.gz
    ├── 22432b9cda1c2ddf4cb79c91fc61b41d6f58f395.nq.gz
    ├── 228afa71098c2c8649ea508c2c6f664fd3ba109a.nq.gz
    ├── 23ea1c74d92abeb3a90cc4c10e4fe10f8f5dcc35.nq.gz
    ├── 24e6842bc08f13ef5904cd73d807d3dee5464912.nq.gz
    ├── 2564d48be10fb133ae0ddf817a2e3232f74b644b.nq.gz
    ├── 260c6a0b50f6d5ca35206e7af4eb47e88c8c1bbe.nq.gz
    ├── 26b09dbbcad1269f9c86c9de18ff2bdeaa983843.nq.gz
    ├── 279e1745ed397f8420139edb2e31eead1571911e.nq.gz
    ├── 28c47db3a64faec634d489c83345ef87296b5fee.nq.gz
    ├── 28ec137f4ccfdbe072cd0cc7d005cd8fdc46b598.nq.gz
    ├── 294421d2d987359d33cadc0d4a1b3e70a2ef1296.nq.gz
    ├── 29702a0dfc280fa9a56d27ea56c30db9da6acfd1.nq.gz
    ├── 29a9631fd1177bbe039ffcf5cc07a492cd6170e8.nq.gz
    ├── 29f76e011a7888bda8006335229785f9bbba419a.nq.gz
    ├── 2a6ef815477ee7d5ca61c12540997d4c2540ca91.nq.gz
    ├── 2c0f3525c18f64fa2d68c6cca27633cb20af00fe.nq.gz
    ├── 2cae1df564863b8f1219e22f851af3a69daa28b2.nq.gz
    ├── 2cb464f8087f54391b76b786689d669b68864420.nq.gz
    ├── 2d0f0b3455aa841b5611ed6a419aca835d43347c.nq.gz
    ├── 2e2c2a41fdbcdd2b218de9a288c88229a3eddeaf.nq.gz
    ├── 2e8cff571184d1144c8a0bef88c1e5062975b4f6.nq.gz
    ├── 2ec14347b5730d748c77541ae9b8f018d533d898.nq.gz
    ├── 302c9704fe6c0b3a657ea1354f8f10569e04ea84.nq.gz
    ├── 3074f9c2b07a9513c7e0cf8fca99d5611c0b71ee.nq.gz
    ├── 30ead7d217f403399626a2bbe2b25f0d6f92a590.nq.gz
    ├── 31079cdcb74f7679c861ac228f9d1df851a5961d.nq.gz
    ├── 316aa8f88a32037a9e8f52d206dadfba37c26fbd.nq.gz
    ├── 31d58bfeda8c21358e3065fe595b64f865a665f8.nq.gz
    ├── 31ecfd30857b2fca6ed68deb8181ab983039d7e1.nq.gz
    ├── 3280e07891eb7af797121c4aa9194309b04308e6.nq.gz
    ├── 32a5382bf50ee9930a715758ffc93598103d66bc.nq.gz
    ├── 3397225a1e1e09745599241486420e7c1625e750.nq.gz
    ├── 340513e65e8a61b60f0074b880b9234fa7f2e308.nq.gz
    ├── 3478b0378ff52fc216d3d606fcf7d30599c88e4b.nq.gz
    ├── 3690fbe989a52171f4eeb0208f3ec183d59b614e.nq.gz
    ├── 372ae5a4452086ff99d7c8610fc9fda20105a976.nq.gz
    ├── 3782c1ebd592483ccb23162beb2e2e4fd08b2504.nq.gz
    ├── 37ffd827aaa40561a9f88be8da8f62076bd68484.nq.gz
    ├── 381fad680aca151438ee83825b8bec1c426e8e08.nq.gz
    ├── 3a093dad24a4a0d0ff34aafc73e1c39b657187be.nq.gz
    ├── 3b1636ec9475fbfa9e6f72de71cf3d2722a30876.nq.gz
    ├── 3b2c0ccf5b0bdaa1900c01460b219691eb7e2dec.nq.gz
    ├── 3bf492ac0676a0fe123a03d5f3c2257701c95b1b.nq.gz
    ├── 3de439cb2bd7198e9a862e4c4cdc22f7887f32cd.nq.gz
    ├── 3e3b308b1f704cf80c10f4e9eb1541e08dd77bf1.nq.gz
    ├── 3e7828a3dafa3032c8d7bc1b24456d4913db7502.nq.gz
    ├── 3ef1d8b9fb62ba5032804d3c75db59cba1942201.nq.gz
    ├── 3fcbf7a39ff9a832a17a4a27cd12566ed2c410b9.nq.gz
    ├── 408a4fafb8ad55a149c9bc1a91803242e487d050.nq.gz
    ├── 4121cb9c55c3afadaf588d3c5a63f34ae07ca284.nq.gz
    ├── 4128a27cf735b2d72504167ff15cfb3055706baa.nq.gz
    ├── 421fdf60fd17f49f8511936a649342416f7d6362.nq.gz
    ├── 42d70f2f8182c640c444b3e11a95161f09a166bc.nq.gz
    ├── 43709b9e2e977a30adba7cd083a96960abb04eca.nq.gz
    ├── 452b5d2aece469c27d972ef5a6ee641752ce857e.nq.gz
    ├── 45b0e7cf535fbacd2fdaeeb4b35edc025a827540.nq.gz
    ├── 45c63f98fb5e6cc4084d0bc63d82d5be28348a8a.nq.gz
    ├── 477eb38908c9d19cb15beb7d72270dc9a3525cb6.nq.gz
    ├── 4902b398ba46258955a5acf56b98bdf97d4a1797.nq.gz
    ├── 491da0c62242ed5a7ff5498deea7c7c267237ce7.nq.gz
    ├── 49651aa6dee6ecdfc9d2194ea3daec844a1f6648.nq.gz
    ├── 499381a4c8c1b86e60b7364412748aaf921d4801.nq.gz
    ├── 4a5d0c8468e9f90e6ac49d82647fd4a6fb0ce51b.nq.gz
    ├── 4ad6906e8bf18fc71ae87a2cb5ae656369904784.nq.gz
    ├── 4b214380ecd9c569cee4d77965b374ed353ca682.nq.gz
    ├── 4b3002843f824d70b74568674d079b159447f50c.nq.gz
    ├── 4b644d44565ce13c0b4a327bc4183b7a05d6a08a.nq.gz
    ├── 4c2f274ae51f2dcc13746958a44214bbd8e56eb1.nq.gz
    ├── 4c76f060f6efabd79bff1604c3d3fb70d3daa989.nq.gz
    ├── 4cca922f00bb23f2e41c5813432feb9219c302cf.nq.gz
    ├── 4f11a03dc6cc37f2b5105c08f2e7b24c603ab2f4.nq.gz
    ├── 4f274838b537edc3f94e562e1bc93043365b8e45.nq.gz
    ├── 4f3065f7c5f1913e9a954cb0cd1dca320a163403.nq.gz
    ├── 4f30ec7b81438472f748d47e44e6717a510359f2.nq.gz
    ├── 4f62263b791279e6b460ebee74a80589f9444c75.nq.gz
    ├── 4f70f8e520cefd25a62e31aca10ac00f665359f9.nq.gz
    ├── 4f86f3695977987b8eea4148c7fcbd324a5ee8c5.nq.gz
    ├── 4feb9d2ef657607f7e26d71f13d1c0d09f8db825.nq.gz
    ├── 500c2043e0d0003a5cb558e57618ed87d66955c9.nq.gz
    ├── 5174b28c565c285e3e312ec5178be64fbeca8398.nq.gz
    ├── 52bff1c2d91e47d5bf65965084e7e9703361ddf0.nq.gz
    ├── 52c54d3bbf2556d2636a4cbe377abf9d71cfdfce.nq.gz
    ├── 52f999a3811ac78c7440c31ec8dd9517b3424178.nq.gz
    ├── 5316f8eb27486b0024461ea43c38ad9f51e610e1.nq.gz
    ├── 53f155b1606bbdad940a2c2680f478e07c0b6aad.nq.gz
    ├── 53f4094a05d875ec18c20ee0c818b77a8efa1abc.nq.gz
    ├── 53f8a55a8ed17351d374a44902b9341f3317cf07.nq.gz
    ├── 54574eaf9c0d374f63b27241cd0182800618c3f3.nq.gz
    ├── 557d7faa1ede335cdc469badfe48407f85c31879.nq.gz
    ├── 55ac6d992eb2e6341adef60e2ffa14d2b444db21.nq.gz
    ├── 55ae5ee17cb0bf8539432cf7fe74b1fc7642143d.nq.gz
    ├── 55f0af8e455fdd967a01c0f932ed64060b50ac52.nq.gz
    ├── 568f833afa312ba75d78883c430d2586ddeb8ccd.nq.gz
    ├── 57d638f1bc45365637cb20d1496ff370ecc4392d.nq.gz
    ├── 595365774e4586310441065f4d2c06662629a0b9.nq.gz
    ├── 59d7601a7b72b3d0d6affa866db9213aa8745dc9.nq.gz
    ├── 59daedc99afae2f0e9aa42ac6e625e01dae621cb.nq.gz
    ├── 59ff2b87a08f28a83a0e90ae48ba0675892df89a.nq.gz
    ├── 5b3b50a0f25d961106c318a350a0fe31229723b7.nq.gz
    ├── 5b6e51400df1a2d215b5bee2181ce61f183ecd44.nq.gz
    ├── 5b942073fc6242e435cb7062e45d48b9422986ef.nq.gz
    ├── 5caca4f9029850a7a1762de40c966ea7709b59b7.nq.gz
    ├── 5d46316f1f0cb555c9599f519d946336a56ae220.nq.gz
    ├── 5d7e46a445a1dfa42bdd93450aa1365edcc38cb8.nq.gz
    ├── 5e65f376ea5a4bf8e4397a66b60e179d13fa1fd0.nq.gz
    ├── 5fb1da4759d1c73b11130409071e4ab3aa5b3345.nq.gz
    ├── 5fc4b2e93014aa28b3012bb666b9b8bf14b4ca04.nq.gz
    ├── 5fe672fb434b786b226483069a3fb83ce7245630.nq.gz
    ├── 60218fef9ee561edfe8e1349675ae2d8731a35cf.nq.gz
    ├── 6167a08219c3106d4956e8baa58a156c6ac4dcf2.nq.gz
    ├── 6228219083f93cc444ba2c704c4912ac9a44ba0f.nq.gz
    ├── 630ed4509bd30de0120a3d3a8da0130de9a1e39e.nq.gz
    ├── 63b44d0eb379e607c74f897ee00aa3b5608efe8a.nq.gz
    ├── 63e1eb14eb92aeb90b3fbc2982f179c0bf1db756.nq.gz
    ├── 64337d0ac90a5149901ec899ac12206799a63176.nq.gz
    ├── 643da4385a1e8a8aed28d65f3a39c7eb0f3983d8.nq.gz
    ├── 64646667fd52ba2b2b78ecec500d457766841242.nq.gz
    ├── 64750a8585fad0d1763ea7b4e0a211af46d47cb2.nq.gz
    ├── 66186eb54c0e58a75bbc84d3df7bc3309f5d7805.nq.gz
    ├── 662b57b8ea0fa4d43ab4b376ba3492bdf1afcfd8.nq.gz
    ├── 6651481b2894078be5205cfc3cbcd9304b483941.nq.gz
    ├── 66df4b2c8660921ac364a29a88b1e0dfb5b87364.nq.gz
    ├── 687d19c982438ba7f4a8749db76f41c4583d054e.nq.gz
    ├── 6888819fe0e43efe9ed704b1ba8b8bbc2d88817c.nq.gz
    ├── 68e4eb455896a6094f707d97d73a5d7a0876837e.nq.gz
    └── 68e700f85239fbefd24b46b22466871598796f76.nq.gz

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

[sweepai/sweep](https://github.com/sweepai/sweep)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
