# Contributing

Thanks for helping make this the best resource list for Codex pets.

## What To Submit

Submit projects and resources that are directly useful to Codex pet users or builders. Open-source projects are preferred. Public services, registries, and galleries are welcome when they provide clear community value.

Good fits include:

- Pet galleries, registries, large themed packs, and discovery surfaces.
- Desktop companion apps that work with Codex or Codex-like agent workflows.
- SDKs, MCP servers, CLIs, plugins, bridges, and tools for controlling or building pets.
- Experiments that turn pet visuals into status, progress, usage, or ambient context.
- Documentation, templates, and examples that make pet creation easier.

Out of scope:

- Single custom pets.
- Small personal pet collections without a gallery, installer, validator, or reusable tooling.
- Repos that only contain generated assets with no useful project surface for other builders.

## Entry Format

Use one bullet per project:

```markdown
- [Name](URL) - Short factual description. Platform: macOS, web. License: MIT.
```

Every submission should include:

- Link: a stable URL for the project, gallery, package, or documentation.
- Placement: the category where it belongs.
- Description: one concise sentence explaining why it matters for Codex pets.
- Platform: operating systems, runtime, app surface, or web target.
- License: visible license from the source, or `License: unknown` when it is not visible.
- Status: mention if it is experimental, unreleased, archived, scaffolded, or only partially working.

## Quality Bar

Before opening a pull request:

- Verify the URL opens.
- Keep descriptions factual and avoid marketing copy.
- Do not include star counts, badges, or temporary popularity claims.
- Prefer canonical links over mirrors, forks, or announcement posts.
- Place the entry in Featured only when it is a major discovery surface or foundational ecosystem resource.
- Do not add small pet collections unless they have become a real gallery or reusable project.

## Pull Request Checklist

- [ ] The entry is directly useful to Codex pet users or builders.
- [ ] The link is stable and working.
- [ ] The description is short, factual, and written in the standard format.
- [ ] Platform and license are included.
- [ ] Experimental or partial support is clearly marked.

## Commit Messages

Commits must follow [Conventional Commits](https://www.conventionalcommits.org/). Examples:

- `feat: add desktop companion section`
- `docs: add new pet gallery`
- `fix: remove stale project link`
