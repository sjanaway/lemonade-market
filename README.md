# The Lemonade Market

An interactive guide for children (about 8–12) to why some things cost more than others: supply, demand, and how a mixed economy like the UK's works. Told through a homemade lemonade stall.

Everything is in one file, `site/index.html`. There's no build step and no data to update.

## View it locally

```bash
open site/index.html
```

## Put it online

Any static host works. The easiest options:

- **Netlify Drop:** drag the `site` folder onto https://app.netlify.com/drop.
- **GitHub Pages:** push this folder to a public repository and deploy the `site` folder with a Pages workflow (`actions/upload-pages-artifact` with `path: site`, then `actions/deploy-pages`), as in the petrol-price-puzzle repository.

`index.html` in the project root is the claude.ai artifact version. The website is the one in `site/`, with UK-specific examples.
