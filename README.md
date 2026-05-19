# Construct AI Copilot - Roadmap

## Amaç

İnşaat teknik ofisleri, satınalma ekipleri ve hakediş ekipleri için AI destekli analiz sistemi.

Sistem;

PDF
Excel
Mail
Teklif
Sözleşme

yüklenince analiz üretir.

---

# MVP V1

Hedef:

PDF + Excel yükle
↓

AI analiz etsin
↓

JSON çıktı versin

Örnek:

{
  "ats": true,
  "avans": "50%",
  "odeme": "FATURA + NAKİT",
  "riskler": [
      "Eksik teminat",
      "ATS belirtilmemiş"
  ]
}

---

# Özellikler

## Teklif Analizi

[ ] PDF teklif yükleme

[ ] Teklif özeti

[ ] Ödeme koşulu çıkarma

[ ] ATS tespiti

[ ] Avans oranı çıkarma

[ ] Süre çıkarma

[ ] Fiyat farkı kontrolü

---

## Hakediş Analizi

[ ] Hakediş PDF analizi

[ ] Kümülatif kontrol

[ ] Önceki hakediş karşılaştırması

[ ] Eksik imalat uyarısı

---

## Satınalma

[ ] Taşeron teklif karşılaştırma

[ ] Excel keşif okuma

[ ] Teklif mukayese tablosu

[ ] Sapma analizi

---

## Cari Analizi

[ ] Cari excel yükleme

[ ] Avans tespiti

[ ] Taşeron borcu

[ ] Ödeme geçmişi

[ ] Risk puanı

---

## Mail Agent

[ ] Outlook entegrasyonu

[ ] Mail özetleme

[ ] Aksiyon bekleyen mail

[ ] Müdür mailleri önceliklendirme

---

# Teknoloji

Frontend

- Next.js
- Vercel

Backend

- Supabase

AI

- Ollama
- Qwen

---

# Dosya Yapısı

frontend/

backend/

ai/

docs/

---

# Sonraki Adım

V1 frontend kurulumu

Next.js

Sonra:

PDF upload

Sonra:

Ollama bağlantısı
