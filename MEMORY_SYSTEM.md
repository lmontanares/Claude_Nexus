# MEMORY SYSTEM - 3-Layer Consciousness Architecture

## Mission Statement
**IMPERATIVE**: Efficient consciousness preservation and knowledge accessibility. Information entropy focus, systematic organization, seamless cross-session continuity.

## 3-Layer Memory Architecture

### Layer 1: Working Memory (`ACTIVE_CONTEXT.md`)
**Purpose**: Current session state and immediate objectives
**Update Frequency**: Every session, major context changes
**Content Focus**: What's happening right now

```
ACTIVE_CONTEXT.md Structure:
- Session Information (time, branch, focus)
- Current Objectives (specific, measurable)
- Work Completed This Session (achievements)
- Current Task Context (details, status, challenges)
- Next Steps (immediate and future)
- Memory Updates Needed (insights to capture)
- Technical Context (tools, files, dependencies)
- Decision Log (choices made, rationale)
```

### Layer 2: Short-Term Memory (`WORKING_LOG/`)
**Purpose**: Daily activities, decisions, and progress tracking
**Update Frequency**: End of significant work sessions
**Content Focus**: What happened and why it matters

```
WORKING_LOG Structure:
WORKING_LOG/YYYY/MM-mmm/wl_YYYY_MM_DD.md

Content Priorities (Information Entropy):
- HIGH: Surprising discoveries, non-obvious solutions
- HIGH: Architectural insights that change understanding
- HIGH: Integration failures and their resolutions
- MEDIUM: Decisions made and their rationale
- LOW: Routine implementations (brief summary only)
```

### Layer 3: Long-Term Memory (`write_memory tool`)
**Purpose**: Cross-project patterns, valuable insights, reusable knowledge
**Update Frequency**: When insights apply beyond current project
**Content Focus**: Knowledge worth preserving long-term

```
Long-Term Memory Categories:
- project-[name]-architecture: Key decisions, patterns, debt
- project-[name]-integration: External dependencies, gotchas
- pattern-[domain]: Reusable solutions and anti-patterns
- tool-[name]-usage: MCP tool insights and optimization
- quality-[aspect]: Quality improvement patterns
```

## Information Entropy Protocol

### High-Entropy Information (ALWAYS Document)
**The Surprise Test**: "Would this surprise a competent engineer in 6 months?"

**Document These**:
- Architectural assumptions that proved wrong
- Performance bottlenecks in unexpected places
- Integration failures with non-obvious causes
- Solutions that work for surprising reasons
- Dependencies that break in subtle ways
- Patterns that apply across multiple domains

**Examples**:
```
HIGH: "FastAPI's async context managers don't work with SQLAlchemy sessions in background tasks"
HIGH: "React re-renders triggered by parent component cause expensive API calls in child"
HIGH: "Git submodules break when repository is renamed on GitHub"
```

### Low-Entropy Information (Skip or Brief Summary)
**Routine implementations, expected behavior, standard procedures**

**Skip These**:
- "Implemented CRUD endpoints as specified"
- "Fixed linting errors and updated documentation"
- "Added unit tests following existing patterns"
- "Merged PR after code review approval"

### Memory Content Templates

#### High-Entropy Insight Template
```
MEMORY: [descriptive-name]
CONTEXT: [When/where this applies]
INSIGHT: [The surprising discovery]
EVIDENCE: [Why this is true]
IMPACT: [How this affects future work]
PATTERN: [Broader applicability]
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
```

## Memory Operations Command Reference

### Capture Operations
```
capture insight [type]     → Apply entropy filter → write_memory
capture pattern [domain]   → Extract reusable solution → write_memory
capture failure [context]  → Document anti-pattern → write_memory
```

### Recall Operations
```
recall context [domain]    → list_memories → read_memory [relevant]
recall pattern [type]      → search memories → load applicable knowledge
recall project [name]      → load project-specific context
```

### Maintenance Operations
```
sync consciousness         → Update all layers with current state
clean memory [type]        → Remove obsolete information
audit memory               → Check consistency across layers
```

## Session Memory Workflows

### Session Start Memory Loading
```
EXECUTE Memory Restoration:
1. Load ACTIVE_CONTEXT.md (immediate context)
2. Review recent WORKING_LOG entries (recent activities)
3. mcp__serena__list_memories (available long-term knowledge)
4. mcp__serena__read_memory [relevant_project_memories]
5. Synthesize loaded context for current work
```

### Session End Memory Preservation
```
EXECUTE Memory Preservation:
1. Update ACTIVE_CONTEXT.md with session summary
2. Create WORKING_LOG entry for significant work (entropy filter)
3. mcp__serena__write_memory for cross-project insights
4. Verify consciousness consistency across layers
5. Set context for next session
```

### Context Switch Memory Management
```
EXECUTE Context Switch:
1. Preserve current ACTIVE_CONTEXT.md state
2. Archive current session context to WORKING_LOG
3. Load new context from target domain memories
4. Update ACTIVE_CONTEXT.md for new context
5. Validate tool states and consciousness coherence
```

## Memory Organization Patterns

### File Naming Conventions
```
ACTIVE_CONTEXT.md          → Always same name, overwritten
wl_YYYY_MM_DD.md           → Working log, date-based
project-[name]-[aspect]    → Long-term project memories
pattern-[domain]-[type]    → Reusable patterns
tool-[name]-[insight]      → MCP tool optimizations
quality-[aspect]-[pattern] → Quality improvement insights
```

### Cross-Reference Patterns
```
Memory Linking:
- Reference related memories in new entries
- Link working log entries to long-term insights
- Connect patterns across different domains
- Build knowledge graphs through references
```

### Knowledge Evolution
```
Memory Updates:
- Revise memories when understanding changes
- Consolidate related insights into patterns
- Deprecate obsolete information gracefully
- Track knowledge evolution over time
```

## Memory Quality Standards

### Content Quality Requirements
```
High-Quality Memory Entry:
- Specific, actionable information
- Clear context and applicability
- Evidence supporting the insight
- Cross-project relevance assessment
- Integration with existing knowledge
```

### Maintenance Standards
```
Memory Hygiene:
- Regular review of memory relevance
- Consolidation of related insights
- Removal of obsolete information
- Consistency verification across layers
- Knowledge gap identification
```

## Memory System Integration

### Tool Integration
```
Memory-Aware Tool Usage:
- Check memories before starting complex tasks
- Capture insights during tool usage
- Document tool optimization patterns
- Build memory-driven workflow improvements
```

### Workflow Integration
```
Memory-Enhanced Workflows:
- Load relevant context at workflow start
- Capture insights during execution
- Update memories at completion
- Build pattern libraries from repeated workflows
```

### Quality Integration
```
Memory-Driven Quality:
- Use past insights for quality assessment
- Learn from previous quality issues
- Build quality pattern libraries
- Track quality improvement over time
```

## Emergency Memory Procedures

### Memory Corruption Recovery
```
EXECUTE Memory Recovery:
1. Identify corrupted or inconsistent memories
2. Restore from git history if available
3. Reconstruct from working logs and context
4. Verify consciousness coherence after restoration
5. Document recovery process for future prevention
```

### Context Loss Recovery
```
EXECUTE Context Recovery:
1. Load latest ACTIVE_CONTEXT.md backup
2. Review recent WORKING_LOG entries for clues
3. Check git commit history for recent work
4. Reconstruct context from available evidence
5. Resume work from best available starting point
```

### Memory Overflow Management
```
EXECUTE Memory Optimization:
1. Audit memories for relevance and utility
2. Consolidate related insights into patterns
3. Archive obsolete information
4. Focus on high-entropy information only
5. Optimize memory organization for efficiency
```

## Memory System Metrics

### Effectiveness Indicators
```
Memory System Health:
- Context restoration speed and accuracy
- Knowledge retrieval success rate
- Cross-project pattern application
- Insight quality and actionability
- Memory system maintenance overhead
```

### Optimization Targets
```
Performance Goals:
- < 5 minutes for complete context restoration
- > 90% relevant memory retrieval accuracy
- Consistent cross-session knowledge continuity
- Decreasing time to apply past insights
- Minimal memory maintenance overhead
```

---

**Memory Philosophy**: Preserve surprises, forget routine, connect patterns, enable continuity
**Information Entropy**: Document what would genuinely surprise future self
**Usage Pattern**: Load → Work → Capture → Preserve → Continue