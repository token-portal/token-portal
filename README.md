<p align="center"><img src="logo/tp-color.png" width="96" alt="" /></p>

# Token Portal

Turn your Figma variables, text styles and shadows into SCSS, CSS custom properties, DTCG JSON
or a Tailwind v4 theme. Publish to your GitHub or GitLab repository in one click, and bring
value changes from code back into Figma.

The files in your repository are the finished ones — ready to `@use`, import or link. No Style
Dictionary, no transform pipeline, no build step.

**[Install on Figma Community](https://www.figma.com/community/plugin/1676193421771513434/token-portal)** — free.

## See it live

Every publish writes a `showcase.html` built from your own tokens — components, type scale,
palette — and a `preview.html` reference. Deployed straight from a published repository:

- **Showcase:** https://token-portal.github.io/design-system-demo/tokens/showcase.html
- **Token reference:** https://token-portal.github.io/design-system-demo/tokens/preview.html

## How it works

1. **Get started** — the plugin reads your variables and styles. Nothing leaves the file.
2. **Download ZIP** — every format at once, plus a self-contained preview page.
3. **Connect a repository** — GitHub or GitLab, one form, one token.
4. **Publish** — the files land in your repository with a commit message that says exactly
   what changed. Publish as a commit to main, or as a pull request for someone to review.
5. **The way back** — edit a value in `tokens.css`, press *Check again* in the plugin, and
   apply the change into your Figma variables. One ⌘Z undoes it.

Your design system stays private. The plugin talks only to the git host you connect, and only
to the repository you name.

## How it's built

Token Portal is developed with Claude (Fable 5, Anthropic) — the code is written by the model,
directed and reviewed by its author. That method is why the discipline is unusually visible:
every claim about an external API is verified against its documentation, every release is tested
against two deliberately unlike design systems and walked end-to-end before shipping, and every
found defect becomes a test before it becomes a fix. The plugin is in active development;
[reports](https://github.com/token-portal/token-portal/issues) are the fastest way to make it
better.

## Privacy

Data is transmitted only to the repository configured by the user, and only on explicit action.
No accounts, no analytics, no first-party servers. Full statement: [PRIVACY.md](PRIVACY.md).

## Support

Something broken, or missing? **[Open an issue](https://github.com/token-portal/token-portal/issues/new/choose)** —
bug reports and feature requests each have a short template. Questions are welcome as issues too.
