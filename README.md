# Insertion-Sort
[22,27,16,2,18,6] -> Insertion Sort  
  
1-) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.  
  
Başla  - [22,27,16,2,18,6]  
1 -  [2, | 27, 16, 22, 18, 6]  
2 - [2, 6, | 16, 22, 18, 27]  
3 - [2, 6, 16, | 22, 18, 27]  
4 - [2, 6, 16, 18, 22, 27]  
  
2-) Big-O gösterimini yazınız.  
  
1 - n  
2 - n + (n-1)  
3 - n + (n-2)  
.  
.  
.  
Son  1 tane kalana kadar  
  
 (n*(n-1))/2 -> O(n^2)  
   
   
> Time Complexity: Average case: Aradığımız sayının ortada olması,  
> Worst case: Aradığımız sayının sonda olması,   
> Best case: Aradığımız sayının dizinin en başında olması.  
>   
3-) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.  
  
Worst Case  
  
4-) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.  
  
Başla  - [7,3,5,8,2,9,4,15,6]  
1 - [2, | 3, 5, 8, 7, 9, 4, 15, 6]  
2 - [2, 3, | 5, 8, 7, 9, 4, 15, 6]  
3 - [2, 3, 4, | 8, 7, 9, 5, 15, 6]  
4 - [2, 3, 4, 5, | 7, 9, 8, 15, 6]  

 
