# 移動手段の判断
## 教師データ
### 北京GEOLIFEデータについて

> ![Peking Label](./images/1.png)

#### ラベルの時間帯

>![Peking Label](./images/2.png)

#### (左から)緯度、経度、意味ないデータ、意味ないデータ、高さ、日付、時間

>![Peking Compiled CSV](./images/3.png)

####  整形されたCSV、（左から）緯度、経度、日付と時間、速度、加速度、ラベル

> ![Peking Compiled CSV](./images/4.png)

####  最寄り駅分布の追加、（左から）緯度、経度、日付と時間、速度、加速度、ラベル、最寄り駅からの距離

---

### 東京高速車データについて

> ![Tokyo](./images/5.png)

####  整形されたCSV、（左から）速度、加速度、緯度、経度、最寄り駅からの距離、ラベル

### 最後まとめた訓練データ

> ![Tokyo](./images/10.png)

> ![Tokyo](./images/11.png)

> ![Tokyo](./images/12.png)

#### 隣接点の速度と加速度（カラム数が変えられる）、最寄り駅からの距離、検証用ラベル。ランダムフォレストに入れた形
 
---

> ![Tokyo](./images/6.png)

###  北京駅分布

> ![Tokyo](./images/7.png)

###  東京駅分布

## 学習データについて

### ブログウォッチャーからのユーザー位置情報

> ![Tokyo](./images/8.png)

#### データの由来

> ![Tokyo](./images/9.png)

#### データの形

> ![Tokyo](./images/13.png)

> ![Tokyo](./images/14.png)

> ![Tokyo](./images/15.png)

#### 訓練データとの同じ操作で変形した

### 結果の一つ

> ![Tokyo](./images/16.png)

#### 赤（車）、黒（電車）、緑（バイク）、青（歩き）、
