# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build/Run Commands
- Run ComfyUI with this extension loaded (see ComfyUI documentation)
- No specific lint/test commands are defined in this repository

## Code Style Guidelines
- Imports: Group standard library imports first, then third-party libraries, finally local imports
- Use numpy (np) and torch for numerical operations
- Variable naming: snake_case for variables and functions
- Class naming: PascalCase for class names (e.g., LivePortraitWrapper, ExpressionSet)
- Error handling: Use try/except blocks with specific exception types
- Type handling: Use simple type annotations for function parameters
- Documentation: Use descriptive function/class names and docstrings
- Module organization: Maintain clear separation between model components and UI nodes

## Repository Structure
- LivePortrait/: Core implementation files
- nodes.py: ComfyUI integration nodes
- sample/: Example workflows and test assets