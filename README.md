# Dilim: veri kaynakları ve lisanslar

## Open Food Facts (ODbL 1.0)

Paketli ürün kayıtları (`src/data/packagedProducts.ts` ve `src/data/packagedProductsExtra.json`) Open Food Facts topluluk
veritabanından alınıp temizlenerek hazırlandı: barkod, ad, marka ve 100 g başına besin değerleri; adlar yazım olarak
düzeltildi, değerler tutarsızsa kayıt çıkarıldı.

- Kaynak: https://world.openfoodfacts.org (Open Food Facts katkıcıları)
- Veritabanı lisansı: Open Database License (ODbL) 1.0 — https://opendatacommons.org/licenses/odbl/1-0/
- İçerik lisansı: Database Contents License 1.0
- Bu kayıtlardan türeyen veritabanı (yukarıdaki iki dosya ve `tools/off_turkey/` betikleri) **ODbL 1.0 ile paylaşılır.**
  Uygulamanın geri kalanı (kod, arayüz, diğer veriler) bu lisansa tabi değildir.
- Ürün fotoğrafları kullanılmıyor (onlar CC BY-SA).
- Uygulama canlı aramada da Open Food Facts API'sini çağırır; kullanım kurallarına uygun User-Agent gönderir.

## USDA FoodData Central

`src/data/usdaFoods.json` ve hazır tarif şablonlarının malzeme değerleri ABD Tarım Bakanlığı FoodData Central
(SR Legacy ve FNDDS) verisinden alındı. Kamu malıdır, atıf zorunlu değildir; kaynak yine de belirtilir.
Tarif miktarları Dilim'in varsayımıdır, USDA'nın değil.

## Kullanılmayan kaynaklar

TürKomp verisi lisanslıdır ve kullanılmaz.
