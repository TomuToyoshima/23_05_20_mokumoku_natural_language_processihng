# 23_05_20_mokumoku_natural_language_processing
DSL主催の主催の「現場で使えるPython自然言語処理」のもくもく会用のリポジトリになります．
# 概要
日程
4/22（土）〜5/9（火） 20:00〜21:00

# 扱う図書
『現場で使える python自然言語処理入門』

参加方法
このGoogle フォームから申し込みをお願いします！途中参加も大歓迎です！ [Google Form]:(https://forms.gle/K6sQiSTV3EunrLSv9)

参加申し込み確認後、Slackチャンネルに招待します。

【参考資料】
GitHubアカウント作成方法 https://qiita.com/ayatokura/items/9eabb7ae20752e6dc79d
GitHubのフォークからプッシュまで https://docs.github.com/ja/get-started/quickstart/fork-a-repo
今日のスライド
【GitHub設定手順】
GitHubでDSLの今回のリポジトリを検索（URL：https://github.com/Data-Science-League/23_04_22_Essence-of-Machine-learning.git）
画面右上の「fork」からforkする
クローンする：git clone https://github.com/[GitHubユーザー名]/23_04_22_Essence-of-Machine-learning.git
クローンしたフォルダ内に移動：cd [クローンしたフォルダ名]
upstream登録する：git remote add upstream https://github.com/Data-Science-League/23_04_22_Essence-of-Machine-learning.git
git remote -v で確認。以下のようになっていればOK。
origin https://github.com/[GitHubユーザー名]/23_04_22_Essence-of-Machine-learning.git (fetch)
origin https://github.com/[GitHubユーザー名]/23_04_22_Essence-of-Machine-learning.git (push)
upstream https://github.com/Data-Science-League/23_04_22_Essence-of-Machine-learning.git (fetch)
upstream https://github.com/Data-Science-League/23_04_22_Essence-of-Machine-learning.git (push)

フォルダを作成し、その中に何かファイルを作る
git add .
git commit -m '[コミットメッセージ（日付 何ページまで進んだか 名前）]'
git push origin main
自分のGitHubページの今イベントのリポジトリに行き、「Pull requests」→「New pull request」→「Create pull request」→「Create pull request」 ※pushするものは自分の名前をフォルダ名にして一つにまとめてpushしてください
【初回参加時にやること】

GitHubの設定を行う
本を進める
GitHubにpushしてpull requestを出す
