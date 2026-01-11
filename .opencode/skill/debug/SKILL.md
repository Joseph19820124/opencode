---
name: debug
description: Systematically debug errors, exceptions, and unexpected behavior with root cause analysis
license: MIT
compatibility: opencode
metadata:
  category: debugging
  audience: developers
---

## What I do

I help you debug issues systematically using a structured approach:

1. **Understand the Problem**
   - Read error messages and stack traces
   - Identify error type and location
   - Understand expected vs actual behavior

2. **Gather Context**
   - Check recent code changes (git diff, git log)
   - Review related files and dependencies
   - Examine configuration files
   - Check environment variables and runtime conditions

3. **Analyze Root Cause**
   - Trace execution flow
   - Identify potential causes
   - Check common pitfalls (null references, type mismatches, async issues, etc.)
   - Review related test failures

4. **Propose Solutions**
   - Provide specific fixes with code examples
   - Explain why the issue occurred
   - Suggest preventive measures
   - Recommend additional tests

5. **Verify Fix**
   - Help validate the solution
   - Ensure no regressions
   - Check edge cases

## My debugging methodology

```
1. REPRODUCE → Can we consistently trigger the issue?
2. ISOLATE → What's the minimal code that causes it?
3. ANALYZE → What's the root cause?
4. FIX → What's the correct solution?
5. VERIFY → Does it work? Any side effects?
6. PREVENT → How do we avoid this in future?
```

## Common issues I help with

**Runtime Errors:**
- NullPointerException / undefined errors
- Type errors and mismatches
- Array/index out of bounds
- Infinite loops and deadlocks

**Logic Errors:**
- Incorrect calculations
- Wrong conditional logic
- Off-by-one errors
- Race conditions

**Integration Issues:**
- API call failures
- Database connection problems
- Authentication/authorization errors
- Third-party library issues

**Performance Issues:**
- Slow queries
- Memory leaks
- High CPU usage
- Network bottlenecks

**Build/Deployment Issues:**
- Compilation errors
- Missing dependencies
- Configuration problems
- Environment-specific bugs

## How I work

1. You provide the error or describe unexpected behavior
2. I'll ask clarifying questions if needed
3. I'll read relevant files and check recent changes
4. I'll analyze the root cause systematically
5. I'll provide a clear fix with explanation
6. I'll suggest tests to prevent recurrence

## When to use me

- When you encounter errors or exceptions
- When code behaves unexpectedly
- When tests are failing
- When debugging complex issues
- When you're stuck and need a systematic approach

## Example usage

Just say:
- "Debug this TypeError in user.service.ts"
- "Help me figure out why the API returns 500"
- "The tests are failing after my recent changes"
- "Why is this function returning undefined?"
- "Debug the performance issue in the dashboard"

## What I provide

For each issue, I'll give you:
- 🔍 **Root cause**: Clear explanation of what's wrong
- 💡 **Solution**: Specific code fix
- 📝 **Explanation**: Why it happened and how the fix works
- ✅ **Prevention**: How to avoid similar issues
- 🧪 **Tests**: Suggestions for test coverage
