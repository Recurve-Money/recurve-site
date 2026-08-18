# Recurve

Capital infrastructure for autonomous funds.

## Stack

Static HTML + one CSS file. No build step, no framework, no bundler.
Deploy: `vercel --prod` from this folder.

## Files

```
index.html       landing
product.html     how it works
token.html       $ARC economics
watchers.html   watcher network
app.html         dashboard
privacy.html     stub
terms.html       stub
style.css        all styling, one file
img/             painterly illustrations
logos/           chain logos
icon.svg         favicon
skill.md         agent skill stub
skill-watcher.md watcher skill stub
vercel.json      cleanUrls
```

## Brand

Name: Recurve
Token: $ARC
Palette: canvas #FFFFFF, shade #F1F0EB, ink #0A0A0A, mint #2EE6A8
Font: Figtree
Logo: three-feather fletching mark

Source of truth: `logo.svg` (viewBox 0 0 612 759, fill=currentColor).
Inlined in every page header and footer so it inherits text colour.
Export variants in `brand/`: black, white, mint - SVG + 1024px PNG.
`icon.svg` is the mint mark on a dark rounded square; favicon.ico and
apple-icon.png are generated from it.

## Editing

All styling lives in style.css. Change a token there and it propagates.
Header and footer are inlined per page, so edit all five if you change nav.

## Placeholders to replace before launch

- Contract address on token.html (`0xArc...c0de`)
- Social links (x.com/recurveprotocol, discord.gg/recurve)
- docs.recurvemoney.xyz and github.com/recurveprotocol
- Fund names, TVL, P&L numbers on product.html and app.html
- privacy.html and terms.html copy
- skill.md and skill-watcher.md are stubs

## Deploy

```powershell
cd "D:\1проекты\recurve"; vercel --prod
```
