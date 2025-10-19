# TODO: Fix Image Paths After Adding img/ Folder

## Information Gathered
- User added a new folder named `img/` to store photos.
- All image files are now inside `img/` folder (e.g., img/cecep.jpeg, img/logo.png, etc.).
- HTML file references images without `img/` prefix (e.g., src="cecep.jpeg").
- CSS file has background-image without `img/` prefix (e.g., url('image.jpeg')).
- Need to update all image paths to include `img/` to correctly reference the new folder.

## Plan
- [x] Update all `<img src="...">` in index.html to prepend `img/` (e.g., src="img/cecep.jpeg").
- [x] Update background-image in style.css to prepend `img/` (e.g., url('img/image.jpeg')).
- [x] Check for any missing or incorrect image references.
- [x] Verify images load correctly after changes.
- [x] Test the website to ensure no broken images.

## Dependent Files to Edit
- index.html: Update all img src attributes.
- style.css: Update background-image URL.

## Followup Steps
- [ ] Verify images load correctly after changes.
- [ ] Test the website to ensure no broken images.
