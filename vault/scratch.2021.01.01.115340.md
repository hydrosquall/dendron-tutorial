---
id: ea35a237-1632-47a6-a0c4-40992d09ab3a
title: '115340'
desc: ''
updated: 1609530259740
created: 1609520022466
---

For notes that don't have a home yet. These can/should be cleared periodically.

E.g. excalidraw blog post

- Open source
- [ ]  Test me!

### New tabs

- [Export web page to markdown](https://chrome.google.com/webstore/detail/markdownload-markdown-web/pcmpcfapbekmbjjkdalcgopdkipoggdi?hl=en-GB)

### Commands for publishing v2 with yarn

Original docs: https://dendron.so/notes/861e4e48-dcc5-4813-a695-8940ba6e64d3.html

Everything seems to port over to `yarn` without problems 🎉

```bash
# build locally
yarn run  dendron-cli buildSiteV2 --wsRoot . --stage dev --serve
```

```bash
# built folder folder to serve on github pages See dendron ym
yarn run dendron-cli buildSiteV2 --wsRoot .  --stage prod
```
