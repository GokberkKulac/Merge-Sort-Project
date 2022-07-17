# Merge-Sort-Project
Patika.dev Merge Sort Projesi
https://app.patika.dev/gokberkkulac

[16,21,11,8,12,22]

  1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
  2. Big-O gösterimini yazınız.
  
 ### 1. AŞAMA 1 ###

-Önce diziyi 2 kısma bölerek bu sonucu elde ediyoruz: [16 21 11] [8 12 22]
-Böldüğümüz sayıları tekrar 2 farklı kısıma ayırıyoruz: [16 21] [11] [8] [12 22]
-Tek eleman kalana kadar devam ediyoruz: [16] [21] [11] [8] [12] [22]

  [16 21 11 8 12 22]
   /     /   \     \
[16 21] [11] [8] [12 22]
 /   \    |    |   \   \ 
[16] [21] [11] [8] [12] [22]

-Şimdi de diziyi sıralıyoruz.

[16] [21] [11] [8] [12] [22]
  \    /   |    |    \  /
  [16,21] [11] [8] [12,22]
      \    /     \     /
    [11,16,21]  [8,12,22]
          \        /
      [8,11,12,16,21,22]
      
  ### 2. AŞAMA 2 ###

     O(nlogn)
     
