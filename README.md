# GRAVITATE OSAKA｜関西ウォーカー P4 純広告プレビュー

A4縦サイズ（210×297mm）の雑誌広告を、ブラウザ表示用HTMLとして作成した校正データです。

## 閲覧方法

1. **直接閲覧**：リポジトリの [index.html](./index.html) を Raw 表示またはダウンロード
2. **GitHub Pages（推奨）**：リポジトリ設定 → Pages → Source を「main / root」に設定すると、以下URLで公開されます
   ```
   https://hirokimagic15-a11y.github.io/-/
   ```

## ファイル構成

```
.
├── index.html          # 広告本体（A4縦）
└── images/
    ├── hero.jpg        # ファーストビュー（ダム湖空撮）
    ├── logo.png        # GRAVITATE OSAKAロゴ
    ├── act01-walk.jpg  # BRIDGE WALK
    ├── act02-bungee.jpg # BUNGEE
    ├── act03-swing.jpg  # GIANT SWING
    └── act04-climb.jpg  # TOWER CLIMB
```

## 設計コンセプト

ユージン・シュワルツの認知度5段階診断、LF8理論、大衆心理の原則に基づき、
「雑誌の中で指を止め、ヘッドラインで本文まで読ませる」機能性を最優先に設計しています。

- ヘッドライン：「梅田から、30分。」（読者の日常と即接続する唯一の数字を主役に）
- 情報序列：近さ → 記録 → 場所の感情三段跳び
- 配色：黒・白・ゴールド1色（#B08A3E）
- 書体：Noto Serif JP（見出し）/ Noto Sans JP（本文）/ Zen Kurenaido（手書き風）

## 印刷時の注意

本ファイルはブラウザ表示用の校正データです。
実際の雑誌入稿には以下の処理が必要です：

- CMYK変換（#B08A3E は特色金DIC620番台または専用CMYK値への置換推奨）
- 350dpi以上の画像解像度確認
- PDF/X-1a形式での書き出し
- トンボ・塗り足しの追加（3mm）
