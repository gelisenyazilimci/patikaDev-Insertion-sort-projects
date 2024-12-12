## Insertion Sort

Verilen dizi: `[22,27,16,2,18,6]`

### Insertion Sort Aşamaları

1. İlk eleman zaten sıralı kabul edilir: `[22]`
2. `27` elemanı sıralı listenin sonuna eklenir: `[22,27]`
3. `16` elemanı sıralı dizide uygun yere yerleştirilir: `[16,22,27]`
4. `2` elemanı sıralı dizide uygun yere yerleştirilir: `[2,16,22,27]`
5. `18` elemanı sıralı dizide uygun yere yerleştirilir: `[2,16,18,22,27]`
6. `6` elemanı sıralı dizide uygun yere yerleştirilir: `[2,6,16,18,22,27]`

### Big-O Gösterimi

- Best Case: `O(n)`
- Average Case: `O(n^2)`
- Worst Case: `O(n^2)`

### Time Complexity ve 18 Sayısının Durumu

- **18 sayısı**, sıralandıktan sonra dizinin ortasında bulunur.
- Bu nedenle **Average Case** kapsamına girer.

---

## Selection Sort

Verilen dizi: `[7,3,5,8,2,9,4,15,6]`

### Selection Sort İlk 4 Adımı

1. Dizinin en küçük elemanı (`2`) bulunur ve ilk eleman ile yer değiştirilir: `[2,3,5,8,7,9,4,15,6]`
2. Geri kalan alt dizi içerisindeki en küçük eleman (`3`) bulunur, zaten yerinde olduğu için değişiklik yapılmaz: `[2,3,5,8,7,9,4,15,6]`
3. Geri kalan alt dizi içerisindeki en küçük eleman (`4`) bulunur ve üçüncü eleman ile yer değiştirilir: `[2,3,4,8,7,9,5,15,6]`
4. Geri kalan alt dizi içerisindeki en küçük eleman (`5`) bulunur ve dördüncü eleman ile yer değiştirilir: `[2,3,4,5,7,9,8,15,6]`

---
