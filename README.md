# Wendy Bottomley for Plymouth City Council

A single-page campaign website. Everything is in `index.html`; the headshot is in `images/`.

## Putting the site online (GitHub Pages, free)

1. On GitHub, open this repository and click **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose the branch that holds `index.html` and the `/ (root)` folder, then **Save**.
4. After a minute or two the page shows the site's address.

The site uses the custom domain **wendyforplymouth.com** (set by the `CNAME` file).
The domain was bought with Google Workspace and its DNS is managed at Squarespace Domains.
DNS records there: four `A` records on `@` pointing at GitHub Pages
(185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a `CNAME`
on `www` pointing at `naudslee.github.io`. Do not touch the `MX` records; they carry email.

## Contact form

The form sends messages through [Formspree](https://formspree.io) (form ID `xljggbyv`) to
wendy@wendyforplymouth.com. Reply to messages from that inbox. The free plan allows
50 messages a month.

To change which address receives messages, or to see past submissions, sign in at formspree.io.
