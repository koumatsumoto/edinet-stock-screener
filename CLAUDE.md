# CLAUDE.md

このファイルは、このリポジトリで Claude Code (claude.ai/code) が作業する際のガイダンスを提供します。

## プロジェクト概要

金融庁の EDINET API を活用し、有価証券報告書から財務データを取得・分析して割安株を発見する Python ツール。財務指標の自動計算、時系列分析、業界比較、バリュー・グロース投資戦略に対応したカスタマイズ可能なスクリーニング機能を提供。

## 開発環境

pyproject.toml で管理される Python 3.12+プロジェクト

### アプリケーション実行

```bash
python main.py
```

### Python 環境

- Python 3.12+が必要（pyproject.toml で>=3.12 を指定）
- pyproject.toml で依存関係を管理
- 現在外部依存関係は未定義

## プロジェクト構造

- `main.py` - 基本的な Hello World 機能を持つエントリーポイント
- `pyproject.toml` - プロジェクト設定と依存関係
- `README.md` - 日本語でのプロジェクト説明

## Git 操作ルール

### Commit 方法

Conventional Commits の仕様に基づいて git commit する。

- 英語で記述する
- 一行目に `<type>: <description>` の形式で概要を書く
- 三行目に具体的な作業内容を書く

例:

```
feat: implement user authentication API

- Add JWT token generation and validation
- Create user login and registration endpoints
```
