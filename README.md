# @officeos/skill-obsidian

Obsidian integration skill for [Office OS](https://github.com/officeos-co) — manage an Obsidian vault backed by CouchDB (Self-hosted LiveSync).

## Install

```bash
eaos skill install obsidian
```

Or from the Office OS dashboard under **Skills > Install**.

## Actions

- `search` — Search notes in the vault
- `read_note` — Read a note's content
- `create_note` — Create a new note
- `update_note` — Update an existing note
- `list_folder` — List files in a vault folder

## Credentials

- **Vault URL** — Your CouchDB endpoint
- **Username** and **Password** — CouchDB credentials

## Development

```bash
npm install
# Skill is defined in skill.ts using @officeos/skill-sdk
```

## License

MIT
