# praktikumm-25-565484

## Deskripsi
Project ini merupakan praktikum Git yang mencakup penggunaan commit, branching, merge, dan rebase.

## Cara Menjalankan
1. Clone repository
2. Buka file index.html di browser

## Tugas 1
Dilakukan pembuatan repository dan beberapa commit menggunakan Conventional Commits. Melakukan minimal 5 commit menggunakan Conventional Commits:
- feat: menambahkan halaman utama
- style: memperbaiki tampilan
- fix: memperbaiki bug
- chore: menambahkan .gitignore

## Git Log
![Git Log](gitlog.png)
Commit History: 
![Commit](commit.png)

## Tugas 2 
Membuat branch feature/navbar, feature/footer, dan hotfix/typo, lalu membuat Pull Request dan merge ke main. Merge dilakukan dengan: 
- Squash and merge untuk feature
- Merge commit untuk hotfix

1. Feature Navbar  
![PR Navbar](Pullrequest1.png)

2. Feature Footer  
![PR Footer](PR2.png)

3. Hotfix Typo  
![PR Typo](PR3.png)


Menerapkan Branch protection rule untuk mencegah push langsung ke main.

## Branch Protection
![Branch Protection](protectionn.png)

## Tugas 3
- experiment/color-A
- experiment/color-B
Konflik terjadi karena kedua branch mengubah bagian CSS yang sama.

1. Konflik: 
Konflik diselesaikan secara manual di VS Code dengan memilih perubahan yang sesuai. 
![konflik](konflikk.png)

2. Menyelesaikan Konflik
Konflik terjadi karena dua branch mengubah bagian CSS yang sama. Konflik diselesaikan dengan memilih perubahan yang sesuai. 
![Resolving](kodebersih.png)

Dilakukan interactive rebase untuk menggabungkan beberapa commit menjadi satu commit agar riwayat lebih rapi.
3. Sebelum rebase: 
![Rebase](bfrrebase.png)

4. Hasil Akhir:
![last](hasil3.png)

## Tugas 4 
1. Dibuat minimal 3 issues: 
![Issue](Issue.png)

2. Menutup Issue menggunakan PR:
![CloseIssue](ClosePR.png)

## Collaborator
Menambahkan collaborator pada repository. 
![Collaboration](addcollaboration.png)


### Release
Membuat release versi v1.0.0.
![Release](createrelease.png)

Hasil release: 
![ResultRelease](releaseResult.png)




## Dokumentasi Git Command
- git clone → mengambil repository
- git add → menambahkan perubahan
- git push → mengirim perubahan ke GitHub
- git pull → mengambil update terbaru dari repository
- git commit → menyimpan perubahan
- git branch → membuat branch
- git merge → menggabungkan branch
- git rebase → merapikan commit