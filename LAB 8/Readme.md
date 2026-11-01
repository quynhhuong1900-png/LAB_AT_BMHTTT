LAB 8:
Vo Phan Quynh Huong_11_DH_TTMT_1150070014
Môi trường bài lab gồm 3 máy ảo kết nối qua mạng nội bộ cô lập VirtualBox dns-lab (dải IP 10.9.0.0/24):
DNS Server (WEB-PROXY): IP 10.9.0.10 (chạy dịch vụ BIND9, UDP/TCP port 53).
Victim (Metasploitable2): IP 10.9.0.100 (máy nạn nhân, trỏ DNS về 10.9.0.10).
Attacker (Kali Linux): IP 10.9.0.200 (máy tấn công, chạy script Scapy nghe lén trên eth0, mở Web Server giả mạo port 80, cấu hình Promiscuous Mode = Allow VMs/Allow All).
