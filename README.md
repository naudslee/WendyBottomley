# Wendy Bottomley for Plymouth City Council

A single-page campaign website. Everything is in `index.html`; the headshot is in `images/`.

## Putting the site online (GitHub Pages, free)

1. On GitHub, open this repository and click **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose the branch that holds `index.html` and the `/ (root)` folder, then **Save**.
4. After a minute or two the page shows the site's address, something like
   `https://naudslee.github.io/WendyBottomley/`.

## Turning on the contact form (Formspree, free)

The form in `index.html` sends messages to [Formspree](https://formspree.io), which emails
them to you. Replies go out from your own email, so nothing automated is sent to voters.

1. Create a free Formspree account using the campaign email address.
2. Click **New form**, name it (for example "Website questions") and confirm the email
   that should receive messages.
3. Formspree shows a form address like `https://formspree.io/f/abcdwxyz`.
   In `index.html`, replace `YOUR_FORM_ID` with the part after `/f/`.
4. Submit a test message from the live site and check that it arrives.

The free plan allows 50 messages a month, which is plenty for a local race.

## Showing the campaign email on the site

In `index.html`, find the comment that begins `Once the campaign email is set up`.
Remove the comment markers and replace both copies of `EMAIL@EXAMPLE.COM` with the real address.
