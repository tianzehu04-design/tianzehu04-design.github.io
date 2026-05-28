# Tianze Hu Research Portfolio

Static version of `www.tianzehu.com`, prepared for free hosting on GitHub Pages or Cloudflare Pages.

The clean deployable site is in `dist/`. The `source/` folder is only a migration archive from Squarespace and does not need to be uploaded.

## Deploy on GitHub Pages

1. Create a public GitHub repository.
2. Upload everything inside `dist/` to the repository root.
3. In the repository, open Settings -> Pages.
4. Set the source to the `main` branch and root folder.
5. Keep the included `CNAME` file if the custom domain should be `www.tianzehu.com`.

## DNS

At the domain registrar, point `www.tianzehu.com` to the GitHub Pages hostname with a CNAME record:

```text
www  CNAME  your-github-username.github.io
```

After the new site works, cancel only the Squarespace website subscription. Keep the domain registration active.
