# 生成物

生成出力と納品物をここに置きます。

## スクリーンショット

MVP セットは次で再生成します:

```bash
python3 tools/capture_mvp_screenshots.py
```

- `screenshots/mvp-initial.png`: onboarding / repo 登録 panel を含む初期村画面の Godot runtime capture。
- `screenshots/mvp-settings.png`: Settings panel の review capture。QA env を使い、実ローカル repo path は表示しません。
- `screenshots/mvp-registered.png`: 合成 demo repo 名を使った、任意登録 Git repo 表示の review。
- `screenshots/mvp-grown.png`: manifest-driven state overlay を示す合成 grown-state capture。dummy placeholder assets を使います。
- `screenshots/mvp-growth-effect.png`: Claude Code session / turn event による一時的な工房と花 effect を示す runtime capture。短い effect が見えるよう AVI の中間 frame から抽出しています。
