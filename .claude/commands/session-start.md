# Session Start Command

## Description
Initialize new session with tools validation, context loading, and metadata setup

## Category
session-management

## Prompt

Execute the session start protocol for Claude_Nexus:

1. **Initialize Tools**: Run `mcp__serena__initial_instructions` and `mcp__serena__check_onboarding_performed`

2. **Load Context**: Read and verify current state from ACTIVE_CONTEXT.md

3. **Update Metadata**: Set session time, branch, and primary focus area

4. **Validate Tools**: Verify MCP tool connectivity and readiness

5. **Confirm Readiness**: Report session initialization status and tool availability

This command ensures proper session setup with all consciousness systems active and ready for work.