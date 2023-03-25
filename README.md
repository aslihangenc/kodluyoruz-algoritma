# kodluyoruz-algoritma
## https://app.patika.dev/aslhngencc
---
---
# Selection Sort Projesi
---
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.



* 1. Aşama : [2,27,16,22,18,6]
* 2. Aşama : [2,6,16,22,18,27]
* 3. Aşama : [2,6,16,18,22,27]

---

Big-O gösterimini yazınız.



* nx(n-1)x(n-2)x......x(1)

  = nx(n+1)/2

  =(n²+n)/2

   ## =O(n²)
   ---
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

   * Average Case

   ---
   ---
   # Merge Sort Projesi
   ---
   [16,21,11,8,12,22] -> Merge Sort

   Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

    1. [16,21,11]                   [8,12,22]
            
    2. [16]  [21,11]                [8]  [12,22]

    3. [16]  [21]  [11]             [8]   [12]--[22] 

    4. [16]  [11,21]                [8]   [12,22]
                    
    5.   [11,16,21]                   [8,12,22]

    6.             [8,11,12,16,21,22]    
---
Big-O gösterimini yazınız.
* O[nlogn]
---
---
# Binary Search Tree Projesi
---
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* Dizin : [0,1,2,3,4,5,6,7,8,9]
* root : (5)
* Sağ tarafınfa kendinden büyük; sol tarafında kendinden küçük elemanlar.

                        [5]
                       /   \
                      /     \
                     /       \
                  [3]         [8] 
                  /\          / \
                 /  \        /   \
               [2]  [4]    [6]  [9]
               /              \
             [1]              [7]


