# 🎯 UniquePersonCounter

[![Open In Colab](https://colab.research.google.com/github/fukayatti0/UniquePersonCounter/blob/main/UniquePersonCounter.ipynb)

## 📝 概要
動画内の静止している人物を検出・カウントするスマートな分析ツールです。AI技術（YOLOv8 & DeepSort）を活用し、高精度な人物追跡と個人識別を実現します。

## ✨ 主な機能
- 🎥 動画からのリアルタイム人物検出 (YOLOv8)
- 🎯 高精度な人物追跡システム (DeepSort)
- 👥 AI駆動の顔認識・個人識別 (MTCNN, FaceNet)
- 📊 ユニークな人物カウンティング
- 💾 検出顔画像の自動保存機能

## 🚀 使用方法
1. Google Colabで`.ipynb`ファイルを起動
2. 必要なライブラリを自動インストール
3. Google Driveをマウント
4. `video_paths`リストに対象動画パスを設定
5. 各セルを順次実行

## 📊 出力データ
- 👥 ユニークな人物の総数
- 🎬 処理フレーム総数
- ⚠️ 顔検出失敗フレーム数
- 🚫 人物検出失敗フレーム数
- 📸 検出顔画像（`/content/unique_face_images/`）
- 📄 詳細な分析レポート

## ⚠️ 注意事項
- 🖥️ GPU環境での実行を強く推奨
- ⏱️ 処理時間は動画の品質に依存
- 📌 顔の明瞭さが識別精度に影響

## 📜 ライセンス
MIT License