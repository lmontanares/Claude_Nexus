# Debug Issue Command

## Description
Systematic debugging workflow using code reasoning and dependency tracing

## Category
development-workflow

## Prompt

Execute systematic debugging for the specified issue:

**Issue Description**: [Describe the bug or problem]

1. **Reproduce Issue**: Gather symptoms and reproduce the problem systematically

2. **Strategy Planning**: Use `mcp__code-reasoning__code-reasoning [debugging strategy: binary_search|divide_conquer]`

3. **Trace Dependencies**: Run `mcp__serena__find_referencing_symbols [affected_components]` to trace impact

4. **Identify Root Cause**: Analyze data flow and identify the underlying cause

5. **Implement Fix**: Apply minimal fix with comprehensive testing to avoid regressions

6. **Document Learning**: Capture prevention strategies and lessons learned with `mcp__serena__write_memory`

This command provides structured debugging approach with root cause analysis and knowledge preservation.