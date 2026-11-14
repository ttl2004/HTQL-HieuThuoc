# Kết quả kiểm thử – Tuần 07

Kiểm thử tự động của repo **OCR-Baseline** (pytest, chạy ngày 14/11/2026; engine OCR và LLM được giả lập, không gọi model/API thật).

| Test case | Mô tả | Số test | Kết quả (Pass/Fail) | Ghi chú |
|---|---|---|---|---|
| TC01 | chế độ chạy cả thư mục với engine giả và LLM giả | 3 | Pass | |
| TC02 |  kiểm tra con số trong kết quả LLM có trong văn bản OCR (chuẩn hoá dấu phẩy thập phân…) | 5 | Pass | |
| TC03 |  thứ tự đọc với bố cục nhiều cột (toạ độ box thật từ ảnh vỏ hộp) | 5 | Pass | |
| TC04 |  cấu hình (profile) OCR | 4 | Pass | |
| TC05 |  quản lý prompt theo phiên bản | 8 | Pass | |
| TC06 |lưu trữ SQLite (bản ghi, dataset, prompt) | 7 | Pass | |
| TC07 |  engine Google Cloud Vision | 5 | Pass | |

**Tổng:** 37/37 pass
