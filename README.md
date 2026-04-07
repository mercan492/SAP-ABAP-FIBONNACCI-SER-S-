# SAP-ABAP-FIBONNACCI-SER-S-

Matematiksel düşünce yapısını programlama mantığıyla birleştiren bu rapor, kullanıcının belirlediği adet kadar Fibonacci sayısını (0, 1, 1, 2, 3, 5, 8, ...) hesaplar. Program, değişken yönetimi ve döngüsel işlemler (iteration) konusunda temel bir yetkinlik göstergesidir.

🛠 Teknik Detaylar
     Dil: ABAP
     Döngü Yapısı: DO n TIMES ... ENDDO (Belirli sayıda tekrar eden döngü bloğu).
     Algoritma Mantığı: Üçlü değişken kaydırma yöntemi kullanılarak, her adımda bir sonraki sayı (n=(n−1)+(n−2)) hesaplanır ve bellek verimli bir şekilde güncellenir.
     Girdi: p_count (Oluşturulacak eleman sayısı - Default: 10).

📈 Algoritma Akışı

    Başlangıç: İki temel değer tanımlanır (lv_first = 0, lv_second = 1).

    Yazdırma: Mevcut sayı ekrana basılır.

    Hesaplama: lv_next değeri, mevcut iki sayının toplamı olarak atanır.

    Güncelleme: Bir sonraki adım için lv_first değeri lv_second'a, lv_second ise yeni hesaplanan lv_next değerine eşitlenir.

    Tekrar: Kullanıcının belirlediği limit dolana kadar döngü devam eder.

🚀 Kullanım

    SAP SE38 işlem kodu üzerinden Z_DONGULER adıyla yeni bir rapor oluşturun.

    Kod bloğunu yapıştırın ve Activate (Ctrl+F3) yapın.

    F8 ile çalıştırdıktan sonra üretilmesini istediğiniz eleman sayısını girin.

📝 Örnek Çıktı (p_count = 8)
Plaintext

Fibonacci Serisi : 8 eleman
0  1  1  2  3  5  8  13

Geliştiren: Mercan Köseoğlu   21.08.2025

Data Analyst & SAP ABAP Consultant
