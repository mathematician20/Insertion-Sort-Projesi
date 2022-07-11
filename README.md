
# INSERTION SORT PROJESİ 1
## Proje 1 
### [22,27,16,2,18,6] -> Insertion Sort 
1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### Cevaplar
1 -> 1.aşama [2,27,16,22,18,6] (2 ile 22 yer değiştirdi)

      2.aşama[2,6,16,22,18,27] (6 ile 27)

      3.aşama[2,6,16,18,22,27] (18 ile 22)

      2 -> Big-O gösterimi insertion sortta n elemanlık dizide n+(n-1)+(n-2)+...+1= n.(n+1)/2 den O(n kare) olacağından bizim 6 elemanlı dizinin Big-O gösterimi O(36) dır.

      4-> Dizinin sıralanmış hali [2,6,16,18,22,27] ve aradığımız 18 sayısı ortada olduğundan 18 sayısı average case kapsamına girer.Eğer aradığımız sayı 2 olsaydı bu best case,27 olsaydı worst case kapsamına girerdi.

      Soru : [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

      1.adım [2,3,5,8,7,9,4,15,6]
      2.adım [2,3,4,8,7,9,5,15,6]
      3.adım [2,3,4,5,7,9,8,15,6]
      4.adım [2,3,4,5,6,9,8,15,7]
