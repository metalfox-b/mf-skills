# Metal Fox Skills

[Make It a 10](skills/make-it-a-10/SKILL.md) reviews a draft, design, plan, video, or code change in two passes. It scores the work against specific criteria and prioritizes fixes within your budget.

## Installation

Clone the repository:

```sh
git clone https://github.com/metalfox-b/mf-skills.git
cd mf-skills
```

### Codex

```sh
mkdir -p ~/.agents/skills
ln -s "$PWD/skills/make-it-a-10" ~/.agents/skills/
```

In a new Codex chat, use `$make-it-a-10` with the work you want reviewed.

### Claude Code

```sh
mkdir -p ~/.claude/skills
ln -s "$PWD/skills/make-it-a-10" ~/.claude/skills/
```

In a new Claude Code session, try `/make-it-a-10 Review README.md for a first-time contributor. I have 30 minutes to improve it.`

Keep the clone in place. Run `git pull` inside it to update the linked skill.
