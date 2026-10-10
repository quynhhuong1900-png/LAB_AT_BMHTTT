LAB 5: Thiết lập và Quản trị Tường lửa pfSense / pfSense Firewall Configuration
Họ và tên: Võ Phan Quỳnh Hương
Lớp: 11_ĐH_TTMT
MSSV: 1150070014
MÔ TẢ MÔI TRƯỜNG THỰC HÀNH (LAB ENVIRONMENT)
Phần mềm ảo hóa: Oracle VM VirtualBox.
Tường lửa chính (pfSense 2.7.2):
WAN Interface: Nhận IP DHCP / Bridged (Kết nối Internet).
LAN Interface: 10.0.0.1/8 (Gateway dải mạng nội bộ LAN).
DMZ Interface: 172.16.0.1/16 (Gateway dải mạng đệm DMZ).
Các máy ảo thành phần:
Domain Controller (DC): Windows Server — IP 10.0.0.2/8, Gateway 10.0.0.1.
LAN-Test Host: Windows/Ubuntu Client — IP 10.0.0.3/8 (hoặc 10.0.0.100), Gateway 10.0.0.1.
DMZ-Web Server: Windows Server (Chạy IIS Web) — IP 172.16.0.2/16 (hoặc 172.16.0.10), Gateway 172.16.0.1
