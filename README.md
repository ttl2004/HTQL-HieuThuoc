# HTQL-HieuThuoc

Repo quản lý tiến độ và lưu minh chứng (evidence) hằng tuần của đồ án **Hệ thống quản lý nhà thuốc**.

## Các repo mã nguồn

| Repo | Vai trò |
|---|---|
| [pharmacy-management-system-backend](https://github.com/ttl2004/pharmacy-management-system-backend) | Backend |
| [drugdb-core](https://github.com/ttl2004/drugdb-core) | ETL / CSDL dược |
| [pharmacy-management-admin-frontend](https://github.com/blueT52Hz/pharmacy-management-admin-frontend) | Frontend trang quản trị |
| [pharmacy-rag](https://github.com/blueT52Hz/pharmacy-rag) | RAG hỏi đáp thông tin thuốc |
| [drug-interaction-ddinter](https://github.com/blueT52Hz/drug-interaction-ddinter) | Cảnh báo tương tác thuốc  |
| [OCR-Baseline](https://github.com/ttl2004/OCR-Baseline) | OCR + LLM trích xuất thông tin từ ảnh bao bì / tờ hướng dẫn sử dụng thuốc |



## Cấu trúc thư mục

```
HTQL-HieuThuoc/
├── README.md                 # file này
└── Evidence/                 # minh chứng theo tuần
    ├── W04/ ... W06/         # các tuần trước
    └── W07/
        ├── README.md         # tóm tắt tuần: repo, milestone, phân công, issue, PR, reviewer, kết quả
        ├── metrics.csv       # mục lục số liệu, trỏ tới từng file trong metrics/
        ├── metrics/          # số liệu chi tiết, mỗi phần một file
        │   └── ocr-llm.csv
        ├── test-results.md   # kết quả kiểm thử
        └── figures/          # hình ảnh, biểu đồ, ảnh chụp màn hình
```

## Quy ước mỗi tuần

Mỗi tuần `WXX` gồm:

- **Trên GitHub:** issue và PR gắn milestone của repo (bảng trên); mỗi thành viên có issue riêng; mỗi PR do thành viên khác review; cuối tuần gắn tag `wXX` (ví dụ `w07`).
- **Trong repo:** thư mục `Evidence/WXX/` có đủ các file như cấu trúc trên; `metrics/` chỉ chứa số liệu mới của tuần đó.
