# Prejects
## Proje 1
### Insertion and Selection sorts

[22,27,16,2,18,6] -> Insertion Sort

[22, 27, 16, 2, 18, 6]
[22, 27, 16, 2, 18, 6] -> [22, 27, 16, 2, 18, 6]
[16, 22, 27, 2, 18, 6] -> [2, 16, 22, 27, 18, 6]
[2, 16, 22, 27, 18, 6] -> [2, 16, 18, 22, 27, 6]
[2, 6, 16, 18, 22, 27]
Big-O gösterimi: O(n^2)

18 sayısı, sıralama algoritması tamamlandıktan sonra dizinin ortasında yer alacak. Bu nedenle ortalama durumda (average case) O(n/2) zaman karmaşıklığına sahip olacaktır.

Sıralama Algoritması:

En iyi durum (Best case): O(n)
Ortalama durum (Average case): O(n^2)
En kötü durum (Worst case): O(n^2)
[7,3,5,8,2,9,4,15,6] -> Selection Sort

[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
İlk 4 adımda sırasıyla en küçük eleman bulunarak dizinin başına yerleştiriliyor. Bu şekilde ilerlendiğinde, dizinin tamamı sıralanmış olacaktır.

## Proje 2
### Merge sort

[16, 21, 11, 8, 12, 22] -> Merge Sort

[16, 21, 11] [8, 12, 22] -> (sol ve sağ alt dizilere bölme)
[16, 21] [11] [8, 12] [22] -> (her alt diziyi ikiye bölme)
[11, 16, 21] [8, 12, 22] -> (birleştirme işlemi)
[8, 11, 12, 16, 21, 22] -> (birleştirme işlemi)
Big-O gösterimi: O(n log n)

Merge sort, alt dizileri ikiye ayırdığı ve birleştirme işlemi sırasında tüm elemanları bir kez karşılaştırdığı için ortalama ve en kötü durumda O(n log n) zamana ihtiyaç duyar.

Sıralama Algoritması:

En iyi durum (Best case): O(n log n)
Ortalama durum (Average case): O(n log n)
En kötü durum (Worst case): O(n log n)

## Proje 3
### Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree (BST) aşamaları şu şekildedir:

1. İlk eleman olan 7, BST'nin kökü olur.
        7
2. 5, kök olan 7'nin soluna yerleştirilir.
        7
       /
      5
3. 1, kök olan 7'nin soluna yerleştirilir.
        7
       /
      5
     /
    1
4. 8, kök olan 7'nin sağına yerleştirilir.
        7
       / \
      5   8
     /   / 
    1   /
       3 
        \
         6
5. 3, 5'in sağ alt ağacına yerleştirilir.
        7
       / \
      5   8
     /   / 
    1   3 
        \
         6
6. 6, 3'ün sağ alt ağacına yerleştirilir.
        7
       / \
      5   8
     /   / 
    1   3 
        \
         6
7. 0, 1'in sol alt ağacına yerleştirilir.
        7
       / \
      5   8
     /   / 
    1   3 
   /    \
  0     6
  
8. 9, 8'in sağ alt ağacına yerleştirilir.
        7
       / \
      5   8
     /   / \ 
    1   3   9
   /    \
  0     6
9. 4, 3'ün sol alt ağacına yerleştirilir.
        7
       / \
      5   8
     /   / \ 
    1   3   9
   / \   \
  0   4   6
       \
        2
10. 2, 4'ün sol alt ağacına yerleştirilir.
        7
       / \
      5   8
     /   / \ 
    1   3   9
   / \   \
  0   4   6
     /
    2

Sonuçta oluşan BST yapısı yukarıdaki gibi olur.
