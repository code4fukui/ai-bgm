# ai-bgm

MagentaのMusicVAEモデルを使用してBGM（背景音楽）を生成するWebアプリケーションです。

## デモ

https://code4fukui.github.io/ai-bgm/

## 主な機能

-   [Magenta MusicVAE](https://magenta.tensorflow.org/music-vae)モデルを使用したAIメロディーの生成
-   生成される音楽のテンポ、拍子、長さのカスタマイズ
-   [smplr](https://github.com/code4fukui/smplr)ライブラリによるSplendid Grand Pianoの音色での再生

## 動作環境

Web Audio APIに対応したモダンなウェブブラウザ

## 使い方

1.  [デモページ](https://code4fukui.github.io/ai-bgm/)を開きます。
2.  お好みに合わせてテンポ、拍子、長さの設定を調整します。
3.  「play」ボタンをクリックすると、音楽が生成・再生されます。

## 使用技術

-   [Magenta.js](https://github.com/magenta/magenta) - 音楽とアートを生成するためのJavaScriptライブラリ。
-   [TensorFlow.js](https://www.tensorflow.org/js) - 基盤となる機械学習フレームワーク。
-   [smplr](https://github.com/code4fukui/smplr) - 楽器音のためのシンプルなWeb Audio APIサンプラー。

## ライセンス

このプロジェクトはMITライセンスです。