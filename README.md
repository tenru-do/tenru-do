# tenru-do apps

Rokidグラス向けの実験アプリを、目的別に探しやすくまとめています。

## すぐ試せるAPK

| アプリ | できること | ダウンロード | 詳細 |
| --- | --- | --- | --- |
| 電脳無能妖精ロキ / Roki | Rokidグラス上に小さな妖精を常駐表示するオーバーレイアプリ | [Roki-v0.1.8-debug.apk](https://raw.githubusercontent.com/tenru-do/dennou-munou-yousei-roki/main/dist/Roki-v0.1.8-debug.apk) | [README](https://github.com/tenru-do/dennou-munou-yousei-roki) |

インストール例:

```powershell
adb install -r Roki-v0.1.8-debug.apk
```

## ビルドして使うアプリ

現在、下のアプリはGitHub ReleasesにAPKを置いていません。使う場合は各リポジトリを開き、READMEの手順でAndroid StudioまたはGradleからビルドしてください。

| アプリ | できること | 入手先 | 状態 |
| --- | --- | --- | --- |
| Rokid GoBe Bridge | HEALBE GoBeの健康データをスマホからRokidグラスへ送るローカルブリッジ | [リポジトリ](https://github.com/tenru-do/rokid-gobe-bridge) | ビルドが必要 |
| Rokid Steps Overlay | スマホの歩数をRokidグラス右上に表示する軽量オーバーレイ | [リポジトリ](https://github.com/tenru-do/rokid-steps-overlay) | ビルドが必要 |
| Rokid AI Input Bridge | Rokidグラスでキーボード入力やGemini応答を使う実験アプリ群 | [リポジトリ](https://github.com/tenru-do/rokid-ai-input-bridge) | プロトタイプ、手動ビルドが必要 |

## その他

| リポジトリ | 内容 |
| --- | --- |
| [VBA_Module](https://github.com/tenru-do/----) | Excel VBA関連モジュール |
| [github-slideshow](https://github.com/tenru-do/github-slideshow) | GitHub学習用リポジトリ |

## 公開時のおすすめ整理

Androidアプリは、各リポジトリの **Releases** にAPKを置くと、利用者が一番迷いません。

おすすめの置き方:

1. APKを `app-name-vX.Y.Z-debug.apk` または `app-name-vX.Y.Z.apk` の名前で作る
2. GitHubの各リポジトリで **Releases** を開く
3. `v0.1.0` のようなタグを作る
4. APKを添付する
5. READMEの一番上に `Download latest APK` リンクを置く

現状では、Rokiだけが直接APKをダウンロードできます。ほかのRokid系アプリもAPKをReleaseに追加すると、このプロフィールからさらにわかりやすく案内できます。
