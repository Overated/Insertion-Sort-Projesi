# **Insertion Sort Projesi**

Bu repo [Patica.dev](https://www.patika.dev/tr) Veri Yapıları ve Algoritmalar Eğitiminde oluşturduğumuz insertion Sort Proje reposudur. İçerisinde bir adet README dosyası barındırmaktadır.

-----
## **Soru**
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

---------------

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## **Cevap**
-----------------

### *Adım 1*

```
[22,27,16,2,18,6] n
```
![1.Adım](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/a1.png)

### *Adım 2*

```
[2,27,16,22,18,6] n-1
```

![2.Adım](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/a2.png)

### *Adım 3*
```
[2,6,16,22,18,27] n-2
```

![3.Adım](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/a3.png)

### *Adım 4*

```
[2,6,16,18,22,27] 1
```

![4.Adım](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/a4.png)






-------

## **2.Big-O gösterimi:**



## $(n.(n+1))\over 2$   ➡️      $(n^2+n)\over 2$  ➡️  Big-O = $0(n^2)$ 


-----

## **3.Time Complexity:**

**Best Case:** Aradığımız verinin dizinin en başında bulunduğu durum

![bestcase](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/bestcase.png)

**Avarage Case:** Aradığımız verinin dizinin ortasında bulunduğu durum

![avaragecase](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/avaragecase.png)

**Worst Case:** Aradığımız verinin dizinin en sonunda bulunduğu durum

![worstcase](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/worstcase.png)


## **4.Dizi sıralandıktan sonra 18 Sayısı hangi case kapsamındadır;**

Dizi sıralandıktan sonra 18 sayısı **Avarage Case** kapsamında bulunmaktadır

![dizisıralama sonrası](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/dizisiralama.png)

## **5.Dizisinin Insertion Sort'a göre ilk 4 adımı;**

### *Adım 1*

```
[2,3,5,8,7,9,4,15,6]       Dizide 2 ile 7'nin yeri değişmiştir.
```

![Adım1](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/b1.png)

### *Adım 2*

```
[2,3,5,8,7,9,4,15,6]       Dizide 3 sayısı 2'den sonraki en büyük sayı olduğu için hiçbir sayı yer değişmemiştir. 
```
![Adım2](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/b5.png)

### *Adım 3*

```
[2,3,4,8,7,9,5,15,6]       Dizide 5 ile 4'ün yeri değişmiştir.
```
![Adım3](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/b2.png)

### *Adım 4*

```
[2,3,4,5,7,9,8,15,6]       Dizide 8 ile 5'in yeri değişmiştir. 
```
![Adım4](https://raw.githubusercontent.com/Overated/Insertion-Sort-Projesi/main/image/b4.png)


[Patica.dev](https://www.patika.dev/tr)

# Contributing
Pull requestler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir konu açınız.

# License
[MIT](https://choosealicense.com/licenses/mit/)