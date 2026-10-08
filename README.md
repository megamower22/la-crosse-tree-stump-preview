# La Crosse Tree & Stump LLC – preview website

This is a free preview website for **La Crosse Tree & Stump LLC** (La Crosse, WI), built by Hudson | Lacrosse Lawn & Landscape.
It is plain HTML and CSS: no build step, no monthly fees for hosting.

Live preview: https://megamower22.github.io/la-crosse-tree-stump-preview/

## How to change text on the site (on github.com)

1. Go to this repo on github.com and sign in.
2. Click **index.html**.
3. Click the **pencil icon** (Edit this file) at the top right of the file.
4. Find the words you want to change and type the new text. Only change the words between the tags, not the `<` `>` parts.
5. Scroll down (or click the green **Commit changes...** button), add a short note like "Update hours", and click **Commit changes**.
6. Wait about a minute, then refresh the website. Your change will be live.

## Good to know

- **Colors** are at the top of `style.css` (look for `--green` for the main dark green, `--green-bright` for stars and highlights, `--paper` for the light background, and `--black`).
- Anything in yellow highlight that says **[Owner to confirm]** still needs real info from the owner. Once it's confirmed, delete the whole `<span class="placeholder">...</span>` part.
- The phone number appears in several places. Search for `498-8733` (and `+16084988733` in the call links) to update all of them.
- The Google rating appears in two places: the big rating card near the top (`class="rating-score"` and `class="rating-count"`) and the "Rated 5.0 on Google" box. Search for `36 Google reviews` to update both as more reviews come in.
- To remove the "Preview site" banner once the owner approves, delete the line with `class="preview-banner"` in `index.html`.
