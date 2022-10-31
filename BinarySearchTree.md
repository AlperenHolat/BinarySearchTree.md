[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1. Root is 7 
       7
2. 5 is smaller than 7. So it is on the left side of the root.
       7
      /
     5
3. 1 is smaller than 7 and 5. Left side.
       7
      /
     5
    /
   1
4. 8 is bigger than 7. Rigth side.
       7
      /  \
     5    8
    /
   1
5. 3 is smaller than 7 and 5 but bigger than 1. 
       7
      /  \
     5    8
    /
   1
    \
     3
6. 6 is smaller than 7 but bigger than 5. 
       7
      /  \
     5    8
    / \
   1   6
    \
     3
 7.0 is smaller than 7, 5 and 1.
       7
     /   \
    5     8
   / \     
  1   6       
 /  \ 
0    3
8. 9 is bigger than 7 and 8.
       7
     /   \
    5     8
   / \     \
  1   6     9  
 /  \
0    3
9. 4 is smaller than 7 and 5 but bigger than 3.
       7
     /   \
    5     8
   / \     \
  1   6     9  
 /  \
0    3
      \
       4
10. 2 is smaller than 7 and 5 but bigger than 1. Also smaller than 3.
       7
     /   \
    5     8
   / \     \
  1   6     9  
 /  \
0    3
    /  \
    2   4

     
  
      
