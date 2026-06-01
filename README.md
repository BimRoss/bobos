# bobos

One-page lander for **bobos** — a burger joint coming to LA where the salsa goes on the burger.

Live: <https://bobos.makeacompany.ai>

## Layout

- `index.html` — the whole site. Single file, no framework. Google Fonts (Fraunces / Inter / JetBrains Mono).

## Local preview

```sh
open index.html
```

## Deploy

Deployed to Cloudflare Pages project `bobos-makeacompany-ai`. To push a new version:

```sh
npx wrangler@latest pages deploy . --project-name=bobos-makeacompany-ai --branch=main
```

## Posture

It's a napkin. Public on purpose. The scouting board, the build log, and the salsa
opinions are real; the menu and the location are still cooking.
