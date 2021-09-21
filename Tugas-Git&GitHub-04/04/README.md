1. What is the difference between git reset and git revert. When would you use one over the other?
Jawaban :
** - Git Revert
menciptakan komit baru yang membatalkan perubahan dari komit sebelumnya. Perintah ini menambahkan sejarah baru ke proyek (itu tidak mengubah sejarah yang ada).
Jika komit telah dibuat di suatu tempat dalam sejarah proyek, dan Anda kemudian memutuskan bahwa komit itu salah dan seharusnya tidak dilakukan, maka git revert adalah alat untuk pekerjaan itu. Ini akan membatalkan perubahan yang dilakukan oleh komit buruk, merekam "undo" di riwayat.

- Git Reset
melakukan beberapa hal yang berbeda tergantung pada bagaimana ia dipanggil. Ini memodifikasi indeks (yang disebut "area pementasan"). Atau perubahan yang dilakukan oleh kepala cabang saat ini mengarah ke. Perintah ini dapat mengubah riwayat yang ada (dengan mengubah komit yang direferensikan cabang).
Jika Anda telah membuat komit, tetapi belum membagikannya dengan orang lain dan Anda memutuskan tidak menginginkannya, maka Anda dapat menggunakan git reset untuk menulis ulang sejarah sehingga seolah-olah Anda tidak pernah membuat komit itu**

2. What is the difference between git merge and git rebase. When would you use one over the other?
**bisa,karena saya harus benar-benar rebase kembali ke komit sebelum salah satu yang anda ingin memodifikasi**

3. What is the difference between git stash pop and git stash apply. When would you use one over the other?
**Perbedaan apply dengan pop adalah jika kamu menggunakan apply, stash yang baru saja di-restore ke sumber tidak akan dihapus dari stack, sementara stash akan hilang jika kamu menggunakan perintah pop**

4. What kinds of things can you do in interactive mode when rebasing?
**Rebasing interaktif dapat digunakan untuk mengubah komit dalam banyak cara seperti mengedit, menghapus, dan squashing . Untuk memberi tahu Git tempat memulai rebase interaktif, gunakan SHA-1 atau indeks komit yang segera mendahului komit yang ingin Anda modifikasi**
