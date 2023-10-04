# BG-NBD-ve-Gamma-Gamma-ile-CLTV-Tahmini

# İş Problemi
FLO satış ve pazarlama faaliyetleri için roadmap
belirlemek istemektedir. Şirketin orta uzun vadeli plan
yapabilmesi için var olan müşterilerin gelecekte şirkete
sağlayacakları potansiyel değerin tahmin edilmesi
gerekmektedir.

# Veri Seti Hikayesi
Veri seti Flo’dan son alışverişlerini 2020 - 2021 yıllarında OmniChannel (hem online hem offline alışveriş yapan)
olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır.

# 13 Değişken 19.945 Gözlem 2.7MB
master_id Eşsiz müşteri numarası
order_channel Alışveriş yapılan platforma ait hangi kanalın kullanıldığı (Android, ios, Desktop, Mobile)
last_order_channel En son alışverişin yapıldığı kanal
first_order_date Müşterinin yaptığı ilk alışveriş tarihi
last_order_date Müşterinin yaptığı son alışveriş tarihi
last_order_date_online Müşterinin online platformda yaptığı son alışveriş tarihi
last_order_date_offline Müşterinin offline platformda yaptığı son alışveriş tarihi
order_num_total_ever_online Müşterinin online platformda yaptığı toplam alışveriş sayısı
order_num_total_ever_offline Müşterinin offline'da yaptığı toplam alışveriş sayısı
customer_value_total_ever_offline Müşterinin offline alışverişlerinde ödediği toplam ücret
customer_value_total_ever_online Müşterinin online alışverişlerinde ödediği toplam ücret
interested_in_categories_12 Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi
store_type 3 farklı companyi ifade eder. A company'sinden alışveriş yapan kişi B'dende yaptı ise A,B şeklinde yazılmıştır.
