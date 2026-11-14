# Evidence – Tuần 07

- **Milestone:** Week 7 (mỗi repo có milestone riêng, xem bảng dưới)
- **Tag cuối tuần:** `w07`
- **Thời gian:** 08/11/2026 - 14/11/2026

# Link các Repo-Github

| Repo | Vai trò | Link |
|---|---|---|
| pharmacy-management-system-backend | Backend  | https://github.com/ttl2004/pharmacy-management-system-backend |
| drugdb-core | ETL/CSDL dược | https://github.com/ttl2004/drugdb-core |
| pharmacy-management-admin-frontend | Frontend  | https://github.com/blueT52Hz/pharmacy-management-admin-frontend |
| pharmacy-rag | RAG | https://github.com/blueT52Hz/pharmacy-rag |
| drug-interaction-ddinter | Tương tác thuốc | https://github.com/blueT52Hz/drug-interaction-ddinter |
| OCR-Baseline | OCR| https://github.com/ttl2004/OCR-Baseline |



# Link các Milestone

| Repo | Milestone | Link |
|---|---|---|
| pharmacy-management-system-backend | Week 7 | https://github.com/ttl2004/pharmacy-management-system-backend/milestone/2 |
| drug-interaction-ddinter | Week 7 | https://github.com/blueT52Hz/drug-interaction-ddinter/milestone/1|
| pharmacy-management-admin-frontend | Week 7 | https://github.com/blueT52Hz/pharmacy-management-admin-frontend/milestone/1|
| pharmacy-rag | Week 7 | https://github.com/blueT52Hz/pharmacy-rag/milestone/1|
| OCR-Baseline | Week 7 | https://github.com/ttl2004/OCR-Baseline/milestone/1|


## Phân công & minh chứng

| Thành viên |Repo| Issue | Pull Request | Reviewer | Kết quả |
|---|---|---|---|---|---|
| Trần Tiểu Long | pharmacy-management-system-backend | #39 | #44 | Nguyễn Hoa Thanh Tùng | Done |
| Trần Tiểu Long | pharmacy-management-system-backend | #38| #43 | Nguyễn Hoa Thanh Tùng | Done |
| Trần Tiểu Long | pharmacy-management-system-backend | #40 | #40 | Nguyễn Hoa Thanh Tùng | Done |
| Trần Tiểu Long | pharmacy-management-system-backend | #37 | #41 | Nguyễn Hoa Thanh Tùng | Done |
|Nguyễn Hoa Thanh Tùng | pharmacy-management-admin-frontend | #7 | #8 | Trần Tiểu Long  | Done |
| Trần Tiểu Long | OCR-Baseline | #1 | #2 | Nguyễn Hoa Thanh Tùng | Done |


## Số liệu & kiểm thử

- Số liệu tổng hợp: [metrics.csv](metrics.csv)
- Số liệu chi tiết từng phần ([metrics/](metrics/)):

  - [ocr-llm.csv](metrics/ocr-llm.csv): so sánh 3 hướng OCR (cục bộ PaddleOCR + VietOCR, Google Cloud Vision, DeepSeek OCR) và OCR + LLM trên 100 ảnh kiểm chứng ViFoodLabel

- Kết quả kiểm thử: [test-results.md](test-results.md) (OCR-Baseline, 37/37 pass)


