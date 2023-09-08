# Veri-yapilari-ve-algoritmalar-kodluyoruz
Kodluyoruz Eğitimi .Net Core Patikası kapsamında yaptığım algoritma ödevleri


1-)
## [22,27,16,2,18,6] -> Insertion Sort

*Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.*

*Big-O gösterimini yazınız.*

*Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız*

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

### Cevaplar:
## 1.A
*Insertion Sort Aşamaları:*
[22,27,16,2,18,6]
[22, 27,16,2,18,6]
[16, 22, 27,2,18,6]
[2, 16, 22, 27,18,6]
[2, 16, 18, 22, 27,6]
[2, 6, 16, 18, 22, 27]

Big-O Gösterimi:
Insertion Sort'un Big-O gösterimi O(n^2)dir.

Time Complexity:
18 sayısı, Insertion Sort ile sıralandığında Average case'i kapsar.
## 1.B
1. [**2**,3,5,8,7,9,4,15,6]
2. [**2, 3**,5,8,7,9,4,15,6]
3. [**2, 3, 4**,8,7,9,5,15,6]
4. [**2, 3, 4, 5**,7,8,9,15,6]
5. [**2, 3, 4, 5, 6**,7,8,9,15]
