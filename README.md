print("hoşgeldiniz")
ad=input("isminiz nedir:")
while True:
    print("karekter sınıfları")
    print("1-savaşçı")
    print("2-büyücü")
    print("3-hırsız")
    secim=input("lütfen sınıfınızı seçin ")
    if secim=="1":
        sinif="savaşçı"
        can=125
        hasar=100
        hiz=75
        dogustan_gelen_ozel_guc="yok"
        break
    elif secim=="2":
        sinif="büyücü"
        can=75
        hasar=125
        hiz=100
        dogustan_gelen_ozel_guc="yok"
        break
    elif secim=="3":
        sinif="hırsız"
        can=100
        hasar=75
        hiz=125
        dogustan_gelen_ozel_guc="gizlilik"
        break
    else:
     print("geçersiz sınıf lütfen tekrar deneyiniz")
print("tebrikler",ad,sinif,"seçimini yaptınız")
print("karekter özelliklerin")
print(f"can :{can}")
print(f"hasar :{hasar}")
print(f"hiz :{hiz}")
print(f"doğuştan gelen özel güç :{dogustan_gelen_ozel_guc}")
print("kadim krallık adında bir krallığa geldin")
print("krallıkta herşey güzel görünüyor ama içinde ürpertici bir his var")
print("muhafızlar seni saraya götürmeye calışıyor")
while True:
    print("seçenekler")
    print("1-muhafızlara karşı koyma ve saraya git")
    print("2-muhafızlardan kaç")
    secim2=input("lütfen seçiminizi yapın: ")
    if secim2=="1":
        print("muhafızlara karşı direnmeyip kadim krallığın ihtişamlı sarayına doğru yola çıktınız")
        break
    elif secim2=="2":
        print("muhafızlara karşı koyup kaçıyorsun krallıkta kaçak ilan edildin")
        break
    else:
        print("geçersiz secim lütfen tekrar deneyin")
