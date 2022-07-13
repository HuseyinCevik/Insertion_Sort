# Insertion_Sort

[22,27,16,2,18,6]

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6] ------>bu dizinin en küçük terimi ile 1. terimi yani 22 yer değiştirir.

[2,27,16,22,18,6] ------>2 elemanı artık sabit. 27,16,22,18,6 arasında en küçük olan ile yine 1. terim yani 27 yer değiştirir.

[2,6,16,22,18,27] ------>2,6 elemanları sıralı ve sabit. 16,22,18,27 arasında en küçük olan ile 16 yer değiştirmeli ancak bu dizide 16 en küçük ve doğru yerde.

[2,6,16,22,18,27] ------>2,6,16, elemanları sıralı ve sabit . 22,18,27 arasında en küçük olan 18 ile 1. terim yani 22 yer değiştirir.

[2,6,16,18,22,27] ------>2,6,16,18 elemanları sıralı ve sabit . Aslında tüm dizi sıralı halde ancak kod çalışmaya ve sıranın doğru olduğundan emin olur.

[2,6,16,18,22,27] ------>2,6,16,18,22 elemanları sıralı ve sabit. 

[2,6,16,18,22,27] ------>2,6,16,18,22,27 elemanları sıralı ve sabit. 


2.Big-O gösterimini yazınız.

O(n^2)

3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Average case: O(n²)
Worst case: O(n²)
Best case: O(n)

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

-Average case

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
