## Merge Sort 
---
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

* Tek sayılı dizi kalana kadar diziyi 2 ye bölüyoruz.

             [16,21,11,8,12,22]

            [16,21,11] [8,12,22]

           [16,21] [11] [8,12] [22]

          [16] [21] [11] [8] [12] [22]

* Dizileri sıralı olarak birleştirirken en küçüğü başa yazıyoruz.

          [16] [21] [11] [8] [12] [22]

            [16-21] [11] [8,12]  [22]

              [11,16,21]  [8,12,22]

                [8,11,12,16,21,22]

2.Big-O gösterimini yazınız.

  O(n*(logn))
