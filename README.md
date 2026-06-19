# Notedekasegu

X投稿・無料note・有料noteの動線を、Claude Codeの複数エージェント（部隊）で運用するための構成。

## 構成

```
.
├── CLAUDE.md           会社全体の方針ファイル
├── agents/             各部隊の役割定義
│   ├── buzz_post.md      Xバズポスト作成部隊
│   ├── engagement.md     X交流部隊
│   ├── free_note.md      無料note作成部隊
│   └── paid_note.md      有料note作成部隊
├── outputs/             各部隊の出力置き場
└── materials/           素材・参考情報置き場
```

## 使い方

各部隊に素材を渡して出力を得る。詳細は `agents/` 配下の各ファイルと `CLAUDE.md` を参照。
