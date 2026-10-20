# ゲームサイト提出用テキスト

提出フォームは英語なので、英語の文をそのままコピーして使ってください。日本語訳は確認用です。
アップロードするファイルとカバー画像は、GitHub の Releases「latest」に自動で置かれます。

## ちょいハマ（choihama）

**Title**
Choihama - 20 Mini Games

**Description（英語）**
Choihama is a pocket arcade of 20 one-tap mini games, each lasting about a minute. Stack blocks with perfect timing, stop a hidden timer at exactly 10.00 seconds, tap numbers 1 to 25 as fast as you can, test your reflexes, whack moles, solve quick math, remember flashing panels, fly through pipes, break bricks and more. Every game has its own rank titles and best score, so there is always one more record to beat.

（日本語訳）1回1分で遊べる、ワンタップのミニゲーム20本。ピタ積み、ピタッと10秒、1→25タッチ、反射神経テスト、もぐらタップ、暗算、記憶パネル、ジャンプ、ブロック崩しなど。ゲームごとにランクとベスト記録があります。

**Controls**
- Tap or click to play. Each game shows its own short instructions before it starts.
- Some games use swipes or arrow keys (Snake, Arrow Swipe) and Space (Stack, Jump).

**Category / Tags（候補）**
Casual / mini games, reaction, puzzle, arcade, one tap, brain

## CrazyGames の設定
| 項目 | 設定 |
|---|---|
| Game file | `choihama-crazygames.zip` をアップロード |
| Orientation（画面の向き） | Portrait（縦）。パソコンでも左右に余白が付いて遊べます |
| Mobile support | Yes（スマホ・タブレット対応） |
| Progress Save（記録の保存） | **必ずオンにする**。オフだとベスト記録が保存されません |
| Covers | `store/` の3枚（1920×1080・800×1200・800×800） |
| Language | English, Japanese（ブラウザの言語で自動切り替え） |

## GameDistribution の設定

1. ゲームを新規登録して、もらった Game ID を `monetize.config.json` の `gamedistribution.gameId` に入れて main に入れる
2. 数分後に Releases「latest」に作り直される `choihama-gamedistribution.zip` をアップロードする
3. タイトル・説明文・操作方法は上と同じ英語を使う。画面の向きは Portrait、スマホ対応は Yes
