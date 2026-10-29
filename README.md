# NXD

Personal site for [@nxd_.10](https://www.instagram.com/nxd_.10/). One page with a loading intro, a hero with floating photos, three journey chapters, a scroll-through photo strip, a journal and a contact section. It is one `index.html` plus the photos, all in the same folder, so there is no build step.

## Put it online with GitHub Pages

1. Upload every file from this folder to the root of a GitHub repository: `index.html`, `README.md` and all the `.jpg` files. Replace any older files with the same names.
2. Open **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then save.
3. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Edit the site

Open `index.html` and search for these names inside the `<script>` section.

- `CHAPTERS`: the three journeys (title, text and the photos used in each collage).
- `FRAMES`: every photo in the scroll-through strip and the viewer, with its title and crop focus.
- `POSTS`: the journal posts. The five posts are samples, so replace them with real writing and remove `sample: true` to hide the "Sample post" tag.
- `POST_PHOTO`: which photo each post uses.
- `IG`: the Instagram link.

The hero text, the large statement and the contact copy are plain text in the HTML part of the same file.

## Photos

`01.jpg` to `20.jpg` are the full-size photos. `t01.jpg` to `t20.jpg` are the small versions used in the strip. To swap a photo, replace both files with the same number.

## Contact form

GitHub Pages only serves static files, so the form has no inbox behind it. It prepares a message that the visitor copies and sends as an Instagram DM.

## Fonts

Bricolage Grotesque, Instrument Serif, Manrope and DM Mono load from Google Fonts. The page falls back to system fonts if they are blocked.
