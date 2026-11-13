# Proposed Game Entry Format

This is a **community submission proposal**, not a claim about the production site's private database schema or public API.

Each entry should be an independently verifiable game. Use the official playable URL when possible.

| Field | Type | Meaning |
| --- | --- | --- |
| `slug` | string | Lowercase hyphenated identifier |
| `name` | string | Official title |
| `url` | URL string | Direct playable or official landing URL |
| `category` | string | Best-fit game category |
| `summary` | string | Objective explanation of the core mechanic |
| `daily` | boolean | Whether the game has a daily challenge |
| `tags` | string[] | Optional discovery keywords |

Validate proposed entries using [schema/game.schema.json](../schema/game.schema.json) and see [examples/sample-game.json](../examples/sample-game.json).

This schema intentionally excludes creator emails, traffic figures, and other unnecessary personal or unverifiable information.
