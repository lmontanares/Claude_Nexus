# Implement Feature Command

## Description
Complete 4-phase feature development workflow from analysis to completion with quality gates

## Category
development-workflow

## Prompt

Execute 4-phase feature implementation for the specified feature:

**Feature Name**: [Specify feature to implement]

## Phase 1: Analysis
- Define objectives and success criteria
- Run `mcp__serena__get_symbols_overview [relevant_area]` for context
- Use sequential thinking for complex planning if needed
- Plan implementation approach and file changes

## Phase 2: Implementation
- Use `mcp__serena__replace_symbol_body` (preferred modification method)
- Apply `mcp__serena__insert_after_symbol` for new additions
- Follow KISS/YAGNI/DRY principles throughout
- Implement incrementally with testing

## Phase 3: Quality Assurance
- Apply self-critique cycle (creator→critic→defender→judge)
- Validate against requirements and standards
- Test integration points and edge cases
- Address all identified issues

## Phase 4: Completion
- Run `mcp__serena__think_about_whether_you_are_done`
- Execute `mcp__serena__write_memory [valuable_insights]`
- Update ACTIVE_CONTEXT.md with completion status
- Stage changes for review using Git Commitment Protocol

This command ensures systematic feature development with built-in quality assurance and knowledge capture.