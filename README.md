# Baseline-model-for-CNN---P1
A simple model based on CNN architecture. Data : CIFAR10
# 🖼️ CIFAR-10 Image Classification with Deep Learning

Ushbu loyiha CIFAR-10 datasetidan foydalanib, rasmlarni klassifikatsiya qilish uchun chuqur o‘rganish (Deep Learning) modelini yaratishga qaratilgan. Loyiha PyTorch yordamida amalga oshirilgan va model treningdan o‘tkazilib, natijalari baholangan.

## 📌 Loyiha haqida

Loyihaning asosiy maqsadi — 10 ta turli kategoriya bo‘yicha rasmlarni avtomatik aniqlash (classification) modelini yaratish.

## 📂 Dataset

CIFAR-10 dataset:

* 60,000 ta 32x32 o‘lchamli rangli rasmlar
* 10 ta klass:

  * airplane
  * automobile
  * bird
  * cat
  * deer
  * dog
  * frog
  * horse
  * ship
  * truck

## ⚙️ Ishlatilgan texnologiyalar

* Python 🐍
* PyTorch 🔥
* Torchvision
* NumPy
* Matplotlib

## 🏗️ Pipeline (Jarayon)

### 1. Ma’lumotlarni yuklash

* CIFAR-10 dataset yuklanadi
* Train va test setlarga bo‘linadi

### 2. Preprocessing

* Normalization
* Tensor formatga o‘tkazish
* Batch qilish (DataLoader)

### 3. Model arxitekturasi

* Convolutional Neural Network (CNN)
* Conv layerlar
* Pooling layerlar
* Fully connected layer

### 4. Trening

* Loss function: CrossEntropyLoss
* Optimizer: Adam yoki SGD
* Epochlar bo‘yicha o‘qitish

### 5. Baholash

* Test datasetda tekshirish
* Accuracy hisoblash

## 🚀 Ishga tushirish

### 1. Repository’ni klon qilish

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Kutubxonalarni o‘rnatish

```bash
pip install torch torchvision numpy matplotlib
```

### 3. Notebook’ni ishga tushirish

```bash
jupyter notebook
```

Ochish:

```
Project3-checkpoint.ipynb
```

## 📊 Natijalar

| Model | Accuracy |
| ----- | -------- |
| CNN   | 83%      |

## 📌 O‘rganilgan narsalar

* Image classification asoslari
* CNN qanday ishlashi
* PyTorch bilan model qurish
* Training va evaluation jarayoni

## 🔮 Kelajakda yaxshilash

* Data augmentation qo‘shish
* Pretrained model (ResNet, VGG) ishlatish
* Hyperparameter tuning
* Modelni deploy qilish

## 👤 Muallif

* Jonibek Abdurahmonov
