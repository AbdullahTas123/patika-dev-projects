# Soru 1
[22,27,16,2,18,6] -> Insertion Sort

Soru 1.1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Soru 1.2- Big-O gösterimini yazınız.

Soru 1.3- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

  1. Average case: Aradığımız sayının ortada olması
  2. Worst case: Aradığımız sayının sonda olması
  3. Best case: Aradığımız sayının dizinin en başında olması.

# Soru 2
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# Cevap 1
## Cevap 1.1 Aşamalar
- [22,27,16,2,18,6] -> [22,27,16,2,18,6]
- [22,27,16,2,18,6] -> [22,16,27,2,18,6] -> [16,22,27,2,18,6]
- [16,22,27,2,18,6] -> [16,22,2,27,18,6] -> [16,2,22,27,18,6] -> [2,16,22,27,18,6]
- [2,16,22,27,18,6] -> [2,16,22,18,27,6] -> [2,16,18,22,27,6]
- [2,16,18,22,27,6] -> [2,16,18,22,6,27] -> [2,16,18,6,22,27] -> [2,16,6,18,22,27] -> [2,6,16,18,22,27]

## Cevap 1.2 Big-O
n*(n-1)/2 = O(n^2)

## Cevap 1.3 Time Complexity
1. Average case: O(n^2)
2. Worst case: O(n^2)
3. Best case: O(n)
- Aradığımız 18 sayısı Avarage Case kapsamına girer.

# Cevap 2
- [7,3,5,8,2,9,4,15,6] -> [2,3,5,8,7,9,4,15,6]
- [2,3,5,8,7,9,4,15,6] -> [2,3,5,8,7,9,4,15,6]
- [2,3,5,8,7,9,4,15,6] -> [2,3,4,8,7,9,5,15,6]
- [2,3,4,8,7,9,5,15,6] -> [2,3,4,5,7,9,8,15,6]
- [2,3,4,8,7,9,5,15,6] -> [2,3,4,5,6,9,8,15,7]

# Patika Profilim
- [Abdullah Taş](https://app.patika.dev/AbdullahTas123)