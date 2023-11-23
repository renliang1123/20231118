# 20231118
環境 google colab python
使用的包
pennylane
tensorflow
tensorflow.keras
numpy
硬體
t4 gpu
混合經典卷積神經網絡和量子神經網絡
從CIFAR-100數據集中載入圖片數據，然後只保留類別3和88的圖片
使用tf.keras建立了一個卷積神經網絡模型
定義了一個QNN層，這是一個使用PennyLane的量子神經網絡。這一層將與經典的全連接層組合在一起
這個QNN層的模型是一個含有2個量子比特的量子電路，用於進行量子前向傳播
使用RMSprop優化器編譯了模型
通過model.fit方法進行模型訓練。使用實時數據增強。
