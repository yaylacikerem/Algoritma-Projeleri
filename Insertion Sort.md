# Insertion Sort Projesi

## [22,27,16,2,18,6] -> Insertion Sort
### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
 ``` 
 I. [22,27,16,2,18,6] => n
 II. [2,27,16,22,18,6] => n-1
 III. [2,6,16,22,18,27] => n-2
 IV. [2,6,16,18,22,27] => 1 
  ```
 ### 2. Big-O gösterimini yazınız. 
 ``` 
 I. (n.(n+1))/2
 II. (n^2+n)/2
 III. O(n^2)
 
 ``` 
 ### 3.Time Complexity:
 ``` 
 Average Case: Aradığımız sayının ortada olması           : Θ(n^2)
 Worst case: Aradığımız sayının sonda olması              : Θ(n^2)
 Best case: Aradığımız sayının dizinin en başında olması. : Θ(n)
  ``` 
  
 ### 4. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 ``` 
 I.  [2,3,5,8,7,9,4,15,6] -> 2 sayısı  ile 7 sayısı yer değiştirdi.
 II. [2,3,4,8,7,9,5,15,6] -> 5 sayısı  ile 4 sayısı yer değiştirdi.
 III.[2,3,4,5,7,9,8,15,6] -> 8 sayısı  ile 5 sayısı yer değiştirdi.
 IV. [2,3,4,5,6,9,8,15,7] -> 6 sayısı  ile 7 sayısı yer değiştirdi.
 ``` 
  ### 5. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 ``` 
Dizinin insertion sort'a göre sıralanmış hali : [2,6,16,18,22,27]
Aradığımız 18 sayısı başta veya sonda bulunmadığı için average case kapsamına girer.
 ``` 
