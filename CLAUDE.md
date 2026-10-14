# 開発ルール（このプロダクト用）

このリポジトリで作業するときは、先に次の2つを読んでください。
- 共通ルール：https://github.com/jumpbol/dev-rules の「common-rules.md」
- 作業手順：https://github.com/jumpbol/dev-rules の「task-guide.md」

読めない場合は、作業を始めずに、人間にそう伝えてください。
準拠する dev-rules の版：v2（2026-10-14）
（dev-rules の版がこれと違うときは、人間に知らせてください。勝手に合わせないでください。）

## このプロダクトだけの約束
- 製品名：（未記入。依頼文 P1 で AI が書く）
- 設計書の場所：docs/ARCHITECTURE.md
- 進捗メモの場所：docs/ARCHITECTURE.md の「4. 進捗・引き継ぎメモ」
- README：README.md
- ADR の場所：docs/adr/
- レビュー結果の場所：docs/reviews/
- テストの場所：tests/（推測した名前は tests/adapter.* にまとめる）
- CI：.github/workflows/ci.yml
- 既存テストの扱い：tests/ にあり、CI で実行される全件（task-guide「保守運用」の定義）
- 追加で守ること：なし
