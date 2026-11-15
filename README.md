# brain-ai v1 preview

シャープの電子辞書 Brain（第4世代・Windows CE 6.0）の上で、オフラインのまま動作する日本語の小型 AI です。
約 1,470 万パラメータで、モデルは約 6.7MB。日常会話・相談・計算・プログラミングに関する簡単な質問に対応します。

## 収録内容

- `Brain/` — Brain 実機用。SD カードの最上位に「アプリ」フォルダをコピーして使います
- `Emulator/` — Visual Studio 2008 Device Emulator（Windows Mobile 5.0）用

詳しい使い方は同梱の「はじめに.txt」をご覧ください。

## 注意

本版はプレビュー版です。モデルが非常に小さいため、回答に誤りが含まれることがあります。正確さが求められる用途には使用しないでください。
Brain 実機での動作は未検証です。

## ライセンス

CC BY-SA 4.0（[LICENSE](LICENSE) 参照）。日本語 Wikipedia に由来する知識を含むため、このライセンスとしています。

学習データの出典:

- 日本語 Wikipedia（CC BY-SA 4.0）
- github-code-clean（MIT / Apache-2.0 / BSD ライセンスのもののみ）
- Qwen3.8-27B による生成データ（Apache-2.0）

モデルの配布先: https://huggingface.co/yamada2wasabi/brain-ai-v1-preview

## 作者

作者は、Brain Wiki を 2017 年ごろに編集していた「おおおおおおおお」です。
