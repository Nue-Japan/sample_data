# sample_data
### 環境作成について
 1. 仮想環境の作成 ： ```python -m venv 仮想環境名 ```
  * 現在最上位にいるpythonのPATHから環境を作成される
 2. 仮想環境を適用 : ``` 仮想環境名/Scripts/Activate ```
 3. 仮想環境内で ``` pip install モジュール名 ``` で必要なライブラリ等をインストールする
 4. ``` pip freeze > requirements.txt ``` インストールしたライブラリを依存パッケージを記述
 - ※ もしファイルを使用する際は、ターミナル上で ``` pip install -r requirements.txt ``` と記述

