# Dilim: gizlilik politikası ve açık veri

Bu depo, Dilim kalori takip uygulamasının gizlilik politikasını ve uygulamada kullanılan paketli ürün veritabanını içerir.

- Gizlilik politikası: `index.html` (GitHub Pages ile yayınlanır)
- Paketli ürün veritabanı: `veri/dilim-paketli-urunler.json`

## Paketli ürün veritabanı (ODbL 1.0)

`veri/dilim-paketli-urunler.json` dosyasındaki 2641 ürün kaydı [Open Food Facts](https://world.openfoodfacts.org) veritabanından
(Open Food Facts katkıcıları) alınıp uyarlanmıştır: barkod, ürün adı, marka ve 100 g başına besin değerleri. Ad ve marka yazımları
düzeltildi, tutarsız ya da eksik besin değerli kayıtlar, alkollü ürünler ve takviyeler çıkarıldı, bazı kayıtlara lif, şeker ve tuz
değerleri eklendi. Değerler olduğu gibi etiketten gelir, Dilim tarafından hesaplanıp tahmin edilmedi.

Bu uyarlanmış veritabanı, kaynağıyla aynı lisans olan **Open Database License (ODbL) 1.0** ile paylaşılır:
<https://opendatacommons.org/licenses/odbl/1-0/>. Veritabanının içeriği [Database Contents License 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)
kapsamındadır. Kaynak ve atıf: Open Food Facts katkıcıları, <https://world.openfoodfacts.org>.

Ürün fotoğrafları bu depoda yoktur ve Dilim'de kullanılmaz.

## Kayıt biçimi

Her kayıt: `id`, `barcode`, `name`, `brand` (isteğe bağlı), `caloriesPer100g`, `proteinPer100g`, `carbsPer100g`, `fatPer100g`
ve varsa `fiberPer100g`, `sugarPer100g`, `saltPer100g` (hepsi gram; alan yoksa değer bilinmiyor demektir, sıfır değildir).

## Diğer kaynaklar

Ham gıdaların besin değerleri ABD Tarım Bakanlığı FoodData Central (SR Legacy ve FNDDS) verisinden alınmıştır, kamu malıdır.

## İletişim

Ahmet Piskin, <ahmetpiskin04@gmail.com>
