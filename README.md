# 🛡️ BÀI THỰC HÀNH SỐ 01: LẬP TRÌNH CƠ BẢN VỚI PYTHON
> **Môn học:** Lập Trình An Toàn Thông Tin  
> **Sinh viên thực hiện:** Nguyễn Phi Phúc  
> **Mã số sinh viên (MSSV):** 2387701131  
> **Repository:** [B4_LTANTT_LAB01_NGUYENPHIPHUC_2387701131](https://github.com/nguyenphiphuc/B4_LTANTT_LAB01_NGUYENPHIPHUC_2387701131)

---

## 📌 Giới thiệu dự án
Repository này lưu trữ toàn bộ mã nguồn bài thực hành **Lab 01: Lập trình cơ bản với ngôn ngữ Python**, bao gồm:
* **Phần 1.1: Cài đặt môi trường & Ví dụ khởi động** (`ex01`)
* **Phần 1.2: Lập trình Python cơ bản** (`ex02`)
* **Phần 1.3: Cấu trúc dữ liệu List, Tuple, Dictionary** (`ex03`)
* **Phần 1.4: Lập trình hướng đối tượng (OOP)** (`ex04`)

---

## 🗂️ Cấu trúc thư mục (Project Structure)

```text
NguyenPhiPhuc_2387701131_Source/
│
├── ex01/                           # Phần 1.1: Khởi động chương trình Python đầu tiên
│   └── ex01_01.py (hoặc hello.py)  # In lời chào mừng "Hello, World!" và thông tin cá nhân
│
├── ex02/                           # Phần 1.2: Lập trình Python cơ bản (Câu 01 - Câu 10)
│   ├── ex02_01.py                  # Câu 01: Nhập họ tên, tuổi và in lời chào
│   ├── ex02_02.py                  # Câu 02: Tính diện tích hình tròn với bán kính r
│   ├── ex02_03.py                  # Câu 03: Kiểm tra một số là số chẵn hay số lẻ
│   ├── ex02_04.py                  # Câu 04: Tìm số chia hết cho 7 nhưng không là bội của 5 [2000, 3200]
│   ├── ex02_05.py                  # Câu 05: Tính lương thực lĩnh nhân viên (tính giờ làm thêm 150%)
│   ├── ex02_06.py                  # Câu 06: Tạo mảng 2 chiều X x Y với giá trị phần tử i * j
│   ├── ex02_07.py                  # Câu 07: Nhập nhiều dòng văn bản và chuyển đổi thành chữ in hoa
│   ├── ex02_08.py                  # Câu 08: Lọc các số nhị phân 4 chữ số chia hết cho 5
│   ├── ex02_09.py                  # Câu 09: Hàm kiểm tra số nguyên tố
│   └── ex02_10.py                  # Câu 10: Hàm đảo ngược chuỗi
│
├── ex03/                           # Phần 1.3: Thao tác List, Tuple, Dictionary (Câu 01 - Câu 06)
│   ├── ex03_01.py                  # Câu 01: Tính tổng các số chẵn trong một List
│   ├── ex03_02.py                  # Câu 02: Đảo ngược thứ tự các phần tử trong danh sách
│   ├── ex03_03.py                  # Câu 03: Tạo Tuple từ một List nhập từ bàn phím
│   ├── ex03_04.py                  # Câu 04: Truy cập phần tử đầu tiên và cuối cùng trong Tuple
│   ├── ex03_05.py                  # Câu 05: Đếm tần suất xuất hiện các từ và lưu vào Dictionary
│   └── ex03_06.py                  # Câu 06: Xóa phần tử khỏi Dictionary theo khóa (Key)
│
├── ex04/                           # Phần 1.4: Lập trình hướng đối tượng OOP
│   ├── SinhVien.py                 # Khai báo lớp SinhVien với các thuộc tính và xếp loại
│   ├── QuanLySinhVien.py           # Lớp nghiệp vụ quản lý (Thêm, sửa, xóa, tìm kiếm, sắp xếp)
│   └── Main.py                     # Chương trình chính với Menu điều hướng tương tác
│
└── README.md                       # Tài liệu hướng dẫn và mô tả dự án