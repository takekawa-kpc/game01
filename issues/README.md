# Issues 一覧

`spec.md` から分解した issue 一覧です。

## v1 実装(§2–§5 に対応)

| # | タイトル | ファイル |
| --- | --- | --- |
| 001 | 盤面とピース定義 | [001-board-tetromino.md](./001-board-tetromino.md) |
| 002 | 落下(ゲームループ) | [002-game-loop.md](./002-game-loop.md) |
| 003 | 移動と回転 | [003-move-rotate.md](./003-move-rotate.md) |
| 004 | ソフトドロップ / ハードドロップ | [004-soft-hard-drop.md](./004-soft-hard-drop.md) |
| 005 | ライン消しとアニメーション | [005-line-clear.md](./005-line-clear.md) |
| 006 | スコアとレベル(速度アップ) | [006-score-level.md](./006-score-level.md) |
| 007 | 次のピースとホールド | [007-next-hold.md](./007-next-hold.md) |
| 008 | ポーズとゲームオーバー | [008-pause-gameover.md](./008-pause-gameover.md) |
| 009 | ハイスコアの永続化 | [009-highscore.md](./009-highscore.md) |
| 010 | UI / デザインとアクセシビリティ | [010-ui-a11y.md](./010-ui-a11y.md) |

## 将来の機能(§8 ロードマップに対応)

| # | タイトル | ファイル |
| --- | --- | --- |
| 011 | ゴーストピース | [011-ghost-piece.md](./011-ghost-piece.md) |
| 012 | ウォールキック | [012-wall-kick.md](./012-wall-kick.md) |
| 013 | 反時計回り回転とキーカスタマイズ | [013-ccw-keys.md](./013-ccw-keys.md) |
| 014 | サウンド / BGM | [014-sound.md](./014-sound.md) |
| 015 | コンボ / スペシャルボーナス | [015-combo-bonus.md](./015-combo-bonus.md) |
| 016 | 統計と結果画面 | [016-stats.md](./016-stats.md) |
| 017 | 難易度モード | [017-difficulty-modes.md](./017-difficulty-modes.md) |
| 018 | オンラインランキング | [018-leaderboard.md](./018-leaderboard.md) |
| 019 | モバイル / タッチ操作 | [019-touch-mobile.md](./019-touch-mobile.md) |
| 020 | DAS / ARR 入力カスタマイズ | [020-das-arr.md](./020-das-arr.md) |
| 021 | テーマとカラーカスタマイズ | [021-themes.md](./021-themes.md) |
| 022 | 多言語対応(日本語 / 英語) | [022-i18n.md](./022-i18n.md) |

## Issue の書式

```markdown
# <番号>: <タイトル>

**ラベル**: <ラベル>
**関連仕様**: spec.md §<章>

## 概要
<1-3 行で何をする issue か>

## 要求
- [ ] <チェック可能な要求項目>

## 検収基準
- [ ] <完了時に満たすべき検証項目>
```
