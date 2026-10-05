<!-- tyhp-readme:start -->
# tyhpdef/symfony-css-selector

Tyhp type definitions for `symfony/css-selector` `7.4.18`.

```bash
composer require --dev tyhpdef/symfony-css-selector:7.4.18
```

This is a metapackage. Composer also installs `tyhpdef/symfony-css-selector-impl` (type files).
Require **this** name, not `tyhpdef/symfony-css-selector-impl`.

See https://tyhplang.com.

## Maintain `symfony/css-selector`? Ship the types yourself

If you are a Packagist maintainer of `symfony/css-selector`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-css-selector-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/css-selector` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-css-selector": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/css-selector` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/css-selector` with a real constraint,
   `"replace": { "tyhpdef/symfony-css-selector": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/css-selector` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-css-selector` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
