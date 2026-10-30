# HTQL-HieuThuoc

Repo quản lý tiến độ và lưu minh chứng (evidence) hằng tuần của đồ án **Hệ thống quản lý nhà thuốc**.

## Các repo mã nguồn

| Repo | Vai trò |
|---|---|
| [pharmacy-management-system-backend](https://github.com/ttl2004/pharmacy-management-system-backend) | Backend |
| [drugdb-core](https://github.com/ttl2004/drugdb-core) | ETL / CSDL dược |
| [pharmacy-management-admin-frontend](https://github.com/blueT52Hz/pharmacy-management-admin-frontend) | Frontend trang quản trị |
| [pharmacy-base-rag](https://github.com/blueT52Hz/pharmacy-base-rag) | RAG hỏi đáp thông tin thuốc |
| [drug-interaction-ddinter](https://github.com/blueT52Hz/drug-interaction-ddinter) | Cảnh báo tương tác thuốc  |

## Cấu trúc thư mục

```
HTQY-HieuThuoc/
├── README.md                 # file này
└── Evidence/                 # minh chứng theo tuần
    ├── W01/ ... W04/         # các tuần trước
    └── W05/
        ├── README.md         # tóm tắt tuần: repo, phân công, issue, PR, reviewer, kết quả
        ├── metrics.csv       # mục lục số liệu, trỏ tới từng file trong metrics/
        ├── metrics/          # số liệu chi tiết, mỗi phần một file (số cột khác nhau)
        │   ├── drugdb-core.csv
        │   ├── pharmacy-base-rag.csv
        │   └── drug-interaction-ddinter.csv
        ├── test-results.md   # kết quả kiểm thử
        └── figures/          # hình ảnh, biểu đồ, ảnh chụp màn hình
```

## Quy ước mỗi tuần

Mỗi tuần `WXX` gồm:

- **Trên GitHub:** milestone `TuanX`; mỗi thành viên có issue riêng; mỗi PR do thành viên khác review; cuối tuần gắn tag `wXX` (ví dụ `w04`).
- **Trong repo:** thư mục `Evidence/WXX/` có đủ các file như cấu trúc trên.
