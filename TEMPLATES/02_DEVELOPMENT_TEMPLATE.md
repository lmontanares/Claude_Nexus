# Development Template - Feature Implementation Workflow

## `implement feature [name]`

### Phase 1: Analysis & Planning
```
□ Define objectives and success criteria
□ mcp__serena__get_symbols_overview [target_area]
□ mcp__serena__find_symbol [related_functionality]
□ Sequential thinking (if complex planning needed)
□ Plan implementation approach
□ Document architectural decisions
```

**Planning Checklist**:
- **Feature Name**: [Descriptive name]
- **User Value**: [Why users need this]
- **Success Criteria**: [Measurable completion criteria]
- **Files to Modify**: [Specific files and components]
- **Integration Points**: [How it connects to existing system]
- **Testing Strategy**: [How feature will be validated]

### Phase 2: Implementation
```
□ mcp__serena__replace_symbol_body [primary_modifications]
□ mcp__serena__insert_after_symbol [new_additions]
□ Follow KISS/YAGNI/DRY principles
□ Implement incrementally with testing
□ Document implementation decisions
□ Handle edge cases and errors
```

**Implementation Progress**:
- [ ] **Core Logic**: [Main functionality implemented]
- [ ] **Error Handling**: [Edge cases and failures handled]
- [ ] **Integration**: [Connected to existing systems]
- [ ] **Testing**: [Functionality validated]
- [ ] **Documentation**: [Code comments and docs updated]

### Phase 3: Quality Assurance
```
□ Apply self-critique cycle (if medium/high impact)
□ Validate against requirements
□ Test integration points
□ Check edge cases and error conditions
□ Apply quality assessment (target ≥7.5)
□ Address identified issues
```

**Quality Checklist**:
- [ ] **Task Completion**: Solves stated problem completely
- [ ] **Code Quality**: Follows Claude_Nexus conventions
- [ ] **Professional Discipline**: Proper tool usage and protocols
- [ ] **Information Entropy**: Valuable insights documented

### Phase 4: Completion
```
□ mcp__serena__think_about_whether_you_are_done
□ mcp__serena__summarize_changes
□ mcp__serena__write_memory [valuable_insights]
□ Update ACTIVE_CONTEXT.md
□ Stage changes: git add [files]
□ Request review: "Feature [name] complete and staged"
```

## Development Command Sequences

### Code Exploration
```
explore code [area]
1. mcp__serena__get_symbols_overview [area]
2. mcp__serena__find_symbol [key_components]
3. mcp__serena__find_referencing_symbols [dependencies]
4. Document architectural insights
```

### Code Modification
```
modify code [target]
1. mcp__serena__find_symbol [target]
2. mcp__serena__replace_symbol_body [changes]
3. Validate changes maintain integrity
4. Test modifications
```

### Bug Debugging
```
debug issue [description]
1. Reproduce issue and gather symptoms
2. mcp__code-reasoning__code-reasoning [debugging strategy]
3. mcp__serena__find_referencing_symbols [trace_flow]
4. Implement minimal fix with testing
5. Document lessons learned
```

## Development Patterns

### Claude_Nexus Principles Application
```
KISS (Keep It Simple):
□ Choose simplest solution meeting requirements
□ Avoid unnecessary complexity
□ Prefer readable over clever code

YAGNI (You Aren't Gonna Need It):
□ Only implement current requirements
□ Avoid speculative features
□ Focus on immediate user needs

DRY (Don't Repeat Yourself):
□ Extract common patterns after 2-3 repetitions
□ Balance abstraction with readability
□ Reuse existing utilities appropriately
```

### Quality Integration
```
Quality During Development:
□ Regular quality checks during implementation
□ Address quality issues immediately
□ Document surprising discoveries
□ Apply self-critique for complex changes
□ Maintain quality score target ≥7.5
```

## Troubleshooting Development Issues

### Implementation Challenges
```
Problem: Unclear requirements
Solution: 
□ Sequential thinking [breakdown approach]
□ Document assumptions
□ Get stakeholder clarification
□ Focus on MVP first

Problem: Integration complications  
Solution:
□ mcp__serena__find_referencing_symbols [dependencies]
□ Break integration into smaller pieces
□ Test each integration point separately
□ Consider alternative integration approaches
```

### Quality Issues
```
Problem: Code quality below standards
Solution:
□ Apply full self-critique cycle
□ Focus on one quality dimension at a time
□ Refactor systematically using symbol-based tools
□ Get external review if needed

Problem: Performance concerns
Solution:
□ Profile before optimizing
□ Use first principles to understand bottlenecks
□ Consider caching, algorithms, or architecture changes
□ Measure before/after improvements
```

---
**Development Philosophy**: Plan → Implement → Validate → Complete
**Quality Focus**: Built-in quality, not bolted-on
**Tool Priority**: MCP tools first, fallbacks when needed