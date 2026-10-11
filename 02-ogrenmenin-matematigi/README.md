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
| 14 — Doğrusal regresyon | Noktalar aynı doğru üzerinde değilse ağırlık ve bias'ı nasıl seçeriz? | Planlandı |
| 15 — Kayıp fonksiyonu | Tahmin hatalarını tek bir sayıyla nasıl değerlendiririz? | Planlandı |
| 16 — Gradyan inişi | Parametreleri daha küçük kayba doğru nasıl güncelleriz? | Planlandı |
| 17 — Genelleme ve overfitting | Eğitimde iyi çalışan model yeni veride neden başarısız olabilir? | Planlandı |

Bu tablo bölümün başlangıç derslerini gösterir. Kapsamdaki diğer konular, ön koşulları kurulduktan sonra ayrı derslerle eklenecek. Yol haritasındaki kutular kişisel öğrenme ilerlemesini gösterir; yayımlanan dersler otomatik olarak öğrenilmiş sayılmaz.

## Ön koşullar

[Temeller bölümünün](../01-temeller/README.md) model, parametre, eğitim–tahmin ve regresyon kavramları. İlk ders için temel cebir yeterlidir; türev ve matris gösterimleri kullanılacakları yerde açıklanacaktır.

[Önceki bölümün son dersi: Tek nöronun sınırları](../01-temeller/12-tek-noronun-sinirlari.md)
