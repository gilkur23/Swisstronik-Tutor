# Mint a PERC-20 token

[Link Script](https://github.com/dante4rt/Ramanode-Guides/blob/main/Swisstronik/perc20.sh) \
[Link Gitpod](https://gitpod.io/workspaces) \
[Link Testnet](https://www.swisstronik.com/testnet2/dashboard)


## Step
1. Buat Repo + buat file ```.sh``` didalam (ex:```namafile.sh```)
2. Copy Script by HCA pastekan ke file ```.sh```
3. Buka gitpod login dengan GitHub
4. Buat new workspaces paste link repo + pilih machine bebas




## Jalankan Script
* Beri akses file .sh dan run (ganti ```namafile.sh``` ke sesuai file kalian)
```
chmod +x namafile.sh && ./namafile.sh
```

* Setting agar PK tidak ter push ke github
  - Create a JavaScript project : ENTER 
  - Hardhat project root : ENTER 
  - Do you want to add a .gitignore? : Y 
  - Do you want to install bla bla : Y  

* Enter private key

* Agar lebih aman hapus PK seblum push
```
nano .env
```

* Push File ke GitHub
```
git add . && git commit -m "feat: initiated the project" && git push origin main
```

## Jika Eror saat push ke GitHub Edit Permissions gitpod Ceklis semua
https://gitpod.io/user/integrations





