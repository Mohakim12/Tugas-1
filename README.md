#TUGAS 1 Matakuliah WEBPRO II

##Nama: Mohammad Riswan Nurhakim
##NIM: 17200427

##10 Syntax Git Terpopuler
  1. Git Pull
Digunakan untuk menyatukan kode dari repository pada branch tertentu ke local repository. Psstt.. Kita bisa melakukan pull request pada branch apapun dari branch manapun!

Command: git pull origin <branch>

  2. Git Push
Jika ingin mengunggah kode pada repository git, gunakan command ini. Namun kita hanya bisa melakukan git push pada branch yang sedang kita kunjungi. Sebagai contoh, jika kita berada pada branch A, maka kita tidak bisa melakukan push pada branch B. Solusinya adalah kita diharuskan untuk berpindah branch dengan menggunakan git checkout.

Command: git push origin <branch>

  3. Git Clone
Sebagai developer baru pada repository tertentu, diharuskan untuk melakukan git clone pada repository local. Seperti namanya, fungsi ini dibutuhkan untuk melakukan cloning dari repo git ke repo local. Defaultnya git clone akan cloning default branch yaitu ‘master’. Jika ingin melakukan cloning pada branch tertentu maka tambahkan -b <branch>

Command: git clone <link repo>

  4. Git Merge
Dilakukan untuk menggabungkan kode dari setiap branch yang berbeda pada default branch ‘master’ atau pada branch tertentu. Namun biasanya penulis melakukan merge atau merge request melalui laman git (manual merge)

  5. Git Rebase
Bertujuan untuk menghilangkan commit tertentu tanpa merubah struktur yang sudah dibuat sebelumnya. Biasanya dilakukan jika ada pesan commit yang salah atau tidak diperlukan.

Command: git rebase <branch>

  6. Git Revert
Dikenal sebagai undo pada git, berfungsi untuk membatalkan perubahan pada commit sebelumnya. Biasanya dilakukan ketika terdapat conflict pada kode dan ingin mencari solusi dengan melihat kembali kode yang sudah dilakukan commit.

Command: git revert <id commit>

  7. Git Stash
Berfungsi untuk memudahkan developer untuk ‘melenyapkan’ perubahan kode program, melakukan perubahan lain, dan kembali lagi pada kode yang sebelumnya telah dikerjakan. Fasilitas stashing tidak hanya dapat mengembalikan kode, namun dapat melakukan merging dengan perubahan yang sekarang.

Command: git stash (menyimpan), git stash pop (mengembalikan)

  8. Git Remote
Digunakan untuk menambahkan remote repository pada local folder. Nantinya setelah dilakukan git remote maka seluruh kegiatan pada folder local akan mengarah pada link repo tersebut

Command: git remote add origin <link repo>

9. Git Checkout
Dilakukan jika ingin melakukan perpindahan pada branch tertentu agar kode terlihat independen bergantung pada branch yang dibuat. Selain melakukan perpindahan, kita juga bisa membuat branch baru melalui lokal yang nantinya akan dilakukan push pada laman git dengan menambahkan command -b <branch>

Command: git checkout <branch>

10. Git Branch
Digunakan untuk melihat daftar branch yang sudah ada pada repository. Selain itu command ini juga berfungsi untuk melihat branch mana yang sedang aktif pada lokal repository

Command: git branch -a