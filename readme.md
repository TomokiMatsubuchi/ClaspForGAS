
## Claspを用いてTSでGASを書くための初期化ディレクトリです

使用方法

```
git clone

npm ci

touch .clasp.json
```


.clasp.jsonには以下を記載してください

```
{
  "scriptId": "--scriptのidを記載--",
  "rootDir": "./dist",
  "scriptExtensions": [
    ".js",
    ".gs"
  ],
  "htmlExtensions": [
    ".html"
  ],
  "jsonExtensions": [
    ".json"
  ],
  "filePushOrder": [],
  "skipSubdirectories": false
}

```
