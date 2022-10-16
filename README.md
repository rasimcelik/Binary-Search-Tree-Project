# Binary-Search-Tree-Project

[patika.dev](https://www.patika.dev)

Patika.dev > Veri Yapıları ve Algoritmalar > Binary Search Tree Projesi

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root = 7

### 1) 5 sayısı 7'den küçük olduğu için sol node olarak ekledik.

| Açıklama      |       |     |     |
| ------------- | ----- | --- | --- |
|               |       |     | 7   |
|               |       | /   |     |
| **5 ekledik** | **5** |     |     |

### 2) 1 sayısı 5 ve 7'den küçük olduğu için sol node olarak ekledik.

| Açıklama      |       |     |     |     |     |
| ------------- | ----- | --- | --- | --- | --- |
|               |       |     |     |     | 7   |
|               |       |     |     | /   |     |
|               |       |     | 5   |     |     |
|               |       | /   |     |     |     |
| **1 ekledik** | **1** |     |     |     |     |

### 3) 8 sayısı 7'den büyük olduğu için 7'nin sağına node olarak ekledik.

| Açıklama      |     |     |     |     |     |     |       |
| ------------- | --- | --- | --- | --- | --- | --- | ----- |
|               |     |     |     |     | 7   |     |       |
|               |     |     |     | /   |     | \   |       |
| **8 ekledik** |     |     | 5   |     |     |     | **8** |
|               |     | /   |     |     |     |     |       |
|               | 1   |     |     |     |     |     |       |

### 4) 3 sayısı 5 ve 7'den küçük fakat 1'den büyük olduğu için 1'in sağına node olarak ekledik.

| Açıklama      |     |     |       |     |     |     |     |
| ------------- | --- | --- | ----- | --- | --- | --- | --- |
|               |     |     |       |     | 7   |     |     |
|               |     |     |       | /   |     | \   |     |
|               |     |     | 5     |     |     |     | 8   |
|               |     | /   |       |     |     |     |     |
|               | 1   |     |       |     |     |     |     |
|               |     | \   |       |     |     |     |     |
| **3 ekledik** |     |     | **3** |     |     |     |     |

### 5) 6 sayısı 5'den büyük ve 7'den küçük olduğu için 5'in sağına node olarak ekledik.

| Açıklama      |     |     |     |     |       |     |     |
| ------------- | --- | --- | --- | --- | ----- | --- | --- |
|               |     |     |     |     | 7     |     |     |
|               |     |     |     | /   |       | \   |     |
|               |     |     | 5   |     |       |     | 8   |
|               |     | /   |     | \   |       |     |     |
| **6 ekledik** | 1   |     |     |     | **6** |     |     |
|               |     | \   |     |     |       |     |     |
|               |     |     | 3   |     |       |     |     |

### 6) 0 sayısı 7'den 5'ten ve 1'den küçük olduğu için 1'in soluna node olarak ekledik.

| Açıklama      |       |     |     |     |     |     |     |     |     |
| ------------- | ----- | --- | --- | --- | --- | --- | --- | --- | --- |
|               |       |     |     |     |     |     | 7   |     |     |
|               |       |     |     |     |     | /   |     | \   |     |
|               |       |     |     |     | 5   |     |     |     | 8   |
|               |       |     |     | /   |     | \   |     |     |     |
|               |       |     | 1   |     |     |     | 6   |     |     |
|               |       | /   |     | \   |     |     |     |     |     |
| **0 ekledik** | **0** |     |     |     | 3   |     |     |     |     |

### 7) 9 sayısı 7'den ve 8'den büyük olduğu için 8'in sağına node olarak ekledik.

| Açıklama      |     |     |     |     |     |     |     |     |     |     |       |
| ------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ----- |
|               |     |     |     |     |     |     | 7   |     |     |     |       |
|               |     |     |     |     |     | /   |     | \   |     |     |       |
|               |     |     |     |     | 5   |     |     |     | 8   |     |       |
|               |     |     |     | /   |     | \   |     |     |     | \   |       |
| **9 ekledik** |     |     | 1   |     |     |     | 6   |     |     |     | **9** |
|               |     | /   |     | \   |     |     |     |     |     |     |       |
|               | 0   |     |     |     | 3   |     |     |     |     |     |       |

### 8) 4 sayısı 7'den ve 5'den küçük 1'den ve 3'den büyük olduğu 3'ün sağına node olarak ekledik.

| Açıklama      |     |     |     |     |     |     |       |     |     |     |     |
| ------------- | --- | --- | --- | --- | --- | --- | ----- | --- | --- | --- | --- |
|               |     |     |     |     |     |     | 7     |     |     |     |     |
|               |     |     |     |     |     | /   |       | \   |     |     |     |
|               |     |     |     |     | 5   |     |       |     | 8   |     |     |
|               |     |     |     | /   |     | \   |       |     |     | \   |     |
|               |     |     | 1   |     |     |     | 6     |     |     |     | 9   |
|               |     | /   |     | \   |     |     |       |     |     |     |     |
|               | 0   |     |     |     | 3   |     |       |     |     |     |     |
|               |     |     |     |     |     | \   |       |     |     |     |     |
| **4 ekledik** |     |     |     |     |     |     | **4** |     |     |     |     |

### 9) 2 sayısı 7'den ve 5'den küçük, 1'den büyük ve 3'den küçük olduğu için 3'ün soluna node olarak ekledik.

| Açıklama      |     |     |       |     |     |     |     |     |     |     |     |
| ------------- | --- | --- | ----- | --- | --- | --- | --- | --- | --- | --- | --- |
|               |     |     |       |     |     |     | 7   |     |     |     |     |
|               |     |     |       |     |     | /   |     | \   |     |     |     |
|               |     |     |       |     | 5   |     |     |     | 8   |     |     |
|               |     |     |       | /   |     | \   |     |     |     | \   |     |
|               |     |     | 1     |     |     |     | 6   |     |     |     | 9   |
|               |     | /   |       | \   |     |     |     |     |     |     |     |
|               | 0   |     |       |     | 3   |     |     |     |     |     |     |
|               |     |     |       | /   |     | \   |     |     |     |     |     |
| **2 ekledik** |     |     | **2** |     |     |     | 4   |     |     |     |     |
