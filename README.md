# pptx-from-layouts (placeholder)

The full, usable copy of this skill lives here:

**https://github.com/Ryen-Xie/pptx-from-layouts-skill**

A Claude Code skill that generates PowerPoint decks from a markdown outline by
reading your own `.pptx` template's **slide master layouts** and filling real
placeholders, instead of duplicating decorative slides and overlaying text boxes.
- Upstream: https://github.com/tristan-mcinnis/pptx-from-layouts-skill (MIT, by Tristan McInnis)

Install:

```bash
git clone https://github.com/Ryen-Xie/pptx-from-layouts-skill.git
mkdir -p ~/.claude/skills ~/.claude/agents
cp -r pptx-from-layouts-skill/.claude/skills/pptx-from-layouts ~/.claude/skills/
cp pptx-from-layouts-skill/.claude/agents/*.md ~/.claude/agents/
pip install python-pptx pydantic
```

This repository can be deleted - it only exists as a pointer.
