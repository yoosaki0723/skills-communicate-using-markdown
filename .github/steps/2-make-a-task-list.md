## Step 2: リストを作る

Markdown では、よく使う 3 種類のリストが使えます。

- [順序なしリスト](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - 箇条書き
- [順序付きリスト](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - 番号付きリスト
- [タスクリスト](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) - チェックボックスのリスト

### 順序なしリスト

順序なしリストは簡単に書けます。各項目を 1 行ずつ置き、行頭に `-`、`*`、`+` のいずれかの文字を付けます。

```md
- Item 1
- Item 2
- Item 3
```

- Item 1
- Item 2
- Item 3

### 順序付きリスト

行頭の記号の代わりに任意の数字を書くと、順序付きリストになります。番号は Markdown が自動で振ってくれます。便利です。

```md
1. Step 1
1. Step 2
1. Step 3
```

1. Step 1
1. Step 2
1. Step 3

### タスクリスト

タスクリストは、順序なしリストを拡張してチェックボックスを使えるようにしたものです。
未完了のタスクには空の角かっこ `[ ]`、完了したタスクには中身の入った角かっこ `[x]` を付けます。注意: 空の角かっこの中には半角スペースが必要です。

```md
- [x] This task is complete
- [ ] This task is not complete
```

- [x] This task is complete
- [ ] This task is not complete

> [!TIP]
> issue や pull request でも、タスクの記法を使って[進捗を伝える](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists)ことができます。

### :keyboard: やること: 朝の計画にアイデアと目標を追加する

1. `start-blog` ブランチで、`day-1.md` ファイルを開いて編集します。

1. **morning planning** のレベル 2 見出しの下に、達成したい目標を管理するための次のタスクリストを追加します。

   ```md
   - [ ] Check out the [github blog](https://github.blog/) for topic ideas.
   - [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
   - [ ] Convert my first blog post into an actual webpage.
   ```

1. **Preview** タブで Markdown の書式を確認します。

1. 右上の **Commit changes** ボタンをクリックし、`start-blog` ブランチに直接コミットします。

1. コードブロックをコミットしたので、Mona が作業を確認しています。少し待って、コメントを見てください。進捗と次の Step が投稿されます。

<details>
<summary>うまくいかないとき 🤷</summary><br/>

- 編集しているファイルとブランチが正しいか確認してください。
- 記法を見直してください。タスクリストの `[ ]` の中には半角スペースが必要です。

</details>
