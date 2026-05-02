# Builder Graph Templates

Shared Builder Graph templates live in this directory as package folders.

Each package contains:

- `package.toml` for metadata, aliases, tags, target, and versioning.
- `graph.buildergraph` for the Builder Graph script.

The root `index.json` lists published Builder Graph packages. Eldiron reads that index from GitHub when the Builder dock Treasury tab is opened.
