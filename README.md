# Merge-Sort-Project
Merge sort algoritmasıyla sıralama 
***
### [16,21,11,8,12,22] dizisinin merge sort algoritmasına göre sıralanması

* Dizi tam ortadan bölünerek iki ayrı dizi oluşturulur. Eğer tam bölünmüyorsa ortada kalan sayı sağ veya sol tarafa eklenir. Bu ayırma işlemi tek eleman kalıncaya dek devam eder.
* [16,21,11] [8,12,22]  
* [16,21] [11]  [8,12] [22] 
* [16] [21] [11] [8] [12] [22] 
* Daha sonra dizi grupları karşılaştırma yapılarak tekrar birleştirilmeye başlanır.
* [16,21] [11] [8,12] [22]
* [11,16,21] [8,12,22]
* [8,11,12,16,21,22]
  
  ## Big O Notation
  ***
Time Complexity : O(nLogn) 'dir.

## Patika Dev 
***
[Patika dev hesabım](https://app.patika.dev/batium)
