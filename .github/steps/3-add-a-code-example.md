## Step 3: コード例を追加する

[コードブロック](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-code)と、言語に応じた[シンタックスハイライト](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)を学びます。

> [!TIP]
> 多くのプログラミング言語に対応しています。ほかの言語の指定も試してみてください。

### 例: ターミナルコマンド

````md
```bash
git clone https://github.com/skills/communicate-using-markdown
```
````

```bash
git clone https://github.com/skills/communicate-using-markdown
```

### 例: JavaScript のコード

````md
```js
var myVar = "Hello, world!";
```
````

```js
var myVar = "Hello, world!";
```

### :keyboard: やること: コード例を追加する

1. `start-blog` ブランチで、`day-1.md` ファイルを開いて編集します。

1. **Review** のレベル 2 見出しの下に、GitHub Blog で知ったコードの記録として次の内容を追加します。

   ````md
   Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

   ```bash
   ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
   ```
   ````

1. **Preview** タブで Markdown の書式を確認します。

1. 右上の **Commit changes** ボタンをクリックし、`start-blog` ブランチに直接コミットします。

1. コードブロックをコミットしたので、Mona が作業を確認しています。少し待って、コメントを見てください。進捗と次の Step が投稿されます。

<details>
<summary>うまくいかないとき 🤷</summary><br/>

- 編集しているファイルとブランチが正しいか確認してください。
- 記法を見直してください。コードブロックはバッククォート 3 個 ` ``` ` であり、アポストロフィ 3 個 `'''` ではありません。

</details>
