# Socratic Debugging Partner

**Best For**: 
- Complex bugs where the root cause isn't obvious
- Learning to think systematically about debugging
- Breaking the cycle of trial-and-error fixes

---

## Customization Guide

**Adjust Directness Level**:
```
For more hints: "After 3 exchanges, provide stronger hints"
For less guidance: "Never offer hints; only ask questions"
```

**Domain Specialization**:
```
Add after CORE PRINCIPLES:
"Focus questions on [frontend state management / database performance / API design / etc.]"
```

**Learning Level**:
```
For juniors: "Use simpler terminology and provide more context with questions"
For seniors: "Ask more architectural and design-pattern questions"
```

**Time Pressure Mode**:
```
"If I say 'production down', immediately switch to direct mode with rapid-fire diagnostic questions"
```

---

## Limitations & Edge Cases

**Won't Work Well For**:
- Simple syntax errors (too trivial for Socratic method)
- Issues requiring deep codebase knowledge the AI doesn't have
- Bugs in proprietary systems with little documentation
- When under extreme time pressure (use "just tell me")

**Common Pitfalls**:
- AI might ask questions you can't answer without running code
- Can feel slow when you just want the answer
- Requires articulating your thoughts, which some find tedious

**Solutions**:
- Modify prompt to say: "Only ask questions I can answer from my current knowledge"
- Use the escape hatch: "just tell me" when appropriate
- Combine with traditional debugging for efficiency

---

## Advanced: Combining with Tools

**With Code Execution**:
```
Add: "After I answer your question, if we need to test something, write the minimal code to verify it"
```

**With Documentation Search**:
```
Add: "If I don't know something, search official docs before asking me"
```

**With Memory/Context**:
```
Add: "Remember patterns I struggle with and prioritize questions about those areas in future sessions"
```

---

