
Ubuntu環境のPython
--------------------------------

`Ubuntu <https://www.ubuntu.com/>`_ には最初から Pythonがインストール済みの状態で提供されており、簡単に Python環境を整えられます。


Ubuntu 16.04 LTS
===========================

Python 3.5/Python 2.7がインストールされており、そのままで利用可能です。

デフォルトでは :jinja:`{{ content.link_to('./pip.rst') }}` がインストールされていませんので、インストールしておきます。

また、Pythonの拡張パッケージをインストールする際に必要となる、開発用パッケージも入れておきましょう。

.. code-block:: console

   $ sudo apt install python3-pip python3-dev
   $ sudo apt install python-pip python-dev


Python 3.6 のインストール
++++++++++++++++++++++++++++++

Python 3.6 を使用する場合は、`Jonathon F さんのプライベートリポジトリ <https://launchpad.net/~jonathonf>`_ からインストールできます。:jinja:`{{ content.link_to('./pip.rst') }}` コマンドは、http://bootstrap.pypa.io よりインストールします。


.. code-block:: console

   $ sudo add-apt-repository ppa:jonathonf/python-3.6
   $ sudo apt-get update
   $ sudo apt-get install python3.6 python3.6-dev python3.6-venv
   $ wget https://bootstrap.pypa.io/get-pip.py
   $ sudo python3.6 get-pip.py


Pythonの実行
+++++++++++++++++++

Python各バージョンは次のコマンドで実行できます。

Python 3.5
    ``python3``、``python3.5``

Python 3.6
    ``python3.6``

Python 2.7
    ``python``、``python2``、``python2.7``




Ubuntu 16.10 以降
===========================

Python 3.5/Python 2.7がインストールされています。Python 3.6も追加インストール可能です。

.. code-block:: console

   $ sudo apt install python3.6


デフォルトでは :jinja:`{{ content.link_to('./pip.rst') }}` がインストールされないので、別途インストールしておきます。

また、Pythonの拡張パッケージをインストールする際に必要となる、開発用パッケージも入れておきましょう。

.. code-block:: console

   $ sudo apt install python3.5-pip python3.5-dev
   $ sudo apt install python-pip python-dev
   $ sudo apt install python3.6-dev
   $ wget https://bootstrap.pypa.io/get-pip.py
   $ sudo python3.6 get-pip.py

Pythonの実行
+++++++++++++++++++

Python各バージョンは次のコマンドで実行できます。

Python 3.5
    ``python3``、``python3.5``

Python 3.6
    ``python3.6``

Python 2.7
    ``python``、``python2``、``python2.7``


