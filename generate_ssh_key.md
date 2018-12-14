#### Membuat Generate Key SSH di Windows ####

1. Buka Git Bash anda.
2. copas text ini dan ganti sesuai dengan email github anda
   - ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
3. selanjutnya enter saja.
   - ssh key akan di simpan ke directory ini (/c/Users/you/.ssh/id_rsa):[Press enter]
4. Uji konektivitas dengan ini ssh -T git@github.com