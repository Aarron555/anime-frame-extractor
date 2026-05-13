# Security Policy

## Project scope

`anime-frame-extractor` is a media workflow utility prototype. It may eventually handle local files, generated frames, directories, and exported assets.

## Security principles

- Treat file paths and user-selected media files as untrusted.
- Validate input paths and output directories.
- Avoid writing outside the intended output directory.
- Do not commit private media, copyrighted source clips, API keys, tokens, or private data.
- Handle large files, missing files, unsupported formats, and permission errors cleanly.

## High-risk areas

- local file paths
- media processing
- output directory writes
- large files
- third-party binaries or codecs
- private or copyrighted media assets

## Current limitations

This is a prototype and is not hardened for production batch media processing. A production version would require stronger path validation, dependency scanning, resource limits, error reporting, and test fixtures using safe synthetic media.
