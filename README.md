# BG-NBD ve Gamma-Gamma ile CLTV Tahmini

Bu proje, FLO adlı bir e-ticaret şirketinin müşterilerinin gelecekte sağlayacakları potansiyel değeri tahmin etmeyi amaçlamaktadır. Bu sayede şirket, satış ve pazarlama faaliyetleri için roadmap belirleyebilecek ve orta uzun vadeli plan yapabilecektir.

## İş Problemi

FLO, müşterilerinin alışveriş davranışlarını anlayarak daha etkili bir pazarlama stratejisi oluşturmak istiyor. Bu doğrultuda aşağıdaki sorulara cevap aranmaktadır:

- Müşterilerin gelecekte şirkete sağlayacakları potansiyel değer nedir?
- Müşterileri potansiyel değerlerine göre segmentlere ayırabilir miyiz?
- Her segment için hangi pazarlama kampanyaları ve indirimler uygulanabilir?
- Sadık müşterileri nasıl belirleyebilir ve onlara özel teklifler sunabiliriz?
- Uyuyan veya kaybedilme riski taşıyan müşterileri nasıl yeniden kazanabiliriz?

## Veri Seti

Veri seti, son alışverişlerini 2020-2021 yıllarında hem online hem offline kanallardan gerçekleştiren FLO müşterilerinin geçmiş alışveriş davranışlarına ait bilgilerden oluşmaktadır. Veri setinde aşağıdaki değişkenler bulunmaktadır:

- master_id: Eşsiz müşteri numarası
- order_channel: Alışveriş yapılan platforma ait hangi kanalın kullanıldığı (Android, iOS, Desktop, Mobile, Offline)
- last_order_channel: En son alışverişin yapıldığı kanal
- first_order_date: Müşterinin yaptığı ilk alışveriş tarihi
- last_order_date: Müşterinin yaptığı son alışveriş tarihi
- last_order_date_online: Müşterinin online platformda yaptığı son alışveriş tarihi
- last_order_date_offline: Müşterinin offline platformda yaptığı son alışveriş tarihi
- order_num_total_ever_online: Müşterinin online platformda yaptığı toplam alışveriş sayısı
- order_num_total_ever_offline: Müşterinin offline'da yaptığı toplam alışveriş sayısı
- customer_value_total_ever_offline: Müşterinin offline alışverişlerinde ödediği toplam ücret
- customer_value_total_ever_online: Müşterinin online alışverişlerinde ödediği toplam ücret
- interested_in_categories_12: Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi
- store_type: 3 farklı company'i ifade eder. A company'sinden alışveriş yapan kişi B'dende yaptı ise A,B şeklinde yazılmıştır.

## Gereksinimler

Bu projeyi çalıştırabilmek için aşağıdaki gereksinimlere ihtiyacınız vardır:

- Python 3.x
- Pandas
- Scikit-Learn
- Lifetimes

## Nasıl Kullanılır

Projeyi kullanabilmek için aşağıdaki adımları takip edebilirsiniz:

1. Proje dosyalarını bilgisayarınıza indirin veya kopyalayın.
2. Gereksinimleri yükleyin: `pip install pandas scikit-learn lifetimes`
3. Proje klasörünün içindeki ana kod dosyasını çalıştırın: `python main.py`

## Testler

Proje testleri aşağıdaki adımlarla çalıştırabilirsiniz:

1. Test veri setini hazırlayın.
2. Proje kodunu çalıştırarak müşterilerin CLTV değerlerini tahmin edin.
3. Oluşturulan CLTV değerlerine göre müşterileri segmentlere ayırın.
4. Her segment için pazarlama stratejilerini belirleyin ve uygulayın.
5. Kampanyaların sonuçlarını izleyin ve müşteri davranışlarını inceleyerek stratejilerin etkinliğini değerlendirin.

## Kullanılan Teknolojiler

Bu proje geliştirilirken aşağıdaki teknolojiler kullanılmıştır:

- Python: Veri analizi ve işleme için kullanıldı.
- Pandas: Veri çerçeveleri oluşturmak ve işlemek için kullanıldı.
- Scikit-Learn: Makine öğrenimi modellerini oluşturmak ve eğitmek için kullanıldı.
- Lifetimes: BG-NBD ve Gamma-Gamma modellerini kullanarak CLTV tahmini yapmak için kullanıldı.

## Katkıda Bulunanlar

Bu projeye katkıda bulunan ekip üyeleri: Miuul, VeriGood

## Lisans

Bu proje için kullanılan lisans: MIT Lisansı
