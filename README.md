# Veri-yapilari-ve-algoritmalar-kodluyoruz
Kodluyoruz Eğitimi .Net Core Patikası kapsamında yaptığım algoritma ödevleri


## 1-)
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

## 2-)
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

### Cevap:

# Merge Sort ile Sıralama

Başlangıç dizisi: [16, 21, 11, 8, 12, 22]

## Adım 1
Diziyi yarıya ayır ve iki alt dizi oluştur.
- Sol dizi: [16, 21, 11]
- Sağ dizi: [8, 12, 22]

## Adım 2
Her iki alt diziyi de ayrı ayrı sırala.

Sol dizi: [11, 16, 21]
Sağ dizi: [8, 12, 22]

## Adım 3
Sıralanmış alt dizileri birleştir.

Birleştirilmiş dizi: [8, 11, 12, 16, 21, 22]

## Big-O Gösterimi
Merge Sort'un zaman karmaşıklığı O(n log n) şeklindedir.
