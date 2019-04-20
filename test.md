# find：活用事例
linuxコマンドのfindの活用事例の覚え書き

### Description
findは検索コマンドであるが、機能が協力なため重宝する。オプションが複雑なため、調べて使った際の事例を残している。

## 事例

* ファイルを検索し、圧縮する
```
find ./ -name "*.htm*" -exec tar rvf /tmp/YYYYMMDD.tar {} \;
```

* 複数条件のファイル名検索
```
find ./ \( -iname '*css' -or -iname \*html \) -print
```

