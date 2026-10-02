# Phân tích Doanh thu Bán lẻ - Superstore Sales

## 1. Giới thiệu dự án

Dự án thực hiện phân tích doanh thu của chuỗi bán lẻ Superstore nhằm:
- Khám phá các yếu tố ảnh hưởng đến doanh thu (danh mục sản phẩm, khu vực, thời gian…).
- Phân tích xu hướng doanh thu theo thời gian.
- Đề xuất các insight hỗ trợ quyết định kinh doanh.

**Môn học:** Khoa học Dữ liệu  
**Đề tài:** Phân tích doanh thu và lợi nhuận bán lẻ (Đề tài số 9)

## 2. Cấu trúc thư mục dự án
Phan-tich-doanh-thu-loi-nhuan/
├── data/
│   ├── raw/              # Dữ liệu gốc (không chỉnh sửa)
│   ├── interim/          # Dữ liệu trung gian
│   └── processed/        # Dữ liệu đã làm sạch
├── notebooks/            # Các notebook phân tích theo thứ tự
├── src/                  # Mã nguồn tái sử dụng
├── reports/
│   └── figures/          # Hình ảnh xuất ra từ phân tích
├── requirements.txt      # Danh sách thư viện
└── README.md             # Tài liệu hướng dẫn
text## 3. Nguồn dữ liệu

- **Tên dataset:** Superstore Sales (Sales Forecasting)
- **Nguồn:** [Kaggle - rohitsahoo/sales-forecasting](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)
- **Mô tả:** Dữ liệu giao dịch bán lẻ bao gồm thông tin đơn hàng, khách hàng, sản phẩm và doanh thu.
- **Kích thước:** 9.800 dòng, 18 cột (sau làm sạch còn 9.789 dòng).

## 4. Cách chạy dự án từ đầu (Reproduce)

### Bước 1: Clone repository
```bash
git clone https://github.com/USERNAME/Phan-tich-doanh-thu-loi-nhuan.git
cd Phan-tich-doanh-thu-loi-nhuan