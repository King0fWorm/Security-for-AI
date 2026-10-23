# Ôn thi AIGP (IAPP): mục tiêu 30/12/2026

Thư mục này chứa toàn bộ tài liệu ôn thi chứng chỉ **AIGP (Artificial Intelligence Governance Professional)** của IAPP, bám theo **Body of Knowledge (BoK) v2.1**, có hiệu lực từ 2/2/2026.

| File | Nội dung |
|---|---|
| [README.md](README.md) | Thông tin kỳ thi, lịch học 9 tuần, cách làm đề đo nền, nhật ký lỗi |
| [01-bok-tom-tat.md](01-bok-tom-tat.md) | Tóm tắt BoK v2.1 bằng tiếng Việt theo từng domain, kèm "cần nắm gì" và "bẫy thường gặp" |
| [02-doi-chieu-sach-bok.md](02-doi-chieu-sach-bok.md) | Đối chiếu cuốn *AIGP Study Guide 2026* (Victor Reynolds) với BoK, các phần sách thiếu và nguồn gốc cần đọc bổ sung |

Các file sẽ được bổ sung trong những tuần tới: tóm tắt chi tiết từng domain, flashcard, bộ câu hỏi luyện tập và phân tích đề.

---

## 1. Thông tin kỳ thi

Nguồn: [AIGP Candidate Handbook](https://iapp.org/certify/aigp-candidate-handbook), [Schedule an exam](https://iapp.org/certify/schedule-an-exam). Thông tin được kiểm tra ngày 23/10/2026. Bạn nên xem lại trước khi đặt lịch.

| Mục | Chi tiết |
|---|---|
| Số câu | 100 câu trắc nghiệm, 1 đáp án đúng nhất. Trong đó **85 câu tính điểm** và 15 câu thử nghiệm không tính điểm (không biết câu nào) |
| Câu tình huống | Khoảng **30%** câu hỏi gắn với case study |
| Thời gian | **3 giờ**, có thể nghỉ 15 phút giữa giờ |
| Điểm đỗ | **300** trên thang 100 đến 500 (scaled). Bỏ trống tính là sai, sai không bị trừ điểm nên **không bao giờ bỏ trống** |
| Kết quả | Có ngay sau khi thi: đỗ/trượt, điểm và tỷ lệ đúng theo từng domain |
| Hình thức | Thi tại trung tâm **Pearson VUE** (Hà Nội và TP.HCM có trung tâm) hoặc thi online **OnVUE** (không áp dụng ở một số nước, cần kiểm tra khi đặt lịch) |
| Lệ phí | 799 USD (649 USD nếu là hội viên IAPP). Thi lại: 625 / 475 USD |
| Đặt lịch | Mua bài thi trên IAPP store, sau đó đặt lịch qua MyIAPP. Đặt trước ít nhất 24 giờ, đổi lịch trước ít nhất 48 giờ. Phải thi trong vòng 1 năm kể từ ngày mua |

**Phân bổ câu hỏi theo BoK v2.1:**

| Domain | Số câu (min đến max) | Tỷ trọng ước tính |
|---|---|---|
| I. Nền tảng quản trị AI | 16 đến 20 | khoảng 18% |
| II. Luật, tiêu chuẩn, khung áp dụng cho AI | 19 đến 23 | khoảng 21% |
| III. Quản trị phát triển AI | 21 đến 25 | khoảng 23% |
| IV. Quản trị triển khai và sử dụng AI | 21 đến 25 | khoảng 23% |

Domain III và IV chiếm gần một nửa đề và chủ yếu là câu áp dụng/phân tích tình huống. Domain II đòi hỏi nhớ chính xác (phân loại rủi ro EU AI Act, nghĩa vụ provider và deployer, mức phạt, mốc thời gian).

---

## 2. Lịch học 9 tuần (khoảng 8 giờ/tuần)

Gợi ý chia tuần: 4 buổi × 1,5 giờ trong tuần (đọc tóm tắt và flashcard) + 1 buổi 2 giờ cuối tuần (làm câu hỏi và xem lại lỗi).

| Tuần | Thời gian | Nội dung chính | Việc cần làm |
|---|---|---|---|
| **1** | 23/10 đến 1/11 | Chốt lịch thi và đo nền | Đặt lịch thi. Đọc [01-bok-tom-tat.md](01-bok-tom-tat.md). Làm đề đo nền (mục 3). Ghi điểm theo domain vào nhật ký |
| **2** | 2/11 đến 8/11 | **Domain I**: AI là gì, rủi ro và tác hại, nguyên tắc AI có trách nhiệm, vai trò, chính sách theo vòng đời, rủi ro bên thứ ba | Tóm tắt Domain I, flashcard, 40 đến 50 câu luyện |
| **3** | 9/11 đến 15/11 | **Domain II (phần 1)**: luật bảo vệ dữ liệu áp dụng cho AI (II.A), luật khác (II.B: chống phân biệt đối xử, bảo vệ người tiêu dùng, trách nhiệm sản phẩm, sở hữu trí tuệ) | Ôn nhanh GDPR (bạn đã vững), tập trung vào điểm giao với AI: Art. 22, DPIA, cơ sở pháp lý cho dữ liệu huấn luyện |
| **4** | 16/11 đến 22/11 | **Domain II (phần 2)**: EU AI Act (II.C), luật AI Hàn Quốc, luật bang ở Mỹ, OECD, NIST AI RMF, ISO 22989/42001/42005 (II.D) | Tuần nặng nhất. Học thuộc bảng phân loại rủi ro, nghĩa vụ theo vai trò, GPAI, mức phạt, mốc thời gian |
| **5** | 23/11 đến 29/11 | **Domain III**: quản trị thiết kế và xây dựng, dữ liệu huấn luyện và kiểm thử, phát hành, giám sát và bảo trì | Gắn với kinh nghiệm security: red teaming, threat modeling, data poisoning, drift |
| **6** | 30/11 đến 6/12 | **Domain IV**: quyết định triển khai, loại mô hình, phương án triển khai (RAG, fine-tuning, agentic), hợp đồng nhà cung cấp, giám sát, ngừng hoặc khoanh vùng hệ thống | Luyện câu tình huống deployer và provider |
| **7** | 7/12 đến 13/12 | Luyện đề thật lần 1 và 2 | 2 đề 100 câu, bấm giờ 3 tiếng. Phân tích lỗi sai theo domain |
| **8** | 14/12 đến 20/12 | Luyện đề thật lần 3 và 4, vá lỗ hổng | Ôn lại phần dưới 70% |
| **9** | 21/12 đến 29/12 | Ôn nước rút | Flashcard hay sai, 1 đề cuối, xem lại bẫy thường gặp. Kiểm tra yêu cầu giấy tờ tùy thân của Pearson VUE (thường cần giấy tờ có chữ Latin và ảnh, hộ chiếu là an toàn nhất) |
| **Thi** | **Thứ Tư 30/12/2026** | | Ngủ đủ, đến sớm 30 phút |

---

## 3. Đề đo nền (tuần 1)

Mục đích: biết điểm xuất phát và domain nào yếu, **không phải** để đỗ.

1. Dùng **Full-Length Practice Exam 1** trong sách (Chapter 6, trang 459). Đáp án ở mục 6.2.
2. Bấm giờ **3 tiếng** như thi thật (sách gợi ý 2,5 giờ, nhưng nên tập theo thời lượng thật).
3. Không mở tài liệu. Làm xong toàn bộ rồi mới chấm.
4. Ghi điểm theo 4 domain vào bảng nhật ký bên dưới.

**Lưu ý khi đọc kết quả:** đề trong sách **dễ hơn đề thật** và khác định dạng. Sách có câu Đúng/Sai và câu chọn nhiều đáp án, còn đề thật chỉ có câu 1 đáp án đúng nhất, có nhiều case study và hỏi kỹ về luật. Nếu bạn đạt dưới 75% ở đề sách, phần đó cần ưu tiên. Nếu đạt trên 85% thì cũng chưa có nghĩa là đã sẵn sàng.

---

## 4. Nhật ký điểm và lỗi

Cập nhật sau mỗi đề hoặc bộ câu luyện. Gửi kết quả cho Claude để nhận phân tích và flashcard bổ sung.

| Ngày | Đề / bộ câu | D.I | D.II | D.III | D.IV | Tổng | Ghi chú |
|---|---|---|---|---|---|---|---|
| | Đề đo nền (Exam 1 trong sách) | /22 | /27 | /26 | /25 | /100 | |

Phân loại lỗi để biết cách sửa:

- **K (Knowledge):** không biết kiến thức. Cách sửa: đọc lại tóm tắt và thêm flashcard.
- **R (Read):** đọc sai câu hỏi, bỏ sót từ "NOT", "FIRST", "BEST", "MOST". Cách sửa: tập gạch chân từ khóa.
- **F (Framework):** nhầm khung hoặc vai trò (ví dụ nhầm nghĩa vụ provider với deployer, hoặc nhầm NIST với ISO). Cách sửa: ôn bảng so sánh.
