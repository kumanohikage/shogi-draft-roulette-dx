# ☗ 将棋ドラフト抽選ルーレットDX ☖

**指名、競合。交渉権の行方は――盤上の駒が決める。**

将棋のドラフト会議で**指名が重複（競合）したとき**に、どのリーダーが交渉権を得るかを決めるルーレットです。
パチンコ風の3D演出と将棋中継さながらの評価値バーで、「誰に決まるか」を最後まで引っ張ります。

▶ **今すぐ回す: https://kumanohikage.github.io/shogi-draft-roulette-dx/**

---

## 抽選は公平です

- 回した瞬間に、競合したリーダー全員から**同じ確率**で1人を選び、結果が決まります
- リーチ・評価値・逆転などの演出は、**決まった結果を盛り上げるための飾り**です
- 演出によって確率を変えたり、特定の人を有利にしたりすることは**一切ありません**

---

## 使い方

1. 上のリンクを開く
2. 右上の **⚙ 設定** で、指名者と競合したリーダーを入れる
3. **SPIN!**

結果は「〇〇 交渉権確定!」と表示されます。画面のどこかをタップすると閉じます。

### 設定

| 項目 | 内容 |
|---|---|
| 指名者 | 重複した棋士の名前 |
| 競合したリーダー | 1行に1人、2〜8人 |
| 指名者の画像（任意） | 盤の真ん中と結果画面に丸く表示。ファイル選択・ドラッグ・Ctrl+V で入れられ、位置と大きさを調整できます |

入力欄から離れると自動で保存され、次に開いたときも残ります。

### キー

| キー | 動作 |
|---|---|
| Space / Enter | 回す・PUSH・結果を閉じる |
| S | 設定を開く |
| H | ボタン類を隠す |

---

## OBS に載せる

| 用途 | URL |
|---|---|
| 横配信（16:9） | https://kumanohikage.github.io/shogi-draft-roulette-dx/?layout=horizontal |
| 縦配信（9:16） | https://kumanohikage.github.io/shogi-draft-roulette-dx/?layout=vertical |
| 横・背景透過 | https://kumanohikage.github.io/shogi-draft-roulette-dx/?layout=horizontal&transparent |
| 縦・背景透過 | https://kumanohikage.github.io/shogi-draft-roulette-dx/?layout=vertical&transparent |

### ブラウザソース（おすすめ）

1. ソースを追加 → **ブラウザ** → 上の URL を入れ、幅×高さを **1920×1080**（横）か **1080×1920**（縦）にする
2. ソースを右クリック → **操作** で開いた窓から、設定と SPIN を行う
3. 背景を透かしたいときは、透過用の URL を使う（クロマキーは不要です）

> **注意**
> - OBS のブラウザソースは、普段のブラウザとは設定の保存場所が別です。名前や画像は「操作」の窓で入れてください
> - 「操作」の窓では**日本語入力ができません**。名前はメモ帳などで入力してコピーし、**Ctrl+V で貼り付けて**ください
> - 「操作」の窓で画像のファイル選択が効かないときは、画像をコピーして設定画面で **Ctrl+V** で貼り付けられます
> - キーボードを使うときは、窓の中を一度クリックしてから。日本語入力はオフにしておくと確実です

### ウィンドウキャプチャ

普段のブラウザで上の URL を開き、OBS の **ウィンドウキャプチャ** でその窓を選びます（アドレスバーはトリミング）。

配信画面にボタンを映したくないときは H キーで隠せます。回している間は自動で消えます。

---

## 改変・利用について

誰でも自由に使ってください。配信での利用、改変、再配布、どれも OK です。ライセンスは [MIT](LICENSE) です。

## クレジット

- 制作: 熊乃ヒカゲ（[@kumanohikage](https://x.com/kumanohikage)） with Claude
- 姉妹作: [光と闇のルーレットDX](https://github.com/kumanohikage/hikari-yami-roulette-dx)
- ドラフト会議をまるごと進行するアプリ版（試作中）: [将棋ドラフト会議アプリ](https://github.com/kumanohikage/shogi-draft-app)
- 3D描画: [three.js](https://threejs.org/)（MIT License）
- フォント: [Dela Gothic One](https://fonts.google.com/specimen/Dela+Gothic+One)、[Noto Sans JP](https://fonts.google.com/noto/specimen/Noto+Sans+JP)（SIL Open Font License）
