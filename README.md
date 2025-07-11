# 防災アプリ学習プログラム

## 概要
このプロジェクトは、プログラミング未経験者向けのPython穴埋め問題による防災アプリ学習プログラムです。5つの問題を段階的に解くことで、防災アプリが完成していきます。

## 学習内容
1. **問題1: 変数の使い方**（10分）
   - 気象庁のAPI URLを設定
   - 基本的な変数の概念を学習

2. **問題2: 条件分岐**（15分）
   - 注意報・警報の判定処理
   - if文の使い方を学習

3. **問題3: 繰り返し処理**（15分）
   - 避難所データの処理
   - for文とループの概念を学習

4. **問題4: リストの操作**（20分）
   - 藤沢市の地区データ管理
   - リストの基本操作を学習

5. **問題5: 辞書の操作**（20分）
   - 通知履歴の管理
   - 辞書（dict）の使い方を学習

## ファイル構成
```
bousai_app_no_experience/
├── README.md              # このファイル（プロジェクト概要）
├── 学習ガイド.md          # 詳細な学習ガイド
├── 講師用解答集.md        # 講師向け解答とヒント
└── bousai_app/
    ├── app.py             # メインアプリケーション（穴埋め問題）
    ├── requirements.txt   # 必要なライブラリ
    ├── data/
    │   ├── shelters.json  # 避難所データ
    │   └── notification_history.json  # 通知履歴
    └── templates/
        ├── base.html      # ベーステンプレート
        ├── index.html     # ホームページ
        ├── login.html     # ログインページ
        ├── shelter_search.html     # 避難所検索ページ
        ├── shelter_register.html   # 避難所登録ページ
        ├── search_results.html     # 検索結果ページ
        └── notification_history.html # 通知履歴ページ
```

## セットアップ手順
1. 必要なライブラリのインストール
```bash
cd bousai_app
pip install -r requirements.txt
```

2. アプリケーションの起動
```bash
python app.py
```

3. ブラウザでアクセス
http://localhost:5000

## 学習の進め方
1. `app.py`を開く
2. 各問題のコメントブロックを確認
3. `# 【問題○】`から始まるコメントを見つける
4. `# TODO:`の指示に従ってコードを記述
5. アプリを起動して動作確認
6. 段階的にアプリの機能が追加されることを確認

## 各問題の目標
- **問題1完了後**: 気象情報の基本表示が動作
- **問題2完了後**: 警報判定機能が動作
- **問題3完了後**: 避難所検索機能が動作
- **問題4完了後**: 地区別検索機能が動作
- **問題5完了後**: 通知履歴機能が動作（完全版）

## 注意事項
- 各問題は順番に解いてください
- プレースホルダー（`___`）を適切なコードに置き換えてください
- わからない場合は、コメントのヒントを参考にしてください

## 技術仕様
- Python 3.x
- Flask（ウェブフレームワーク）
- Bootstrap（CSS フレームワーク）
- JSON（データ形式）

## 学習時間目安
総学習時間: 約80分
- セットアップ: 10分
- 各問題: 10-20分
- 動作確認・復習: 10分
