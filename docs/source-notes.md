# Source Notes

本仓库中的 Skill 基于三篇用户提供的本地文章蒸馏：

- Source A: 高中食堂、楼梯、身高与暗恋叙事
- Source B: 语文老师、高考、强基、编程启蒙与 LLM agent 互文
- Source C: 小学大院、饭卡烧饼、图灵社、早期互联网与 LLM agent 叙事

原始文章全文不包含在开源仓库中。它们已移入本地 `private/source-materials/`，并通过 `.gitignore` 排除。

## Grounding

当前版本只使用本地源文章，没有做外部网页交叉验证。因此完整来源校验中的 `source_grounding` 会因为缺少可验证外部 URL 而失败。这是有意保留的限制，不应通过伪造 URL 或泛化平台首页来绕过。

## Copyright Safety

- 不提交原始全文。
- 不提交长篇逐字摘录。
- `knowledge/research/` 中只保留概括、模式分析、推断和明确标注的缺口。
- 如后续加入公开来源，请使用具体、可打开、可追溯的页面链接。
