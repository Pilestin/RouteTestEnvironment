# RouteTestEnvironment

### Bu proje geliştirme aşamasındadır.

Bu repo VRP (araç rotalama problemi) gibi optimizasyon problemlerinde karşılaşılan ve önemli bir ihtiyaç olan rota test ortamını sağlamayı amaçlar. 
Bu ortam rotalamaya standart getirmek için Yasin Ünal tarafından geliştirilen  Routing Markup Language (RoutingML) formatını kullanır. Bu standart henüz publish edilmedi fakat belki bir gün aniden yayınlanır. 


Bu repo Streamlit kullanılarak geliştirilecektir. Arayüz üzerinden aşağıdakine benzer olarak girilen rota bilgileri test edilebilecek, rota görselleştirmeleri ve dashboard gibi özellikler sağlanacaktır.

[[Depo, müşteri_id1, müşteri_id2, ..., Depo], [Depo, müşteri_id3, müşteri_id4, ..., Depo], . . . ]



RoutingML Nedir?

> Şüphesiz ki bu standartı uyasınız diye oluşturduk. 
Ta ki rotalarınız test edilebilsin, verileriniz birbirine zulmetmesin. 

> Ve biz, rotaları bir ölçü üzere kıldık;
her düğüm yerini bilsin,
her araç menzilini aşmasın,
ve enerji, hakkıyla sarf olunsun diye.

...
