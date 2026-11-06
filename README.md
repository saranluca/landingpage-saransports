# landingpage-saransports

The site root currently serves a self-contained "Website kommt bald" (coming-soon) page: `index.html`, inline CSS, `noindex`.

The earlier dummy site (index, Impressum, AGB, Datenschutz, `css/`, `js/`) was removed from the root and is kept in git history (last present in commit `7bc26e7`).

Deploy: `develop` → `main` → GitHub Pages (staging, `.github/workflows/deploy.yml`) → Ansible to the Hetzner server.
