---
layout: post
title:  "Java dan Android "
date:   2016-11-30 10:00:45 +0200
categories: jekyll update
---

# ALTERATION : Pertemuan 3 - Java dan Android

---
Bahasa Java memiliki definisi bahasa yang berada pada level tingkat tinggi. Penggunaan bahasa Java terdapat pada beberapa perangkat keras seperti Televisi, Handphone, dan alat elektronik lainnya.

Khususnya, Android dari pengembangan versi terawalnya hingga versi paling akhir menggunakan bahasa Java sebagai mesin untuk menjalankan aplikasi.

Untuk dapat menjalankan Android kita membutuhkan :
1. Java Development Kit (JDK) / Open JDK
2. Android SDK (Standard Development Kit)

---

---
Pada tutorial ini, penulis akan menjelaskan berbagai metode yang biasa pada Java biasa lakukan diantaranya:

* Percabangan
* Perulangan
* Array

implementasinya akan dihadirkan pada halaman kerja Android Studio. Untuk dapat mendownload Android Studio dapat mengikuti tautan berikut ini: [Android Studio ](https://developer.android.com/studio/index.html?hl=id "Android Studio")  .

Notes:
> Sesuaikan spec PC Anda dengan Android Studio yang ingin di unduh.

---
Judul : Aplikasi Cek Berat.

Definisi : membuat aplikasi Android untuk mengecek inputan yang berupa nama.

Langkah - langkah sebagai berikut :

* Buatlah project baru dengan mengklik file-> new project

![alt text](https://github.com/jolabti/jolabti.github.io/blob/master/assets/newproject.png "Logo Title Text 1")







* Buat nama project "CekBerat" (tanpa tanda kutip)

* Atur pada file res>layout>activity_main.xml dengan kode sebagai berikut:

```xml

<?xml version="1.0" encoding="utf-8"?>

<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
   xmlns:tools="http://schemas.android.com/tools"
   android:layout_width="match_parent"
   android:layout_height="match_parent"
   android:paddingBottom="@dimen/activity_vertical_margin"
   android:paddingLeft="@dimen/activity_horizontal_margin"
   android:paddingRight="@dimen/activity_horizontal_margin"
   android:paddingTop="@dimen/activity_vertical_margin"

   tools:context="com.apps.alter.cekberat.MainActivity">

   <TextView
       android:layout_width="wrap_content"
       android:layout_height="wrap_content"
       android:text="@string/judul"
       android:textAlignment="center"
       android:textSize="20dp" />

   <EditText
       android:layout_marginTop="35dp"
       android:layout_width="match_parent"
       android:layout_height="wrap_content"
       android:id="@+id/angkaberat"
       android:hint="masukan angka"
       android:textColor="@color/colorAccent"
       android:textSize="12pt"


       />

   <Button
       android:layout_width="match_parent"
       android:layout_height="wrap_content"
       android:paddingLeft="12dp"
       android:layout_marginTop="150dp"
       android:text="Hasil"
       android:id="@+id/button" />



</RelativeLayout>

```

*



2.





---


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
