# TOOL QUICK REFERENCE - 30-Second Selection

## 5-Second Decision Tree

**IMPERATIVE**: Always follow this hierarchy
```
Need to do what?

📄 Code work?          → Serena Tools (Primary)
🧠 Code reasoning?     → Code-reasoning Tools
🌐 Browser testing?    → Playwright Tools  
📚 Documentation?      → Context7 Tools
🔧 GitHub operations?  → GitHub Tools
📁 Simple files?       → Native Tools (Last Resort)
```

## Essential Tool Commands

### Serena Tools (PRIMARY - Use First)

#### Session Initialization (ALWAYS START)
```
mcp__serena__initial_instructions          → Get project context
mcp__serena__check_onboarding_performed    → Verify setup
mcp__serena__onboarding                    → If setup needed
```

#### Code Analysis Sequence  
```
mcp__serena__get_symbols_overview [path]   → START HERE for new code
mcp__serena__find_symbol [pattern]         → Locate specific elements
mcp__serena__find_referencing_symbols      → Trace dependencies
mcp__serena__search_for_pattern [regex]    → Find by content
```

#### Code Modification Hierarchy
```
mcp__serena__replace_symbol_body           → PREFERRED modification method
mcp__serena__insert_after_symbol           → Add new functions/methods
mcp__serena__insert_before_symbol          → Add imports/setup
mcp__serena__replace_regex                 → LAST RESORT for complex changes
```

#### Quality & Completion
```
mcp__serena__think_about_task_adherence    → Before major changes
mcp__serena__think_about_collected_information → After research
mcp__serena__think_about_whether_you_are_done → Completion check
mcp__serena__summarize_changes             → Document work
```

#### Memory Management
```
mcp__serena__write_memory [name] [content] → Save valuable insights
mcp__serena__read_memory [name]            → Recall saved context
mcp__serena__list_memories                 → Browse available knowledge
```

### Code-reasoning Tools (Code-Specific Reasoning)

#### Code Analysis & Architecture
```
mcp__code-reasoning__code-reasoning        → Code architecture decisions
mcp__code-reasoning__code-reasoning        → Complex debugging of code  
mcp__code-reasoning__code-reasoning        → Code design patterns
mcp__code-reasoning__code-reasoning        → Performance analysis
```

#### General Problem Solving (Plain Claude)
```
Sequential thinking                        → Multi-step planning (no tools)
Systematic analysis                        → Decision making (no tools)
Problem decomposition                      → Break down complexity (no tools)
Multiple perspectives                      → Consider alternatives (no tools)
```

### Playwright Tools (Browser Testing)

#### Browser Navigation & Analysis
```
mcp__playwright__browser_navigate [url]    → Go to page
mcp__playwright__browser_snapshot          → SEE page structure (use first)
mcp__playwright__browser_take_screenshot   → Visual capture
```

#### Interaction Sequence
```
mcp__playwright__browser_click [element] [ref]     → Click elements
mcp__playwright__browser_type [element] [text]     → Fill forms
mcp__playwright__browser_select_option [values]    → Dropdown selection
mcp__playwright__browser_wait_for [condition]      → Wait for changes
```

### Context7 Tools (Documentation)

#### Library Research
```
mcp__context7__resolve-library-id [name]   → ALWAYS DO THIS FIRST
mcp__context7__get-library-docs [id]       → Get current documentation
```

### Native Tools (Fallback Only)

#### When MCP Tools Fail
```
Serena failure fallbacks:
- get_symbols_overview ❌ → LS + Read
- find_symbol ❌ → Grep  
- replace_symbol_body ❌ → Edit
- search_for_pattern ❌ → Grep
```

## Workflow Tool Sequences

### Code Exploration Workflow
```
1. mcp__serena__get_symbols_overview [area]
2. mcp__serena__find_symbol [target]
3. mcp__serena__find_referencing_symbols [dependencies]
4. Document insights with write_memory
```

### Feature Development Workflow
```
1. Sequential thinking [planning approach]
2. mcp__serena__get_symbols_overview [codebase]
3. mcp__serena__replace_symbol_body [implementation]
4. mcp__serena__think_about_whether_you_are_done
```

### Bug Investigation Workflow
```
1. mcp__code-reasoning__code-reasoning [debugging strategy]
2. mcp__serena__find_referencing_symbols [trace_flow]
3. mcp__serena__replace_symbol_body [fix]
4. mcp__serena__write_memory [lessons_learned]
```

### Browser Testing Workflow
```
1. mcp__playwright__browser_navigate [url]
2. mcp__playwright__browser_snapshot
3. mcp__playwright__browser_click/type [interactions]
4. mcp__playwright__browser_wait_for [validation]
```

### Research Workflow
```
1. mcp__context7__resolve-library-id [library]
2. mcp__context7__get-library-docs [id] [topic]
3. mcp__serena__search_for_pattern [existing_usage]
4. mcp__serena__write_memory [integration_notes]
```

## Tool Selection Rules

### Priority Enforcement
1. **Try MCP tools first** (30 seconds max)
2. **If MCP fails, switch immediately** to documented fallbacks
3. **Don't debug tools** - focus on work completion
4. **Document tool failures** for operational awareness

### Context Efficiency
```
Batch Operations:
- Multiple symbol lookups together
- Related memory operations
- Sequential browser interactions
- Grouped context updates
```

### Quality Gates
```
Tool Readiness Verification:
- Serena tools responding
- Code-reasoning tools accessible
- Browser tools functional
- All fallbacks documented
```

## Emergency Procedures

### Tool Failure Recovery
```
Serena Tools Unresponsive:
1. Try mcp__serena__restart_language_server
2. Switch to native tool alternatives
3. Continue work without blocking
4. Document failure for later resolution

Code-reasoning Tools Error:
1. Simplify code problem statement  
2. Use plain Claude reasoning approach
3. Continue with implementation
4. Note pattern for future reference

Playwright Tools Broken:
1. Use manual browser testing
2. Document test steps manually
3. Continue validation process
4. Report issues for resolution
```

### Context Overload
```
Too Much Information:
1. Focus on ACTIVE_CONTEXT primary objectives
2. Park non-essential context for later
3. Use sequential thinking to break down complexity
4. Define minimum viable context for current task
```

## Tool Performance Optimization

### Efficiency Patterns
```
Minimize Tool Switching:
- Plan tool sequences before starting
- Batch similar operations together
- Use thinking tools for planning, not micro-decisions
- Prefer symbol-based operations over file reads
```

### Context Management
```
Reduce Context Usage:
- Use get_symbols_overview before deep reading
- Focus searches with specific patterns
- Prefer symbol-based edits over full file operations
- Batch memory operations
```

## Success Metrics

### Tool Selection Effectiveness
- **Selection Time**: Target < 30 seconds
- **Tool Switching**: Minimize mid-task changes
- **Fallback Usage**: Track frequency and causes
- **Task Completion**: Overall efficiency improvement

### Quality Indicators
- Consistent tool hierarchy usage
- Reduced cognitive overhead in tool selection
- Improved workflow execution speed
- Better pattern recognition and reuse

---

**Tool Philosophy**: MCP First, Fallback Fast, Document Failures, Focus Work
**Usage Pattern**: Select → Execute → Validate → Continue
**Optimization**: Batch Similar, Plan Sequences, Minimize Switching