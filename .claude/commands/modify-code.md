# Modify Code Command

## Description
Code modification workflow with symbol-based editing and integrity validation

## Category
tool-execution

## Prompt

Execute code modification workflow for the specified target:

**Modification Target**: [Specify code area, function, or component to modify]

1. **Locate Target**: Use `mcp__serena__find_symbol [target]` to locate modification point

2. **Apply Changes**: Execute `mcp__serena__replace_symbol_body [preferred_method]` for modifications

3. **Add Components**: Use `mcp__serena__insert_after_symbol [additions]` for new elements

4. **Validate Integrity**: Ensure changes maintain system integrity and don't break dependencies

5. **Test Modifications**: Verify modifications work correctly and document decisions

This command provides safe code modification through symbol-based editing with integrity validation.