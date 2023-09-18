# WPFNameList
## Made Nanda Wija Vahindra (5025211160)
### Aplikasi Names
Aplikasi ini sederhananya menyimpan input nama yang diberikan oleh user ke dalam sebuah listbox.  
![image](https://github.com/NandaVahindra/WPFNameList/assets/114988957/d0f33084-ff6a-47d8-aaf0-1e509e8582bc)  
Tampilan Utama aplikasi.  

Kode untuk membuat halaman utama aplikasi
https://github.com/NandaVahindra/WPFNameList/blob/1b91f137e694c5f10db0d37f326ec4fe04c642dd/MainWindow.xaml#L1-L28  
Pada Grid ditambahkan row dan column definition. Kemudian menambahkan elemen-elemen lain seperti listbox, label, stackpane, textbox, dan button.
https://github.com/NandaVahindra/WPFNameList/blob/1b91f137e694c5f10db0d37f326ec4fe04c642dd/MainWindow.xaml#L24  
Pada button ditambahkan action CLick dengan nama ButtonAddName_Click, yang nantinya akan diberikan kode untuk menambahkan nama ke listbox.  
https://github.com/NandaVahindra/WPFNameList/blob/1b91f137e694c5f10db0d37f326ec4fe04c642dd/MainWindow.xaml.cs#L24-L31  
Kode untuk ButtonAddName_Click. Pertama Dicek terlebih dahulu apakah textbox tidak kosong dan nama yang ada di dalam textbox tidak ada di listbox.
Jika kedua syarat terpenuhi maka text yang ada pada textbox di Add ke listbox kemudian textbox di clear.  
Link Blog Dokumentasi : https://nandavahindra.blogspot.com/2023/09/latihan-wpf.html

