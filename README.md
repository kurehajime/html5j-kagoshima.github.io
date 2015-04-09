# html5j-kagoshima

html5j鹿児島の公式サイト公開用リポジトリです。

* https://github.com/html5j-kagoshima/kagoshima.html5j.org
* https://github.com/html5j-kagoshima/html5conference.2015

のリポジトリをビルドしたものを、このリポジトリにコピーします。

コピーが完了したら

* git add
* git commit
* git push

でサイトを公開することが可能です

### 正式なurl

正式なurlは

http://kagoshima.html5j.org/

です。

### ファイルのコピー

HTML5カンファレンスは

```
$ cd ~
$ cp -r html5conference.2015/dist/* html5j-kagoshima.github.io/html5conference.2015/
```

HTML5サイトは

```
$ cd ~
$ cp -r kagoshima.html5j.org/dist/* html5j-kagoshima.github.io/
```

