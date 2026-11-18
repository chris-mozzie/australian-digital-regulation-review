# Australian Digital Regulation Review

Independent public-interest Astro site designed for Cloudflare Workers.

## Important branding note
The visual language is inspired by the clarity and institutional restraint of Australian Government sites, but this is **not an Australian Government website**. The Commonwealth Coat of Arms has deliberately not been included. PM&C states that the Arms signify Commonwealth authority and ownership and that unauthorised third-party use may breach Australian law. Obtain written permission from PM&C before adding it.

## Local
```bash
npm install
npm run dev
```

## Cloudflare Workers
1. Create a GitHub repository and push this directory.
2. Cloudflare Dashboard → Workers & Pages → Create → Import a repository.
3. Framework: Astro. Build command: `npm run build`.
4. Deploy command can be `npx wrangler deploy` where required by your Workers build configuration.
5. Change `site` in `astro.config.mjs` to your final hostname.

CLI alternative:
```bash
npm install
npx wrangler login
npm run build
npx wrangler deploy
```

## Editorial rule
Keep fact, interpretation and recommendation visibly distinct. The source list deliberately prioritises Parliament, eSafety, OAIC and PM&C primary materials.
