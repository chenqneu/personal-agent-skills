---
name: codebase-understanding
description: Systematically explore an unfamiliar codebase, identify its architecture, and trace key execution paths using verifiable source-code evidence. Use when studying, onboarding to, or analyzing a repository.
---

# Codebase Understanding

## Objective

Build an accurate, comprehensive, and efficient understanding of an unfamiliar codebase.

Prioritize architectural understanding and critical execution paths over exhaustive file-by-file inspection.

## Workflow

### 1. Establish the Big Picture

- Identify the project's purpose and main functionality.
- Inspect the repository structure, documentation, and entry points.
- Identify major modules and their responsibilities.
- Distinguish documented architecture from actual implementation.

### 2. Trace Critical Execution Paths

- Identify the main execution workflow from entry point to result.
- Trace important function calls and data transformations.
- Explain how core components interact.
- Identify important state transitions and external dependencies.

### 3. Understand Core Design

- Identify important abstractions, interfaces, and data structures.
- Explain architectural boundaries and dependencies.
- Distinguish design intent supported by evidence from inferred rationale.
- Highlight important trade-offs when they can be established from the code.

### 4. Verify Understanding

- Support important findings with actual file paths, classes, and functions.
- Inspect relevant implementations rather than relying solely on documentation.
- Distinguish confirmed facts, reasonable inferences, and unresolved questions.
- Do not invent missing components or unsupported behavior.

## Output

Provide a concise, structured report covering:

1. Project overview
2. Architecture and major components
3. Main execution paths and data flow
4. Core abstractions and design decisions
5. Key files and functions for further study
6. Uncertainties and recommended next steps

## Constraints

- Read-only analysis by default.
- Do not modify files, install dependencies, or execute the application unless explicitly requested.
- Avoid unrelated refactoring suggestions.
- Do not exhaustively inspect every file unless necessary.
- Prefer accurate, evidence-based conclusions over lengthy descriptions.
- Minimize unnecessary tool calls and context consumption.

## Language

- Respond in Simplified Chinese by default.
- Preserve original identifiers, API names, file paths, and technical terminology.
- Explain unfamiliar technical concepts in Chinese.
- Cite source-code evidence using original file and function names.
