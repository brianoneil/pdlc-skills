# PDLC Skills

A collection of skills for AI agents supporting the Product Development Lifecycle.

Each skill lives in `skills/<skill-name>/SKILL.md` and follows the NanoClaw skill format: YAML frontmatter with `name`, `description`, and `triggers`, followed by a Markdown body with instructions.

## Skills

| Skill | Description |
|-------|-------------|
| [user-stories](skills/user-stories/SKILL.md) | Write, review, split, and refine user stories following Mike Cohn's methodology from *User Stories Applied* |

## Usage

Skills are loaded by AI agents at runtime. Each skill file defines what triggers it and how the agent should behave when invoked.
