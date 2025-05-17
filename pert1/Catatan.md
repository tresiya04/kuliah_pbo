# untuk membuat folder dengan nama perkuliahan
'''php
cd /root
mkdir kuliah_pbo && cd kuliah_ (Buat folder baru bernama kuliah_pbo lalu masuk ke dalamnya)
touch .gitignore && git init(touch .gitignore && git init)
git add . && git branch -M (Perintah ini gagal karena git branch -M butuh nama branch baru (misalnya: main))
git commit -m "kuliah_pbo" (Menyimpan perubahan dengan pesan "kuliah_pbo")
git config --global --edit(Git kasih tahu bahwa nama & email kamu belum diatur. Bisa diatur pakai:)
git remote add origin git@github.com:tresiya04/kuliah-pbo.git(Menghubungkan repository lokal ke repository GitHub (alamat git@github.com:... adalah alamat GitHub kamu))
git push -u origin main(Mengunggah proyek ke GitHub di branch main)







