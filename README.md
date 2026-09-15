# Coto Retreat Website

Static website for Cheerful Coto Retreat, ready to deploy with Cloudflare Pages.

## Project files

- `dist/index.html` — complete website, styling, and motion
- `dist/assets/` — locally hosted property images

## Publish with GitHub and Cloudflare Pages

1. Create a new GitHub repository named `coto-retreat`.
2. Unzip this package and upload `README.md` and the entire `dist` folder to the repository.
3. In Cloudflare, open **Workers & Pages**.
4. Select **Create application** → **Pages** → **Connect to Git**.
5. Choose the `coto-retreat` repository.
6. Use these deployment settings:
   - Framework preset: `None`
   - Build command: leave blank
   - Build output directory: `dist`
7. Deploy the site.
8. Open the new Pages project, select **Custom domains**, and add the domain you purchased.

Cloudflare will automatically update the website whenever a new change is pushed to the GitHub repository.

## Houfy booking link

The booking form and button space are already included. Add the final Houfy listing URL before promoting the site so the booking button can send guests to the live listing.
