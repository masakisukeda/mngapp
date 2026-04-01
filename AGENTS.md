# AGENTS.md (予実.app / mng)

このフォルダを触る AI / 自動化ツール向けの「最初に読む」メモです。

## 0. 共通ルール（最優先）
- 共通指示書: `/Users/masakisukeda/Library/CloudStorage/GoogleDrive-masaki.sukeda@gmail.com/マイドライブ/Playground/AGENTS.md`
- スコープは `/app` `/chat` `/dic` `/mng` のみ。無関係フォルダの編集・デプロイは禁止。
- **このフォルダ以外へ絶対にデプロイしないこと**。
- デプロイはFTP経由。`/mng` 以外へアップロードしないこと。

## 1. 対象
- 公開URL: `https://drsp.cc/mng/mng.html`
- 主要実装:
  - `index.html`（本体）
  - `mng.html`（`index.html` へのリダイレクト）
  - `manual.html`（運用マニュアル）
  - `lp/index.html`（LP）

## 2. 作業ルール
- 変更は最小差分。
- 既存の運用フロー（GAS接続・保存・固定化）の導線は維持。
- KPI表示・比較表・入力フォームの文言は、運用者目線で一貫性を保つ。
- `index.html` は1ファイル集約型のため、編集箇所の前後文脈を崩さない。

## 3. 反映前チェック
- 画面確認:
  - `index.html`
  - `manual.html`
  - `lp/index.html`
- リンク確認:
  - `/mng/index.html`
  - `/mng/mng.html`
  - `/mng/manual.html`
  - `/mng/lp/`

## 4. NG
- 無関係な全体リデザイン。
- 導入手順の文言や順序を根拠なく変更。
- 反映手順未確認での完了報告。
