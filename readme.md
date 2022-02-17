# Resume Materi Version Control and Branch Management (Git)

## Version Control System (VCS)
Version Control System (VCS) adalah salah satu tool yang digunakan dalam proses mengatur berbagai versi atau melacak perubahan pada source code program. Proses mengatur berbagai versi atau melacak perubahan pada source code program ini disebut dengan Versioning. Terdapat perkembangan tipe Version Control System (VCS), yaitu :
- Single User Version Control System (lokal). Contohnya : SCCS
- Centralized Version Control System (terpusat). Contohnya : CVS
- Distributed Version Control System (terdistribusi). Contohnya : Git

Dengan adanya Version Control System (VCS) dapat melacak dan mengetahui setiap perubahan sehingga kesalahan dapat ditemukan. Contohnya pada saat proses revisi. Hal ini sangat bermanfaat bagi para developer dalam berkolaborasi mengembangkan software.

## Git sebagai Distributed Version Control System
Git adalah Version Control System (VCS) terdistribusi yang dibuat pada tahun 2005 oleh Linus Torvalds. Git terkenal dikalangan developer. Dalam pengembangan software, Git digunakan secara bersama-sama oleh developer. Setiap perubahan yang ada pada file akan dilacak oleh Git. Git didukung dan dapat diinstalasi pada berbagai sistem operasi seperti Windows, Mac, Linux. Proses mengatur server git cukup rumit sehingga diperlukan layanan untuk menjadi server. Layanan yang dapat dipakai untuk menghost proyek Git ialah GitHub.

## Cara Kerja Git pada Layanan GitHub
Kini GitHub menghadirkan fitur sebagai hosting dalam repository Git. Dalam penggunaan suatu Git, hal yang perlu diperhatikan pertama kali yaitu pembuatan repository baru pada GitHub. Setelahnya, kode program local yang telah dibuat dapat diproses menggunakan push ke GitHub dengan cara commit. Kemudian rekan kolaborator lain dapat menggunakan pull guna mendapatkan data dan kode program yang telah tersimpan di repository Git hosting service. Agar proses pembuatan pembuatan kode dapat dipermudah, maka dapat diberlakukan branching pada repository. Pada proses ini, branching memisahkan branch master dan develop kemudian menciptakan branch baru pada setiap fitur yang sedang dikembangkan. Setelah itu merge ke develop akan dilakukan pada setiap fitur jika sudah bekerja secara maksimal. Apabila proses pengembangan telah selesai, maka branch develop akan di merge ke branch master.