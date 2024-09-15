# About
この資料では、各ディレクトリとファイルの役割を記載する。

## ディレクトリ構造
```
discord-gpt
├─.github
│  ├─workflows
│  │  └─ci.yaml
│  └─pull_request_template.md
├─.vscode
│  └─settings.json
├─src
│  ├─modules
│  │  ├─ai
│  │  │ ├─chat.py
│  │  │ └─image.py
│  │  └─discord
│  │     └─commands.py
│  ├─tests
│  │  ├─conftest.py
│  │  └─test_main.py
│  └─main.py
├─.env
├─.gitignore
├─.pylintrc
├─design.md
├─pytest.ini
└─requirements.txt
```