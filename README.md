# Havaalanı Otomasyonu Projesi

Havaalanındaki yolcu uçak ve havayolu verilerinin düzenlenmesi ve bilgi kolaylığı sağlamak.

Projedeki Öğrenciler:

-> Kerem AYDIN (215260069)
-> Ahmet Mert KUMCU (215260049)
-> Miraç Ayşe YERKAZAN (215260083)

Proje Özeti:

Havaalanı otomasyon sistemi hem yolcuların hem de havayolu firmalarının bilgi güvenliğini ve bu bilgiler doğrultusunda insanlara kolaylık sağlamak amacıyla oluşturulmuştur.


Varlıklar ve Nitelikler:

Yolcu:
- AdSoyad : Yolcunun tam adı
- TcKimlikNo : Yolcunun TC Kimlik numarası
- Cinsiyet : Yolcunun Cinsiyeti
- Yaş : Yolcunun yaşı
- Bagaj : Yolcunun taşıyabileceği bagajın kg cinsinden sayısı

Uçak:
- UçakNo: Uçağın kimlik numarası
- KalkışSaati : Uçağın kalkış saati
- Havaalanı : Uçağın kalkış yapacağı havaalanı
- İstikamet : Uçağın iniş yapacağı havaalanı
- KapıNo : Uçağın yolcu alımı yapacağı kapı numarası
- Hatlar : Uçağın iç ya da dış hatlara gideceği hakkındaki bilgi

Havaalanı:
- HavaalanıAdı : Havaalanının adı
- FirmaAdı : Havaalanındaki firmanın adı
- Uçuşlar : Havaalanından hangi istikamete uçuşlar yapılabileceği

Bilet:
- BiletNo : Yolcunun bilet numarası
- Sınıf : Yolcunun uçuş yapacağı sınıf


İlişkiler :
Yolcu-Uçak ilişkisi : Her yolcu bir uçağa binebilir
Yolcu-Bilet İlişkisi : Yolcuların birden fazla bileti olabilir
Havaalanı-Uçak İlişkisi : Her havaalanında birden fazla uçak bulunabilir







