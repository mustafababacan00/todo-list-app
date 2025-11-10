# TO-DO LIST UYGULAMASI

Python ile geliştirilmiş basit ve kullanışlı bir yapılacaklar listesi uygulaması.

## Projenin Amacı

Bu To-Do List uygulaması, kullanıcıların günlük görevlerini kolayca yönetmelerini sağlar. Python ile Google Colab ortamında çalışır ve tüm görevler "gorevler.txt" dosyasına otomatik kaydedilir.

## Kullanıcı Arayüzü

Program çalıştırıldığında 5 seçenekli bir menü görüntülenir:

```
1. Görevleri Listele
2. Yeni Görev Ekle
3. Görev Düzenle
4. Görev Sil
5. Çıkış
```

## Temel İşlevler

1. **Görevleri Listele**
Tüm görevleri numaralı liste halinde gösterir. Liste boşsa bilgi mesajı verir.

2. **Yeni Görev Ekle**
Görev metnini yazıp Enter'a basarak yeni görev eklersiniz. Boş görev eklenemez.

3. **Görev Düzenle**
Düzenlemek istediğiniz görevin numarasını seçip yeni metni yazarsınız. Geçersiz numara veya boş metin kabul edilmez.

4. **Görev Sil**
Silmek istediğiniz görevin numarasını girerek listeden kaldırırsınız. Geçersiz numara hata verir.

5. **Çıkış**
Programı güvenli şekilde kapatır.

## Önemli Özellikler

- **Otomatik Kayıt:** Her işlemden sonra görevler dosyaya kaydedilir
- **Kalıcı Veri:** Program her açıldığında önceki görevler yüklenir
- **Türkçe Destek:** UTF-8 kodlama ile Türkçe karakterler sorunsuz çalışır
- **Hata Kontrolü:** Geçersiz girişlerde anlaşılır hata mesajları gösterilir

## Kurulum ve Kullanım

### Google Colab'da Çalıştırma

1. Kodu Google Colab hücresine yapıştırın
2. `Shift + Enter` ile çalıştırın
3. Menüden işlem numarasını seçin
4. İşlemleri tamamlayın

### Yerel Bilgisayarda Çalıştırma

```bash
# Dosyayı indirin
git clone https://github.com/mustafababacan00/todo-list-app.git

# Klasöre gidin
cd todo-list-app

# Programı çalıştırın
python todo_list.py
```

## Dosya Yapısı

```
todo-list-app/
│
├── todo_list.py      # Ana program dosyası
├── gorevler.txt      # Görevlerin kaydedildiği dosya (otomatik oluşturulur)
└── README.md             
```

## Kullanım İpuçları

- Her işlem sonrası "Enter'a basın" mesajı gösterilir
- Görevleriniz otomatik kaydedilir
- Türkçe karakterleri rahatlıkla kullanabilirsiniz
- Program sezgisel tasarımı sayesinde kolay öğrenilebilir


```
TO-DO LIST UYGULAMASI
======================
1. Görevleri Listele
2. Yeni Görev Ekle
3. Görev Düzenle
4. Görev Sil
5. Çıkış
=======================
```
**Not:** Görevleriniz "gorevler.txt" dosyasına kaydedildiği için verileriniz kaybolmaz.

## Geliştirici

Mustafa Babacan  
mail: mustafababacan000@gmail.com
