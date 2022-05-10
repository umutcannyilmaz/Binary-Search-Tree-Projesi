# Binary Search Tree Projesi
## Proje 3

> [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

>**Örnek:** root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

> Binary Search Tree 'de eleman eklemek için root' dan başlanır. Root 'tan küçük sayılar sol tarafa, büyük sayılar ise sağ
tarafına yazılırak bir ağaç(tree) yapısı oluşturulmuş olur.


````
Root = 7
````

5<7 root' un solunda 5 bulunur.

            7
        5


1<7 root' un solunda

1>5 5' in solunda bulunur.

            7
        5
    1

8>7 root' un sağında bulunur.

                7
                    8

3<7 root' un solunda

3<5 5' in solunda

3>1 1' in sağında bulunur.

                7
            5       8
        1  
            3

6<7 root' un solunda

6>5 5' in sağında bulunur.

                7
            5       8
        1       6
            3

0<7 root' un solunda

0<5  5' in solunda

0<1 1' in solunda bulunur.

                7
            5       8
        1       6
    0        3

9>7 root 'un sağında

9>8 8' in sağında

                7
            5       8
        1       6       9
    0        3

4<7 root' un solunda

4>5 5' in solunda

4>1 1' in sağında

4>3 3' ün sağında bulunur.

                7
            5       8
        1       6       9
    0        3
                4

2<7 root' un solunda

2<5 5' in solunda

2>1 1' in sağında

2<3 3' ün solunda bulunur.

                7
            5       8
        1       6       9
    0        3
        2        4


            