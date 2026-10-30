# Evidence – Tuần 05

- **Milestone:** Week 5 (mỗi repo có milestone riêng, xem bảng dưới)
- **Tag cuối tuần:** `w05`
- **Thời gian:** 25/10/2026 - 31/10/2026

# Link các Repo-Github

| Repo | Vai trò | Link |
|---|---|---|
| pharmacy-management-system-backend | Backend  | https://github.com/ttl2004/pharmacy-management-system-backend |
| drugdb-core | ETL/CSDL dược | https://github.com/ttl2004/drugdb-core |
| pharmacy-management-admin-frontend | Frontend  | https://github.com/blueT52Hz/pharmacy-management-admin-frontend |
| pharmacy-base-rag | RAG | https://github.com/blueT52Hz/pharmacy-base-rag |
| drug-interaction-ddinter | Tương tác thuốc | https://github.com/blueT52Hz/drug-interaction-ddinter |


# Link các Milestone

| Repo | Milestone | Link |
|---|---|---|
| pharmacy-management-system-backend | Week 5 | https://github.com/ttl2004/pharmacy-management-system-backend/milestone/2 |
| drug-interaction-ddinter | Week 5 | https://github.com/blueT52Hz/drug-interaction-ddinter/milestone/1|


## Phân công & minh chứng

| Thành viên |Repo| Issue | Pull Request | Reviewer | Kết quả |
|---|---|---|---|---|---|
| Trần Tiểu Long | pharmacy-management-system-backend | #28 | #29 | Nguyễn Hoa Thanh Tùng | Done |
| Nguyễn Hoa Thanh Tùng | drug-interaction-ddinter | #3 | #1 | Trần Tiểu Long | Done |


## Số liệu & kiểm thử

- Số liệu tổng hợp: [metrics.csv](metrics.csv)
- Số liệu chi tiết từng phần ([metrics/](metrics/)):

  - [pharmacy-base-rag.csv](metrics/pharmacy-base-rag.csv): bộ 100 câu hỏi, gồm truy xuất (80 câu) và sinh câu trả lời (100 câu)
  - [drug-interaction-ddinter.csv](metrics/drug-interaction-ddinter.csv): crawl DDInter, kiểm định dữ liệu, ánh xạ hoạt chất, import CSDL, kiểm thử API
