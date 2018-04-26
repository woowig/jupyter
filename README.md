# woowig/jupyter

Jupyter Notebookが動くDockerイメージ。

使い方
------

```sh
docker run -it --rm -v $HOME/Documents/notebooks:/data -p 8888:8888 woowig/jupyter
```

等を実行した後、 `http://localhost:8080` を開きます。
