# Binary Search

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
(root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.)

>CEVAP:  
>İlk eleman root olarak seçilir.  
Sonra gelen elemanlar root dan aşağı doğru bakılarak büyükse sağa küçükse sola dallanır.
	
|             |  |  |     |  |  |  |  |  |  |  |  |
|--           |--|--|-    |- |- |- |- |- |- |- |- |
|             |  |  |     |  |  |  | 7|  |  |  |  |  
|             |  |  |     |  |  | /|  |\ |  |  |  | 
|             |  |  |     |  | 5|  |  |  |8 |  |  | 
|             |  |  |     | /|  |\ |  |  |  |\ |  | 
|             |  |  | 1   |  |  |  |6 |  |  |  | 9|
|             |  | /|     |\ |  |  |  |  |  |  |  |
|             | 0|  |     |  | 3|  |  |  |  |  |  |
|             |  |  |     | /|  |\ |  |  |  |  |  |
|             |  |  |  2  |  |  |  |4 |  |  |  |  |	
