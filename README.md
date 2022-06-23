## Anaconda3_vscode_win

### Python実習用の環境構築

#### VSCodeからの操作
1. 画面左下の緑背景アイコンをクリックし、メニューから「Reopen in Container」を選択
2. 作りたい環境を選択（Anaconda / Miniconda / Python / ...）
 -- Anaconda / Node.js=16 / 選択なし
3. Dockerfileの編集
 -- OSライブラリ（apt-get）、Pythonライブラリ(pip)を追加

<p>.devcontainer<br>
　┣ devcontainer.json　　　　　　※主にVSCodeでの設定（拡張機能など）を記述する<br>
　┗ Dockerfile　　　　　　　　　※コンテナ自体の設定</p>
