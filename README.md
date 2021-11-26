# yellowbrick-example

機械学習の可視化ライブラリー(yellowbrick) のexample リポジトリです。

## リポジトリ構成

```
.
├── Dockerfile
├── README.md
├── data
├── docker-compose.yml
├── docs
├── models
├── notebooks
│   ├── bbengfort
│   │   ├── classifiers.ipynb
│   │   ├── cluster.ipynb
│   │   └── cooks_distance.ipynb
│   ├── clustering_visualizers.ipynb
│   ├── gokriznastic
│   │   ├── Iris\ -\ clustering\ example.ipynb
│   │   └── silhouette-visualizer-test.ipynb
│   ├── regression_visualizers.ipynb
│   └── walkthrough.ipynb
├── pyproject.toml
├── requirements.txt
├── setup.cfg
├── src
├── tests
│   └── __init__.py
└── work
```

## 環境詳細

- Python : 3.9.6

## 事前準備

- Docker インストール

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/yellowbrick-example）

```
cd Desktop/yellowbrick-example
```

- Dockerによる環境構築（フォルダをマウント：Desktop/yellowbrick-example）

```
docker-compose up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## Display notebooks

- [View Jupyter notebooks in nbviewer](https://nbviewer.jupyter.org/github/ykato27/yellowbrick-example/tree/main/notebooks/)

## 動作環境

マシンスペック（Mac)

- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
