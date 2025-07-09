# 🚌 Konya Akıllı Kart Verisi Analizi

Bu proje, Konya iline ait toplu taşıma sisteminde kullanılan **akıllı kart** verileri üzerinden yapılan analizleri ve görselleştirmeleri içermektedir. Çalışma kapsamında günlük biniş sayılarına dayalı zamansal analizler ile birlikte, **transfer yoğunluklarına** göre hazırlanmış ısı haritası sunulmaktadır.

## 📅 Nisan 2024 Günlük Biniş Sayıları

Aşağıda, 1 Nisan – 30 Nisan 2024 tarihleri arasında akıllı kartla yapılan binişlerin günlük sayıları yer almaktadır:

| Tarih       | Biniş Sayısı |
|-------------|--------------|
| 01.04.2024  | 309,018      |
| 02.04.2024  | 392,846      |
| 03.04.2024  | 390,792      |
| 04.04.2024  | 391,200      |
| 05.04.2024  | 387,114      |
| 06.04.2024  | 266,542      |
| 07.04.2024  | 185,064      |
| 08.04.2024  | 214,490      |
| 09.04.2024  | 165,542      |
| 10.04.2024  | 1,740        |
| 11.04.2024  | 667          |
| 12.04.2024  | 819          |
| 13.04.2024  | 168,388      |
| 14.04.2024  | 149,772      |
| 15.04.2024  | 390,336      |
| 16.04.2024  | 398,898      |
| 17.04.2024  | 394,523      |
| 18.04.2024  | 398,125      |
| 19.04.2024  | 398,044      |
| 20.04.2024  | 252,001      |
| 21.04.2024  | 213,130      |
| 22.04.2024  | 403,307      |
| 23.04.2024  | 289,004      |
| 24.04.2024  | 409,116      |
| 25.04.2024  | 402,873      |
| 26.04.2024  | 401,940      |
| 27.04.2024  | 279,718      |
| 28.04.2024  | 194,980      |
| 29.04.2024  | 400,827      |
| 30.04.2024  | 401,159      |
| **Toplam**  | **8,651,975** |

### 📈 Biniş Sayısı Zaman Serisi Görselleştirmesi

![Biniş Zaman Serisi Grafiği](md/gunluk_binis.png)

Bu grafik, ay boyunca günlük biniş sayılarını göstermektedir. Özellikle hafta içi günlerinde biniş sayılarının daha yüksek, hafta sonları ve bayram tatili dönemlerinde (örneğin 10–12 Nisan) belirgin şekilde düştüğü görülmektedir.

---

## 🔁 Transfer Yoğunluğu Isı Haritası

Toplu taşıma ağında aktarma yapılan noktaların yoğunluğu aşağıdaki ısı haritası ile görselleştirilmiştir:

![Transfer Yoğunluğu Isı Haritası](md/transfer_yogunlugu.png)

### Açıklama:

- **Kırmızı**: Yüksek transfer yoğunluğuna sahip merkezler (örneğin Zafer, Nalçacı, Meram çevresi).
- **Yeşil**: Orta seviye yoğunlukta transfer yapılan bölgeler.
- **Mavi**: Görece düşük yoğunlukta kalan, daha az transfer yapılan bölgeler.

Bu görselleştirme, **toplu taşıma planlamasında aktarma merkezlerinin optimizasyonu** ve **yoğunluk haritalarının analiz edilmesi** için önemli ipuçları sunar.

---

## 📌 Amaç ve Kullanım

Bu proje, Konya’daki toplu taşıma sisteminin:
- Günlük kullanım eğilimlerini izlemek,
- Tatil dönemlerinin etkisini değerlendirmek,
- Aktarma merkezlerinin konumsal yoğunluğunu analiz etmek

amacıyla hazırlanmıştır. Planlamacılar, karar vericiler ve ulaşım mühendisleri için değerli içgörüler sağlamayı hedeflemektedir.

---

## 🛠️ Kullanılan Araçlar

- Python (Pandas, Matplotlib, Folium)

