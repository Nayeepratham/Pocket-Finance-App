# Apps website

Home pages and privacy policies for my Android apps, published with GitHub Pages
from the `docs/` folder at **https://nayeepratham.github.io/**.

| App | Home page | Privacy policy |
|---|---|---|
| Coinlet | https://nayeepratham.github.io/coinlet/ | https://nayeepratham.github.io/coinlet/privacy-policy.html |

## Layout

```
docs/
├─ index.html              apps home page (one block per app)
├─ coinlet/                Coinlet's home page and privacy policy
└─ _new-app-template/      starting point for the next app (not published: folders
                           starting with "_" are skipped by GitHub Pages)
```

## Add a new app

1. Copy `docs/_new-app-template/` to `docs/<app-name>/` (lowercase, hyphens, no spaces).
2. In both files, replace `APP NAME` and `DATE`, and delete the TEMPLATE comment.
3. **Rewrite the privacy policy** so it matches what the new app really does with data.
   The template describes Coinlet: offline, no data collected.
4. Add a block for the app in `docs/index.html`.
5. Commit and push. The pages go live in a minute or two at
   `https://nayeepratham.github.io/<app-name>/privacy-policy.html`.
