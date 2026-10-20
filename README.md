# writing-skills

A collection of Claude Code skills for technical writing and publishing.

## How to install a skill

Copy the skill directory into your Claude skills folder:

```bash
# macOS / Linux
cp -r <skill-name> ~/.claude/skills/

# Example
cp -r technical-book-writing ~/.claude/skills/
```

After copying, the skill is immediately available in any Claude Code session — no restart needed.

## Available skills

### `technical-book-writing`

撰写与重构技术书籍指南（目录、正文、出版规范）。

Covers:
- TOC as navigation: neutral naming, abbreviation control, heading hierarchy
- Prose techniques: metaphors, "why not" motivation, code breathing, golden path, guardrails
- Discipline rules: diction density, meta-narration, punctuation, emphasis, no review notes in manuscript
- Publisher manuscript standards (numbering, terminology, punctuation, figures/tables, references)
- Whole-book structure governance and heading rules
- Self-check checklist before submission

**Trigger keywords:** 写技术书籍, 书稿, 目录, TOC, 写作, 出版, 审稿, technical book, manuscript

**Usage:** mention any trigger keyword or type `/technical-book-writing` in the prompt.

---

## Contributing

1. Create a directory named after your skill
2. Add a `SKILL.md` with the required frontmatter:

```markdown
---
name: your-skill-name
description: one-line description used for trigger matching
---

# Skill content here
```

3. Submit a PR.
