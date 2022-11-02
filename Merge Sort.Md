# Merge Sort Projesi

## [16,21,11,8,12,22] -> Merge Sort
### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
1.	Dizinin ilk hali =>	[16,21,11,8,12,22]					
2.	Diziyi sağ ve sol olmak üzere ikiye bölüyoruz =>	[16,21,11]			[8,12,22]		
3.	Tek eleman kalıcak şekilde bölme işlemine devam ediyoruz =>	[16]	[21]	[11]	[8]	[12]	[22]
4.	Bölme işlemini yaptıktan sonra dizinin elemanlarını ikili şekilde sırayalarak birleştiriyoruz =>	[16,21]		[11]	[8,12]		[22]
5.	Birleştirme işlemine devam ediyoruz => [11,16,21]			[8,12,22]		
6.	Son kez birleştirme işlemi yapıyoruz ve dizinin 
son halini elde ediyoruz =>	[8,11,12,16,21,22]	

   ![image](https://user-images.githubusercontent.com/116514758/199437726-9d64c606-adda-4614-8274-b58bc454a339.png)





 ### 2. Big-O gösterimini yazınız.
 ```
  O(nlogn)
 ```
 
