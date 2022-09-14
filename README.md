# Veri Yapıları ve Algoritmalar

## Binary Search Tree Projesi

### Proje 3
---
1. **[7,5,1,8,3,6,0,9,4,2]** dizisinin Binary-Search-Tree aşamalarını yazınız.
   
    **Örnek:** root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
---
### Cevaplar
1. Cevap
   1.  Adımları
        > Root 8'dir.
        >
        > 7<8 root'un solunda 7 bulunur.
        >
        > 5<8 root'un solunda 5 bulunur. 
        >
        >> 5<7 - 7'nin solunda 5 bulunur.
        >>
        > 1<8 root'un solunda 1 bulunur.
        >>
        >> 1<7 - 7'nin solunda 1 bulunur.
        >>
        >> >1<5 - 5'in solunda 1 bulunur.
        >
        > 3<8 root'un solunda 3 bulunur.
        >>
        >> 3<7 - 7'nin solunda 3 bulunur.
        >>
        >>> 3<5 - 5'in solunda 3 bulunur.
        >>>
        >>>> 3>1 - 1'in sağında 3 bulunur.
        >>
        > 6<8 root'un solunda 6 bulunur.
        >>
        >> 6<7 - 7'nin solunda 6 bulunur.
        >> 
        >>> 6>5 - 5'in sağında 6 bulunur.
        >>
        > 0<8 root'un solunda 0 bulunur.
        >>
        >> 0<7 - 7'nin solunda 0 bulunur.
        >>
        >>> 0<5 - 5'in solunda 0 bulunur.
        >>>
        >>>> 0<1 - 1'in solunda 0 bulunur.
        >>
        > 9>8 root'un sağında 9 bulunur.
        >>
        > 4<8 root'un solunda 4 bulunur.
        >>
        >> 4<7 - 7'nin solunda 4 bulunur.
        >>
        >>> 4<5 - 5'in solunda 4 bulunur.
        >>>
        >>>> 4>1 - 1'in sağında 4 bulunur.
        >>>>
        >>>>> 4>3 - 3'ün sağında 4 bulunur.
        >>
        > 2<8 root'un solunda 2 bulunur.
        >>
        >> 2<7 - 7'nin solunda 2 bulunur.
        >>
        >>> 2<5 - 5'in solunda 2 bulunur.
        >>>
        >>>> 2>1 - 1'in sağında 2 bulunur.
        >>>> 
        >>>>>2<3 - 3'ün solunda 2 bulunur.

#