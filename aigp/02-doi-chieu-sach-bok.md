# Đối chiếu sách *AIGP Study Guide 2026* với BoK v2.1

Sách: *AIGP Study Guide 2026: 2000+ Practice Materials, 18 Full-Length Tests* (Victor Reynolds, Divinemind Exam Prep, 2025). Đây là **tài liệu không chính thức**, không liên kết với IAPP. Câu hỏi trong sách do tác giả tự soạn.

## Kết luận nhanh

| Đánh giá | Chi tiết |
|---|---|
| ✅ **Mạnh** | Vòng đời AI, quản trị dữ liệu (lineage/provenance), model card, drift, giám sát, bias, quản lý sự cố, checklist thực hành. Phù hợp **Domain I, III, IV** |
| ❌ **Yếu** | **Domain II**: sách nói về luật một cách chung chung ("EU AI Act-style", "horizontal AI acts"), cụm "AI Act" chỉ xuất hiện khoảng 11 lần, **không có** OECD, luật AI Hàn Quốc, GPAI, ISO 22989/42001/42005, FTC, GDPR Art. 22, luật bang Mỹ cụ thể. Gần như không có RAG, agentic AI, điều khoản hợp đồng nhà cung cấp |
| ⚠️ **Khác đề thật** | Sách có câu Đúng/Sai và câu chọn nhiều đáp án. Đề thật **chỉ có câu 1 đáp án đúng nhất**, khoảng 30% là case study. Câu trong sách **dễ hơn** và thường lộ đáp án qua các phương án nhiễu vô lý (ví dụ "Facilities management", "Color scheme") |
| ⚠️ **Tỷ trọng** | Đề full-length trong sách chia 22/27/26/25 câu, gần với BoK nhưng phân loại theo chương cũ của sách, không theo các competency I.A đến IV.C |

**Cách dùng sách hiệu quả:** dùng làm **ngân hàng câu hỏi để ôn khái niệm** và đọc phần giải thích (rationale). Phần luật (Domain II) phải học từ [01-bok-tom-tat.md](01-bok-tom-tat.md) và nguồn gốc bên dưới.

## Bảng đối chiếu theo competency

Số trang theo mục lục của sách.

| BoK | Phần tương ứng trong sách | Mức độ phủ | Cần bổ sung |
|---|---|---|---|
| **I.A** AI là gì, rủi ro, nguyên tắc | Ch.1: 1.1, 1.2, 1.3 (tr.10 đến 13) | Khá | Định nghĩa AI của OECD; danh sách đặc điểm riêng của AI theo BoK (opacity, autonomy, probabilistic outputs...); agentic AI |
| **I.B** Vai trò, đào tạo, cách tiếp cận theo tổ chức | Ch.1: 1.4, 1.5 (tr.13 đến 15) | Khá | Phân biệt developer, provider, deployer, user; AI literacy (EU AI Act Art. 4) |
| **I.C** Chính sách theo vòng đời, bên thứ ba | Ch.2: 2.5 (tr.80); Ch.3: 3.1 (tr.183) | Khá | Acceptable use policy cho GenAI; rủi ro chuỗi cung ứng mô hình |
| **II.A** Luật bảo vệ dữ liệu áp dụng cho AI | Ch.2: 2.2 (tr.60) | Trung bình | GDPR Art. 22, DPIA, cơ sở pháp lý cho dữ liệu huấn luyện, BIPA |
| **II.B** Luật khác (IP, chống phân biệt đối xử, người tiêu dùng, trách nhiệm sản phẩm) | Ch.2: 2.1 (tr.53), 2.7 (tr.91) | **Yếu** | FTC Section 5 và algorithmic disgorgement; ECOA/FCRA; Title VII disparate impact; EU Product Liability Directive mới; TDM opt-out |
| **II.C** Luật chuyên về AI | Ch.2: 2.1 (tr.53) | **Rất yếu** | **Toàn bộ EU AI Act** (phân loại, nghĩa vụ provider và deployer, GPAI, mốc thời gian, phạt); luật AI Hàn Quốc; Colorado AI Act; NYC LL144 |
| **II.D** Tiêu chuẩn: OECD, NIST AI RMF, ISO | Ch.2: 2.4 (tr.73) | **Yếu** | OECD Principles và Classification Framework; NIST AI RMF (4 chức năng, 7 đặc tính, Playbook, GenAI Profile); ISO 22989/42001/42005 |
| **III.A** Thiết kế và xây dựng | Ch.3: 3.1, 3.7 (tr.183, 214) | Tốt | Ma trận xác suất × mức độ nghiêm trọng, hệ thống phân cấp giảm thiểu rủi ro |
| **III.B** Dữ liệu huấn luyện và kiểm thử | Ch.3: 3.2, 3.3, 3.4 (tr.190 đến 200) | Tốt | |
| **III.C** Phát hành, giám sát, bảo trì | Ch.3: 3.5, 3.6 (tr.205, 209); Ch.4: 4.3 (tr.328) | Tốt | Conformity assessment, instructions for use, post-market monitoring theo EU AI Act |
| **IV.A** Quyết định triển khai, loại mô hình, phương án triển khai | Ch.4: 4.1 (tr.316) | **Yếu** | Open vs. proprietary, SLM vs. LLM, cloud/on-prem/edge, **RAG**, **fine-tuning**, **agentic** |
| **IV.B** Đánh giá hệ thống, hợp đồng nhà cung cấp | Ch.4: 4.1, 4.5 (tr.316, 340) | **Yếu** | Điều khoản hợp đồng (dùng dữ liệu để huấn luyện, IP indemnity, thông báo thay đổi mô hình, quyền kiểm toán) |
| **IV.C** Triển khai, giám sát, tắt hoặc khoanh vùng hệ thống | Ch.4: 4.2 đến 4.7 (tr.322 đến 351) | Tốt | Kế hoạch truyền thông bên ngoài; tắt hệ thống tại một khu vực vì lý do pháp lý |

## Ngân hàng câu hỏi trong sách và cách dùng theo lịch

| Bộ câu | Trang | Dùng vào |
|---|---|---|
| Ch.1: 250 câu | tr.17 | Tuần 2 (Domain I) |
| Ch.2: 400 câu | tr.108 | Tuần 3 và 4, kèm câu hỏi bổ sung về luật do Claude soạn |
| Ch.3: 4 bộ × 100 câu | tr.227, 249, 271, 292 | Tuần 5 (Domain III) |
| Ch.4: 4 bộ × 100 câu | tr.366, 381, 396, 411 | Tuần 6 (Domain IV) |
| Ch.5: 100 câu | tr.441 | Tuần 7, luyện kỹ năng làm bài |
| **Full-Length Exam 1** | tr.459 | **Tuần 1: đề đo nền** |
| Full-Length Exam 2, 3 | tr.476, 495 | Tuần 7 và 8 |

Sách chỉ có 3 đề full-length (dù tiêu đề ghi 18). Đề luyện tập thêm cho tuần 7 và 8 sẽ do Claude soạn theo đúng định dạng đề thật (1 đáp án, có case study, tỷ trọng theo BoK).

## Nguồn gốc nên đọc bổ sung (miễn phí)

| Chủ đề | Nguồn | Ưu tiên |
|---|---|---|
| EU AI Act | Văn bản Regulation (EU) 2024/1689 trên EUR-Lex; đọc kỹ Art. 3 (định nghĩa), 5, 6, 9 đến 17, 25 đến 27, 50 đến 55, 99 và Annex III. Công cụ tra cứu dễ đọc: artificialintelligenceact.eu | ⭐⭐⭐ |
| NIST AI RMF | NIST AI 100-1 (AI RMF 1.0), AI RMF Playbook, NIST AI 600-1 (GenAI Profile) | ⭐⭐⭐ |
| OECD | OECD AI Principles (bản cập nhật 2024), OECD Framework for the Classification of AI Systems | ⭐⭐ |
| ISO | ISO/IEC 42001 (bản PDF đã có trong repo: `0423-ISO-42001-2023.pdf`); phần giới thiệu và thuật ngữ của 22989; tóm tắt 42005 | ⭐⭐ |
| Luật AI Hàn Quốc | Các bài tóm tắt của IAPP về South Korea AI Basic Act | ⭐⭐ |
| Luật bang Mỹ | IAPP US State AI Governance Legislation Tracker; Colorado SB 24-205 | ⭐ |
| Tổng hợp | IAPP AI Governance Center (tin tức, bảng so sánh, các bài "AI governance in practice") | ⭐ |
