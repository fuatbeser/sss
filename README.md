# Sık Sorulan Sorular (Frequently Asked Questions)
Answers to commonly asked questions on AI (in Turkish)

Çeşitli zamanlarda yapay zekâ, makine öğrenmesi, derin öğrenme ve veri bilimi hakkında sorulan soruları bu repodan yanıtlayacağım. Herkesin faydalanması ve cevaplayabilmesi için yeni sorularınızı ilk olarak [Global AI Hub](http://community.globalaihub.com/) üzerinde bulunan [Turkish AI Hub](https://community.globalaihub.com/community-hubs/turkish-ai-hub/)'da sormanızı rica ederim. Tabii ki öncelikle [kayıt olmanız](https://community.globalaihub.com/register/) gerekiyor.

Bu çalışmayı faydalı bulduysanız ve daha fazla kişiye ulaşmasını isterseniz hemen üstteki Star butonuna hafifçe basarak yıldız verebilirsiniz.

### Bu alanda uzmanlaşmak için geç mi kaldık? 

Açıkcası herhangi bir konuyu öğrenmek ve o konuda uzmanlaşmak için geç olduğunu düşünmüyorum. Neredeyse her 15 dakikada 1 adet makine öğrenmesi makalesinin yayımlandığı ([bkz](https://data-mining.philippe-fournier-viger.com/too-many-machine-learning-papers/)) günümüzde hızlı öğrenen, hızlı adapte olanlar başarıya ulaşabilir. "Ben çok biliyorum. Kendimi geliştirmeme gerek yok." diyenler maalesef geride kalacaklar. Ne yapmak istediğinize karar verdikten sonra hızlı bir şekilde öğrenme ve uygulama sürecine geçmenizi tavsiye ederim. Şimdiye dek bu konuların öneminin farkında olmadığınız için geç kalmış olabilirsiniz. Fakat önemini bildiğiniz halde öğrenmek için adım atmadan geçirdiğiniz her bir yıl artık sizin "tercihiniz" olur.

### Yapay zekâ alanında yeterli talep oluşacak mı sizce?

Şirketlerin yatırımları ve bu alanda yayımlanan iş ilanlarının sayısındaki artış dikkate alındığında; her sene katlanarak artan bir talep olduğu açıktır. 2020 yılı için LinkedIn tarafından yayımlanan [LinkedIn’s 2020 Emerging Jobs](https://blog.linkedin.com/2019/december/10/the-jobs-of-tomorrow-linkedins-2020-emerging-jobs-report) raporuna göz atabilirsiniz. Raporda da belirtildiği üzere; teknik yetkinliklerin yanı sıra otomasyonun artması ile birlikte iletişim, yaratıcılık ve iş birliği gibi "soft skilller" her zamankinden daha fazla önem kazanmaya başlıyor.

### Bu alanda kendini geliştirmek isteyenlere ne tavsiye edersiniz?

Sırasıyla aşağıdaki başlıkları öğrenmenizi tavsiye ederim:

* Yapay Zekanın Temelleri
  * Kodlama ve teknik kısımların olmadığı bu ilk kısmı atlamamanızı tavsiye ederim. Genel resme hakim olmak her zaman işinize yarayacak.
* Programlama Dili
  * Şu an yaygın olarak Python kullanılıyor. Fakat R, Scala, Julia, Go gibi dillerde de kendinizi geliştirebilirsiniz. Python öğrenmek için [Python Notlarım](https://github.com/fuatbeser/python-notlarim) isimli repoma göz atabilirsiniz.
* İstatistik ve Matematik
  * Tüm algoritmaların arka planında istatistik ve/veya matematik olduğu için bu kısmı da ihmal etmemenizi öneririm. Bazı kütüphaneler yardımıyla bu matematiksel işlemleri elle yapmıyoruz çoğunlukla ama bir modeli geliştirmek için ileride ihtiyacınız olacak. 
* Makine Öğrenmesi/Derin Öğrenme/Veri Bilimi
  * Makine öğrenmesinde bulunan algoritmalara hakim olmanız çok önemli. 
   * Algoritmalar nasıl çalışır? 
   * Arkasında nasıl bir matematik var? 
   * Algoritmalarda hangi parametreler var? 
   * Sıfırdan nasıl gerçekleniyor (implemente edilir)? 
   * Kütüphaneler kullanılarak nasıl gerçeklenir?
   * En çok hangi problemler çözmek kullanılıyor?
   * Algoritmanın artısı ve eksisi nedir?
  
Makine öğrenmesi yöntemlerinden birisi de yapay sinir ağlarıdır. Özellikle bilgisayarlı görü (computer vision), ses tanıma ve işleme (speech recognition and processing) ya da doğal dil işleme (natural language processing) gibi alanlarda çalışmak istiyorsanız yapay sinir ağlarıyla -yani derin öğrenme- çalışmanız gerekecek. Görüntü, ses ve metinlere yapısal olmayan veriler (unstructured data) deniliyor. 

Yapısal verilerle (structured data) çalışırken ise veri bilimi, makine öğrenmesi, istatistik yöntemlerini iyice öğrenmelisiniz. Yeni başlayan birinin hangi alanda çalışacağı henüz belli olmadığı için bu konuların mümkünse hepsinde ya da çoğunda projeler geliştirmenizi tavsiye ederim.
  
### Reinforcement learning (pekiştirmeli öğrenme) tam olarak nedir?

Günümüzde makine öğrenmesi yöntemlerinden en çok gözetimli öğrenme (supervised learning) kullanılıyor. Fakat gözetimli öğrenme çok fazla etiketli veri gerektiriyor. Bu nedenle kendi kendine karar vermekten biraz uzak. Etiketsiz verinin olmadığı gözetimsiz öğrenme (unsupervised learning) ve farklı bir çalışma şekli olan pekiştirmeli öğrenme (reinforcement learning) üzerine yapılan araştırmalar da hız kazandı. Yapay zekâ sistemlerinin kendi kendine öğrenmeyi öğrenmesi ve kararlar alabilmesi gerekiyor. Peki bunu hangi algoritma ile yapabiliriz? Pekiştirmeli öğrenme, bunu gerçekleştirebileceği düşünülen güçlü adaylardan birisidir. Günümüzde özellikle robotik ve oyun alanlarında kullanılmaya başlandı.

Pekiştirmeli öğrenme, kendisine konulan hedefe göre hangi aksiyonların alınmasını gerektiğini kendi başına öğrenen bir makine öğrenmesi yaklaşımıdır. Bu yaklaşıma göre; başlangıç anından itibaren bir sanal ajan (agent) karşılaştığı olaylara ve çevreden aldığı tepkilere göre bir aksiyon alır. Buna karşılık da bir ödül (ya da ceza) alır. Süreç boyunca ajanın görevi en fazla ödülü alabileceği aksiyonları keşfetmektir.

### Yapay zeka ile ilgilenen birisi iş dünyasında hangi pozisyonda çalışabilir? Sadece veri bilimci olarak mı?

Hem teknik hem de iş dünyası tarafında farklı pozisyonlar var. Aşağıdaki pozisyonlar en başlıcaları ama farklı şirketlerde farklı isimlendirmeler oluyor:

- Data Scientist
- Data Engineer
- Machine Learning Engineer
- Machine Learning Researcher
- Deep Learning Engineer
- Deep Learning Researcher
- Data Analyst
- Software Engineer (Machine Learning)
- Software Engineer (Deep Learning)
- AI Product Manager

Bu pozisyonların her biri için farklı seviyelerde veri bilimi, makine öğrenmesi, matematik, algoritmik kodlama, yazılım, iletişim ve (kıvrak) iş zekası gerekiyor.
