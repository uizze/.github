# UIZZE

> **Stop AI coding agents from shipping generic UI.**

UIZZE gives coding agents compact local UI workflows plus optional focused
references from 800,000+ real web and iOS screens.

## Install a free skill

Use `ui-design` for broad design and implementation work:

```bash
npx skills add https://uizze.com --skill ui-design
```

Use `anti-ui-slop` for a focused generic-UI finish gate:

```bash
npx skills add https://uizze.com --skill anti-ui-slop
```

Production publishes `anti-ui-slop`, `ui-design`, and `ui-radar`. They work
without an account, token, script, or MCP connection.

## Connect the paid MCP

The authenticated MCP at `https://uizze.com/mcp` exposes two tools:

- `find_ui_references` for a few focused full-screen references.
- `find_ui_materials` for hosted fonts, icons, animated icons, or explicitly
  requested packs.

Empty retrieval is an intentional no-op. See the [setup documentation](https://uizze.com/docs).

## GitHub Action

```yaml
- uses: uizze/uizze@v1
```

The action performs a conservative source check on the GitHub runner and does
not upload source.

## Links

- [Product](https://uizze.com)
- [Public repository](https://github.com/uizze/uizze)
- [Agent Skills index](https://uizze.com/.well-known/agent-skills/index.json)
- [MCP manifest](https://uizze.com/.well-known/mcp.json)
- [Privacy](https://uizze.com/privacy)
- [Terms](https://uizze.com/terms)
