# revit-sp-tools

A single-file browser-based tool for managing Revit Shared Parameter Files (SPF).  
No installation, no server required — open the HTML file directly in your browser.

Revit 共有パラメータファイル（SPF）を管理するブラウザベースのツールです。  
インストール不要・サーバー不要 — HTMLファイルをブラウザで直接開くだけで使えます。

---

## Features / 機能

### 📊 Viewer
- Load and parse Revit Shared Parameter files (UTF-16LE/BE, UTF-8)
- Summary cards: parameter count, group count, data types, visibility, editability
- Sortable / filterable parameter table
- Charts: parameters per group, data type distribution, flag summary

---

- 共有パラメータファイルの読み込み・解析（UTF-16LE/BE、UTF-8対応）
- サマリーカード：パラメータ数・グループ数・データ型・表示設定・編集設定
- ソート・絞り込み対応のパラメータテーブル
- グラフ表示：グループ別パラメータ数、データ型分布、フラグ集計

### 🔀 Diff
- Compare two SPF files side by side
- Detects Added / Removed / Changed / Unchanged parameters
- Filter by diff status via summary cards
- Export diff results as HTML or CSV

---

- 2つのSPFファイルの差分比較
- 追加・削除・変更・変更なし のステータス検出
- サマリーカードクリックでステータス絞り込み
- 差分結果をHTML・CSVでエクスポート

### ✏️ Editor
- Edit DESCRIPTION fields inline (expand on focus)
- Add / Delete parameters with GUID auto-generation
- ChangeLog panel: tracks all edits with timestamp, user, field, old/new values
- Save as `filename_YYYYMMDD.txt` + simultaneous `filename_YYYYMMDD_ChangeLog.html`
- EN / JP UI toggle

---

- DESCRIPTIONフィールドのインライン編集（フォーカスで展開）
- パラメータの追加・削除、GUID自動生成
- 変更履歴パネル：タイムスタンプ・ユーザー・フィールド・変更前後を記録
- `ファイル名_YYYYMMDD.txt` + `ファイル名_YYYYMMDD_ChangeLog.html` を同時保存
- EN / JP UI切り替え

---

## Usage / 使い方

1. Download `sp-tools.html`
2. Open in Chrome or Edge
3. Load your `.txt` Shared Parameter file via drag & drop or file picker

---

1. `sp-tools.html` をダウンロード
2. Chrome または Edge で開く
3. 共有パラメータファイル（`.txt`）をドラッグ＆ドロップまたはファイル選択で読み込む

---

## Requirements / 動作環境

- Browser: Chrome or Edge (recommended)
- No internet connection required after download
- No dependencies — all libraries are self-contained

---

- ブラウザ：Chrome または Edge（推奨）
- ダウンロード後はオフラインで動作
- 外部依存なし — 必要なライブラリはすべて同梱済み

---

## Target Users / 対象ユーザー

MEP / BIM engineers working with Autodesk Revit,  
particularly those managing shared parameter files for Japanese building projects (BLCJ / RUG conventions).

RevitでMEP・BIM業務を行うエンジニア。  
特に日本の建築プロジェクト（BLCJ・RUG規約）に準拠した共有パラメータ管理を行う方を想定しています。

---

## License

MIT — see [LICENSE](LICENSE)
