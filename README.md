# Codified Context Infrastructure

Codified Context provides infrastructure for organizing project knowledge to enhance AI coding agents. It structures codebases, documentation, and context into a machine-readable format, enabling more accurate and context-aware code generation and reasoning.

## Key Features
*   Structures project knowledge (code, docs, issues) into a unified, queryable format.
*   Provides tools for generating and maintaining a persistent context index for AI agents.
*   Enables efficient retrieval of relevant context for coding tasks and queries.

## Tech Stack
*   Python
*   Pydantic (for data modeling)
*   Tree-sitter (for code parsing)

## Getting Started
```bash
git clone https://github.com/zoreanuj/codified-context-infrastructure.git
cd codified-context-infrastructure
pip install -r requirements.txt
# Run the context builder on your project
python -m codified_context.build /path/to/your/project
```