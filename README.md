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

A- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
B- Big-O gösterimini yazınız.

### Cevaplar:

## 2.A
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

## 2.B Big-O Gösterimi
Merge Sort'un zaman karmaşıklığı O(n log n) şeklindedir.


### 3-)[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Binary Search Tree Oluşturma

- Root 7'dir.

    - 5, 1, 8, 3, 6, 0, 9, 4, 2 sırasıyla eklenir.

        - 5, 1, 8, 3, 6, 0, 9, 4, 2 eklemeleri sırasında ağaç şu şekilde büyür:

          - Root 7'dir.
          
            - 5, Root'un solundadır.

            - 1, 5'in solundadır.
            
            - 8, Root'un sağındadır.

            - 3, 5'in sağındadır.

            - 6, 3'ün sağındadır.

            - 0, 1'in solundadır.
            
            - 9, 8'in sağındadır.

            - 4, 3'ün sağındadır.

            - 2, 1'in sağındadır.
