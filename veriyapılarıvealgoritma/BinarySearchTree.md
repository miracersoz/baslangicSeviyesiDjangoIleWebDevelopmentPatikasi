# Proje 3 - Binary Search Tree

## 1.Soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Çözüm
Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1. İlk eleman olan 7 root olarak seçilir.
2. 5, 7'nin soluna eklenir: root'un sağından y bulunamadı, solunda 5 bulundu. 7'nin soluna 5 eklenir.
3. 1, 7'nin solundan eklenir: 5'in sağından y bulunamadı, solunda 1 bulundu. 5'in soluna 1 eklenir.
4. 8, 7'nin sağına eklenir: 7'nin sağından 8 bulundu. 7'nin sağına 8 eklenir.
5. 3, 5'in sağına eklenir: 5'in sağından y bulunamadı, solunda 3 bulundu. 5'in sağına 3 eklenir.
6. 6, 7'nin solunun sağına eklenir: 7'nin solunun sağından 6 bulundu. 7'nin solunun sağına 6 eklenir.
7. 0, 1'in sağına eklenir: 1'in sağından y bulunamadı, solunda 0 bulundu. 1'in sağına 0 eklenir.
8. 9, 8'in sağına eklenir: 8'in sağından y bulunamadı, solunda 9 bulundu. 8'in sağına 9 eklenir.
9. 4, 5'in sağından eklenir: 5'in sağından y bulunamadı, solunda 4 bulundu. 5'in sağına 4 eklenir.
10. 2, 3'ün sağına eklenir: 3'ün sağından y bulunamadı, solunda 2 bulundu. 3'ün sağına 2 eklenir.

      7
     / \
    5   8
   / \   \
  1   6   9
 / \     /
0   3   9
   / \
  2   4
