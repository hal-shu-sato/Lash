# オート（自動）モデレーション
## コマンド
automod
## 機能
条件に合わせて自動でMute・Kick・BANをする機能
役職設定は全自動で行う
## 基準
- 連投[quicksend]
- 同じ文字・単語の連続[spam]
- メンション乱用[massmention]
- NGワード（NG共有ワード）[ngword] [ngshare]
- サーバー招待リンク[invite]
- リンク[link]
- 絵文字乱用[massemoji]
- 全員宛メンション[ateveryone]（無権限者のみ削除）
## コマンド構文
これらを専用構文で設定できるようにする
```
<基準名> <回数> <処分> [時間]
```
例:
```
quicksend 10 mute 10m
```
## 処分
- delete
-  mute
-  kick
-  ban