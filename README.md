# Patika.dev Merge Sort Projesi
Patika.dev Merge Sort Projesi



# Sorular

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


# Cevap 1 / Sort Türüne Göre Aşamalar

1) [16,21,11,8,12,22] 
2) [16,21,11]          |          [8,12,22] 
3) [16,21]   /   [11]          |          [8,12]   /   [22] 
4) [16] / [21] / [11] | [8] / [12] / [22] 
5) [16,21]   /   [11]          |          [8,12]   /   [22] 
6) [11,16,21]          |          [8,12,22] 
7) [8,11,12,16,21,22] 



# Cevap 2 / Big-O Gösterimi
Big O Notation = O(nlogn)

