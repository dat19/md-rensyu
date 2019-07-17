# 見出し1

見出し1
===

パラグラフ=段落=pタグ  
改行=brタグ=半角スペース2つ以上

hello.  
hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello.

---

> hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello. hello.

## 区切り線

---
- ハイフン3つ

___
- アンダースコア3つ

***
- アスタリスク3つ

- - -
- ハイフンスペース3つ


## 見出し2

見出し2
---

### 見出し3

#### 見出し4

##### 見出し5

###### 見出し6

- item1

    hello. hello.
hello. hello. hello. hello.
hello. hello. hello. hello. hello.
hello.
hello. hello. hello. hello.
hello.

- item2
- item3


# 強調
hello. hello. *hello. hello.* hello. hello. _hello. hello._ hello. hello. **hello. hello.** hello. hello. __hello. hello.__ hello. hello.

*日本語は斜体にならないことが多い*

# ナンバリング

1. item1
1. item2
1. item3
1. item4

# ハイパーリンク

- https://unityroom.com
- [ドットインストール](https://dotinstall.com)
- [ドットインストール](https://dotinstall.com "動画学習サイト")
- [区切り線](https://github.com/dat19/md-rensyu#区切り線)
  - 作成したGitHubのマークダウンの見出しにカーソルを合わせて、左のリンクアイコンを右クリックして、**リンクのコピー**で、その項目を直接開くリンクが得られる

# コード

- バッククォートは、[Shift]+[@]キー
- バッククォート3つの後ろに、言語を指定できる
  - csならC#
  - cならc言語
  - java
  - html
- スペースがなければ戻る
  - インデント
    - インデント
      - インデント

1. インデント
  1. インデント
  1. インデント
1. インデント

```cs
function x() {
  Debug.Log("hello.");
}
```

- インラインは、バッククォート1つで囲う。`Debug.Log()`はデバッグ表示

# 画像

![画像](figure_barrier_plate.png "from いらすとや")

[![画像](figure_barrier_plate.png "from いらすとや")](https://www.irasutoya.com/)

# テーブル

|列見出し1|列見出し2|列見出し3|
|:---|:---:|---:|
|左揃え|中央揃え|右揃え|
|0|data|data|
