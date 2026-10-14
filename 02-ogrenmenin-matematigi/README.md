# Öğrenmenin matematiği

[Kitabın giriş sayfası](../README.md) · [Yol haritası](../ROADMAP.md) · [Kaynak rehberi](../KAYNAKLAR.md)

## Amaç ve kapsam

Temeller bölümünde modelin ne olduğunu ve nöronun nasıl hesap yaptığını gördük. Bu bölümün ana sorusu: **Modelin parametrelerini veriden nasıl bulur, bulduğumuz modelin başarısını nasıl değerlendiririz?**

Fonksiyon yaklaşımı; doğrusal regresyon; en küçük kareler; kayıp fonksiyonları; türev ve gradyan; gradyan inişi; olasılıksal yorum; genelleme ve regularization bu bölümün kapsamındadır. Regularization, modelin aşırı esnek davranmasını sınırlayan düzenleme yöntemlerinin ortak adıdır; ilgili derslerde açıklanacaktır.

## Nasıl ilerleyeceğiz?

Anlatım bu bölümde daha ayrıntılıdır. Her yeni sembol önce sözel olarak açıklanır; denklemler ara adımlar atlanmadan çözülür. Önce küçük, tek girdili bir örneği elle hesaplayacak, ardından gerektiğinde çok girdili ve matris gösterimine geçeceğiz.

Grafiklerde eksenleri, birimleri, ölçüm noktalarını ve model tahminlerini birlikte okuyacağız. Önce gürültüsüz örnekle mekanizmayı kuracak, sonra ölçümlerin tam uyuşmadığı duruma geçeceğiz. Kod, anlatılan hesabı gözlemlemeye ihtiyaç duyduğumuzda eklenecek.

**Başlangıç:** [Ders 13 — Veriden fonksiyon öğrenmek](13-veriden-fonksiyon-ogrenmek.md).

## Dersler

| Ders | Ana soru | Durum |
|---|---|---|
| [13 — Veriden fonksiyon öğrenmek](13-veriden-fonksiyon-ogrenmek.md) | Birkaç ölçümden yeni girişlerde tahmin yapan bir kuralı nasıl kurarız? | Okumaya hazır |
| [14 — Doğrusal regresyon](14-dogrusal-regresyon.md) | Noktalar aynı doğru üzerinde değilse ağırlık ve bias'ı nasıl seçeriz? | Okumaya hazır |
| [15 — Kayıp fonksiyonu](15-kayip-fonksiyonu.md) | Tahmin hatalarını tek bir sayıyla nasıl değerlendiririz? | Okumaya hazır |
| [16 — Gradyan inişi](16-gradyan-inisi.md) | Parametreleri daha küçük kayba doğru nasıl güncelleriz? | Okumaya hazır |
| [17 — Genelleme ve overfitting](17-genelleme-ve-overfitting.md) | Eğitimde iyi çalışan model yeni veride neden başarısız olabilir? | Okumaya hazır |
| [18 — Çok girdili doğrusal regresyon ve matris gösterimi](18-cok-girdili-regresyon-ve-matrisler.md) | Birkaç özelliği birlikte kullanırken hesapları nasıl düzenleriz? | Okumaya hazır |
| [19 — Matrislerle en küçük kareler ve parametrelerin belirlenebilirliği](19-matrislerle-en-kucuk-kareler.md) | Çok girdili veride parametreleri nasıl buluruz ve çözüm ne zaman tektir? | Okumaya hazır |
| 20 — Özellik ölçekleme, Ridge/Lasso ve düzenlileştirme | Özellik ölçeklerini ve katsayıları nasıl kontrol ederiz? | Planlandı |
| 21 — Regresyonun olasılıksal yorumu ve belirsizlik | Tahmin ve hata modelini nasıl yorumlarız? | Planlandı |
| 22 — Bölüm tekrarı ve uçtan uca uygulama | Öğrenme döngüsünün bütün adımlarını nasıl birleştiririz? | Planlandı |

**Bölüm 22. dersle tamamlanacak şekilde planlandı.** 13–19. dersler okumaya hazır; 20–22. derslerle ölçekleme ve düzenlileştirme, olasılıksal yorum ve uçtan uca uygulama tamamlanacak. Ardından [03 — Klasik makine öğrenmesi](../03-klasik-makine-ogrenmesi/README.md) bölümüne geçilecek.

Bu tablo 02 bölümünün tamamlanma planını gösterir. İleri ayrıntılar ilgili sonraki bölümlerde genişletilecek. Yol haritasındaki kutular kişisel öğrenme ilerlemesini gösterir; yayımlanan dersler otomatik olarak öğrenilmiş sayılmaz.

## Ön koşullar

[Temeller bölümünün](../01-temeller/README.md) model, parametre, eğitim–tahmin ve regresyon kavramları. İlk ders için temel cebir yeterlidir; türev ve matris gösterimleri kullanılacakları yerde açıklanacaktır.

[Önceki bölümün son dersi: Tek nöronun sınırları](../01-temeller/12-tek-noronun-sinirlari.md)
