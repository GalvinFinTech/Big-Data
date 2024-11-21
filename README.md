# Hệ thống Gợi ý Sản phẩm

## Giới thiệu

Đây là hệ thống gợi ý sản phẩm được xây dựng để phân tích dữ liệu khách hàng và đưa ra các gợi ý sản phẩm phù hợp. Hệ thống sử dụng thuật toán **Collaborative Filtering** để phân tích hành vi của khách hàng.

## Cấu trúc dự án

- **src**: Chứa mã nguồn Python của hệ thống.
    - **241CN1302_Nhóm2- Colab.ipynb**: File chạy chính của hệ thống.
    - **rcm_sys.py**: File chứa code cho ứng dụng web.
  
- **data**: Chứa dữ liệu đầu vào, bao gồm file `OnlineRetail.csv`.

- **docs**: Chứa tài liệu và tài nguyên.
    - **241CN1302_Nhóm2.pdf**: Báo cáo chi tiết quá trình xây dựng hệ thống.
    - **Wed_app.mov**: Video demo giới thiệu ứng dụng web.

## Truy cập tài liệu và mã nguồn

Để xem chi tiết và tải xuống tài liệu, vui lòng truy cập thư mục Google Drive tại đây:

[https://drive.google.com/drive/folders/1VKl13o2U92kdMG5rMDanLBIBQfgyPxOa?usp=share_link]

Trong thư mục này, bạn sẽ tìm thấy:

- Thư mục **src**: Chứa các file code chính (main.py, app.py) và các file code khác.
- Thư mục **data**: Chứa file dữ liệu `OnlineRetail.csv`.
- Thư mục **docs**: Chứa file báo cáo `241CN1302_Nhóm2.pdf` và video demo `Wed_demo.mov`.

## Hướng dẫn sử dụng

### Yêu cầu hệ thống:
- Python >= 3.7
- Các thư viện yêu cầu được liệt kê trong file `requirements.txt`.

### Cách chạy dự án:
1. **Chạy hệ thống**:  
    Để bắt đầu hệ thống, chạy file `241CN1302_Nhóm2- Colab.ipynb`:
    ```bash
    python src/241CN1302_Nhóm2- Colab.ipynb
    ```

2. **Chạy ứng dụng web (nếu có)**:  
    Để chạy ứng dụng web, chạy file `rcm_sys.py`:
    ```bash
    python src/rcm_sys.py
    ```

## Tính năng chính

- **Phân tích dữ liệu khách hàng**:  
    Sử dụng thuật toán **K-means** để phân nhóm khách hàng.

- **Gợi ý sản phẩm**:  
    Gợi ý các sản phẩm phù hợp dựa trên hành vi khách hàng.

## Demo

Xem video demo tại: `Wed_demo.mov`.

## Tài liệu tham khảo

- **Báo cáo chi tiết**: Xem file `241CN1302_Nhóm2.pdf` để biết thêm thông tin về quá trình xây dựng hệ thống.
- **Hệ thống gợi ý sản phẩm**: Dựa trên dữ liệu từ file `OnlineRetail.csv`.

## Liên hệ

- **Tác giả**: _[Galvin]_
- **Email**: [vinh21414@st.uel.edu.com](mailto:vinh21414@st.uel.edu.com)
- **GitHub**: [Link GitHub](https://github.com/GalvinFinTech?)

---
