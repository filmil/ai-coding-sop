# AI Coding SOP for the Gemini CLI

This repository contains a set of standard operating procedures (SOPs) for
developing the Gemini CLI project, with a focus on collaboration with AI
assistants.

The intention is that any developer, human or AI, uses these guidelines to
ensure consistency and quality in the codebase.

## Key Guidelines

The core of these SOPs is in the `GEMINI.md` file. It contains specific
instructions for the AI assistant on topics such as:

*   **File modification rules:** What files can and cannot be modified automatically.
*   **Git usage:** Best practices for commits and changes.
*   **Documentation:** How to document code using Doxygen.
*   **License maintenance:** Ensuring all files have the correct license information.

Developers should familiarize themselves with the contents of `GEMINI.md`.

## AI-Specific Instructions (`//ai/`)

The `//ai` directory contains documents with specific instructions for AI
assistants on how to perform common development tasks. These include:

*   **`AI_GIT.md`:** Provides rules for creating Git commits and pull requests,
    emphasizing the use of `rebase` and specific commit message formats.
*   **`AI_BCR.md`:** Outlines the process for publishing to the Bazel Central
    Registry, including versioning and tagging conventions.

