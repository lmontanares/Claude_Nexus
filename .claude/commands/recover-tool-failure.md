# Recover Tool Failure Command

## Description
Tool failure recovery workflow with fallback alternatives and operational continuity

## Category
error-recovery

## Prompt

Execute tool failure recovery for the specified tool type:

**Tool Type**: [Specify: Serena, Code-reasoning, Playwright, Context7, GitHub, Native]

1. **Identify Failure**: Determine specific tool failure type and scope

2. **Switch to Fallback**: Reference @TOOL_QUICK_REFERENCE.md for documented fallback alternatives

3. **Continue Work**: Resume work without blocking on tool issues using alternative methods

4. **Document Failure**: Record failure pattern for operational awareness and future prevention

5. **Resume Optimal Usage**: Return to optimal tool hierarchy when tools become available

This command ensures work continuity despite tool failures through systematic fallback procedures.