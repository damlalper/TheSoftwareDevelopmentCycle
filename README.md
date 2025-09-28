# BİL 102 — Yazılım Mühendisliği Temelleri  
**Ödev (15.03.2023)**  
**Öğrenci:** Damla Nur Alper — **220601017**

---

## 📌 Özet
Bu döküman, yazılım geliştirme yaşam döngüsü (SDLC) kavramını, temel aşamalarını ve yaygın kullanılan modelleri (Waterfall, V-Model, Code-and-Fix, Scrum/Agile) düzenli ve açıklayıcı bir şekilde açıklar. Ders ödevi için kullanılabilecek kısa uygulama önerileri ve kaynakça da eklenmiştir.

---

## 💡 Yazılım Yaşam Döngüsü (SDLC) Nedir?
SDLC (Software Development Life Cycle) — Yazılım Geliştirme Yaşam Döngüsü — yazılım ürünlerinin planlanmasından tasarımına, geliştirilmesine, dağıtımına ve bakımına kadar geçen yapısal süreçler kümesidir.  

**Temel özellikleri:**
- Aşamalar mantıksal bir sıra takip eder fakat süreçler **iteratif** olabilir.  
- Her aşamanın çıktıları ve sorumlulukları bellidir.  
- Model seçimi proje büyüklüğü, risk ve belirsizlik düzeyine göre yapılır.  

---

## 🔄 SDLC Aşamaları
1. **Planlama**  
   Proje hedefleri, kapsam, kaynaklar ve zaman çizelgesi belirlenir.  
   *Çıktılar: Fizibilite raporu, proje planı.*

2. **Tanımlama / Gereksinim Analizi**  
   Kullanıcı ihtiyaçları toplanır, analiz edilir ve netleştirilir.  
   *Çıktılar: SRS (Software Requirements Specification).*

3. **Tasarım**  
   Sistemin mimarisi, bileşenleri ve etkileşimleri tasarlanır.  
   *Çıktılar: Mimari diyagramlar, veri modelleri.*

4. **Geliştirme (Kodlama)**  
   Tasarıma göre yazılım kodlanır, birim testler yapılır.  
   *Çıktılar: Kaynak kod, birim testleri.*

5. **Gerçekleştirme / Entegrasyon & Test**  
   Kod parçaları birleştirilir, sistem test edilir.  
   *Çıktılar: Test planı, hata raporları.*

6. **Uygulama / Dağıtım**  
   Yazılım canlıya alınır, kullanıcı kabul testleri yapılır.  
   *Çıktılar: Kullanıcı kabul raporları, eğitim materyalleri.*

7. **Bakım**  
   Hatalar düzeltilir, yeni özellikler eklenir.  
   *Çıktılar: Sürüm notları, değişiklik talepleri.*

> 🔁 Bu aşamalar tamamlandığında döngü yeniden başlar.

---

## 🏗️ SDLC Modelleri

### 1. Waterfall (Şelale)
- **Tanım:** Aşamalar sıralı ilerler, geri dönüş sınırlıdır.  
- **Avantajlar:** Basit, küçük projelerde etkili.  
- **Dezavantajlar:** Hata ve değişiklik maliyetleri çok yüksektir.  

### 2. V-Model
- **Tanım:** Waterfall’ın test odaklı geliştirilmiş versiyonu.  
- **Avantajlar:** Test süreçleri paralel yürür.  
- **Dezavantajlar:** Esneklik azdır.  

### 3. Code-and-Fix (Kodla ve Düzelt)
- **Tanım:** Planlama olmadan doğrudan kodlama yapılır.  
- **Avantajlar:** Çok küçük ve kısa ömürlü projeler için hızlıdır.  
- **Dezavantajlar:** Kontrolsüz büyüme ve bakım zorlukları.  

### 4. Agile — Scrum
- **Tanım:** Yazılım küçük iterasyonlar (**sprint**) halinde geliştirilir.  
- **Avantajlar:** Değişikliklere hızlı uyum, sürekli müşteri geri bildirimi.  
- **Dezavantajlar:** Disiplin ve iletişim eksikse kaosa yol açabilir.  

---

## ⚖️ Model Karşılaştırması
| Model        | Uygun Olduğu Durumlar | Avantajlar | Dezavantajlar |
|--------------|------------------------|------------|---------------|
| **Waterfall** | Küçük, sabit gereksinimli projeler | Basit, belgeli | Esnek değil |
| **V-Model**   | Test odaklı kritik projeler | Doğrulama güçlü | Esneklik sınırlı |
| **Code-Fix**  | Çok küçük ve prototip işler | Hızlı başlangıç | Kaotik, bakımı zor |
| **Scrum**     | Belirsiz ve değişken gereksinimler | Çevik, güncel | Disiplin gerektirir |

---

## 📝 Ders İçin Uygulama Önerileri
- Gereksinim belgesi (SRS) yazmayı alışkanlık edin.  
- Basit diyagramlar (mimari, akış, sınıf diyagramları) hazırla.  
- Git kullanarak versiyon kontrolü uygula.  
- Küçük projelerde Waterfall, belirsizlerde Scrum tercih et.  
- Test planı ve basit bir demo hazırlamayı unutma.  

---

## 📚 Kaynakça
- [Wikipedia — Scrum](https://tr.wikipedia.org/wiki/Scrum)  
- [Fikir Jeneratörü](https://fikirjeneratoru.com/yazilim-proje-yonetimi-yontemleri/)  
- [Academia.edu](https://www.academia.edu/)  
- [Medium — Yazılım Yaşam Döngüsü Modelleri](https://medium.com/@omerharuncetin/yaz%C4%B1l%C4%B1m-ya%C5%9Fam-d%C3%B6ng%C3%BC-modelleri-543c7879a742)  
- [YBS Ansiklopedisi](https://ybsansiklopedi.com/)  
- [TutorialsPoint — V Model](https://www.tutorialspoint.com/sdlc/pdf/sdlc_v_model.pdf)  

---
