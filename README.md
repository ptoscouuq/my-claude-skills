# my-claude-skills

Reusable agent skills: review, commit, refactor, test

## Examples

```bash
# skills trigger automatically on matching tasks
# or invoke directly: /code-review
```

## Highlights

- Each skill is a folder with a single SKILL.md
- YAML frontmatter: name + when-to-use description
- Drop-in compatible with ~/.claude/skills
- Concrete instructions, output formats and examples
- Versioned like code: review changes in PRs

## Installation

```bash
git clone <this repo>
cp -r skills/* ~/.claude/skills/
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   └── roadmap.md
├── skills/
│   ├── code-review/
│   │   └── SKILL.md
│   ├── commit-message/
│   │   └── SKILL.md
│   ├── refactor-plan/
│   │   └── SKILL.md
│   └── test-writer/
│       └── SKILL.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
└── SECURITY.md
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas

## License

MIT. Do whatever you want.
