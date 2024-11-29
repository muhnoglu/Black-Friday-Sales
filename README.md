![Black_Friday_Sales](https://github.com/user-attachments/assets/fba46fa0-6b40-4486-a677-73181dc355da)
# Proje:Black-Friday-Sales
Bu proje, "ABC Private Limited" isimli bir perakende şirketinin sağladığı müşteri satın alma davranışı verilerini kullanarak müşteri segmentasyonu yapmayı amaçlamaktadır. Veri seti, müşterilerin demografik <br/> bilgilerini (yaş, cinsiyet, medeni durum, yaşadığı şehir kategorisi, mevcut şehirde kalma süresi), ürün bilgilerini (ürün kimlikleri ve kategorileri) ve müşterilerin toplam satın alma tutarını içermektedir. <br/> 
# Projenin Amacı
Bu projede ana amaç, veri setini K-Means Kümeleme Algoritması kullanılarak müşteri segmentasyon analizine hazırlamaktır. Bu analizle, müşterilerin satın alma alışkanlıklarına göre gruplara ayrılması ve bu <br/> grupların özelliklerine yönelik stratejik çıkarımlar yapılması hedeflenmiştir. <br/> 
K-Means, kümeleme analizlerinde yaygın kullanılan bir algoritmadır ve verideki benzerliklere dayalı olarak gruplar oluşturur.<br/> 
Bu yöntem, müşterilerin ortak özelliklerine göre segmentler oluşturarak farklı müşteri gruplarına özgü pazarlama stratejileri geliştirmeyi mümkün kılar.<br/> 
Özellikle satın alma verileri gibi nümerik ağırlıklı veri setleri için uygundur ve güçlü içgörüler sunar.<br/> 
# Veri Hazırlık Adımları (Data Cleaning ve Data Preprocessing)
Projede, veri setini analiz için uygun hale getirmek amacıyla aşağıdaki adımlar gerçekleştirilmiştir:<br/> 
# Veri Yükleme ve Eksik Değerlerin İncelenmesi:
Eksik değerler tespit edilerek bu değerler uygun yöntemlerle doldurulmuştur.<br/> 
Eksik değer doldurma işlemi sırasında mod (kategorik veriler için) ve medyan (nümerik veriler için) yöntemleri kullanılmıştır.<br/> 
# Kategorik ve Nümerik Verilerin Ayrıştırılması:
Kategorik ve nümerik değişkenler ayrı ayrı analiz edilerek düzenlenmiştir.<br/> 
Veri setinde hangi değişkenlerin kategorik, hangi değişkenlerin nümerik olduğuna dair bir yapı oluşturulmuştur.<br/> 
# Aykırı Değerlerin Tespiti ve Düzenlenmesi:
Nümerik değişkenlerde aykırı değerler boxplot yöntemiyle tespit edilmiştir.<br/> 
Aykırı değerler standartlaştırma işlemiyle düzenlenerek verinin analiz gücü artırılmıştır.<br/> 
# Yeni Değişkenlerin Eklenmesi (Feature Engineering):
Veri setine analiz gücünü artırmak amacıyla yeni değişkenler eklenmiştir:LabelEncoder(sıralı) ve One Hot Encoder(sırasız)<br/> 
Purchase_Scaled: Satın alma tutarının ölçeklenmiş hali.<br/> 
Purchase_Category: Satın alma tutarına göre müşterilerin kategorilere ayrılması.<br/> 
Category_Avg_Purchase: Her ürün kategorisinin ortalama satın alma tutarı.<br/> 
Purchase_vs_Category_Avg: Müşterinin satın alma tutarının ürün kategorisi ortalamasına göre oranı.<br/> 
# Çıkarımlar ve Beklentiler
K-Means analizi ile şu tür çıkarımlar yapılması planlanmaktadır:<br/> 
Müşteri segmentlerinin demografik özelliklerine göre sınıflandırılması (örneğin yaş grubu, şehir kategorisi)<br/> 
Her segmentin satın alma alışkanlıklarının incelenmesi.<br/> 
Şirketin pazarlama stratejilerini optimize edebileceği hedef segmentlerin belirlenmesi.<br/> 
 # Kaggle Proje Linki:https://www.kaggle.com/code/muhammedhanolu/black-friday-sales 
