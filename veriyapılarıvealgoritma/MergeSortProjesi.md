# Proje 2 - Merge Sort

## 1.Soru
[16, 21, 11, 8, 12, 22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

## Çözüm
Verilen dizi: [16, 21, 11, 8, 12, 22]

1.Diziyi ikiye bölelim: [16, 21, 11] [8, 12, 22]
2.Soldaki yarıyı daha da bölelim: [16] [21, 11]
3.Soldaki yarıyı sıralayalım: [16] [11, 21]
4.Sağdaki yarıyı sıralayalım: [8] [12, 22]
5.Soldaki yarıyı ve sağdaki yarıyı birleştirelim ve sıralayalım: [11, 16, 21] [8, 12, 22]
6.Son olarak tüm diziyi birleştirip sıralayalım: [8, 11, 12, 16, 21, 22]

## 2.Soru
Big-O gösterimini yazınız.

## Çözüm
Big-O Gösterimi: Merge Sort algoritmasının karmaşıklık analizi

Best case: O(n log n)
Average case: O(n log n)
Worst case: O(n log n)

Merge Sort algoritması en iyi, ortalama ve en kötü durumlarda da O(n log n) zaman karmaşıklığına sahiptir.