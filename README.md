# Repolex Knowledge Graph of clap-rs/clap

RDF knowledge graph data for [clap-rs/clap](https://github.com/clap-rs/clap), parsed by [repolex](https://repolex.ai).

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
lexq download clap-rs/clap
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9ab6dee710aa384e02ec5e9e2cfeadb2f35abf2a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9ab6dee710aa384e02ec5e9e2cfeadb2f35abf2a.nq.gz
│   └── repolex
│       └── 9ab6dee710aa384e02ec5e9e2cfeadb2f35abf2a
│           └── chunk-001.nq.gz
└── blob
    ├── 003726318744d1b5739bf357f4dd1d88ae373f24.nq.gz
    ├── 0090fd7b5e113f1e36978b7e31987780f7b7e2bf.nq.gz
    ├── 00b742d09155bea007e67f941c597c9f837d3b6b.nq.gz
    ├── 00ce589234d934dd9176e4b2b68e836e8c26d6ce.nq.gz
    ├── 01480e22f2d075c03e844fe392369e442998a666.nq.gz
    ├── 0192a76fd26b100e35e341789016aaf7f6c2021d.nq.gz
    ├── 02657848482c58f1de3e2d5eb142829fbc4a509c.nq.gz
    ├── 028c83a85f0c463324c98675e5448895945b94df.nq.gz
    ├── 03a926ca85b6cfed46d3b254a367405db27272db.nq.gz
    ├── 03f2c65c69a9eca94194fb6782c4230bd2e57c6f.nq.gz
    ├── 045923c477113e74a52bddda81c8fe6d6456ab46.nq.gz
    ├── 045ca437fe762286f263850dccb445432f886ec9.nq.gz
    ├── 057274012c7e5dd9bd82dd26618947769b2e3756.nq.gz
    ├── 05d95b4e51c41876cfdbd5e9ee24e246270eabaf.nq.gz
    ├── 060285be832927bdd85bd774e106104161d8c98d.nq.gz
    ├── 067ae9e2d747b812c40b54b2dfcc336698bc6ebc.nq.gz
    ├── 0757758c8eb7bd553186eb86963ee856ae8f0840.nq.gz
    ├── 078f4d4567095617bddac79e8037869af8ec7965.nq.gz
    ├── 07c14013b02163c4400af6f0cf1a36d7a323d2e2.nq.gz
    ├── 0886d273f2ac50f26ae3199ac971d6da7ef01cbc.nq.gz
    ├── 0a6df92984ff6372d7840feb31d1566e8b54d9e4.nq.gz
    ├── 0a83eb9b8e6ee65c2e14195124a8ad22c48402c6.nq.gz
    ├── 0b31a3c4a9629c718a5049f57bc75174e195ac60.nq.gz
    ├── 0bbbd8a6fc248d3b0e3041d2871b0388830642c3.nq.gz
    ├── 0c1597a1564d31b08fe30b609c9df60c4bf33ddf.nq.gz
    ├── 0c524bde53495dbcab1427a14f3c9032a4b38a0d.nq.gz
    ├── 0c894e18ab869414112de882fffcffbb54a57746.nq.gz
    ├── 0c992672953ab5dfe51ea28fb83d3e5142169681.nq.gz
    ├── 0ce53d654472314e812c53ea27a9c6736f8bc523.nq.gz
    ├── 0d925ce8aa375c3393b8f4db379559c513f667c8.nq.gz
    ├── 0df1274e152149cf2a87baca9d6a108dfb1eca78.nq.gz
    ├── 0e76a72d8ad417db4b18dc41c829f6a0fb7dd295.nq.gz
    ├── 0eb1f4e6b786b4d82aa186b1b02aed7994577eb4.nq.gz
    ├── 0f207a9999f2a83053df1cff8b63952e463927d5.nq.gz
    ├── 0f6c44f253f430720eb7932ba17241a247e403db.nq.gz
    ├── 0f7b928ba35303f0d06d0aac2d49fccd2d5c85ab.nq.gz
    ├── 0ff6d14e736179930fca1571d6d7714a446154da.nq.gz
    ├── 126a92fae999a17120ede5719a8807595b95dfe1.nq.gz
    ├── 13984b8bd1816d432a22416ac98b81b30f0a1b21.nq.gz
    ├── 13fa0f8fcae72c3b06f9d6e954921095ccc19e47.nq.gz
    ├── 14592ad0a9ef8b7226806493455ceb9f1aa0d3cb.nq.gz
    ├── 14f189adf88a3851808bd36615c4c56ce161950b.nq.gz
    ├── 1583de5f0b6003815e0c57ed9a5b22543c59316d.nq.gz
    ├── 162b0bc8632ebfe23f06f2f319c2bd964a3d16fb.nq.gz
    ├── 1658f779c1e78c19b8728d96ba179f0390996bd2.nq.gz
    ├── 16eaffd8e92961770197bed93dbdb770ae599c56.nq.gz
    ├── 17169e821ad838a8eb35dc42cc70083f0a787831.nq.gz
    ├── 174ddd9f7ba2afebc7a87ec6702a0a784835f88b.nq.gz
    ├── 18976de0770ed6940854b51b6afee43dad9d6eb2.nq.gz
    ├── 18d1486cfea14a2a8bc4d9b7b096fcfe8771ac77.nq.gz
    ├── 192356157b7068f70eae279f51024ebf9681e08b.nq.gz
    ├── 19a667b1ae6d9a4781b5b862ba8cb2dbfb0c6482.nq.gz
    ├── 19aa82b4f1cbe7b8ac6d0afc832c96d8a312c63e.nq.gz
    ├── 19d87787d2ab5c2d268426c199b21d0a4e50df4f.nq.gz
    ├── 1a601d847cc59999494bf7cef84db5bdc984f8b2.nq.gz
    ├── 1b0d684fac80eb972f9b4048f4b748e3e80d9568.nq.gz
    ├── 1b3a323e54efd39d853674d82388d94df2729fdb.nq.gz
    ├── 1b8e58d978d0d725ee1ad5d32c5cf6812238bc6d.nq.gz
    ├── 1b932f7eaa59009e293c28b5c7410da985d16535.nq.gz
    ├── 1d25b3ddec1d6075513edfe3e555f864ddb50b63.nq.gz
    ├── 1d2969f07cce462b6b478ddb88abc196e9489079.nq.gz
    ├── 1d4fd850696ddf8d3d0b9e3387d47cb7cf8c66e4.nq.gz
    ├── 1d8019b0e2a634b627fb3be300f01aab76d1d41a.nq.gz
    ├── 1db1e4827c5b4b581d3af0a6df75d3b7217cf7d5.nq.gz
    ├── 1de60f7b079122270f85946ee0ebbad80004884f.nq.gz
    ├── 1e0cb3f20e7ade11fce3a7d1dade5085c07af6e8.nq.gz
    ├── 1e4b60dcd16c464665614a6c024e3313dbb31042.nq.gz
    ├── 1ef0afe670ed5f0a1ad47d763f1391425ebc4d55.nq.gz
    ├── 1f21ba3cb0fd4b967539d9dad1086037e27e6470.nq.gz
    ├── 1f7cc02211710f6686f20890f1f10a88a7bce827.nq.gz
    ├── 1f8a1d26c7c2cfbe3031dee79aec347697de276a.nq.gz
    ├── 1f8b071b194fb99d8facea2c804eb1480e9dacdc.nq.gz
    ├── 1fac68432be72aee494bd2c271fe7ab684ed9733.nq.gz
    ├── 1fbdc7531ab92f1ee1ed7eaf4df3d2d0928968cf.nq.gz
    ├── 209363a57b31328cb46d7d3a6cdd623bf0170037.nq.gz
    ├── 21a6c10f8eefc765b726da4475e116efaf8edadf.nq.gz
    ├── 21bbfe1a65bdc4fe05809fdb891e2945e480b0be.nq.gz
    ├── 22dda094153b26a661c43cb9b65498765de3afec.nq.gz
    ├── 231726afa686c0212f0a412dc050e64f814db6a7.nq.gz
    ├── 2371b5afc369c7a14a05106bfb30ccc8779c353b.nq.gz
    ├── 24183696c0d04bd8bc1b5da43af900551731890e.nq.gz
    ├── 241d7c7d57cbcd2ad6648969a59bc6fd5300acde.nq.gz
    ├── 244bb5da409bb4875d192d4d3fa324f3f5aee8bb.nq.gz
    ├── 24733787a30efaa8a2059ae4d318943929178218.nq.gz
    ├── 24d44889aca1c6d599e3488a4cecf0836865333d.nq.gz
    ├── 2557d92d27a8c2643ef0849e9394970f3d28aea2.nq.gz
    ├── 2633f17df519e1ddeb115885d8da6d67843fbb66.nq.gz
    ├── 26b342a092578e43786e1b8344f8c68214381167.nq.gz
    ├── 2713a9010bf5c38483777b4b6528e30028489ee8.nq.gz
    ├── 27bf59a884cdc6948c686a9eb9b3f0fe99691c95.nq.gz
    ├── 27d33e5f572dc05857d7d4a6e3a1bf01ca0ca857.nq.gz
    ├── 2807d9d9170104dd2fd2599a5594b1866120ed54.nq.gz
    ├── 282048bc1752e796205c17ca24555b98a948af0b.nq.gz
    ├── 287ffd3da0371f28a28dea2111505c6c5ea124df.nq.gz
    ├── 29a74ee4a9a83e0153a0d07525265b4018948679.nq.gz
    ├── 2b53afb7e02f557dac5953e560267f0872f6ef7d.nq.gz
    ├── 2c393a3e74935a9f7afbfeb456953e5caec06298.nq.gz
    ├── 2ca11c665d21677b88d0ac2e26ad6e91355c6135.nq.gz
    ├── 2e29bdd3055f51b8b8970e927dcb342f94a69503.nq.gz
    ├── 2eadb8a1e098f83e85391ed762d55cf1cb0099e0.nq.gz
    ├── 2f037969eb46157fab09f2efdacc11e24f1aceea.nq.gz
    ├── 2f6004c7131e02477d15aa307eab4d257fb543b1.nq.gz
    ├── 2f605efa14ef1deae708fe507aa13d4b7830a22a.nq.gz
    ├── 2f8e29d8eaed39bb3ca419622fe4697f7414112c.nq.gz
    ├── 3024efd04810f7ab55a0e25c2fddf18a47e79c62.nq.gz
    ├── 306aa053da1381edb6f69b7b4a684ddec10671fc.nq.gz
    ├── 30a8a9946745d69f45cd750bda81c05f22637863.nq.gz
    ├── 3187af5239d439868bb532d2519a0062cf0b510c.nq.gz
    ├── 32475f0d6476e65bf213f7c44213856f24a1f417.nq.gz
    ├── 326cf42298ca29b015b2b59413f62d103b376464.nq.gz
    ├── 328dd092b0f02c1930ce9d8a9d1f4c729181a456.nq.gz
    ├── 329824b890e1d1333702bf65771932cf143a7b75.nq.gz
    ├── 32f566e716ce72caea3c3bcc19f1cc8e15009ff4.nq.gz
    ├── 3319719950259fbaadcf026e181ca27c2a0adc5b.nq.gz
    ├── 337e326b20f81b0c51ac1964d00b9e9caf5c9930.nq.gz
    ├── 3397d33e2a52822fa252e25ce1ea4c96b78bbb52.nq.gz
    ├── 341aa1838d6f2aa0948c7181c7b52e63c9a3a98b.nq.gz
    ├── 341cc0f29884de01672dc8e82e8fc5e944cd82a5.nq.gz
    ├── 342ad3c08ac84a21deba3505efd474299378ff51.nq.gz
    ├── 34407eb97b64ce62b780df638eb14cebfcd40a87.nq.gz
    ├── 345e503a1730897b90d78ea2301812865f536584.nq.gz
    ├── 351ae4de20c0f8fa709807142f2001aea2469060.nq.gz
    ├── 358f0653e534688dcd68256f0d9f1966def68daa.nq.gz
    ├── 35ee1bf35c64c0bae3e6ae004ba33b588fd6effc.nq.gz
    ├── 35f186638f253cbfde2da55b5c1c7cb3af5e37fa.nq.gz
    ├── 360462a83c696e0affbd4cd6e294b5bbb5e8a66f.nq.gz
    ├── 36192e195ada8b1ad8c420d59643e35ebcc2ad4f.nq.gz
    ├── 364e43b11953313b437739aff310e8c107d60541.nq.gz
    ├── 369d9c04b8545aa6347b27f56cf9a251e4c0ac08.nq.gz
    ├── 36aac09323aef0a4499041e5f5c46c337e9234b7.nq.gz
    ├── 37214f20381c2d57630dc3bbd585635f1708d5ec.nq.gz
    ├── 374a9e786b1c6bb930f4706ff076bafde81bd0e3.nq.gz
    ├── 374f84d779fb560f267877461df8fefc94ed3d97.nq.gz
    ├── 375119127f242a5c1a6034fee396ee2192b3db3a.nq.gz
    ├── 37f8b0ba7398afa33cbd4b72a76d08ef7d956c94.nq.gz
    ├── 383f5f68a0edc132a81fc84d1631691bdc20153b.nq.gz
    ├── 3a189315eae4bc173500387adfd96dcf3187a613.nq.gz
    ├── 3a5135308d7bfb35794f0b0719e91b487149302b.nq.gz
    ├── 3aa8e8f89fabce8eaa157576237a40278ed2fedd.nq.gz
    ├── 3ac9a95e7847c0f489e45adc880a7ba844d81b52.nq.gz
    ├── 3ae0677440280e4a899815d8efd2d2167929a2ad.nq.gz
    ├── 3c3f66318f27200350c7503f5f260a4aa119b1a9.nq.gz
    ├── 3cadf2652e16f06528e3076e5bdb69df5d6f7a3f.nq.gz
    ├── 3da7aca74b69c7d3949801e38973f56266fa77c0.nq.gz
    ├── 3dcc1582044a62d580b696c332ccf14803107bd6.nq.gz
    ├── 3ef7991a6216abc594e45451bcd15a26ea39d65a.nq.gz
    ├── 3f6446064090a82ae337a0aea1cca5f31a4bf7bb.nq.gz
    ├── 3f7beb32cbda5033440497e0196e03104871bfd3.nq.gz
    ├── 3ff084d834a2ae73bcdf3a37a4c778a72f017173.nq.gz
    ├── 405f7793baf935bf07b7807d26634cea40449de3.nq.gz
    ├── 408fc3c0224657d3f57265e30fa4cf0ac74486d8.nq.gz
    ├── 40d3760e81bc7a9773e14f34e87d10eeff37e838.nq.gz
    ├── 41ca7cec320c3e81eb574a1186e17e718dace358.nq.gz
    ├── 41e122bacf4a92441f4272d1f5273e5d1ac42169.nq.gz
    ├── 4211ae3842810ba7207dfc2148a5354e28276bda.nq.gz
    ├── 429e6358f0302fd5c397cfb89fc43c0f3ce416a7.nq.gz
    ├── 42b81fd42664af1d99724980fef9c16aaf8ac36a.nq.gz
    ├── 439ef57229de950302d40191e0964ed397005df1.nq.gz
    ├── 43a80c19c4540d06ae6a1671c659708501477e81.nq.gz
    ├── 441ca948d911b5ee15d2ea170c8a17bb95f9a20c.nq.gz
    ├── 444137478698fa3d555658a03f3ce6e7e55c5fc7.nq.gz
    ├── 4459174fc18687c1fe9cc6e09674d5edad3f9a78.nq.gz
    ├── 4646e320a079a9e2a340c223409a4a5bd5c582c3.nq.gz
    ├── 485d77d4cec40fca39e174348923b77ff08b4c81.nq.gz
    ├── 490299130200ece2934f325de25eb0481712a228.nq.gz
    ├── 490f4e2e52a3e9f654f87909354bf97e905165b2.nq.gz
    ├── 4a6a1abdd612113aea698f0f51e28cb675ea8ead.nq.gz
    ├── 4a7323bc95f253ee2673fde8a47c796b94b2b258.nq.gz
    ├── 4acf76529747348c5aed234b7d464d73d893dce7.nq.gz
    ├── 4b4cd39a2d2d0f3b8a9ba41ce21ab49514c5f86d.nq.gz
    ├── 4b8b0945dbcf53cbbbe342b53e45cd066fe9bcaf.nq.gz
    ├── 4d5f72c155bf17c4dd670d649ff2d3d66f7d7fa4.nq.gz
    ├── 4e6cccfb72d0fbc6675fee0886dd80de71c27dcd.nq.gz
    ├── 4f5876ea6df56ad629dec0e1e3ecf7d553228dc4.nq.gz
    ├── 500d77a8700f2ffe71c819c94c33caf7fdbcbedb.nq.gz
    ├── 51cbe75d2a286f615e8df17e667322df26a137b9.nq.gz
    ├── 51f3dcd2550a9a22fff8d9320c7d86ddfd81be19.nq.gz
    ├── 51f6b4a2d0b57d77c1338c181b66889dad582ad5.nq.gz
    ├── 52aae9e83e2bab5dfe5453d3c2c7db4f37609aaa.nq.gz
    ├── 52f8117b92ce63e8701f3573a69df46adb1a38af.nq.gz
    ├── 537c8fc1b5aa7041b068baf487de5d17bf34df9d.nq.gz
    ├── 53edac4b2dff7634dd2ebda78ccd725d6491e065.nq.gz
    ├── 543010d3e62b79096fde153b09245d4410f5e0b2.nq.gz
    ├── 549ec825908b2731c712e1f98b079e43e3e42490.nq.gz
    ├── 55b896ea67fce69f74565d19002877c65a4a6c28.nq.gz
    ├── 56ef9cafd9117814e3991b37b4f72f69abc64386.nq.gz
    ├── 56fc39857982c58b456e71c236d95bbcea4bc1bb.nq.gz
    ├── 573b43cc79304c0bb722dda73759ed3c1f3e014e.nq.gz
    ├── 5799039734b49cc5a3e73ba13d57ba73587ce221.nq.gz
    ├── 57eeefc6f63cb1149b3e501016426f84c1d5637f.nq.gz
    ├── 583c21e8c51551b8de1df79ff3e5d43c3a3ce279.nq.gz
    ├── 584d9b991359f25c759ad7df8c5ac8ccd6838436.nq.gz
    ├── 5864870fdb7ec29f28e7444601c4bc34987e1569.nq.gz
    ├── 58a9fe34b93fefd60481c960916522fb9ac674f2.nq.gz
    ├── 58eb159f1a16d59c549b9c68cf32e1a0f6da60fe.nq.gz
    ├── 596fbe09db7b6e2328b03486d8ea65f1a6dcfd1a.nq.gz
    └── 5a573aa2ab747737c159edf6ed1fff4472045307.nq.gz

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

[clap-rs/clap](https://github.com/clap-rs/clap)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
