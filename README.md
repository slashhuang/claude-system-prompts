# claude-system-prompts

与 Claude Code **system prompt** 相关的离线材料。

**来源说明**：`claude-code-source-code` 目录下的 TypeScript 源码快照与 [sanbuphy/claude-code-source-code](https://github.com/sanbuphy/claude-code-source-code) 同源（从 npm 包解包的研究用镜像；著作权归属见该仓库声明）。本目录内的提示重建与分析文档为基于该源码的整理，与上游 Anthropic 官方产物的关系以原仓库说明为准。

| 文件 / 目录 | 说明 |
|-------------|------|
| `claudeSystemPrompt.md` | **英文**提示正文：静态段、边界后动态模板、常见变体摘录；不含拼装分析（见分析稿）。 |
| `claudeSystemPrompt.zh.md` | **中文**对照，与上一文件**同结构、同顺序**；文末补充条件分支提要。 |
| `claudeSystemPromptAnalysis.md` | **分析**：函数/分支/registry/缓存；与上两 file **配套阅读**，修改时三者宜同步。 |
| `claude-code-source-code/` | 从本仓库根目录 **`claude-code-source-code`** 拷贝的源码副本（仅 system prompt 相关文件），便于对照与检索；公开对照见 [sanbuphy/claude-code-source-code](https://github.com/sanbuphy/claude-code-source-code)。 |

本地拷贝仅为快照；同步时请从上述来源或本仓库 `claude-code-source-code` 重新复制对应文件。

维护 **`claudeSystemPrompt.md` / `.zh.md` / `claudeSystemPromptAnalysis.md`** 时：改提示原文则更新前两份；改条件与注册表则更新分析稿。
