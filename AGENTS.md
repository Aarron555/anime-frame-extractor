# Engineering Protocol

Use this file as the project standard for future AI-assisted code changes.

## Core standard

- Treat input files and paths as untrusted.
- Validate file types, file paths, and output directories before processing.
- Avoid placeholder logic in workflow paths.
- Handle missing files, bad formats, large files, and permission errors clearly.
- Keep dependencies minimal and documented.
- Do not commit private media, copyrighted source clips, secrets, tokens, or private data.

## Change workflow

1. Break the requested change into small parts.
2. Identify likely reliability and file-processing failure modes before coding.
3. Implement the full change with readable code and clear errors.
4. Add or update tests where practical.
5. Verify the utility can run, or document what was not verified.

## Hiring-proof emphasis

This repo should demonstrate creative workflow automation, file-processing discipline, AI-assisted production thinking, and clear documentation.
