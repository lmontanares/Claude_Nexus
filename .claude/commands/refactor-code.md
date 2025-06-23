# Refactor Code Command

## Description
Safe refactoring workflow with regression prevention and quality validation

## Category
development-workflow

## Prompt

Execute safe refactoring workflow for the specified target:

**Refactor Target**: [Specify code area to refactor]

1. **Analyze Structure**: Run `mcp__serena__get_symbols_overview [target_area]` to understand current architecture

2. **Define Objectives**: Identify refactoring goals and constraints clearly

3. **Plan Changes**: Design atomic changes with comprehensive testing strategy

4. **Apply Changes**: Use `mcp__serena__replace_symbol_body [incremental_changes]` for safe modifications

5. **Validate Integrity**: Ensure no functionality regression through testing

6. **Assess Quality**: Apply quality assessment and document improvement patterns

This command provides structured refactoring approach that maintains system integrity while improving code quality.