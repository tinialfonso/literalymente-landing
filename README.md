# Literalymente

Responsive landing page redesign for Literalymente, based on its existing educational content, logo, and brand colors.

## Preview locally

No build step or dependencies are required. From the repository directory, run:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000.

## Files

- `dist/index.html` — page, responsive styling, and navigation.
- `dist/assets/logo.webp` — supplied brand artwork.
- `.openai/hosting.json` — existing Sites deployment configuration.

The page uses Google Fonts. Contact buttons open an email draft; platform and tools links lead to the existing Squarespace website.

## Hosted proposal

https://literalymente-nueva-mirada.tini-alfo.chatgpt.site

The hosted proposal requires the owner's ChatGPT sign-in.

## Shared preview

https://tinialfonso.github.io/literalymente-landing/

GitHub Pages automatically publishes `dist/` whenever changes reach `main`.
To collaborate, create a branch and open a pull request. Merging the pull request
updates the shared preview. Publication progress appears in the Actions tab.
