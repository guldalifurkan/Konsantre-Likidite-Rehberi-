# Konsantre-Likidite-Rehberi-
Selamlar,DeFi ürünlerinin kullanımı söz konusu olduğunda akla gelen en önemli temel taş likidite kavramıdır. Geleneksel DeFi (1.0) uzun yıllar likidite sorununa çözüm arayışında olmuştur. Bu çözüm arayışları sonucunda ortaya çıkan ve DeFi araçları için kilometre taşlarından birisi olarak ifade edebileceğimiz gelişme ise ‘Konsantre Likidite’dir.
Konsantre likidite kavramını anlamadan önce likidite kavramının ne olduğuna bakmak gerekir.
Bir piyasada fiyatta çok önemli değişikliklere sebep olmadan bir varlığın alınıp satılabilmesine likidite denir.
Likidite kavramı iki farklı alanı ifade edebilir. Likit bir piyasa ve likit bir varlık.
Likit piyasa, piyasada işlem yapmak isteyen çok sayıda yatırımcı olduğuna işaret eder. Likit bir varlık ise kolayca nakde dönüştürülebilecek bir varlık anlamına gelir. 
Likidite eklemek; bir platformda işlem gören token çiftine ait havuza protokollerin izin verme durumuna göre birisini ya da her ikisini birden eklemektir. Geleneksel Likidite ekleme işlemini yaparken genellikle bir token çiftini aynı oranında havuza eklersiniz.
Örnek vermek gerekirse  herhangi bir platforma likidite ekleyebilmek için bir likidite pairine ihtiyacınız var bu $ETH — $USDT havuzuna ( Pool ) 1 $ETH likidite ekleyecekseniz $ETH ‘nin karşılık geldiği değer kadar da diğer tokenden eklemeniz gerekir.
İşlem yaptığınız sırada $ETH ‘nin 4000$ olduğunu varsayarsak havuza 4000 $USDT eklemeniz gerekir.
Mesela ETH fiyatı 4500$ oldu diyelim ne olacak,sonuçta pair eşit olmalı.
Böyle bi durumda Smart Contract ETH satıp havuzu dengeler.
ETH fiyatı düşerse bu sefer USDT satıp ETH alarak havuzu dengele.İsminin geçici kayıp olmasının nedeni budur.Fiyat bugün düştüyse yarın çıkarak yerine gelebilir.
Likidite eklemenin mantığını anladıysak ‘Konsantre Likidite’nin nasıl çalıştığına bakalım.
Konsantre likidite size işlem gören bir token çiftine ait belirli bir fiyat aralığına likidite eklemenize imkan sağlar. Bunun amacı fonlarınızı daha verimli kullanmaktır. Örneğin üstte bahsettiğim örnekte 8000$ likidite ekleyip elde edeceğiniz geliri, konsantre likidite ile dar bir fiyat aralığına 800$ ekleyerek de kazanabilirsiniz.
Yine örnekle açıklayalım. Üstte verdiğim örnekte havuz toplamı 80.000$ ve sizin payınız %10. Eğer tüm havuz yerine $ETH — $USDT için 3900$-4100$ aralığına 800$ likidite ekleseniz ve bu aralıktaki toplam likidite de $8000 dolar ise yine aynı oranda gelir elde edersiniz.
Hatta protokoller bunu yapmanızı daha cazip hale getirmek için fiyat aralığı daraldıkça sizden alacağı komisyon oranından feragat ederler.
Aşağıdaki görselde Uniswap’ın konsantre likidite havuzları için komisyon oranlarını görebilirsiniz. Görseldeki $ETH-$USDT havuzunda 5$’lık bir fiyat aralığına likidite eklemeniz durumunda platform komisyonu %0.05'e düşüyor. Tabii bu fiyat aralığı aslında daha çok stabil coin havuzları için avantajlı. ( Örn $USDT- $USDC )![Ekran görüntüsü 2024-06-04 040811](https://github.com/guldalifurkan/Konsantre-Likidite-Rehberi-/assets/107002954/b501e740-8908-4d0f-a4a4-896bf178c5ac)
