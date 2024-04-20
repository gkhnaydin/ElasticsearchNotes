# Elasticsearch Nedir ?
1-Bir search ve analytics enginedir.
2-Java ile Apache lucene üzerinde geliştirilmiştir.
3-Kullanımı ve ölçeklendirilmesi kolaydır.
4-Tüm data tipleri için near real time search ve analytics işlemleri sunar. (Gerçek zamanlı işlemler yapılabilir. Bir veriyi indekslediniz yani elastic search üzerinde tutmaya 
başladınız bir sn sonra bu veri search ya da analiz edilebilir demek anlamına gelmektedir.)
5-Verinin dağıtık tutulması ile hizmet vermektedir.

Kullanım alanları(Use cases)
1-Search işlemi gerektiren uygulamalarda sıklıkla kullanılır.
2-Auto-completion (Otomatik tamamlama, web sitelerinde sıklıkla görülen bir özellik.)
3-Sistem loglarını,metriklerini ve security event datalarını depolayıp analiz etmeyede yarar.
4-Elastic Search ve Kibana kullanılarak  Machine Learning modelleri ile veriyi gerçek zamanlı analiz etme
5-Büyük ölçekli datalarda analiz etmede başarılıdır. (Terabyte boyutundaki datayı çok kolay bir şekilde indeskleyip sorgulama performası yüksek bir şekilde hizmet verebilir.)

Avantaj-Dezavantaj
1-Java ile geliştirilmesi +
2-Realtime search engine +
3-Distributed Cluster (Dağıtık mimari ile kolayca yatay bir şekilde ölçeklenebilir, yeni bir node ekleyip işlemlere kesintisiz devam edebilir.) +
4-Open Source (Açık kaynaklı) +
5- Data store  - , (Mongodb ,hadop gibi platformlara göre veri tutması iyi değildir. Bir nosql db olarak düşünmek yanlıştır aslında amaç bir search ve analytics engine olarak kullanmaktır. Yani
döküman tabanlı bir nosql veritabanı gibi kullanmak doğru değildir. Biz elastic searchu database gibi kullanmamaya özen gösteriyoruz. Eğer bir nosql gibi bir db ye ihtiyaç varsa mongodb ya 
yönelebiliriz.)

Elastic Stack Nedir ?
1-Elasticsearch tarafından geliştirilen Xpack,Kibana,logstash,beats gibi ürünleri de kapsayan yapıya verilen isimdir. Bu ürünler genelde birlikte kullanılır.Bunların temelinde elasticsearch kullanılmaktadır.
Kibana: Elasticsearch ün yönetimsel işlemlerini gerçekleştirdiğimiz veri görselleştirme ile alakalı özellikleri kullanabildiğimiz ve cluster yönetimi ile ilgili işlemlerde kullandığımız
bir yönetimsel web arayüzüdür. Elasticsearch yönetim işlemlerini vs konsoldan da yapabiliyoruz ancak kibana bize daha kullanışlı bir web arayüzü  sunmaktadır.
