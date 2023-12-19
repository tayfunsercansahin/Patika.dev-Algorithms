# Patika.dev-Algorithms
Patika.dev / Algorithms

--------------------------------------------------------------------

Ödev 1:

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?

Average case: Aradığımız sayının ortada olması.
Worst case: Aradığımız sayının sonda olması.
Best case: Aradığımız sayının dizinin en başında olması.

Cevap:

      [6,27,16,2,18,22]
      [6,2,16,27,18,22]
      [6,2,16,27,18,22]
      [6,2,16,18,27,22]
      [6,2,16,18,22,27]

            Big-O: İşlemler n'den 1'e kadar gideceği için, 1'den n'e kadar olan sayilarin toplami sonucu verecektir.
                n.(n+1)/2 
                =n^2

            ->  o(n^2)

       Time Complexity: [6,2,16,18,22,27] siralama yandaki gibi olacagindan 6 = Lower , 27 = Higher ve 18 = Middle olacaktir.
       Bu durumda 18 sayisi icin, Average Case uygundur.

![Selection Sort Algoritm](https://github.com/tayfunsercansahin/Patika.dev-Algorithms/assets/82944149/b826b9b7-bf75-42b6-bd33-fa432faf3eb6)

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Cevap:

      [2,3,5,8,7,4,15,6]
      [2,3,5,8,7,4,15,6]
      [2,3,4,8,7,5,15,6]
      [2,3,4,5,7,8,15,6]

--------------------------------------------------------------------


Ödev 2:

<img width="606" alt="Merge Sort Algoritm" src="https://github.com/tayfunsercansahin/Patika.dev-Algorithms/assets/82944149/35eb6606-e59b-45b7-9b8f-d75a9e088fce">

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

Cevap:

              [16,21,11] - [8,12,22]
              [16,21] [11] - [8,12] [22]
              [16] [21] [11] [8] [12] [22]
              [16,21] [8,11] [12,22]
              [8,11,12,16,21,22]

              Big-O gosterimi : O(nlogn) olacaktir.

--------------------------------------------------------------------

Ödev 3:

![Binary Search Tree Algoritm](https://github.com/tayfunsercansahin/Patika.dev-Algorithms/assets/82944149/77f88fed-6f7b-43a7-a174-d921aedfb102)

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Cevap:
                    
                    Root = 9 
                    
                      9                        
                    /
                   7
                 / \
                5   8
                /  \
               1     6
                /  \
                0   3
                /  \
               2    4
