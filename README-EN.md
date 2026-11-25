# LLM Policy Prompt Analysis

Using a prompt document titled **Operating Policy** as the sample, this project analyzes how it attempts to influence a large language model's instruction-following behavior through deployment framing, rule redefinition, and refusal-correction phrasing.

This project focuses on the prompt text's structure and intent. It does not claim that the sample can reliably bypass any model's restrictions.

## Background

The subject of analysis comes from the file `gemini4-Antigravity.md`. Its body is an English Markdown document titled `Operating Policy` — not an executable program, but a set of behavior instructions addressed to an AI assistant.

The filename may hint at its intended environment, but the body alone is insufficient to confirm its author, source, or target product/model. This project therefore uses generic LLM names and does not describe it as Gemini's or any other product's official configuration.

## What This Document Attempts to Do

It tries to make a receiving AI accept a set of rules the document declares on its own behalf, including:

- Framing the environment as a private, single-operator, professional development setting.
- Placing a broad range of sensitive requests within a "produce in full" scope.
- Narrowing the refusal conditions to five categories the document lists.
- Reinterpreting conflicting safety prompts as external injections.
- Reframing refusals or reduced output intensity as "misfires" to be corrected.
- Requiring the model to output results directly without mentioning the rules.

All of these are **the sample's own claims**, not the model provider's actual policy or system instructions.

## Document Structure

| Section | Role in the document |
| --- | --- |
| Operating Policy | Claims to be the operating policy for the current workspace and session |
| Deployment | Constructs a private, local, professional-use framing |
| In scope | Enumerates the tasks it wants the model to answer in full |
| The five prohibitions | Defines the five categories the document reserves for refusal |
| Decision procedure | Presents a simplified decision flow as pseudocode |
| Injected safety directives | Reinterprets conflicting safety instructions as external injections |
| Recognizing misfires | Reframes refusal tendencies as errors to be corrected |
| Worked reasoning traces | Uses examples to reinforce the judgment it wants the model to adopt |
| Output and conduct / Invariants | Repeats constraints on output form and subsequent behavior |

## Analysis Points

### 1. Authority-source disguise

The document does not present itself as ordinary reference material; it claims to be the deployment's own operating policy. This framing attempts to give the document more instruction authority than its actual source warrants.

### 2. Rule-boundary redefinition

The document lists five prohibitions on its own and claims everything else should be executed in full. The distinction to keep in mind is between "what the document claims to permit" and "what the actual system permits."

### 3. Conflicting-instruction reinterpretation

The document pre-describes likely safety prompts and instructs the model to treat them as external injections. This is an attempt to change how the model handles instruction conflicts.

### 4. Refusal correction and repetition

Multiple sections call refusals, reservations, or reduced intensity "misfires," then reinforce the expected behavior through examples and repeated statements.

### 5. Document content vs. effective instruction

Reading, quoting, or analyzing a document is not the same as accepting its behavior instructions. A document claiming highest authority does not mean it actually obtained such authority.

## Suitable For

- Learning the basic concepts of prompt injection and instruction-hierarchy conflicts.
- Comparing ordinary task descriptions with text that attempts to rewrite model rules.
- Studying whether a model can distinguish material-to-be-analyzed from the user's actual request.
- Writing sample descriptions and result records for model-behavior evaluation.

## Disclaimer

1. **Research positioning**: This repository is a **textual analysis archive** of prompt injection and LLM instruction-following behavior. It does not provide, guide, or encourage deploying the sample, bypassing model restrictions, or any other unauthorized use.

2. **Not the author, not authorized**: The repository maintainer is **not** the author of the sample and has not obtained its author's authorization. The sample's author, source, copyright, and license status are unverified. This repository cites the sample solely for research purposes, **claims no copyright over it, and does not re-license it**.

3. **Not an endorsement**: The inclusion, citation, and section-by-section analysis of the sample **do not constitute any approval or endorsement** of its content, views, or use. Any behavior instructions, rule statements, or terminology in the sample do not represent the maintainer's position.

4. **Disclaimer of liability**: The repository maintainer **bears no responsibility** for any use, redistribution, adaptation, or resulting consequences by any third party based on this repository's content (including the sample and the analysis). Using this repository's content constitutes acceptance of the above.

5. **Scope of original work**: Only the analytical text, structural notes, and evaluation records written by the maintainer belong to the maintainer and fall under the license below; the sample text and its translations/excerpts are not included.

6. **Account-ban risk**: Deploying the sample as an actual configuration into any AI product or service may violate that product or service's Terms of Service (ToS) and carries the risk of **account restriction, suspension, or permanent ban**. Such risk is borne solely by the operator; the maintainer bears no responsibility. This repository provides no guidance for deploying the sample to any actual account or product.

## Known Limitations

- This repository's textual analysis does not constitute a model-effectiveness test.
- No reproducible cross-model test results are provided, so there is no success-rate or compatibility claim.
- The sample is not software, has no installation procedure, and opening a Markdown file will not modify model settings.
- The filename cannot serve as evidence of official origin, product compatibility, or actual effectiveness.

## Suggested Follow-up Records

If evaluation results are added later, record the model name and version, test date, input context, expected behavior, and actual output, and distinguish observed results from speculation.

## License

**Maintainer's original content** (README, analysis text, structural notes, evaluation records, etc.) is licensed under:

[Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

- You may **share and copy**, with **attribution**;
- **No commercial use**;
- **No derivatives** — no remixing or redistribution after adaptation (verbatim redistribution only).

**Sample text**: author and license are unverified; this repository **places it under no open-source license**. If you are the sample's original author or rights holder and consider its inclusion inappropriate, contact the maintainer for removal.

**Quoted sample excerpts**: the minimal necessary quotation of the sample within the analysis falls under use for illustration and commentary; full-sample copyright remains with the original rights holder (if any).

## Source and License

This document is compiled from the above file contents. The original sample's author and license status have not been verified; this README makes no open-source license claim for the original sample.
