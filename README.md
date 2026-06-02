# 🧪 Polyglot Suite: Mimic & Deck Architect

> **Dil Öğrenenler İçin İki Güçlü Araç Tek Bir Arayüzde.** Aksanınızı kusursuzlaştırın, ses dalgalarınızı kıyaslayın ve saniyeler içinde Anki kelime kartlarınızı (.CSV) ücretsiz üretin. **%100 Serverless, Sıfır Maliyet.**

---

## 🍏 Polyglot Suite Nedir?

Dil öğrenme sürecindeki en büyük iki problem; **akıcı bir aksana (telaffuza) sahip olamamak** ve **kelime ezber kartları hazırlarken saatler harcamaktır**. 

**Polyglot Suite**, bu iki problemi tarayıcınızın gücünü kullanarak çözen minimalist ve şık bir çalışma stüdyosudur. İçerisinde iki bağımsız modül barındırır:
1. **Accent Mimic:** Ses taklidi (Shadowing) yöntemiyle telaffuz çalışmanızı sağlar.
2. **Deck Architect:** Kelimelerinizi toplu olarak Anki flashcard formatına dönüştürür.

---

## ✨ Öne Çıkan Özellikler

### 1. Accent Mimic Stüdyosu (Aksan & Telaffuz)
* **Görsel Dalga Kıyaslama:** Orijinal sesin dalga şeması ile kendi sesinizin dalga şemasını alt alta görerek tonlama hatalarınızı fark edin.
* **Yerel Kayıt Yeteneği:** Sesiniz hiçbir sunucuya yüklenmez; tamamen tarayıcı içinde (`MediaRecorder API`) anlık kaydedilir ve çalınır.
* **Sıfır Maliyetli Ses:** Tarayıcının yerleşik ses motorunu kullanır, harici ücretli TTS servislerine bağımlılığı yoktur.

### 2. Anki Deck Architect (Kart Fabrikası)
* **Akıllı Prompt Entegrasyonu:** Kelimelerinizi yazın, sistem yapay zekanın (ChatGPT/Claude) tam istediği formatta bir komut üretsin.
* **Tek Tıkla .CSV İndirme:** Yapay zekadan aldığınız çıktıyı yapıştırın ve doğrudan masaüstü/mobil Anki uygulamasına aktarabileceğiniz kusursuz bir `.csv` dosyası indirin.
* **Zengin Kart İçeriği:** Kartların ön yüzünde kelime, arka yüzünde ise Türkçe anlamı, yapay zekanın kurduğu örnek cümle ve cümlenin çevirisi otomatik olarak şablonlanır.

---

## 🛠️ Nasıl Çalışır?

### Mod 1: Accent Mimic
1. **Dinleyin:** Orijinal cümleyi duymak için oynat butonuna basın.
2. **Kaydedin:** Mikrofon simgesine basarak cümleyi kendiniz seslendirin.
3. **Kıyaslayın:** Oluşan yeşil ses dalgalarını mavi dalgalarla kıyaslayın ve kendi kaydınızı dinleyerek hatalarınızı düzeltin.

### Mod 2: Deck Architect
1. **Kelimeleri Yazın:** Öğrenmek istediğiniz kelimeleri virgülle ayırarak girin (Örn: `run, walk, speak`).
2. **Komutu Alın:** "Yapay Zeka Komutunu Kopyala" butonuna basın ve bu komutu ücretsiz ChatGPT'ye yapıştırın.
3. **Sonucu Yapıştırın & İndirin:** ChatGPT'nin size verdiği pipe (`|`) işaretli satırları sağdaki kutuya yapıştırıp `.csv` dosyanızı anında indirin. Anki uygulamasından içeri aktarın!

---

## 🚀 Teknolojik Altyapı & Mimari

Bu proje, harici hiçbir ağır kütüphane veya backend sunucusu olmadan **tek bir `index.html` dosyası** olarak tasarlanmıştır:

* **HTML5 & JavaScript (ES6+)**
* **Tailwind CSS:** Modern, gözü yormayan derin karanlık mod (Apple-style) arayüzü.
* **Alpine.js:** Sekme geçişleri ve ses kayıt durumları için ultra hafif reaktif yönetim.
* **Web Audio & Speech API:** Tarayıcı içi ses sentezleme ve mikrofon yönetimi.

---

## 📦 Kurulum ve Canlıya Alma

Proje sunucusuz (serverless) olduğu için kurulum gerekmez:

1. Bu depoyu klonlayın veya `index.html` dosyasını indirin.
2. Tarayıcınızda çift tıklayarak **anında lokalde çalıştırın**.
3. **GitHub Pages** kullanarak 1 dakika içinde tamamen ücretsiz olarak tüm dünyaya açın (Settings > Pages > Branch: Main > Save).

---

## 📄 Lisans

Bu proje **MIT Lisansı** ile lisanslanmıştır. Tamamen açık kaynaklıdır; dilediğiniz gibi geliştirebilir, klonlayabilir veya kendi topluluğunuz için yayına alabilirsiniz.

---

*Projeyi beğendiyseniz bir ⭐️ bırakmayı unutmayın! Katkılarınızı (Pull Request) bekliyoruz. 🧪*
