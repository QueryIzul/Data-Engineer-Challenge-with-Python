Data Engineer Challenge with Python

Project Kerjasama DQLab dengan CT Corp
CT Corp adalah konglomerat konsumen terbesar dan berkembang pesat di Indonesia dengan bisnis utama di perbankan, jasa keuangan, media, gaya hidup, hiburan, sumber daya alam, dan F&B. CT Corp telah mendirikan perusahaan yang kuat di pasar konsumen seperti: Bank Mega, Bank Mega Syariah, Mega Life, DetikNetwork, TRANSMEDIA (Trans TV, Trans 7, TV CNN Indonesia, CNNIndonesia.com, CNBC TV, (CNBCIndonesia.com), Trans Fashion, Transmart (Carrefour), and F&B (Baskin Robins, Coffee Bean, Wendy’s).

Apa saja yang dibahas dalam project ini?
Project ini berupa tes untuk melihat kemampuan kamu dalam mulai berkarir menjadi Data Engineer. Tes ini terdiri atas 2 (dua) bagian, yaitu: 

Web Scraping, yang dirancang untuk memperlihatkan kemampuan member dalam mengambil data dari website dalam bentuk data HTML
Function and Regular Expression, yang dirancang untuk memperlihatkan pengetahuan member terkait dasar-dasar pembuatan sebuah function dan penggunaan Regular Expression dalam bahasa pemrograman Python.

Data Engineer Coding Challenge

Web Scraping

Sebagai seorang Data Engineer, Anda diminta untuk menggali informasi dari https://id.wikipedia.org/wiki/Demografi_Indonesia menggunakan bahasa pemrograman Python. 

Buatlah suatu script Python untuk menyimpan tabel "Jumlah Penduduk menurut Provinsi" dari web tersebut dengan format CSV.

File CSV menggunakan format double-apostrophe quoting ('...') dan disimpan dengan nama 'Indonesia_Demography_by_Province.csv'.

Kolom yang perlu Anda ambil adalah sebagai berikut.

Nama provinsi 
Luas (km2)
Populasi (2010)
Populasi (2020)
Dataframe yang akan kamu buat diassign dengan nama variabel df.

Function and Regular Expression
Sebagai seorang Data Engineer, Anda diminta untuk membuat suatu fungsi yang bernama “email_check” untuk menyaring beberapa email menggunakan regular expression dalam bahasa pemrograman Python. Fungsi ini akan menerima suatu parameter yang bernama “input” yang mana merupakan email dan output-nya akan berupa “Pass” atau “Not Pass”. Fungsinya harus memenuhi pola berikut :

Pola	Pass / Not Pass
my-name@someemail.com

Not Pass

myname@someemail.com

Pass

my.name@someemail.com

Pass

my.name2019@someemail.com

Pass

my.name.2019@someemail.com

Not Pass

somename.201903@someemail.com

Not Pass

my_name.201903@someemail.com

Pass

201903myname@someemail.com

Not Pass

201903.myname@someemail.com

Not Pass

