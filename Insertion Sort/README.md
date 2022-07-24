# Proje 1

## Insertion Sort Projesi

- **[22,27,16,2,18,6]** -> Insertion Sort

**1.** Verilen dizinin sort türüne göre aşamalarını yazınız.

**2.** Big-O gösterimini yazınız.

**3.** Time Complexity: Average case, Worst case, Best case

**4.** Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

**C1**  

​		[22,27,16,2,18,6]

​		[22,16,27,2,18,6]

​		[16,22,27,2,18,6] -> [16,22,2,27,18,6] -> [16,2,22,27,18,6] ->[2,16,22,27,18,6]

​		[2,16,22,27,6,18] -> [2,16,22,6,27,18] -> [2,16,6,22,27,18] -> [2,6,16,22,27,18] 

​		[2,6,16,22,18,27] -> [2,6,16,18,22,27] 

**C2** 

​		n^2

**C3** 

​		Worst case: n^2

​		Best case: n

​		Average case:  (n^2 + n)/2

**C4** 

​		Average case kapsamına girer.  



- **[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.



​		[7,3,5,8,2,9,4,15,6]

​		[3,7,5,8,2,9,4,15,6]

​		[3,5,7,8,2,9,4,15,6]

​		[3,5,7,8,2,9,4,15,6]



