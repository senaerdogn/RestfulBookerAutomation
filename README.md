# RestfulBookerAutomation
 Postman API Testi
 
# Restful Booker API Testleri
Bu repo, [Restful Booker](http://restful-booker.herokuapp.com/apidoc/index.html) API'sinin Postman kullanılarak yapılan testlerini içerir.

## Gereksinimler
Bu projeyi kullanmak için aşağıdaki araca ihtiyacınız olacak:
- [Postman](https://www.postman.com/downloads/)

## Kurulum
Bu repo'yu yerel bilgisayarınıza klonlayın:
```bash
git clone https://github.com/kullaniciadi/restful-booker-api-tests.git

**Koleksiyonların Kullanımı**
Postman'i açın ve File > Import seçeneğine tıklayın.
Bu repo içindeki .json uzantılı dosyaları seçin ve import edin.
Koleksiyonları kullanarak Restful Booker API'sini test edin.

**Testler**
API'nin temel fonksiyonlarını ve hata durumlarını test eden çeşitli testler Postman koleksiyonlarına dahil edilmiştir.
Test edilen başlıca özellikler şunlardır:
CreateToken: PUT ve DELETE/booking erişimi için kullanılacak yeni bir token oluşturur.
GetBookingIds: API içinde var olan tüm rezervasyonların id'lerini döndürür.
GetBooking: Mevcut bir rezervasyonu döndürür.
CreateBooking: Yeni bir rezervasyon oluşturur.
UpdateBooking: Var olan bir rezervasyonu günceller.
PartialUpdateBooking: Var olan bir rezervasyonu kısmi günceller.
DeleteBooking: Rezervasyonu siler.

**Environment Variables**
authToken: CreateToken isteğinden alınan token'ı depolamak için kullanılır.
bookingId: İstekler sırasında oluşturulan veya alınan rezervasyonların id'sini depolamak için kullanılır.


--> Bu proje "AkakçeRestfulAutomation" monitorü oluşturularak otomasyona bağlanmıştır. Testler başarıyla koşturulmuş olup, test sonuçlarının ekran görüntüsü 'Images' klasörüne eklenmiştir. <--
