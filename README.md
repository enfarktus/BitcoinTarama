# BitcoinTarama
Kayıp Bitcoinleri Bulmaya Çalışıyoruz!

Gelişmeleri X'den paylaşıyorum! https://x.com/BitcoinBulmaca

KURULUM:
Kurulum gerekmez. Kodlar Python dilinde yazıldı, pyinstaller ile kolay çalıştırılabilir duruma getirildi. Dosyaları indirip, bir klasöre açın. "bitcointarama.exe" dosyasına tıkladığınızda çalışmaya başlayacak. 

YÖNTEM:
"bitcointarama.exe" dosyasına tıkladığınızda random olarak 64 karaktere sahip private keyler oluşturmaya başlar. Bu keylerden de Pay-to-Public-Key-Hash (P2PKH), Pay-to-Script-Hash (P2SH) ve Pay-to-Witness-Public-Key-Hash (P2WPKH) türü bitcoin adresleri oluşturulur. Oluşturulan adresler, "btcf.txt" dosyasında bulunan yaklaşık 7 milyon kayıtlı zengin adreslerle karşılaştırılarak, eşleşme tespit etmeye çalışır. Eşleşme bulunması demek, belirtilen adresin private keyinin bulunduğu anlamına gelir.

Aynı anda istediğiniz kadar "bitcointarama.exe" çalıştırabilirsiniz. Standart olarak aynı anda en fazla üç dosya çalıştırmanız önerilir. Programı her çalıştırdığınızda yeni ve benzersiz private keyler oluşturur. Bunun için random kütüphanesi kullanılmıştır.
Ekranda gördüğünüz "Toplam" değeri, program çalışmaya başladığından itibaren ürettiği toplam private key sayısını ifade eder.

EŞLEŞME BULDUĞUNUZDA:
Eşleşme bulmanız durumunda ekranda "BİNGOOOOO" şeklinde bir uyarı ile privkey ve adres bilgilerini göreceksiniz. Privkey ve adres bilgileri programın bulunduğu klasöre "XXXX.txt" adında bir dosya oluşturularak bu dosyaya yazılacaktır. 

Ödül paylaşımı %50 oranında yapılacaktır.

Sorularınız için: enfarktus0@gmail.com

0xe47BBeAc8F268d7126082D5574B6f027f95AF5FB
3FerqQF5DVY1tPCEV7nXENoqxuVHGLjRh3
