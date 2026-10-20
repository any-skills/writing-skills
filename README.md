# writing-skills

A collection of Claude Code skills for technical writing and publishing.

## How to install a skill

Copy the skill directory into your Claude skills folder:

```bash
# macOS / Linux
cp -r <skill-name> ~/.claude/skills/

# Example
cp -r book-writing ~/.claude/skills/
```

After copying, the skill is immediately available in any Claude Code session — no restart needed.

## Available skills

### `book-writing`

技术书稿写作与出版规范。

Covers:
- Reader-facing prose only: no review notes, TODOs, internal discussion or implementation tracking in body text or code comments
- Forbidden vs. allowed examples
- Templates for rewriting review notes into neutral prose (rationale, alternatives, trade-offs)

**Trigger keywords:** 写书, 书稿, 写作, 出版, 写作规范, 清稿, 审稿笔记, 技术写作, book writing, manuscript, technical writing

**Usage:** mention any trigger keyword or type `/book-writing` in the prompt.

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
