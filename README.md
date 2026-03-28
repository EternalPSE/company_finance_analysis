# company_finance_analysis

Phân tích dữ liệu hóa đơn doanh nghiệp từ bộ dữ liệu MolaDatabase, phục vụ viết báo cáo khoa học dữ liệu và minh họa quy trình xử lý dữ liệu thực tế: đọc dữ liệu JSON/Excel, chuẩn hóa dữ liệu 3NF, phân tích dịch vụ, tiền xử lý, trực quan hóa, và xây dựng mô hình dự báo.

---

## 1. Mục tiêu dự án

Dự án này nhằm:

- Đọc và chuẩn hóa dữ liệu hóa đơn từ các file `.json` và `.xlsx`
- Kết nối dữ liệu giữa bảng hóa đơn, chi tiết hóa đơn và phân tích tổng hợp
- Phân loại dịch vụ theo nhóm nghiệp vụ như:
  - Inspection
  - Survey
  - Calibration
  - Testing
  - Other
- Tạo bộ dữ liệu mức hóa đơn để phục vụ:
  - Data preprocessing
  - Exploratory Data Analysis (EDA)
  - Modeling
  - Evaluation
- Hỗ trợ chèn code, bảng và biểu đồ vào báo cáo LaTeX học thuật

---

## 2. Cấu trúc thư mục đề xuất

```text
company_finance_analysis/
│
├── 01_data_understanding_sql_style.ipynb
├── 02_preprocessing_outlier_flagging.ipynb
├── 03_eda_visualization.ipynb
├── 04_modeling_linear_regression.ipynb
│
├── MolaDatabase.invoices.json
├── MolaDatabase.invoice_items.json
├── MolaDatabase.invoice_analytics.json
├── join_3NF_result.xlsx
│
├── prepared_invoice_dataset.csv
├── prepared_invoice_dataset_cleaned.csv
│
└── README.md
