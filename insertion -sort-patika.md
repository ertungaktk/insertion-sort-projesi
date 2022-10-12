# insertion-sort-projesi

[22,27,16,2,18,6]
1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


Aşama-1
[2,27,16,22,18,6]  değişen 2-22
[2,6,16,22,18,27]  değişen 6-27
[2,6,16,22,18,27]  değişen yok
[2,6,16,18,22,27]  değişen 18-22
[2,6,16,18,22,27]  değişen yok

Aşama-2
6(n) değerden 6(n) tane işleme baktım her aşamada 1 değer eksildiği için her aşamada (n-1) değere bakmış oldum
n+ (n-1) + (n-2) + (n-3) + (n-4)  -->  n.(n+1)/2  ----> n^2+2/2  ----->  O(n^2)

Aşama-3
18 sayısı average case kapsamına girmektedir.Değer dizinin ortasında bulunmaktadır.
