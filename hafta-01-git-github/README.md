Hafta 1
# Hafta 1: Git ve GitHub

## Araştırma
* **Git ve GitHub Nedir?:** Git, projelerdeki kaynak kod değişikliklerini takip eden yerel bir versiyon kontrol sistemidir. GitHub ise bu projelerin bulut ortamında barındırılmasını ve takım çalışmasını sağlayan platformdur.
* **Kavramlar:** 
  * **Repository:** Proje dosyalarını ve geçmişini tutan ana depodur.
  * **Commit:** Değişikliklerin anlık görüntüsünün kalıcı olarak kaydedilmesidir.
  * **Branch ve Merge:** Branch yeni özellikler için açılan paralel çalışma dalıdır. Merge bu dallardaki kodların birleştirilmesidir.
  * **Clone, Pull, Push:** Clone uzak depoyu yerele kopyalar. Pull güncellemeleri çeker. Push ise yereldeki commitleri GitHub'a gönderir.
  * **.gitignore:** Git'in takip etmemesi gereken, şifre veya bağımlılık klasörleri gibi dosyaları belirtir.
* **Çözdüğü Problem ve Sektörel Kullanımı:** Kod kayıplarını engeller ve aynı anda birden fazla geliştiricinin kod çakışması yaşamadan çalışmasını sağlar.
* **Avantajları, Dezavantajları ve Alternatifleri:** Hata yapılan eski bir koda dönmek çok kolaydır. Dezavantajı ise başlangıç aşamasındaki dik öğrenme eğrisidir. Sektördeki popüler alternatifleri GitLab ve Bitbucket'tır.

## Sektörde Kullanımı
Versiyon kontrol sistemleri yazılım sektöründe takım çalışmasının temelidir. Farklı geliştiricilerin aynı proje üzerinde birbirlerinin kodlarını ezmeden çalışabilmesini sağlar. Açık kaynak projelerin geliştirilmesinden, büyük şirketlerin kurumsal projelerine kadar her alanda kodun geçmişini tutmak, geri alabilmek ve güvenle saklamak için kullanılır.

## İncelediğim Projeler
1. **Laravel**
   * **GitHub Adresi:** https://github.com/laravel/laravel
   * **Kullanılan Dil / Framework:** PHP / Laravel
   * **Projenin Amacı:** Gelişmiş sözdizimi ile hızlı ve modern web uygulamaları geliştirmek için kullanılan framework.
   * **Commit / Contributor Sayısı:** 7.000+ commit, 600+ contributor.
   * **Klasör / README Yapısı:** `src`, `config`, `tests` gibi yapısal klasörlere ayrılmıştır. README dosyasında resmi dokümantasyon ve sponsor bağlantıları yer alır. Mimarisinin modüler ve anlaşılır olması dikkat çekicidir.

2. **Bootstrap**
   * **GitHub Adresi:** https://github.com/twbs/bootstrap
   * **Kullanılan Dil / Framework:** HTML, CSS, JavaScript
   * **Projenin Amacı:** Duyarlı (responsive) ön yüz bileşenleri oluşturmayı sağlayan tasarım kütüphanesi.
   * **Commit / Contributor Sayısı:** 22.000+ commit, 1.300+ contributor.
   * **Klasör / README Yapısı:** `scss` ve `js` klasörlerinde kaynak kodlar tutulur. Grid sisteminin parçalara ayrılmış yapısı dikkatimi çekti.

3. **React**
   * **GitHub Adresi:** https://github.com/facebook/react
   * **Kullanılan Dil / Framework:** JavaScript / TypeScript
   * **Projenin Amacı:** Kullanıcı arayüzleri inşa etmek için bileşen tabanlı kütüphane.
   * **Commit / Contributor Sayısı:** 16.000+ commit, 1.600+ contributor.
   * **Klasör / README Yapısı:** `packages` klasörü altında alt paketler (monorepo) barındırır. README'si projeye nasıl katkı yapılacağını adım adım anlatır.

## Yaptığım Uygulama
Dönem boyunca geliştireceğim "Oyunlaştırılmış Görev, Onay ve Ödül Portalı" web projesi için temel HTML iskeletini ve gerekli arayüz taslaklarını (yönetici paneli, görevler, ödüller) projeye dahil ettim.

* **GitHub Reposu:** [https://github.com/DanubioF/web-programciligi-3]
* **Kurulum ve Çalıştırma:** Repoyu `git clone` komutu ile indirdikten sonra HTML dosyalarını tarayıcıda açarak veya yerel sunucu (Laragon vb.) üzerinden doğrudan çalıştırabilirsiniz.
* **Commit Geçmişim:** 
  1. Proje dokümantasyonu ve 1. hafta araştırma raporu eklendi
  2. Kullanıcı giriş ekranı ve temel portal iskeleti oluşturuldu
  3. Öğrenci görev listeleme ve onay arayüz taslağı eklendi
  4. Kazanılan puanlar ve ödül marketi sayfası oluşturuldu
  5. Yönetici paneli sayfası eklendi

## Karşılaştığım Problemler
Terminalde commit atarken mesajın sonundaki tırnak işaretini kapatmayı unuttuğum için Git dosyaları bulamadı ve `error: pathspec` hatası verdi. Ayrıca terminalde kopyala-yapıştır işlemi sırasında PowerShell `>>` satırında takılı kaldı. Bu sorunu `Ctrl+C` kısayolu ile işlemi iptal edip terminali temizleyerek çözdüm.

## Öğrendiklerim
Sıfırdan bir yerel depo oluşturmayı (`git init`), dosyaları takibe alıp commit atmayı ve bu yerel depoyu GitHub'daki uzak sunucuya bağlayarak (`git remote add origin`) kodları yüklemeyi (push) pratik olarak deneyimledim. Git ve GitHub arasındaki farkı uygulamalı olarak kavramış oldum.

## Kaynaklar
* GitHub Resmi Dokümantasyonu (docs.github.com)
* Git SCM (git-scm.com/doc)