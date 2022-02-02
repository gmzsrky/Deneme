Girişte sayfasında kullanıcı girişi formu bulunmakta. Dört adet kullanıcı tanımlı, tanımlı kullanıcılar haricindeki girişlere, kullanıcı adı-şifre uyuşmazlığında girişlere izin vermiyor. Hatalı kullancıcı adı veya şifre uyarısı veriyor. Büyük küçük harfe duyarlı. Tanımlı kullanıcı adı ve şifreler:

Kullanıcı adı:	Şifre:
Ahmet	12345
Ceylin	25262
Zeynep	12345
Mehmet	birnisan

Kullanıcı adı  ve şifre edit textleri hatasız bir şekilde doldurduktan sonra istenilen temaya uygun radio butona basılacaktır (Açık renkli tema için açık, koyu renkli tema için koyu butonuna). Kullanıcı adı ve şifre doğru olduğu takdirde giriş sağlanır.

2)
	İkinci sayfada Kredi taksit, Hesap makinesi ve listview yazılı butonlar bulunmaktadır gidilmek istenen sayfanın adı bulunan butona basılmalıdır. En üstteki textView kullanıcı adını içeren bir home dizidir.

3)
	Kredi taksit yazan butonun sayfasında kredi tutarını giriniz ve taksit sayısını giriniz yazan iki adet edit text bulunmaktadır. Edit textlere integer değerler yazıldıktan sonra (Paydaya geleceğinden dolayı taksit sayısını giriniz edit texti “0” girdisini kabul etmemektedir.) İstenilen faiz oranının olduğu -%1,%2,%5- radio butonlardan biri seçilmelidir. (Radio butonlar boş bırakılmamalıdır. Boş bırakılırsa “Lütfen faiz oranı seçiniz.” şeklinde bir uyarı alınacaktır. Edit textlere integer değer girilip radio butonlardan biri seçildiğinde ve hesapla butonuna basıldığında sonuç “Taksit tutarı:” yazısının altındaki edit textte yer alacaktır.

4)
	Hesap makinesi yazan butonun sayfasında  istenilen sayı değeri için ilgili tuşalra basıldıktan sonra işlemin işaretinin olduğu tuşa basıp ardından ikinci sayı girilir ve en son eşittir işaretine basılır. Sonuç “Sayı giriniz:” yazan edit textte çıkacaktır. Hesap makinesinde rakamlar ve +, -, *, /, = tuşları çalışır durumdadır. Kalan tuşlar xml ve grid layout tasarımı için kullanılmıştır. Hesap makinesi toplama, çıkarma, çarpma, bölme yapabilir durumdadır.

5)
	Listview yazan butonun sayfasında önceden tanımlı kullanıcı adları yer almaktadır. 4 adet kullanıcı adı değeri girilmiştir. Listeye eleman ekle yazılı edit texte yazılan kullanıcı adından sonra ekle tuşuna basıldığında eleman eklenecektir
