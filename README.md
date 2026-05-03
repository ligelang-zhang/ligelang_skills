# ligelang_skills

Personal skill collection for [skills.sh](https://skills.sh) ecosystem — works with Hermes Agent, Claude Code, Codex CLI and more.

## Install

```bash
# Install all skills
npx skills add ligelang-zhang/ligelang_skills --skill '*'

# Or a specific one
npx skills add ligelang-zhang/ligelang_skills --skill codebase-deep-dive

# Target a specific agent
npx skills add ligelang-zhang/ligelang_skills --skill codebase-deep-dive --agent claude
```

## Skills

- **codebase-deep-dive** — Systematic deep-dive into a codebase: features, competitive analysis, algorithm principles, execution path tracing, and architecture analysis.

## Add a New Skill

1. Create `<skill-name>/SKILL.md` with skills.sh-compatible YAML frontmatter
2. Commit and push
3. Users run `npx skills add ligelang-zhang/ligelang_skills --skill <name>`
