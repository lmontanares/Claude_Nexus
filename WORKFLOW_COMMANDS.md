# WORKFLOW COMMANDS - Slash Command Orchestration

## Mission Statement  
**IMPERATIVE**: Orchestrate complex workflows through slash command composition. Multi-step patterns, decision trees, and workflow automation using Claude Code command system.

## Core Workflow Philosophy
- **Compose Commands**: Chain slash commands for complex multi-step workflows
- **Decision-Driven**: Use conditional logic for workflow branching
- **Pattern-Based**: Reusable workflow templates for systematic execution
- **Reference-Based**: Individual commands in `.claude/commands/` contain detailed execution

## Slash Command Quick Reference

### Session Management
- `/session-start` - Initialize session with tools and context
- `/session-end` - Close session with memory sync and staging
- `/context-switch` - Switch between projects or contexts
- `/emergency-restore` - Recover from session/context failures

### Development Workflows
- `/analyze-codebase` - Systematic code analysis and architecture understanding
- `/implement-feature` - 4-phase feature development with quality gates
- `/debug-issue` - Systematic debugging with root cause analysis
- `/review-code` - Self-critique review process with improvement cycle
- `/refactor-code` - Safe refactoring with regression prevention
- `/explore-code` - Code exploration for mental model building
- `/modify-code` - Symbol-based code modification with validation

### Research & Analysis
- `/research-library-docs` - Context7 documentation research for libraries
- `/research-web` - Playwright web research for live sites and demos
- `/analyze-requirements` - Requirements breakdown with decision framework
- `/investigate-performance` - Performance analysis and optimization

### Quality Assurance
- `/assess-quality` - 4-dimension quality assessment with scoring
- `/apply-critique` - Self-critique cycle for systematic improvement
- `/validate-completion` - Completion verification with readiness check

### Memory Management
- `/capture-insight` - High-entropy insight capture with cross-referencing
- `/recall-context` - Context restoration from distributed memory layers
- `/sync-consciousness` - Memory synchronization across all layers
- `/clean-memory` - Memory maintenance and consolidation

### Tool Execution
- `/test-browser` - Browser testing with systematic interaction sequences
- `/modify-code` - Code modification through symbol-based editing

### Error Recovery
- `/recover-tool-failure` - Tool failure recovery with fallback procedures
- `/handle-context-overload` - Context optimization for information overload
- `/resolve-memory-inconsistency` - Memory reconciliation across layers

## Multi-Command Workflow Patterns

### Complete Feature Development Flow
```
1. /session-start
2. /analyze-codebase [target_area]
3. /research-library-docs [dependencies] (if needed)
4. /implement-feature [feature_name]
5. /review-code [implementation]
6. /test-browser [feature_testing] (if UI involved)
7. /validate-completion [feature]
8. /session-end
```

### Debugging & Investigation Flow
```
1. /debug-issue [problem_description]
2. /investigate-performance [area] (if performance-related)
3. /modify-code [fix_implementation]
4. /test-browser [validation] (if UI involved)
5. /apply-critique [fix_review]
6. /validate-completion [fix]
```

### Research & Implementation Flow
```
1. /research-library-docs [library_name]
2. /research-web [demo_sites] (if needed)
3. /analyze-requirements [integration_specs]
4. /implement-feature [integration]
5. /assess-quality [implementation]
```

### Quality Improvement Flow
```
1. /assess-quality [target_component]
2. /apply-critique [identified_issues]
3. /refactor-code [improvements] (if needed)
4. /validate-completion [improved_version]
```

### Memory Management Flow
```
1. /recall-context [relevant_domain]
2. [Execute main work]
3. /capture-insight [valuable_discoveries]
4. /sync-consciousness
5. /clean-memory [outdated_items] (periodic)
```

## Conditional Workflow Decision Trees

### Research Decision Tree
```
Need information about:
├── Library/API documentation? → /research-library-docs
├── Live website/demo functionality? → /research-web  
├── Performance characteristics? → /investigate-performance
└── Requirements analysis? → /analyze-requirements
```

### Development Path Selection
```
Starting development work:
├── New feature? → /implement-feature
├── Bug fix needed? → /debug-issue → /modify-code
├── Code quality issues? → /apply-critique → /refactor-code
└── Exploration needed? → /analyze-codebase → /explore-code
```

### Quality Gate Decision Tree
```
Quality assessment results:
├── Score ≥ 7.5? → /validate-completion
├── Score 6.0-7.4? → /apply-critique → re-assess
├── Score < 6.0? → /refactor-code → /apply-critique → re-assess
└── Critical issues? → /debug-issue → restart workflow
```

### Error Recovery Decision Tree
```
Encountering errors:
├── Tool failure? → /recover-tool-failure
├── Context overload? → /handle-context-overload  
├── Memory inconsistency? → /resolve-memory-inconsistency
└── Session corruption? → /emergency-restore
```

## Advanced Workflow Automation

### Parallel Command Execution
```
Concurrent research workflow:
- Terminal 1: /research-library-docs [primary_library]
- Terminal 2: /research-web [competitor_analysis]  
- Terminal 3: /analyze-codebase [integration_points]
→ Synthesize results → /implement-feature
```

### Iterative Improvement Cycle
```
Quality improvement loop:
1. /assess-quality [component] 
2. If score < 7.5: /apply-critique [issues]
3. /modify-code [improvements]
4. Repeat step 1 until score ≥ 7.5
5. /validate-completion [final_version]
```

### Context-Aware Workflow Selection
```
Based on ACTIVE_CONTEXT.md objectives:
├── Research phase? → Research Flow pattern
├── Implementation phase? → Development Flow pattern  
├── Quality phase? → Quality Improvement Flow pattern
└── Completion phase? → Validation and documentation
```

## Workflow Efficiency Patterns

### Batched Operations
```
Memory management session:
/recall-context [project] → 
/capture-insight [discovery1] → 
/capture-insight [discovery2] → 
/sync-consciousness → 
/clean-memory [obsolete]
```

### Tool-Specific Workflows
```
Browser-heavy workflow:
/research-web [target_site] → 
/test-browser [functionality] → 
/implement-feature [ui_components] → 
/test-browser [validation]

Research-heavy workflow:  
/research-library-docs [lib1] →
/research-library-docs [lib2] →
/analyze-requirements [integration] →
/implement-feature [solution]
```

### Recovery-Enabled Workflows
```
Resilient development pattern:
1. /session-start
2. Try: /implement-feature [name]
3. On failure: /recover-tool-failure → retry
4. On quality issues: /apply-critique → improve
5. On completion: /validate-completion
6. /session-end
```

## Workflow Customization Guidelines

### Creating Custom Workflow Patterns
1. **Identify Repetitive Sequences**: Look for command combinations used frequently
2. **Define Decision Points**: Add conditional logic for workflow branching  
3. **Include Error Handling**: Plan recovery commands for common failure modes
4. **Optimize for Context**: Consider token efficiency and tool switching overhead
5. **Document Pattern**: Create reusable template with parameter placeholders

### Workflow Pattern Template
```
### [Pattern Name] Flow
**Purpose**: [Brief description]
**Triggers**: [When to use this workflow]
**Prerequisites**: [Required context or setup]

Workflow:
1. /command1 [parameter]
2. /command2 [parameter] 
3. [Conditional logic if needed]
4. /command3 [parameter]

**Success Criteria**: [How to know workflow completed successfully]
**Recovery**: [What to do if workflow fails]
```

---

**Workflow Philosophy**: Compose commands systematically, handle errors gracefully, optimize for efficiency
**Command Integration**: Individual commands provide execution, workflows provide orchestration
**Pattern Evolution**: Document successful patterns, iterate on workflow effectiveness