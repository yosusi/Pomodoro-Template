# Stock - タスクバックログ

このファイルは全タスクのバックログを時間軸で管理します。

## タスク記述構文
- 書式: `- [ ] タスク名 [p][p] {due:YYYY-MM-DD}`
- ポモドーロ記号:
  - `p` (小文字): 予定（planned）
  - `P` (大文字): 実績（Performed）
- 締切タグ: `{due:YYYY-MM-DD}` または `{due:NONE}`

---

## Daily
<!-- 毎日行うタスク -->

- [ ] メールチェック [p] {due:NONE}
- [ ] 朝の計画立て [p] {due:NONE}

## Weekly
<!-- 毎週行うタスク -->

- [ ] 週次レビュー [p][p] {due:NONE}
- [ ] チームミーティング準備 [p] {due:NONE}

## Monthly
<!-- 毎月行うタスク -->

- [ ] 月次レポート作成 [p][p][p] {due:NONE}
- [ ] 経費精算 [p] {due:NONE}

## Someday
<!-- いつか実施するタスク -->

- [ ] 新しいツールの調査 [p][p] {due:NONE}
- [ ] ドキュメントの整理 [p] {due:NONE}
