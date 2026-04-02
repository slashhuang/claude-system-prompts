本目录为 **`claude-code-source-code`** 中与 system prompt 拼装相关的源码快照（从本仓库根目录 `claude-code-source-code` 拷贝）。

**来源**：[sanbuphy/claude-code-source-code](https://github.com/sanbuphy/claude-code-source-code)（与 `npm` 包解包研究镜像同源；使用与版权以该仓库 README 为准）。

| 路径 | 作用 |
|------|------|
| `src/constants/prompts.ts` | `getSystemPrompt`、`getSimpleIntroSection`、各静态段、`computeSimpleEnvInfo` 等主逻辑 |
| `src/constants/systemPromptSections.ts` | 动态段注册与 `resolveSystemPromptSections` |
| `src/constants/cyberRiskInstruction.ts` | `CYBER_RISK_INSTRUCTION` |
| `src/utils/systemPrompt.ts` | `buildEffectiveSystemPrompt`（覆盖 / Agent / append 优先级） |
| `src/utils/systemPromptType.ts` | `SystemPrompt` 类型与 `asSystemPrompt` |
