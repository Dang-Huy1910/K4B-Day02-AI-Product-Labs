# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Đặng Quang Huy | 2A202602962 | Facilitator / AI Product Engineer (Trưởng nhóm & Thiết kế giải pháp kỹ thuật) |
| 2   | Thành viên 2 (Long NH) | 2A202601845 | Workflow & Operations Designer (Khảo sát quy trình nghiệp vụ BQL) |
| 3   | Thành viên 3 (Đức TM) | 2A202603120 | Market & Solution Researcher (Nghiên cứu thị trường & Benchmarking) |
| 4   | Thành viên 4 (Trang LT) | 2A202602418 | Quality & Documentation Lead (Quản lý chất lượng & Thư ký tổng hợp) |

**Candidate problem nhóm chọn (1 câu):**
Tự động phân loại danh mục phòng ban, nhận diện sự cố khẩn cấp cấp độ P1 và soạn nháp tin nhắn phản hồi tiếp nhận phản ánh cư dân trên App Vinhomes Resident.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Huy ĐQ | Triage & Dispatch ticket phản ánh cư dân trên App Vinhomes Resident | Lễ tân / CSKH BQL tòa nhà | Đọc hiểu mô tả tự do, phân loại phòng ban & gán nhãn P1-P3 (12/17 phút/ticket) | Bài toán kinh điển, dữ liệu nhiều, ROI cực cao, ranh giới rõ ràng. |
| 2 | Huy ĐQ | Thẩm định hồ sơ bản vẽ đăng ký thi công nội thất căn hộ | Kỹ sư MEP/Xây dựng BQL | Đọc đối chiếu từng trang PDF bản vẽ với 25 quy chuẩn PCCC (3-5 ngày) | Giá trị thực tế cao nhưng xử lý bản vẽ kỹ thuật CAD/PDF rất phức tạp cho bài lab. |
| 3 | Huy ĐQ | Xử lý vi phạm đỗ xe trái phép trong đại đô thị bằng OCR | Bảo vệ tuần tra, Cư dân | Tra cứu thủ công biển số trên danh sách Excel để gọi điện thoại (20-25 phút) | Hay, thực tế, nhưng quy mô ảnh hưởng hẹp hơn bài Triage cư dân. |
| 4 | Long NH | Tự động hóa báo cáo giao ban kỹ thuật ca trực MEP hằng ngày | Kỹ sư trưởng ca BQL | Gom số liệu từ 8 sổ tay hiện trường và nhóm chat Zalo vào file Excel (60-90 phút) | Mang tính nghiệp vụ nội bộ, ít ảnh hưởng trực tiếp đến trải nghiệm cư dân. |
| 5 | Long NH | Giám sát và phát hiện sớm rò rỉ nước/điện công cộng tòa nhà | Kỹ thuật tòa nhà | Đợi đồng hồ cơ chốt số cuối tháng mới phát hiện thất thoát | Phụ thuộc cảm biến IoT phần cứng, khó làm trong phạm vi phần mềm/AI. |
| 6 | Long NH | Quản lý và kiểm kê tài sản công cộng và vật tư kho BQL | Thủ kho, Kế toán BQL | Đếm và đối chiếu vật tư bảo trì thủ công định kỳ | Bài toán ERP/quản lý kho thuần túy, Rule/Database giải quyết tốt, không cần AI. |
| 7 | Đức TM | Trợ lý ảo giải đáp quy chế, nội quy đô thị và tiện ích ngoài giờ | Cư dân, Trực ban hotline | Chatbot bấm phím cứng nhắc, cư dân gọi dồn hotline đêm | Rất tiềm năng, nhưng rủi ro AI "ảo giác" (hallucination) cam kết sai quy chế với cư dân. |
| 8 | Đức TM | Điều phối và giải tỏa xe xăng chiếm trụ sạc xe điện V-Green | Tài xế Xanh SM, Chủ xe điện | Chờ bảo vệ xuống kiểm tra và liên hệ chủ xe (30-45 phút) | Pain point thực tế của hệ sinh thái VinFast/Xanh SM, nhưng phụ thuộc vào camera hầm. |
| 9 | Đức TM | Tự động hóa đặt lịch khám và phân luồng sơ bộ bệnh nhân Vinmec | Lễ tân bệnh viện, Bệnh nhân | Phân loại chuyên khoa dựa trên triệu chứng tự kể | Rủi ro y tế quá cao (High-risk Health domain), không phù hợp thử nghiệm nhanh. |
| 10 | Trang LT | Lọc và giảm báo động giả từ Camera AI an ninh đô thị (IOC) | Nhân viên giám sát IOC | 65% cảnh báo là lá cây/bóng động vật gây mệt mỏi cảnh báo | Cần can thiệp vào tầng Computer Vision của camera, nhóm khó tiếp cận model gốc. |
| 11 | Trang LT | Tổng hợp và phân tích báo cáo đo lường hài lòng cư dân (CSAT) | Giám đốc Vận hành | Đọc và phân loại hàng nghìn khảo sát text mở cuối mỗi quý | Tần suất chỉ theo quý (3 tháng/lần), không giải quyết được áp lực hằng ngày. |
| 12 | Trang LT | Rà soát và đối soát hợp đồng cho thuê mặt bằng Shophouse | Pháp chế, Chuyên viên cho thuê | Đọc rà soát điều khoản phạt và gia hạn trên hợp đồng giấy | Khối lượng hợp đồng không quá lớn (chỉ vài trăm hợp đồng/khu), chưa đủ nghẽn. |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A: Customer Service & Ticket Operations** | #1, #4, #7, #11 | Tiếp nhận ngôn ngữ tự nhiên từ cư dân/nội bộ, phân loại danh mục, điều phối công việc và phản hồi thông tin. | Cụm có khối lượng công việc lặp lại lớn nhất, dữ liệu văn bản phong phú, AI phát huy giá trị cao nhất. |
| **B: Technical Compliance & Document Review** | #2, #12 | Đọc hiểu tài liệu có cấu trúc/bản vẽ kỹ thuật và đối chiếu với bộ quy chuẩn cố định. | Phức tạp về định dạng đầu vào (PDF nhiều trang, bản vẽ thiết kế), cần mô hình chuyên sâu. |
| **C: Physical Operations & Smart Mobility** | #3, #5, #8, #10 | Nhận diện thực địa (Computer Vision, Camera, Biển số xe, Cảm biến phần cứng) để can thiệp trật tự đô thị. | Phụ thuộc nhiều vào thiết bị phần cứng hiện trường và đường truyền camera. |
| **D: Administrative & Internal ERP** | #6, #9 | Quản lý kho, đặt lịch hành chính, biểu mẫu nội bộ. | Giải pháp phần mềm truyền thống (Rule-based / SQL) giải quyết tốt hơn AI. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **Candidate 1: Vinhomes Resident Triage & Dispatch AI** | 1. Tần suất cực cao (1.500–3.500 ticket/ngày), giá trị ROI tính được ngay.<br>2. Bottleneck phân loại & soạn nháp rất rõ ràng (chiếm 12/17 phút).<br>3. Ranh giới vận hành rõ: AI chỉ trích xuất thông tin & draft, Lễ tân duyệt trước khi gửi. | Độ chính xác khi gặp câu mô tả tiếng Việt tối nghĩa, tiếng lóng địa phương hoặc viết tắt ("hành lang t5 s2.01 mùi khét lẹt"). |
| **Candidate 2: Thẩm định hồ sơ thi công nội thất căn hộ** | 1. Pain point lớn của cư dân khi mới nhận nhà (chờ 3-5 ngày).<br>2. Bộ tiêu chuẩn PCCC và xây dựng đã có văn bản ban hành chính thức. | Mô hình Document AI có thể gặp khó khi đọc bản vẽ sơ đồ kiến trúc phức tạp hoặc scan mờ. |
| **Candidate 3: Xử lý xe đỗ trái phép & Giải tỏa trụ sạc VinFast** | 1. Giải quyết mâu thuẫn bức xúc thực tế giữa cư dân, tài xế Xanh SM và bảo vệ.<br>2. Quy trình 3 bước gọn gàng, có thể dùng OCR biển số. | Chất lượng ảnh chụp hiện trường trong hầm thiếu sáng có thể làm giảm độ nhận diện biển số. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Candidate 1 (Triage & Dispatch)** | 5 | 5 | 5 | 5 | 5 | 5 | 5 | **35** |
| **Candidate 2 (Thẩm định hồ sơ)** | 4 | 4 | 4 | 4 | 3 | 4 | 3 | **26** |
| **Candidate 3 (Đỗ xe & Trụ sạc)** | 4 | 4 | 4 | 4 | 4 | 4 | 4 | **28** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Candidate 1: Tự động phân loại danh mục sự cố, phát hiện nguy cơ khẩn cấp P1 và soạn nháp tin nhắn phản hồi tiếp nhận phản ánh của cư dân trên App Vinhomes Resident.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn Candidate 1 vì đây là bài toán có tần suất nghiệp vụ lớn nhất và gây áp lực kiệt sức trực tiếp lên đội ngũ Lễ tân BQL mỗi ngày (1.500 - 3.500 ticket/ngày/đại đô thị). 
Quy trình hiện tại có hai điểm nghẽn bằng văn bản rõ rệt (đọc phân loại phòng ban và gõ tin phản hồi), hoàn toàn khớp với thế mạnh xử lý ngôn ngữ tự nhiên của LLM. 
Hơn nữa, bài toán có ranh giới kiểm soát (Human-in-the-loop) vô cùng chặt chẽ: AI chỉ đóng vai trò trợ lý sinh bản nháp để con người bấm duyệt, triệt tiêu rủi ro gửi nhầm cho cư dân. 
Đặc biệt, việc tích hợp nhận diện sự cố khẩn cấp P1 giúp giải quyết bài toán an toàn sinh mạng và tài sản trong "15 phút vàng", mang lại giá trị vận hành và xã hội vượt trội.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Không chọn Candidate 2 (Thẩm định hồ sơ thi công): Đòi hỏi xử lý file bản vẽ kiến trúc/CAD phức tạp và tính toán tải trọng điện nước, vượt quá phạm vi và năng lực dữ liệu của một bài lab 4 tiếng. Ngoài ra, tính trách nhiệm pháp lý về kết cấu tòa nhà đòi hỏi kỹ sư công trình phải trực tiếp chịu trách nhiệm con dấu.
- Không chọn Candidate 3 (Xử lý xe đỗ sai & trụ sạc): Phụ thuộc nhiều vào góc chụp ảnh camera hiện trường và API đăng ký phương tiện của bên thứ ba, bài toán này thuần về Computer Vision và Rule-based tra bảng cơ sở dữ liệu hơn là một bài toán kết hợp Workflow + LLM điển hình.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Thành viên Trang LT và Đức TM từng bày tỏ lo ngại: Nếu cư dân nhắn tin vắn tắt kèm ảnh chụp (ví dụ ảnh chụp một vũng nước sàn hành lang) mà không viết chữ thì AI có thể phân loại sai sang đội Vệ sinh trong khi thực tế là vỡ ống nước kỹ thuật MEP.
Nhóm đã chốt giải pháp: Áp dụng cơ chế Confidence Score và Phân loại Đa phương thức (Multimodal). Nếu AI nhận diện độ tin cậy < 80% hoặc thông tin quá mơ hồ, hệ thống tự động gắn cờ [CẦN XÁC MINH] và giữ nguyên trong luồng thẩm định thủ công của Lễ tân, đảm bảo không tự động gán nhầm việc cho đội hiện trường.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| **Interview Lễ tân BQL** | 2 người (Lễ tân ca tối tòa S2 Vinhomes) | *"Khung giờ từ 18h đến 21h là kinh hoàng nhất, chuông thông báo app nhảy liên tục. Tụi em vừa phải nghe điện thoại vừa đọc tin nhắn mô tả của cư dân để gán đúng đội Thang máy hay Điện nước. Nhiều khi mệt quá gõ nhầm căn hộ là bị cư dân mắng ngay."* | Không có phản bác về sự cần thiết; chỉ lo ngại AI phản hồi tự động nghe sẽ như máy móc vô cảm. | Nhóm bổ sung yêu cầu: Bản nháp AI phải tuân thủ đúng văn phong chuẩn mực Vinhomes (kính ngữ, xưng hô tôn trọng) và bắt buộc Lễ tân bấm duyệt mới gửi. |
| **Interview Cư dân** | 3 cư dân (Tòa S1 và S2 Ocean Park) | *"Có lần bồn cầu bị rò nước nhỏ giọt, tôi gửi từ 19h mà đến 23h mới thấy tin nhắn hệ thống báo đã tiếp nhận. Biết là giờ cao điểm nhưng chờ đợi không biết BQL đã đọc chưa rất sốt ruột."* | Cư dân không quan tâm ai đọc, miễn là có người xác nhận đã nắm được sự việc và cử thợ đến đúng hẹn. | Xác định rõ giá trị của giải pháp là rút ngắn thời gian gửi tin xác nhận tiếp nhận từ 4-12 tiếng xuống dưới 2 phút. |
| **Survey nhanh cộng đồng** | 10 người (nhân viên dịch vụ & cư dân) | 9/10 người khẳng định bước "chờ lễ tân đọc và phân loại" là nút thắt gây trễ toàn bộ quy trình; 100% đồng ý sự cố khẩn cấp P1 (khét điện, kẹt thang) phải có đường dây riêng. | 1 người cho rằng chỉ cần làm form bắt cư dân chọn đúng mục là xong. | Nhóm bảo vệ lập luận: Cư dân khi hoảng loạn hoặc đang vội sẽ không chọn form đúng, form càng phức tạp tỉ lệ bỏ dở và chọn sai càng cao. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không nằm ở khâu kỹ thuật sửa chữa hiện trường, mà nằm ở "nút thắt cổ chai" tiếp nhận tại bàn lễ tân: Lễ tân bị quá tải đọc/gõ thủ công vào giờ cao điểm khiến phản ánh thông thường bị ngâm trễ hàng tiếng đồng hồ, còn sự cố khẩn cấp P1 bị chôn vùi nguy hiểm trong hàng đợi FIFO.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `02-group-problem-statement-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Zendesk Advanced AI (Intelligent Triage)** | [zendesk.com/service/ai](https://www.zendesk.com/service/ai/) | Tự động đọc ticket, phân loại ý định (intent), ngôn ngữ, và cảm xúc (sentiment) để định tuyến. | Tích hợp sâu vào CRM, xử lý hàng triệu ticket, độ trễ thấp (<2s). | Tối ưu cho Helpdesk IT/SaaS bằng tiếng Anh; chưa hiểu sâu ngôn ngữ bất động sản/đô thị Việt Nam và không có cơ chế kích hoạt cảnh báo an toàn vật lý khẩn cấp (P1 physical incident). | Cần học hỏi cách gán nhãn đa tầng (Danh mục + Mức độ khẩn cấp) và trả về JSON có cấu trúc. |
| **Freshworks Freddy AI Copilot** | [freshworks.com/freshdesk/freddy-ai](https://www.freshworks.com/freshdesk/freddy-ai/) | Hỗ trợ nhân viên CSKH tóm tắt nội dung trao đổi và soạn nháp câu trả lời phản hồi khách hàng. | Soạn văn phong lịch sự, đề xuất câu trả lời dựa trên kho tri thức (KB) nhanh chóng. | Chỉ dừng ở mức soạn thảo email/chat hỗ trợ thông thường, thiếu liên kết tự động đẩy lệnh điều phối (work order) sang bộ phận kỹ thuật hiện trường. | Giữ nguyên mô hình Copilot (Human-in-the-loop): AI chỉ soạn nháp, nhân viên kiểm tra và gửi đi. |
| **ServiceNow ITSM Incident Dispatcher** | [servicenow.com/products/itsm](https://www.servicenow.com/products/itsm.html) | Nhận diện mức độ nghiêm trọng (Major Incident P1/P2) và tự động kích hoạt cuộc gọi khẩn cấp cho đội kỹ thuật trực ban. | Quy trình phản ứng sự cố P1 cực kỳ chặt chẽ, audit log minh bạch, tuân thủ tiêu chuẩn ITIL. | Quá nặng nề và phức tạp, chi phí triển khai hàng trăm nghìn USD, không thiết kế cho giao diện app cư dân đại đô thị. | Tách riêng cơ chế "Còi báo động đỏ" (Fast-track alert) cho sự cố P1 ngay khi phát hiện từ khóa nguy hiểm. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nên xây dựng: Một lớp AI Feature nhẹ nhàng đóng vai trò Copilot cho Lễ tân, kết hợp phân loại danh mục + sinh nháp phản hồi + còi báo động P1 nhanh. 
Tuyệt đối KHÔNG xây dựng: Một hệ thống Agent tự động toàn quyền gửi tin nhắn ra ngoài hoặc tự tạo lệnh thi công mà không có con người duyệt, vì rủi ro ngôn ngữ và trách nhiệm pháp lý trong quản lý đại đô thị là rất lớn.
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png`

```text
[1. Cư dân gửi ticket: 1' - Cư dân] 
       ↓
[2. Mở hòm thư & tra cứu CRM: 2' - Lễ tân] 
       ↓
[3. Đọc, hiểu tiếng Việt, phân loại phòng ban & gán P1-P3: 7' - Lễ tân] <-- 🔴 BOTTLENECK CHÍNH
       ↓
[4. Tạo work-order chuyển giao đội hiện trường: 2' - Lễ tân] 
       ↓
[5. Gõ tin nhắn phản hồi lịch sự gửi cư dân: 5' - Lễ tân]              <-- 🔴 BOTTLENECK PHỤ
       ↓
[Cư dân nhận xác nhận tiếp nhận sau 4-12 giờ chờ hàng đợi]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| **1. Gửi ticket** | Cư dân tòa nhà | Mô tả text + ảnh chụp sự cố qua App | Ticket ghi nhận trên hệ thống | 1 phút / 1.500–3.500 ticket/ngày | Handoff #1: Cư dân → Hệ thống App Vinhomes. |
| **2. Tra cứu căn hộ** | Lễ tân / CSKH | Mã căn hộ, số điện thoại | Hồ sơ căn hộ trên CRM (chủ hộ, tầng, tòa) | 2 phút/ticket | Handoff #2: Lễ tân đối chiếu App ↔ Phần mềm CRM. |
| **3. Đọc & Phân loại** | Lễ tân / CSKH | Đoạn text tiếng Việt tự do + ảnh | Nhãn phòng ban (MEP/An ninh...) + Mức P1-P3 | **7 phút/ticket** | 🔴 **BOTTLENECK CHÍNH:** Đọc ngôn ngữ tự nhiên không chuẩn, dễ sai nhãn, sót P1. |
| **4. Gán việc đội hiện trường** | Lễ tân / CSKH | Nhãn phòng ban + Tóm tắt lỗi | Work-order trên nhóm bộ đàm/chat nội bộ | 2 phút/ticket | Handoff #3: Lễ tân → Đội kỹ thuật hiện trường. |
| **5. Soạn tin phản hồi** | Lễ tân / CSKH | Thông tin tiếp nhận + Quy chuẩn văn phong | Tin nhắn hoàn chỉnh gửi qua App | **5 phút/ticket** | 🔴 **BOTTLENECK PHỤ:** Gõ tay lặp lại, dễ nhầm tên/số căn, áp lực thời gian. |

**Bottleneck chính (2-3 câu):**

```text
Nút thắt nghiêm trọng nhất nằm ở Bước 3 và Bước 5 (chiếm tổng cộng 12/17 phút mỗi ticket). Lễ tân phải tự mình đọc hiểu các mô tả lủng củng, không dấu hoặc dùng từ ngữ địa phương, sau đó gõ tay từng câu phản hồi. Đây là nguyên nhân trực tiếp khiến hàng đợi bị dồn ứ hàng trăm ticket vào giờ cao điểm, biến thời gian chờ thực tế của cư dân từ vài phút thành 4-12 tiếng.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1. Cư dân gửi ticket qua App] 
       ↓
[2. Tự động lấy thông tin căn hộ qua CRM API: 1s - Hệ thống máy (Rule)]
       ↓
[3. Quét từ khóa nóng P1 (cháy, khét, kẹt thang): 0.5s - Bộ lọc Rule]
       │
       ├──> [NẾU LÀ P1 CỰC GẤP]: Bắn còi báo động đỏ & SMS ngay cho Trưởng ca An ninh (Fast-track)
       ↓
[4. LLM Feature phân tích text/ảnh: Trích xuất JSON phòng ban, gán P1-P3 & sinh nháp tin nhắn: 3s - AI]
       ↓
[5. Màn hình Triage: Lễ tân xem bản nháp, bấm "Phê duyệt" hoặc chỉnh sửa: 30 - 60s - Con người] <-- 🛡️ HUMAN BOUNDARY
       ↓
[6. Tự động gửi work-order hiện trường & phát tin phản hồi cho cư dân: 1s - Hệ thống máy]

Fallback: Nếu AI có điểm tin cậy (confidence score) < 80% hoặc gặp lỗi định dạng 
          --> Tự động đẩy về hàng đợi thường để Lễ tân xử lý thủ công từ đầu.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| **Tổng thời gian xử lý (khi cầm việc)** | ~17 phút / ticket | **~1 - 1.5 phút / ticket** | Đo timestamp từ lúc mở ticket đến lúc bấm gửi duyệt. |
| **Thời gian cư dân chờ phản hồi tiếp nhận** | 4 – 12 tiếng (do kẹt hàng đợi) | **< 15 phút** (90% ticket giờ hành chính) | Log hệ thống App Vinhomes Resident. |
| **Số bước thao tác thủ công** | 5 bước (toàn bộ thủ công) | **1 bước** (Lễ tân chỉ cần rà soát và bấm Duyệt) | Đếm số thao tác trên màn hình CRM. |
| **Bottleneck chính** | Đọc hiểu, phân loại & gõ tin thủ công | Thời gian Lễ tân đọc lướt bản nháp để bấm duyệt | Bấm giờ thao tác của lễ tân trên giao diện Triage. |
| **Risk mới phát sinh** | Lễ tân kiệt sức, nhầm lẫn, sót P1 | Lễ tân ỷ lại bấm duyệt nhanh mà không đọc kỹ bản nháp | Kiểm toán ngẫu nhiên (Audit log) 5% ticket mỗi tuần. |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Lễ tân và chuyên viên CSKH tại Ban Quản lý các tòa nhà Vinhomes, những người phải trực tiếp tiếp nhận và xử lý hàng đợi phản ánh của cư dân mỗi ngày. Đối tượng hưởng lợi gián tiếp là hàng chục nghìn cư dân đại đô thị và các đội kỹ thuật hiện trường. |
| **Workflow** | Cư dân gửi ticket phản ánh qua App $\to$ Lễ tân mở hệ thống tra cứu căn hộ $\to$ Đọc mô tả, tự xác định phòng ban tiếp nhận và mức độ khẩn cấp $\to$ Tạo lệnh điều phối cho kỹ thuật $\to$ Soạn thảo tin nhắn phản hồi gửi lại cư dân. |
| **Bottleneck** | Khâu đọc hiểu ngôn ngữ tự do của cư dân để phân loại phòng ban (7 phút) và khâu gõ tay tin nhắn phản hồi lịch sự (5 phút), chiếm hơn 70% tổng thời gian xử lý một yêu cầu. |
| **Impact** | Tiêu tốn 375 – 875 giờ làm việc của đội ngũ lễ tân mỗi ngày trên toàn đại đô thị. Hàng đợi bị trễ 4–12 tiếng vào giờ cao điểm, làm suy giảm nghiêm trọng chỉ số hài lòng cư dân (CSAT) và có nguy cơ trễ "15 phút vàng" đối với các sự cố an toàn P1. |
| **Success Metric** | Giảm thời gian phân loại và sinh nháp từ 12 phút xuống < 10 giây; Lễ tân duyệt trong < 60 giây. Đạt tỷ lệ phân loại đúng phòng ban $\ge$ 92% và độ nhạy phát hiện sự cố khẩn cấp P1 $\ge$ 99%. |
| **Boundary** | AI chỉ được phép đọc dữ liệu phản ánh, đề xuất phân loại danh mục, gán nhãn P1-P3 và sinh bản nháp tin nhắn phản hồi. AI tuyệt đối KHÔNG được tự động gửi tin nhắn cho cư dân khi chưa có người duyệt, không được tự đóng ticket, và không được tự động hạ cấp sự cố P1. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Boundary và Metric ban đầu chưa nêu rõ cơ chế xử lý khi AI nhận diện nhầm P1 giả hoặc bỏ sót P1 thật.
- Tôi sửa gì: Đã bổ sung ranh giới cứng: Mọi cảnh báo P1 chỉ được phép báo động cho con người (Trực ban An ninh/Kỹ thuật) đến kiểm tra thực địa, AI không được tự ý kích hoạt các thiết bị ngắt điện hay khóa cửa tự động.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: **[x] Thấp (có đúng/sai rõ)** / [ ] Cao — Vì sao: Danh mục phòng ban tiếp nhận (MEP, An ninh, Vệ sinh, Chăm sóc khách hàng) và mức độ khẩn cấp (P1, P2, P3) đã có quy chuẩn rõ ràng của Vinhomes; một phản ánh vỡ ống nước chỉ có thể là MEP P1, không thể hiểu mơ hồ sang việc khác.
- Độ phức tạp: [ ] Thấp / **[x] Cao (3+ bước/nguồn, phụ thuộc nhau)** — Vì sao: Quy trình đòi hỏi kết nối dữ liệu từ App cư dân, truy vấn CRM thông tin căn hộ, phân tích đa phương thức (vừa đọc text vừa xem ảnh chụp), phân luồng P1 và soạn thảo văn bản chuẩn hóa.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô: Workflow Automation with LLM (Quy trình nghiệp vụ cố định nhiều bước, tích hợp tính năng LLM để giải quyết khâu nhận thức ngôn ngữ tự nhiên).
```

**Vì sao (2-3 câu):**

```text
Đầu vào của bài toán là ngôn ngữ tự nhiên phi cấu trúc nên không thể dùng Rule đơn thuần. Tuy nhiên, luồng nghiệp vụ sau đó hoàn toàn cố định theo quy trình 5 bước của ban quản lý tòa nhà, không đòi hỏi AI phải tự do khám phá hay tự lập kế hoạch nhiều vòng như một Autonomous Agent.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng từ khóa (Keywords/Regex) để lọc ticket: thấy từ "cháy", "kẹt thang" $\to$ P1; thấy từ "đèn", "rác" $\to$ Kỹ thuật/Vệ sinh. | Chỉ đủ khi cư dân viết ngắn gọn, dùng đúng từ ngữ chuẩn xác trong danh từ điển định sẵn. | Bỏ sót rất nhiều trường hợp dùng từ ngữ linh hoạt ("có mùi khét ở hộp gen", "thang máy rung bần bật"), hoặc báo động giả liên tục gây tê liệt trực ban. | **Dùng làm lớp lọc trước (Pre-filter P1)**: Nếu bắt đúng từ khóa nguy hiểm cực độ $\to$ Kích hoạt chuông báo động ngay lập tức. |
| **Workflow (LLM Feature)** | Hệ thống pipeline cố định: Nhận ticket $\to$ Gọi LLM trích xuất JSON (Phòng ban, P1-P3, Tóm tắt) + Sinh nháp tin nhắn $\to$ Đưa lên giao diện cho Lễ tân bấm Duyệt. | Đủ khi mục tiêu là giải phóng 80% thời gian đọc/gõ lặp lại của con người, giữ con người ở khâu kiểm soát cuối cùng (HITL). | LLM có thể sinh ảo giác nhỏ trong câu từ hoặc đánh giá sai độ khẩn cấp khi ảnh bị mờ; tuy nhiên Lễ tân dễ dàng phát hiện và sửa lại trong vài giây. | **CHỌN LÀM GIẢI PHÁP CHÍNH**: Giải quyết hoàn hảo Bước 3 và Bước 5 mà vẫn an toàn 100%. |
| **Agent** | AI Autonomous Agent tự đọc ticket, tự gọi API CRM, tự động xuất work-order chuyển thợ, tự gửi tin cho cư dân và tự đóng ticket khi thợ báo xong. | Chỉ phù hợp trong tương lai xa khi toàn bộ hệ sinh thái đô thị đã số hóa hoàn hảo, API đồng bộ và tỷ lệ lỗi của AI tiệm cận 0. | Cực kỳ nguy hiểm: Agent có thể gửi nhầm thông tin pháp lý cho cư dân, kích động khiếu nại tập thể, hoặc tự đóng nhầm các ticket P1 nguy hiểm dẫn đến hỏa hoạn. | **LOẠI BỎ**: Vượt quá ranh giới an toàn vận hành tòa nhà, chi phí token cao, không cần thiết cho mục tiêu bài toán. |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. **Rule có giải được 70-80% case không?** Không, ngôn ngữ cư dân rất đa dạng, viết tắt, không dấu, dùng từ địa phương nên Rule chỉ bắt được khoảng 30-40% trường hợp rõ ràng.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** Quy trình đi thẳng một đường (Linear Pipeline): Nhận $\to$ Phân loại $\to$ Nháp $\to$ Duyệt $\to$ Gửi; chỉ có một nhánh rẽ duy nhất là cảnh báo khẩn cấp P1.
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?** Tuyệt đối không cần; chuỗi bước đã cố định sẵn, việc trao quyền tự quyết cho Agent chỉ làm tăng rủi ro lỗi và chi phí vận hành.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?** Lễ tân là người phát hiện ngay lập tức trên màn hình Triage trước khi bấm duyệt; việc sửa lại chỉ mất 5–10 giây bằng thao tác chọn lại dropdown.
5. **Có hạ được từ Agent → Workflow → Rule không?** Có, kiến trúc nhóm đề xuất chính là sự kết hợp tối ưu: dùng Rule để bắt từ khóa khẩn cấp cực đoan và dùng Workflow (LLM Feature) để xử lý phần còn lại.

**Mức chọn:**

```text
Workflow (LLM Feature with Human-in-the-loop)
```

**Vì sao chọn (3-4 câu):**

```text
Mức Workflow kết hợp LLM Feature là điểm cân bằng hoàn hảo giữa hiệu quả giải phóng sức lao động và mức độ an toàn vận hành. Mô hình xử lý xuất sắc bài toán hiểu ngữ nghĩa tự nhiên tiếng Việt và sinh bản nháp đúng chuẩn mực văn phong Vinhomes. Việc duy trì con người trong vòng lặp (HITL) ở khâu bấm duyệt đảm bảo trách nhiệm pháp lý và loại trừ hoàn toàn rủi ro AI phát ngôn sai lệch đến cư dân.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Không thể chỉ dùng Rule thuần túy vì văn bản phản ánh của cư dân là ngôn ngữ đời thường rất phong phú, nhiều tiếng lóng và lỗi chính tả. Nếu chỉ dùng Rule, tỷ lệ phân loại sai và bỏ sót ticket sẽ vượt quá 50%, khiến đội ngũ vận hành mất thêm thời gian đi dọn rác dữ liệu và làm trầm trọng hơn sự bức xúc của cư dân.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Lễ tân / Chuyên viên CSKH Ban Quản lý các tòa nhà Vinhomes (người trực tiếp vận hành hàng đợi tiếp nhận phản ánh mỗi ngày). |
| **Workflow** | Cư dân gửi phản ánh qua App $\to$ Hệ thống tự động liên kết dữ liệu căn hộ $\to$ AI phân loại danh mục, gán nhãn P1-P3 và sinh bản nháp phản hồi $\to$ Lễ tân kiểm tra và bấm phê duyệt trên giao diện Triage $\to$ Hệ thống tự động điều phối lệnh đến đội hiện trường và gửi tin xác nhận cho cư dân. |
| **Bottleneck** | Hai bước thủ công tốn thời gian nhất: Đọc hiểu phân loại danh mục (7 phút) và gõ tin nhắn phản hồi lịch sự cho từng căn hộ (5 phút). |
| **Impact** | Giải phóng 375 – 875 giờ làm việc/ngày trên toàn đại đô thị; rút ngắn thời gian phản hồi cư dân từ 4–12 tiếng xuống dưới 15 phút; loại bỏ nguy cơ chậm trễ trong "15 phút vàng" của sự cố an toàn P1. |
| **Success Metric** | Thời gian AI phân loại và tạo nháp < 10 giây; Lễ tân duyệt trong < 60 giây. Tỷ lệ phân loại đúng phòng ban $\ge$ 92%. Độ nhạy phát hiện sự cố khẩn cấp P1 $\ge$ 99%. Tỷ lệ phản hồi trong 15 phút đạt $\ge$ 80%. |
| **Boundary** (làm / không làm) | **LÀM:** Đọc văn bản/hình ảnh, đề xuất nhãn phòng ban, đề xuất mức P1-P3, soạn nháp tin nhắn có thẻ `[DRAFT_ONLY]`.<br>**CẤM:** Tuyệt đối không tự ý gửi tin nhắn khi chưa có con người duyệt, không tự động đóng ticket, không tự hạ cấp mức độ khẩn cấp P1, không can thiệp điều khiển thiết bị kỹ thuật tòa nhà. |
| **AI intervention point** | Can thiệp ngay sau Bước 2 (sau khi đã nạp dữ liệu căn hộ từ CRM) và ngay trước Bước 4 (trước khi Lễ tân bấm duyệt để gửi đi). |
| **Mức chọn** | **Workflow (LLM Feature + HITL)** vì quy trình 5 bước cố định, tận dụng LLM để đọc hiểu và sinh nháp, giữ con người làm chốt chặn an toàn cuối cùng. |
| **Rủi ro & người thật kiểm tra** | Rủi ro lớn nhất là Lễ tân bị hiện tượng "lơ là tự động hóa" (Automation Bias) bấm duyệt bừa khiến tin nhắn sai sót lọt đến cư dân. Người kiểm tra: Trưởng bộ phận CSKH tòa nhà thực hiện kiểm toán ngẫu nhiên (Audit Log) 5% số lượng ticket mỗi tuần và tái đào tạo nhân viên. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Lễ tân BQL tòa nhà là người dùng duy nhất của màn hình Triage; quy trình 5 bước được chuẩn hóa rõ ràng. |
| Baseline + metric đo được chưa? | **Yes** | Baseline hiện tại là 17 phút/ticket và trễ hàng đợi 4-12 tiếng; mục tiêu đo bằng giây trên hệ thống log. |
| Data/input đủ dùng chưa? | **Yes** | Dữ liệu text phản ánh và ảnh chụp hiện trường của cư dân gửi qua App Vinhomes Resident có sẵn hàng nghìn lượt mỗi ngày. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Bản nháp sai sẽ bị Lễ tân phát hiện và sửa lại ngay trên giao diện duyệt trong vài giây trước khi phát tán ra ngoài. |
| Có người review/owner không? | **Yes** | Lễ tân trực ca chịu trách nhiệm phê duyệt từng ticket; Trưởng ca CSKH chịu trách nhiệm toàn diện về chất lượng dịch vụ. |
| Có cách non-AI đơn giản hơn không? | **No** | Đã thử nghiệm form dropdown bắt cư dân chọn danh mục nhưng cư dân chọn bừa và không thể sinh câu trả lời cá nhân hóa. |

**Decision:**

```text
GO
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Dự án thỏa mãn toàn bộ 6 tiêu chí sàng lọc nghiêm ngặt của một sản phẩm AI khả thi: bài toán có tần suất lớn (hàng nghìn lượt/ngày), điểm nghẽn nhận thức rõ ràng, dữ liệu dồi dào và kiến trúc Human-in-the-loop đảm bảo an toàn tuyệt đối. Việc triển khai giải pháp sẽ mang lại ROI tức thì bằng việc cắt giảm hàng trăm giờ lao động thủ công mỗi ngày cho khối vận hành. Đây là bài toán mẫu mực để ứng dụng GenAI nâng cao chất lượng dịch vụ đô thị thông minh Vinhomes.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Phạm vi Pilot: Triển khai thử nghiệm tại 01 tòa nhà cụ thể (ví dụ: Tòa S2.01 Vinhomes Smart City) trong thời gian 02 tuần.
- Cách chạy: Chạy song song (Shadow mode / Copilot) cho 2 lễ tân ca trực; AI sinh nháp trên giao diện riêng, lễ tân bấm xem và góp ý.
- 03 Con số cốt lõi đo lường:
  1. Tỷ lệ phân loại đúng phòng ban (Mục tiêu: ≥ 92% trên tập 500 ticket thử nghiệm).
  2. Độ nhạy phát hiện sự cố khẩn cấp P1 (Mục tiêu: 100% không bỏ sót).
  3. Thời gian Lễ tân hoàn tất duyệt một phản ánh (Mục tiêu: ≤ 60 giây).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì đã quyết định GO).
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng vì đã quyết định GO).
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng thử nghiệm và ngắt kết nối AI ngay lập tức nếu:
1. Độ chính xác phân loại giảm xuống dưới 80% trong 3 ngày liên tiếp.
2. Xảy ra 01 trường hợp bỏ sót sự cố nguy hiểm P1 (False Negative) do AI phân loại nhầm thành việc không khẩn cấp mà Lễ tân không phát hiện kịp.
3. Chi phí API token bình quân vượt quá 100 VNĐ / ticket tiếp nhận.
Hệ thống sẽ tự động bật công tắc chuyển mạch (Feature Toggle) quay về giao diện hòm thư thủ công truyền thống cho lễ tân xử lý trong 1 phút mà không làm gián đoạn việc gửi tin của cư dân.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
