# The Project Before the Project – Event Photos

Photo gallery with face search for the AIA New York Committee on Residential Architecture
event (November 5, 2026, 121 Varick Street). Photos shared by Cravtsman.

## Structure
- `index.html`: the whole page (layout, styles, script, gallery data)
- `public/photos/`: web-size photos (lightbox)
- `public/thumbs/`: grid thumbnails
- `public/faces.jpg`: face thumbnails, combined into one image
- `public/logos/`: event and sponsor logos

## Run locally
```
npm install
npm run dev
```

## Notes for editing
- High-res requests and "This is me" name-tag requests are emailed to info@cravtsman.com.
- Names are added to faces only after approval (edit the `name` field for a person in the
  gallery data inside `index.html`).
