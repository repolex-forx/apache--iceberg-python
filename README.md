# Repolex Knowledge Graph of apache/iceberg-python

RDF knowledge graph data for [apache/iceberg-python](https://github.com/apache/iceberg-python), parsed by [repolex](https://repolex.ai).

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
lexq download apache/iceberg-python
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8dee48a8e0218353f706133ed035334869a7ee12
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8dee48a8e0218353f706133ed035334869a7ee12.nq.gz
│   └── repolex
│       └── 8dee48a8e0218353f706133ed035334869a7ee12
│           └── chunk-001.nq.gz
└── blob
    ├── 024d14fba656eb4bc1b76f63cedeed498abc8a3b.nq.gz
    ├── 03a33e4c782f1413192236f7505514b2527c17f9.nq.gz
    ├── 03f5684ce4fcaf43af7f6092cb66132c672d7d58.nq.gz
    ├── 04bc3ecfac8a5e2c5e23434c8e667a47088a5f22.nq.gz
    ├── 0626950638bd4928238991505fc92e6c92962d28.nq.gz
    ├── 08f90c66005a94630e98902228d82dcf43cab9a5.nq.gz
    ├── 09273768d9ed5c40a48c792d165bf97f95559401.nq.gz
    ├── 09dd9ac81b0574542c025774c5d305cdcae78549.nq.gz
    ├── 0beb0f3df062f56d733d333f5d4f7a11ffd73319.nq.gz
    ├── 0cbc11689af68609fcf4ba4022602beddcc7fe35.nq.gz
    ├── 0cda688f2a644a905116ea54fd58385154e80f3d.nq.gz
    ├── 0dc6fdb7f42b665d5efd887df04a4a12c83f2a33.nq.gz
    ├── 0e1c0b342d13cd39e4a2acb2cbee19e7fa6bc276.nq.gz
    ├── 0e1f29d15205a1b211b2f350de009670c4357819.nq.gz
    ├── 0e39beb24138ba3568af1d461699443eacef1440.nq.gz
    ├── 0e5a489f8935caf16b1ffce5b0cfb6b610c820be.nq.gz
    ├── 0e628829eb3f2b03ab1290dea1ffaaedc1208081.nq.gz
    ├── 0fcda35ae9c32028b84774126b7b8b9e053a6cea.nq.gz
    ├── 106e5b786cb805478f02facdc16e38aa9ee586dd.nq.gz
    ├── 136145ce8a2cec08364b02b1010828efab9dc546.nq.gz
    ├── 137215ebc8f3b16aa8e36d990d9cbb2a3e0dee00.nq.gz
    ├── 13a83393a9124bf6ec36540556b4808abd47e206.nq.gz
    ├── 157c1adaf1d480099fb16d25e6256f2f3a0c1fd3.nq.gz
    ├── 157e4bfa16b6bfe3e1ae5e5f0ba9b4c6491c3a66.nq.gz
    ├── 163ad8405ed92f9af462b88ce77db7264319294f.nq.gz
    ├── 1706ab96fe75725b79f7d8eddfd03fe838503e31.nq.gz
    ├── 1844a9bc8568769bf3704697a75697445b842a91.nq.gz
    ├── 1a2204341b7d9c121dc23172405d0f98238085b9.nq.gz
    ├── 1a47478313a185b788cdfe4aa382dc865b8a1a5e.nq.gz
    ├── 1b1cb4d44c57c2d7a5122870fa6ac3e62ff7e94e.nq.gz
    ├── 1bec186ca84329bf520937b79bf1af8990b1e8ca.nq.gz
    ├── 1cf6bc01065087c458c3dbb696e8e7e602990aae.nq.gz
    ├── 200904fd97dcdd747a59f165c0eed4ea9659f4f8.nq.gz
    ├── 20149a0e1a3e17c1d5a0d4475bb5b9382692038a.nq.gz
    ├── 21508a8f63e62e4fc75f0143288fae92c25e6537.nq.gz
    ├── 2444e18737cb6a81cd4adedd7f289df09cbd0f6b.nq.gz
    ├── 24786681f27495763f7b92736a7c1761dda60524.nq.gz
    ├── 24a8d9f6ef862171c828207cbe07085fb2bd4c7f.nq.gz
    ├── 252385d1cb6a266748b49b20b0fe68329fc092de.nq.gz
    ├── 26b6e3d3ad8832db9d92825196f052dfeeee04fe.nq.gz
    ├── 271025a72666c29b95554656de3f30932bc3f2a4.nq.gz
    ├── 282326edd835b4a7803a73b5afa6527eed9f1c93.nq.gz
    ├── 2a95b39a506c09543081e587593caa7fba52b5fc.nq.gz
    ├── 2bc498560939cc218b2cbcdca2f593acc9d0406a.nq.gz
    ├── 2cb4ea5ace99c70689533667d784bdbef1debbaf.nq.gz
    ├── 2cb632378229525ba6cfc9b8d3e212392233503b.nq.gz
    ├── 2d35b2c5e26b5447a393b8415cb393a1d8aa1390.nq.gz
    ├── 2db4853ad0e4cecf795f028cab7a916e79ac15c4.nq.gz
    ├── 2ea7229772aac235c3563a424ef436e67890cc13.nq.gz
    ├── 2f0c444dc4122c6fa1e8ec99fdbd82d060d59677.nq.gz
    ├── 2fbac5e816d4feaa6704dfbdc2e03a5fe9594e85.nq.gz
    ├── 315521555e61c8ea685fbe5839fb4e795c6dd248.nq.gz
    ├── 320fc337934ed4344892a65d18cd495007198e0f.nq.gz
    ├── 332221008c0507cf23e10851947ba8b8168eb91a.nq.gz
    ├── 33fc11cd438a23c3378fd08d665851fe15ba8483.nq.gz
    ├── 34185b980a989df52e8db12a3481a4aa0490bdc4.nq.gz
    ├── 34ecbbee0521127047b0bc852fae16125d9f5523.nq.gz
    ├── 34eee94bbd878a96edbb4e1049b477a2d6d7b8cf.nq.gz
    ├── 37f2b44db98f26ee244b87979cddbe07f3fd4762.nq.gz
    ├── 38373ff809f0a18029ec6acf13b60d0383ded153.nq.gz
    ├── 3862d6b68292ad6e69e81f9a93df80b5987ca617.nq.gz
    ├── 386e92340277dc245e4817cc87f45f358c1eb8dd.nq.gz
    ├── 3910a146c7d155f8e2e42ef90a411039c8f3d241.nq.gz
    ├── 391cca78b09b9971d1fe20a6ce66f85f523663d1.nq.gz
    ├── 3d9ee92a66c1b6a9cd595a4c4f230adce29e1443.nq.gz
    ├── 3de185d886f2056ad63acb1a534993e0bad6de5b.nq.gz
    ├── 3e4a55c19ad8b5f87e8f3298b4f258009fb8fd80.nq.gz
    ├── 3e67bf691af307227457290e2365d7e052845d8e.nq.gz
    ├── 3f0f15912feff5378e084c935b947bb26292c25b.nq.gz
    ├── 41a4cb802080d6472d2556780754ef20a49340aa.nq.gz
    ├── 420043bd55b91ce91136b441f75f6b5c53eaccf1.nq.gz
    ├── 42f210c6e4678a8e7bf9cadcad6fd80bc7919c02.nq.gz
    ├── 433350c22569d7d0590791b8ecb29ad43eed03b0.nq.gz
    ├── 43a711fa6b33caaae0fdd92d90d3d9624d3a432c.nq.gz
    ├── 44322849d8a0dc29b7c65f149ad131a31d47175f.nq.gz
    ├── 4462da1c8c14a447ab7bee57d3548747b38a3646.nq.gz
    ├── 456dbe41a6ba91476342c78e6e3124ae04e592a6.nq.gz
    ├── 475b894417e44cff61d8810057fc1530cef05718.nq.gz
    ├── 4a8d548612b97321feeac631b055074270a51e05.nq.gz
    ├── 4ab54d97e786f00486464cb15cd929f8b7486878.nq.gz
    ├── 4c68f5e3d545cf32614e3a1874732d2b2b56f37f.nq.gz
    ├── 4cc815214ff426a452c4bcee9a0502d26fb20b7d.nq.gz
    ├── 4d0c2c13463a75267cf947ed13bb82a182cf3f32.nq.gz
    ├── 4e50f590c79b3252113f0f177db5ed4f44a24a33.nq.gz
    ├── 50100b9befd1e9329f269810260bc4d0d5d7565d.nq.gz
    ├── 506547fcd665cb021567f7b6f70e721816795ab8.nq.gz
    ├── 50e2429cb1725ab6648ba17f6baef5c1d7c89999.nq.gz
    ├── 51386d56c446b27d58c997ac694900ee41a54fe0.nq.gz
    ├── 5273db22f8dbb1e1397d0146d62809acff0de594.nq.gz
    ├── 52caec33085663dcdea96c02d400135b424150fb.nq.gz
    ├── 52d57a65c02653f657682ae37a4d83e3cf9497d5.nq.gz
    ├── 5391b8e2f5f99ac5b6eb14cd64392db2bec92ea3.nq.gz
    ├── 53ce6fcd42bb29813fd34d399fe188345c790e47.nq.gz
    ├── 545ede41e42b86e232d26a1d173d6b9c72acd07e.nq.gz
    ├── 548c6692dbff7b47fde9abe5cee3dcd433f7fd0a.nq.gz
    ├── 5592bc9953b157b8260979602c5241d67e9f8a22.nq.gz
    ├── 567f1444a79ac0f4a19301a877861660005495bd.nq.gz
    ├── 570f6808603b7432c2b5c2b3aa5caa659e4af5f0.nq.gz
    ├── 5866719434e7a1394726e11a052f32cae0faa9c7.nq.gz
    ├── 5933e7d4729ec38c8b08d5daf2ed201a987227ad.nq.gz
    ├── 5bf70990b9a5bbb0d4ba343da379e6c6f5fe4900.nq.gz
    ├── 5c09cdbd0fb5d819c1c2207986e94309af3d1850.nq.gz
    ├── 5c4323ea8faad1c0ebdbcefcc27a22e43a531746.nq.gz
    ├── 5c529e6efbd5f44782cd13477ae9c12ff12ce1b0.nq.gz
    ├── 5cd6a7203a5e394f18d181911b35d172a38c1b17.nq.gz
    ├── 5da343ccb6ecb7bb8bcf4267beb8f13f0adad300.nq.gz
    ├── 5ef82640d9872b9cfa6111a964e43572b5166f1d.nq.gz
    ├── 5f4a63f6ff64dde9c17bb5636d767a13072c98c6.nq.gz
    ├── 602074282cb486c08ecfcc80bbbf10bf60da6e1b.nq.gz
    ├── 609ac8d51f99d183d08fb0dd81d376d1cc07f714.nq.gz
    ├── 63b5b50dbca38c9930cdf98e3bf54e1cd0533f3d.nq.gz
    ├── 63ec55bab4a5b7ecdde264d32ddde2162984775b.nq.gz
    ├── 64f3eb95a3278e595dacc9f25a5253c9409e9a40.nq.gz
    ├── 65f06ca8b138793f47eda98bab1ede0bf12aaf61.nq.gz
    ├── 673908e19f5693b0bb76701d1a3eb69571cf54e7.nq.gz
    ├── 695ef9b1bf17d861caeae019a434691a4f9e50c3.nq.gz
    ├── 69f3c78c0c3dd1aac4253c22fffb2c071b7efa69.nq.gz
    ├── 6ae14bca0632960503419bba7c2ffe1c32801d8b.nq.gz
    ├── 6b3fc7f4b2c39974ae465e7e1082d16d93e911ec.nq.gz
    ├── 6bb71e1d94cf02d549820184f6e924bb66085a2e.nq.gz
    ├── 6c14eea062ed6fc0aed717626e6354cdf17fa14e.nq.gz
    ├── 6c2bf7baed77ae09e5ba073aa656836b045c847f.nq.gz
    ├── 6c91990ea319ee34d7ca7e059690ff076c7e878a.nq.gz
    ├── 6dd7520f3c507c690b7093f28fef6ba982135da0.nq.gz
    ├── 6ddf4c11d582a4400bad8f70f07f436749743013.nq.gz
    ├── 6f32826eb0b3010d36404a62fd67267c06fbca11.nq.gz
    ├── 6fd3aadaa32307940682da8fbab792443415eb78.nq.gz
    ├── 7215e0d6e3c345568c4897ecb4788e9e6bb3d856.nq.gz
    ├── 726e6b5f62e19d028ff59d71034d1d01190a7010.nq.gz
    ├── 739e18a6e684cda50c817985964c6abcb6ed1cbb.nq.gz
    ├── 742012886ce4421252d582645acdd4c222e8498c.nq.gz
    ├── 742da00f57486eaef83dff878d3b754874cc6cfc.nq.gz
    ├── 75440db77c1d57b909b18a76453cfa1a47f8c603.nq.gz
    ├── 7687d2e5a08ee7e56ee8bd5d7eefdb5bfecc940e.nq.gz
    ├── 76fe2cb07bd2424ec46714df38ae5f2024932f52.nq.gz
    ├── 771c6b5a0f911143d4a6b670bb3f31490836db7d.nq.gz
    ├── 7bb34ef7c1795545e153c21e22bc1b36b9dddfe5.nq.gz
    ├── 7d754d329639242d70cdf8cd810c9106b51db248.nq.gz
    ├── 7e4c6eb1ec3c6d4e1986067bb7a6683d2c78bc5c.nq.gz
    ├── 7f5b740380a463aa3b1f238d7652a2a001a5c04c.nq.gz
    ├── 801c1e86a910ba249bdadcb2c934c423561e6a3e.nq.gz
    ├── 80fc5303ad6894888ae3ed63cf42ad082338e476.nq.gz
    ├── 814d2694fe2e992d2dc07b212b0c79c0f4714dee.nq.gz
    ├── 82454c8574505dece648cfd6ba05c2c0ec2b3a9e.nq.gz
    ├── 828f1e877a8f0a648b8346e1464ecf1755e1dce0.nq.gz
    ├── 83c72f6ba32721c6756bc78cba163441c92b16bd.nq.gz
    ├── 8877e8bf805038a41be3b11b086dda2fcb52d8b9.nq.gz
    ├── 88b653e44f00c5c5996edc243b95c6d73c6373d6.nq.gz
    ├── 8d2a39629cecef940f31417570c630f3cd29622e.nq.gz
    ├── 917d387f45f420f4d2bad2b2ec90f9b3ae9c4efb.nq.gz
    ├── 91c7a25b031b77319ace346a556b9b9ce130337d.nq.gz
    ├── 93301a01c78cdc280907aa8158208fcab9ce3da5.nq.gz
    ├── 93ddc16202dfe87dc75e33d0c2e50672f07884b9.nq.gz
    ├── 948656aadd6f5619782601137d2ded8a9d44d18f.nq.gz
    ├── 94a7ba59c5bb2c32ab5eb6dd0608ddd3ae124441.nq.gz
    ├── 96500907cfab0a8e41cea0aa465bc87665ec7992.nq.gz
    ├── 96a299cc45af0deb397ea3d1e17c4d3da080a85e.nq.gz
    ├── 9d72e1db1ce44de36a672c25c54b1d078f38bf8a.nq.gz
    ├── a053bf90adbb2dfa6480709e6947e1991813dc3a.nq.gz
    ├── a0fccb8131c4a55fcb5bcad75848e60360dcc8b3.nq.gz
    ├── a120c3b776a1e65f0153c2c9139c38c35ed99dd5.nq.gz
    ├── a27046ef3022a890bf75f8c3a6857d190d886cdc.nq.gz
    ├── a37f3be8b08f218949a5127571208be05db8a4d7.nq.gz
    ├── a38787e1262f1ab0d3d18a3e43c1b9fd6340aeec.nq.gz
    ├── a5842e4bf090f0aff1e9014633999f950947f9fe.nq.gz
    ├── a67d5ea255b2740eced14aa70b32af32abaefa95.nq.gz
    ├── a77ed66563912c3d5233cb63f6e8047a198c9abb.nq.gz
    ├── a804d65db7c803bfbcbf8bb7a1a08d9a0813964c.nq.gz
    ├── a8b7e32850aa0972d9351da66525767c72786671.nq.gz
    ├── a95b015a99b29245416b21fad1b70a3daa29e53d.nq.gz
    ├── ab97ab6990d2124c43757c818538c596eac17380.nq.gz
    ├── ab9b549d251b4709af57778b59d40f1e3e4d306d.nq.gz
    ├── add6e56156328fd99afca0c0c2c3958cd1d8e972.nq.gz
    ├── ae5d40f5aa45a3ce9014d52cef1938a28307f977.nq.gz
    ├── b110b6291b78091eea143a67ffef9fbe7a0b8851.nq.gz
    ├── b40ba7e176a71d3c840df782c998b9c213fd4403.nq.gz
    ├── b59f43fbcd902aa6e9a6531ffc12bd26c5e61880.nq.gz
    ├── b5bb6d01cd6be7e01585fb72ae5936355fe62b62.nq.gz
    ├── b5cde34f26a0520716a3762e2c9d816284be3c75.nq.gz
    ├── b762c1047cca7b5f1c1017c2bad1df21dc2084b8.nq.gz
    ├── b94bb7bbe498b382c8b1aeba4596906d1ca936a7.nq.gz
    ├── b9c3c10335facec540ff80e073fb2074583b1ffd.nq.gz
    ├── b9e92d36861f42f7f9d4270ce6cb347236cd251e.nq.gz
    ├── ba0a0da2e5efa65508a864b1a9c382c564da770a.nq.gz
    ├── bb11fdd7090776f9b36339c8071056eadd37823a.nq.gz
    ├── bbfe8aa4f2641cc1286ad52b7c30a99288df5844.nq.gz
    ├── bc787ff3c51d0fc054388d9696b7d2e6db987b68.nq.gz
    ├── be3ea2b6a17ffbc537097fe958d9ba2df814fef3.nq.gz
    ├── bf8c82014c49254c36aca3693f0f0edd186e66eb.nq.gz
    ├── bffb97c22597faf70b57e75034d259c4e959d9a9.nq.gz
    ├── c163c90626540a4d4a7906ae0cd4be604b1aa525.nq.gz
    ├── c3954f330d30e53262d1b84af5d4716707c11e95.nq.gz
    ├── c3ace5d368c9fc5ff7ee3cbd5ec259f59ba010ea.nq.gz
    ├── c416c2b8dfd6976435a89991e7da34945657e6a5.nq.gz
    ├── c429770268c30087ba26c97db94770ba49aa012d.nq.gz
    ├── c45d8993881b65feb1bbc96c5eea386d95db9f85.nq.gz
    └── c655156c2a1c8291b901ba5b10172bb07a4c9df7.nq.gz

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

[apache/iceberg-python](https://github.com/apache/iceberg-python)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
