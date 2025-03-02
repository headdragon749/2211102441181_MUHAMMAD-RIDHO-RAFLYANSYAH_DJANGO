"# NEW_django Project" 

project ini ada langkah awal dalam membuat sebuah project dengan membuat framework django
tahap - tahapan:
1. instalisasi python gunakan versi terbaru yang available
2. pembuatan Venv (virtual Envirotment)
   2.1 pemilihan tempat Venv. misal: "C:\Users\AXIOO\OneDrive\Desktop\NEW_django"
   2.2 membuat Venv ("py -m venv myVenv")
   2.3 mengaktifkan atau menggunakan Venv ("myVenv\scripts\activate")
       jika berhasil akan seperti ini: "(myVenv) C:\Users\AXIOO\OneDrive\Desktop\NEW_django>"
3. instalisasi django ("pip install django")
4. pastikan django sudah terinstal ("pip list")
5. membuat project  ("django-admin startproject myproject")
6. lalu pastikan project sudah terbuat ("dir")
7. masuk kedalam direktori "myproject" (">cd myproject")
8. membuat migrasi pada project ("py manage.py migrate")
9. membuat user dan password ("py manage.py createsuperuser")
10. menjalankan project ("py manage.py runserver")

lalu ada pula cara mengupload project yang sudah kita buat ke git hub
berikut adalah tahap - tahapannya :
1. pastika sudah membuat dan login akun git hub
2. masuk keberanda git hub klik "create a new repository"
3. masukkan nama repository sesuai foemat yang sudah di tentukakkn
4. pilih public accses
5. lalu buat repository
6. buka cmd masuk kedalam alamat folder project kalian misal:" (myVenv)C:\Users\AXIOO\OneDrive\Desktop\NEW_django>"
7. ikuti perintah yang ada di github
   7.1 add README.md
   7.2 add . ("tambahan untuk mengupload semua file dan folder yang ada")
   7.3 git commit -m "first commit"
   7.4 git branch -M main
   7.5 git remote add origin https://github.com/headdragon749/2211102441181_MUHAMMAD-RIDHO-RAFLYANSYAH_DJANGO.git
   7.6 git push -u origin main
   7.7 git add .gitignore ("pastikan file gitignore ada di dalam folder")
lalu masuk keling yang mucul dan masukkan username dan password yang sudah di buat
