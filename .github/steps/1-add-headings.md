## Step 1: 見出しを追加する

**_Markdown_ とは**: Markdown は、GitHub 上でのやり取りに使う[軽量な記法](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)です。見出し、リスト、**太字**、_斜体_、表など、さまざまな書式を付けられます。Markdown は GitHub の次のような場所で使えます。

- [issue](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues)、[pull request](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)、[discussion](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions) のコメント
- 拡張子が `.md` または `.markdown` のファイル
- [Gist](https://docs.github.com/github/writing-on-github/editing-and-sharing-content-with-gists/creating-gists) に書いたテキスト

**_見出し_ とは**: 見出しは、セクションの先頭に置く少し大きな文字です。大きさは 6 段階あります。

### 例

```md
# This is an `<h1>` heading, which is the largest

## This is an `<h2>` heading

###### This is an `<h6>`heading, which is the smallest
```

# This is an `<h1>` heading, which is the largest

## This is an `<h2>` heading

###### This is an `<h6>` heading, which is the smallest

### ⌨️ やること: Markdown ファイルを作る

1. ブラウザーで新しいタブを開きます。説明は今のタブで読み、操作はもう一方のタブで行います。

1. 上部のメニューで **Code** タブを開きます。

1. 次の名前で新しいブランチを作ります。

   ```md
   start-blog
   ```

1. ファイル一覧の上にある **Add file** ボタンをクリックし、**Create new file** を選びます。

1. ファイル名は次のとおりにします。

   ```md
   day-1.md
   ```

1. エディターの 1 行目に、レベル 1 の見出しでページのタイトルを書きます。

   ```md
   # Daily Learning
   ```

1. 各ブログ記事の名前として、レベル 2 の見出しを 2 つ追加します。

   ```md
   ## Morning Planning

   ## Review
   ```

1. エディターの上にある **Preview** の切り替えをクリックして、表示結果を確認します。

1. 右上の **Commit changes** ボタンをクリックし、`start-blog` ブランチに直接コミットします。

1. 見出しを作成してコミットしたので、Mona が作業を確認しています。少し待って、コメントを見てください。進捗と次の Step が投稿されます。

<details>
<summary>うまくいかないとき 🤷</summary><br/>

- 編集しているファイルとブランチが正しいか確認してください。
- 記法を見直してください。`#` と最初の単語の間には半角スペースが必要です。

</details>
