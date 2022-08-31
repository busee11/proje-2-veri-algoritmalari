# proje-2-veri-algoritmalari
Merge Sort Projesi
https://www.patika.dev/tr

[16,21,11,8,12,22] -> Merge Sort

1)  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2)  Big-O gösterimini yazınız.


1)
       *  [16,21,11,8,12,22] dizisini tek bir parça kalana kadar ikiye bölüyoruz.

       *  [16,21,11]   [8,12,22]

       *  [16,21]  [11] ve [8,12]  [22]

       *  [16] [21] [11] ve [8] [12] [22] 

       *  [11,16,21] ve [8,12,22] parçalar kendi grupları arasında küçükten büyüğe sıralanır..

       *  [8,11,12,16,21,22] en son tek parça gibi düşünülerek küçükten büyüğe sıralanır.
       
       
2)  Worst Case: O(nlogn)

      Average Case: O(nlogn)

         Best Case: O(nlogn)
