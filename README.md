# Personal website

Files in this folder:

- `index.html`: the whole site (one page with sections: About, Teaching, Mentoring, Research, Seminars).
- `cv.pdf`: copy of `..\CV\cv.pdf`. Replace it whenever the CV changes.
- `photo.jpg`: **not yet here.** Until it exists, the page shows the initials "IN" in the photo frame.

## Adding the photo

1. Open https://sites.google.com/view/ikshu/home, right-click the photo, and choose "Save image as".
2. Save it in this folder as `photo.jpg`. The frame is portrait (4:5) and crops to fit, so any reasonably centered photo works. Later, replace it with the new photo under the same name.

## Editing

Open `index.html` in VS Code. The content is plain text between tags; each course, student, or talk is one `<li>...</li>` block, so copy an existing block and change the text. Double-click `index.html` to check the result in a browser.

## Hosting: GitHub Pages (recommended)

Free, no ads, a stable address that does not depend on your employer (a University of Helsinki page would disappear when the position ends), and the files stay exactly as written.

1. Create a GitHub account (github.com). The username becomes the address, e.g. `ikshu.github.io` if the name `ikshu` is available.
2. Create a new **public** repository named exactly `<username>.github.io`.
3. On the repository page: "Add file" → "Upload files". Drag in `index.html`, `cv.pdf`, `photo.jpg`. Click "Commit changes".
4. Settings → Pages → "Deploy from a branch", branch `main`, folder `/ (root)` → Save. The site appears at `https://<username>.github.io` within a few minutes.
5. To update later, upload the changed file again the same way.

## The old Google Sites address

Applications already submitted list `sites.google.com/view/ikshu` (it is on the CV). Keep that site live, and replace its Home page text with one line: "This site has moved to https://<username>.github.io", with a link. Delete its other pages. Then update the URL on the CV (header of `cv.tex`) and in the job tracker notes for any application not yet submitted.
