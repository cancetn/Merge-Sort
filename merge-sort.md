# Merge Sort
## Patika.dev egitim kampi süresince yapilmis proje odevdir.

### Elemanlarin Siralanmasi

[16,21,11,8,12,22] -> Merge Sort

* [16,21,11] ve [8,12,22] -> Dizi iki parcaya ayrilir.
* [16][21,11] ve [8][12,22] -> Parcalanan bu bloklar kendi iclerinde parcalanir.
* [16][21][11] ve [8][12][22] -> Tum bloklar parcalanarak tek eleman haline donusturulmus olur.
* [16][11,21] ve [8][12,22] -> Tek elemanlar sırlama goz onunde bulundurularak birlestirilir.
* [11,16,21] ve [8,12,22] -> Bloklar siralama goz onunda bulundurulark tekrar olusturulur.
* [8,11,12,16,21,22] -> Bloklar birlestirilir ve sirlama saglanmis olur.

### Big-o-notation

O(nlogn) n=6 , O(6log6)