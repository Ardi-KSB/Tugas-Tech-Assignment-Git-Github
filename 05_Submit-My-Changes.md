1. Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu. https://drive.google.com/drive/folders/1ut5nHxUb71PnKs5VcMzy6gosVtA-bhJj?usp=sharing
2. Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya. $ git clone https://github.com/Ardi-KSB/tech4impact-students-bio.git --single-branch
<!--Buat Folder Baru untuk memasukkan hasil cloning, buka folder tersebut dengan Gitbash--> $ git add . $ git status $ git commit -m "..."
3. Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master. $ git branch Mohammad-Sunardi
4. Checkout ke dalam branch tersebut yang telah kamu buat. $ git checkout Mohammad-Sunardi $ git status
5. Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md . $ touch Mohammad-Sunardi.md
6. Isi file tersebut davidwinalda.md dengan konten di bawah ini:
Nama Lengkap: David Winalda
Umur: 27
Pesan yang ingin disampaikan: Semangat untuk kamu yang disana sedang berjuang. https://drive.google.com/drive/folders/1ZYNG29FrY-GiUy4IZ0KfXPxtH5gfFLQL?usp=sharing
7. Masukkan file .md tersebut ke dalam staging area. $ git add Mohammad-Sunardi.md
8. Commit dengan memberikan pesan nama file .md kamu. $ git commit -m "Mohammad-Sunardi"
9. Merge branch yang telah kamu buat ke dalam branch master. $ git checkout master $ git merge Mohammad-Sunardi
10. Push ke dalam branch master. $ git status $ git add . $ git checkout Mohammad-Sunardi $ git push origin master
11. Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch master pada GitHub Repository aslinya. https://drive.google.com/drive/folders/1rmF-qUBOrt532JpvRUPu8iB3-nCe19CV?usp=sharing