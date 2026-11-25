# wohuishuo

北京理工大学计算机科学与技术本科生，正在找后端、Android 或 AI 应用开发实习。我主要做书域阅读器：读者能在手机上离线读书，也能针对书中的一段话提问，随回答拿到对应原文。我使用 AI 协助开发；需求、技术取舍和结果验收由我负责。

## 可以直接看的作品

- **[书域：原文问答的 Java 实现](https://github.com/wohuishuo/br-ai-service/blob/main/src/main/java/com/bookrealm/ai/service/RagService.java)**。这个早期版本先从书里找出最多三段原文，再把段落和编号交给模型。没有配置模型密钥时，读者仍能看到检索结果。
- **[星落：Android 下载器演示与安装包](https://github.com/wohuishuo/xingluo/releases/tag/v1.2.0)**。用户选了 720p，旧版实际保存的却是 360p。我修正了下载回退时的画质选择，用同一视频在 Android 16 模拟器上复测：保存文件从 640×360 变为 1280×720。
- **[书域：让网页和 Android 用同一套界面样式](https://github.com/wohuishuo/book-realm/pull/4)**。之前两端要各改一次颜色、字号和间距。这次改动把它们放进一份 JSON，分别生成 CSS 和 Kotlin，提交时检查两端是否同步。

## English

I study Computer Science and Technology at Beijing Institute of Technology and am looking for internships in backend, Android, or applied AI development. My main project, BookRealm, is an Android reader with offline reading and passage-based Q&A. I use AI coding tools, choose the implementation approach, and verify the results.

In [BookRealm’s early Q&A service](https://github.com/wohuishuo/br-ai-service/blob/main/src/main/java/com/bookrealm/ai/service/RagService.java), the model receives up to three numbered passages; readers can still retrieve the passages without a model API key. In [Xingluo 1.2.0](https://github.com/wohuishuo/xingluo/releases/tag/v1.2.0), I fixed a download fallback that ignored the selected resolution. With 720p selected, the same Android emulator test saved a 1280×720 video instead of 640×360.
