# Repolex Knowledge Graph of NousResearch/wterm

RDF knowledge graph data for [NousResearch/wterm](https://github.com/NousResearch/wterm), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/wterm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 615efcde2fb8e1415e7b8f0d8ddc107600c0f48b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 615efcde2fb8e1415e7b8f0d8ddc107600c0f48b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00201a84e95aa045f61f137a1074dc6fde2be2c1.nq.gz
│   ├── 0164da38acede705503485e34b238656211be00c.nq.gz
│   ├── 039ef77e117565e606dae9ca0840d2c854e160a3.nq.gz
│   ├── 03dca2e18d82a253b110302547988f171786e527.nq.gz
│   ├── 03fe3bdd2e59ec523f85fe8b670295de4be0ebbc.nq.gz
│   ├── 06707d59a0572530ff06170f75c50b5552402041.nq.gz
│   ├── 07853d78f85acd8d397fd4a54f554c9e859b8846.nq.gz
│   ├── 07b2926599833be9684a278dc066f2f1bbeb9e62.nq.gz
│   ├── 07f9e4fcf6a58366129b149297efcd34fdeaa391.nq.gz
│   ├── 0afea638e01a3406bdd7aaf071852578248bd9b3.nq.gz
│   ├── 0fc3facd64b165a0c031e159ae95f8815cedbaeb.nq.gz
│   ├── 10625cb9464c0acd3063da74e424f1b49bd5f34c.nq.gz
│   ├── 10943406619cd90e90d75c8f3514ed2b97d9db41.nq.gz
│   ├── 11e5462c39b99b12b7f4f409f2a40241ba60e3d7.nq.gz
│   ├── 11eaef8f635d6b8f1df90ad23f2f520dcff617e9.nq.gz
│   ├── 12170f8051b635f5d7c301b4e11631fafb00af5a.nq.gz
│   ├── 12cee59e194842fd93802f29addcc4dec45dc772.nq.gz
│   ├── 1411c31d79ae4ae5ae602cf131175924ce951d7c.nq.gz
│   ├── 1ab81ec871e7f1b6c7f02107fe449a03aad672ed.nq.gz
│   ├── 1aba2ab23dcd3d91251a815db68a580aa1efe8f8.nq.gz
│   ├── 1b4a294f90c7824905a429f54649d39fecc8e063.nq.gz
│   ├── 1bfbe00095f63806da19f2f86ca945fe65aee4c7.nq.gz
│   ├── 1c30eb3fdaef4a69e5aa1d67b69c8962ddf7884b.nq.gz
│   ├── 1d016edcc530c6faba05d86ec5527e20bd080090.nq.gz
│   ├── 1fb52f99152800931263e260ad766ec2263bc6c9.nq.gz
│   ├── 22098d6fab0983057a82616f092cd64c356c807b.nq.gz
│   ├── 225230fd5e4ef20a3da444064546f624c293bc64.nq.gz
│   ├── 232dd8006a7655b4939f570c974d54c819308867.nq.gz
│   ├── 268174fcb00303254c8533bb11ccc16d0ccc2a0f.nq.gz
│   ├── 269a8c3d708dfc014f3e065b382ba74b05d7c5aa.nq.gz
│   ├── 276a7c5ea2480efee1740326ddbd26e5670cb171.nq.gz
│   ├── 27f14e397cba50f2f0ec6fd1b61da7832b37879c.nq.gz
│   ├── 28e1aa8678e58149418b67607880ac885f3fa36d.nq.gz
│   ├── 294f5de27af6ef3c5ba6dea9d739845dc7716939.nq.gz
│   ├── 29e81075342fddb1ee64f8b5d5fc09b7e841170b.nq.gz
│   ├── 2a250cac3a9c082c678082fda7f8aa212fbcc32b.nq.gz
│   ├── 2a387c9073850a441761204c7eba3d7cddcf293d.nq.gz
│   ├── 2ad2b210a8741c4d6843122c737697759b6d0a15.nq.gz
│   ├── 2c6a0ff504e8683bcb1022b55307e5630c5c8979.nq.gz
│   ├── 334d3b2ae918829a591fa5d5445c340234062994.nq.gz
│   ├── 33e195235a4ce0a63ef5e567e40280ec5accd97a.nq.gz
│   ├── 34c04e3d4c2901bd17c84baa50df1e462812ea0a.nq.gz
│   ├── 3603bd1d4f06ac90d7020573986a3ea7d9913922.nq.gz
│   ├── 365058cebd7d2bdb327ca1c081b16e4937e11050.nq.gz
│   ├── 38399c19dcadaa7d2e2e793de17a348acbb76a01.nq.gz
│   ├── 38d3dbbc29e1e36da99d052f9f4873795901a41a.nq.gz
│   ├── 3a2c340baebc577d53bd8f957fc32fe51c99566a.nq.gz
│   ├── 3b8c054216b681e3bdc2d816658ac1496f876ddd.nq.gz
│   ├── 3e17c17d5bec234f8f10021a5d36c2413183116c.nq.gz
│   ├── 40314b3c8b02257b46d683c0fd283fc863d1699d.nq.gz
│   ├── 40e3ecd406f29a77a9cb60857515793698ca5428.nq.gz
│   ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
│   ├── 446b46518e45e40d1addf441817051d6d8bf0861.nq.gz
│   ├── 4762117b8be9035501e27a84b94e3959ec9095c5.nq.gz
│   ├── 4974e8a3d6124489966aefb558fc67b35b2142db.nq.gz
│   ├── 4d7a98577f6a3ec2abb0ef2f2f7a711e4a6d2121.nq.gz
│   ├── 4e7ff20ec6b6399a9435f901fb32e3f2ab623fe4.nq.gz
│   ├── 4f4c0988fd17e78097ea1f68062952fc3d8d0078.nq.gz
│   ├── 4f954ef38e90360b52a8a1e3e5adf77279ddf5a1.nq.gz
│   ├── 50ce10c6e216de558baa776b095e593a1d850656.nq.gz
│   ├── 555229746ded17fb09c31c91e348cbac7f860c7c.nq.gz
│   ├── 577d1a982849e55d73ea58842dadf7683aa5d8ac.nq.gz
│   ├── 5c67e8158d21528b2aba5e9ed19f346569d7ec97.nq.gz
│   ├── 5ca798f71df4e8ea62fd094a3c3fa1428d683969.nq.gz
│   ├── 5de18aee723ee47b56c6f69cc22144ce788f8a7d.nq.gz
│   ├── 5ecac7744fb2dffd491e025d7bd8cedd69610b26.nq.gz
│   ├── 5f6ce515e78ee7ef5d924b02a9e81b61cbcc3b78.nq.gz
│   ├── 61e36849cf7cfa9f1f71b4a3964a4953e3e243d3.nq.gz
│   ├── 6596ee27fe9a549eb7ba5d7b1c866813eac85218.nq.gz
│   ├── 65b4e7b73f78db1ca70ed19cb2b4c9677b52daf5.nq.gz
│   ├── 6646df48aadcec552d3f8c909e316f92ecae313b.nq.gz
│   ├── 66a4788eafc0963aab12cf60f52c3237b1b4f95f.nq.gz
│   ├── 66f47ecb045424a928cc2564246e84db1032e36a.nq.gz
│   ├── 678ea63c2dc87796a6acb407860bb31cf703c46a.nq.gz
│   ├── 6dd84a5c1ce91a5f96853dc666ccd944c9d4a1b9.nq.gz
│   ├── 6f153ceb3c2183570fb6ecb47ee64dee0a118dfb.nq.gz
│   ├── 718d6fea4835ec2d246af9800eddb7ffb276240c.nq.gz
│   ├── 71e5011340a508a2bd11c4e2beb6b0190717f8ae.nq.gz
│   ├── 73db73eccc3b207fdf57c9b0facfd20c8906372b.nq.gz
│   ├── 78bca4add0ae054ebe701f5251e6b86a7a3cd011.nq.gz
│   ├── 7a1b2259912f1b14358205efa5432543a72b3718.nq.gz
│   ├── 7b1dd651c27d103864185b87576c29383090f7f9.nq.gz
│   ├── 7c3eaf612c526726f50b1e5a15a4bfd0d0714a05.nq.gz
│   ├── 7fa0c616fad02de7321083a408c79eb490dfac7a.nq.gz
│   ├── 812329e9a93b3af59bf85596d540459e79402331.nq.gz
│   ├── 828cef5f532a8d9cb7843b0d2861da8184faf5c6.nq.gz
│   ├── 8306944fa4a65a1bb77be080ab29cbb315a2c511.nq.gz
│   ├── 8350c2d04abab2cbc4224b95690473ec13e7a1f3.nq.gz
│   ├── 854fa0025aacecdfd0f3dd2e18e2246130a783dd.nq.gz
│   ├── 8a30ce930221b05b7f8705b35293446b97fa954b.nq.gz
│   ├── 8c440200c0d78cdf7d896cf080c6b642cfddb583.nq.gz
│   ├── 8d71c79931287d62ef5612f169f52f26d242b7f2.nq.gz
│   ├── 8e05adf48e87ca0383cc2bb270cd1704c3ad0265.nq.gz
│   ├── 8e2255621b62b8cf8cbcd740a749d37317180220.nq.gz
│   ├── 900c6da761a9bf7b6d8233745a9d134eaf1b9597.nq.gz
│   ├── 96bb6655f0cccf51340cb7a0b03a3cacd99c4869.nq.gz
│   ├── 9a3526e085730c19abc0e9c624897c32c9b1d154.nq.gz
│   ├── 9af4ce3afc3587a2ddada162f50e01e3bb344385.nq.gz
│   ├── 9b73ea8111a4d1f17e4afffb93e867401c7be597.nq.gz
│   ├── 9c85d89176aaed92209cb89c01689ae31a5772d4.nq.gz
│   ├── 9eb20c0a04de9634a74263a08df1768d99859ae3.nq.gz
│   ├── a13e8ea770a08aeaf47a6cd002b585506c471d0b.nq.gz
│   ├── a2c1a6aad9f91a1d5ae64aa79077aedc3c2a822b.nq.gz
│   ├── a3b019e1d91cf34a8447537456afdab8fc14a566.nq.gz
│   ├── a5ef193506d07d0459fec4f187af08283094d7c8.nq.gz
│   ├── a88e475c4edad6d7094dae61fd1a90191fb800dc.nq.gz
│   ├── ae2df5c1e2ce444cf76fa7425a8dbeb532b22582.nq.gz
│   ├── aefbc0a23d49b1278a66d9ab8c77bdfa3c3f72c6.nq.gz
│   ├── b149fbdaf446db433a866c55a1151de4f09745a4.nq.gz
│   ├── b1fabfa376d236dd2e066432534e9b10c1883369.nq.gz
│   ├── b25181a2c5e212253aba47b400811f3c5a74c562.nq.gz
│   ├── b2b7d34f7734a3b1aedd2c1302a5de99bac1f164.nq.gz
│   ├── b4f40c7656932d10127736413d718fd5bc9b313e.nq.gz
│   ├── b51645daa03d42f8bf96c1eab980dbf3ad7605de.nq.gz
│   ├── b67ea0d66a606da0ce8501c8675c0f552b0bcd40.nq.gz
│   ├── b72406665b98b83647c0a59e3776c6338a6f9132.nq.gz
│   ├── b8fe0ab70d6886ddb828a8640d92cdbd8ae6c111.nq.gz
│   ├── bad52c8b758b823e4c8722a24d68639244ef5923.nq.gz
│   ├── bb23fc0179edbeb0d44a75c43bc6285daacc98c3.nq.gz
│   ├── bb541dd80234757cb00b662c991c5a79fda0f170.nq.gz
│   ├── be5d8540921efff10548ba9fa47dd44f30c11f19.nq.gz
│   ├── c0c953def1ca892aaafce7dc3ba3b166057e92ae.nq.gz
│   ├── c22b69316ef81aab4ff47d3640e8e74f039c714b.nq.gz
│   ├── c2ddf7482206a37d9ae2e5ca0eeddd81b4bde2b7.nq.gz
│   ├── c36bbce77d23405e0fac5dc68068854ad1102c78.nq.gz
│   ├── c37063c9f6faf9d8d9f23b228fed7d4f2752ffe2.nq.gz
│   ├── c3ae243b00f31894ddb9b0c778a14e008956a1bf.nq.gz
│   ├── c757cc508ef69949b6d91f964cf73b303f7e4b70.nq.gz
│   ├── c77e000e530a06d1f043bd4b3a9f9584460d16bd.nq.gz
│   ├── c8507161a5560ece09e8b269dac449e58fb8384a.nq.gz
│   ├── caa0a610af8788ce5bb1672bb94c7b7de6d68e2e.nq.gz
│   ├── cbe469e698f4ff9cf6e956af881539feafb9922f.nq.gz
│   ├── cc0240ef535a7df0261ee5c2d3e3efd8deca504b.nq.gz
│   ├── cd475f80804f97f54f661f9f9fb19cbc755c9e92.nq.gz
│   ├── cddbf10f7244cda906a1af770b32355515cb94c6.nq.gz
│   ├── d1ca4f564be4a45a4e176a6474fbda13028f4bc4.nq.gz
│   ├── d28907c6a3cc4ae6b29dd28d32017d325c7ca278.nq.gz
│   ├── d364b78abed666f3a130103bbb075192e133c50f.nq.gz
│   ├── d38b79b69a3550afc471812394164644d3198b41.nq.gz
│   ├── d3bedaa060d60072bcab00674fc315d592a7eccf.nq.gz
│   ├── d4c389b6d7e62b85663e02bc9f9a421df2749e51.nq.gz
│   ├── d774b1310599038e7e9a3cc1fae14101f31c80ef.nq.gz
│   ├── d7fe5cbf74a488c69ef24ee9debacfc443f7f4c3.nq.gz
│   ├── d95edf7b5b10a5a04cf866df1e2bfbf5d7abdbec.nq.gz
│   ├── da3fa653786d8800f293cec1607bd20bb6aba195.nq.gz
│   ├── dad5d95b97c578f5a4e25c3bfd8025515fbe9871.nq.gz
│   ├── dd65e1031da1c8372843133cbf2f4b672a31c2ba.nq.gz
│   ├── dd744d7020187cb36ea75a3f2510522afa64dd7a.nq.gz
│   ├── df60eb5cdc4a0d4b7ea81fdc955e47e1ecdef6ab.nq.gz
│   ├── e03367b58860890c926403182398c757d019074e.nq.gz
│   ├── e0c29b5aafb50e7232791a949747576665da253e.nq.gz
│   ├── e31420efaebd4e3c9065f9229ccf1e8c6a5d2dfb.nq.gz
│   ├── e37a1955ae76edb02ec73f31a56007502958d16e.nq.gz
│   ├── e56489591d5c2745c9a6dba7d9fde8257a661cf4.nq.gz
│   ├── e59a46612701ad2124dd8dcc406e68f6f8d86cdb.nq.gz
│   ├── e75feabcbf7c9eeb4fb0cf8de88e2c457a6f91c2.nq.gz
│   ├── e7ff3a26b4400007243cc9a73fea3d9307e795a3.nq.gz
│   ├── e802f09193c4c786982b4fd10096c758b82aa8d6.nq.gz
│   ├── e9010d3f741bd9477221ac78323b2e50df5e3aee.nq.gz
│   ├── e97d48544ee0ab088c68ebe66bebeb60b069ff3f.nq.gz
│   ├── ec19925eec72776864c5fd5fe5920f220ad1c975.nq.gz
│   ├── ecd9fcb52a730da63cad23ae6d537d9bb118d017.nq.gz
│   ├── ed6ebba12a638bc442017a88ed5373dad6074ec4.nq.gz
│   ├── ede8220b9928860b550c4e73c8c6fec64f525001.nq.gz
│   ├── ef546f4710cde7e8c9057e7791b7382bb2c3f411.nq.gz
│   ├── ef9bedbf4b3f945bfa230b55bab91ee1e8a62fa5.nq.gz
│   ├── f02d9c6fa62eaa1471e26fe757341a3152b8344b.nq.gz
│   ├── f0c76fd343dad4117720178d586eafcd8145a8a7.nq.gz
│   ├── f382eb79e22a42ad32685df41f70ea739f73d65d.nq.gz
│   ├── f3c58ec5feb6081ff0d552b51747a2f9785eb380.nq.gz
│   ├── f443835250120454b0aeb11c2f3e1f445047b3ec.nq.gz
│   ├── f58ae21e02b8fa0a04f5258faca907d6d80a14b9.nq.gz
│   ├── f5dd15223d30ead885d3a1b9b81d9db9eceb91ac.nq.gz
│   ├── f714c03e103adebd7be847efbe0a84f624415184.nq.gz
│   ├── fb5bf86a9a016981bccc9fe8934a51f4faedcc5e.nq.gz
│   ├── fb614790cecc253c52299ef1aca9940dc16fddb9.nq.gz
│   ├── fc03d96260ad66a9cdf352143fdb52e385b0f1ac.nq.gz
│   ├── ff4673d945c4ac1163c0fddfa776224e6358aecb.nq.gz
│   └── ff5dcb3b806b30e779598a830b711061d0f73cf9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 615efcde2fb8e1415e7b8f0d8ddc107600c0f48b.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 185 files
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

[NousResearch/wterm](https://github.com/NousResearch/wterm)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
