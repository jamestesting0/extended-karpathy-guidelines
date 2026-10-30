# Extended Karpathy Guidelines

An extended version of the [Karpathy guidelines](https://x.com/karpathy/status/2015883857489522876) skill for coding
agents, with good coding habits I picked up from my own projects.

The idea is a simple, short skill for day-to-day coding conventions: it helps the agent decide whether a guard,
`try/except`, abstraction, or test should exist at all, instead of adding them by default.

On top of the original four principles (think before coding, simplicity first, surgical changes, goal-driven
execution), it adds:

- **Readability:** clear names, comments that explain why, flat control flow, plain over clever.
- **Guards and error handling:** validate once at trust boundaries, no guards without a named input and harm, no silent
  fallbacks.
- **Tests that earn their place:** every test names the bug it catches; no tests that just restate the code.
- **A short pre-finish checklist.**

## Install

Copy `SKILL.md` into your agent's skills directory, for example:

```bash
git clone https://github.com/jamestesting0/extended-karpathy-guidelines ~/.agents/skills/karpathy-guidelines
```

## License

MIT
