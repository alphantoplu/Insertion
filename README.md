# Insertion_Sort
[22 27 16 2 18 6]    our series
1-[2|27 16 22 18 6]      
2-[2 6 | 16 22 18 27]   
3-[2 6 16 | 22 18 27]  
4-[2 6 16 18 | 22 27]  
5-[2 6 16 18 22 | 27]  
6-[2 6 16 18 22 27 |]  

Worst Case: Worst case is a reverse sequence.
0+1+2+....+n= n.(n+1)/2 = (n^2+n)/2--->dominator is n^2
For example 18 is a worst case

Best case: Best case is A sequence ordered from smallest to largest.
Big-O=n
For example 16 is a best case 

Average Case= (n^2+n)/2----> Big-O dominator is n^2 

Another Example
[7 3 5 8 2 9 4 16 6] our series
1-[2 | 3 5 8 7 9 4 15 6]
2-[2 3 | 4 8 7 9 5 15 6]
3-[2 3 4 | 5 7 9 8 15 6]
4-[2 3 4 5 | 7 9 8 15 6]



