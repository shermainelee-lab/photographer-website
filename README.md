# Alice Huang Photography

One-page portfolio site for a wedding and portrait photographer. Plain HTML and CSS with a few lines of JavaScript. There is no build step and no dependencies.

## Files

- `index.html` is the whole site.
- `wedding-1.png` is the first portfolio image. The other five tiles are placeholders.
- `vercel.json` holds the Vercel settings (clean URLs, security headers, image caching).

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
npx serve .
```

## Deploy to Vercel

1. Sign in at vercel.com and choose **Add New > Project**.
2. Import this GitHub repository.
3. Leave the framework preset as **Other**. Leave the build command and output directory empty.
4. Select **Deploy**.

Every push to `main` then redeploys the site automatically. With the CLI: `npx vercel --prod`.

## Replace the placeholders

- Name, about text, photo captions and the email address (`hello@alicehuang.com`) in `index.html`.
- Photos: put each image in this folder and swap the matching `<span>Photo goes here</span>` tile for an `<img>` like the first one.
