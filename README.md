# 79watch.ph — Watch Showcase

A free, mobile-first, single-page watch catalogue built with plain HTML, CSS and JavaScript. No database, paid hosting, or build tools required.

## Preview locally
Open `index.html` in a browser.

## Update your watches
Edit `index.html` and find `const watches = [ ... ]`. Each watch is one object. Replace the sample entries with your real listings.

```js
{
  name: "Seamaster", brand: "Omega", model: "Ref. 1234",
  price: 85000, currency: "PHP",
  condition: "Very good", size: "41 mm", movement: "Automatic",
  strap: "Stainless steel", boxPapers: "Box only", warranty: "Seller warranty",
  status: "Available",
  photos: ["assets/seamaster-front.jpg", "assets/seamaster-back.jpg"]
}
```
- Set `price` as a number (e.g. `85000`).
- Status must be `Available`, `Reserved`, or `Sold`.
- Upload photos into `assets/` and use exact filenames in the `photos` list.
- WhatsApp is connected to +63 917 154 6894. Change `WHATSAPP_NUMBER` if needed (country code, no plus or spaces).

## Publish with GitHub Pages
1. In this repository, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then click **Save**.
4. After GitHub finishes deploying, the site should be available at:
   https://jtwoubaldo31-oss.github.io/79watch-ph/

The repository is public, so visitors can view/download the source. Only you and collaborators you approve can edit this repository.

## Before sharing
Replace all sample watch names, prices, specifications, and placeholder illustrations with your actual inventory and real watch photos. Check every listing and status before posting the public link.
