## 戦闘システム

オーソドックスなRPGにいろいろ追加したもの

---

#### リンク集
- [キャラステータス](battle/status.html)
- [スキル](battle/skill.html)
- [キャラクター一覧](battle/charactor-list.html)

#### ターンの流れ

こんな感じ。ごちゃごちゃやなぁ。

``` mermaid
graph TB
    戦闘開始 --> コマンド選択
    コマンド選択 --> スキル選択
    スキル選択 -- 対象指定スキルの場合 --> 対象選択
    スキル選択 --> コマンド選択
    対象選択 -- 未操作キャラが居る --> コマンド選択
    対象選択 -- 待機 --> 技発動
    技発動　-- 後隙　--> コマンド選択
```

キー操作
- 





