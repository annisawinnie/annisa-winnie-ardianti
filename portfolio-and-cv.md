1. membuat sebuah folder kosong dengan namamu sendiri. **mkdir annisa-winnie-ardianti**
2. membuat sebuah file dengan nama README.md, isi file tersebut dengan kalimat  
"Halo perkenalkan aku halaman utama". **touch README.md**. **nano README.md**
3. insialisasi folder tersebut dengan Git, kemudian dokumentasikan menggunakan commit dengan pesan "Inisialisasi Git Repository". **git init** **git commit -m "Inisialisasi Git Repository"**
4. buat branch baru dengan nama cv, hal ini berguna agar histori kita tidak tercampur. **git branch cv**
5. pindah branch kedalam cv, kemudian buat file dengan nama cv.txt dan isi file tersebut dengan kalimat:. **git checkout cv** **touch cv.txt** **nano cv.txt** 
"Ini adalah file CV"
6. kemudian dokumentasikan menggunakan commit dengan pesan. **git commit -m "Inisialisasi CV"** **git add cv.txt**
"Inisialisasi CV"
7. tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi menggunakan commit  
. **nano cv.txt** **git add cv.txt** **git commit -m "menambahkan perusahaan pertama"**  
. **nano cv.txt** **git add cv.txt** **git commit -m "menambahkan perusahaan kedua"**
. **nano cv.txt** **git add cv.txt** **git commit -m "menambahkan perusahaan ketiga"**
8. kembali ke branch master. **git checkout master**
9. ubah file README.md menjadi. **nano README.md** **git add README.md**
Halo perkenalkan aku halaman utama
Ini adalah update pertama pada branch master
jangan lupa untuk mendokumentasikannya menggunakan commit dengan pesan. ** git commit -m "update master pertama"**
"update master pertama"
10. gabungkan branch cv kedalam branch master menggunakan perintah git merge. **git merge cv** **git commit -m "Merge branch 'cv'"**
11. unggah Git Repository tersebut kedalam GitHub. **git remote add origin https://github.com/annisawinnie/annisa-winnie-ardianti.git **git push -u origin main**


 
 
 
