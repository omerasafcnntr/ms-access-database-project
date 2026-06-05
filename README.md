# MS Access Veri Tabanı Projesi: Kişisel Ajanda ve Randevu Sistemi

## 📌 Proje Hakkında
Bu proje, kişisel bilgi yönetimi, ajanda takibi ve randevu sistemlerinin temel veri tabanı mantığını kavramak amacıyla **Microsoft Access** kullanılarak geliştirilmiştir. 

İlişkisel veri tabanı yönetim sistemlerinin (RDBMS) temellerini atmak üzere tasarlanan bu uygulama; kişilerin, adreslerin, notların ve randevuların birbirleriyle nasıl entegre bir şekilde çalıştığını pratik bir şekilde göstermektedir.

## ⚙️ Temel Özellikler
* **Yapılandırılmış Tablolar:** Verileri düzenli tutmak için `KİŞİLER`, `ADRESLER`, `AJANDA / NOTLAR`, `RANDEVULAR` ve `KATEGORİLER` olmak üzere birbiriyle ilişkili tablolar oluşturuldu.
* **Gelişmiş Sorgular:** Veri tabanı içinden spesifik verileri çekebilmek için çeşitli sorgular (Ada/soyada göre arama, tarih aralığına göre filtreleme, belirli kategoriye göre listeleme) yazıldı.
* **Kullanıcı Arayüzü (Formlar):** Veri girişini ve kullanım kolaylığını artırmak için bir `ANA MENÜ` tasarlandı. Ayrıca `KİŞİLER`, `AJANDA` ve `RANDEVULAR` için özel giriş formları oluşturuldu.
* **Raporlama:** Seçilen kişiye ait ajanda dökümleri ve tüm kişi listesi gibi verileri düzenli bir formatta sunan Access raporları hazırlandı.

## 🛠️ Kullanılan Teknolojiler
* **Veri Tabanı Yönetimi:** Microsoft Access
* **Kavramlar:** İlişkisel Veri Modeli (RDBMS), Temel Veri Tabanı Mimarisi, Form ve Rapor Tasarımı

## 🚀 Nasıl Çalıştırılır
1. Bu depoyu (repository) klonlayın veya `.zip` dosyası olarak indirin.
2. Bilgisayarınızda **Microsoft Access**'in yüklü olduğundan emin olun.
3. İndirdiğiniz klasördeki `.accdb` uzantılı veri tabanı dosyasını açın.
4. Formların düzgün çalışması ve doğrudan `ANA MENÜ` üzerinden işlem yapabilmek için Access uyarı verirse "İçeriği Etkinleştir" (Enable Content) seçeneğine tıklayın.

## 💡 Neler Öğrendim
Bu proje sayesinde, bir uygulamanın arka planındaki tablo ilişkilerini (primary/foreign key) kurmayı, bu tablolardan anlamlı veriler çekmek için sorgular oluşturmayı ve kullanıcı dostu bir arayüz tasarlamayı öğrendim. Burada attığım ilişkisel veri tabanı temelleri, güncel olarak geliştirdiğim **C#** ve **T-SQL** tabanlı projelerimdeki mimari kurgu için oldukça sağlam bir altyapı oluşturdu.
