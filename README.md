# 東京の電気・ガス料金比較（GitHub Pages）

20A/30A判定、電気・ガス使用量入力、各社の単品料金・セット割込み総額を比較するサイトです。

## `hippop81` のGitHub Pagesで公開する方法

1. `hippop81` で https://github.com/new を開き、`tokyo-energy-compare` という **Public** リポジトリを作成。`Add a README file` にチェックするとアップロード操作が簡単です。
2. 作成したリポジトリの **Add file → Upload files** で、同梱の `index.html` を選んでアップロードし、**Commit changes**。
3. リポジトリの **Settings → Pages → Build and deployment** で **Deploy from a branch**、ブランチ **main**、フォルダ **/(root)** を選んで **Save**。
4. 公開後のURL： https://hippop81.github.io/tokyo-energy-compare/

`index.html` はリポジトリ直下に置いてください。フォルダ内の `index.html` やZIPファイルのままではトップページに表示されません。

## 注意

- 公開ページとリポジトリは誰でも見られます。秘密の情報は置かないでください。
- 計算はブラウザ内で完結します。サーバーへの入力値送信はありません。
- 料金は2026年10月28日時点の比較用モデルです。燃料費・原料費調整額・キャンペーン等は変化します。サイト内の「計算条件と出典」を必ず確認してください。
- アンペア判定は家電の概算ワット数から考える目安で、設備や瞬間的な最大電力まで保証するものではありません。
