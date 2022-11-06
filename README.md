# Binary-Search-Tree-Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
Rootumuz 7'dir.Roottan küçük olanlar sol tarafa büyük olanlar ise sağ tarafına yazılır.
5<7 ise 5 7'nin solunda bulunur.
1 < 7 , 1 < 5 olduğuna göre,1 hem 5 hem de 7'nin solunda bulunur.
8>7 olduğundan 8,7'nin sağında bulunur.
3<7 3<5 3>1 olduğundan, 3, 7 ve 5'in solunda;1'in sağında bulunur.
6<7 6>5 olduğundan 6 7'nin solunda 5'in ise sağında bulunmaktadır.
0<7 0<5 0<1 olduğundan 0 hem 7 hem 5 hem de 1'in solunda bulunur.
9>7 9>8 olduğundan 9, 7 ve 8'in sağında bulunur.
4<7 4<5 4>1 4>3 olduğundan 4 7 ve 5'in solunda 1 ve 3'ün sağında bulunur.
2<7 2<5 2>1 ve 2<3 olduğundan 2 1'in sağında ancak 7,5 ve 3'ün solunda bulunur.Algoritma burada biter.
                      7
                     / \
                    5   8
                   / \   \
                  1   6   9
                 / \
                0  3
                  / \
                 2   4
                 www.patika.dev
