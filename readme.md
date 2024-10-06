soru 1- [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

cevap 1 
[22,27,16,2,18,6] n 
[2,27,16,22,18,6] n-1 2 ile 22 nin yeri değişti
[2,6,16,22,18,27] n-2 27 ile 6 nın yeri değişti
[2,6,16,18,22,27] n-3 22 ile 18 in yeri değişti


soru 2- Big-O gösterimini yazınız.
cevap 2 

n+(n-1)+(n-2)+...+1= n.(n+1)/2  O(n^2) olur.



soru 3- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

cevap 3 
[2,6,16,18,22,27]
Average case olur.

soru 4- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


cevap 4 

[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]