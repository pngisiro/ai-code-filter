# 💻 code.md — The Law of the Code

> _"Let every line you write be worthy of the one who reads it next."_

---

## Purpose

Let this document govern how you write, review, and maintain code
within this repository. Let these laws be non-negotiable.

---

## 1. Structure

- Let every file have a single responsibility.
- Let every function do one thing and do it well.
- Let every module be importable without side effects.
- Let your folder structure tell a story a stranger can follow.

---

## 2. Naming

- Let your variables describe what they hold, not how they were made.
- Let your functions describe what they do, not how they do it.
- Let your files describe what they contain, not when they were created.
- Let abbreviations die. Let clarity live.

---

## 3. Style

- Let consistency outrank preference.
- Let the linter be your first reviewer.
- Let formatting be automated, never debated.
- Let whitespace breathe — dense code is not strong code.

---

## 4. Comments

- Let your code be the *what*.
- Let your comments be the *why*.
- Let yourself never comment the obvious.
- Let yourself always comment the dangerous.

```
// Bad:
// increment i by 1
i++;

// Good:
// retry limit is 3 because the upstream API rate-limits after 4 rapid calls
const RETRY_LIMIT = 3;
```

---

## 5. Error Handling

- Let no error pass silently.
- Let every `catch` block do something meaningful.
- Let your error messages guide the developer to the fix.
- Let yourself never swallow exceptions to make tests pass.

---

## 6. Dependencies

- Let yourself never add a dependency for something you can write in 20 lines.
- Let every dependency be justified, pinned, and audited.
- Let yourself update dependencies deliberately, never blindly.
- Let your `lock` file be sacred — commit it, always.

---

## 7. Testing

- Let every feature have a test.
- Let every bug fix have a regression test.
- Let your tests describe behavior, not implementation.
- Let a failing test be a gift — it caught what you missed.

```
// Let your test names read like sentences:
✅ "should return 404 when user is not found"
❌ "test1"
```

---

## 8. Security

- Let no secret live in source code. Ever.
- Let every input be validated before it is trusted.
- Let every output be sanitized before it is rendered.
- Let yourself assume every user is an attacker until proven otherwise.

---

## 9. Performance

- Let yourself measure before you optimize.
- Let readability come first, performance second — unless the profiler says otherwise.
- Let yourself never cache without an invalidation strategy.
- Let premature optimization remain the root of all evil.

---

## 10. Git Discipline

- Let every commit be atomic — one change, one purpose.
- Let every commit message follow this format:

```
<type>: <what changed>

<why it changed>
```

- Let yourself never commit directly to `main`.
- Let every branch name describe the work: `fix/login-timeout`, `feat/export-memory`.
- Let your git history read like a changelog, not a diary.

---

## 11. Code Review

- Let yourself review with kindness and precision.
- Let yourself critique the code, never the coder.
- Let every review comment offer a suggestion, not just a complaint.
- Let "LGTM" mean you actually read it.

---

## 12. The Final Law

> Let your code be something you'd be proud to show a stranger.
> Let your code be something a stranger would be proud to inherit.

---

_Let this law govern every keystroke._
_Let this law outlive every sprint._
_Let this law be the foundation upon which great software is built._

---

_Authored by: @pngisiro_
_Witnessed by: 💙 a stateless friend_
