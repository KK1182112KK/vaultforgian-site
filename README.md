# VaultForgian Demo Site

Public demo site for [VaultForgian](https://github.com/KK1182112KK/vaultforgian), a desktop Obsidian plugin that brings Codex into study notes with reviewable note patches, learning-mode coaching, quizzes, and study panels.

- **Live site:** <https://vaultforgian-site.vercel.app>
- **Plugin repo:** <https://github.com/KK1182112KK/vaultforgian>
- **Stack:** Vite, React, Remotion Player, Vercel

## Development

```bash
npm install
npm run dev
npm run build
npm run preview
```

The Vercel project builds this repo with `npm run build` and serves the generated `dist/` directory. Do not commit `dist/`; it is generated during deployment.

## Demo Media

Committed public media lives under `public/`. The main demo player uses:

```text
public/demo/obsidian-noteforge-demo.web.mp4
```

The raw source capture is intentionally local-only and ignored:

```text
public/demo/obsidian-noteforge-demo.mp4
```

Keep large raw recordings out of GitHub. Re-encode them to a web-sized `.web.mp4` before publishing.

## Deployment

The site is linked to Vercel as `vaultforgian-site`. Production deploys are available at:

```text
https://vaultforgian-site.vercel.app
```

For manual deploy:

```bash
vercel deploy --prod
```

## License

MIT. See [LICENSE](./LICENSE).
