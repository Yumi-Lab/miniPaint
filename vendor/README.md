# Vendored dependencies

## hermite-resize 2.2.10

- Source: https://github.com/viliusle/Hermite-resize (same author as miniPaint), MIT license (`hermite-resize/MIT-LICENSE.txt`).
- File: `hermite-resize/dist/hermite.npm.js`, the package's own `main` entry, copied unchanged.
- sha256: `25a48257393d8bd51b155ba9f7f562c273aef5d5eb159cee756fd3cbd0292881`
- Why vendored: the upstream `package.json` pulls it from a git URL, and npm 12 refuses git
  dependencies (`EALLOWGIT`, then `EALLOWSCRIPTS` for its nested install). The package is no longer
  published on the npm registry (unpublished in 2018).
