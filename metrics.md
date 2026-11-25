# 公开仓库统计说明

2026-11-25 通过 GitHub API 核对。下面版本均为检查时默认分支的头提交。

- 提交采用固定版本可达的提交列表，检查第二页为空；跨仓库不去重，不按作者过滤。
- 源文件从这些版本的 Git 文件树取出；按项目实现所涉及的语言扩展名计数，排除依赖、常见构建目录和打包文件。115 份内容与树上的 blob 一一核对。
- 非空行是去掉空白行后的物理行数，保留注释、测试以及提交的样式配置；不统计图片、Markdown、JSON 或私有仓库。

| 仓库 | 核对版本 | 提交 | 文件 | 非空行 |
| --- | --- | ---: | ---: | ---: |
| book-realm | [`882f86ea3`](https://github.com/wohuishuo/book-realm/tree/882f86ea3f7170a305c09eb776c112100feb57e2) | 87 | 5 | 184 |
| br-ai-service | [`8a452cf2d`](https://github.com/wohuishuo/br-ai-service/tree/8a452cf2d357efb97d7d200d094e3a17fec81190) | 7 | 13 | 518 |
| br-reader-app | [`f98fed29e`](https://github.com/wohuishuo/br-reader-app/tree/f98fed29e204237e57a7fecf0c5bbd2f371c230e) | 24 | 30 | 3323 |
| user-center-team-project | [`e978a4eb2`](https://github.com/wohuishuo/user-center-team-project/tree/e978a4eb2e3e57c3fd4adf30b7674822a69ed9b6) | 27 | 45 | 2182 |
| xingluo | [`d7414b35c`](https://github.com/wohuishuo/xingluo/tree/d7414b35cc4f6dc11c4b65e180d39cb79ca1fa6b) | 3 | 22 | 1475 |

机器可读数字：[metrics.json](metrics.json)。
