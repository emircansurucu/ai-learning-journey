# Yapay Zekâ Öğrenme Yolculuğu

Yapay zekâyı sıfırdan, teorik temelleri ve küçük uygulamalarıyla öğrenmek için Türkçe bir ders kitabı.

Amaç; bir yöntemin neden gerektiğini anlamak, denklemlerini okuyabilmek, davranışını tahmin etmek ve küçük bir örnekle doğrulamaktır. Yapay zekâ terimleri önceden biliniyor kabul edilmez. Matematik ve Python bilgisi, gerektiğinde konulara bağlanarak kullanılır.

## Nereden başlamalı?

1. [Yol haritası](ROADMAP.md) ile konu sırasını incele.
2. [Anlatım standardı](ANLATIM_STANDARDI.md) ile derslerin nasıl işleneceğine bak.
3. [Kaynak rehberi](KAYNAKLAR.md) ile kitap ve videoların hangi amaçla kullanılacağını gör.
4. [Temeller](01-temeller/README.md) bölümünden sırayla ilerle.

**Durum:** [Ders 01 — Yapay zekâ nedir?](01-temeller/01-yapay-zeka-nedir.md), [Ders 02 — AI, ML ve DL haritası](01-temeller/02-ai-ml-dl-haritasi.md), [Ders 03 — Elle yazılan kurallar ve veriden öğrenme](01-temeller/03-kurallar-ve-veriden-ogrenme.md), [Ders 04 — Bir öğrenme probleminin parçaları](01-temeller/04-ogrenme-probleminin-parcalari.md), [Ders 05 — Model ve parametre](01-temeller/05-model-ve-parametre.md), [Ders 06 — Eğitim ve tahmin](01-temeller/06-egitim-ve-tahmin.md), [Ders 07 — Öğrenme düzenleri](01-temeller/07-ogrenme-duzenleri.md) ve [Ders 08 — Regresyon ve sınıflandırma](01-temeller/08-regresyon-ve-siniflandirma.md) okumaya hazır. Diğer dersler konu konu eklenecek. Yol haritasındaki kutular kişisel öğrenme ilerlemesini gösterir; dersin yayımlanması, konunun öğrenildiği anlamına gelmez.

## Bölümler

| Bölüm | Odak |
|---|---|
| [Yapay zekâ ve öğrenmenin temelleri](01-temeller/README.md) | AI–ML–DL ilişkisi; kurallar ve öğrenme; veri, özellik, etiket, model ve parametre; eğitim ve tahmin; öğrenme düzenleri; yapay nörona giriş. |
| [Öğrenmenin matematiği](02-ogrenmenin-matematigi/README.md) | Fonksiyon yaklaşımı; doğrusal regresyon; en küçük kareler; kayıp fonksiyonları; türev ve gradyan; gradyan inişi; olasılıksal yorum; genelleme ve regularization. |
| [Klasik makine öğrenmesi](03-klasik-makine-ogrenmesi/README.md) | Lojistik regresyon; kNN; karar ağaçları; random forest; gradient boosting; SVM; değerlendirme metrikleri; çapraz doğrulama; kümeleme; PCA; anomali tespiti. |
| [Yapay sinir ağları](04-yapay-sinir-aglari/README.md) | Perceptron; XOR; çok katmanlı ağlar; ileri yayılım; hesaplama grafiği; zincir kuralı; backpropagation; SGD, momentum ve Adam; başlangıç ağırlıkları; gradyan sorunları. |
| [Derin öğrenme](05-derin-ogrenme/README.md) | CNN; zaman serileri; RNN ve LSTM; embedding; attention; transformer; normalization; dropout; residual bağlantılar. |
| [Diğer öğrenme yaklaşımları ve üretici modeller](06-ogrenme-yaklasimlari/README.md) | Transfer learning; semi-supervised ve self-supervised learning; imitation learning; autoencoder; VAE; GAN; diffusion. |
| [Pekiştirmeli öğrenme](07-pekistirmeli-ogrenme/README.md) | Bandit; durum, eylem ve ödül; MDP; politika ve değer; Bellman denklemi; dynamic programming; Monte Carlo; temporal-difference; Q-learning; DQN; policy gradient; actor–critic. |
| [Mühendislik uygulamaları](08-muhendislik-uygulamalari/README.md) | Veriyle sistem tanımlama; öğrenilmiş dinamikler; belirsizlik; zaman serisi tahmini; model tabanlı RL; PID/LQR/MPC ile karşılaştırmalar; kontrol ve otonomi deneyleri. |

## Nasıl çalışacağız?

**Somut problem → sezgisel anlatım → görsel → matematik → çözümlü örnek → kısa deney → anlama kontrolü**

Her ders bir ana soruya odaklanır. Yeni terimler ilk kullanımda açıklanır; Türkçe karşılığının yanında İngilizcesi verilir. Denklemlerdeki semboller, boyutlar ve varsayımlar tanımlanır. İlk örnekler elle hesaplanabilecek kadar küçüktür.

İlerleme ölçütü bir videoyu bitirmek değil, fikri kendi cümlelerinle açıklayabilmek ve basit bir örnekte kullanabilmektir. Matematik, görseller ve deneyler aynı problemi açıklamak için birlikte kullanılır.

## Dosya düzeni

Her bölümün giriş sayfası `README.md` dosyasıdır. Dersler `01-konu-adi.md` biçiminde numaralandırılır. Gerektiğinde bölüm içine `assets/` (görseller) ve `notebooks/` (kısa deneyler) eklenir. Kaynak bağlantıları ders sonunda bulunur.

Kaynakların tümü baştan sona takip edilmek zorunda değildir. Her ders için uygun bir ana okuma ve görsel destek seçilir; ayrıntılı referanslar isteğe bağlı tutulur.
