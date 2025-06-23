# Emergency Restore Command

## Description
Recover from session loss, context corruption, or system failures using backup restoration

## Category
session-management

## Prompt

Execute emergency restore protocol for Claude_Nexus:

1. **Load Backup Context**: Load latest ACTIVE_CONTEXT.md backup

2. **Verify Repository**: Check git repository state and branch integrity

3. **Restart Language Server**: Run `mcp__serena__restart_language_server` if needed

4. **Reload Consciousness**: Restore consciousness files from known good state

5. **Resume Work**: Resume work from last confirmed checkpoint

This command provides crisis recovery capabilities to restore Claude_Nexus to a functional state after system failures or context loss.