# Pham Phi Khanh - Personal Portfolio

[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-222222.svg?logo=githubpages&logoColor=white)](https://phihanh-qg.github.io/portfolio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Website hồ sơ năng lực cá nhân (Personal Portfolio) của **Phạm Phi Khanh**. Dự án tổng hợp thông tin cá nhân, định hướng nghề nghiệp, kế hoạch phát triển bản thân (PDP), các thành tích học tập và hồ sơ năng lực (CV/Resume).

Trang web trực tuyến (Live Preview): **[https://phihanh-qg.github.io/portfolio/](https://phihanh-qg.github.io/portfolio/)**

---

## Cấu Trúc Website

Website được tổ chức dưới dạng trang web tĩnh đa trang (Multi-Page Static Site), bao gồm các phân hệ nội dung:

| Tệp Nguồn | Trang Hiển Thị | Nội Dung Chính |
| :--- | :--- | :--- |
| `index.html` | Trang Chủ (Home) | Giới thiệu tổng quan, thông điệp cá nhân và điều hướng chính |
| `about.html` | Giới Thiệu (About Me) | Chi tiết thông tin bản thân, thế mạnh và tính cách (MBTI) |
| `education.html` | Học Vấn (Education) | Quá trình đào tạo, chuyên ngành và kết quả học tập |
| `achievements.html` | Thành Tích (Achievements) | Danh sách giải thưởng, thành tích học thuật và chứng nhận |
| `pdp.html` | Kế Hoạch Bản Thân (PDP) | Personal Development Plan: Mục tiêu ngắn hạn, trung hạn, dài hạn |
| `roadmap.html` | Lộ Trình (Roadmap) | Lộ trình tích lũy kiến thức chuyên môn và kỹ năng thực tế |
| `teamwork.html` | Làm Việc Nhóm (Teamwork) | Trải nghiệm dự án nhóm, phương pháp phối hợp và bài học rút ra |
| `self-eval.html` | Tự Đánh Giá (Self-Evaluation) | Bảng tự soi chiếu năng lực, điểm cần cải thiện và kế hoạch khắc phục |
| `resume.html` | Hồ Sơ Năng Lực (Resume) | Bản CV trực tuyến tích hợp tải về tệp `resume.pdf` |
| `contact.html` | Liên Hệ (Contact) | Kênh kết nối mạng xã hội, email và thông tin liên lạc |

---

## Công Nghệ Sử Dụng

- **HTML5 Semantic**: Cấu trúc ngữ nghĩa rõ ràng, thân thiện với công cụ tìm kiếm (SEO) và tối ưu khả năng truy cập (Accessibility).
- **Vanilla CSS3**: 
  - Hệ thống bố cục kết hợp Flexbox và CSS Grid.
  - Thiết kế thích ứng (Responsive Web Design) tương thích đa kích thước màn hình từ điện thoại, máy tính bảng đến máy tính để bàn.
  - Sử dụng hiệu ứng chuyển động mượt mà (Transitions & Micro-interactions).
- **Vanilla JavaScript**: Xử lý logic điều hướng thanh cuộn (Reveal animations), tương tác menu trên thiết bị di động.
- **Phông chữ**: Tích hợp Google Fonts (`Inter`).

---

## Hướng Dẫn Xem Trực Tiếp và Chạy Local

### 1. Xem Trực Tiếp Trên Web
Truy cập địa chỉ đã xuất bản thông qua GitHub Pages:
```
https://phihanh-qg.github.io/portfolio/
```

### 2. Chạy Thử Trên Máy Cá Nhân (Local)
Không cần cài đặt framework hay phụ thuộc bên ngoài:
1. Tải hoặc clone repository về máy:
   ```bash
   git clone https://github.com/phihanh-qg/portfolio.git
   ```
2. Mở thư mục dự án và nhấp đúp vào file `index.html` để mở trực tiếp trên trình duyệt (Chrome, Edge, Firefox,...).
3. Hoặc sử dụng tiện ích **Live Server** trên Visual Studio Code để tự động tải lại trang khi chỉnh sửa mã nguồn.

---

## Hướng Dẫn Kích Hoạt GitHub Pages

Nếu trang web chưa tự động hiển thị tại đường dẫn trên, thực hiện kích hoạt theo các bước:
1. Truy cập vào kho chứa trên GitHub: `https://github.com/phihanh-qg/portfolio`
2. Chọn tab **Settings** (Cài đặt).
3. Tại menu bên trái, chọn mục **Pages**.
4. Trong phần **Build and deployment**:
   - **Source**: Chọn `Deploy from a branch`.
   - **Branch**: Chọn nhánh `main`, thư mục `/ (root)`.
5. Nhấn **Save**. Sau khoảng 1-2 phút, website sẽ hoạt động chính thức.

---

## Cấu Trúc Thư Mục

```plaintext
portfolio/
├── img/                      # Thư mục hình ảnh, chứng chỉ, tư liệu minh chứng
├── .gitignore                # Danh sách loại trừ file tạm hệ thống và editor
├── LICENSE                   # Giấy phép mã nguồn mở MIT
├── README.md                 # Tài liệu mô tả dự án
├── index.html                # Trang chủ
├── about.html                # Trang giới thiệu bản thân
├── achievements.html         # Trang thành tích
├── contact.html              # Trang liên hệ
├── education.html            # Trang học vấn
├── pdp.html                  # Kế hoạch phát triển cá nhân
├── resume.html               # Bản CV trực tuyến
├── resume.pdf                # Tệp CV đính kèm định dạng PDF
├── roadmap.html              # Lộ trình học tập & nghề nghiệp
├── self-eval.html            # Bảng tự đánh giá năng lực
└── teamwork.html             # Kỹ năng làm việc nhóm
```

---

## Bản Quyền

Dự án được phân phối theo giấy phép [MIT License](LICENSE).

Tác giả: [Pham Phi Khanh (phihanh-qg)](https://github.com/phihanh-qg)
