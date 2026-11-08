# Text Annotation Practice

Bootcamp exercises covered text classification and named-entity recognition.

## Classification tasks
- Sentiment: positive, negative, neutral and mixed.
- Intent: identify the user's primary request, such as tracking an order, cancellation or a promotion issue.
- Spam detection: apply the task's definitions rather than treating every unwanted message as spam.

## NER labels practised
PERSON, ORG, LOCATION, DATE, MONEY and PRODUCT.

## Span rules
- Select the minimal complete entity span.
- Exclude surrounding punctuation unless the task guideline says otherwise.
- Tag every repeated occurrence when required.
- Do not invent an entity or label that is not supported by the text.
- Follow the project's fallback rule or flag unclear cases.

The CSV and JSON examples in examples/ use synthetic text created for this portfolio.
