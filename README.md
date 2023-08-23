# Pavilion2 Simulator Documents

本仓库是Pavilion2自动驾驶仿真器说明文档的开发仓库，如需查阅请移步至[Pavillion2 Simulator 官方文档](https://docs.pavilion2.org/)

This repository serves as the development hub for the Pavilion2 Simulator documentation. For reference, please visit the [Official Pavilion2 Simulator Documentation](https://docs.pavilion2.org/).

## Document Technology

本文档工程使用Markdown语法编辑，使用[Obsidian](https://obsidian.md/)作为编辑器并使用[Obsidian Publish](https://obsidian.md/publish)服务建立文档web页面。

The documentation is written in Markdown syntax and edited using [Obsidian](https://obsidian.md/) . The documentation is also published as a web page using the [Obsidian Publish](https://obsidian.md/publish) service.

基于上述因素，本文档中可能存在仅供[Obsidian](https://obsidian.md/)解析的特殊Markdown语法，使用其他Markdown编辑器如Visual Studio Code或者Typora时可能得到不正确的可视化结果。因此，我们建议您在进行文档工程的编写时也使用[Obsidian](https://obsidian.md/)作为编辑器以确保一致性。

Due to the above technical factors, the documentation may include Markdown syntax that is specific to Obsidian and may not render correctly in other Markdown editors such as Visual Studio Code or Typora. Therefore, we recommend that you choose [Obsidian](https://obsidian.md/) as your editor for consistency while working on this documentation project.

特别的，由于[Obsidian](https://obsidian.md/)可以使用第三方插件来强化其功能，使用插件可能会引入新的特殊语法构成。因此在本项目中，[Obsidian](https://obsidian.md/)编辑器除[Obsidian-Git](https://github.com/denolehov/obsidian-git)插件外不应当设置或引入其他第三方插件。

Please note that Obsidian allows the use of third-party plugins to extend its functionality, which may introduce new and specific syntax constructs. Therefore, we recommend that you use only the [Obsidian-Git](https://github.com/denolehov/obsidian-git) plugin in this project and refrain from introducing any other third-party plugins. This will help maintain consistency and avoid potential issues with conflicting syntax.

## Multi-languages

本文档使用简体中文和英文作为标准语言，两种语言以段落为单元并列出现，中文自然段在前，英文段落在后，正如您在本README文档中看到的那样。其中简体中文是本文档的初始编写语言，英文由中文翻译而来但经过了人工校对，因此两种语言均是可信的。

This document uses both Simplified Chinese and English as its primary languages. The content is organized in paragraphs, with Chinese paragraphs appearing first, followed by their English counterparts, as you can see in this README document. Simplified Chinese was initially used for writing, and the English translation has been carefully checked for accuracy. Content in both languages is equally reliable.

如果您需要将本文档翻译为其他语言，请Fork本仓库进行修改发布，但在修改时请保留原始语言中的至少一个。

If you wish to translate this document into another language, please fork this repository for modification and publication. However, when making changes, please ensure that at least one of the primary languages is retained.

需要特别声明的是，部分内容使用了[DeepL](https://www.deepl.com/)以及[ChatGPT](https://chat.openai.com/)进行翻译，可能存在一些谬误，我们欢迎您随时指正。

It's important to note that some of the content has been translated using [DeepL](https://www.deepl.com/) and [ChatGPT](https://chat.openai.com/), which may contain errors. We welcome any corrections or feedback at any time.

## Contributing

对本工程文档的编辑按照一般开源项目的方式进行，您可以提交[Issues](https://github.com/Pavilion2-Simulator/Pavilion2-Documents/issues)、[Pull requests](https://github.com/Pavilion2-Simulator/Pavilion2-Documents/pulls)或者在[Discussions](https://github.com/Pavilion2-Simulator/Pavilion2-Documents/discussions)上进行讨论。

Editing of this project's documentation should follow the typical conventions of open-source projects. You can submit [issues](https://github.com/Pavilion2-Simulator/Pavilion2-Documents/issues), create [pull requests](https://github.com/Pavilion2-Simulator/Pavilion2-Documents/pulls), or engage in discussions in the [Discussions](https://github.com/Pavilion2-Simulator/Pavilion2-Documents/discussions) section.

## Publishing

本文档工程的发布使用了[Obsidian Publish](https://obsidian.md/publish)服务，并发布在[Pavillion2 Simulator 官方文档](https://docs.pavilion2.org/)处。发布的审查与实施由人工进行，使用且仅使用最新的 `origin/main` 分支版本。因此，发布版本内容可能延后于 `origin/main` 分支处的内容，且部分内容可能不会在发布版本上出现（例如本文档）。

The documentation for this project is published using the [Obsidian Publish](https://obsidian.md/publish) service and is available on the [Pavillion2 Simulator Official Documentation](https://docs.pavilion2.org/). The review and implementation of these publications is done manually, using only the latest version of the `origin/main` branch. As a result, content in the published version may lag behind that in the `origin/main` branch, and some content, such as this document, may not appear in the published version.