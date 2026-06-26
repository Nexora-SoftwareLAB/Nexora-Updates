# Nexora-Updates

Nexora Software uygulamaları için **version.txt tabanlı otomatik güncelleme sistemi**.

## 📌 Amaç

Bu repo, Nexora uygulamalarının güncel sürümünü kontrol etmek ve gerektiğinde yeni sürümleri kullanıcıya sunmak için kullanılır.

## ⚙️ Çalışma Mantığı

Uygulama şu dosyayı kontrol eder:

```
version.txt
```

Bu dosya GitHub üzerinden okunur:

```
https://raw.githubusercontent.com/NexoraSoftware/Nexora-Updates/main/version.txt
```

Eğer sürüm farklıysa, uygulama kullanıcıya güncelleme bildirimi gösterir.

## 📁 Repo Yapısı

```
Nexora-Updates/
├── version.txt   → En son sürüm numarası
├── app.zip       → Güncel uygulama dosyası
└── README.md     → Bilgilendirme dosyası
```

## 🧾 version.txt Örneği

```
1.0.0
```

## 🚀 Güncelleme Yayınlama

Yeni sürüm yayınlamak için:

1. `version.txt` dosyasını güncelle
2. Yeni uygulama dosyasını (`app.zip`) yükle
3. Değişiklikleri commit et

## 🔄 Örnek Güncelleme Akışı

* Kullanıcı uygulamayı açar
* Uygulama `version.txt` okur
* Sürüm farklıysa:

  * Güncelleme bildirimi gösterilir
  * Yeni sürüm indirilir

## 🏢 Nexora Software

Bu sistem Nexora Software uygulamaları için geliştirilmiştir.
