# HOPEFUL! Upstander pledge photo maker

One web page. People take a selfie (or pick a photo), type their pledge, and the page puts the HOPEFUL! Upstander sign in their hands. The image is made on their phone; nothing is uploaded. The logo is loaded from the Hopeful website (Squarespace CDN), with logo.webp as a fallback.

- Live: https://hopeful-pledge-photo.vercel.app/ (Vercel, IT Yogi account, deployed from this repo by hand)
- On the Hopeful website: shown in an iframe on the Take the Pledge page (`?embed=1` hides the page's own heading)
- Sign style: `DEFAULT_STYLE` in index.html. `'colour'` = stronger logo colours, `'classic'` = faint tree like the printed sign. Preview either with `?sign=classic` or `?sign=colour`.

Hosted by IT Yogi Network Solutions for now; to move to a HOPEFUL! account later.
