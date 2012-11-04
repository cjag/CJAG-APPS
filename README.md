CJAG-APPS
=========

日本アンドロイドの会中国支部の何かのアプリ

* cloneする時の注意
外部参照のActionBarSherlockも一緒にcloneする場合は、下記のように--recursiveオプションをつけてください。
<pre>
$ git clone --recursive リポジトリ
</pre>

もし、
<pre>
$ git clone リポジトリ
</pre>
した後にActionBarSherlockのプロジェクトを取り込みたい場合は下記のようにしてください。
<pre>
$ git submodule init
$ git submodule update
</pre>
