# Repolex Knowledge Graph of deepchecks/deepchecks

RDF knowledge graph data for [deepchecks/deepchecks](https://github.com/deepchecks/deepchecks), parsed by [repolex](https://repolex.ai).

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
rlex download deepchecks/deepchecks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 98475d17b08a21fca29d533b94b8ec3c70544a85
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 98475d17b08a21fca29d533b94b8ec3c70544a85
│           └── chunk-001.nq.gz
└── blob
    ├── 00089ca5fbe42b336464fb63fd29fcd49fc4257a.nq.gz
    ├── 00c2032853b4801352ca6d687eda62d8fc3cb853.nq.gz
    ├── 0287d0b412a31425e52a38d32d69533b5dde077f.nq.gz
    ├── 02aecede4a3c0def4a8e352c7ee2de6a763400f3.nq.gz
    ├── 03218174bf4cfa775010df9ba436ca6415a0d30e.nq.gz
    ├── 03aa364f117c5956c75815c532c6907e71604361.nq.gz
    ├── 03b59cd69f6af920277a2ddd95ce77a6a318d526.nq.gz
    ├── 050c60688dfb4f19850d838db1c7def5230af190.nq.gz
    ├── 071071c7e088dd1641408d601c9e803d3540a15e.nq.gz
    ├── 07555cce37f70e39b2b19330c87479fa73081641.nq.gz
    ├── 08412769ac399f146827992de72eaa56cf2378ed.nq.gz
    ├── 0858cd6a20cb91d796eaa40a5734e43bc165ac6e.nq.gz
    ├── 087917596bee413c64ea80ad3fbfdce3bf307771.nq.gz
    ├── 08a2238cd759cb04e5561a9f9a5aa9bb9d127170.nq.gz
    ├── 0a294ce6b6de6b26ac1ffcd5d4f75fa04be9565a.nq.gz
    ├── 0acda9c5770abf277bbe067b091ff113b3666b1b.nq.gz
    ├── 0ae7a97a85d0a8713494619cc223aa78b585c59d.nq.gz
    ├── 0c8c16266cf74924cc30a8e90bdbff60a8928b8e.nq.gz
    ├── 0cc75d98dba63fc6ac637a0840ff90bab770639e.nq.gz
    ├── 0d0d7e1ae5ac2851ec7f181d50f378973d880934.nq.gz
    ├── 0dab8bd1cbc32ab6ced5357cbcbd05c82af18e92.nq.gz
    ├── 0f0455c00ef044933c8edaeb3bad137fadda465f.nq.gz
    ├── 0f15af33d262e6c702ba266aaebb136acd12d7ef.nq.gz
    ├── 0f2e72511f60b1a5c04d0a50aa810b757548fca9.nq.gz
    ├── 0f475b890733fecdb59093f6732ee2e7ba4a2179.nq.gz
    ├── 0fe5c2824f4546849224414fb6138b4d6ff59171.nq.gz
    ├── 101486cfaed312139aec660fca458f29c33cde67.nq.gz
    ├── 12f99b228a70af37bd504660a1169ef7ec8e702b.nq.gz
    ├── 136b1bde062afa508228924f96f19c0dd64ed358.nq.gz
    ├── 1503a10454715f064ca37d165d1d264b3b4c5bcf.nq.gz
    ├── 154e7ccb9ea3ba78b0777d12419d6a73ed924d37.nq.gz
    ├── 1582c24b8e56ba43433b8cb5e078889c9adfe0d3.nq.gz
    ├── 15cb0ecb3e219d1701294bfdf0fe3f5cb5d208e7.nq.gz
    ├── 167f49e06e83aa266499908352b1c8754c681d8e.nq.gz
    ├── 16ea7ac177b35b640117f959e93a942bef1dcbb0.nq.gz
    ├── 172c41306211aade816c3f6b2e91570e5ed3855a.nq.gz
    ├── 174cef4114964f0feb58d40a9002707e336dc9b5.nq.gz
    ├── 175bcac2129cfe8ecda43ffc48c6e654ffad79a4.nq.gz
    ├── 17774d4eb557b6581359de8af3ad9f267275c0f8.nq.gz
    ├── 179a740c4f0820aaf1eca519c9152f1db92224ac.nq.gz
    ├── 18abb377b541216b1825af72737a71aaceed06dc.nq.gz
    ├── 18af8ca28dc522f2c050a69a49be2fc2e62ab95b.nq.gz
    ├── 19004bac8aa958bac9d0e181b7f2202a60cefc04.nq.gz
    ├── 19ada36f5f413b2a910c622ebb77146d69a3b222.nq.gz
    ├── 19e338d0bf5a98734c00e3142851e53a541fcb3b.nq.gz
    ├── 19ec17adea6e6f55a7d6f84386943d5329d1f437.nq.gz
    ├── 1cd381a43ac306e3cf9c573eecb741649b253104.nq.gz
    ├── 1d20a3f17c9a8a764b013d9b97fde6c8013f0275.nq.gz
    ├── 1e2f00d31a8ddec511eaaa95373d6c2129319f43.nq.gz
    ├── 1e6aa040d096c3ec6953b562aaa4d30431969bdd.nq.gz
    ├── 1f23cd7b7279f6b28f62f13b737e034384bb46d7.nq.gz
    ├── 1f5021a64f129f9187183441d845707e95e22c7b.nq.gz
    ├── 201b430a0823690619b089161e16b4a8f8cf6d47.nq.gz
    ├── 2032408a6e89bd2f2015d5a2ebd5fc3e4a0ed764.nq.gz
    ├── 20389aa6e6517c2aae7cc44aeb490a10201f861a.nq.gz
    ├── 2081d87ddf7c08327d4f9ad23fb4fbb861bec11f.nq.gz
    ├── 214ab1c4e1211b18c37d437dfd83e70cfba496b0.nq.gz
    ├── 2185c9d6a3f46d7b0e4c71856f9549c6d3a7321e.nq.gz
    ├── 255ae6bec594dc9fb51fde8258deb31cf33b9947.nq.gz
    ├── 25837b655846b7090a5d62583cbdf71c189bbc6c.nq.gz
    ├── 259827fbdb839ce3b90e8fa9db079ec3476f9d0b.nq.gz
    ├── 264af3d7136ce4642a3a09c8bc4cec2502e06a1a.nq.gz
    ├── 26a514f7c433e156c9f98f4f21ce48d87a95fe4f.nq.gz
    ├── 27344e6e02ed266b23f6fdd3ffc36742b4786ed0.nq.gz
    ├── 288bb581567477c4671acfe2039ede87ee04ef61.nq.gz
    ├── 28d01a0b51af13c491ec96e18bff6499c80e058c.nq.gz
    ├── 2923dcc8b9ff4b2c8533f20a1df4a2591a2dc359.nq.gz
    ├── 29f0de92cabb89b60981332bfe1e9efa9a92cabf.nq.gz
    ├── 2aa5065f1f18c16e0bb2aebddcfc83ef9102efe7.nq.gz
    ├── 2ab3d39ef29ccdacffb0423ed937ace6aac2baee.nq.gz
    ├── 2b08b03aa9c1c908f66ec536cbe1aa40e92c35d0.nq.gz
    ├── 2b1508e59c8094e3d346f954b6185d4d7df8a048.nq.gz
    ├── 2cb75ccb4efb8a841fc5063bd433278e90ee05be.nq.gz
    ├── 2cfdaebdc3b76cbbc07abed7f365dd26766cbd55.nq.gz
    ├── 2d5bda44379937778afb807b810d842687009c72.nq.gz
    ├── 2de80847b4403d88e43fd3c57c92e940bd19672b.nq.gz
    ├── 2f3264760e1dfa9decd210288e8615ec990f3dca.nq.gz
    ├── 2f48a272810e9e21a88f53fa7aec5e5ff381a96c.nq.gz
    ├── 2fb17dca3b236f6842450b8cb2a248803fd321c9.nq.gz
    ├── 301223c6439a67cb89c212530356c68cfb56aa3e.nq.gz
    ├── 306c31a19c75eb8d0381e767e80cdc1bf91e36f8.nq.gz
    ├── 30a70bebebe1b1d2e4e56c83e73a9f5975c1358d.nq.gz
    ├── 30e56f74946fbd8f586ef983a0e0c1b651fbd97d.nq.gz
    ├── 3177b109c0eba6173263b120339a5dd697fe7ee7.nq.gz
    ├── 318ec621018cfe150bdb7e64c8f65c0a48cd8cdb.nq.gz
    ├── 31ed6edbe275ef726945c1e968fcc15ed1540be9.nq.gz
    ├── 31eef63e3bd9393a291837a21e71f39fc146f676.nq.gz
    ├── 32577180f6a35799b4bacb0466a13c1f4c526995.nq.gz
    ├── 325b15941ea4ee81c3332196f9c5c0bf2533a2ad.nq.gz
    ├── 325fd02ed226f3eba8dc5d4b78c6a5c4cb199a38.nq.gz
    ├── 32abfb83a03de853712d1f9d647857dda9fa6899.nq.gz
    ├── 330c837917b7895ae842cc7981fc9521cff5e90e.nq.gz
    ├── 3339add3de68aa8a044be31980023b2c4a09e66d.nq.gz
    ├── 33cbaef4e0ffb3af65822cdbf966463ffbb2c0a2.nq.gz
    ├── 34798af499e9ec6200eb3f7f12a295d01d51f16b.nq.gz
    ├── 34ba45817bf07ea304f8d23a161893a9fca50aed.nq.gz
    ├── 36ddbfebb971c761ac996eecac5fd3d45b4a5b4b.nq.gz
    ├── 36e3c8ba3e360bee3a02900fbcbbd422d4577f90.nq.gz
    ├── 370ebdb0654ebedc2136bf34340e705bcb705011.nq.gz
    ├── 377f42b003431472591e7b3b81f7ae096cb2d670.nq.gz
    ├── 38c281ed6acd8e1cac9f16b5031cf7b6219f845c.nq.gz
    ├── 395eaeb5a04e229fb8764ae48268b2c536d88456.nq.gz
    ├── 39e1c8d51c18de5791714a2c2e372faeff9b5a67.nq.gz
    ├── 3a1f66ed1d3e709d81f01133b3939d9fe2c0ce26.nq.gz
    ├── 3a3701444551e9558b332025dfeda85fd61b18ad.nq.gz
    ├── 3ac349502e0d7f8cba1c57ed00a35512eae90044.nq.gz
    ├── 3b00fc76865b9e847d2fc7f62d2e375b94fb78e0.nq.gz
    ├── 3bd85bdb62353b4a8d6ef9ce56fc8d865b182235.nq.gz
    ├── 3bf3df562e0616176b40fdae73b7dffe39a0bbd8.nq.gz
    ├── 3c24c7ff1de36e3cfe59a570ed25138e412e161b.nq.gz
    ├── 3d2002c08b68795ca6237f7907bf9dd7fe86a158.nq.gz
    ├── 3d220629a47a50a1c8c54c53705392843823b7c9.nq.gz
    ├── 3d8b89f9ff0e57ebc12ca157e1b5060b272e3d99.nq.gz
    ├── 3e48352a7498205a199ed1dfdcc87ce02a08ad3f.nq.gz
    ├── 3ed48c326f0eb19a5c39e8d567b7bd10c2ae4cfe.nq.gz
    ├── 3fcadd359115651ec7732acb1160ca59cc77b69c.nq.gz
    ├── 4107db2a6895786c976ac8374848e184cab881f7.nq.gz
    ├── 417f57a1cd05441ee6fbab720c67f6ac78b6e644.nq.gz
    ├── 41c39abe704fddb9c1d4e6acc5f673e4e9e6647c.nq.gz
    ├── 424e6d1e110c32b06be5fac6f595f3bcfcc1fcad.nq.gz
    ├── 426ece4d96fd372ae79ff6592733b33509639ebb.nq.gz
    ├── 42728c9bfe27b2d1e9797af5efab64d0afb8b35c.nq.gz
    ├── 42e0f6c05e18910a6f2ed15a7ac1d8f2e8bb9313.nq.gz
    ├── 43468a6001ed8bdd60f504dc669d667e67964868.nq.gz
    ├── 437225f3b3b2a7c02e8c3cc405d223f240395430.nq.gz
    ├── 444493685b9de8f70ca845a0dbb0d854711ef9c9.nq.gz
    ├── 44b9c281e601e62e97db0f5326e2115367495b6d.nq.gz
    ├── 454b6d6ccaac858800b623ab1248b4d78ac31668.nq.gz
    ├── 45b2d4a5d320bec5e6a38a31ec34b0f8c57a8658.nq.gz
    ├── 45bf5158c56d9782cf2110c802c2ccbbd9c20bc3.nq.gz
    ├── 45d5fe91300ea38523cc9ee5d47915f57cf2b63b.nq.gz
    ├── 45fc2d47c744f7d80f3b5aaf03a2e49e73174e55.nq.gz
    ├── 47192d948bc3417ad3a300be93c91bce51747a01.nq.gz
    ├── 4795de221beb6bb9a0244dc148b48f1939dcfc2a.nq.gz
    ├── 48d10320febef641c284eb8f2a2ae55409c31b05.nq.gz
    ├── 48d4392f61e1e2876f5a8d9ae7e043bd18bfeb0b.nq.gz
    ├── 48f72e5818955ef600de284f9dee854a98073314.nq.gz
    ├── 49de042b40a77b34ee1ddf77a9ed7505bbeed5ea.nq.gz
    ├── 4a2e75b35cf8d540a5fec926b20f13213e71bd63.nq.gz
    ├── 4a587dc9c1302952d498e4eaa486f0253deb04da.nq.gz
    ├── 4aa6f8863948c81766757b9638855bbade249383.nq.gz
    ├── 4add0f7c862fcc819ecdd38c8ee31c9540d21f87.nq.gz
    ├── 4b33a4f3f1719290e02d79e14915d114f15f3866.nq.gz
    ├── 4b88ea34f0c6189d0f205fd1874e7cc177dc951a.nq.gz
    ├── 4c2f80aa964c539d91c3d28ab8033272ec5abd75.nq.gz
    ├── 4dc724c8da0d7965c6e3ca5fa23fbb5c6c08a28e.nq.gz
    ├── 4df0d891e9e7853944c4cb88d83a7121d05bc2fc.nq.gz
    ├── 4ea2b8b3922b338b8190ba0e347115ab19ce8342.nq.gz
    ├── 4ed45b424be3878d63796efcbe9172cb78b82a66.nq.gz
    ├── 4fe565fe78e37301668ff1cbcf48c0463c4e1ad6.nq.gz
    ├── 5075bf13ce2ac6f0a5130f7f3d68338b00d45d53.nq.gz
    ├── 507602afc60f16253cf974d06dca32e8ad7ce0f7.nq.gz
    ├── 5084d214247a91e65ff8f6f90d8fe1b813a4a761.nq.gz
    ├── 511622c438c805fffe41081b32251fcd1adc0e83.nq.gz
    ├── 511aa833fa5029a9eea7a53254c9a9cd4ef89068.nq.gz
    ├── 5143b42623c58020a2fd7fc2b97354d72967c201.nq.gz
    ├── 5145edbe90aaeb5e4bd64865f72f03bc6aab7686.nq.gz
    ├── 5242c14a76aaba0fba144498c9dbcb15aa1b5936.nq.gz
    ├── 526163dae71aeb35b9f7b223f9a587d632f2c754.nq.gz
    ├── 52bdacb985573288d878092f6e5779a0568d8161.nq.gz
    ├── 52f5d0ef2743879f3613484a576d2961265ae4d4.nq.gz
    ├── 5380bdfcca8865b38bf530391969a88eecf75ced.nq.gz
    ├── 53cc4b03a03694cfd6a4ca0b7d4d6ac1758396e2.nq.gz
    ├── 53d078376e956f79ca332ac858e7bc83037f6894.nq.gz
    ├── 54fe505e78ded603024c5686c00ddc516a7c0701.nq.gz
    ├── 55a7f8c7c4f749b3a9560877d0a13d6f0c9671d5.nq.gz
    ├── 55cb1fffffd15f9171e976763a664f74aa5ea2b6.nq.gz
    ├── 567c03956f34d91b572626d2e34e42ae93de165f.nq.gz
    ├── 56cd91ea27ac61bfcacf6c4c5b5892400ec86cbc.nq.gz
    ├── 5784d243419d22361b1fe8df44dd3944c1da4d78.nq.gz
    ├── 578d970db7dbbe42037f3758253298abc3594b7a.nq.gz
    ├── 57a937cbadd54bf91bd4c489d2cfd1e7bfac3a1f.nq.gz
    ├── 5857b3d3a3ce98bd4b916fb624b935e6ee91f67e.nq.gz
    ├── 5865ccc1286276f0722944879ba721d4fff3c98d.nq.gz
    ├── 589c04c3adcee9b5772f0ba08fc05678212f8cdb.nq.gz
    ├── 58e4feb1ca0c4250fc13b10a1a465ce6604a0dba.nq.gz
    ├── 5902af992fe068e6ea0d6a44d1b36721ce053a5f.nq.gz
    ├── 5931a29abb947cc2bc1dface047d473e6febb3e3.nq.gz
    ├── 5aaef9bcc0cc6332c96457b7c30e4a8e88dc3cab.nq.gz
    ├── 5abcd375718ef9b5795f9061bb5bf1ad63d4683f.nq.gz
    ├── 5aff668f3d4656699db6452e1260ab7afd6da8d4.nq.gz
    ├── 5b532282aa49f1089f0ad37ce14b58be96c47afa.nq.gz
    ├── 5ba61d7dba81cb1fd7ce86778faba5b11407f466.nq.gz
    ├── 5bb60e82ce3c120abbd1dbc4c2990138cadf31df.nq.gz
    ├── 5d4c4af6faf0c1f5da546eed3b54c2213d4b7d19.nq.gz
    ├── 5e2db04e2ad4336543dfcaaebc63310842f51dae.nq.gz
    ├── 5ecff08c2277b5e4b8b5c504b6625d2f555343ee.nq.gz
    ├── 5f16f37dfd7fb5253928639c452f5cebf8c182c4.nq.gz
    ├── 5f668d4fa71a6a7abe71f7b1354cfdc3155d1bc9.nq.gz
    ├── 602b5b8838f8257889c1f0e2401787e323870a42.nq.gz
    ├── 60573d98f98502cb41178fd93f7f30cf7095d3b7.nq.gz
    ├── 609cc0458cafc1829ff012ce4f3fde1ed247fc30.nq.gz
    ├── 615d490fee523772c24a47eacd584e8493a1877d.nq.gz
    ├── 61694c8e62ad02910b3e83fe48d2cbc78275d22a.nq.gz
    ├── 62211e0d59c74faf550c668c49c7ce7afa66afd8.nq.gz
    ├── 62c29950897208458c498aef35bab957ad769e7c.nq.gz
    ├── 631cca69fb39ffdb03610ead1fec6607a1814986.nq.gz
    └── 63280f8d67c24a192e9a5bbe8fb385381425aba0.nq.gz

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

[deepchecks/deepchecks](https://github.com/deepchecks/deepchecks)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
