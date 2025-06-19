## 🧠 Real-Time Object Detection with YOLO and OpenCV

This project is a simple implementation of real-time object detection using **YOLO (You Only Look Once)** with **OpenCV** in Python. It allows detection of objects from a webcam feed using either `yolov3` or the lightweight `yolov3-tiny` configuration.

### 🚀 Features

* Real-time object detection via webcam
* YOLOv3 and YOLOv3-tiny support
* Easy to run with minimal setup
* Detects 80+ object categories from COCO dataset

### 🗂️ Project Structure

```
├── coco.names               # COCO object class names
├── real_time_yolo.py        # Main script for real-time detection
├── requirements.txt         # Python dependencies
├── yolov3.cfg               # YOLOv3 configuration
├── yolov3-tiny.cfg          # YOLOv3-tiny configuration
└── README.md
```

### 📦 Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/sistem_analiz2_vize.git
   cd sistem_analiz2_vize
   ```

2. Install required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the required weight files:

   * [YOLOv3 weights](https://pjreddie.com/media/files/yolov3.weights)
   * [YOLOv3-tiny weights](https://github.com/smarthomefans/darknet-test/blob/master/yolov3-tiny.weights)

   Place them in the root project folder.

### ▶️ Usage

Run the script with the desired configuration:

```bash
# For full YOLOv3
python real_time_yolo.py --weights yolov3.weights --config yolov3.cfg

# For YOLOv3-tiny (faster, less accurate)
python real_time_yolo.py --weights yolov3-tiny.weights --config yolov3-tiny.cfg
```

### 📌 Notes

* Make sure your webcam is properly connected.
* Accuracy and performance may vary depending on the model you use.

---

## 🧠 YOLO ve OpenCV ile Gerçek Zamanlı Nesne Tespiti

Bu proje, **YOLO (You Only Look Once)** algoritması ve **OpenCV** kullanılarak Python diliyle geliştirilmiş basit bir gerçek zamanlı nesne tespit sistemidir. Webcam üzerinden gelen görüntülerde nesne tespiti yapılmasını sağlar ve hem `yolov3` hem de hafif sürüm olan `yolov3-tiny` yapılandırmalarını destekler.

### 🚀 Özellikler

* Gerçek zamanlı webcam görüntüsü üzerinden nesne tespiti
* YOLOv3 ve YOLOv3-tiny desteği
* Hızlı kurulum ve kolay kullanım
* COCO veri kümesinden 80+ nesne sınıfını algılama

### 🗂️ Proje Yapısı

```
├── coco.names               # COCO nesne sınıfı isimleri
├── real_time_yolo.py        # Ana Python betiği
├── requirements.txt         # Gereken Python paketleri
├── yolov3.cfg               # YOLOv3 yapılandırma dosyası
├── yolov3-tiny.cfg          # YOLOv3-tiny yapılandırma dosyası
└── README.md
```

### 📦 Kurulum

1. Depoyu klonlayın:

   ```bash
   git clone https://github.com/kullanici-adin/sistem_analiz2_vize.git
   cd sistem_analiz2_vize
   ```

2. Gerekli Python paketlerini yükleyin:

   ```bash
   pip install -r requirements.txt
   ```

3. Gerekli ağırlık dosyalarını indirin:

   * [YOLOv3 weights](https://pjreddie.com/media/files/yolov3.weights)
   * [YOLOv3-tiny weights](https://github.com/smarthomefans/darknet-test/blob/master/yolov3-tiny.weights)

   Bu dosyaları proje klasörünün kök dizinine yerleştirin.

### ▶️ Kullanım

```bash
# YOLOv3 için
python real_time_yolo.py --weights yolov3.weights --config yolov3.cfg

# YOLOv3-tiny (daha hızlı, daha düşük doğruluk)
python real_time_yolo.py --weights yolov3-tiny.weights --config yolov3-tiny.cfg
```

### 📌 Notlar

* Webcam'inizin doğru şekilde bağlı olduğundan emin olun.
* Kullanılan modele göre doğruluk ve hız değişiklik gösterebilir.

---

### 👨‍💻 Developer / Geliştirici
**Yusuf Tufan**
