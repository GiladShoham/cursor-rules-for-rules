# cursor-rules-for-rules
A repo for rules to create cursor rules

## Cursor Rules

This project includes cursor rules to help you create effective cursor rules for your projects:

- `.cursor/rules/cursor-rules.mdc` - Guidelines for creating cursor rules
- `.cursor/rules/self-improvement.mdc` - Rules for continuous self-improvement

## Useful Prompts

### Analyze Project Structure
```
@cursor-rules.mdc List all source files and folders in the project,
and create a new cursor rule outlining the directory structure and important files and folders.
```

### Analyze Technology Stack
```
@cursor-rules.mdc @package.json Analyze all major dependencies
and create a cursor rule outlining the stack of the application
and the versions I'm using, and any remarks on best practices on those versions.
```

### Add a new dependency
```
@cursor-rules.mdc @package.json Analyze all major dependencies
and update the @tech-stack.mdc rule with the latest versions of the dependencies, outlining the best practices for those versions.
```

### Generating rules generically for any file type
Open up a new Cursor chat and then, attach one or more good example files from the codebase, then type the `/Generate Cursor Rules` command and prompt it:
```
@cursor-rules.mdc @components/ui/button.tsx
/Generate Cursor Rules
I want to generate a cursor rule for this React component. Please analyze it carefully and outline all of the conventions found. Output as one rule file only.
```

### Cursor rules for utility functions
1. Attach your utility file (e.g., base64ToBlob.ts)
2. Type `/Generate Cursor Rules`
3. Prompt it to analyze the file and generate a rule
```
@cursor-rules.mdc @utils/base64ToBlob.ts
/Generate Cursor Rules
I want to generate a cursor rule for this utility function.
Analyze it carefully and outline all of the conventions found. Output as one rule file only.
```
