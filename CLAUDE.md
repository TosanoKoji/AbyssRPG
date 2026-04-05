# ABYSS RITE — 奈落の儀式 開発メモ

ブラウザゲーム（単一HTML + data.json）。GitHub Pages でホスト。
プレイURL: https://tosanokoji.github.io/AbyssRPG/

## 開発ルール（絶対守る）
- confirm() / alert() は使わない → showInlineAlert() で代替
- 動的生成ボタンは必ず createElement + addEventListener
- 作業完了後は必ずpush: git add -A && git commit -m "説明" && git push

## Notionマスターデータ
引き継ぎメモ: https://www.notion.so/336385f8380381238614f742d3cced0c
管理ページ: https://www.notion.so/336385f8380381eea24ed870ef82fb50

## 現在の実装状況（2026-04-05）
- キャラ8種 / 武器9種 / 防具6種 / アクセサリ10種
- アクティブスキル10種 / パッシブスキル10種 / ユニークスキル19種
- ステージ9種（地下1〜5階、地上、空中都市、宇宙、地獄）
- 達成報酬22件

## localStorageキー
abyss_souls, abyss_exp, abyss_totallv, abyss_cleared,
abyss_unlocked, abyss_lvbonus, abyss_achstats, abyss_achdone,
abyss_unique, abyss_system, abyss_encounter, abyss_last_run, abyss_lost_souls
