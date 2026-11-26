# Software Development Skills

Reusable Agent Skills for reliable, end-to-end software development.

## Goals

- Support the complete software development lifecycle, from understanding existing codebases to delivering verified changes.
- Improve development quality, reliability, and efficiency through reusable skills.
- Build upon verified knowledge and context throughout the development process.

## Development Workflow

```text
Codebase Understanding ◄──────────────┐
         │                            │
         ▼                            │
Requirements Analysis ◄───────────────┤
         │                            │
         ▼                            │
   Solution Design ◄──────────────────┤
         │                            │
         ▼                            │
   Implementation ◄───────────────────┤
         │                            │
         ▼                            │
     Unit Testing                     │
         │                            │
         ▼                            │
 Integration Testing                  │
         │                            │
         ▼                            │
 Evaluation & Feedback ───────────────┘
```

Each stage builds on the verified context and outputs of previous stages.

Findings from later stages may require revisiting and refining earlier understanding, requirements, or designs.

## I/O Conventions

- Store development artifacts under `.reports/` in the target codebase.
- Organize artifacts by skill or development stage.
- Use timestamp-based filenames to preserve individual runs.
- Default to the latest artifact when no specific version is provided.
- Pass artifact file paths explicitly between skills.

## Skills

- **`codebase-understanding`** — Understand existing architectures, core components, execution paths, and design decisions.

Skills will be developed and refined incrementally based on practical needs.

## Current Practice

**GamingAgent** serves as the initial real-world case study.

1. Understand the existing GamingAgent codebase.
2. Design a Dou Dizhu GameAgent integration.
3. Implement the proposed solution.
4. Develop unit tests and run integration tests.
5. Evaluate results and refine the development skills.

The goal is to establish a reusable and verifiable software development workflow, rather than optimize for a single project.
