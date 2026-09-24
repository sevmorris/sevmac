# sevmac

A hand-written guide to how my Macs are set up and run, published at
**[sevmorris.github.io/sevmac](https://sevmorris.github.io/sevmac/)**.

- **[SMAC-1 — Personal Mac Management Guide](https://sevmorris.github.io/sevmac/)**
  (`docs/index.html`) is the full reference: new-machine setup, the Brewfile and
  preferences workflows, the migration checklist, and troubleshooting. It also
  covers Barkeep and Magic Backup Machine.
- **[SMAC-2 — My Daily Mac Operations](https://sevmorris.github.io/sevmac/daily.html)**
  (`docs/daily.html`) is the day-to-day command card.

Both pages document [mrk](https://github.com/sevmorris/mrk), the scripts and
dotfiles that do the setup. They are kept in step with mrk by hand, not
generated from it, so an mrk change that touches a command, a Make target, an
install phase or what moves between machines needs an edit here too. mrk's
`CLAUDE.md` has the table of which change needs which section. Command flags
are the exception: they live in mrk's
[BIN-1](https://sevmorris.github.io/mrk/bin/mrk-usage.html), which SMAC-1 links
into, and are not repeated here.

## Editing

Plain HTML with `.nojekyll`: no build step, and no Jekyll. Open
`docs/index.html` in a browser to preview. Pushing to `main` publishes in under
a minute.

## Licence

MIT. See [LICENSE](LICENSE).
