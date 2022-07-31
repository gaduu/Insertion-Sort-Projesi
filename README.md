# Insertion-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]--> n
 
[2,27,16,22,18,6]-->(n-1)

[2,6,16,22,18,27]-->(n-2)

[2,6,16,18,22,27]-->1

2. Big-O gösterimini yazınız.

n+ n-1 + n-2 +n-3+.....+1 = (n^2+n)/2 --> O(n^2)

3.Time Complexity:

Average case: Aradığımız sayının ortada olması, 16 ya da 18
Worst case: Aradığımız sayının sonda olmasıi, bu örnek için 27
Best case: Aradığımız sayının dizinin en başında olması, bu dizi için 2.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

18 sayısı Average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

-->[2,3,5,8,7,9,4,15,6]

-->[2,3,4,8,7,9,5,15,6]

-->[2,3,4,5,7,9,8,15,6]

-->[2,3,4,5,6,9,8,15,7]

www.patika.dev

