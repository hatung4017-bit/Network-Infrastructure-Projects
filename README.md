# Tích hợp và Bảo mật Hạ tầng Mạng Doanh nghiệp

Dự án mô phỏng quá trình sáp nhập hạ tầng mạng của hai công ty độc lập, tập trung vào việc thiết lập định tuyến liên vùng và tăng cường bảo mật luồng dữ liệu nội bộ.

**Sơ đồ mạng lưới (Topology)**

*(Xóa dòng chữ này và kéo thả file ảnh sơ đồ mạng từ máy tính của bạn vào đây)*

**Kỹ thuật triển khai cốt lõi**

* **Quy hoạch IP:** Thiết kế không gian địa chỉ bằng kỹ thuật VLSM.
* **Định tuyến & Chuyển mạch:** Tái phân phối định tuyến (2-way Route Redistribution) giữa OSPF Area 0 và EIGRP; cấu hình VLAN.
* **Bảo mật:** Thiết lập Access Control Lists (ACLs) để cô lập các dịch vụ trái phép, chỉ cho phép truy cập chéo vào Web Server.
* **Dự phòng:** Cấu hình Site-to-Site VPN làm đường liên kết dự phòng an toàn.

**Thành phần dự án**

* `BaoCao.pdf`: Tài liệu giải thích chi tiết quy hoạch IP và chính sách bảo mật.
* `VLAN_Cde6-2-1-nối-1-1.pkt`: File chạy mô phỏng trên nền tảng Cisco Packet Tracer.
