> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is the documentation site for [Planasonix](https://planasonix.com), an enterprise ETL/ELT platform
- Hosted at docs.planasonix.com via [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "Planasonix" not "Planalytix" (legacy name)
- Use "pipeline" not "workflow" or "job"
- Use "node" not "step" or "stage" when referring to pipeline components
- Use "connection" not "connector" when referring to a configured data source/destination
- Use "connector" when referring to the connector type/template in the gallery
- Use "sync" not "job" when referring to reverse ETL operations
- Use "organization" not "workspace" or "tenant"
- Use "project" not "folder" for top-level pipeline grouping
- Tier names: Starter, Professional, Premium, Enterprise

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use Mintlify callout components: `<Note>`, `<Tip>`, `<Info>`, `<Warning>` where appropriate
- Use `<Steps>` for procedural instructions
- Use `<Tabs>` for alternative approaches or platform-specific instructions
- Use `<CardGroup>` or `<Columns>` for navigation cards

## Content boundaries

- Document all user-facing features of the Planasonix platform
- Do not document internal admin portal features
- Do not document OneLink-specific driver management features (separate product)
- Mark enterprise-only features with an `<Info>` callout stating tier requirement
- Mark premium features similarly
- Do not expose internal API endpoints or implementation details
