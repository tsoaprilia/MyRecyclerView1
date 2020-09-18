# RecyclerView
RecyclerView adalah sebuah komponen tampilan (widget) yang lebih canggih ketimbang pendahulunya listview. RecyclerView bersifat lebih fleksibel. RecyclerView memiliki kemampuan untuk menampilkan data secara efisien dalam jumlah yang besar. Terlebih jika memiliki koleksi data dengan elemen yang mampu berubah-ubah sewaktu dijalankan (runtime). [ Baca Selengkapnya...](https://developer.android.com/guide/topics/ui/layout/recyclerview?hl=id#structure)

# Komponen yang terdapat dalam RecyclerView
1. RecyclerView dan LayoutManager: Komponen yang digunakan untuk menampilkan data set yang dimiliki di dalamnya. Layout manager mengatur posisi tampilan data secara list, grid atau staggered grid.
2. Adapter: Komponen yang akan mengatur bagaimana menampilkan data set ke dalam RecyclerView. 
3. Dataset: Kumpulan data yang dimiliki dan ingin ditampilkan. 
4. Item Animator:  Komponene yang digunkaan untuk memasang animasi untuk tiap item di dalamnya. 


# Langkah-langkah mengimplementasikan recyclerview :
1. Tambahkan dependencies komponen recyclerview pada file build.gradle  level modul.
2. Tambahkan obyek RecyclerView di berkas layout xml dari activity / fragment.
3. Definisikan model kelas (POJO) yang akan digunakan sebagai data source.
4. Buat berkas layout xml untuk baris item di RecyclerView.
5. Buat sebuah kelas adapter yang inherit ke RecyclerView.Adapter dan ViewHolder untuk menampilkan tiap elemen data.
6. Definisikan obyek RecyclerView berikut dengan bentuk yang diinginkan (bisa dalam bentuk list, grid, atau staggered) dan selanjutnya pasang obyek adapter (binding) agar bisa menampilkan koleksi data ke dalam RecyclerView. 





## Tampilan List Mode
Mode List ini digunakan untuk menampilkan data atau nilai dalam bentuk daftar/list, nilai atau data yang ditampilkan tersebut didapat dari sebuah Array atau Database yang sudah ditentukan. [ Baca Selengkapnya...](https://medium.com/@axella.gerald/tutorial-menampilkan-list-pada-aplikasi-android-44abda6c574d)

![Aa](https://user-images.githubusercontent.com/60412314/93603393-27979680-f9ee-11ea-90cb-dccdeae72bf9.jpg)


## Menu
Menu ini digunakan untuk berpindah ke Mode Lain. Seperti Berpindah dari List mode ke Grid Mode. Menu adalah komponen antarmuka pengguna yang lazim dalam banyak tipe aplikasi. [ Baca Selengkapnya...](https://developer.android.com/guide/topics/ui/menus?hl=id)

![cc](https://user-images.githubusercontent.com/60412314/93604100-22871700-f9ef-11ea-80b1-75a0d90f9b60.jpg)

## Tampilan Grid Mode
Mode Grid ini digunakan untuk menampilkan konten View, konten View tersebut akan tersusun berbentuk kotak .Semua item secara otomatis masuk ke layout menggunakan ListAdapter. [ Baca Selengkapnya...](https://www.androidrion.com/tutorial-gridview-android-studio/)

![bb](https://user-images.githubusercontent.com/60412314/93605070-79412080-f9f0-11ea-9363-ed52f4c1b6da.jpg)

# Terimakasih :)  
