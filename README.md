# My talk

A [slideit](https://github.com/geraldserafin/md-slides) presentation. Every push to `main` builds it and publishes it with GitHub Pages.

## Set up (once)

1. **Use this template** → create your repository.
2. In the new repository: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. Push (or run the *Pages* workflow). Your talk is at `https://<you>.github.io/<repository>/`, and the PDF at `…/talk.pdf`.

## Edit

The slides are the `.slide` files in `talk/`, one file per slide, played in file-name order.

```sh
npm i -g @geraldserafin/slideit
slides dev talk      # live preview in the browser
slides check talk    # find mistakes
```

Editor support: [VS Code / VSCodium](https://github.com/geraldserafin/md-slides/tree/main/editors/vscode),
[Vim / Neovim](https://github.com/geraldserafin/md-slides/tree/main/editors/vim). Syntax reference:
<https://github.com/geraldserafin/md-slides#writing-slides>.
