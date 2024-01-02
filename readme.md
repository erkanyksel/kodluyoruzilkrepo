[22,27,16,2,18,6] -> Insertion Sort

2,27,16,22,18,6
2,6,16,22,18,27
2,6,16,22,18,27
2,6,16,18,22,27


Average Case

[7,3,5,8,2,9,4,15,6]

2,3,5,8,7,9,4,15,6
2,3,5,8,7,9,4,15,6
2,3,4,8,7,9,5,15,6
2,3,4,5,7,9,8,15,6


Merge Sort

Sol parça: [16, 21, 11]
Sağ parça: [8, 12, 22]

Sol parça: [16, 21, 11]
    Sol parça: [16]
    Sağ parça: [21, 11]
        Sol parça: [21]
        Sağ parça: [11]
    Merge: [11, 21]

Sağ parça: [8, 12, 22]
    Sol parça: [8]
    Sağ parça: [12, 22]
        Sol parça: [12]
        Sağ parça: [22]
    Merge: [12, 22]

Merge: [11, 16, 21] ve [8, 12, 22]

Merge: [8, 11, 12, 16, 21, 22]


toplam zaman karmaşıklığı O(n log n) 

