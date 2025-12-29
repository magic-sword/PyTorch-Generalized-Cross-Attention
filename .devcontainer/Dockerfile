# 作成したpytorch  バージョンは最新のものを確認
FROM magicsword0001/pytorch-jupyterlab-gpu:latest
ARG USERNAME=dev
USER $USERNAME

# パッケージの作成に必要
RUN python3.12 -m pip install setuptools twine wheel

# 設定ファイルをホームディレクトリに配置
COPY .devcontainer/.pypirc ~/