#patika.dev veribilimi Insertion Sort proje

[22,27,16,2,18,6] -- Insertion sort

^Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1-[2,27,16,22,18,6]
2 en önde geldi.

2-[2,6,16,22,18,27]
6, 2. sıraya geldi.

3-[2,6,16,18,22,27]
18 ile 22 yer değiştirdi ve sorting tamamlandı.

^Big-O gösterimini yazınız.

Dominant faktör - n
[22,27,16,2,18,6] -- O(n)

^Time Complexity

Worst case: O(n)
Average case: O(n/2) dominant faktör n
Best case: 1

^Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average case kapsamındadır.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1-[2,3,5,8,7,9,4,15,6]
2-[2,3,4,8,7,9,5,15,6]
3-[2,3,4,5,7,9,8,15,6]
4-[2,3,4,5,6,9,8,15,7]