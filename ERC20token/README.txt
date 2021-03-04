ERC20 TOKEN - LimitToken (LMT)

ERC Token Standard #20 Interface'ini kullanarak kendi tokenimi oluşturdum.
İşlemler için Safe Math Library kullanıldı.
Bir tokenin ismi ve sembolü olması gerektiği için bu variablelar tanımlandı.
Constructor'da tokenın ismi, sembolü, decimali ve toplam miktarı belirlendi.

Sonrasında interface'te kullanılan fonksiyonların içi dolduruldu.
Fonksiyonlar:
totalSupply() -> Oluşturulan toplam ERC-20 token sayısını belirtir. 
balanceOf() -> Belirli bir adreste, contract sahibinin hesabında bulunan token sayısını döndürür.
allowance() -> Kullanıcının işlemi yapmak için gereken minimum miktarda tokena sahip olup olmadığını kontrol eder.
approve() -> Bakiye kontrol edildikten sonra onaylama işlemi için kullanılmaktadır.
transfer() -> Tüm kontroller yapıldıktan sonra, token sahibi transfer için bu fonksiyonu kullanabilir.
transferFrom()  -> Belirli bir hesaba payment transferlerini otomatik ödemeye döndürmeyi sağlar.

En çok kontrat adresimi bulurken zorlandım. Onu bulmaya çalışırken metamask'in tüm özelliklerini öğrendim. Birçok kez LMT'yi yollamayı denedim, source code'unu paylaştım. En sonunda kontrat adresimi bulabildim. 
