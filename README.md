# stl
install 
opkg update && opkg install unzip
opkg install openvpn-openssl && opkg install ip-full && opkg install openssh-client && opkg install stunnel && opkg install *.ipk && opkg install lsof && opkg install fping screen
wget --no-check-certificate "https://raw.githubusercontent.com/idtunnel/STL-OpenWRT/main/stl/install.sh" -O ~/install.sh && chmod 777 ~/install.sh && ~/./install.sh

# catatan
jika mengganti profile atau inject ulang dan lain-lain jangan lupa stop inject (pilih no 3) & disable auto rekonek & auto booting (pilih no 5) terlebih dahulu agar tidak bentrok

untuk lebih lengkap bisa baca di https://www.idtunnel.com/install-tunnel-stl-di-openwrt/

