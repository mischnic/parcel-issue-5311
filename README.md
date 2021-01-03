# a (`@parcel/packager-html: Asset has no content`)

`(rm -rf .parcel-cache && parcel2 build a/index.html || parcel2 build a/index.html) | cat`

Revert https://github.com/parcel-bundler/parcel/commit/0cd78e2be54ddb24d6048b88c179b3ad4dd272f8

# b (`@parcel/packager-js: Asset has no content`)

0. `rm -rf .parcel-cache`
1. `parcel b/index.html`
2. Change `blue` to `red`, save
3. Change `red` back to `blue`, save: `@parcel/packager-js: Asset has no content`
