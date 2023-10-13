---
title: Markdown 構文ガイド
date: 2020-01-01
authors:
  - name: John Doe
    link: https://example.com/johndoe
excludeSearch: true
---

この記事では、Hugoのコンテンツファイルで使用できる基本的なMarkdown構文の例を提供しています。

<!--more-->

## 基本構文

### ヘッダー

# レベル1 ヘッダー
## レベル2 ヘッダー
### レベル3 ヘッダー
#### レベル4 ヘッダー
##### レベル5 ヘッダー
###### レベル6 ヘッダー

## レベル2 ヘッダー
### レベル3 ヘッダー
#### レベル4 ヘッダー
##### レベル5 ヘッダー
###### レベル6 ヘッダー

*このテキストはイタリックになります*
_これもイタリックになります_

**このテキストは太字になります**
__これも太字になります__

_あなたは **組み合わせる** ことができます_

### リスト

#### 順序なしリスト

* 項目 1
* 項目 2
  * 項目 2a
  * 項目 2b

#### 順序付きリスト

1. 項目 1
2. 項目 2
3. 項目 3
   1. 項目 3a
   2. 項目 3b

### 画像

![GitHub ロゴ](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### リンク

[Hugo](https://gohugo.io)

### ブロック引用

牛頓は言いました：
> もし私が遠くを見ることができるのなら、それは巨人の肩に立っているからだ。

### インラインコード

インライン `コード` は `バッククォート` で囲まれています。

### コードブロック

#### シンタックスハイライト

```go
func main() {
    fmt.Println("Hello World")
}

### 表格
```markdown
| 構文      | 説明       |
| --------- | ---------- |
| ヘッダー  | タイトル   |
| パラグラフ | テキスト  |
```

| 構文      | 説明       |
| --------- | ---------- |
| ヘッダー  | タイトル   |
| パラグラフ | テキスト  |

## 参考

- [Markdown 構文](https://www.markdownguide.org/basic-syntax/)
- [HugoのMarkdown](https://gohugo.io/content-management/formats/#markdown)
