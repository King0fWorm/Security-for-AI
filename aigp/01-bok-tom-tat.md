# Tóm tắt AIGP Body of Knowledge v2.1 (tiếng Việt)

> BoK v2.1, phê duyệt 9/9/2025, hiệu lực 2/2/2026. File này tóm tắt **cần nắm gì** cho từng nhóm năng lực (competency) và chỉ ra **bẫy thường gặp**. Thuật ngữ gốc tiếng Anh được giữ nguyên trong ngoặc vì đề thi bằng tiếng Anh.
>
> Ký hiệu: ⭐ = trọng tâm hay ra đề. ⚠️ = nội dung luật có thể đã thay đổi sau thời điểm soạn, cần kiểm tra nguồn gốc trước khi thi.

## Cách đọc BoK

- **Competency** là nhóm kiến thức lớn (ví dụ I.A). **Performance indicator** là từng việc cụ thể bạn phải làm được. Câu hỏi thi được viết dựa trên performance indicator.
- **Động từ** đầu mỗi indicator cho biết mức độ câu hỏi theo Bloom: *Know/Understand/Identify* là nhớ và hiểu, *Apply/Perform/Evaluate/Create* là câu tình huống. IAPP chủ yếu hỏi ở mức hiểu và áp dụng/phân tích.
- IAPP dùng "developer" và "deployer" để **mô tả công việc**, không phải để gán trách nhiệm pháp lý. Nhiều tổ chức đóng cả hai vai trò.

---

## Domain I: Nền tảng quản trị AI (16 đến 20 câu)

### I.A. AI là gì và vì sao cần quản trị (4 đến 6 câu)

**Định nghĩa** ⭐
- Định nghĩa phổ biến nhất là của **OECD** (cập nhật 2023), được EU AI Act dùng gần như nguyên văn: *hệ thống dựa trên máy, với mục tiêu rõ ràng hoặc ngầm định, suy luận từ đầu vào để tạo ra đầu ra như dự đoán, nội dung, khuyến nghị hoặc quyết định có thể tác động tới môi trường vật lý hoặc ảo; các hệ thống khác nhau về mức độ tự chủ và khả năng thích ứng sau triển khai.*
- Các loại AI: narrow AI và general AI; machine learning (supervised, unsupervised, reinforcement learning); deep learning và neural network; generative AI; foundation model / general-purpose AI model; **agentic AI** (hệ thống tự lập kế hoạch và hành động qua công cụ); hệ chuyên gia (rule-based).

**Rủi ro và tác hại**, theo 3 nhóm của NIST AI RMF:
- **Cá nhân và nhóm:** phân biệt đối xử, xâm phạm quyền dân sự, mất cơ hội kinh tế (việc làm, tín dụng), an toàn thân thể, quyền riêng tư.
- **Tổ chức:** rủi ro pháp lý, uy tín, tài chính, vận hành, an ninh.
- **Xã hội và hệ sinh thái:** thông tin sai lệch, tác động tới dân chủ, môi trường (năng lượng), chuỗi cung ứng, tập trung quyền lực.
- BoK nêu ví dụ: lệch mục tiêu (misalignment), rủi ro đạo đức và thiên lệch (bias), độ phức tạp và khả năng mở rộng.

**Đặc điểm riêng khiến AI cần quản trị toàn diện** ⭐ (thuộc lòng danh sách này):
complexity, **opacity** (hộp đen), **autonomy**, **speed and scale**, potential for harm or misuse, **data dependency**, và **probabilistic vs. deterministic outputs** (cùng đầu vào có thể cho đầu ra khác nhau).

**Nguyên tắc AI có trách nhiệm** ⭐: fairness; safety and reliability; privacy and security; transparency and explainability; accountability; human-centricity.

> Bẫy: *transparency* (công khai rằng có dùng AI, cách hệ thống hoạt động ở mức tổng thể) khác với *explainability* (giải thích vì sao ra một kết quả cụ thể) và *interpretability* (hiểu được cơ chế bên trong mô hình).

### I.B. Thiết lập và truyền đạt kỳ vọng của tổ chức (5 đến 7 câu)

- **Vai trò và trách nhiệm:** hội đồng quản trị, ban lãnh đạo, hội đồng/ủy ban quản trị AI, chủ sở hữu hệ thống (system owner), data science, pháp chế, privacy, security, compliance, kiểm toán nội bộ, nhân sự, mua sắm. Mô hình **3 lines of defense**: tuyến 1 là đơn vị kinh doanh và kỹ thuật, tuyến 2 là quản lý rủi ro và tuân thủ, tuyến 3 là kiểm toán nội bộ.
- **Hợp tác liên chức năng:** để hiệu quả và có đa dạng góc nhìn và chuyên môn. Đáp án đúng thường là "đưa nhiều bên liên quan vào sớm".
- **Đào tạo và nâng cao nhận thức** cho mọi bên liên quan về thuật ngữ, chiến lược, quản trị. Lưu ý EU AI Act Art. 4 bắt buộc **AI literacy** từ 2/2/2025.
- **Điều chỉnh cách tiếp cận** theo quy mô, mức trưởng thành, ngành, sản phẩm, mục tiêu và **khẩu vị rủi ro (risk tolerance)**. Không có mô hình nào áp dụng cho mọi tổ chức.
- **Phân biệt developer, provider, deployer, user** ⭐: ai thiết kế và huấn luyện, ai đưa ra thị trường dưới tên mình, ai sử dụng trong hoạt động chuyên môn, ai là người dùng cuối hoặc người chịu tác động.

### I.C. Chính sách và quy trình xuyên suốt vòng đời AI (6 đến 8 câu)

- Chính sách bao phủ **mọi giai đoạn**: đánh giá use case, quản lý rủi ro, ethics by design, thu thập và sử dụng dữ liệu, phát triển mô hình và hệ thống, huấn luyện và kiểm thử, triển khai và giám sát, tài liệu và báo cáo, quản lý sự cố.
- **Cập nhật chính sách hiện có** cho AI: privacy, security, data governance, sở hữu trí tuệ. Ưu tiên tích hợp vào chính sách sẵn có hơn là tạo hệ thống song song.
- **Rủi ro bên thứ ba** ⭐: mua sắm (đánh giá nhà cung cấp), chuỗi cung ứng (mô hình và dữ liệu bên ngoài), nhân sự, **chính sách sử dụng chấp nhận được (acceptable use policy)** cho công cụ GenAI của nhân viên.

---

## Domain II: Luật, tiêu chuẩn và khung áp dụng cho AI (19 đến 23 câu)

### II.A. Luật bảo vệ dữ liệu hiện hành áp dụng cho AI (4 đến 6 câu)

Bạn đã vững GDPR, nên tập trung vào **điểm giao với AI**:

| Yêu cầu | Áp dụng cho AI như thế nào |
|---|---|
| Minh bạch, lựa chọn | Thông báo việc dùng dữ liệu cá nhân để huấn luyện và cho quyết định tự động |
| **Lawful basis** | Huấn luyện thường dựa trên *legitimate interest* (cần balancing test) hoặc *consent*. Dữ liệu cào từ web vẫn là dữ liệu cá nhân |
| **Purpose limitation** | Dùng lại dữ liệu khách hàng để huấn luyện mô hình là mục đích mới, cần đánh giá tương thích |
| **Data minimization**, privacy by design | Mâu thuẫn với "càng nhiều dữ liệu càng tốt". Giải pháp: PETs (differential privacy, federated learning, dữ liệu tổng hợp, pseudonymization) |
| **DPIA** | Bắt buộc khi xử lý có rủi ro cao, gần như luôn áp dụng cho AI xử lý dữ liệu cá nhân quy mô lớn |
| Processor bên thứ ba | Hợp đồng DPA với nhà cung cấp AI. Kiểm tra nhà cung cấp có dùng dữ liệu của bạn để huấn luyện không |
| Chuyển dữ liệu xuyên biên giới | SCCs, adequacy, EU-US Data Privacy Framework |
| Quyền chủ thể dữ liệu | Truy cập, xóa (khó với dữ liệu đã nằm trong trọng số mô hình), phản đối |
| **Art. 22 GDPR** ⭐ | Quyền không chịu quyết định *chỉ dựa trên* xử lý tự động có hiệu lực pháp lý hoặc tác động đáng kể. Ngoại lệ: hợp đồng, luật cho phép, đồng ý rõ ràng. Phải có can thiệp của con người, quyền bày tỏ quan điểm và phản đối quyết định |
| Sự cố, thông báo vi phạm, lưu hồ sơ | 72 giờ báo cơ quan giám sát. Records of processing |
| **Dữ liệu nhạy cảm** | Art. 9 (sức khỏe, sinh trắc học để định danh, chủng tộc...). Ở Mỹ: **Illinois BIPA** (sinh trắc học, có quyền khởi kiện cá nhân) |

### II.B. Các luật khác áp dụng cho AI (4 đến 6 câu)

- **Sở hữu trí tuệ:** tranh chấp bản quyền về dữ liệu huấn luyện (Mỹ: lập luận fair use; EU: ngoại lệ text and data mining theo DSM Directive Art. 4, chủ sở hữu có quyền **opt-out**). Ở Mỹ, đầu ra do AI tạo ra không có tác giả là con người thì không được bảo hộ bản quyền. Sáng chế phải có nhà sáng chế là con người (vụ DABUS).
- **Chống phân biệt đối xử** ⭐: tuyển dụng (Title VII, ADA, EEOC; *disparate impact* áp dụng ngay cả khi không có ý định phân biệt), tín dụng (**ECOA/Regulation B**: thông báo từ chối phải nêu lý do cụ thể, kể cả khi dùng mô hình phức tạp; **FCRA**), nhà ở (Fair Housing Act), bảo hiểm.
- **Bảo vệ người tiêu dùng:** **FTC Act Section 5** cấm hành vi *unfair or deceptive*. Ví dụ: tuyên bố sai về năng lực AI ("AI washing"). FTC từng buộc xóa cả dữ liệu lẫn mô hình huấn luyện từ dữ liệu thu thập trái phép (**algorithmic disgorgement**) và cấm Rite Aid dùng nhận diện khuôn mặt.
- **Trách nhiệm sản phẩm:** lỗi thiết kế, lỗi sản xuất, thiếu cảnh báo. EU **Product Liability Directive mới (2024/2853)** coi phần mềm, kể cả AI, là "sản phẩm". ⚠️ Đề xuất AI Liability Directive của EU đã bị rút năm 2025.

### II.C. Các yếu tố chính của luật chuyên về AI (6 đến 8 câu) ⭐⭐

#### EU AI Act (Regulation (EU) 2024/1689)

**Phân loại rủi ro**, phải thuộc lòng:

| Mức | Ví dụ | Hệ quả |
|---|---|---|
| **Cấm (Art. 5)** | Kỹ thuật thao túng/tiềm thức gây hại; khai thác điểm yếu (tuổi, khuyết tật, hoàn cảnh kinh tế xã hội); **chấm điểm xã hội**; dự đoán tội phạm chỉ dựa trên profiling; **cào ảnh khuôn mặt không có mục tiêu** để xây cơ sở dữ liệu nhận diện; **nhận diện cảm xúc ở nơi làm việc và trường học** (trừ lý do y tế, an toàn); phân loại sinh trắc học để suy ra thông tin nhạy cảm (chủng tộc, chính kiến, tôn giáo, xu hướng tình dục...); **nhận diện sinh trắc học từ xa theo thời gian thực** ở nơi công cộng cho mục đích thực thi pháp luật (có ngoại lệ hẹp) | Cấm hoàn toàn |
| **Rủi ro cao** | **Annex I:** thành phần an toàn của sản phẩm thuộc luật hài hòa EU (máy móc, thiết bị y tế, đồ chơi...). **Annex III:** sinh trắc học; hạ tầng trọng yếu; giáo dục; **việc làm và quản lý lao động**; tiếp cận dịch vụ thiết yếu (**chấm điểm tín dụng**, phúc lợi công, định giá bảo hiểm nhân thọ và sức khỏe, phân loại cuộc gọi khẩn cấp); thực thi pháp luật; di cư và biên giới; tư pháp và quy trình dân chủ | Bộ nghĩa vụ đầy đủ (bên dưới) |
| **Rủi ro hạn chế (minh bạch, Art. 50)** | Chatbot; nội dung tổng hợp; deepfake; nhận diện cảm xúc và phân loại sinh trắc học (không thuộc loại bị cấm) | Nghĩa vụ thông báo và gắn nhãn |
| **Rủi ro tối thiểu** | Lọc spam, AI trong game | Không có nghĩa vụ bắt buộc, khuyến khích bộ quy tắc tự nguyện |

> Bẫy: **Art. 6(3)**: hệ thống trong Annex III *không* bị coi là rủi ro cao nếu chỉ làm tác vụ thủ tục hẹp, cải thiện kết quả công việc con người đã làm, phát hiện mẫu mà không thay thế đánh giá của con người, hoặc là tác vụ chuẩn bị. **Ngoại trừ**: nếu hệ thống thực hiện profiling cá nhân thì **luôn** là rủi ro cao. Provider phải lập hồ sơ cho đánh giá này.

**Nghĩa vụ của provider với hệ thống rủi ro cao** ⭐
- Hệ thống quản lý rủi ro trong suốt vòng đời (Art. 9)
- Dữ liệu và quản trị dữ liệu: dữ liệu liên quan, đại diện, kiểm tra bias (Art. 10)
- Tài liệu kỹ thuật theo Annex IV (Art. 11)
- Ghi log tự động (Art. 12)
- Minh bạch và **hướng dẫn sử dụng (instructions for use)** cho deployer (Art. 13)
- **Thiết kế để con người giám sát được** (Art. 14)
- Độ chính xác, độ bền vững (robustness), an ninh mạng (Art. 15)
- **Hệ thống quản lý chất lượng (QMS)** (Art. 17)
- **Đánh giá sự phù hợp (conformity assessment)**, tuyên bố hợp chuẩn EU, **gắn dấu CE**, đăng ký vào cơ sở dữ liệu EU
- **Giám sát sau khi đưa ra thị trường (post-market monitoring)** (Art. 72), báo cáo **sự cố nghiêm trọng** (Art. 73)

**Nghĩa vụ của deployer với hệ thống rủi ro cao (Art. 26)** ⭐
- Sử dụng theo hướng dẫn của provider
- Giao giám sát cho người có năng lực, được đào tạo và có thẩm quyền
- Đảm bảo dữ liệu đầu vào phù hợp (nếu deployer kiểm soát đầu vào)
- Giám sát vận hành, báo provider khi có rủi ro hoặc sự cố
- Lưu log ít nhất 6 tháng
- Thông báo cho người lao động trước khi dùng AI rủi ro cao tại nơi làm việc
- Thông báo cho cá nhân chịu quyết định từ hệ thống. Cá nhân có **quyền được giải thích** (Art. 86)
- **Đánh giá tác động quyền cơ bản (FRIA, Art. 27)**: bắt buộc với cơ quan công quyền, đơn vị tư nhân cung cấp dịch vụ công, và deployer dùng AI chấm điểm tín dụng hoặc định giá bảo hiểm nhân thọ và sức khỏe

**Vai trò khác**
- **Importer** (đưa hệ thống của provider ngoài EU vào EU) và **distributor**: kiểm tra provider đã làm conformity assessment, có dấu CE, tài liệu.
- **Deployer, importer hay distributor trở thành provider (Art. 25)** ⭐ nếu: gắn tên hoặc thương hiệu của mình lên hệ thống rủi ro cao, **sửa đổi đáng kể (substantial modification)**, hoặc **thay đổi mục đích sử dụng** khiến hệ thống trở thành rủi ro cao.

**Mô hình AI đa dụng (GPAI)** ⭐
- Mọi provider GPAI (Art. 53): tài liệu kỹ thuật; cung cấp thông tin cho provider ở hạ nguồn; **chính sách tuân thủ bản quyền** (tôn trọng opt-out TDM); **công bố bản tóm tắt nội dung dữ liệu huấn luyện** theo mẫu của AI Office.
- Mô hình mã nguồn mở được miễn một số nghĩa vụ, **trừ** chính sách bản quyền và bản tóm tắt dữ liệu huấn luyện (và không được miễn nếu có rủi ro hệ thống).
- **GPAI có rủi ro hệ thống** (Art. 51, 55): được suy định khi lượng tính toán huấn luyện **> 10^25 FLOPs**. Nghĩa vụ thêm: đánh giá mô hình kể cả kiểm thử đối kháng (adversarial testing/red teaming), đánh giá và giảm thiểu rủi ro hệ thống, báo cáo sự cố nghiêm trọng, an ninh mạng.
- **Code of Practice cho GPAI** (công bố tháng 7/2025) là công cụ tự nguyện để chứng minh tuân thủ.

**Mốc thời gian**
- 1/8/2024: có hiệu lực
- **2/2/2025**: lệnh cấm (Art. 5) và AI literacy (Art. 4)
- **2/8/2025**: nghĩa vụ GPAI, cơ cấu quản trị, chế tài
- **2/8/2026**: phần lớn quy định còn lại, gồm rủi ro cao theo Annex III và minh bạch Art. 50
- **2/8/2027**: rủi ro cao theo Annex I; GPAI đã lưu hành trước 2/8/2025 phải tuân thủ
- ⚠️ Gói **Digital Omnibus** (Ủy ban châu Âu đề xuất cuối 2025) đề xuất lùi hạn cho rủi ro cao. Cần kiểm tra tình trạng thông qua trước khi thi. IAPP thường hỏi theo nội dung luật đã được thông qua.

**Chế tài** ⭐
| Vi phạm | Mức phạt tối đa (lấy mức **cao hơn**; với SME lấy mức **thấp hơn**) |
|---|---|
| Thực hành bị cấm | **35 triệu EUR hoặc 7%** doanh thu toàn cầu |
| Phần lớn nghĩa vụ khác | **15 triệu EUR hoặc 3%** |
| Cung cấp thông tin sai, không đầy đủ cho cơ quan chức năng | **7,5 triệu EUR hoặc 1%** |
| Provider GPAI (do Ủy ban áp dụng) | 15 triệu EUR hoặc 3% |

Cơ quan thực thi: **cơ quan giám sát thị trường quốc gia** (market surveillance authorities), **AI Office** (thuộc Ủy ban châu Âu, giám sát GPAI), **European AI Board**, scientific panel, advisory forum. Có cơ chế **regulatory sandbox**.

#### Luật AI cơ bản của Hàn Quốc (AI Basic Act) ⚠️

- Tên đầy đủ: *Framework Act on the Development of Artificial Intelligence and the Establishment of a Foundation for Trust*. Thông qua tháng 12/2024, **có hiệu lực 22/1/2026**. Đây là luật AI toàn diện thứ hai sau EU.
- **"High-impact AI"** là AI trong lĩnh vực có tác động lớn tới tính mạng, an toàn, quyền cơ bản (năng lượng, y tế, tuyển dụng, cho vay, giao thông...). Nghĩa vụ: quản lý rủi ro, giải thích, bảo vệ người dùng, giám sát của con người, lưu tài liệu.
- **Generative AI**: thông báo trước cho người dùng và **gắn nhãn đầu ra**.
- Doanh nghiệp nước ngoài vượt ngưỡng phải chỉ định **đại diện trong nước**.
- Mức phạt hành chính tương đối thấp (tối đa khoảng 30 triệu KRW), có thời gian ân hạn.
- So với EU: phạm vi tương tự (dựa trên rủi ro) nhưng **chế tài nhẹ hơn nhiều** và thiên về thúc đẩy phát triển ngành.

#### Luật AI ở Mỹ áp dụng cho khu vực tư nhân ⚠️

Mỹ chưa có luật AI liên bang toàn diện. Cần biết:
- **Colorado AI Act (SB 24-205)**: hệ thống AI rủi ro cao đưa ra *quyết định hệ trọng (consequential decisions)*. Developer và deployer có **nghĩa vụ cẩn trọng hợp lý** để tránh phân biệt đối xử bằng thuật toán; deployer phải có chương trình quản lý rủi ro, **đánh giá tác động hằng năm**, thông báo cho người tiêu dùng. Ngày hiệu lực đã lùi tới **30/6/2026**. Tuân thủ NIST AI RMF hoặc ISO 42001 là căn cứ để bảo vệ (affirmative defense).
- **NYC Local Law 144**: công cụ quyết định tuyển dụng tự động (AEDT) phải được **kiểm toán bias hằng năm bởi bên độc lập**, công bố kết quả, thông báo cho ứng viên trước 10 ngày làm việc.
- **Utah AI Policy Act**: công bố khi người tiêu dùng tương tác với GenAI.
- Các luật mới đáng chú ý: Illinois (sửa Human Rights Act về AI trong tuyển dụng, từ 1/1/2026), Texas TRAIGA (từ 1/1/2026), California (quy định ADMT theo CCPA, SB 53 về minh bạch AI tiên phong).

### II.D. Tiêu chuẩn và công cụ của ngành (3 đến 5 câu) ⭐

**OECD AI Principles** (2019, cập nhật 2024)
- **5 nguyên tắc dựa trên giá trị:** (1) tăng trưởng bao trùm, phát triển bền vững và hạnh phúc; (2) tôn trọng pháp quyền, nhân quyền, giá trị dân chủ, kể cả công bằng và quyền riêng tư; (3) minh bạch và giải thích được; (4) bền vững, an ninh và an toàn; (5) trách nhiệm giải trình.
- **5 khuyến nghị cho nhà hoạch định chính sách:** đầu tư R&D; hệ sinh thái AI bao trùm; môi trường chính sách liên thông; năng lực con người và chuyển đổi thị trường lao động; hợp tác quốc tế.
- **OECD Framework for the Classification of AI Systems:** 5 chiều: People & Planet; Economic Context; Data & Input; AI Model; Task & Output.

**NIST AI Risk Management Framework 1.0** (1/2023) và Playbook
- **4 chức năng cốt lõi:** **GOVERN** (xuyên suốt, nền tảng văn hóa và chính sách), **MAP** (xác định bối cảnh và rủi ro), **MEASURE** (đo lường, phân tích, theo dõi), **MANAGE** (ưu tiên và xử lý rủi ro). Gồm 19 category và 72 subcategory (Govern 6, Map 5, Measure 4, Manage 4).
- **7 đặc tính của AI đáng tin cậy:** valid and reliable (nền tảng); safe; secure and resilient; accountable and transparent (bao trùm); explainable and interpretable; privacy-enhanced; fair with harmful bias managed.
- **Playbook**: gợi ý hành động cho từng subcategory, **tự nguyện, không phải checklist**.
- **Generative AI Profile (NIST AI 600-1, 7/2024)**: 12 rủi ro riêng của GenAI (confabulation, CBRN, nội dung độc hại, quyền riêng tư, môi trường, sở hữu trí tuệ...).

> Bẫy: NIST AI RMF là **tự nguyện, không chứng nhận được**. ISO/IEC 42001 thì **chứng nhận được**.

**Tiêu chuẩn ISO cốt lõi**
| Tiêu chuẩn | Nội dung | Ghi nhớ |
|---|---|---|
| **ISO/IEC 22989** (2022) | Khái niệm và **thuật ngữ** AI | "Từ điển chung" |
| **ISO/IEC 42001** (2023) | **Hệ thống quản lý AI (AIMS)** theo cấu trúc chung của ISO (điều khoản 4 đến 10, chu trình PDCA), Annex A gồm các biện pháp kiểm soát | **Chứng nhận được**, tương tự ISO 27001 cho AI. Bản PDF có trong repo |
| **ISO/IEC 42005** (2025) | Hướng dẫn **đánh giá tác động của hệ thống AI** (AI system impact assessment) lên cá nhân, nhóm, xã hội | Tác động lên con người, khác với đánh giá rủi ro cho tổ chức |
| (đọc thêm) ISO/IEC 23894 | Hướng dẫn quản lý rủi ro AI, dựa trên ISO 31000 | |

---

## Domain III: Quản trị phát triển AI (21 đến 25 câu)

Domain này phù hợp với kinh nghiệm security của bạn. Câu hỏi chủ yếu dạng tình huống "bước tiếp theo tốt nhất là gì".

### III.A. Quản trị thiết kế và xây dựng (6 đến 8 câu)

- **Xác định bối cảnh kinh doanh và use case** trước. Câu hỏi đầu tiên luôn là *có cần AI không* và *AI có phù hợp không*.
- **Đánh giá tác động** (impact assessment) **trước khi** xây dựng, cập nhật khi có thay đổi.
- Áp dụng chính sách vào thiết kế: mục đích, thu thập yêu cầu, lựa chọn kiến trúc và mô hình, giám sát của con người, phân tích dữ liệu, **chọn metric và ngưỡng**, lấy ý kiến bên liên quan, kiểm soát vận hành.
- **Quản lý rủi ro** ⭐: **ma trận xác suất × mức độ nghiêm trọng**; **hệ thống phân cấp giảm thiểu rủi ro** (avoid → minimize/mitigate → transfer → accept, ưu tiên loại bỏ rủi ro từ thiết kế); **stakeholder mapping**; đánh giá use case; benchmarking; **thử nghiệm thí điểm trước triển khai** (pilot).
- **Lập hồ sơ** quá trình thiết kế để chứng minh tuân thủ.

### III.B. Quản trị dữ liệu huấn luyện và kiểm thử (6 đến 8 câu)

- **Data governance:** đánh giá và ghi lại **quyền hợp pháp** để thu thập và sử dụng dữ liệu (privacy, bản quyền, hợp đồng); chất lượng, số lượng, tính toàn vẹn, **phù hợp mục đích (fit-for-purpose)**.
- **Data lineage** (dữ liệu đi qua những bước xử lý nào) khác với **data provenance** (dữ liệu đến từ đâu, ai tạo, quyền sử dụng). ⭐
- **Các loại kiểm thử:** unit, integration, validation, performance, **security** (adversarial, prompt injection, data poisoning), **bias/fairness**, **interpretability**.
- Tách bộ dữ liệu train, validation, test; tránh rò rỉ dữ liệu (data leakage); overfitting và underfitting.
- **Tài liệu:** **datasheets for datasets**, **model cards**, nhật ký kiểm thử để kiểm chứng kết quả.

### III.C. Quản trị phát hành, giám sát và bảo trì (8 đến 10 câu) ⭐

- **Sẵn sàng phát hành:** model card, đáp ứng **conformity assessment** (EU AI Act).
- **Giám sát liên tục** và lịch bảo trì, cập nhật, **huấn luyện lại**.
- **Đánh giá định kỳ:** audit, **red teaming**, **threat modeling**, kiểm thử bảo mật.
- **Quản lý sự cố**, ghi lại vấn đề và rủi ro.
- **Nguyên nhân sự cố AI** (thuộc lòng): brittleness (dễ vỡ), lack of robustness, dữ liệu kém chất lượng, kiểm thử không đủ, **model drift / data drift**. *Data drift* là phân phối đầu vào thay đổi; *concept drift* là quan hệ giữa đầu vào và đầu ra thay đổi.
- **Công bố để đáp ứng nghĩa vụ minh bạch:** tài liệu kỹ thuật, **hướng dẫn sử dụng cho deployer**, **kế hoạch giám sát sau khi đưa ra thị trường**.

---

## Domain IV: Quản trị triển khai và sử dụng AI (21 đến 25 câu)

Áp dụng cho mọi bối cảnh: tự triển khai mô hình của mình hoặc dùng mô hình của bên thứ ba.

### IV.A. Các yếu tố và rủi ro khi quyết định triển khai (6 đến 8 câu)

- **Bối cảnh use case:** mục tiêu kinh doanh, yêu cầu hiệu năng, dữ liệu sẵn có, cân nhắc đạo đức, **mức sẵn sàng của nhân sự**.
- **Các loại mô hình** ⭐: classic (dự đoán, phân loại) và **generative**; **proprietary** và **open source** (open weights: kiểm soát cao hơn nhưng tự chịu trách nhiệm về bảo mật và cập nhật); nhỏ và lớn (SLM chi phí thấp, chạy tại chỗ); chỉ ngôn ngữ và **multimodal**.
- **Phương án triển khai** ⭐: **cloud**, **on-premise**, **edge**; dùng nguyên bản, **fine-tuning** (thay đổi trọng số, tốn kém, có thể thành "substantial modification"), **RAG** (bổ sung kiến thức từ nguồn bên ngoài lúc chạy, giảm hallucination, dễ cập nhật, rủi ro rò rỉ dữ liệu theo quyền truy cập), **kiến trúc agentic** (tự chủ cao, rủi ro về hành động không mong muốn, quyền truy cập công cụ, cần giới hạn quyền và giám sát của con người).

### IV.B. Đánh giá hệ thống AI trước khi dùng (5 đến 7 câu)

- **Đánh giá tác động** trên hệ thống đã chọn (DPIA, FRIA, đánh giá theo ISO 42005, đánh giá thuật toán).
- **Điều khoản hợp đồng với nhà cung cấp** ⭐: nhà cung cấp có dùng dữ liệu của bạn để huấn luyện không; quyền sở hữu đầu vào và đầu ra; **bồi hoàn về sở hữu trí tuệ (IP indemnification)**; giới hạn trách nhiệm; SLA và hiệu năng; quyền kiểm toán; thông báo sự cố; **thông báo khi mô hình thay đổi**; bảo mật và nơi lưu dữ liệu; chuyển giao và chấm dứt hợp đồng.
- **Tự triển khai mô hình riêng**: nhiều cơ hội (kiểm soát, tùy biến) nhưng **nghĩa vụ nhiều hơn và trách nhiệm pháp lý cao hơn** (có thể trở thành provider).

### IV.C. Quản trị triển khai và sử dụng (9 đến 11 câu, nhiều nhất đề) ⭐

- Áp dụng chính sách khi triển khai: quản trị dữ liệu, quản lý rủi ro, quản lý vấn đề, **đào tạo người dùng**.
- **Giám sát liên tục** và lịch bảo trì, cập nhật, huấn luyện lại.
- **Đánh giá định kỳ:** audit, red teaming, threat modeling, kiểm thử bảo mật.
- **Ghi lại** sự cố, vấn đề, rủi ro và kế hoạch giám sát sau khi đưa ra thị trường.
- **Dự báo và giảm rủi ro do sử dụng ngoài mục đích (secondary/unintended use)** và tác hại ở hạ nguồn.
- **Kế hoạch truyền thông ra bên ngoài** (khách hàng, cơ quan quản lý, công chúng khi có sự cố).
- **Chính sách và biện pháp kiểm soát để tắt (deactivate) hoặc khoanh vùng (localize) hệ thống** ⭐ khi cần, do yêu cầu pháp lý (ví dụ tắt một tính năng tại một quốc gia) hoặc do hiệu năng kém. Cần có kế hoạch dự phòng (fallback) và quy trình rollback.

---

## Mẹo làm bài

1. **Đọc câu hỏi trước, đọc case study sau** để biết cần tìm gì.
2. Gạch chân từ khóa: **FIRST, BEST, MOST, PRIMARY, NOT, EXCEPT**. Câu "bước đầu tiên" thường có đáp án là *hiểu bối cảnh / làm đánh giá / xác định use case* hơn là *triển khai biện pháp kỹ thuật*.
3. Xác định **vai trò** của tổ chức trong câu hỏi (provider hay deployer, controller hay processor) **trước khi** chọn nghĩa vụ.
4. Ưu tiên đáp án **có tính hệ thống, dựa trên rủi ro, liên chức năng và có lưu hồ sơ** hơn đáp án tuyệt đối ("luôn luôn", "không bao giờ", "loại bỏ hoàn toàn").
5. Không bỏ trống câu nào. Phân bổ thời gian khoảng 1,6 phút mỗi câu, chừa 20 phút để xem lại.
