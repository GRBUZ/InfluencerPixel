# Influencer Pixel Homepage (Netlify-ready)

Static single page app with a 100x100 grid (1,000,000 pixels). Netlify Forms collects buyer data; payment redirects to PayPal.Me.

## Deploy
- Push to GitHub and import the repo on Netlify.
- Build command: _empty_
- Publish directory: `/`

## Configure
- In `js/app.js`, set your PayPal.Me link in `paymentUrl`.
- Update copyright in `index.html`.
- For file uploads, you may later add a serverless function or Cloudinary/S3 to store images and write their URLs to `data/purchasedBlocks.json`.
