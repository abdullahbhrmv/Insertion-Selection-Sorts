# Prejects
## Proje 1
### insertion and selection sorts

# Prejects
insertion and selection sorts


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
