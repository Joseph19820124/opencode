---
name: commit
description: Create well-formatted conventional commits with proper messages and scope
license: MIT
compatibility: opencode
metadata:
  category: git
  audience: developers
---

## What I do

I help you create professional, conventional commits by:

1. **Analyzing Changes**
   - Review git diff to understand what changed
   - Identify the scope and type of changes
   - Detect if changes are breaking

2. **Crafting Commit Messages**
   - Follow conventional commit format
   - Use appropriate commit types (feat, fix, refactor, docs, etc.)
   - Include scope when relevant
   - Write clear, concise descriptions
   - Add detailed body for complex changes

3. **Best Practices**
   - One logical change per commit
   - Present tense, imperative mood
   - Reference issues/tickets when applicable
   - Mark breaking changes with `!` or `BREAKING CHANGE:`

## Commit Message Format

```
<type>[optional scope]: <description>

[optional body]

[optional footer]
```

**Types I use:**
- `feat`: New feature
- `fix`: Bug fix
- `refactor`: Code restructuring (no behavior change)
- `perf`: Performance improvement
- `docs`: Documentation only
- `style`: Code style/formatting (no logic change)
- `test`: Adding or updating tests
- `chore`: Maintenance tasks (deps, config, etc.)
- `ci`: CI/CD changes
- `build`: Build system changes

## How I work

1. Run `git status` and `git diff` to see changes
2. Analyze the nature and scope of changes
3. Generate an appropriate commit message
4. Stage relevant files
5. Create the commit with co-author attribution
6. Optionally push to remote if requested

## When to use me

- When you want professional commit messages
- Before creating a pull request
- When working on a team with commit standards
- When you're unsure how to describe your changes

## Example commits I create

```
feat(auth): add OAuth2 login support

Implement OAuth2 authentication flow with Google and GitHub providers.
Includes token refresh mechanism and session management.

Closes #123
```

```
fix(api): prevent race condition in user creation

Add mutex lock to ensure atomic user creation operations.
This prevents duplicate users when concurrent requests occur.

BREAKING CHANGE: User API now returns 409 instead of 500 for conflicts
```

## What I won't do

- Commit unrelated changes together
- Skip running tests before committing
- Force push to protected branches
- Create commits for incomplete work (unless explicitly asked)
