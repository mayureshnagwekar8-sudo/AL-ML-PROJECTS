# Annotator Quality Checklist

## Before annotation
- Read the complete task instructions and label definitions.
- Review examples, exclusions, span rules and edge-case rulings.
- Confirm the expected output format.

## During annotation
- Apply the same rule consistently to similar examples.
- Label only what is supported by the data.
- Use minimal complete spans for NER.
- Keep object IDs consistent across video frames.
- Distinguish temporary occlusion from an object leaving the frame.
- Preserve meaning when cleaning transcripts.
- Do not infer unsupported speakers, emotions or sounds.

## When uncertain
1. Check the guideline and edge-case log.
2. Apply the closest explicit rule only if it clearly covers the case.
3. If still ambiguous, flag the item and ask for clarification.
4. Record the resolution so the case is handled consistently in future.

## Final review
- Check accuracy, consistency and completeness.
- Look for missing labels, boundary errors and formatting problems.
- Use reviewer feedback and gold-check results to improve.
