# stellar-notes-cli

A tiny, dependency-free CLI for managing markdown notes with tags and simple full-text search.

## Install / Run

This is a pure-Python project.

```bash
python -m stellar_notes_cli init
python -m stellar_notes_cli add "First Note" --tag ideas --body "Hello, world."
python -m stellar_notes_cli list
python -m stellar_notes_cli search hello
```

## Repo location

By default it stores your notes in:

- `./.stellar-notes/` (relative to the current working directory)

Override with:

- `--home /path/to/repo`
- or `STELLAR_NOTES_HOME=/path/to/repo`
