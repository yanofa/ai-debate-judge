# AI議論判定

Geminiで生成した議論判定JSONを表示・画像保存するためのツールです。

## 含まれるファイル

* `schema.json` — 議論判定JSONのSchema定義
* `prompt_template.txt` — Gemini用プロンプトテンプレート
* `index.html` — 判定結果ビューアー

## 使い方

1. [Google AI Studio](https://aistudio.google.com/) にログイン
2. 右下の **Structured Output** を有効化し、**Code Editor** に `schema.json` の内容をを貼り付ける
3. `prompt_template.txt` の「前提となる話題」「議論の本文」を記入して Google AI Studio のチャットで送信
4. 返ってきたJSONをダウンロード
5. [index.html](https://yanofa.github.io/ai-debate-judge/) を開いてJSONを読み込む
6. 表示結果を右クリックから画像保存する
