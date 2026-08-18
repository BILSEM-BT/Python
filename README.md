# BİLSEM BT - Python ve Yapay Zeka Dersleri

Bu depo, **Niyazi Sayın BİLSEM Bilişim Teknolojileri derslerinde** kullanılmak üzere hazırlanmış Python ve Yapay Zeka eğitim içeriklerini içerir.

Ders materyalleri temel Python programlamadan başlayarak veri analizi, masaüstü ve web uygulamaları, makine öğrenmesi, derin öğrenme, doğal dil işleme, büyük dil modelleri, RAG ve yapay zeka destekli web uygulamalarına kadar ilerleyen bütüncül bir eğitim yapısına sahiptir.

Ders içerikleri GitHub üzerinde ana kaynak olarak tutulur. Öğrenciler dersleri sınıfta öğretmen rehberliğinde takip edebilir, evde tekrar edebilir ve Google Colab üzerinden kodları çalıştırarak kendi denemelerini yapabilir.

## Eğitim Yaklaşımı

Bu depo yalnızca hazır kod örneklerinden oluşmaz. Amaç öğrencinin:

- Python programlama mantığını öğrenmesi,
- algoritmik düşünme becerisini geliştirmesi,
- veri ile çalışabilmesi,
- gerçek uygulamalar geliştirebilmesi,
- yapay zeka modellerinin temel mantığını anlayabilmesi,
- modelleri değerlendirebilmesi,
- web, veritabanı ve yapay zeka bileşenlerini bir araya getirebilmesi,
- kendi özgün BİLSEM projelerini geliştirebilecek seviyeye ulaşmasıdır.

Dersler birbirini takip edecek şekilde hazırlanmıştır. Bu nedenle özellikle Python'a yeni başlayan öğrencilerin dosyaları numara sırasına göre ilerletmesi önerilir.

---

# Hesap Gereksinimleri

## Gmail / Google Hesabı

Bu eğitim sürecinde **her öğrencinin aktif bir Gmail hesabının olması zorunludur.**

Ders notebook'ları Google Colab üzerinde çalıştırılabildiği için öğrencilerin kendi Google hesaplarıyla Colab'a giriş yapması gerekir.

Bu derslerde standart olarak Gmail hesabı kullanılacaktır.

Gmail hesabı sayesinde öğrenciler:

- Google Colab'a giriş yapabilir,
- notebook dosyalarını çalıştırabilir,
- kendi kopyalarını oluşturabilir,
- çalışmalarını Google Drive üzerinde saklayabilir,
- evden veya farklı bir bilgisayardan çalışmalarına devam edebilir.

Öğrencilerin ders başlamadan önce Gmail hesaplarına giriş yapabildiğinden emin olması önerilir.

## GitHub Hesabı

Her öğrencinin bir **GitHub hesabı oluşturması önemle önerilir**, ancak yalnızca ders dosyalarını görüntülemek için GitHub hesabı zorunlu değildir.

GitHub hesabı öğrencinin ilerleyen süreçte:

- kendi projelerini yayınlaması,
- kodlarını sürümlemesi,
- proje geçmişini takip etmesi,
- portföy oluşturması,
- takım projelerinde çalışması,
- açık kaynak kültürünü öğrenmesi

açısından önemli bir kazanımdır.

Özellikle proje geliştirme aşamasına gelen öğrencilerin kendi GitHub hesaplarını oluşturmaları tavsiye edilir.

---

# GitHub Deposu

Ana ders deposu:

```text
https://github.com/BILSEM-BT/Python
```

Bu depodaki `main` branch derslerin ana ve değiştirilmeyen kaynağı olarak kullanılacaktır.

Öğrencilerin ana ders dosyalarını değiştirmesi beklenmez.

Ders dosyalarında yapılacak kişisel çalışmalar öğrencinin kendi bilgisayarında, kendi Google Colab çalışma alanında veya kendi GitHub deposunda tutulmalıdır.

---

# Dosya Türü

Derslerin büyük bölümü:

```text
.ipynb
```

uzantılı **Jupyter Notebook** dosyalarıdır.

Notebook dosyaları aynı belge içinde:

- konu anlatımı,
- açıklamalar,
- Python kodları,
- tablolar,
- grafikler,
- uygulamalar

bulundurabilir.

Bu nedenle her ders tek bir `.ipynb` dosyası üzerinden takip edilebilir.

---

# Ders Dosyaları Nasıl Açılır?

## 1. Google Colab ile Açmak

Ders dosyalarını kullanmanın en kolay yöntemi Google Colab'dır.

Her notebook dosyasının en üst bölümünde:

```text
Open in Colab
```

butonu bulunur.

Kullanım adımları:

1. GitHub üzerinde istediğiniz ders dosyasını açın.
2. Dosyanın üst kısmındaki **Open in Colab** butonuna tıklayın.
3. Google hesabınızla giriş yapın.
4. Notebook Google Colab üzerinde açılacaktır.
5. Kod hücrelerini `▶` düğmesiyle çalıştırın.
6. Kodları değiştirerek farklı sonuçları deneyin.

Colab üzerinde yaptığınız değişiklikler GitHub'daki ana ders dosyasını otomatik olarak değiştirmez.

Bu nedenle öğrenciler rahatlıkla kodlar üzerinde deney yapabilir.

## 2. Google Colab'da Kendi Kopyanızı Oluşturmak

Bir ders üzerinde uzun süre çalışacaksanız notebook'un kendi kopyanızı oluşturmanız önerilir.

Google Colab üzerinden:

```text
Dosya > Drive'a bir kopya kaydet
```

seçeneği kullanılabilir.

Böylece çalışma öğrencinin kendi Google Drive hesabında saklanır.

Ana GitHub dosyası değişmeden kalır.

## 3. GitHub Üzerinden Görüntülemek

Notebook dosyaları GitHub üzerinde doğrudan görüntülenebilir.

Bu yöntem özellikle:

- konu anlatımını okumak,
- kod örneklerini incelemek,
- ders sırasını takip etmek

için kullanılabilir.

Kodları çalıştırmak için Google Colab veya yerel Python geliştirme ortamı kullanılmalıdır.

## 4. Bilgisayara İndirerek Açmak

Notebook dosyaları GitHub üzerinden bilgisayara indirilebilir.

Dosya indirildikten sonra aşağıdaki ortamlardan biri kullanılabilir:

- Visual Studio Code
- Jupyter Notebook
- JupyterLab

Visual Studio Code kullanılıyorsa Python ve Jupyter eklentilerinin kurulu olması önerilir.

## 5. Visual Studio Code ile Açmak

Visual Studio Code içerisinde:

1. Python kurulmalıdır.
2. Visual Studio Code kurulmalıdır.
3. Python eklentisi kurulmalıdır.
4. Jupyter eklentisi kurulmalıdır.
5. `.ipynb` dosyası Visual Studio Code ile açılmalıdır.
6. Kullanılacak Python interpreter / kernel seçilmelidir.

Böylece notebook hücreleri doğrudan bilgisayarda çalıştırılabilir.

---

# Derslerde Nasıl Çalışacağız?

Sınıf ortamında öğretmen konu anlatımını yaparken notebook dosyası ana ders dokümanı olarak kullanılacaktır.

Önerilen çalışma düzeni:

```text
Öğretmen Anlatımı
↓
Notebook Örneği
↓
Kodun Çalıştırılması
↓
Kodun Değiştirilmesi
↓
Yeni Denemeler
↓
Mini Uygulama
↓
Bağımsız Proje
```

Öğrencilerin yalnızca kodu çalıştırması değil, kod üzerinde değişiklik yapması beklenir.

Örneğin:

- değişken değerlerini değiştirmek,
- farklı veri kullanmak,
- yeni koşullar eklemek,
- yeni fonksiyonlar yazmak,
- uygulamayı geliştirmek,
- farklı grafikler üretmek

öğrenme sürecinin önemli bir parçasıdır.

---

# GitHub ve Google Colab Birlikte Nasıl Kullanılır?

Bu eğitimde iki sistemin görevleri farklıdır.

## GitHub

GitHub:

```text
Derslerin ana kaynağıdır.
```

Buradaki dosyalar öğretmen tarafından hazırlanmış ve ders sırasına göre düzenlenmiş ana içeriklerdir.

## Google Colab

Google Colab:

```text
Kodların çalıştırıldığı ve öğrencinin deney yaptığı ortamdır.
```

Öğrenci Colab üzerinde kodları değiştirebilir.

Ancak bu değişiklikler GitHub'daki ana notebook dosyasına otomatik olarak gönderilmez.

Temel çalışma mantığı:

```text
GitHub
Ana Ders Dosyası
↓
Open in Colab
↓
Öğrencinin Çalışma Alanı
↓
Kodları Çalıştır
↓
Kodları Değiştir
↓
Yeni Denemeler Yap
```

Bu nedenle GitHub her zaman ana ders kaynağı olarak kabul edilmelidir.

---

# Ders Dosyalarının Sırası

## Python Temelleri

1. `01-PythonaGiris.ipynb`
2. `02-PythonKararYapilari.ipynb`
3. `03-PythonHataYonetimi.ipynb`
4. `04-PythonDonguler.ipynb`
5. `05-PythonListeler.ipynb`
6. `06-PythonDemetlerVeKumeler.ipynb`
7. `07-PythonSozlukler.ipynb`
8. `08-PythonFonksiyonlar.ipynb`
9. `09-PythonDosyaIslemleri.ipynb`
10. `10-PythonModullerVeKutuphaneler.ipynb`

## Veri Bilimi ve Görselleştirme

11. `11-PythonNumPy.ipynb`
12. `12-PythonPandas.ipynb`
13. `13-PythonMatplotlib.ipynb`
14. `14-PythonVeriAnaliziProjesi.ipynb`

## Masaüstü, Veritabanı ve Web Programlama

15. `15-PythonTkinter.ipynb`
16. `16-PythonSQLiteVeritabani.ipynb`
17. `17-PythonTkinterSQLiteCRUD.ipynb`
18. `18-PythonFlaskWebGiris.ipynb`
19. `19-PythonFlaskSQLiteCRUD.ipynb`
20. `20-PythonFlaskKullaniciGirisi.ipynb`

## Makine Öğrenmesi

21. `21-PythonYapayZekayaGiris.ipynb`
22. `22-PythonRegresyon.ipynb`
23. `23-PythonSiniflandirmaAlgoritmalari.ipynb`
24. `24-PythonModelDegerlendirme.ipynb`
25. `25-PythonKMeansKumeleme.ipynb`
26. `26-PythonYapayZekaTahminProjesi.ipynb`

## Doğal Dil İşleme, Görüntü İşleme ve Derin Öğrenme

27. `27-PythonDogalDilIsleme.ipynb`
28. `28-PythonMetinSiniflandirmaUygulamasi.ipynb`
29. `29-PythonGoruntuIsleme.ipynb`
30. `30-PythonYapaySinirAglari.ipynb`
31. `31-PythonDerinOgrenmeGoruntuSiniflandirma.ipynb`
32. `32-PythonTransferLearning.ipynb`

## Üretken Yapay Zeka ve LLM Uygulamaları

33. `33-PythonUretkenYapayZeka.ipynb`
34. `34-PythonLLMAPIUygulamalari.ipynb`
35. `35-PythonRAGDokumanSoruCevap.ipynb`
36. `36-PythonYapayZekaFlaskUygulamasi.ipynb`

## Bitirme Projesi

37. `37-PythonYapayZekaBitirmeProjesi.ipynb`

---

# Derslerin Genel Hedefi

Bu ders serisinin sonunda öğrencilerin aşağıdaki zinciri anlayabilmesi ve uygulayabilmesi hedeflenmektedir:

```text
Problem
↓
Algoritma
↓
Python
↓
Veri
↓
Analiz
↓
Model
↓
Evaluation
↓
Uygulama
↓
Veritabanı
↓
Web
↓
Yapay Zeka
↓
LLM
↓
RAG
↓
Gerçek Proje
```

Öğrencinin yalnızca hazır bir yapay zeka aracını kullanan kişi olması değil, yapay zeka uygulamalarının arkasındaki yazılım ve veri süreçlerini anlayan bir geliştirici olması hedeflenmektedir.

---

# Yapay Zeka Derslerinde Dikkat Edilecek Noktalar

Yapay zeka çıktıları her zaman doğru kabul edilmemelidir.

Öğrenciler:

- model sonuçlarını kontrol etmeli,
- kullanılan veriyi incelemeli,
- evaluation sonuçlarını değerlendirmeli,
- modelin hata yapabileceğini bilmeli,
- yapay zeka tarafından verilen bilgileri doğrulamalı,
- gizli ve kişisel bilgileri yapay zeka sistemlerine göndermemelidir.

API anahtarları, parolalar ve kişisel bilgiler notebook dosyalarının içine yazılmamalıdır.

---

# OpenAI API Kullanılan Dersler

Üretken yapay zeka derslerinin bazı bölümlerinde OpenAI API kullanım örnekleri bulunmaktadır.

Bu örneklerde gerçek API çağrıları varsayılan olarak kapalı tutulmuştur.

Amaç:

- öğrencinin yanlışlıkla ücretli API çağrısı yapmasını önlemek,
- API anahtarı olmayan öğrencilerin de dersi çalıştırabilmesini sağlamak,
- temel mimariyi internet bağlantısından bağımsız öğretmektir.

API kullanılacaksa anahtar kaynak kod içine yazılmamalıdır.

Environment variable veya güvenli secret sistemi kullanılmalıdır.

---

# Google Colab Hakkında Önemli Not

Google Colab bulut tabanlı bir çalışma ortamıdır.

Bu nedenle bazı masaüstü uygulamaları Colab üzerinde doğrudan çalışmayabilir.

Örneğin:

- Tkinter masaüstü pencereleri,
- bazı yerel GUI uygulamaları,
- yerel Flask sunucusunun tarayıcı kullanımı

bilgisayarda çalıştırılmaya daha uygundur.

Bu derslerde Colab özellikle:

- Python temelleri,
- NumPy,
- Pandas,
- Matplotlib,
- makine öğrenmesi,
- derin öğrenme,
- doğal dil işleme,
- yapay zeka

çalışmaları için kullanılacaktır.

Masaüstü ve web uygulamalarının bazı bölümleri öğrencinin kendi bilgisayarında Visual Studio Code üzerinden çalıştırılabilir.

---

# Öğrencilere Önerilen Çalışma Ortamı

Her öğrencinin aşağıdaki araçlara sahip olması önerilir:

```text
Gmail Hesabı
Google Colab
GitHub Hesabı
Python
Visual Studio Code
Python Extension
Jupyter Extension
```

Bu eğitim sürecinde **Gmail hesabı zorunlu**, GitHub hesabı ise **önemle önerilen** bir araçtır.

---

# Ders Dosyalarını Değiştirirken

GitHub'daki ana ders dosyaları öğretmen tarafından yönetilir.

Öğrencilerin:

```text
main branch
```

üzerindeki ana ders içeriklerini değiştirmesi yerine kendi çalışmalarını ayrı ortamda tutması önerilir.

Çalışmalar:

- Google Drive,
- öğrencinin kendi GitHub deposu,
- kendi bilgisayarındaki proje klasörü

içinde saklanabilir.

---

# Proje Çalışmaları

Derslerin ilerleyen bölümlerinde öğrencilerden yalnızca notebook örneklerini tekrar etmesi değil, kendi projelerini geliştirmesi beklenmektedir.

Örnek proje alanları:

- veri analizi,
- yapay zeka,
- robotik,
- doğal dil işleme,
- görüntü işleme,
- web uygulamaları,
- RAG sistemleri,
- LLM destekli uygulamalar.

Bitirme aşamasında öğrencilerin problem tanımlaması, veri hazırlaması, model veya yapay zeka yöntemini seçmesi, uygulamayı test etmesi ve sonuçlarını sunması beklenmektedir.

---

# Kaynak Kod ve Sorumluluk

Bu depo eğitim amacıyla hazırlanmıştır.

Kod örnekleri öğrenme, geliştirme ve proje üretme amacıyla kullanılmalıdır.

Öğrenciler yazdıkları veya yapay zeka araçlarından aldıkları kodların ne yaptığını anlamalı ve çalıştırmadan önce kontrol etmelidir.

Özellikle internetten veya yapay zeka araçlarından alınan bilinmeyen kodların doğrudan çalıştırılması önerilmez.

---

# Sonuç

Bu depo temel Python programlamadan başlayarak öğrenciyi adım adım gerçek bir yapay zeka uygulaması geliştirebilecek seviyeye taşımak amacıyla hazırlanmıştır.

Derslerin sonunda öğrencilerin:

```text
Python yazabilmesi
+
veri analiz edebilmesi
+
makine öğrenmesi modeli geliştirebilmesi
+
yapay zeka sonuçlarını değerlendirebilmesi
+
veritabanı kullanabilmesi
+
web uygulaması geliştirebilmesi
+
LLM ve RAG sistemlerini anlayabilmesi
+
kendi projesini geliştirebilmesi
```

hedeflenmektedir.

Ana ders kaynağı GitHub, uygulama ve deneme ortamı ise Google Colab ve öğrencinin kendi bilgisayarıdır.
