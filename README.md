# Strong at Home

A 12-week, 4-day-a-week strength program as a simple phone web app.

- `index.html` — the whole app (no build step). Hosted with GitHub Pages.
- Progress saves on the phone and to Firebase Firestore at `progress/<code>`, where `<code>` is the private `?u=` value in the person's link.
- `firestore.rules` — paste into Firebase console → Firestore Database → Rules.

To give someone their own copy of the program, send them the site link without `?u=`; the app creates a private code for them on first open.
