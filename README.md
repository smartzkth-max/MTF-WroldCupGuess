# MTF World Cup Guess - Google Sheets Database Version

Static GitHub Pages app for a private friends prediction game.

## This updated version

- Golden Glove / Best Goalkeeper now uses a goalkeeper-only dropdown.
- Public friend view hides admin tools, Database tab, Results setup, Settings, and backup/export controls.
- Participants tab shows only joined names in friend view.
- Admin tools appear only on first setup or on a browser/link that has the admin PIN saved.

## GitHub upload

Upload these files to the repository root:

- `index.html`
- `README.md`
- `.nojekyll` optional

Do not upload `google-apps-script/Code.gs` to GitHub root. Paste that code into Google Apps Script.

## Important privacy note

This is still a static GitHub Pages app. Hiding UI buttons prevents normal visitors from seeing admin screens, but it does not make the source code secret if your GitHub repo is public. For stronger protection, keep the repository private or do not share the repo link; share only the GitHub Pages app link with friends.
