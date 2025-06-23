# Create Command from Workflow

Analyze recent conversation context to create a new slash command for the workflow: $ARGUMENTS

## Process:
1. **Context Analysis:** Review the last 10-15 messages in our conversation to identify the workflow pattern for "$ARGUMENTS"

2. **Pattern Extraction:** Identify the sequence of steps, tools used, and decision points in the completed workflow

3. **Generalization:** Remove project-specific details and create a reusable template that works across different projects

4. **Template Generation:** Create a markdown command with:
   - Clear title and description
   - Step-by-step process instructions
   - Benefits and use cases
   - Proper argument handling if needed

5. **Confirmation:** Present the generated command template and ask for user approval

6. **File Creation:** Once approved, create the actual .md file in `.claude/commands/` directory

## Benefits:
- ✅ Converts manual workflows into reusable automation
- ✅ Learns from conversation context intelligently  
- ✅ Creates consistent, well-structured commands
- ✅ Builds a growing library of workflow automations

## Example Usage:
```bash
/project:create-command "dependency refresh workflow"
/project:create-command "Django setup process"
/project:create-command "testing pipeline"
```

This meta-command creates a self-improving automation system where any completed manual workflow can be instantly converted into a reusable slash command.