.. article::
   :date: 2014-05-21 14:00:00

Python 2.7.7 rc1 リリース
=============================




Python 2.7.7 のリリース候補 `Python 2.7.7rc1 <https://www.python.org/download/releases/2.7.7/>`_ が公開されました。このリリースでの修正内容は、`Misc/Newsファイル <http://hg.python.org/cpython/raw-file/e32e3a9f3902/Misc/NEWS>`_ で確認できます。

このリリースでは、セキュリティホールとなる可能性がある、潜在的な問題を2件修正しています。一つは `jsonモジュール <https://docs.python.org/ja/2.7/library/json.html>`_ の `JSONDecoder` による不正なメモリアクセスで、もう一件は `stringモジュール <https://docs.python.org/ja/2.7/library/string.html>`_ から呼び出される、`strop` モジュールの不具合です。
