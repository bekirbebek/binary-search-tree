# binary-search-tree
Veri Yapıları ve Algoritmalar 
Binary Search Tree Projesi Dev Patkika Ödevi 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
Çözüm: Bir düğüm her iki tarafa da referans verebilir. 
Başlangıçtaki sayıdan büyükse sağa, küçükse sola geçip bağlanır. 
Yeni bir sayı geldiğinde en baştaki sayıdan itibaren sorgulayarak, o sayıdan büyükse sağına; küçükse soluna referans alarak devam eder. 
Kendini düğüme en sondan bağlar. 
                                  7 (root:X)
                           5 (Z)            8 (Y)
                       
                   4            6                 9
              3             2 
          1            0
          Bu şekilde bir sıralama yapılabilir. 
