<h1>Proje 1</h1>

[22,27,16,2,18,6] -> Insertion Sort

#### 1) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız:
##### Cevap: <p align="center">

| Aşama | Dizi | Seçilen Eleman | Karşılaştırma |
| :----: | :----: | :----: | :----: |
| 1 | [22, 27, 16, 2, 18, 6] | 27 | (22 < 27) |
| 2 | [22, 27, 16, 2, 18, 6] | 16 | (16 < 27) & (16 < 22) |
| 3 | [16, 22, 27, 2, 18, 6] | 2 | (2 < 27) & (2 < 22) & (2 < 16) |
| 4 | [2, 16, 22, 27, 18, 6] | 18 | (18 < 27) & (18 < 22) & (16 < 18) |
| 5 | [2, 16, 18, 22, 27, 6] | 6 | (6 < 27) & (6 < 22) & (6 < 18) & (6 < 16) & (2 < 6) |
| 6 | [2, 6, 16, 18, 22, 27] | - | - |
</p>

#### 2) Big-O gösterimini yazınız:
##### Cevap: O(n^2)

#### 3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız:
##### Cevap: Average case kapsamına girer.
