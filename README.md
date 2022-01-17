# Project Ödevi - Emre Akdag
## Proje 1 -Insertion Sort

### Asagidaki dizinin sort türüne göre siralanmasi
```
* [22,27,16,2,18,6]
* [22|27,16,2,18,6]
* [22,27|16,2,18,6]
* [16,22,27|2,18,6]
* [2,16,22,27|18,6]
* [2,16,18,22,27|6]
* [2,6,16,18,22,27]
```
```
Dizinin Big-O gösterimi ise; n²
```
### Time Complexity;
* *Average Case*: Aradigimiz sayinin ortada olmasi.
* *Worst Case*: Aradigimiz sayinin sonda olmasi. 
* *Best Case*: Aradigimiz sayinin en basta olmasi.

Yukaridaki durumlara göre 18 sayinin yerini inceleyecek olursak, bu durumun ***Average Case*** kapsamina girdigini belirtebiliriz.

[7,3,5,8,2,9,4,15,6] dizininin ilk dört asamasi asagidaki sekildedir ;

```
* [7|3,5,8,2,9,4,15,6]
* [3,7|5,8,2,9,4,15,6]
* [3,5,7|8,2,9,4,15,6]
* [3,5,7,8|2,9,4,15,6]
``` 
