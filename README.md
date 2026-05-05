# res-projects

Project metadata for [resweb2.0](https://github.com/Austin-TB/resweb2.0): all projects live in `projects/projects.jsonl` (one JSON object per line).

Example line:

```json
{"title":"My Project","description":"Short description.","github_link":"https://github.com/you/repo","deployed_link":"https://example.com"}
```

Optional fields: `github_link`, `deployed_link`.

Archived or skipped entries can stay under `projects/skipped/` as separate JSON files (not loaded by the site).
