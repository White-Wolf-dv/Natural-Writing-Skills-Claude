# Natural Writing Skills

Four [Claude Skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) that make AI-generated prose read like a person wrote it — for Persian, English, Arabic, Spanish, Hebrew, Italian, and French.

All four are built around patterns documented in Wikipedia's ["Signs of AI Writing"](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) guide — a field guide Wikipedia editors put together from real cases of undisclosed AI content. Instead of guessing at what "sounds robotic," these skills target the specific, catalogued tells: generic superlatives, mechanical summary phrases, rigid section structure, vague attribution, and a handful of others.

## Why this exists

Unedited AI text has a fingerprint. It leans on phrases like "a rich tapestry of culture" or "stands as a testament to," closes every section with "in conclusion," and keeps the same tone from the first sentence to the last. None of that is wrong exactly — it's just recognizable, and it reads as generic rather than considered.

These skills catch that fingerprint and rewrite around it: concrete facts instead of vague praise, varied sentence rhythm instead of a flat cadence, a register that actually drifts the way a real person's voice does mid-thought.

## What's included

| Skill | Language | Use for |
|---|---|---|
| `natural-writing-fa` | Persian (فارسی) | Blog posts, articles, ad copy, product descriptions, reports — any long-form Persian text |
| `natural-writing-en` | English | Blog posts, articles, essays, reports, marketing copy — any long-form English text |
| `natural-writing-ar` | Arabic (العربية) | Blog posts, articles, ad copy, product descriptions, reports — any long-form Arabic text |
| `natural-writing-es` | Spanish (Español) | Blog posts, articles, essays, reports, marketing copy — any long-form Spanish text |
| `natural-writing-he` | Hebrew (עברית) | Blog posts, articles, essays, reports, marketing copy — any long-form Hebrew text |
| `natural-writing-it` | Italian (Italiano) | Blog posts, articles, essays, reports, marketing copy — any long-form Italian text |
| `natural-writing-fr` | French (Français) | Blog posts, articles, essays, reports, marketing copy — any long-form French text |

All four skills share the same structure and catch the same nine patterns:

1. Generic or exaggerated descriptors
2. Repetitive summary/conclusion phrases
3. Rigid formulaic structure
4. Excessive lists, bolding, or headers
5. Vague attribution ("some critics believe...")
6. "Not X, but Y" contrast constructions
7. Transition-word overload
8. Puffed-up significance (small facts inflated into sweeping claims)
9. Leftover chatbot phrasing

Each pattern entry explains what it looks like, why it's a tell, and how to fix it — followed by a 12-point self-check the model runs against its own draft before delivering anything.

## How to use

Download the `.skill` file for the language you need and add it to your Claude Skills. Claude picks it up automatically for long-form writing requests, or you can trigger it directly:

- **Persian:** «این متن رو طبیعی‌تر کن», «الگوهای هوش مصنوعی رو حذف کن»
- **English:** "make this sound more natural," "remove AI patterns," "humanize this text"
- **Arabic:** «اجعل هذا يبدو طبيعيًا أكثر», «أزل أنماط الذكاء الاصطناعي»
- **Spanish:** "que suene más natural," "quita los patrones de IA," "humaniza este texto"
- **Hebrew:** «הפוך את הטקסט לטבעי יותר», «הסר דפוסי כתיבה של בינה מלאכותית»
- **Italian:** "rendi il testo più naturale," "rimuovi i modelli dell'IA"
- **French:** "rends ce texte plus naturel," "supprime les schémas de l'IA"

The skill applies to fresh drafts and existing text alike — write something new with it active, or hand it a finished draft to clean up.

## Scope and limits

These skills are about writing quality, not about defeating plagiarism checkers or AI-content detectors when the underlying goal is deceptive — passing off AI coursework as your own where that's against the rules, laundering fake reviews past disclosure requirements, that sort of thing. If a request's real intent is evading detection for a dishonest purpose, the skill declines that framing and just writes good, honest, natural prose instead. Same techniques either way — intent is what changes.

They also don't introduce deliberate typos or grammar mistakes. Sounding natural means well-written and unpredictable, not sloppy on purpose.

## Structure

```
natural-writing-en.skill
natural-writing-fa.skill
natural-writing-ar.skill
natural-writing-es.skill
natural-writing-he.skill
natural-writing-it.skill
natural-writing-fr.skill
README.md
```

Each `.skill` file is self-contained: pattern catalogue, register guidance, sentence-variety notes, self-check list, and a short workflow section.

## License

MIT (or your preference — update this section as needed).
