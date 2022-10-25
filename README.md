# binary-search-tree

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

ilk değer olan 7 ROOT seçilir.


5 değeri root değerinden küçük olduğu için root değerinin sol altına yazılır.

         7 
        /
       5


1 değeri 7 ve 5 değerinden küçük olduğu için 5 değerinin sol altına yazılır.

         7
        / 
       5
      /
     1
     
     
8 değeri 7 değerinden büyük olduğu için 7 değerinin sağ altına yazılır.
  
           7
          / \
         5   8
        /
      1
      
       
3 değeri, 7 değerinden küçük olduğu için 5 değerine bakarız, 5 değerinden de küçük olduğu için 1 değerine bakarız, 1 değerinden büyük olduğu için 1 değerinin sağ altına yazarız.

          7
         / \
        5   8
       /
      1
       \
         3


6 değeri, 7 değerinden küçük olduğu için 5 değerine bakarız, 5 değerinden büyük olduğu için 5 değerinin sağ altına yazarız.

           7
          / \
         5   8
        / \
       1   6
       \
         3


0 değeri, 7 değerinden küçük olduğu için 5 değerine bakarız, 5 değerinden küçük olduğu için 1 değerine bakarız, 1 değerinden küçük olduğu için sol altına yazarız.

           7
          / \
         5   8
        / \
       1   6
      / \
     0   3


9 değeri. 7 değerinden büyük olduğu için 8 değerine bakarız, 8 değerinden büyük olduğu için sağ altına yazarız.

            7
           / \
          5   8
         / \    \
        1   6    9
       / \
      0   3
      

4 değeri, 7 değerinden küçük olduğu için 5 değerine bakarız, 5 değerinden küçük olduğu için 1 değerine bakarız, 1 değerinden büyük olduğu için 3 değerine bakarız, 3 değerinden büyük olduğu için sağ altına yazarız.

             7
            / \
           5    8
          / \     \
         1   6     9
        / \
       0   3
            \
             4


2 değeri, 7 değerinden küçük olduğu için 5 değerine bakarız, 5 değerinden küçük olduğu için 1 değerine bakarız, 1 değerinden büyük olduğu için 3 değerine bakarız, 3 değerinden küçük olduğu için 3 değerinin sol altına yazarız.

               7
              / \
             5   8
            / \    \
           1   6    9
          / \
         0   3
             / \
            2    4



















