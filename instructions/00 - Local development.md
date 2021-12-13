# ローカルコンピューターの環境セットアップ

ローカルコンピューターで作業をしている場合は、以下の手順でラボを利用できるように環境を設定できます。

## C++ のインストール

1. [Visual C++ Redistributable (x64)](https://aka.ms/vs/16/release/vc_redist.x64.exe)をダウンロードしインストールしてください。

## Pythonおよび必要なパッケージのインストール

1. [Python 3.6.1](https://www.python.org/downloads/release/python-361/)をインストールしてください。
   - **重要**: PATH変数にPythonを追加し、Pythonのデフォルト環境として登録するためのオプションを選択します。
2. インストール後、**コマンドプロンプト**を開き、以下のコマンドを入力して必要なパッケージをインストールします。

> pip install ipython jupyter matplotlib pillow requests azure-cognitiveservices-vision-computervision azure-cognitiveservices-vision-customvision azure-cognitiveservices-vision-face azure-cognitiveservices-language-textanalytics azure.cognitiveservices.speech azure_ai_formrecognizer

## Visual Studio Code

1. まだVisual Studio Codeをお持ちでない場合は、 [こちらかダウンロードしてください](https://code.visualstudio.com/Download)。インストール後、Visual Studio Codeを起動し、「拡張機能」タブ（CTRL+SHIFT+X）で、Microsoft社の**Python**拡張機能を検索してインストールしてください。

2. Visual Studio Codeで新しいターミナルを開き、以下のコマンドを入力して*Enterキー*を押下してください。

> git clone https://github.com/MicrosoftLearning/mslearn-ai900
