# Recall Context Command

## Description
Context restoration workflow with memory synthesis and working memory update

## Category
memory-management

## Prompt

Execute context recall workflow for the specified domain:

**Context Domain**: [Specify domain: project, pattern, technology, problem area]

1. **Memory Scan**: Run `mcp__serena__list_memories` to scan available context

2. **Load Relevant**: Use `mcp__serena__read_memory [relevant_memories]` for specific knowledge

3. **Review Recent**: Check ACTIVE_CONTEXT.md and recent WORKING_LOG entries

4. **Synthesize Information**: Combine relevant information for current task context

5. **Update Working Memory**: Load synthesized context into current working memory

This command enables efficient context restoration from distributed memory layers with synthesis for immediate use.