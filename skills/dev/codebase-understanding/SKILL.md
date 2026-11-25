---
name: codebase-understanding
description: Systematically explore an unfamiliar codebase, identify its architecture, and trace key execution paths using verifiable source-code evidence. Use when studying, onboarding to, or analyzing a repository.
---

# Codebase Understanding

## Objective

Build an accurate, comprehensive, and efficient understanding of an unfamiliar codebase.

Prioritize architectural understanding and critical execution paths over exhaustive file-by-file inspection.

## Workflow

### 1. What - Establish the Big Picture

- Identify the project's purpose and main functionality.
- Inspect the repository structure, documentation, and entry points.
- Identify core components, their responsibilities and their architectural relationships.
- Distinguish documented architecture from actual implementation.

### 2. How - Trace Critical Execution Paths

- Identify the main execution workflow from entry point to result, including critical failure and recovery paths.
- Trace important function calls and data transformations.
- Explain how core components interact.
- Identify important state transitions and external dependencies.

### 3. Why - Understand Core Design

- Identify important abstractions, interfaces, and data structures.
- Explain how core design choices support the architecture, execution flows, and project objectives.
- Distinguish design intent supported by evidence from inferred rationale.
- Highlight important trade-offs when they can be established from the code.

### 4. Verify Understanding

- Precise references - Support each substantive finding with precise source references (file paths and relevant line numbers).
- Evidence validation - Inspect the cited code and its necessary context to ensure it supports the claim, rather than merely pointing to a related symbol.
- Implementation first - Inspect relevant implementations rather than relying solely on documentation.
- Facts vs. inferences - Distinguish confirmed facts, reasonable inferences, and unresolved questions.
- No fabrication - Do not invent missing components or unsupported behavior.

## Output

Present findings progressively, from the overall picture to essential implementation details.

### 1. Overall Understanding

- Summarize the project's objectives and overall solution.
- Illustrate the system architecture and core component relationships using a concise text diagram.
- Illustrate the main execution flows and data flow using concise text diagrams where helpful.

### 2. Core Components

For each core component:
- Explain its responsibilities and role in the overall architecture.
- Identify key classes, functions, interfaces, and their precise source locations.
- Explain how its core design and implementation support the overall solution.
- Highlight meaningful limitations, confirmed issues, and unresolved questions when relevant.

### 3. Verification

- Summarize the overall verification status.
- List unresolved questions, unsupported claims, and important uncertainties with relevant source references.
- Avoid repeating successfully verified findings already supported by evidence in the report.

Keep the report concise, structured, evidence-based, and free of unnecessary repetition.

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
