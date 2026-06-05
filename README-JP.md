[EN](README.md) | [JP](README-JP.md)

# Machine Learning Examples for Computer Vision

コンピュータビジョンのための機械学習サンプルコードおよびリファレンス実装集

## はじめに

1. 「Open in Colab」ボタンをクリックします。
2. Google Colabでノートブックを開きます。
3. (オプション)「ランタイム」→「ランタイムのタイプを変更」→「GPU」を選択します。
4. 「すべてのセルを実行」を選択します。
5. 必要に応じて画像をアップロードします。


## [YOLO (You Only Look Once)](https://github.com/ultralytics/ultralytics)

画像全体に対して ImageNet の 1000 カテゴリの中から 1 つのラベルを割り当てます。  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) Classification](https://colab.research.google.com/github/mastnk/cv-samples/blob/main/yolo/yolo_classification_JP.ipynb)

画像内の複数の物体を検出し、バウンディングボックスと信頼スコアを描画します。  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) Detection](https://colab.research.google.com/github/mastnk/cv-samples/blob/main/yolo/yolo_detection_JP.ipynb)

物体を検出し、各物体の形状をピクセル単位のマスクで描画します。  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) Segmentation](https://colab.research.google.com/github/mastnk/cv-samples/blob/main/yolo/yolo_segmentation_JP.ipynb)

人物を検出し、関節や顔のランドマークなど身体のキーポイントを推定します。  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) Pose](https://colab.research.google.com/github/mastnk/cv-samples/blob/main/yolo/yolo_pose_JP.ipynb)


## [Depth Anything](https://github.com/DepthAnything/Depth-Anything-V2)

1 枚の画像からピクセルごとの深度を推定し、カラーマップで可視化します。  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) Depth Anything](https://colab.research.google.com/github/mastnk/cv-samples/blob/main/depth/depth_anything_JP.ipynb)

## [Insight Face](https://github.com/deepinsight/insightface)

顔を検出し、各顔のバウンディングボックス・ランドマーク・年齢・性別を推定します。  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) InsightFace](https://colab.research.google.com/github/mastnk/cv-samples/blob/main/face/insightface_JP.ipynb)

## [BLIP (Bootstrapping Language-Image Pre-training)](https://github.com/salesforce/BLIP)

画像の内容とコンテキストを説明する自然言語キャプションを生成します。  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) BLIP](https://colab.research.google.com/github/mastnk/cv-samples/blob/main/blip/blip_JP.ipynb)
