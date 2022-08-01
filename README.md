# Binary-Search-Tree-Projesi

Binary Search Tree Projesi - Aysun Akbal

www.patika.dev

Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


1. Aşama: Root 7'dir. 

Root'un sağına büyük değerler, soluna küçük değerler yazılır.

2. Aşama: 5, 7'den küçük olduğu için sola yazılır.

3. Aşama: 1, 5'ten küçük olduğu için 5'in soluna yazılır.

                  7
              5 
            1
          
4. Aşama: 8, 7'den büyük olduğu için 7'nin sağına yazılır.

                  7
              5       8
            1

5. Aşama: 3, 7 ve 5'ten küçük, 1'den büyük olduğu için 1'in sağına yazılır.

                  7
              5       8
            1
               3

6. Aşama: 6, 7'den küçük, 5'ten büyük olduğu için 5'in sağına yazılır.

                  7
              5       8
            1    6
               3

7. Aşama: 0, 7'den küçük, 5 ve 1'den küçük olduğundan 1'in soluna yazılır.

                  7
              5       8
            1    6
          0    3
          
8. Aşama: 9, 7'den ve 8'den büyük olduğu için 8'in sağına yazılır.


                  7
              5       8
            1    6       9
          0    3

9. Aşama: 4, 7 ve 5'ten küçük, 1 ve 3'ten büyük olduğu için 3'ün sağına yazılır.


                  7
              5       8
            1    6       9
          0    3
                  4

10. Aşama: 2, 7 ve 5'ten küçük olduğu için sol tarafa yazılacaktır. 1'den büyük olduğu için sağındaki 3'e bakarız. 3'ten küçük olduğundan soluna yazılır.

                7
              5       8
            1    6       9
          0    3
              2   4



www.patika.dev

