# Merge-Sort
Merge Sort Ödev
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


Merge Sort'a göre ayıracağımız için ortadan 2 ye böldük
 16,21,11   8,12,22 oldu tekrar 2 ye bölüyoruz
 16,21  11        8,12   22     Tam ikiye bölünemeyeceği için böyle aldık 11 ve 22 ile işimiz kalmadı tekrar 2 ye böldük
 16   21   11       8  12  22   Bu sefer tüm sayılar ayrı ayrı ayrılmış oldu sıra combine kısmına geldi. 3'ü arasında hangisi daha küçükse onu sola büyüğünü sağa yazacağız
 11,16,21       8,12,22       combine işlemi yapıldı bu sefer 2 grubun en solundaki yani en küçük elemanlarını karşılaştıracağız bu şekilde küçükten büyüğe sıralama yapabileceğiz
8<11 bu yüzden 8 sola 11 sağa yazılır, artık bu sayılarla bi işimiz kalmadı
12<16'dan bu yüzden 12 sola 16 sağa yazılır bu sayılarla da işimiz kalmadı
21<22'den bu yüzden 21 sola 22 sağa yazılır ve artık sayımız kalmadı 

8,11,12,16,21,22 olarak küçükten büyüğe sıralanmış oldu

Big-O gösterimi ise elimize hangi sayı gelirse gelsin her zaman ikiye böleceğimiz için 
best case :   Ω(n log n) average case :  Θ(n log n) worst case : O(n log n)

 
 
 


![mergesort](https://user-images.githubusercontent.com/83555226/211175417-13fb0f0a-fa93-443a-b618-e47d00f5877c.png)
