Proje 2


[16,21,11,8,12,22] -> Merge Sort

•	Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

•	Big-O gösterimini yazınız

ÇÖZÜM:

1)

16, 21, 11   ---   8, 12, 22 : ikiye böleriz

[16,21] --- 11  ///   [8, 12] --- 22 : bölünen kısımları da tek eleman olana kadar ikiye böleriz, bölünmüyorsa bir tarafta birden çok eleman olabilir.

[11, 16, 21]    ----    [8, 12, 22] bölünen kısımları sıralarız ve en sonunda hepsini birleştiririz.

            8,11,12,16,21,22
            
2)

Worst case   : O(n*logn)

Average case : O(n*logn)

Best case    : O(n*logn)

