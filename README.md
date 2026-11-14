# Solfej Aynası

Konservatuvara hazırlanan öğrenciler için tarayıcıda çalışan bir solfej çalışma aracı. Notayı söylersin, sesin hedef notanın üstüne canlı bir çizgi olarak çizilir; sonunda nota nota geri bildirim ve 100 üzerinden puan alırsın.

## Özellikler

- Nota dizeği ve solfej isimleriyle (Do, Re, Mi…) alıştırmalar
- Hazır alıştırmalar + sınırsız rastgele alıştırma üretici
- **Dinle:** ezgiyi çalar
- **Söyle:** başlangıç sesi, 4 vuruş sayım ve metronomla birlikte sesini kaydeder, gerçek zamanlı ses yüksekliği grafiği çizer
- Nota başına geri bildirim: "tam isabet", "20 sent tiz", "≈ Sol söyledin", "1 oktav pes"
- İnce ses / kalın ses seçeneği ve oktav farkını yok sayma
- Mikrofon seçimi, anlık akort göstergesi ve ses seviyesi çubuğu
- Açık ve koyu tema, telefon uyumlu

Tek bir HTML dosyasıdır; sunucu, kurulum ya da dış kütüphane gerektirmez. Ses yüksekliği tarayıcıda YIN algoritmasıyla hesaplanır, ses hiçbir yere gönderilmez.

## Çalıştırma

Mikrofon erişimi için sayfa `localhost` ya da `https` üzerinden açılmalıdır:

```bash
python -m http.server 8765
```

Ardından tarayıcıda `http://localhost:8765` adresini aç.
