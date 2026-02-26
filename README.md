📝 İletişim Ve Sunum Teknikleri - İlk Proje
Bu depo, Yazılım Mühendisliği 1. sınıf kapsamında hazırladığım, C dilinde temel konsol çıktılarını ve karakter kodlama yapılarını içeren başlangıç projesini barındırmaktadır.

🚀 Proje Amacı
Bu basit program, Windows konsol ortamında Türkçe karakter desteğini (UTF-8) aktif hale getirerek "İletişim Ve Sunum Teknikleri Dersine Hoşgeldiniz." mesajını ekrana yazdırmayı amaçlar.

🛠 Kullanılan Teknolojiler ve Araçlar
Dil: C


Derleyici: GCC (MinGW-w64 13.1.0) 


Kütüphaneler: stdio.h, windows.h (Konsol kod sayfası ayarları için) 

💻 Kod İçeriği
Program içerisinde yer alan SetConsoleOutputCP(65001); komutu, konsolun çıktı dilini UTF-8 olarak ayarlar. Bu sayede "İletişim", "Hoşgeldiniz" gibi Türkçe karakter içeren kelimeler konsolda bozulmadan görüntülenir.

🛠 Çalıştırma Talimatları
Programı yerel makinenizde derleyip çalıştırmak için:

C derleyicinizin (GCC gibi) yüklü olduğundan emin olun.

Terminali açın ve dosyanın bulunduğu dizine gidin.

Aşağıdaki komutu kullanarak derleyin:

Bash
gcc main.c -o main.exe
Ardından programı çalıştırın:

Bash
./main.exe
👤 Geliştirici

Adı: Mehmet 


Bölüm: Yazılım Mühendisliği - 1. Sınıf Öğrencisi
