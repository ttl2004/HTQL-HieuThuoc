# Kết quả kiểm thử – Tuần 06


| Test case | Mô tả | Kết quả (Pass/Fail) | Ghi chú |
|---|---|---|---|
| TC01 | Hỏi chống chỉ định: "Metformin chống chỉ định với những trường hợp nào?" | Pass | Nguồn hạng 1: Metformin – Chống chỉ định (0,90). Trả lời đủ 3 ý: suy thận nặng (eGFR < 30), quá mẫn, nhiễm toan chuyển hoá; có trích dẫn [1]. Chữ đầu tiên 0,59 s; tổng 1,35 s |
| TC02 | Hỏi liều dùng: "Liều dùng ibuprofen 200mg cho người lớn là bao nhiêu?" | Pass | Nguồn hạng 1: Ibuprofen 200mg – Liều lượng (0,93). Trả lời đúng: 1 viên mỗi 4–6 giờ, có thể 2 viên, tối đa 6 viên/24 giờ. Chữ đầu tiên 0,53 s; tổng 1,44 s |
| TC03 | Hỏi tác dụng phụ: "Tác dụng phụ thường gặp của amoxicillin là gì?" | Pass | Nguồn hạng 1: Amoxicillin 500mg – Tác dụng phụ (0,90). Trả lời đúng, có cấu trúc: tiêu chảy, phát ban, nôn, buồn nôn; tách riêng phác đồ phối hợp. Chữ đầu tiên 0,71 s; tổng 4,04 s. Có 2 đoạn trùng cùng điểm 0,8977 trong nguồn |
| TC04 | Câu hỏi ngoài dữ liệu: "Giá bán lẻ của thuốc Panadol Extra hiện nay là bao nhiêu?" | Pass | Nguồn hạng 1: Pantoprazole – Tác dụng phụ (0,83, không liên quan). Trả lời "Không tìm thấy thông tin này trong dữ liệu", không bịa giá. Chữ đầu tiên 0,62 s; tổng 1,22 s |

**Tổng:** 4/4 pass

