# Session Template - Universal Session Management

## Quick Session Commands

### `session start`
```
□ mcp__serena__initial_instructions
□ mcp__serena__check_onboarding_performed
□ Load ACTIVE_CONTEXT.md → verify current state
□ Update session metadata (time, branch, focus)
□ Set primary objectives for session
```

### `session end`
```
□ Update ACTIVE_CONTEXT.md with summary
□ mcp__serena__summarize_changes (if code work)
□ Create WORKING_LOG entry (if significant work)
□ mcp__serena__write_memory (if valuable insights)
□ Set next session context
```

## Session Context Template

### ACTIVE_CONTEXT.md Update
```
## Session Information
- **Start Time**: [YYYY-MM-DD HH:MM]
- **Current Branch**: [branch_name]
- **Primary Focus**: [main_objective]
- **Session Type**: [Development/Research/Debug/Review]

## Current Objectives
1. [Primary objective - specific and measurable]
2. [Secondary objective - if time permits]
3. [Stretch goal - if everything goes smoothly]

## Work Completed This Session
- [Achievement 1 with outcome]
- [Achievement 2 with outcome]
- [Key decisions made]

## Current Task Context
- **Task**: [Current specific task]
- **Status**: [In Progress/Blocked/Complete]
- **Next Action**: [Immediate next step]
- **Challenges**: [Current blockers or issues]

## Next Steps
- **Immediate**: [What happens next]
- **This Session**: [Session completion criteria]
- **Future Sessions**: [Planned follow-up work]

## Memory Updates Needed
- [Insight 1 to capture]
- [Pattern discovered]
- [Lesson learned]

## Technical Context
- **Tools Used**: [MCP tools, specific configurations]
- **Files Modified**: [Key files changed this session]
- **Dependencies**: [External requirements, APIs, etc.]

---
**Session Quality**: [1-10] | **Ready for Next**: [Yes/No]
```

## Session Troubleshooting

### Context Lost
```
RECOVERY SEQUENCE:
1. Load latest ACTIVE_CONTEXT.md
2. Review recent WORKING_LOG entries
3. Check git commit history
4. mcp__serena__list_memories → read relevant memories
5. Reconstruct context from available evidence
```

### Tool Failure
```
TOOL RECOVERY:
1. mcp__serena__restart_language_server
2. Switch to documented fallback tools
3. Continue work without blocking
4. Document failure for operational awareness
```

---
**Usage**: Copy relevant sections, adapt to session type, execute systematically