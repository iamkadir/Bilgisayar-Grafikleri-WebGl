# Bilgisayar-Grafikleri-WebGl
# HTML Yapısı:

canvas öğesi tüm ekranı kaplayacak şekilde ayarladım
WebGL bağlamı ile (gl) elde ettim ve desteklenmiyorsa hata mesajı görüntülenecek.

# Veri Hazırlığı:

vertices dizisi, her harfin köşe noktalarını içeren koordinatları tanımlar:
K, A, D, İ, R harfleri için çizgi koordinatları.

# WebGL Kurulumu:

buffer oluşturdum ve vertices dizisi bu tampon belleğe yükledim.
Temel bir vertexShader ve fragmentShader tanımladım:
vertexShader ile köşe pozisyonlarını tanımladım.
fragmentShader ile renkleri tanımladım.

# Çizim Fonksiyonu:

draw fonksiyonu, ekranı temizler ve her harfi belirli bir renkle çizer:
K: Kırmızı
A: Yeşil
D: Mavi
İ: Sarı
R: Magenta
Her harf için vertex sayıları belirledim ve uygun renkler ayarladım.
requestAnimationFrame(draw) ile animasyon döngüsü başlattım.
