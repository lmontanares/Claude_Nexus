# Test Browser Command

## Description
Browser testing workflow with systematic interaction sequences and validation

## Category
tool-execution

## Prompt

Execute browser testing workflow for the specified scenario:

**Testing Workflow**: [Specify test scenario or application to test]

1. **Navigate**: Use `mcp__playwright__browser_navigate [target_url]` to reach target page

2. **Understand Structure**: Run `mcp__playwright__browser_snapshot` to analyze page structure

3. **Execute Interactions**: Apply `mcp__playwright__browser_click/type [interaction_sequence]` for user actions

4. **Validate Results**: Use `mcp__playwright__browser_wait_for [validation_criteria]` to confirm expected outcomes

5. **Document Results**: Capture test results and any issues discovered during testing

This command provides systematic browser testing with structured interaction patterns and result validation.