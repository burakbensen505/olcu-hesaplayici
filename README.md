

Mobilya üreticileri ve hobi amaçlı marangozlar için geliştirilmiş, web tabanlı bir kabin (modül) ölçülendirme ve plaka kesim optimizasyon aracıdır. Bu proje, malzeme fire oranını en aza indirerek maliyetleri düşürmeyi ve üretim sürecini hızlandırmayı hedefler. Uygulama, tüm işlemleri tarayıcı üzerinde yerel olarak gerçekleştirir ve herhangi bir sunucuya ihtiyaç duymaz.

✨ Öne Çıkan Özellik: Malzeme Gruplama

Bu sürümdeki en önemli yenilik, kesilecek parçaların malzeme kalınlığına göre otomatik olarak gruplanmasıdır.

    Sorun: Önceki versiyonlarda, 18mm'lik gövde parçaları ile 3mm'lik arkalık parçaları aynı optimizasyon havuzunda değerlendirilebiliyordu. Bu, gerçek üretim süreçleriyle uyumsuzdu.

    Çözüm: v4 ile birlikte, farklı kalınlıktaki malzemeler (örneğin 18mm gövde suntası ve 3mm arkalık) ayrı ayrı gruplanır ve her grup kendi plaka tipi üzerinde optimize edilir. Bu sayede, her malzeme türü için gereken plaka sayısı ve fire oranı gerçeğe en uygun şekilde hesaplanır.

🚀 Temel Özellikler

    Dinamik Kabin Tasarımı:

        Standart kapaklı ve çekmeceli modül tipleri oluşturma.

        Genişlik, yükseklik, derinlik, raf ve kapak/çekmece sayısı gibi parametreleri belirleme.

    Detaylı Proje Ayarları:

        Gövde birleşim tipi (Yandan/Üstten Basma).

        Malzeme kalınlıkları (Gövde, Arkalık).

        Üretim payları (Testere payı, Kenar bandı, Fuga boşluğu, Ray boşluğu).

    Akıllı Kesim Optimizasyonu:

        Parçaları, belirlenen plaka ölçülerine en az fire verecek şekilde yerleştiren 2D bin-packing (Maximal Rectangles) algoritması.

        Her malzeme kalınlığı için ayrı optimizasyon ve fire hesabı.

    Görsel Plaka Planı:

        Optimize edilmiş plakaların kesim planını interaktif olarak <canvas> üzerinde görselleştirme.

        Plakalar arasında kolayca geçiş yapma.

    Detaylı Kesim Listesi:

        Gerekli tüm parçaları; adı, adedi, ölçüleri ve ait olduğu kabin bilgisiyle birlikte liste halinde sunma.

        Malzeme kalınlığına göre gruplandırılmış tablolar.

    Proje Yönetimi:

        Mevcut projeyi tarayıcının yerel depolama alanına (localStorage) kaydetme.

        Kaydedilmiş projeyi geri yükleme.

        Tek tıkla yeni ve temiz bir projeye başlama.

    📄 PDF Raporlama:

        Tüm proje özetini, malzeme ihtiyaç listelerini ve görsel kesim planlarını içeren detaylı bir PDF raporu oluşturma.

🛠️ Kullanılan Teknolojiler

    Frontend: HTML5, CSS3, Vanilla JavaScript (ES6+)

    Styling: Tailwind CSS

    PDF Kütüphaneleri:

        jsPDF

        jsPDF-AutoTable

📖 Nasıl Kullanılır?

    Ayarları Yapılandırın: Sol üstteki "Proje Ayarları" kartından imalat standartlarınıza uygun gövde, arkalık, testere payı gibi değerleri girin.

    Kabin Ekle: "Yeni Kabin Ekle" formunu kullanarak projenize dahil etmek istediğiniz modüllerin özelliklerini girin ve "Kabini Projeye Ekle" butonuna tıklayın.

    Projeyi Gözden Geçirin: Eklediğiniz tüm kabinler "Proje Kabinleri" listesinde görünecektir. Düzenlemek için bir kabinin üzerine tıklayabilir, silmek için çöp kutusu ikonunu kullanabilirsiniz.

    Hesapla: Tüm kabinleri ekledikten sonra sağ bölümdeki "Hesapla" butonuna tıklayın.

    Sonuçları İnceleyin:

        Gerekli plaka sayısı ve fire oranları kartlarda gösterilir.

        "Kesim Listesi" tablosundan tüm parçaların ölçülerini kontrol edin.

        "Plaka Kesim Planı" bölümünden optimize edilmiş plakaların görsel yerleşimine göz atın.

    Rapor Alın: "Dışa Aktar" butonu ile projenizin tüm detaylarını içeren PDF dosyasını indirin.

    Kaydet/Yükle: Projenize daha sonra devam etmek için "Kaydet" butonunu kullanın.

📂 Yerel Ortamda Çalıştırma

Proje, herhangi bir bağımlılık veya derleme süreci gerektirmez.

    Bu repoyu klonlayın veya dosyaları ZIP olarak indirin.

    index.html dosyasını modern bir web tarayıcısında (Google Chrome, Firefox, Edge vb.) 
