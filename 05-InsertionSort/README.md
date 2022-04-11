
## Insertion Sort


Dizideki ikinci eleman başlangıç elemanı olarak seçilir ve kendisinden önce gelen yani solunda eleman ile kıyaslanır. Eğer birinci eleman ikinci elemandan büyükse yer değiştirirler. Değilse bir sonraki elemana geçilir.

**[22,27,16,2,18,6]** dizisinin Insertion sort'a göre aşamaları;


- [22,**27**,16,2,18,6]
- [22,**16**,27,2,18,6]
- [**16**,22,27,2,18,6]
- [16,22,**2**,27,18,6]
- [16,**2**,22,27,18,6]
- [**2**,16,22,27,18,6]
- [**2**,16,22,18,27,6]
- [2,16,**18**,22,27,6]
- [2,16,18,22,**6**,27]
- [2,16,18,**6**,22,27]
- [2,16,**6**,18,22,27]
- [2,**6**,16,18,22,27]

**[22,27,16,2,18,6]** dizisinin zaman karmaşıklıkları;

- Average Case : **Ω(n)**
- Best Case : **O(n2)**
- Worst Case : **O(n2)**

**18** sayısının aranılan sayı olması durumu, average case kapsamına girer. Aranılan sayının ortada olması durumudur.