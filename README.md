# BCCD_OBJECT_DETECTION

細胞検知モデルの作成を行うチュートリアルスクリプト

なんどもファインチューニングすることを見据えて [W&B](https://www.wandb.jp/) 上で実験管理するようにしている

## 参考 & 引用
- BCCD データセット : https://github.com/Shenggan/BCCD_Dataset
- huggingface サンプルコード : https://huggingface.co/docs/transformers/ja/tasks/object_detection
- W&B ガイド : https://docs.wandb.ai/ja/guides/artifacts/download-and-use-an-artifact

## スクリプト
### 01_データ準備.ipynb

データのダウンロードと学習用データとして利用するために整形する

### 02_ファインチューニング.ipynb

データの前処理～モデルのダウンロード～ファインチューニングを行う
