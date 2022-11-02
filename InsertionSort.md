[Patika.dev](https://www.patika.dev/tr) 
### Proje 1 [22,27,16,2,18,6] ->  Insertion Sort 
### 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. 
    [22,27,16,2,18,6]     // Başlangıç 
    [2,27,16,22,18,6]    // 2 ile 22 yer değiştirir. 
    [2,6,16,22,18,27]    // 6 ile 27 yer değiştirir. 
    [2,6,16,18,22,27]    // 22 ile 18 yer değiştirir. 

### 2) Big-O gösterimini yazınız. 
    Worst case:  O(n^2) 
    Average case: O(n^2) 
    Best case: O(n) 

### 3) Time Complexity: 
    -Average case: Aradığımız sayının ortada olması,                [2,6,16,18,22,27] 
    -Worst case: Aradığımız sayının sonda olması,  			[27,22,18,16,6,2] 
    -Best case: Aradığımız sayının dizinin en başında olması.    	[2,6,16,18,22,27] 

### 4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. 
    Aradığımız sayı başta /sonda olmadığı için Best/Worst Case kapsamına girmez. 
    Ortada olduğu için Average Case kapsamındadır. 
    Average Case: [2,6,16,18,22,27] 

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız. 
    [7,3,5,8,2,9,4,15,6]	// Başlangıç. 
    [2,3,5,8,7,9,4,15,6]	// 2 ile 7 yer değiştirir. 
    [2,3,4,8,7,9,5,15,6]	// 5 ile 4 yer değiştirir. 
    [2,3,4,5,7,9,8,15,6]	// 8 ile 5 yer değiştirir.