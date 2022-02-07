# Proje 2

## Soru 1

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Cevap 1

```
Ara adımlarla birlikte: 
[16,21,11,8,12,22]

       [16,21,11]  [8,12,22]

     [16] [21,11]  [8,12] [22]

     [16] [11,21]  [8,12] [22]

   [16] [11] [21]  [8] [12] [22]

     [16] [11,21]  [8,12] [22]

       [11,16,21]  [8,12,22]

        [8,11,12,16,21,22]
```

```
O(n*logn)
```




