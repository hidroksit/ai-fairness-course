# Yapay Zekâda Adalet ve Güvenilirlik: 10 Haftalık Eğitim

Programlama geçmişi sınırlı üniversite öğrencilerine yapay zekânın nasıl çalıştığını ve yapay zekâ sistemlerindeki önyargının nasıl **ölçülüp, sorgulanıp, raporlanacağını** anlatmak için hazırladığım ders serisi. Eğitim, katılımcıların sonunda gerçek bir sistem üzerinde "kırmızı takım" testi yapıp risk analizi raporu yazmasını hedefler.

> **English:** A 10-week Turkish course on how AI works and how to audit it for bias, designed for students with little programming background. Every technical module (neural networks, LLMs, explainability, fairness metrics, bias mitigation) is taught on one running example: a synthetic hiring dataset with a built-in gender gap.

## Yaklaşım

- **Önce sezgi, sonra mekanizma, en son gerçek terim.** Sıfır seviyeden başlayan bir sınıfın takip edebileceği sırayla ilerler.
- **Tek bir örnek boyunca.** Bütün teknik modüller aynı sentetik işe alım veri seti (adayların %77'si erkek, %23'ü kadın; cinsiyet farkını taşıyan bir vekil değişken) üzerinden anlatılır. Böylece öğrenci her hafta aynı sistemin farklı bir katmanına bakar.
- **Sayılar gerçek koddan.** Slaytlardaki tüm metrikler `scikit-learn` ve `fairlearn` ile hesaplanıp doğrulanmıştır.
- **Kodlama gerektirmeyen uygulama.** Katılımcılar sıfırdan model yazmaz; hazır bir sistemi açıp test eder (gruplar arası seçilme ve hata oranları), sonuçları yorumlar ve rapora döker.

## Haftalar

| Hafta | Konu | Slayt |
|---|---|---|
| 1 | Yapay zekâ: temeller, tarihçe, "öğrenmek" ne demek | [PDF](slaytlar/hafta-01-yz-genel-bolum-1.pdf) |
| 2 | Yapay zekâ türleri, üretken YZ ve geleceği | [PDF](slaytlar/hafta-02-yz-genel-bolum-2.pdf) |
| 3 | Kodlama ve Python'a giriş | [PDF](slaytlar/hafta-03-python-giris.pdf) |
| 4 | Veri: öznitelik, etiket ve önyargının veriden girişi | [PDF](slaytlar/hafta-04-veri.pdf) |
| 5 | Makineler nasıl öğrenir: nöron, katman, kayıp, gradyan inişi, geri yayılım | [PDF](slaytlar/hafta-05-sinir-aglari.pdf) |
| 6 | Derin öğrenme ve büyük dil modelleri: token, embedding, attention, RLHF, halüsinasyon | [PDF](slaytlar/hafta-06-buyuk-dil-modelleri.pdf) |
| 7 | Açıklanabilirlik: "Neden bu kararı verdin?" | [PDF](slaytlar/hafta-07-aciklanabilirlik.pdf) |
| 8 | Adaleti ölçmek: demografik eşitlik, fırsat eşitliği, öngörü eşitliği | [PDF](slaytlar/hafta-08-adaleti-olcmek.pdf) |
| 9 | Önyargıyı azaltmak: ön, iç ve son işleme yöntemleri ve bedelleri | [PDF](slaytlar/hafta-09-onyargiyi-azaltmak.pdf) |
| 10 | Gerçek vakalar ve kapanış: kendi denetimini yap | [PDF](slaytlar/hafta-10-vakalar-kapanis.pdf) |

Haftalar 90 dakikalık oturumlar için tasarlanmıştır.

## İlgili depo

Slaytlardaki ölçüm ve azaltma adımlarının çalıştırılabilir bir sürümü: [hiring-fairness-audit](https://github.com/hidroksit/hiring-fairness-audit)

## Lisans

Ders materyalleri [CC BY 4.0](LICENSE) ile paylaşılmaktadır: kaynak göstererek kullanabilir ve uyarlayabilirsiniz.
