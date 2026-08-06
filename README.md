# Mashroom サポート／プライバシー（GitHub Pages 用）

TrailTune（GPX）と同じ考え方で、App Store Connect に貼る公開ページです。

## ファイル

| ファイル | 用途 | App Store Connect |
|----------|------|-------------------|
| `index.html` | アプリ説明・サポート | **サポートURL** |
| `privacy.html` | プライバシーポリシー | **プライバシーポリシーURL** |

お問い合わせメール: `appnameshin@gmail.com`（TrailTune と同じ）

## 公開方法（おすすめ）: GitHub Pages

### A. 専用リポジトリ（いちばん簡単）

1. GitHub でリポジトリ作成（例: `mashroom-support`、Public）
2. このフォルダの中身を **リポジトリ直下** に置く  
   （`index.html` と `privacy.html` がルートにある状態）
3. Settings → Pages  
   - Source: Deploy from a branch  
   - Branch: `main` / `/ (root)`  
4. 数分後の URL 例:

```
サポート:     https://name-shintaro.github.io/mashroom-support/
プライバシー: https://name-shintaro.github.io/mashroom-support/privacy.html
```

（GitHub ユーザー名が違う場合は置き換えてください）

### B. 本リポジトリの docs を使う場合

1. GitHub に `mashroom` リポジトリを push
2. Settings → Pages  
   - Source: Deploy from a branch  
   - Branch: `main` / `/docs`  
3. さらに `docs/support` をルートにしたい場合は、Pages のフォルダ設定か、専用リポジトリ（A）の方が確実です。

**審査用には A（専用リポジトリ直下に HTML）を推奨します。**

## App Store Connect への貼り方

1. アプリ → App 情報 / アプリのプライバシー  
2. サポートURL → `.../mashroom-support/`  
3. プライバシーポリシーURL → `.../mashroom-support/privacy.html`

## ローカル確認

```bash
open /Users/nameshin/mashroom/docs/support/index.html
open /Users/nameshin/mashroom/docs/support/privacy.html
```
