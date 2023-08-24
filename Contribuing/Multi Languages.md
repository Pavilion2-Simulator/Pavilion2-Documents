Pavilion2 项目使用中文和英文作为项目开发和文档撰写中的首要语言。通常情况下开发团队使用中文书写注释、文档等文本性资料文件，并通过机器生成、人工审阅的方式将其翻译为英文以确保其双语可信性。

The Pavilion2 Simulator project uses Chinese and English as its primary languages for development and documentation. Typically, the development team writes comments, documentation, and other textual materials in Chinese, and then uses a combination of AI translation and manual review to translate them into English, ensuring the credibility of both languages.

本页面将会用于约定 Pavilion2 项目中使用多语言的若干情形。

This page will be used to establish conventions for the use of multiple languages within the Pavilion2 Simulation project.

## Documentation

首先，我们约定“文档”一词所涵盖的内容：

- [官方文档](https://docs.pavilion2.org/)及其[工程仓库](https://github.com/Pavilion2-Simulator/Pavilion2-Documents)
- 其他Github仓库中的必要 `README.md`

First, let's define what the term "documentation" means:

- The [official documentation](https://docs.pavilion2.org/) and its [project repository](https://github.com/Pavilion2-Simulator/Pavilion2-Documents).
- The necessary `README.md` files in other GitHub repositories.

### Common Cases

通常情况下，文档中的内容以段落为单元，呈现中文在前，英文紧随其后的方式呈现，就像你在本文档中随处见到的那样。

In most cases, the content in the documentation is presented in paragraph units, with Chinese appearing first and English immediately following, as you can see throughout this document.

在一些情况下，你可能会看到单独出现的中文内容，这是由于文档尚在开发中，该内容尚未被翻译。您可以在[工程仓库](https://github.com/Pavilion2-Simulator/Pavilion2-Documents)中提交Issue来向我们反馈这一问题。

In some cases, you may encounter isolated Chinese content. This occurs because the document is still under development, and that particular content has not yet been translated. You can provide feedback on this issue by submitting an issue in the [project repository](https://github.com/Pavilion2-Simulator/Pavilion2-Documents).

### Titles

正如本文章所展示的那样，本文档中所有的标题元素，仅允许使用英文，其要求范围包括：

1. 文档中所有的 Markdown 标题
2. 文档工程中的文件名与文件夹名
3. 文档中 `Callout` 的标题

As demonstrated in this article, within this documentation, all header elements must be **in English only**. This requirement includes:

1. All Markdown headings within the document.
2. Filenames and folder names within the documentation project.
3. Titles of `Callouts` within the document.
### Lists

当遇到需要以有序列表或无序列表呈现的内容时，该列表属于它上方的段落，应当合并翻译，就像是这里示范的一样:

- 示例列表内容1
- 示例列表内容2

When you encounter content that needs to be presented in an ordered or unordered list, the list is associated with the preceding paragraph and the translation should be integrated, as shown here:

- Example list item 1
- Example list item 2

### Tables

表格在文档中属于独立的单元，通常来说表格内的每个单元格内应当包含双语翻译内容，译文与原文之间以 `<br/>` (HTML换行符）隔开。但若出现以下情形时，**仅允许使用英文**：

- 代码
- 程序的输入与输出
- 专有名词或常用缩略

Tables in the document are independent units. Generally, each cell in the table should contain bilingual translation content, with the translation separated from the original text by `<br/>` (HTML line break). However, the use of **English only** is allowed in the following situations:

- Code
- Program inputs and outputs
- Proper nouns or common abbreviations

表格的示例如下：

Here's an example of a table:

| 编号<br/>No. | 状态<br/>Status | 类<br/>Class   | 说明<br/>Describe                                       |
|----------|-------------|-------------|-----------------------------------------------------|
| 1        | BUG         | `UMyObject` | 无法找到 `UMyObject` 类<br/>Can‘t find `UMyObject` class |
| 2        | OK          | -           | 示例内容 <br/>Demo Content                              |

> [!tip] 
> 由于Markdown语法下的表格编辑非常繁琐，因此建议尽可能减少其使用
> 
> Due to the cumbersome nature of table editing in Markdown syntax, it is advisable to minimize its use whenever possible.

### Image & Graphs

图像与图表对于Markdown格式的文本文档而言属于外部内容，通常无法在文档中直接编辑，因此在制作时应当考虑到多语言的兼容性。图像与图表是一个单独的单元，其中内应当同时包含中文和英文。

Images and graphics in Markdown text documents are considered external content and typically cannot be edited directly within the document. Therefore, multilingual compatibility should be considered when creating them. Images and graphics are treated as separate units and should contain both Chinese and English content simultaneously.

“图像”在这里多指屏幕截图或照片，我们不对图像内的文字做出要求，但是如涉及到操作，请在上下文中提供对应的内容翻译，如以下内容所示：

"Images" here refers primarily to screenshots or photographs. We do not need to translate the text within the images, but if there are any relevant actions or instructions, please provide the appropriate translations in the surrounding context, as shown in the example below:

![[Pasted image 20230823210942.png]]

> 示例操作的顺序为：[文件]->[新建文件]
> 
> The sequence for performing example operations is: [File] -> [New File]
> 

”图表“在这里指数据图、流程图等内容，其中所有的内容应当以双语的形式呈现，如果遇到空间局限排版困难时，**允许仅使用英文**，如下图所示：

" Graphs" here refers to data graphs, flowcharts, and similar content that should be presented bilingually. If space limitations make formatting difficult, it is allowed to use English only, as shown in the following example:

![[Pasted image 20230823214354.png]]
## Development

在开发的过程中，多数情况下会使用英文作为主要语言，但为了增强项目的可理解性，在一些情况下应当或允许提供多语言支持。

During development, English is usually used as the primary language. However, there may be cases where it is necessary or permissible to provide or allow multi-language support in order to enhance the understanding of the project.

### Code & Script

所有的代码与脚本内容仅允许使用英文。

All code and script content must be **in English only**.

```
Int64 myInt64;
class MyClass;
```

### Comments

代码的注释应当使用两种主要语言其中之一编写，并应当尽快的翻译为对应的译文，示例如下：

Code comments should be written in one of the two primary languages and should be promptly translated into the corresponding language, as demonstrated below:

```
# 用于示例的Int64变量
# An Int64 used for demo
Int64 myInt64 = 123;
```

### Art Assets

在 Unreal Engine 中出现的所有美术资源，如贴图、模型、骨骼、动画等内容，其外部名称（文件名）与内部名称均应当使用英文。具体的命名规范请参考[虚幻引擎项目中推荐的资产命名规范](https://docs.unrealengine.com/5.2/zh-CN/recommended-asset-naming-conventions-in-unreal-engine-projects/)。

In Unreal Engine, all art assets such as textures, models, skeletons, animations, and other content should have their external and internal names (file names) in English. For specific naming conventions, please refer to the [Recommended Asset Naming Conventions in Unreal Engine Projects](https://docs.unrealengine.com/5.2/en-US/recommended-asset-naming-conventions-in-unreal-engine-projects/) documentation within the Unreal Engine project.

```
BP_Car
```

> [!warning]
> 特别的，禁止在任何情况下使用汉语拼音。
> 
> In particular, the use of Chinese Pinyin is prohibited in all circumstances.

### File and Folder

在开发中的所有文件与文件夹都应当使用且仅使用英文命名。

During development, all files and folders should be named in **English only**.

```
Folder1
Folder2
 |- File1
 |- File2
```

### Licience

在开发中存在的版权声明、开源协议等应当使用且仅使用英文。

Copyright notices, open source licences and similar legal documentation in development should be in **English only**.

```
# Example MIT Licience

Copyright (C) <year> <copyright holders>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

## Git & Github Cooperation

