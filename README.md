# Beyond the Code

An editable [Slidev](https://sli.dev/) internship presentation, ready to run locally, export to PDF, or publish with GitHub Pages.

Live presentation: [carlin421.github.io/beyond-the-code](https://carlin421.github.io/beyond-the-code/)

The Universal Processing logo on the cover is clickable and links to the company website.

## Run it locally

You need Node.js 20.12 or newer.

```bash
npm install
npm run dev
```

Slidev prints the local address in the terminal. Press `o` to open it, or visit the displayed URL in a browser.

## Add the real screenshots and photos

Put the files in `public/media/` using the filenames listed in that folder's README. The deck uses `MediaFrame`, so a missing file appears as a tidy placeholder instead of a broken-image icon.

Example:

```md
<MediaFrame
  src="/media/jira-workflow.png"
  alt="Jira workflow screenshot"
  label="Add Jira workflow screenshot"
/>
```

`MediaFrame` also accepts `caption`, `fit="cover"` or `fit="contain"`, `position`, and `aspect`.

## Export a PDF

```bash
npm run export
```

This creates `Carlin_Hou_Internship_Presentation.pdf`. The project includes the Chromium dependency Slidev requires for reliable PDF export.

## Build a portable website

```bash
npm run build
```

The static site is written to `dist/`. You can copy that folder to any static web host. The standard build also generates a downloadable PDF because `download: true` is enabled in `slides.md`.

The standard build intentionally **keeps the speaker notes** so the complete presentation remains available in presenter mode. Notes included in a public build are not private. To publish a copy without them, run:

```bash
npm run build -- --without-notes
```

## Publish with GitHub Pages

1. Create a GitHub repository and push this project to its `main` or `master` branch.
2. In the repository, open **Settings → Pages** and choose **GitHub Actions** under “Build and deployment.” The included workflow can also enable Pages automatically.
3. Open the repository's **Actions** tab and wait for “Deploy pages” to finish.
4. Visit `https://<username>.github.io/<repository-name>/`.

The workflow builds with the repository name as Slidev's base path, so media and navigation work beneath the GitHub Pages subdirectory.

## Edit the presentation

- Presentation content and speaker notes: `slides.md`
- Deck-wide visual styling: `style.css`
- Reusable media placeholder: `components/MediaFrame.vue`
- Screenshots and photos: `public/media/`

Slidev separates slides with `---`. Speaker notes are the HTML comment at the end of each slide:

```md
<!--
Say this while the slide is visible.
-->
```
