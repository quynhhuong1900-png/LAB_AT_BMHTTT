Họ và tên: Võ Phan Quỳnh Hương
MSSV: 1150070014
Lớp: 11_ĐH_TTMT
LAB 3: Nhận diện và ứng phó các mối đe dọa đến ATBMTT
Phiên bản môi trường: Hệ điều hành: Windows 11 (64-bit) chạy trên môi trường máy ảo (VMware / VirtualBox), Trình quản trị & Thực thi: Windows PowerShell với quyền Administrator, Giải pháp bảo mật endpoint: Microsoft Defender Antivirus & Windows Defender Firewall (luôn bật bảo vệ thời gian thực - Real-time Protection).
Bộ công cụ bổ trợ: Microsoft Sysinternals (Sysmon, Autoruns, Process Explorer).
Quy trình dựng môi trường: Bước 1 (Khởi tạo thư mục): Mở PowerShell Admin, tạo thư mục gốc C:\LAB3 cùng các thư mục con: Evidence (chứa bằng chứng), Tools (chứa công cụ), Downloads (chứa file tải về) và Assets (chứa tài nguyên lab), Bước 2 (Tải công cụ): Tải và giải nén các công cụ giám sát hệ thống Sysinternals vào C:\LAB3\Tools, Bước 3 (Thu thập Baseline): Xuất các thông tin trạng thái ban đầu của hệ thống (OS, Defender, Firewall, Mạng, Tiến trình) thành các tệp .txt lưu trong C:\LAB3\Evidence để làm cơ sở đối chiếu khi xảy ra sự cố.
