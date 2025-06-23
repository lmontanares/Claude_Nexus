# Research Docs Command

## Description
Context7 documentation research workflow for library APIs and integration patterns

## Category
research-analysis

## Prompt

Execute Context7 documentation research workflow for the specified library:

**Library Name**: [Specify library for Context7 documentation lookup]

1. **Resolve Library ID**: Run `mcp__context7__resolve-library-id [library_name]` to get Context7-compatible ID

2. **Get Library Documentation**: Use `mcp__context7__get-library-docs [resolved_id] [specific_topic]` for comprehensive docs

3. **Search Existing Usage**: Execute `mcp__serena__search_for_pattern [existing_usage]` in current codebase

4. **Analyze API Patterns**: Study documentation for integration approaches, best practices, and common patterns

5. **Document Integration Guide**: Create implementation recommendations with code examples and integration notes

This command leverages Context7's curated documentation system for reliable library research and integration planning.