# Insertion_Sort
## [22,27,16,2,18,6] -> Insertion Sort
### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
* [22,27,16,2,18,6]   n
* [2,27,16,22,18,6]   n-1
* [2,6,16,22,18,27]   n-2
* [2,6,16,18,22,27]   n-3
### 2.Big-O gösterimini yazınız.
 * (n.(n+1))/2
 * (n^2+n)/2
 * O(n^2)
 ### 3.Time Complexity:
 * Average case: Aradığımız sayının ortada olması durumunda gerçekleşir. =>[22,27,16,2,18,6]
 * Worst case: Aradığımız sayının sonda olması durumunda gerçekleşir. =>[27,22,18,16,6,2]
 * Best case: Aradığımız sayının başta olması durumunda gerçekleşir. =>[2,6,16,18,22,27]
 ### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 * [7,3,5,8,2,9,4,15,6]    n
 * [2,3,5,8,7,9,4,15,6]    n-1
 * [2,3,5,8,7,9,4,15,6]    n-2
 * [2,3,4,8,7,9,5,15,6]    n-3
