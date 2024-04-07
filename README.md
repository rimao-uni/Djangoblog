Pythonで実装されたWebアプリケーションフレームワークであるDjangoを使って練習のため簡易的なブログ管理ツールを構築した。

adminサイトからブログを投稿し、フロントページに表示できるようにした。フロントページと詳細ページにはCSSフレームワーク「Bulma」を使用した。

ブログの詳細ボタンを押すと詳細ページに飛び、記事の詳細が表示され、また、ページ遷移なしで他のユーザがコメントを追加できるようにした。

データベースには標準のSQLiteを使用した。

Requirement
```
asgiref==3.6.0
dj-database-url==1.2.0
Django==4.1.5
django-heroku==0.3.1
gunicorn==20.1.0
psycopg2==2.9.5
sqlparse==0.4.3
whitenoise==6.3.0
```
