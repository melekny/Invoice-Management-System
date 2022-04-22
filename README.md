# Patika.dev & Logo Yazılım .NET Core Bootcamp Bitirme Projesi : Invoice Management System
## Proje Tanımı
Bir sitede yer alan dairelerin aidat ve ortak kullanım; elektrik, su ve doğalgaz faturalarının yönetimini 
gerçekleştirebildiğimiz bir sistemdir. Bu sistemde iki tip kullanıcı vardır:

### 1- Admin/Yönetici
✔️ Daire bilgilerini girebilir.  
✔️ İkamet eden kullanıcı bilgilerini girer.  
✔️ Daire başına ödenmesi gereken aidat ve fatura bilgilerini girer(Aylık olarak). Toplu veya tek tek atama yapılabilir.  
✔️ Gelen ödeme bilgilerini görür.  
❌ Gelen mesajları görür.  
❌ Mesajların okunmuş/okunmamış/yeni mesaj olduğu anlaşılmalı.  
✔️ Aylık olarak borç-alacak listesini görür.  
✔️ Kişileri listeler, düzenler, siler.  
✔️ Daire/konut bilgilerini listeler, düzenler siler.  

### 2-Kullanıcı
✔️ Kendisine atanan fatura ve aidat bilgilerini görür.  
✔️ Sadece kredi kartı ile ödeme yapabilir.  
❌ Yöneticiye mesaj gönderebilir.  
❌ Mesajların okunmuş/okunmamış/yeni mesaj olduğu anlaşılmalı.  
✔️ Yaptığı ödemelerini görür.  

### Daire/Konut bilgilerinde:
● Hangi blokda ● Durumu (Dolu-boş) ● Tipi (2+1 vb.) ● Bulunduğu kat bulunur.

### Kullanıcı bilgilerinde:
● Ad-soyad ● TCNo ● E-Mail ● Telefon ● Araç bilgisi(varsa plaka no) bulunur.

### Kredi Kartı ile Ödeme Servisi:
❌ Sistemdeki her bir kullanıcı için banka bilgileri (bakiye, kredi kartı no vb.) kontrol edilerek ödeme yapılması sağlanır.  
✔️ Ödeme sadece kredi kartı ile yapılabilir.  
✔️ Veriler MongoDB'de tutulmalı. Servis .Net WebApi olarak yazılacaktır.  

## Projede Kullanılan Teknolojiler
- Backend: .Net Core - C# | Frontend: Razor
- Sistemin yönetimi/database: MS SQL Server - MongoDB

## Tamamlanan Modüller ve Uygulama Ekran Görüntüleri

✔ Kullanıcıların sisteme erişimi için Giriş ve Kayıt ekranları oluşturulmuştur.  
![Login_Page](https://github.com/melekny/Invoice-Management-System/blob/main/Images/Login_Page.png)
![Register_Page](https://github.com/melekny/Invoice-Management-System/blob/main/Images/Register_Page.png)

✔ "Ana Sayfa" üzerinden diğer sayfalara ulaşılabilir.

✔ Yönetici, "Apartmanlar" sayfasında; apartman bilgisi ekleme, listeleme, düzenleme ve silme işlemlerini yapabilir.

✔ Yönetici, "Daireler" sayfasında; daire/konut bilgisi ekleme, listeleme, düzenleme ve silme işlemlerini yapabilir.

✔ Yönetici, "Kullanıcılar" sayfasında; sitede ikamet eden kullanıcı bilgisi ekleme, listeleme, düzenleme ve silme işlemlerini yapabilir.  

✔ Yönetici, "Faturalar" sayfasında; fatura bilgisi ekleme, listeleme, düzenleme ve silme işlemlerini yapabilir.  

✔ Yönetici, "Profilim" sayfasında; kullanıcı bilgisini düzenleyebilir.

✔ Kullanıcılar, "Faturalar" sayfasında; yönetici tarafından atanan fatura ve aidat bilgilerini görebilirler.

✔ Kullanıcılar, ödeme modülüyle; sadece kredi kartı ile ödeme yapabilir ve ödemelerini görüntüleyebilirler.  



## Eksik Modüller
❌ Mesajlaşma modülü tamamlanamadı.  
❌ Kredi kartı ile ödeme servisi için MongoDB bağlantısı yapılmış ve Web API şeklinde oluşturulmuştur. Ancak düzgün çalışmamaktadır.  