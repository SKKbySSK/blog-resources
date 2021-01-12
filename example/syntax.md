
## 特殊構文


一部のMarkdown機能を拡張しています

| 構文 | 説明 |
| --- | --- |
| `[](URL "{Title}")` | ボーダー付きのボタンが生成されます |
| `[](https://twitter.com/{ID} "{Follow, Timeline}")` | 指定IDユーザーのツイート一覧か、フォローボタンを表示 |
| `[](https://twitter.com/{UserID}/status/{TweetId} "Tweet")` | 指定ツイートを表示 |

## 構文例

##### ボタン

[](https://kscafe.work "Go to Home")
```
[](https://kscafe.work "Go to Home")
```

---
##### Twitter

[](https://twitter.com/SKKbySSK_TC "Follow")
```
[](https://twitter.com/SKKbySSK_TC "Follow")
```

[](https://twitter.com/SKKbySSK_TC "Timeline")
```
[](https://twitter.com/SKKbySSK_TC "Timeline")
```

[](https://twitter.com/DEGUANA1984/status/1347936570364497921 "Tweet")
```
[](https://twitter.com/DEGUANA1984/status/1347936570364497921 "Tweet")
```
