
### Verilen listenin içindeki elemanları tersine döndüren bir fonksiyon yazın. Eğer listenin içindeki elemanlar da liste içeriyorsa onların elemanlarını da tersine döndürün.

```
l = [[1, 2], [3, 4], [5, 6, 7]]

l2 = l[::-1]

reverse_l = []

for i in l2:
  x = i[::-1]
  reverse_l.append(x)

reverse_l
```
