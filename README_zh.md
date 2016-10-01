Atom Editor簡單的批次/大量安裝套件的檔案列表。

## 如何使用:

使用命令列工具`apm`。更改下面的`package-list-file.txt`為general.txt/react.txt/rn.txt/sass.txt/md.txt/php.txt。

> apm install --packages-file package-list-file.txt

## 已測試:

- Mac OS X ✅
- Windows(10) ✅

### HTML/CSS/JS/Git

!! 基本使用的套件，請先安裝這個。

- general.txt

### SASS(SCSS)

- sass.txt

### React

- react.txt

### React Native

- rn.txt

### Markdown

- md.txt

### PHP Development

!! 要安裝這個請先在電腦中安裝php。

- php.txt

### 繁體中文語言選單

- cht.txt

## 注意事項

你的電腦需要超過400MB的空間，而且這會花你15~30分來安裝上面所有的套件。

- atom-ternjs: 如果這沒辦法正常使用，請降級到0.14.2版本。
- [sync-settings](https://atom.io/packages/sync-settings): 備份設定使用的，你需要先申請github帳號。
- [nuclide](https://atom.io/packages/nuclide): 包含許多套件。 (!!注意: 有些功能不支援Windows)

## 更新日誌

### 161001

- add nuclide.txt
- rename web.txt to general.txt

### 160930

- remove all verion annotation, apm now will install the latest version of packages.
- add sass.txt and rn.txt.
- add some packages for web and markdown usage.
