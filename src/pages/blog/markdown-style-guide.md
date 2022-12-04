---
layout: "../../layouts/BlogPost.astro"
title: "AstroによるMarkdown Blogの表示"
description: "Here is a sample of some basic Markdown syntax that can be used when writing Markdown content in Astro."
pubDate: "2022/12/4"
heroImage: "/placeholder-hero.jpg"
---

AstroによるMarkdown Blogで`.md`ファイルがどのように表示されるかのサンプルです。内容はAstroの[example blog post](https://github.com/withastro/astro/blob/main/examples/blog/src/pages/blog/markdown-style-guide.md)の和訳です。

## 見出し

Markdownの見出し(`#`)がhタグに対応。

# H1
## H2
### H3
#### H4
##### H5
###### H6

## 段落

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## 画像

![This is a placeholder image description](/placeholder-social.jpg)

## 引用

#### 例1

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.  
> **Note** that you can use *Markdown syntax* within a blockquote.

#### 例2

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## 表

| Italics   | Bold     | Code   |
| --------  | -------- | ------ |
| *italics* | **bold** | `code` |

## ソースコード

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

## リスト

#### 箇条書き（数字あり）

1. First item
2. Second item
3. Third item

#### 箇条書き（数字なし）

* List item
* Another item
* And another item

#### ネスト

* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese

## その他 — abbr, sub, sup, kbd, mark

HTMLタグをそのままMarkdownに記載することで、変換後のページに適用できます。

- `<abbr>`: 略語表記
- `<sub>`, `<sup>`: 下付き、上付き文字
- `<kbd>`: キーボード
- `<mark>`: 文字列マーク

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
