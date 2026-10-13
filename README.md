# FarsDetox

FarsDetox is a Farsi text detoxification resource for studying how harmful language can be rewritten while balancing toxicity reduction with preservation of meaning, tone, and style.

## Publication status

The accompanying paper has not yet been published. Public release of the dataset, annotation guidelines, and experimental code is planned upon publication.

## Dataset overview

FarsDetox contains 5,691 records covering 5,499 source comments from five social-media platforms.

The resource covers:
- Insults
- Profanity
- Hate speech
- Sexual content
- Threats

Comments include explicit, implicit, and mixed expressions of toxicity.

## Rewriting levels

- **Minimal:** Local edits that soften harmful expressions while preserving wording and tone; offensive language may remain.
- **Moderate:** Broader changes that remove toxicity while preserving communicative intent and informal style.
- **Complete:** Substantial reformulation into respectful, neutral language, preserving non-harmful information where possible.

## Reference construction

Three native Farsi-speaking annotators manually classified comments and wrote the references from scratch. No LLM drafts were used.

One external reviewer assessed the references and revised them where needed. This process is separate from downstream model generation and evaluation.

## Research scope

The study examines zero-shot and LoRA-fine-tuned detoxification, automatic and human evaluation, internal model representations, and activation steering.

## Planned release

The public release will include:
- The final dataset and fixed data splits
- Annotation and rewriting guidelines
- Model outputs and aggregate results
- Experimental and evaluation code

Raw annotation histories and individual human-rating records are excluded.

## Content notice

The resource contains offensive and potentially distressing language. It is intended for research on toxicity reduction and meaning preservation.

## Licensing

Data and software licensing details are being finalized.
