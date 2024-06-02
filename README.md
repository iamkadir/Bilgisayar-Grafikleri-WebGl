﻿# Bilgisayar-Grafikleri-WebGl
# HTML Yapısı:

canvas öğesi tüm ekranı kaplayacak şekilde ayarlanmıştır.
WebGL bağlamı (gl) elde edilir ve desteklenmiyorsa hata mesajı görüntülenir.

Veri Hazırlığı:

vertices dizisi, her harfin köşe noktalarını içeren koordinatları tanımlar:
K, A, D, İ, R harfleri için çizgi koordinatları.
WebGL Kurulumu:

buffer oluşturulur ve vertices dizisi bu tampon belleğe yüklenir.
Temel bir vertexShader ve fragmentShader tanımlanır:
vertexShader köşe pozisyonlarını tanımlar.
fragmentShader renkleri tanımlar.
Çizim Fonksiyonu:

draw fonksiyonu, ekranı temizler ve her harfi belirli bir renkle çizer:
K: Kırmızı
A: Yeşil
D: Mavi
İ: Sarı
R: Magenta
Her harf için vertex sayıları belirlenmiştir ve uygun renkler ayarlanır.
requestAnimationFrame(draw) ile animasyon döngüsü başlatılır.
