# **Program Deteksi Serangan Siber pada Nginx Log**


Program ini dibuat untuk memenuhi FP mata kuliah Sistem Keamanan Cerdas, Program ini menggunakana bahasa `python` dengan librari `re` yang dapat mendeteksi serangan File Inclusion Attempt, SQL Injection, Brute Force Attack dan Normal pada log file Nginx Log yang berasal dari PUTI Tel-U Surabaya. 

Data yang dipakai dalam percobaan program file ini adalah data yang dipilah menjadi sekitar 62.000 baris dari tiap log. `old.log` adalah log yang masih berisi url berbahaya, sedangkan `new.log` adalah log yang sudah bersih sekitar 90%. Data akses url untuk full log :
`old.log` : https://telkomuniversityofficial-my.sharepoint.com/:u:/g/personal/rizkyfenaldo_telkomuniversity_ac_id/EcyNiJEV1JdLsqHr1g6Gp2QBf_okPqVebY6mEdt0Av-HJw?e=xA4cGs
`new.log` : https://telkomuniversityofficial-my.sharepoint.com/:u:/g/personal/rizkyfenaldo_telkomuniversity_ac_id/EfFXKXjhCdJHl5sL6VzqfjEB9wKpgq2-dR2t3ZHMcVDhZw?e=0warUs
