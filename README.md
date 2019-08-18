# pythondiary

## 專案介紹

我就是想做個網站!!!

## 成品展示

![](https://github.com/grand-coder/pythondiary/raw/master/index.png)

## 使用技術

工具名稱 | 用途
---------|----------
Python 3 | 不需要解釋
Flask(python)    | 幫助我建立伺服器
HTML/CSS  | 網頁表示和排版
Heroku   | 託管網頁
Github   | 存放原始碼

## 程式碼片段

.. code-block:: python

    from flask import Flask

    app = Flask(__name__)

    @app.route("/")
    def hello():
        return "Hello, World!"
