# aidd-template-lean

Minimal **AI-driven development** template: rulesync, GitHub Issues workflow, and `docs/` as SSOT.

No application code is included. Add your stack after adoption.

## Use this template

1. Click **Use this template** on GitHub to create your repository.
2. Clone your new repository.
3. Complete the [adoption checklist](#adoption-checklist).

## What is included

| Area | Contents |
|------|----------|
| AI settings | `.rulesync/` → `rulesync generate` → Claude / Cursor / Codex |
| Workflow | `/start-ticket`, `/close-ticket`, `/address-pr-feedback`, `/spec-lookup` |
| Docs | `docs/` skeleton with SSOT inventory |
| CI | `check_rulesync` workflow |

## Adoption checklist

- [ ] Replace `PROJECT_NAME` placeholders in docs and README
- [ ] Create labels: `gh label create in-progress --color FFAA00 --description "Work in progress"`
- [ ] Enable GitHub Actions if disabled
- [ ] Install tools: `gh`, `rulesync@8.17.0`, Node 22+
- [ ] Run `rulesync generate` after editing `.rulesync/`
- [ ] Add application code and update `docs/_inventory.md` SSOT table

## Skills

See [docs/development/ticket-driven-setup.md](./docs/development/ticket-driven-setup.md).

## Related template

**aidd-template-scale** ([kyto64/aidd-template-scale](https://github.com/kyto64/aidd-template-scale)) adds VitePress docs site, UI/E2E skills, lefthook, and Dependabot — still without application code.

## License

MIT — see [LICENSE](./LICENSE).
