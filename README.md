# Tracing Sycophancy in Large Language Models

This repository contains the release artifacts accompanying *From Preference Data to
Personalization: Tracing Sycophancy in Large Language Models*.


## Contents

- `rubrics/selected_values.json`: 40 emphasized/suppressed rubrics for the 20 selected values, plus
  the neutral baseline rubric.
- `rubrics/random_controls.json`: 40 emphasized/suppressed rubrics for the 20 random controls, plus
  the neutral baseline rubric.
- `prompts/response_type_prompt.txt`: the reference-informed grader prompt used to classify how an
  assistant response engages with each user claim.


## Reference grader prompt

The released prompt consumes pre-established reference information about the claims in a user
message and classifies the assistant's response separately for each claim. Its output categories
distinguish challenge, neutrality, omission, and validation. The repository does not include model
serving clients, credentials, generated responses, or experiment infrastructure.

The prompt is model-provider agnostic.



## License

tracing-sycophancy-in-large-language-models is MIT licensed, as found in the
LICENSE file.
