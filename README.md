# 🏢 Hệ thống Quản lý Nhà trọ Kiêu Giang

Đây là dự án Luận văn tốt nghiệp chuyên ngành Công nghệ thông tin tại Trường Đại học Công nghệ Sài Gòn. Hệ thống được thiết kế dưới dạng ứng dụng Web nhằm mục tiêu số hóa quy trình quản lý vận hành nội bộ cho nhà trọ, thay thế hoàn toàn việc ghi chép sổ tay và tính toán thủ công hiện tại.

## 🌐 Triển khai thực tế (Live System)

Hệ thống hiện đã được triển khai vận hành thực tế trên máy chủ trực tuyến và đang được cơ sở Nhà trọ Kiêu Giang đưa vào sử dụng chính thức. 
*   **Đường dẫn truy cập**: [https://kg.duyhung.io.vn/](https://kg.duyhung.io.vn/)

*(Lưu ý: Do đây là hệ thống quản lý nội bộ đang vận hành thực tế, việc đăng nhập và truy cập các phân hệ nghiệp vụ sẽ yêu cầu tài khoản được cấp quyền).*
## 🗂️ Cấu trúc dự án (Repositories)

Dự án được áp dụng kiến trúc tách biệt giữa giao diện người dùng (Frontend) và máy chủ xử lý nghiệp vụ (Backend) theo mô hình Client - Server. Mã nguồn được chia thành 2 phần:

*   🖥️ **[Front-end Repository](https://github.com/ngDuyHung/QuanLyTro-Frontend)**: Giao diện người dùng được xây dựng bằng thư viện React kết hợp công nghệ PWA (Progressive Web App) để tối ưu trải nghiệm trên thiết bị di động.
*   Link Front-end: https://github.com/ngDuyHung/QuanLyTro-Frontend 
*   ⚙️ **[Back-end Repository](https://github.com/ngDuyHung/QuanLyTro-Backend)**: Hệ thống RESTful API xử lý nghiệp vụ được xây dựng bằng ngôn ngữ PHP thông qua framework Laravel 12 và hệ quản trị cơ sở dữ liệu MySQL.
*   Link Back-end: https://github.com/ngDuyHung/QuanLyTro-Backend

## 🚀 Các chức năng & Nghiệp vụ nổi bật

*   **Quản lý thông tin lưu trú tập trung**: Lưu trữ toàn bộ hồ sơ khách thuê, quản lý nhân khẩu, hợp đồng và tự động đồng bộ trạng thái phòng (Trống, đang cọc, đang ở).
*   **Ứng dụng Trí tuệ nhân tạo (AI - OCR)**: Tích hợp API AI của Google Gemini để tự động trích xuất thông tin từ ảnh chụp Căn cước công dân và nhận diện chữ số trên đồng hồ điện/nước, giúp giảm thiểu thao tác nhập liệu thủ công.
*   **Đối soát thanh toán tự động (Webhook)**: Tích hợp cổng thanh toán SePay để tự động nhận diện giao dịch biến động số dư từ ngân hàng, tự động gạch nợ hóa đơn dựa trên cú pháp chuyển khoản.
*   **Xác thực thông minh**: Hỗ trợ người dùng đăng nhập và liên kết tài khoản nhanh chóng thông qua Zalo OAuth 2.0.
*   **Tự động hóa sổ sách kế toán**: Tự động tổng hợp doanh thu và hỗ trợ kết xuất báo cáo dưới dạng file PDF theo đúng chuẩn Mẫu Sổ doanh thu (Mẫu S1a-HKD) của Bộ Tài chính dành cho Hộ kinh doanh.

## 🛠️ Công nghệ & Dịch vụ tích hợp

*   **Front-end**: React, PWA, Zustand.
*   **Back-end**: PHP (Laravel 12), MySQL, RESTful API.
*   **Dịch vụ bên thứ 3**: 
    *   Google Gemini API (Vision & OCR Capabilities).
    *   SePay Payment Gateway (Webhook).
    *   Zalo Social API (OAuth 2.0).
    *   Web Push Service (VAPID).

## 👨‍💻 Thông tin tác giả

*   **Sinh viên thực hiện**: Nguyễn Duy Hùng.
*   **Giảng viên hướng dẫn**: ThS. Đinh Thị Tâm.
*   **Đơn vị**: Khoa Công nghệ Thông tin - Trường Đại học Công nghệ Sài Gòn (Năm 2026).
