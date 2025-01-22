# **1. INSERTION SORT PROJESİ**


*[22,27,16,2,18,6] -> Insertion Sort*

*1.* *Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.*

*2.* *Big-O gösterimini yazınız.*

*3.* *Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.*

*4.* *Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.*

---
## ***Verilen dizinin insertion sort adımları***

* Dizinin insertion sort türüne göre adımları:  
[22,27,16,2,18,6] -> Başlangıç
```
1-> İlk eleman zaten sıralı kabul edilir. [22]

2-> 27 22'den büyük olduğu için yer değiştirmez. [22, 27]

3-> 16, 27'den küçük olduğu için 27'nin önüne, ardından 22'nin de önüne geçer. [16, 22, 27]

4-> 2, dizideki tüm elemanlardan küçük olduğu için en başa yerleşir. [2, 16, 22, 27]

5-> 18, 22'den küçük ancak 16'dan büyük olduğu için 16 ile 22'nin arasına yerleşir. [2, 16, 18, 22, 27]

6-> 6, 16'dan küçük olduğu için 16'nın önüne geçer. [2, 6, 16, 18, 22, 27]

Sonuç: [2, 6, 16, 18, 22, 27]
```

## ***Big-O Gösterimi***
En kötü durumda her eleman için dizinin geri kalan elemanlarıyla kıyaslama yapılır. Bu da n(n-1)/2* kıyaslama demektir.
En iyi durumda, yani dizi zaten sıralıysa, her eleman sadece bir kez kontrol edilir. O(n).

**Worst Case:** O(n^2)

**Average Case:** O(n^2)

**Best Case:** O(n)



##  ***Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.***
Sıralamanın ortasında bulunduğu için **Average Case** kapsamına grirer.


---


## **[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [2,3,5,7,8,9,4,15,6]
```
---
