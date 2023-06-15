# C-file-operation-example
searching and scanning the file
dowland it kısmını indirip masaüstüne kurun ve yazılan kod ile üniversite  dosyasında güncellem ve arama yapın şu koşullar ile :
Dosya İçeriği
İç içe klasörlerden oluşan bir universite adlı ana klasör bulunmaktadır. Ana klasör altında
bolumler ve dersler olmak üzere en az iki adet alt klasör bulunmaktadır. (Değerlendirme esnasında daha
fazla klasör içeren örnek verilebilir. Arama işlemi tüm alt klasörlerde yapılmalıdır.) Alt klasörlerde bir
veya daha fazla txt dosyası ve farklı uzantılarda (.docx, .config, .png, .gif vb.) birçok dosya
bulunmaktadır. Her txt dosyasının içerisinde metin ve bu metinler içerisinde etiketler bulunmaktadır.
Bir etiket birden fazla txt dosyası içerisinde geçebilir.
 Etiket formatı:
o Eğer bir kelime etiket ise formatı şu şekillerde olmalıdır:
 [[kelime]], [[kelime1 kelime2]]
o Hatalı etiket formatları:
 [[kelime], [kelime]], [kelime], {{kelime}} vb.
 Yetim etiket:
o Alt klasörlerde etiketlere ait txt dosyaları bulunmaktadır. Ancak her etikete ait txt
dosyası olmak zorunda değildir. Aynı şekilde her txt dosyasının etiketi olmak
zorunda değildir.
o Eğer bir etikete ait txt dosyası yoksa o etiket, yetim etikettir.
Ders Şablon İçeriği
Her bir dersin bir kodu, adı ve içeriği olmalıdır. Tüm dersler bu şablona uygun olmalıdır.

Arama 
Kullanıcı kelime ve etiket araması yapabilmelidir. Aranan kelime etiket olabileceği gibi etiket
olmayan bir kelime de olabilir. Arama fonksiyonu bu iki kontrolü de sağlamalıdır. Arama sonucunda
hangi dosyada, hangi satır/satırlarda arama ifadesinin geçtiği ekranda yazdırılmalıdır. Ayrıca arama ara
yüzünde yetim etiketler ve istenen etiketler listelenmelidir.
Yetim etiket: Dosyası olmayan etiket
İstenen etiket: Dosya var fakat etiket yok. Dosya ismi veritabanı_yonetimi.txt olduğunda
istenen etiket : veritabanı yönetimi olmalıdır.
Güncelleme 
Kullanıcı bir etiketin adını değiştirebilir. Örneğin veritabaniyonetimi.txt dosyasında
[[veritabaniyonetimi]] etiketi değiştirilip [[veritabani yönetimi]] olduğunu varsayalım. Bu durumda
yeni txt dosyasının adı da veritabani_yonetimi.txt şeklinde olmalıdır.
Yetim bir etiketin txt dosyası oluşturulurken, oluşturulan txt dosyası yukarıda belirtilen ders
şablon içeriğine uygun olmalıdır. Burada Dersin Kodu 200’den başlayarak artarak atanmalıdır. Dersin
Adına yetim etiket atanmalıdır. Dersin içeriği boş olmalıdır. Dolayısıyla artık yetim olmayan bu etiketin
yetim etiketler listesinden silindiğinden emin olunmalıdır.
Dosyaya Yazma
Ana klasörün içerisinde bir output.txt dosyası olmalıdır ve programın tüm çıktıları bu dosyaya
yazdırılmalıdır. Çıktılarda tüm etiketler listelenmeli, toplamda kaç adet olduğu bilgisi yer almalıdır.
Bunun yanı sıra yetim etiketlerin de listesi oluşturulmalıdır. Örnek output.txt Şekil 2’de verilmiştir.
