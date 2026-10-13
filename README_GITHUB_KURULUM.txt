========================================================================
HAICARTOONS.COM — GITHUB "public" KLASÖRÜ & FIREBASE HOSTING REHBERİ
========================================================================

SORU: "GitHub'daki public klasörüne mi yükleyeceğim?"
CEVAP: EVET! Kesinlikle haicartoons projenizin "public" klasörüne yükleyeceksiniz!

NEDEN?
Çünkü haicartoons.com projeniz Firebase Hosting ile yayınlanıyor.
Firebase Hosting, projenizdeki "public" klasörünün içindeki her şeyi
otomatik olarak internete açar.

Dolayısıyla "public/deneyim" klasörü açtığınızda:
-> Tarayıcıdan "https://haicartoons.com/deneyim" yazdığınızda
   bu interaktif video sayfası anında açılır!

------------------------------------------------------------------------
ADIM ADIM YAPILACAKLAR:
------------------------------------------------------------------------
1. haicartoons projenizi GitHub üzerinde açın (veya AI Studio'daki projenizi açın).
2. "public" klasörünün içine girin.
3. "public" klasörü içinde "deneyim" adında yeni bir klasör oluşturun:
   -> Klasör Yolu: public/deneyim/

4. İndirdiğiniz zip içindeki şu dosyaları "public/deneyim/" içine kopyalayın:
   - public/deneyim/index.html
   - public/deneyim/assets/ (içindeki .js ve .css dosyalarıyla birlikte)

5. (İsteğe Bağlı) Kendi videolarınızı kalıcı yapmak için:
   - public/deneyim/videolar/ klasörü açıp videolarınızı içine koyabilirsiniz.
   - Bu videolar doğrudan şu linkte kalıcı olur:
     https://haicartoons.com/deneyim/videolar/video1.mp4

6. Değişiklikleri kaydedip GitHub'a gönderin (git commit & git push).
7. Firebase Hosting otomatik olarak sitenizi günceller (yaklaşık 1 dakika).

8. ARTIK YAYINDA:
   - https://haicartoons.com/deneyim
   - Sadece katılımcı video oynatıcı için:
     https://haicartoons.com/deneyim/?mode=player

Sayfa kapatıldığında hiçbir içerik kaybolmaz, Firebase Hosting üzerinde
7/24 ömür boyu kalıcı olarak yaşar!
========================================================================