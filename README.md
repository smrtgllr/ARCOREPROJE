# ARCOREPROJE
Unity ve ArCore kullanarak artırılmış gerçeklik
sayesinde Android bir cihazda çalışacak olan,
kendi belirlemiş olduğumuz görselin kamera tarafından tespit edilmesi
sonrasında yine kendi belirlemiş olduğumuz üç boyutlu
karakterin bulunduğumuz ortam içerisinde belirmesi ve
kontrolcü yardımı ile dikey ve yatay eksenlerde kontrol edilmesi
gibi özellikler barındıran bir mobil uygulama geliştirdik.
Kendimize projede referans fotoğraf olarak kullanılacak olan
Kocaeli Üniversitesi logosu içeren bir görsel ayarladık.
Projede kullanmak için Unity’nin asset store’undan Joystick
Pack ve Dragon For Boss 3D karakterini indirdik. İndirdiğimiz
3D karakteri ve Joystick Pack’i packet managerda aratarak,
logo içeren görselimizi ise sürükle bırak yöntemi ile Unity
içerisindeki Assets klasörüne import ettik.
Programdan build ayarını Android olarak değiştirdik ve
Android 7.0 için gerekli ayarlamaları yaptık. Ardından AR
plugini ayarlarından AR Core’u aktif ettik. XR Origin ve AR
Session eklentilerini projemize ekledik. XR Origin üzerinden
AR Tracked Image Manager modülünü seçtik. Bu modül ile
kullanmak istediğimiz Kocaeli Üniversitesi logosunu içeren
görseli kameramıza okuttuğumuzda 3D karakterimizin aktif
olmasını hedefledik. Modül üzerinden resim tercihini
seçtiğimiz resim ile güncelledik. XR Origin üzerinden
PrefabCreator isimli, yazmamız gereken kodlar için script
oluşturduk. Scriptimizi Visual Studio ile açıp gerekli olan
kütüphaneleri koda ekledik.
