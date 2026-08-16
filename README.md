# emad-ii/site

Public home for Emad Mostaque. Source for Cloudflare Pages.

This site sits beside [ii.inc](https://ii.inc). It does not replace it.

## Do not

- Do not enable GitHub Pages on this repo.
- Do not touch `emad-ii.github.io`.
- Do not add Vercel or Netlify.
- Do not invent biography.

## Attach Cloudflare Pages

1. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git.
2. GitHub repository: `emad-ii/site`.
3. Framework preset: **None**.
4. Build command: empty.
5. Output directory: `/` (repo root).
6. Production branch: `main`.
7. Deploy. Preview URL is enough until a domain is named.

ii.inc already uses Cloudflare DNS. A custom domain later is a DNS record, not a second host.

Workers are not required for v1.
