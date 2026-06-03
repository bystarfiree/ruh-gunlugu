# Ruh Günlüğüm ve Ben 🌙

Kullanıcıyla sohbet ederek ruh hali takibi yapan, Türkçe duygu analizi tabanlı bir günlük uygulaması. Kullanıcının gününü anlattığı metni analiz eder, sağlık alışkanlıklarını takip eder ve sonuçları grafiklerle gösterir.

## Özellikler

- **Türkçe duygu analizi:** Kullanıcının yazdığı günlük metnini analiz edip olumlu/olumsuz olarak sınıflandırır (BERT tabanlı Türkçe model).
- **Vitamin takibi:** Eksik vitaminleri tespit eder ve geri bildirim verir.
- **Vücut Kitle İndeksi (VKİ):** Boy ve kilodan VKİ hesaplar ve yorumlar.
- **Günlük takip:** Su tüketimi, uyku, ekran süresi, kafein ve spor verilerini gün gün kaydeder.
- **Puanlama:** Tüm alışkanlıklara göre günlük bir sağlık puanı üretir.
- **Grafikler:** Seçilen verilerin zaman içindeki değişimini matplotlib ile çizer.

## Kullanılan Kütüphaneler

- `transformers` – Türkçe duygu analizi modeli (`savasy/bert-base-turkish-sentiment-cased`)
- `matplotlib` – Grafik çizimi
- `numpy`, `pandas` – Veri işleme
- `sys`, `os` – Sistem işlemleri

## Nasıl Çalıştırılır

1. Gerekli kütüphaneleri yükleyin:
pip install transformers torch matplotlib numpy pandas

2. 2. Notebook dosyasını Jupyter'da açıp hücreleri sırayla çalıştırın.

## Not
Bu proje, yapay zeka ve veri bilimi öğrenme sürecimde geliştirdiğim kişisel bir çalışmadır.
