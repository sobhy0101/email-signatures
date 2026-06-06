# email-signatures

Self-hosted Gmail signature assets deployed on Vercel.

## Structure

```
public/
  index.html        ← Signature preview + raw HTML to copy into Gmail
  photo.jpg         ← Profile photo (replace with your own)
  icons/
    gmail.png
    whatsapp.png
    facebook.png
    x.png
    linkedin.png
    instagram.png
    youtube.png
    tiktok.png
```

## Icons

Place 24×24px PNG icons inside `public/icons/`. Brand-color flat icons recommended.
Free sources: [Icons8](https://icons8.com), [Flaticon](https://flaticon.com), [SimpleIcons](https://simpleicons.org).

## Deployment

1. Push to GitHub
2. Import repo in [vercel.com](https://vercel.com) → assign custom domain or use the generated `.vercel.app` URL
3. Update icon `src` URLs in `public/index.html` to match your Vercel domain
4. Paste the signature HTML into Gmail → Settings → Signature

## Photo

Drop your profile photo as `public/photo.jpg` (recommended: 160×160px, JPEG).
