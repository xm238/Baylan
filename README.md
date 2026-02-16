# Baylan Landing Page

Yüksek dönüşüm odaklı, çok dilli (TR/EN/عربي) premium landing page.

## Özellikler

- TR ana dil + EN ve عربي dil geçişi
- Desktop için pill/rounded header
- Mobil için overlay menü + segmentli dil seçici
- Güçlü CTA akışı (Ara, menü, iletişim)
- Baylan görselleri yeniden adlandırılmış dosya yapısı
- Placeholder rezervasyon formu (backend entegrasyonuna hazır)

## Çalıştırma

Statik dosya projesidir. Klasörde herhangi bir basit sunucu ile açabilirsiniz:

```bash
python3 -m http.server 8080
```

Ardından `http://localhost:8080` adresini açın.

## Backend Notu

Şu an form demo modda çalışır ve sadece arayüz davranışı sağlar.
Gerçek kullanım için bu formu aşağıdakilerden birine bağlayabilirsiniz:

- E-posta API (Resend / SendGrid)
- WhatsApp Business API
- CRM webhook (HubSpot / custom)

