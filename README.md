# 中文文档编制规范

为中文文档提供一套默认编制规则和 Word 起始模板，适合个人写作、团队协作和工作交付。已有指定规范或模板时，优先采用指定要求，再用通用规则补齐。

## 使用

从 [GitHub Releases](https://github.com/woshiheihei/chinese-document-standard/releases/latest) 下载技能 ZIP。解压后，把整个 `chinese-document-standard` 文件夹放进技能目录。在 Codex 中，可以放到项目的 `.agents/skills/`，也可以放到用户级目录 `~/.agents/skills/`。如果技能未出现，重新打开会话。

可在对话中显式调用 `$chinese-document-standard`，例如下面两种用法。

> 用 $chinese-document-standard 把这些材料整理成一份供同事执行的 Word 操作说明。我们没有固定模板，做成能照着执行和核对的版本。

> 按附件模板排版。用 $chinese-document-standard 检查模板没有规定的部分。只修格式，保留原有内容和编号。

## 包内文件

| 文件 | 用途 |
| --- | --- |
| [SKILL.md](SKILL.md) | 适用条件、规则优先级和工作步骤。 |
| [字段与版本规则](references/document-rules.md) | 判断何时加签审、附件、版本和分发记录。 |
| [通用 Word 版式](references/word-layout.md) | 字体、字号、页距、标题、目录和打印要求。 |
| [Word 起始模板](assets/word-starter.docx) | 下载后可在 Word 或 WPS 中另存为副本，按需要加入签审栏和目录。 |

Skill 版本为 1.0.0，规则基线为《文件编制规范管理制度》通用版 V1.1。样式说明和 Word 模板可单独使用。改动规则或模板后，可用以下用例复核交付结果。 [回归用例](evals/cases.md)

本项目采用 MIT 许可证。 [LICENSE](LICENSE)
