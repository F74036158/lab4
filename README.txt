(A)
average(double *n1,double &2) : 0000000400624 T _Z7averagePdRd
average(int n1,float n2) : 0000000000400652 T _Z7averageif
(B)
output:
18
48
48
88
explain:
output的數字表示各個type所佔用的記憶體空間，
18的1指的是char佔1byte
兩個48的4分別指的是int和float佔4bytes
88的第一個8指的是double佔8bytes 
第二行數字都是8，是因為point是記憶體位址，大小都會一樣，如此才能定位所有位址。
顯示8是因為作業系統是64bit(8bytes),如果是32bit，結果會是4。
