Proje 1

[22,27,16,2,18,6] -> Insertion Sort
1.	Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.	Big-O gösterimini yazınız.
3.	Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

ÇÖZÜM:
Not: videodaki anlatımla internetten baktığım sort tanımları farklıydı. Ben internetteki çözümü baz alarak soruları çözdüm.

1)

[22,27,16,2,18,6] : (n) 22 ile 27 sıralı olduğundan onlar tutulup bir sonrakine bakılır, 16 hepsinden küçük olduğu için en başa geçer.

[16,22,27,2,18,6] : (n-1) baştakiler sıralı tutulur ve bir sonraki elemana bakılır, 2 hepsinden küçük olduğu için başa geçer.

[2,16,22,27,18,6] : (n-2) bir sonraki 18 değeri 16’dan sonra gelir.

[2,16,18,22,27,6] : en son 6, 2’den sonra yerleştirilir. (n-3)

[2,6,16,18,22,27] : sıralı hali

---------------

2)

Big-O gösterimi: işlem sayılarını baştan itibaren topladığımızda, n + n-1 + n-2 + … + 1 ile karşılaşırız. Bu sayıların toplamı ise 

n.(n+1)/ 2 = n^2 + n / 2 'dir. Kısaca: n^2

---------------
3)

Worst Case:

[27,22,18,16,6,2] - O(n^2)

Best Case:

[2,6,16,18,22,27] - O(n)

----------------

4)
Sıralanan dizide 18 sayısı dizinin ortanca değeri olduğu için, average case kapsamına girmektedir.

----------------

5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


•	[3,7,5,8,2,9,4,15,6]

•	[3,5,7,8,2,9,4,15,6]

•	[3,5,7,8,2,9,4,15,6]

•	[3,5,7,2,8,9,4,15,6]

