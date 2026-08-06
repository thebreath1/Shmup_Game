## Prompt pembuatan game shmup ##

*Prompt pertama*
Karena game-nya untuk tugas sekolah, aku pengen kamu buatin game ini berdasarkan UI yang diatas sebagai inti game-nya, dimana sebelum main, ada tulisan "Tap the keyboard to play" dengan tema-tema arcade gitu, kayak "Insert Coin" di game arcade. Di dalam game-nya, ada 5 level yang berbeda nantinya, masing-masing ada 2 wave dengan total kapal kira-kira ada 12, dengan total 3 kapal muncul 4 kali dalam satu wave dan jeda sekitar 2 detik setelah 3 kapal pertama muncul dan sudah hancur. Jeda per-wave kira-kira 5 detik dengan tambahan teks "Second wave" didepan layar. Ketika level naik, kalau bisa pergerakan musuh jadi semakin sulit untuk dibaca sehingga ada tantangan tersendiri untuk pemain, seru juga kalau pola nembaknya random dari yang tadinya predictable. Kalo bisa, ada 5% kemungkinan peluru yang ditembak musuh itu memantul pas nabrak box permainannya kalo udah level 3 atau 4, memantul untuk 3 kali pantulan. Nyawa bakal +1 setiap naik level jika nyawa pemain < 3. Jika user berhasil selamat sampai level 5 dan menamatkan game-nya, bakal muncul screen khusus "Congratulations!" dan kembali ke tap screen. Untuk bar "Ultimate", itu berjumlah 100% dan bakal terakumulasi 25% setiap pemain menghancurkan satu pesawat musuh. Skill Ultimate yang diperoleh adalah tembakan area yang lebih lebar dari dari tembakan normal dan mungkin saja hampir memakan seluruh box permainan dengan syarat si pesawat pemain harus membesar 2x lipat dari sebelumnya. Skill Ultimate harus ditrigger dengan menekan keyboard U. Untuk nyawa pemain, setiap terkena tembakan bakal mengurangi satu nyawa, sementara untuk musuh, jika mereka tertembak dua kali, maka pesawat mereka akan hancur. Pergerakan user bisa menggunakan arrow ataupun tombol WASD, dengan tembak menggunakan spasi. Hanya menggunakan HTML, CSS, dan JavaScript. Bisa?

*Prompt kedua(revisi)*
OH, aku pengen mengajukan revisi, dong;

1. Setelah Second Wave berakhir disetiap level, ada boss fight, dimana pesawatnya itu dua kali lebih besar dari yang biasa, dan setiap boss itu memiliki skill yang unik. Contoh, sapuan yang bisa mengurang -25 HP pemain. Untuk tembakan boss biasa hanya mengurangi 10 HP pemain saja.
2. Tambahkan pause in-game
3. Setiap naik level, ketahanan musuh semakin tinggi ditambah satu, misal di level 1 butuh dua hit untuk menghancurkan musuh, di level 2 butuh 3, dan seterusnya. Tembakan musuh biasa hanya akan mengurangi darah pemain sebanyak 5.
4. Ada batas peluru pemain berjumlah 15, jika kosong akan reload selama 2 detik dengan indikator bar seperti ultimate.
5. Jumlah pesawat musuh setiap naik level akan bertambah sebanyak satu.
6. Kemungkinan peluru pantulan yang tadinya 5% jadi 15% kemunculannya dan juga akan menghilang ketika bola sudah memantul 5 kali.
7. Love akan diubah menjadi HP sebanyak 100%, HP akan direset sebanyak 50% disetiap level.
8. Dalam satu wave, yang tadinya hanya ada 3 X 4 pesawat menjadi 5 X 4 pesawat dalam satu wave.
9. Intensitas permainan seiring naiknya level akan semakin tinggi.
10. Insert Coin-nya hilangkan
11. Skill Ultimate yang semula hanya membutuhkan 4 kill untuk mengaktifkannya sekarang harus mendapat 10 kill untuk dapat mengaktifkan Ultimate.
12. Ada indikator bar musuh ditengah setiap badan pesawat mereka.
13. Boss memiliki HP 100%, pemain memiliki damage -10 ke arah boss dilevel 1 dan akan berkurang damage-nya sebanyak 1 setiap level bernaik, contoh : level 1 = 10 -> level 2 = 9, dan seterusnya.
14. Ketika menghadapi boss, ultimate akan di reset ke 0% dan setiap tembakan satu tembakan akan memulihkan bar ultimate sebanyak 10%.
15. Pergerakan boss akan lebih dinamis daripada pesawat musuh, meski di level satu sekalipun. Meningkat setiap naik level.

Segitu saja permintaan revisinya.

*Prompt ketiga(revisi kedua)*
Permintaan revisi lagi:

1. Ketika kita berhasil menghancurkan pesawat, ada kemungkinan sebesar 50% kita akan mendapatkan buff yang jatuh kearah kita. Buff ini berupa-rupa, bisa penambahan HP, penambahan kapasitas menembak menjadi 3 peluru dalam satu klik dan menyebar, dan apapun itu.
2. Buatkan leaderboard pada game ini juga, dengan syarat setelah user mengklik TAP THE KEYBOARD TO PLAY, akan ada form nama sederhana dengan max nama terdiri dari 5 huruf.
3. Second Wave sebaiknya dihapus, jadi setelah first wave selesai, langsung menghadapi boss.
4. Skill boss sebaiknya dimulai lebih mudah di level 1 dan akan semakin sulit dan berbahaya seiring naiknya level.