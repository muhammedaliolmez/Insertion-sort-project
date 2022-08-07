# Insertion sort projesi

## [22,27,16,2,18,6] -> Insertion Sort
## Yukarı verilen dizinin ınsertion sort türüne göre aşamalarını yazınız.

[22|,27,16,2,18,6]  
[22,27|,16,2,18,6]   
[22,16,27|,2,18,6]  
[16,22,27|,2,18,6]  
[16,22,2,27|,18,6]  
[16,2,22,27|,18,6]  
[2,16,22,27|,18,6]  
[2,16,22,18,27|,6]  
[2,16,18,22,27|,6]  
[2,16,18,22,6,27|]  
[2,16,18,6,22,27|]  
[2,16,6,18,22,27|]  
[2,6,16,18,22,27|]  

## Big-O gösterimini yazınız.

(n.(n+1))/2  
O(n²)  

## Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Algoritma 18 sayısını 8.adımda sıraya sokmaktadır.Best case = n, Worst Case=n² olarak hesaplanmıştır. Bu durumda örnek 7-28 adım aralığında çözülmesi beklenmektedir. 8 sayısı bu aralıkta olduğu için 18 sayısının sıralanması avarage case olarak değerlendirilir.  

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7|,3,5,8,2,9,4,15,6]  
[3,7|,5,8,2,9,4,15,6]  
[3,5,7|,8,2,9,4,15,6]  
[3,5,7,8|,2,9,4,15,6]  
[3,5,7,2,8|,9,4,15,6]  


