﻿# Patika.dev & Logo Yazılım .NET Core Bootcamp Bitirme Projesi : Invoice Management System
Bir sitede yer alan dairelerin aidat ve ortak kullanım; elektrik, su ve doğalgaz faturalarının yönetimini 
gerçekleştirebildiğimiz bir sistemdir. Bu sistemde iki tip kullanıcı vardır:

## Proje Tanımı

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
● Hangi blokda ● Durumu (Dolu-boş) ● Tipi (2+1 vb.) ● Bulunduğu kat

### Kullanıcı bilgilerinde:
● Ad-soyad ● TCNo ● E-Mail ● Telefon ● Araç bilgisi(varsa plaka no) bulunur.

### Kredi Kartı ile Ödeme Servisi:
❌ Sistemdeki her bir kullanıcı için banka bilgileri (bakiye, kredi kartı no vb.) kontrol edilerek ödeme yapılması sağlanır.  
✔️ Ödeme sadece kredi kartı ile yapılabilir.  
✔️ Veriler MongoDB'de tutulmalı. Servis .Net WebApi olarak yazılacaktır.  

## Projede Kullanılan Teknolojiler
- Backend: .Net Core - C# | Frontend: Razor
- Sistemin yönetimi/database: MS SQL Server - MongoDB

## Tamamlanan Modüller ve Ekran Görüntüleri



## Eksik Modüller
❌ Mesajlaşma modülü tamamlanamadı.  
❌ Kredi kartı ile ödeme servisi düzgün çalışmamaktadır.  