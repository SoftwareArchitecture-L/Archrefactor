## 3Erefactor: 面向架构一致性的智能重构方法与工具

为了应对随着软件的不断发展，业务功能变得越来越复杂，软件的实现不可避免的和预期的架构设计出现偏离，从而导致架构不一致的出现。架构不一致使软件维护变得困难，并且需要付出大量的努力来进行重构。为了应对这个问题，我们推出了工具3Erefactor，它是一个专门针对消除架构不一致的智能重构推荐工具。

 ### 工具核心功能:

   - 代码依赖模型构建和可视化
   - 架构不一致检测和可视化
   - 消除架构不一致的自动重构推荐
   - 交互式代码重构


### 工具演示在线链接：
   中文版演示视频：https://www.bilibili.com/video/BV1UN4y1k7pE/?spm_id_from=333.999.0.0

   英文版演示视频: https://youtu.be/8QMpd9TnsE0

### 文件结构说明:

   1. ##### 演示相关demo文件夹
      - [3Erefactor-demo-video.MP4](./demo/3Erefactor-demo-video.mp4)文件为工具演示视频。
      - json-sample为功能使用的样例文件夹，包含工具输入的样例json文件。
      - sample-project项目样例文件夹，包含工具演示测试使用到的java项目文件。

   2. ##### 文档相关docs文件夹

      - [install-guide.md](./docs/install-guide.md)为工具安装说明文档，包含工具安装调试说明。
      - [usage-guide.md](./docs/usage-guide.md)为工具使用说明文档，包含工具核心功能的详细介绍和使用说明。

   3. ##### 安装包相关install-package文件夹
      - frontend放置各版本的前端安装包.vsix文件。
      - backend放置各版本的后端安装包.jar文件。
      - 安装文件使用GIT LFS协议，拉取时请使用git pull指令，使用zip包获取可能导致安装文件损害。
