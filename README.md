# Pathway Atlas

A static sponsor research aid for device-led combination-product regulatory pathways.

## Host it on GitHub Pages

1. Create a GitHub repository for the site.
2. Upload the contents of this folder to the repository root. Keep `index.html` at the root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select your main branch and the `/ (root)` folder, then save.
5. GitHub will provide the published website URL in the Pages settings.

For another static host, upload this folder or the ZIP contents and use `index.html` as the entry page.

## Notes

- This is a static, single-page site. It does not require a build step, server, or secrets.
- Some 510(k) and PMA examples are retrieved from the openFDA APIs in the visitor's browser. Data availability and refresh timing follow FDA's dataset schedules. The De Novo page links to FDA's searchable database because openFDA does not provide a De Novo JSON endpoint.
- API records are research references, not determinations of pathway eligibility. Verify details against the linked FDA records and current guidance.
- The Inter font is loaded from Google Fonts; if that service is unavailable, the page falls back to system fonts.
