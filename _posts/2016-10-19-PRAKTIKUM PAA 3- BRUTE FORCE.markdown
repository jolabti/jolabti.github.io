---
layout: post
title:  "MATERI PAA - 3 : Algoritma Bruteforce"
date:   2016-10-19 11:49:45 +0200
categories: jekyll update


---
### MATERI PERTEMUAN 3 - PAA : ALGROITMA BRUTEFORCE

Definisi dari Algoritma Brutefore adalah sebuah metode pencarian yang lempang (_straightfoward_) yang mana memiliki cara kerja untuk mencari solusi hingga tuntas pada proses pencariannya.

Penggunaan Algoritma Bruteforce terdapat pada _pencarian string_ , _pemecahan kombinasi password_ , serta pada Metode ( _ Traveling Salesman Problem _ ) yang berkeenaan dengan jarak tempuh efisien.

---
Pada pertemuan sesi ini , praktikum menggunakan bahasa C++ untuk membuat contoh dasar mengenai operasi string untuk menemukan jumlah sebuah karakter masukkan terhadap total dari jumlah keseluruhan data karakter yang tersedia.



```c++
#include <iostream>

// #include <stdio>

using namespace std;

char inputanChecker [1000];
int penghitung =0;
string detected;

int main(){

		cout << "Program Checker Untuk Test Karakter dan Jumlahnya \n";
		cout <<"===================================================== \n";
		cout <<"\n";
		cout <<"\n";
		string sourceData= "908g0dojdkfdkjldsjfnvdkjncsjvfkgjrlqkjaldkjaldkalaaasklfjdlgjdlgj";

		cout <<"Masukkan (sebuah saja) karakter untuk diperiksa jumlahnya \n";
		cout <<"============================================================\n";
		cin >> inputanChecker;
		for (int i = 0 ; i< sourceData.size() ;i++){

				if (sourceData[i]==inputanChecker[0]){
					penghitung+=1;
				}
				else if (sourceData[i]==inputanChecker[i]){
					detected = sourceData[i];
				}
		}
		cout << " Total Karakter yang dihasilkan adalah .... \n";
		cout << "Detected character adalah ...." << detected;
		cout << penghitung;

}
```

Outputnya adalah :

![alt text](/assets/output.png )

> Untuk Pertanyaan Lebih Lanjut :
> johandata@yahoo.com

---

3IA05
========
---
Buatlah laporan akhir seperti kondisi di bawah ini :.

Deretan sumberdata : 100101010010111 __1010101__ 0001

Kombinasi yang harus dicari : __1010101__

Buatlah program dalam bahasa C++ untuk menemukan solusi berapa jumlah kombinasi yang harus di cari dalam sekumpulan deretan sumber data dan konvert kombinasi tersebut ke dalam _desimal_ !

---

3IA11
========
---
Buatlah laporan akhir seperti kondisi di bawah ini :.

Deretan sumberdata : 100101010 __010111101__ 01010001

Kombinasi yang harus dicari : __010111101__

Buatlah program dalam bahasa C++ untuk menemukan solusi berapa jumlah kombinasi yang harus di cari dalam sekumpulan deretan sumber data dan konvert kombinasi tersebut ke dalam _hexa_ !

---



3IA13
========
---
Buatlah laporan akhir seperti kondisi di bawah ini :.

Deretan sumberdata : 100001101010010101010000101010101010

Kombinasi yang harus dicari : 101 dan 100

Buatlah program dalam bahasa C++ untuk menemukan solusi berapa jumlah kombinasi yang harus di cari dalam sekumpulan deretan sumber data dan konvert kombinasi tersebut ke dalam _desimal_ !

---







<!--
Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->
