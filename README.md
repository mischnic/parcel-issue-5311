# a

0. `rm -rf .parcel-cache`
1. `parcel build a/index.html`, build error
2. Stop
3. `parcel build a/index.html`: `@parcel/packager-html: Asset has no content`

# b

0. `rm -rf .parcel-cache`
1. `parcel build a/index.html`
2. Change `blue` to `red`, save
2. Change `red` back to `blue`, save: `@parcel/packager-js: Asset has no content`
