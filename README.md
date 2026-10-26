# Nationality Test by Face web

Static landing and legal pages for the Android app `com.cukkacreatives.skinscanner`.
The prepared store-listing name is **Nationality Test by Face**. The current Android app
still displays **VibeCheck**, and subscriptions may display **VibeCheck Pro**.
The pages explain these names so users can identify the same app.

- `index.html`: product landing page
- `privacy-policy.html`: privacy and data-deletion information
- `terms-of-use.html`: terms of use
- `styles.css`: shared responsive design
- `logo.png`: app artwork
- `app-ads.txt`: advertising verification

Contact and data-deletion requests: `cukkacreatives@gmail.com`.

All pages share `styles.css` and relative links, so this folder can be served
at the domain root or a subdirectory. Preview locally with
`python -m http.server 8000 --directory assets/web` from the repository root.

The privacy text reflects photo deletion after processing, as confirmed by
the developer. No model-training or provider-specific retention claims are made.
The advertising publisher ID matches the app's AdMob application ID.
For advertising verification, publish `app-ads.txt` at the root of the developer
website's hostname, even when the HTML pages are hosted in a subdirectory.
For example, a developer website at `https://durdenk.github.io/vibecheck-web/`
requires `https://durdenk.github.io/app-ads.txt` (or a redirect from that URL).
See [Google's app-ads.txt setup guide](https://support.google.com/admob/answer/9363762?hl=en).

Editing this folder does not publish the site. The project's documented publication URLs are
`https://durdenk.github.io/vibecheck-web/privacy-policy.html` and
`https://durdenk.github.io/vibecheck-web/terms-of-use.html`; deploy these files
to that hosting location when publishing an update.
