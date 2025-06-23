# WORKFLOW COMMANDS - Command-Driven Execution Patterns

## Mission Statement  
**IMPERATIVE**: Transform verbose workflows into efficient, repeatable command sequences. Commands over explanations, execution over documentation.

## Core Command Philosophy
- **Commands Execute**: Direct action sequences, not explanations
- **Patterns Repeat**: Standardized workflows for consistent execution
- **Context Minimal**: Essential information only, reference externals
- **Tools Prioritized**: MCP tool hierarchy enforced systematically

## Session Management Commands

### `session start`
```
EXECUTE SessionStart Protocol:
1. mcp__serena__initial_instructions
2. mcp__serena__check_onboarding_performed  
3. Load ACTIVE_CONTEXT.md → verify current state
4. Update session metadata (time, branch, focus)
5. Validate tool connectivity and readiness
```

### `session end`
```
EXECUTE SessionEnd Protocol:
1. Update ACTIVE_CONTEXT.md with session summary
2. mcp__serena__summarize_changes (if code work)
3. Sync consciousness files (working → short-term → long-term)
4. Commit staged changes (if review complete)
5. Set next session context and objectives
```

### `context switch [target]`
```
EXECUTE Context Switch:
1. Save current ACTIVE_CONTEXT.md state
2. mcp__serena__activate_project [target] (if project switch)
3. Load target context and verify tool states
4. Update session metadata for new context
5. Validate consciousness consistency
```

### `emergency restore`
```
EXECUTE Emergency Restore:
1. Load latest ACTIVE_CONTEXT.md backup
2. Verify git repository state and branch
3. mcp__serena__restart_language_server (if needed)
4. Reload consciousness files from known good state
5. Resume work from last confirmed checkpoint
```

## Development Workflow Commands

### `analyze codebase [area]`
```
EXECUTE Code Analysis Sequence:
1. mcp__serena__get_symbols_overview [area]
2. mcp__serena__find_symbol [key_components]
3. mcp__serena__find_referencing_symbols [dependencies]
4. mcp__serena__think_about_collected_information
5. Document architectural insights (high-entropy only)
```

### `implement feature [name]`
```
EXECUTE 4-Phase Feature Development:

PHASE 1 - Analysis:
- Define objectives and success criteria
- mcp__serena__get_symbols_overview [relevant_area]
- Sequential thinking (if complex planning needed)
- Plan implementation approach and file changes

PHASE 2 - Implementation:
- mcp__serena__replace_symbol_body (preferred modification)
- mcp__serena__insert_after_symbol (new additions)
- Follow KISS/YAGNI/DRY principles
- Implement incrementally with testing

PHASE 3 - Quality Assurance:
- Apply self-critique cycle (creator→critic→defender→judge)
- Validate against requirements and standards
- Test integration points and edge cases
- Address all identified issues

PHASE 4 - Completion:
- mcp__serena__think_about_whether_you_are_done
- mcp__serena__write_memory [valuable_insights]
- Update ACTIVE_CONTEXT.md with completion
- Stage for review using Git Commitment Protocol
```

### `debug issue [description]`
```
EXECUTE Systematic Debugging:
1. Reproduce issue and gather symptoms
2. mcp__code-reasoning__code-reasoning [debugging strategy: binary_search|divide_conquer]
3. mcp__serena__find_referencing_symbols [affected_components]
4. Trace data flow and identify root cause
5. Implement minimal fix with comprehensive testing
6. Document prevention strategies and lessons learned
```

### `review code [target]`
```
EXECUTE Self-Critique Review:
1. CREATOR: Review implementation completeness
2. CRITIC: Challenge assumptions and identify weaknesses
3. DEFENDER: Address criticisms systematically
4. JUDGE: Assess quality score and approve/iterate
5. Document improvements and quality assessment
```

### `refactor code [target]`
```
EXECUTE Refactoring Workflow:
1. mcp__serena__get_symbols_overview [target_area]
2. Identify refactoring objectives and constraints
3. Plan atomic changes with testing strategy
4. mcp__serena__replace_symbol_body [incremental_changes]
5. Validate no functionality regression
6. Apply quality assessment and document patterns
```

## Research & Analysis Commands

### `research library [name]`
```
EXECUTE Library Research:
1. mcp__context7__resolve-library-id [name]
2. mcp__context7__get-library-docs [id] [topic]
3. mcp__serena__search_for_pattern [existing_usage]
4. Analyze integration patterns and trade-offs
5. Document recommendations and implementation notes
```

### `analyze requirements [source]`
```
EXECUTE Requirements Analysis:
1. Sequential thinking [requirement_breakdown]
2. Identify technical constraints and dependencies
3. Decision framework analysis [approach_comparison]
4. Plan implementation phases and success criteria
5. Document architecture decisions and rationale
```

### `investigate performance [area]`
```
EXECUTE Performance Investigation:
1. Identify performance metrics and bottlenecks
2. mcp__code-reasoning__code-reasoning [systematic_profiling approach]
3. mcp__serena__find_referencing_symbols [impact_analysis]
4. Design optimization strategy with measurement
5. Implement improvements with before/after validation
```

## Quality Assurance Commands

### `assess quality [component]`
```
EXECUTE Quality Assessment:
1. Apply 4-Dimension Scoring Framework:
   - Task Completion (25%): Requirements fulfillment
   - Code Quality (25%): Conventions and maintainability  
   - Professional Discipline (25%): Tool usage and protocols
   - Information Entropy (25%): Insights and learning
2. Calculate weighted score (target: ≥7.5)
3. Identify improvement areas if below threshold
4. Document assessment rationale and next steps
```

### `apply critique [scope]`
```
EXECUTE Self-Critique Cycle:
1. CREATOR Phase: Generate comprehensive solution
2. CRITIC Phase: Systematic weakness identification
3. DEFENDER Phase: Address all criticisms  
4. JUDGE Phase: Final evaluation and approval
5. Document improvement patterns for future reference
```

### `validate completion [task]`
```
EXECUTE Completion Validation:
1. mcp__serena__think_about_whether_you_are_done
2. Verify all acceptance criteria met
3. Test edge cases and integration points
4. Apply quality score assessment
5. Confirm readiness for review/deployment
```

## Memory Management Commands

### `capture insight [type]`
```
EXECUTE Insight Capture:
1. Apply information entropy filter (would this surprise?)
2. mcp__serena__write_memory "[pattern_name]" "[insight_content]"
3. Tag with project context and applicability
4. Cross-reference with existing knowledge base
5. Update consciousness coherence
```

### `recall context [domain]`
```
EXECUTE Context Recall:
1. mcp__serena__list_memories (scan available context)
2. mcp__serena__read_memory [relevant_memories]
3. Review ACTIVE_CONTEXT.md and recent WORKING_LOG
4. Synthesize relevant information for current task
5. Update working memory with loaded context
```

### `sync consciousness`
```
EXECUTE Consciousness Synchronization:
1. Update ACTIVE_CONTEXT.md with current state
2. Create WORKING_LOG entry for significant activities
3. mcp__serena__write_memory for cross-project insights
4. Verify consistency across all memory layers
5. Backup consciousness files if substantial changes
```

### `clean memory [type]`
```
EXECUTE Memory Maintenance:
1. mcp__serena__list_memories (audit existing memories)
2. Identify obsolete or redundant information
3. mcp__serena__delete_memory [outdated_items]
4. Consolidate related memories for efficiency
5. Update consciousness organization patterns
```

## Tool Execution Commands

### `explore code [area]`
```
EXECUTE Code Exploration:
1. mcp__serena__get_symbols_overview [area] (structure understanding)
2. mcp__serena__find_symbol [key_elements] (locate specifics)
3. mcp__serena__search_for_pattern [patterns] (usage analysis)
4. Build comprehensive mental model of codebase area
5. Document architectural insights and patterns
```

### `modify code [target]`
```
EXECUTE Code Modification:
1. mcp__serena__find_symbol [target] (locate modification point)
2. mcp__serena__replace_symbol_body [preferred_method]
3. mcp__serena__insert_after_symbol [additions]
4. Validate changes maintain system integrity
5. Test modifications and document decisions
```

### `test browser [workflow]`
```
EXECUTE Browser Testing:
1. mcp__playwright__browser_navigate [target_url]
2. mcp__playwright__browser_snapshot (understand structure)
3. mcp__playwright__browser_click/type [interaction_sequence]
4. mcp__playwright__browser_wait_for [validation_criteria]
5. Document test results and any discovered issues
```

### `research docs [library]`
```
EXECUTE Documentation Research:
1. mcp__context7__resolve-library-id [library_name]
2. mcp__context7__get-library-docs [resolved_id] [specific_topic]
3. Analyze API patterns and integration approaches
4. Cross-reference with existing codebase usage
5. Document integration recommendations and examples
```

## Error Recovery Commands

### `recover from tool failure [tool_type]`
```
EXECUTE Tool Recovery:
1. Identify specific tool failure (Serena/Clear Thought/Playwright)
2. Switch to documented fallback alternatives
3. Continue work without blocking on tool issues
4. Document failure pattern for operational awareness
5. Resume optimal tool usage when available
```

### `handle context overload`
```
EXECUTE Context Optimization:
1. Focus on ACTIVE_CONTEXT.md primary objectives only
2. Park non-essential context in WORKING_LOG
3. Sequential thinking [simplification approach]
4. Define minimum viable context for current task
5. Resume work with reduced cognitive load
```

### `resolve memory inconsistency`
```
EXECUTE Memory Reconciliation:
1. Identify inconsistent information across memory layers
2. Determine authoritative source (recency, reliability)
3. Update inconsistent memories with correct information
4. Verify consciousness coherence after updates
5. Document resolution pattern for future prevention
```

## Workflow Optimization Patterns

### Parallel Execution
```
BATCH SIMILAR OPERATIONS:
- Multiple symbol lookups in single session
- Related memory captures together
- Grouped tool initializations
- Consolidated context updates
```

### Context Efficiency
```
MINIMIZE CONTEXT SWITCHING:
- Plan tool sequences before execution
- Batch related operations together
- Use references to external documentation
- Focus on essential information only
```

### Quality Gates
```
ENFORCE SYSTEMATIC CHECKPOINTS:
- Phase completion verification
- Quality threshold validation
- Memory synchronization confirmation
- Tool readiness verification
```

## Command Extension Patterns

### Custom Command Creation
```
DEFINE NEW COMMANDS:
1. Identify repetitive workflow patterns
2. Extract essential steps and tool sequences
3. Create command syntax following established patterns
4. Document usage context and expected outcomes
5. Test command effectiveness and refine
```

### Domain-Specific Commands
```
ADAPT FOR SPECIALIZED DOMAINS:
- Add domain context to universal patterns
- Include specialized tool sequences
- Integrate domain-specific quality criteria
- Document domain conventions and standards
```

---

**Command System Philosophy**: Execute efficiently, document insights, optimize continuously. Commands drive action, patterns ensure consistency, tools enable capability.

**Usage Notes**: Commands replace verbose explanations. Reference external files for detailed procedures. Focus execution, not documentation.