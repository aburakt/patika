# Merge Sort

[16,21,11,8,12,22] -> Merge Sort

a)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
b)Big-O gösterimini yazınız.

>CEVAP:
>a)  
> [16,21,11]          [8,12,22]  
> 16 [21,11]          8 [12,22]  
>  16 21 11            8 12 22  
> 16 [11,21]          8 [12,22]  
> [11,16,21]          [8,12,22]  
>        [8,11,12,16,21,22]  

>b)ikiye bölme (2^x = n)'den x=log(n) defa yapılır. Her bir adımın time complexity değeri O(n) olduğu için genel ifademiz;  
>O(nlog(n))
