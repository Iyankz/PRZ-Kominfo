# RPZ-Kominfo

Sync RPZ Kominfo

1. Lakukan pengisian form data pada link berikut http://bit.ly/FormKoneksiRPZ agar di allow kominfo.
2. Install Debian12 (BookWorm) / Ubuntu 22.04 (jammy Jellyfish)
3. Copy Paste Kode di bawah (Pastikan sudah di privilege root)
##
    wget --no-check-certificate https://raw.githubusercontent.com/Iyankz/RPZ-Kominfo/refs/heads/main/install.sh
##
    chmod +x install.sh
##
    ./install.sh
4. Jika ingin merubah IP mana saja yang di Allow reqest DNS bisa edit file named.conf.optins pada bagian 0.0.0.0/0 (Secara Default Semua IP di allow)
##
    nano /etc/bind/named.conf.options
##
    systemctl restart bind9
