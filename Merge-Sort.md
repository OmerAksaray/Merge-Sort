[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Dizimizi parçalara ayırıyoruz
[16,21,11] [8,12,22] Tekrardan parçalara ayırıyoruz
[16] [21,11]
Şmdi ise sıralanmış dizilimle birleşmeye başlıyor.
[16] [11,21] , [8] [12,22] 
şimdi bir üst basmağa çıkarak 3 lü dizi oluşturuyorlar
[11,16,21] ,[8,12,22]
son olarak en üst basamakta birleşiyorlar
[8,11,12,16,21,22].
Time Complexi hesapladığımızda n log n buluruz.
çünkü parçalarken n kere parçalayacağız bu da 2^x=n den log n 
ve her satırda da n kere kontrol yapcağımızdan O(n log n) bulmamızı sağlar.
