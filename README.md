# 🕶️ Meta-Glasses-Photo-Maker

[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## ✨ Proje Amacı

Bu uygulama, herhangi bir JPEG görüntünün **EXIF meta verisini** basitçe değiştirmek için tasarlanmış, bağımsız bir GUI aracıdır.

Instagram veya Facebook gibi platformlar, bir görüntünün meta verisinde belirli kamera üreticisi (`Meta AI`) ve modeli (`Ray-Ban Meta Smart Glasses`) etiketlerini algıladığında, hikayelerde ve gönderilerde otomatik olarak **"Ray-Ban META glasses"** etiketini görüntüler.

Bu uygulama, bu gerekli meta veriyi mevcut fotoğraflarınıza ekleyerek, fotoğraflarınızın Meta akıllı gözlüklerle çekilmiş gibi görünmesini sağlar.

## 🚀 Temel Özellikler

* **Bağımsız GUI:** Tkinter ile oluşturulmuş, basit ve kullanımı kolay arayüz.
* **EXIF Enjeksiyonu:** Gerekli `Maker` (Üretici) ve `Model` etiketlerini doğrudan yazar.
* **Zaman Damgası:** EXIF çekim tarihi/saatini, işleme anının güncel zamanına ayarlar.
* **Farklı Kaydet:** Orijinal dosyayı asla değiştirmez; her zaman etiketlenmiş yeni bir kopyasını kaydeder.
* **Sıfır Bağımlılık (Derlendikten Sonra):** EXE olarak derlendikten sonra, kullanıcının bilgisayarında önceden Python kurulu olmasını gerektirmez.

## 🛠️ Kurulum

### 1. Gereksinimler

Bilgisayarınızda Python 3.x kurulu olmalıdır.

Gerekli kütüphaneleri yüklemek için, sağlanan `requirements.txt` dosyasını kullanarak aşağıdaki komutu çalıştırın:

```bash
pip install -r requirements.txt
