## Step 4: 画像を追加する

[Markdown での画像](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images)の入れ方を、相対 URL、絶対 URL、サイズ指定、簡単な配置指定とあわせて学びます。

### 通常の Markdown

画像は、リポジトリ内のファイルへの相対 URL か、インターネット上のどこかを指す絶対 URL で表示できます。

角かっこの中に書く説明文は、画像を読み込めなかったときに表示され、スクリーンリーダーを使う人には読み上げられます。

注意: Markdown の記法には、画像サイズを変える方法がありません。

### 例

リポジトリ内の画像への相対 URL:
```md
![Mona the Octocat](myrepo/original.png)

```

インターネット上の画像への絶対 URL:
```md
![Mona the Octocat](https://octodex.github.com/images/original.png)
```

<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png" width="200">

### 簡単な HTML

画像を小さくしたい、テキストの横に並べたい、ということはよくあります。通常の HTML の記法を使うと、もう少し自由に指定できます。

- `alt` は代替テキストを指定します。
- `src` は画像の URL を指定します。
- `width` と `height` は、ピクセル単位でサイズを指定します。
- `align` は配置（`left`、`right`）を指定します。

```md
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
```

### :keyboard: やること: 飾りを追加する

今のブログ記事はかなり素っ気ないので、飾りを足します。

1. `start-blog` ブランチで、`day-1.md` ファイルを開いて編集します。

1. **Morning Planning** のレベル 1 見出しの下に画像を挿入します。

   ```md
   ![Cloudy morning](https://octodex.github.com/images/cloud.jpg)
   ```

1. **Preview** タブで Markdown の書式を確認します。

   - 画像が大きすぎることに気づきます。

1. 単純な Markdown 版を、サイズと配置の情報を含む HTML 版に置き換えます。見栄えがよくなります。

   ```md
   <img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
   ```

1. 右上の **Commit changes** ボタンをクリックし、`start-blog` ブランチに直接コミットします。

1. 画像を追加してコミットしたので、Mona が作業を確認しています。少し待って、コメントを見てください。進捗と次の Step が投稿されます。

<details>
<summary>うまくいかないとき 🤷</summary><br/>

- 編集しているファイルとブランチが正しいか確認してください。
- 記法を見直してください。HTML の画像タグは `img` で始まり、`src` 属性を含んでいる必要があります。

</details>
