# -
掲示板サイトの作成を行いました。
ファイルは現在以下の9ファイルで構成されています。

・home.php
ホームのページ。新規登録ページやログインページへの導線がある。
・new.php
新規登録を行うページ。
・infomation.php
新規登録ページ後、確認のための会員情報を表示。
・rogin.php
ログイン情報を記入するページ。
・again_new.php
新規登録の場合、すでにあるユーザー情報と
ユーザーネーム、パスワードの両方が一致すると遷移するペーシ。
再登録を促す。
・again_rogin.php
ログインの場合、入力情報が誤っていると遷移するページ。
再ログインor再登録を促す。
・write.php
掲示板への書き込みを行うページ。
・look.php
掲示板の閲覧を行うページ。投稿されたデータが保存されている。データベースへの接続必須。
・manager.php
管理者用ページ。ここに会員情報を保存している。指定したユーザーネームとパスワードを入力しないと閲覧不可。
データベース接続必須。

＊データベースの情報はあらかじめ削除しています。
