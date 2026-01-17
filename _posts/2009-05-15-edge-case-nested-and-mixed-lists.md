---
title: "Autocad Trim komutu"
categories:
  - Tasarım
tags:
  - content
  - css
  - edge case
  - lists
  - markup
---

AutoCAD'de `TRIM` komutu, çizim üzerindeki nesnelerin istenmeyen fazlalıklarını kesmek/kırpmak için kullanılır. Aşağıda temel kullanım, örnekler ve pratik ipuçları adım adım verilmiştir.

**Temel adımlar**

1. Komutu başlatın: `TRIM` veya kısaca `TR` yazıp Enter'a basın.
2. Kesme kenarlarını (cutting edges) seçin: kırpma işleminin sınırlarını belirleyecek nesneleri tıklayın. Tüm mevcut nesneleri kesme kenarı olarak almak için doğrudan Enter tuşuna basın.
3. Kırpmak istediğiniz nesneleri seçin: kırpmak istediğiniz çizgileri, polylineleri veya kenarları tıklayın. Fare ile sürükleyerek crossing selection da yapabilirsiniz.
4. İşlemi bitirmek için Enter'a basın.

**Örnek kullanım senaryoları**

- Bir çizgiyi dairenin kenarına kadar kısaltmak: Önce `TRIM` komutunu başlatın, daireyi kesme kenarı olarak seçin (veya Enter ile tümünü seçin), sonra çizgiyi tıklayarak daireye göre kırpın.
- Fazla uzayan çizgi veya çizgi parçasını başka bir çizgiyle kesişen noktadan temizlemek: Kesişim çizgisini kesme kenarı seçip fazla kısmı tıklayın.

**Pratik ipuçları ve seçenekler**

- Kesme kenarlarını seçmek yerine Enter'a basarsanız AutoCAD tüm nesneleri kesme kenarı kabul eder; bu, hızlı küçük düzenlemeler için pratiktir.
- `Fence` (Çit) seçeneği: `TRIM` çalışırken `F` yazarak bir fence çizebilir ve fence ile kesişen tüm nesneleri tek adımda kırpabilirsiniz.
- `Shift` tuşu bazı AutoCAD sürümlerinde trim/extend modları arasında geçiş sağlar; gerektiğinde `EXTEND` komutunu kullanarak ters işlemi (uzatma) yapabilirsiniz.
- Yanlışlıkla fazla kırparsanız `U` (Undo) ile geri alabilirsiniz.

**İyi uygulamalar**

- Kırpmadan önce kesme kenarı olarak yalnızca gerçekten sınır oluşturan nesneleri seçin; gereksiz kenarlar karmaşaya yol açar.
- Karmaşık bölgelerde önce küçük bir alanla deneyin, sonra tüm çizime uygulayın.
- `TRIM` ile yapamadığınız düzenlemeler için `FILLET` (radyuslu köşe), `EXTEND` veya `BREAK` komutlarını değerlendirin.

