# Good Conscience

Marketing site for the Good Conscience Android app.

**Pages URL:** https://goodconscienceapp.github.io/good-conscience-site/

There is no custom domain.

## Pages

| Page | File |
| --- | --- |
| Home | `index.html` |
| Privacy | `privacy.html` |
| Delete account | `delete.html` |
| Contact Us | `contact.html` |
| Creator Opportunities | `creators.html` |

## Preview locally

From the repository root:

```bash
python3 -m http.server 8765
```

Open http://127.0.0.1:8765/

Links and assets are relative, so the same files work on GitHub Pages under `/good-conscience-site/`.

## GitHub Pages

- Repository: `GoodConscienceApp/good-conscience-site`
- Branch: `main`
- Source folder: `/` (root)
- A `.nojekyll` file keeps Pages from running Jekyll.

In the repository settings, GitHub Pages should be enabled from the `main` branch, folder `/`. The repository homepage field should be the Pages URL above.

## Product screenshot

`assets/access-screen.png` is a real app screenshot. The only edit is the access-screen app icon, which is a red exclamation mark. The rest of the screen is unchanged.

Privacy policy text and the delete-account page are copied from the source documents and restyled to this site.
