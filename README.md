Atom Editor packages list files for batch(bulk) installed packages easily.

## How to use:

Use command line. Change the `package-list-file.txt` to web.txt/react.txt/rn.txt/sass.txt/md.txt/php.txt below.

> apm install --packages-file package-list-file.txt

## Test:

- Mac OS X ✅
- Windows(10) ✅

### HTML/CSS/JS/Git

!! Basic usage, install this first.

- web.txt

### SASS(SCSS)

- sass.txt

### React

- react.txt

### React Native

- rn.txt

### Markdown

- md.txt

### PHP Development

!! To install php in your computer first for linter.

- php.txt

### Chinese Menu

- cht.txt

### excluded some useful extensions

- [sync-settings](https://atom.io/packages/sync-settings): for backup settings. You need a github account.
- [nuclide](https://atom.io/packages/nuclide): for react native, contains many extensions. (!!NOTE: isn't supported Windows)

## Note

- atom-ternjs: if it isn't worked, downgrade to 0.14.2 version.

## Changlog

### 160930

- remove all verion annotation, apm now will install the latest version of packages.
- add sass.txt and rn.txt.
- add some packages for web and markdown usage.
