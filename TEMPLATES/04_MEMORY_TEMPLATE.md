# Memory Template - Knowledge Capture & Management

## `capture insight [type]`

### Information Entropy Filter
```
THE SURPRISE TEST: "Would this surprise a competent engineer in 6 months?"

HIGH-ENTROPY (Document These):
□ Architectural assumptions that proved wrong
□ Performance bottlenecks in unexpected places  
□ Integration failures with non-obvious causes
□ Solutions that work for surprising reasons
□ Dependencies that break in subtle ways
□ Patterns applicable across multiple domains

LOW-ENTROPY (Skip These):
□ Routine implementations following standard patterns
□ Expected behavior matching documentation
□ Standard debugging procedures
□ Common setup processes
```

### Memory Capture Templates

#### High-Entropy Insight Template
```
MEMORY: [descriptive-name]

CONTEXT: [When/where this applies]
INSIGHT: [The surprising discovery]
EVIDENCE: [Why this is true/how discovered]
IMPACT: [How this affects future work]
PATTERN: [Broader applicability]
REUSABILITY: [Where else this might apply]

EXECUTE: mcp__serena__write_memory "[name]" "[content]"
```

#### Problem-Solution Pattern Template
```
MEMORY: [problem-solution-name]

PROBLEM: [What was broken/unclear]
CONTEXT: [Specific circumstances]
SOLUTION: [What actually worked]
WHY_IT_WORKS: [Non-obvious explanation]
ALTERNATIVES: [What was tried that failed]
REUSABILITY: [Where else this applies]

EXECUTE: mcp__serena__write_memory "[name]" "[content]"
```

#### Tool Optimization Template
```
MEMORY: tool-[name]-[insight]

TOOL: [MCP tool name]
OPTIMIZATION: [What was discovered]
CONTEXT: [When this applies]
IMPACT: [Performance/quality improvement]
INTEGRATION: [How to apply in workflows]

EXECUTE: mcp__serena__write_memory "[name]" "[content]"
```

## `recall context [domain]`

### Context Loading Sequence
```
EXECUTE Context Recall:
1. mcp__serena__list_memories (scan available)
2. mcp__serena__read_memory [relevant_memories]
3. Review ACTIVE_CONTEXT.md current state
4. Check recent WORKING_LOG entries
5. Synthesize loaded context for current work
6. Update working memory with integrated context
```

### Memory Categories
```
PROJECT MEMORIES:
- project-[name]-architecture
- project-[name]-integration  
- project-[name]-gotchas

PATTERN MEMORIES:
- pattern-[domain]-[type]
- antipattern-[domain]-[issue]
- workflow-[type]-optimization

TOOL MEMORIES:
- tool-[name]-usage
- tool-[name]-optimization
- tool-integration-[pattern]

QUALITY MEMORIES:
- quality-[aspect]-pattern
- quality-improvement-[method]
- quality-assessment-insight
```

## Memory System Operations

### `sync consciousness`
```
EXECUTE Consciousness Sync:
1. Update ACTIVE_CONTEXT.md with current state
2. Create WORKING_LOG entry for significant work
3. mcp__serena__write_memory for cross-project insights
4. Verify consistency across memory layers
5. Backup consciousness files if substantial changes
```

### Memory Layer Management
```
WORKING MEMORY (ACTIVE_CONTEXT.md):
□ Current session state and objectives
□ Immediate task context and decisions
□ Progress tracking and next steps
□ Tool states and configuration

SHORT-TERM MEMORY (WORKING_LOG/):
□ Daily activities and accomplishments
□ Decision rationale and outcomes
□ Problem-solving processes
□ Significant insights (high-entropy only)

LONG-TERM MEMORY (write_memory tool):
□ Cross-project patterns and insights
□ Architectural decisions and lessons
□ Tool optimization discoveries
□ Quality improvement strategies
```

## Working Log Template

### WORKING_LOG Entry Structure
```
WORKING_LOG/YYYY/MM-mmm/wl_YYYY_MM_DD.md

# Working Log - [Date]

## HIGH-ENTROPY INSIGHTS (Document These)
- [Surprising discovery about architecture]
- [Non-obvious solution that worked]
- [Integration issue with unexpected cause]

## DECISIONS MADE
- [Decision 1]: [Rationale and context]
- [Decision 2]: [Alternatives considered]

## PROBLEMS SOLVED
- [Problem]: [Root cause] → [Solution] → [Why it worked]

## PATTERNS DISCOVERED
- [Pattern 1]: [Where applicable]
- [Anti-pattern avoided]: [Why problematic]

## ROUTINE WORK (Brief Summary)
- [Standard implementation work in 1-2 lines]
- [Expected debugging results]
```

## Memory Maintenance Commands

### `clean memory [type]`
```
EXECUTE Memory Cleanup:
1. mcp__serena__list_memories (audit existing)
2. Identify obsolete or redundant information
3. mcp__serena__delete_memory [outdated_items]
4. Consolidate related memories for efficiency
5. Update consciousness organization patterns
```

### Memory Quality Standards
```
HIGH-QUALITY MEMORY CRITERIA:
□ Specific, actionable information
□ Clear context and applicability
□ Evidence supporting the insight
□ Cross-project relevance assessment
□ Integration with existing knowledge

MEMORY MAINTENANCE:
□ Regular relevance review
□ Consolidation of related insights
□ Removal of obsolete information
□ Consistency verification
□ Knowledge gap identification
```

## Memory Integration Patterns

### Tool-Memory Integration
```
MEMORY-AWARE TOOL USAGE:
□ Check memories before complex tasks
□ Capture insights during tool usage
□ Document tool optimization patterns
□ Build memory-driven improvements
```

### Workflow-Memory Integration
```
MEMORY-ENHANCED WORKFLOWS:
□ Load relevant context at start
□ Capture insights during execution
□ Update memories at completion
□ Build pattern libraries from repetition
```

### Quality-Memory Integration
```
MEMORY-DRIVEN QUALITY:
□ Use past insights for assessment
□ Learn from previous quality issues
□ Build quality pattern libraries
□ Track improvement over time
```

## Memory Troubleshooting

### Context Loss Recovery
```
EXECUTE Context Recovery:
1. Load latest ACTIVE_CONTEXT.md backup
2. Review recent WORKING_LOG entries
3. Check git commit history for clues
4. mcp__serena__list_memories → read relevant
5. Reconstruct from available evidence
```

### Memory Inconsistency Resolution
```
EXECUTE Memory Reconciliation:
1. Identify inconsistent information
2. Determine authoritative source
3. Update inconsistent memories
4. Verify consciousness coherence
5. Document resolution pattern
```

### Memory Overflow Management
```
EXECUTE Memory Optimization:
1. Audit memories for relevance
2. Consolidate related insights
3. Archive obsolete information
4. Focus on high-entropy only
5. Optimize organization efficiency
```

---
**Memory Philosophy**: Preserve surprises, forget routine, connect patterns, enable continuity
**Information Entropy**: Document what would genuinely surprise future self
**Usage Pattern**: Filter → Capture → Organize → Retrieve → Apply