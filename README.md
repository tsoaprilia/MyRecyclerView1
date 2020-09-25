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

## Tampilan Card View Mode
Mode Card View ini digunakan untuk menampilkan desain yang diberisi informasi, gambar dan button. CardView berfungsi sebagai wrapper atau frame layout yang akan membungkus layout di dalamnya dengan desain menyerupai kartu. [ Baca Selengkapnya...](https://arifdauhiblog.wordpress.com/2019/06/29/tutorial-membuat-cardview-di-android-studio/)

![WhatsApp Image 2020-09-25 at 20 17 09](https://user-images.githubusercontent.com/60412314/94271698-2de8be00-ff6c-11ea-8ef7-1b4bdd6a3641.jpeg)

## Toast
Toast ini digunakan untuk menampilkan notifikasi berupa teks, yang akan menghilang setelah beberapa waktu.  [ Baca Selengkapnya...](https://medium.com/@lobothijau/membuat-custom-toast-di-android-studio-f04f502f9042)

- List Mode

![WhatsApp Image 2020-09-25 at 18 14 39 (1)](https://user-images.githubusercontent.com/60412314/94272233-fb8b9080-ff6c-11ea-8fda-161dc17a69b6.jpeg)

- Grid Mode

![WhatsApp Image 2020-09-25 at 18 14 39 (2)](https://user-images.githubusercontent.com/60412314/94272298-165e0500-ff6d-11ea-9bc9-d12087421266.jpeg)

-  Card View Mode

![WhatsApp Image 2020-09-25 at 18 14 39 (3)](https://user-images.githubusercontent.com/60412314/94272404-38578780-ff6d-11ea-8d78-a963f91e8b89.jpeg)

![WhatsApp Image 2020-09-25 at 18 14 39 (5)](https://user-images.githubusercontent.com/60412314/94272599-73f25180-ff6d-11ea-8753-6d8b317038b3.jpeg)


## Tampilan Full

Tampilan judul halaman aplikasi akan berbeda di setiap perubahan bentuk RecyclerView.

- List Mode

![WhatsApp Image 2020-09-25 at 21 58 51](https://user-images.githubusercontent.com/60412314/94282708-58417800-ff7a-11ea-9468-fb949aef815d.jpeg)

- Grid Mode

![WhatsApp Image 2020-09-25 at 18 14 39 (7)](https://user-images.githubusercontent.com/60412314/94282182-b883ea00-ff79-11ea-9fc9-da914c1ad3ca.jpeg)

- Card View Mode

![WhatsApp Image 2020-09-25 at 18 14 39](https://user-images.githubusercontent.com/60412314/94271835-638da700-ff6c-11ea-8391-716a22de7071.jpeg)

# Terimakasih :)  
