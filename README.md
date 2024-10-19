---
license: mit
title: pic-to-header
sdk: streamlit
emoji: 🐨
colorFrom: blue
colorTo: purple
pinned: false
app_file: pic_to_header/app.py
---

<div align="center">

# Pic-to-Header

![Pic-to-Header Result](https://raw.githubusercontent.com/Sunwood-ai-labs/pic-to-header/refs/heads/main/assets/result.png)

[![GitHub license](https://img.shields.io/github/license/Sunwood-ai-labs/pic-to-header)](https://github.com/Sunwood-ai-labs/pic-to-header/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Sunwood-ai-labs/pic-to-header)](https://github.com/Sunwood-ai-labs/pic-to-header/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/Sunwood-ai-labs/pic-to-header)](https://github.com/Sunwood-ai-labs/pic-to-header/issues)
[![GitHub release](https://img.shields.io/github/release/Sunwood-ai-labs/pic-to-header.svg)](https://GitHub.com/Sunwood-ai-labs/pic-to-header/releases/)
[![GitHub tag](https://img.shields.io/github/tag/Sunwood-ai-labs/pic-to-header.svg)](https://GitHub.com/Sunwood-ai-labs/pic-to-header/tags/)
[![PyPI version](https://badge.fury.io/py/pic-to-header.svg)](https://badge.fury.io/py/pic-to-header)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)

</div>

Pic-to-Headerは、マスク画像と入力画像を使用してヘッダー画像を生成するPythonアプリケーションです。

## 🚀 機能

- マスク画像と入力画像をアップロード
- 入力画像にマスクを適用してヘッダー画像を生成
- 生成されたヘッダー画像のプレビューとダウンロード
- コマンドラインインターフェース (CLI) を使用した画像処理

## 🛠️ インストール

### 方法1: PyPIからのインストール

Pic-to-Headerは、PyPIで利用可能です。以下のコマンドでインストールできます：

```
pip install pic-to-header
```

### 方法2: ソースからのインストール

1. リポジトリをクローンします：

```
git clone https://github.com/Sunwood-ai-labs/pic-to-header.git
cd pic-to-header
```

2. パッケージをインストールします：

```
pip install -e .
```

## 📖 使用方法

### Streamlitウェブアプリケーション

1. Streamlitアプリケーションを起動します：

```
streamlit run pic_to_header/app.py
```

2. ブラウザで表示されるURLにアクセスします。

3. 入力画像とマスク画像をアップロードします。

4. "ヘッダー画像を生成"ボタンをクリックします。

5. 生成されたヘッダー画像をプレビューし、必要に応じてダウンロードします。

### コマンドラインインターフェース (CLI)

CLIを使用して画像を処理することもできます：

```
pic-to-header input_image.png mask_image.png output_image.png
```

例：

```
pic-to-header assets/sample.png assets/mask.png output_image.png
```

## 💻 開発

- `pic_to_header/core.py`: 画像処理の主要な機能を含みます。
- `pic_to_header/app.py`: Streamlitを使用したWebインターフェースを提供します。
- `pic_to_header/cli.py`: コマンドラインインターフェースを提供します。

## 📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細については、[LICENSE](LICENSE)ファイルを参照してください。
