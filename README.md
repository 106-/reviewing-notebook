# reviewing-notebook

Jupyter Notebookによるプログラミングは試行錯誤しながら行うには最適の環境ですが、一方で読みにくいコードを量産する原因にもなります。

そこでこのリポジトリではコーディング規約を用意し、それに反するような物があればLLMに怒られる仕組みを作ります。

Jupyter Notebook用にコーディング規約を作ろうとしても結局はPython用のものとほぼ同等になってしまいそうだったので、できるだけNotebookに固有な書き方をあげつらうこととします。

あまりきつく縛りたくはないので、心構え的なものだと考えてください。

# 見るべき点

- **主な成果物:** [ci.yml](https://github.com/106-/reviewing-notebook/blob/main/.github/workflows/ci.yml)

- **結果の例:** [#3](https://github.com/106-/reviewing-notebook/pull/3#issuecomment-2875087562)