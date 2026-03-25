# Work Log

## 2026-03-26

- 画像エディタの「サイズ」操作を改善。
- フォントサイズをスライダーと数値入力の両方で変更できるようにし、相互同期を追加。
- JPEG 書き出し時のファイル名を、重ねるテキストをベースに生成するように変更。
- 保存に使えない文字はファイル名から除外し、空の場合は `image-draft-<timestamp>.jpg` を使用。

## Published Commits

- `ea99600` Add numeric font size control
- `a3562e7` Use overlay text for export filenames
