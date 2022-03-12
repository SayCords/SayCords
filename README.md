MatNot= int(input("Öğrencinin Matematik Ortalamasını Giriniz:   "))
EdbNot= int(input("Öğrencinin Edebiyat Ortalamasını Giriniz:  "))
KimyaNot= int(input("Öğrencinin Kimya Ortalamasını Giriniz:  "))
BiyoNot= int(input("Öğrencinin Biyoloji Ortalamasını Giriniz:  "))
FizikNot= int(input("Öğrencinin Fizik Ortalamasını Giriniz:  "))
CografyaNot = int(input("Öğrencinin Coğrafya Ortalamasını Giriniz:  "))
TarihNot = int(input("Öğrencinin Tarih Ortalamasını Giriniz:  "))
if MatNot>100 or EdbNot>100 or KimyaNot>100 or BiyoNot>100 or FizikNot>100 or CografyaNot>100 or TarihNot>100:
     print("Öğrencinin Notlarından Biri Hatalı Girilmiştir.")
elif MatNot<0 or EdbNot<0 or KimyaNot<0 or BiyoNot<0 or FizikNot<0 or CografyaNot<0 or TarihNot<0:
    print("Öğrenicin Notlarından Biri Hatalı Girilmiştir.")
elif MatNot>=85 and EdbNot>=85 and KimyaNot>=85 and BiyoNot>=85 and FizikNot>=85 and CografyaNot>=85 and TarihNot >=85:
    print("Sen istediğin her şey olabilirsin yeter ki iste :)")
elif MatNot>=85 and EdbNot >=85:
    if BiyoNot>=85:
        print("Önerilen Meslekler Doktor,Veteriner")
    else:
        print("Önerilen Meslekler Avukat,Hakim,Savcı vb.")
elif EdbNot>= 85:
    if TarihNot>=85 and CografyaNot >=85:
        print("Önerilen Meslekler Halkla İlişkiler Uzmanı,Yönetmen,Sosyal Medya Uzmanı,Arkeolog")
    elif CografyaNot>=85:
        print("Önerilen Meslekler Coğrafya Öğretmeni,Kartograf")
    elif TarihNot>=85:
        print("Önerilen Meslekler Tarih Öğretmeni,Sosyal Bilgiler Öğretmeni")
    else:
        print("Önerilen Meslekler TDE Öğretmenliği,Gazetecilik")
elif MatNot>=85:
    if KimyaNot>=85 and FizikNot>=85 and BiyoNot >=85:
        print("Önerilen Meslekler Astronot,Genetik Mühendisi ")
    elif FizikNot>=85:
        print("Önerilen Meslekler Yazılım Mühendisliği,Bilgisayar Mühendisliği,Makine Mühendisliği")
    elif BiyoNot>=85:
        print("Önerilen Meslekler Biyolog,Biyomühendislik,Jeoloji Mühendisliği")
    else:
        print("Önerilen Meslekler Pilot,Endüstri Mühendisliği")
else:
    print("Bir mesleğinin olması için daha çok çalışman lazım")

        
        
