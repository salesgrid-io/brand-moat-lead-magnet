# The Brand MOAT (AGENTS.md)

Urban Unity free resource by Marshall Crews: the unfair advantage a brand already has, and how to turn it into protection no competitor can copy. Linked as resource 07 on https://marshallcrewslinks.com/#resources.

- Live: https://brand-moat.urbanunity.io
- GitHub: salesgrid-io/brand-moat-lead-magnet (branch **`master`**, not main)
- Vercel: team `info-sales-grid`, project `brand-moat-lead-magnet` (git-connected through the Vercel GitHub app)
- Server copy: /root/lead-magnets/brand-moat-lead-magnet

## Files

- `index.html`: the whole page (Syne + DM Mono, white cards on dark, amber gold). The ending CTA block goes to https://urbanunity.io/apply.

## How to make and push an update

1. Confirm the exact change with Joey. Don't guess.
2. `cd /root/lead-magnets/brand-moat-lead-magnet && git pull`
3. Edit `index.html`.
4. `git add -A && git commit -m "<what changed>" && git push` (pushes `master`)
5. Vercel deploys `master` automatically (~1 min). Check the live URL shows the change before telling Joey it's live.

Static page on Vercel. NOT PM2: never `pm2 restart` it.
