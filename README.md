# Gemma 4 custom chat template

Archived backup of an active custom Jinja chat template used for a private local Gemma 4 serving setup.

## Status

This is a small, purpose-built reference repository. It is intentionally minimal: the template is the artifact, and the README explains why it exists.

## What this is

- File: `gemma-4-12b-chat_template.jinja`
- Purpose: custom llama.cpp/Gemma 4 chat template for a local assistant/server stack.
- Reason it exists: to preserve the exact active template outside the private runtime host so it can be audited, restored, compared, or shared without exposing internal infrastructure details.

## Notes

- The template is Jinja for llama.cpp `--chat-template-file` / `--jinja` style serving.
- It includes local behavior tweaks for the Gemma 4 assistant workflow.
- Do not assume this is a generic upstream Google Gemma template.
- If you are not operating this kind of local Gemma setup, treat this as a reference example rather than a drop-in upstream template.

## Verification

At the time it was uploaded, the raw GitHub copy matched the active private runtime template SHA-256:

```text
834d46273b25d061d2f38595aac8781fd3cde84cdc0e71425df36593377054a5
```
