# OpenCV ile Ön İşleme

Beyin BT görüntüleri üzerinden inme tespiti yapmak amaçlı oluşturulan bir YSA'nın inmeli bölgeyi daha net görmesi ve bunun sonucunda oluşturulan YSA modelinin daha yüksek doğruluk vermesi için BT görüntülerine yapılan ön işleme çalışmasıdır. Bu çalışmada kullanılan dil Python olup veri önişleme adımları için openCV kütüphanesi kullanılmıştır.

<h4>Scikit Learn: </h4> Bu kütüphanede bulunan imread() metoduyla görüntünün okunması sağlanır.

<h4>openCV: </h4> Bu kütüphanede bulunan resize(), cvtColor(), createCLAHE(), bileteralFilter()  gibi metodlar kullanılarak görüntünün ön işleme aşaması yapılmıştır.

<h4>Matplotlib: </h4> Bu kütüphane sayesinde verilerin görüntülenmesi sağlanır.


 Aşağıdaki görüntüler kanamalı inmeye ait bir BT görüntünün ön işlemeden önceki ve sonraki halidir:
 
![normal2](https://user-images.githubusercontent.com/52465630/157882942-5482cff9-b3db-43f3-8500-7568c4a487e9.png)
![bileteral20125125](https://user-images.githubusercontent.com/52465630/157881842-beca98e0-994e-4565-9507-d098d8a9249b.png)





