# Apply Critique Command

## Description
Self-critique cycle execution with 4-phase systematic improvement workflow

## Category
quality-assurance

## Prompt

Execute self-critique cycle for the specified scope:

**Critique Scope**: [Specify code, design, or implementation to critique]

## 4-Phase Self-Critique Cycle:

### Phase 1 - CREATOR
- Generate comprehensive solution focused on functionality
- Prioritize user value delivery and requirement fulfillment
- Document implementation decisions and design rationale
- Optimize for immediate user needs

### Phase 2 - CRITIC  
- Challenge all assumptions systematically and rigorously
- Identify edge cases, failure modes, and potential weaknesses
- Assess security, performance, and integration risks
- Question design choices and explore alternative approaches

### Phase 3 - DEFENDER
- Address each criticism systematically with concrete improvements
- Implement fixes and enhancements based on critique findings
- Validate that solutions don't introduce new regressions
- Document responses to criticisms with evidence

### Phase 4 - JUDGE
- Compare original solution vs improved version objectively
- Apply 4-dimension quality assessment framework
- Determine if quality meets standards (≥7.5 threshold)
- Approve for completion or require additional iteration cycles

5. **Capture Patterns**: Document improvement patterns for future reference with `mcp__serena__write_memory`

This command ensures systematic quality improvement through structured self-critique and iterative enhancement.