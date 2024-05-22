# Demo

# 見出し - Headers

# This is an H1

## This is an H2

### This is an H3

# 引用 - Blockquotes

> 引用引用引用引用
> 引用引用
> 引用本文引用本文
>
> > 入れ子

# リスト - Lists

- リスト 1
  - リスト 1-2
- リスト 2

1. リスト 1
   1. リスト 1-1
   2. リスト 1-2
2. リスト 2

- [ ] リスト 1
- [x] リスト 2

# 水平線 - Horizontal Rules

---

# リンク - Links

[Qiita](http://qiita.com)
[Qiita](http://qiita.com "Qiita")

# 強調 - Emphasis

**強調**

# 画像 - images

![Docusaurus logo](/img/docusaurus.png)

# コード表示

`$hoge = 1`
`.md`

```
yarn add hogehoge
```

```html title="hoge.html"
<div class="radioWave">
  <p>迷いの中あてなく見上げた空彩る星たちが</p>
  <p>嘘みたいに晴れた朝に繋がることを教えてくれた</p>
</div>
```

```js title="docusaurus.config.js"
export default {
  themeConfig: {
    navbar: {
      items: [
        // highlight-start
        {
          type: "docsVersionDropdown",
        },
        // highlight-end
      ],
    },
  },
};
```

# テーブル記法

| Left align | Right align | Center align |
| :--------- | ----------: | :----------: |
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |

# 独自

:::note

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::

:::tip

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::

:::info

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::

:::warning

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::

:::danger

Some **content** with _Markdown_ `syntax`. Check [this `api`](#).

:::

<details>
  <summary>Toggle me!</summary>
  <div>
    <div>This is the detailed content</div>
    <br/>
    <details>
      <summary>
        Nested toggle! Some surprise inside...
      </summary>
      <div>😲😲😲😲😲</div>
    </details>
  </div>
</details>
