# mindfulrepetitions.space

Marketing, privacy and support pages for **Mindful Repetitions**, published with GitHub
Pages at <https://mindfulrepetitions.space>.

Static HTML with one stylesheet. No build step, no dependencies — edit and push.

| Path       | Serves                              | Used by                              |
|------------|-------------------------------------|--------------------------------------|
| `/`        | Landing page                        | App Store "Marketing URL" (optional) |
| `/privacy/`| Privacy policy                      | App Store "Privacy Policy URL" (required) and `LegalLinks.privacyPolicy` in the app |
| `/support/`| Support page and FAQ                | App Store "Support URL" (required)   |
| `/terms/`  | Terms of use (Apple's standard EULA)| Purchase screen "Terms of Use" link  |

The privacy policy is the published copy of `PRIVACY.md` in the app repository. Change one,
change the other — the app links here, so a drift between them is a drift a customer sees.

`CNAME` holds the custom domain and must not be deleted; GitHub Pages rewrites it when the
domain is changed in repository settings.

© Zen Abbondanza LLC
