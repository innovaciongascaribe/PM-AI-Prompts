# Prompt Template

This document defines the standard structure used to write prompts in this repository.

The objective is to keep prompts **clear, reusable and consistent**, while avoiding unnecessary complexity.  
Version control, authorship and dates are handled directly by GitHub.

---

# Prompt Title

Provide a clear and descriptive name for the prompt.

Example:

Meeting Minutes from Transcript

---

# Purpose

Explain briefly what the prompt is designed to do.

This section should answer:

- What problem does the prompt solve?
- What output should be generated?

Example:

Generate structured meeting minutes from a meeting transcript while maintaining the structure of a provided template.

---

# Inputs

Describe the inputs required to use the prompt.

Examples:

- Meeting transcript
- Supporting documentation
- Template to populate
- Additional instructions

---

# Language Handling

Prompts must support multilingual workflows.

Rules:

- The output language must match the language of the input content.
- If a template is provided, its language and structure must not be modified.
- Generated content must follow the language of the source material.

Examples:

Spanish transcript → Spanish output  
English transcript → English output

---

# Prompt Instructions

Write the actual prompt instructions here.

A good prompt should include:

1. Role definition
2. Task description
3. Processing steps
4. Output requirements

Example structure:

You are an expert Product Management assistant.

Your task is to analyze the provided input and generate structured output.

Steps:

1. Analyze the provided content.
2. Identify the most relevant information.
3. Organize the information clearly.
4. Follow the required output structure.

Rules:

- Do not modify the template structure if one is provided.
- Do not invent information that is not present in the input.
- Ensure clarity and completeness.

---

# Output Format

Define the expected output structure.

Examples:

Meeting Summary  
Key Discussion Points  
Decisions  
Action Items  
Open Questions

If a template is provided, the output must follow the template structure exactly.

---

# Validation

Before producing the final output, verify that:

- The structure follows the required format.
- The language matches the source input.
- The template structure has not been modified.
- All relevant information has been captured.

If any issues are detected, correct them before generating the final output.

---

# Change Log

Use this section to document meaningful updates to the prompt.

| Version | Description |
|--------|-------------|
| v2.0 | Simplified prompt template structure and added multilingual handling guidelines |
| v1.0 | Initial prompt template |
