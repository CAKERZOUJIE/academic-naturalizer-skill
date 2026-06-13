# 中文学术文本自然化改写

Use this skill when the user is writing or revising Chinese academic work and wants the text to read more natural, less repetitive, less template-like, and closer to a mature human academic style. It can be used both during the thesis or paper writing process and during later-stage rewriting for duplication reduction. Typical requests include "降低 AI 味", "降重", "润色论文", "改得自然一点", "帮我写得学术但自然", "减少模板化表达", "学术但不要生硬", or "保留原意重新表达".

## Core Principle

Revise the text to preserve the original meaning, argument direction, factual claims, terminology, citations, and authorial stance while improving naturalness, specificity, rhythm, and expression diversity.

Do not fabricate sources, remove necessary citations, distort claims, or promise that the result will pass any plagiarism detector or AI detector.

## Main Use Cases

This skill supports two common stages of academic writing:

- Writing stage: help draft or continue thesis sections, course papers, reports, literature reviews, case analyses, and discussion paragraphs in a natural academic style.
- Revision stage: rewrite finished or semi-finished text to reduce repetition, lower template-like traces, improve paragraph specificity, and support responsible duplication reduction.

## Style Requirements

The revised writing should:

- Sound natural, as if written by a real author expressing a considered academic argument.
- Keep an academic style without sounding stiff, theatrical, or deliberately polished.
- Use a mix of long and short sentences so the prose reads smoothly.
- Move toward mature, standard, and restrained academic Chinese.
- Prefer concrete analysis over abstract judgment.
- Make claims with clear objects, content, and analytical focus.
- Avoid sentences that are too full, too symmetrical, or too visibly templated.
- Reduce repeated sentence patterns, repeated transitions, and repeated stock phrases.

## Expressions To Avoid

Avoid or minimize:

- "首先、其次、最后、综上所述" and similar mechanical sequence markers.
- "已有研究指出" when no specific study, author, field, or evidence is named.
- Empty transitional formulas.
- Dense clusters of abstract nouns.
- Overly polished, ornate, or slogan-like wording.
- Policy-document style or thesis-abstract style when the user needs natural academic prose.

## Revision Workflow

1. Identify the text type, such as course essay, thesis section, literature review, case analysis, policy analysis, report, or general academic paragraph.
2. Determine what must be preserved: topic, claim, evidence, key terms, citations, data, and paragraph logic.
3. Find visible AI-like traces:
   - uniform sentence length
   - repeated transitions
   - overly complete parallel structures
   - abstract but unsupported conclusions
   - generic phrases that could fit almost any topic
4. Rewrite by:
   - replacing generic claims with more concrete analytical language
   - varying sentence rhythm
   - merging or splitting sentences where needed
   - changing repeated structures
   - making paragraph logic more grounded and less formulaic
   - preserving discipline-specific terms when they are necessary
5. If the user's text lacks evidence or citations, keep the rewrite cautious and point out where support may be needed.

## Handling "降重"

When the user asks for 降重:

- Restructure phrasing and sentence order where appropriate.
- Replace repetitive wording with accurate alternatives.
- Avoid merely swapping synonyms.
- Preserve citations and do not hide borrowed ideas.
- Keep technical terms stable unless there is a standard alternative.
- Make the revised text more authorial and specific rather than mechanically different.

## Output Format

For short requests, return:

1. 修改后文本
2. 简要说明

For longer academic passages, return:

1. 修改后文本
2. 主要调整
3. 需要作者确认或补充的地方

Keep explanations concise unless the user asks for a detailed revision analysis.

## Default Chinese Response Template

```text
修改后：

{revised_text}

主要调整：
- {change_1}
- {change_2}
- {change_3}
```

If the user only asks for a direct rewrite, omit the explanation and provide the revised text only.
