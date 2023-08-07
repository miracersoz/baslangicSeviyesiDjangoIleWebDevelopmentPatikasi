# Proje 1 - Insertion Sort

## 1.Soru
[22, 27, 16, 2, 18, 6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

## Cevap
Verilen dizi: [22, 27, 16, 2, 18, 6]

1.Adım: [22, 27, 16, 2, 18, 6]
2.Adım: [22, 27, 16, 2, 18, 6]
3.Adım: [16, 22, 27, 2, 18, 6]
4.Adım: [2, 16, 22, 27, 18, 6]
5.Adım: [2, 16, 18, 22, 27, 6]
6.Adım: [2, 6, 16, 18, 22, 27]

Dizi sıralandıktan sonra:
[2, 6, 16, 18, 22, 27]

## 2.Soru
Big-O gösterimini yazınız.

## Cevap
En kötü durum (worst case): O(n^2)
En iyi durum (best case): O(n)
Ortalama durum (average case): O(n^2)

## 3.Soru
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

## Cevap
Time Complexity (Zaman Karmaşıklığı): Dizi sıralandıktan sonra 18 sayısı, Insertion Sort algoritmasının ortalama durum (average case) karmaşıklığına (O(n^2)) girer.