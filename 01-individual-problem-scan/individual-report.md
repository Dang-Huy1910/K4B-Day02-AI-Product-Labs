# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Đặng Quang Huy
- Mã học viên: 2A202602962
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên ngành CNTT / AI Product Engineer Intern tại Khối Công nghệ Vin Smart Future (Tập đoàn Vingroup)
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Khảo sát thực tế luồng vận hành dịch vụ cư dân tại Ban Quản lý (BQL) các đại đô thị Vinhomes (Smart City, Ocean Park)
  - Phân tích nhật ký ticket khiếu nại, phản ánh chất lượng tiện ích và sự cố kỹ thuật gửi qua App Vinhomes Resident
  - Đánh giá thời gian phản hồi (SLA) giữa Lễ tân/CSKH và các đội hiện trường (Kỹ thuật MEP, An ninh, Vệ sinh)
  - Nghiên cứu khả thi ứng dụng Generative AI / LLM hỗ trợ phân loại văn bản, xử lý ảnh sự cố và tự động hóa soạn thảo

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | **Lặp lại** *(Repetitive)* | Đọc, phân loại danh mục (Điện nước, An ninh, Vệ sinh) và chuyển tiếp ticket phản ánh hằng ngày trên App Vinhomes Resident. | Lễ tân / CSKH BQL tòa nhà Vinhomes | 1.500 – 3.500 ticket/ngày/đại đô thị; lễ tân mất 15–17 phút/lượt đọc và nhập CRM; hàng đợi trễ 4–12 tiếng vào giờ cao điểm (18h-22h). |
| 2 | **Tốn thời gian** *(Time-consuming)* | Thẩm định hồ sơ bản vẽ đăng ký thi công / sửa chữa nội thất căn hộ mới nhận bàn giao. | Kỹ sư MEP/Xây dựng BQL & Cư dân nhận nhà | BQL mất 3–5 ngày đọc từng trang bản vẽ đối chiếu danh mục PCCC, kết cấu tường; trung bình 40–60 bộ hồ sơ/tháng/tòa nhà mới bàn giao. |
| 3 | **AI có thể tốt hơn** *(AI-upgrade)* | Trợ lý ảo giải đáp quy chế tòa nhà, thủ tục hành chính cư dân và nội quy tiện ích (vườn nướng BBQ, bể bơi, sân tennis) ngoài giờ làm việc. | Cư dân đại đô thị & Nhân viên trực ca đêm | Chatbot cây thư mục (bấm phím 1, 2) chỉ trả lời được câu hỏi cứng; 70% cư dân thoát chatbot và gọi dồn hotline trực ban đêm để hỏi. |
| 4 | **Pain từ người khác** *(Stakeholder Pain)* | Nhận diện và phản ứng chậm với sự cố khẩn cấp cấp độ P1 (mùi khét tủ điện hành lang, kẹt thang máy, tràn nước ngập sàn) do bị xếp chung hàng chờ FIFO với việc thông thường. | Đội An ninh/Kỹ thuật trực ban P1 & Cư dân gặp nạn | Bỏ lỡ "15 phút vàng" can thiệp ban đầu; thống kê có 3 vụ ngập sàn gỗ lan ra thang máy trong quý trước do tin báo kẹt trong hàng đợi hơn 2 tiếng. |
| 5 | **Pain từ người khác** *(Stakeholder Pain)* | Tiếp nhận và xử lý khiếu nại ô tô đỗ sai vị trí, đỗ chắn cửa hầm hoặc đè vỉa hè trong đại đô thị. | Bảo vệ tuần tra, Cư dân bị cản trở giao thông | Bảo vệ mất 20–30 phút tra cứu biển số xe thủ công trên file Excel/CRM gửi xe để tìm số điện thoại gọi chủ xe; xảy ra cãi vã, khiếu nại gay gắt. |
| 6 | **Lặp lại** *(Repetitive)* | Tổng hợp báo cáo giao ban ca trực kỹ thuật vận hành tòa nhà (hệ thống điện, nước, máy bơm, thang máy) mỗi sáng. | Kỹ sư trưởng ca & Ban Giám đốc Vận hành | Mất 60–90 phút cuối mỗi ca gom dữ liệu từ 8–10 sổ tay ghi chép/nhóm Zalo kỹ thuật hiện trường để lập bảng tổng kết Excel. |
| 7 | **AI có thể tốt hơn** *(AI-upgrade)* | Lọc và phân loại cảnh báo an ninh từ hệ thống Camera AI đại đô thị (nhầm lẫn lá cây rơi, bóng động vật với người xâm nhập vùng cấm). | Nhân viên Trung tâm Điều hành Tập trung (IOC) | Hơn 65% cảnh báo là "false alarm"; nhân viên IOC bị mệt mỏi cảnh báo (alert fatigue), dẫn đến nguy cơ bỏ sót sự cố xâm nhập thật. |
| 8 | **Tốn thời gian** *(Time-consuming)* | Xác minh và điều phối giải tỏa xe xăng đỗ chiếm chỗ tại các trụ sạc xe điện VinFast / V-Green trong hầm chung cư. | Tài xế taxi Xanh SM, Chủ xe điện VinFast, Bảo vệ hầm | Tài xế Xanh SM mất 30–45 phút chờ đợi bảo vệ hầm tìm chủ xe xăng dời xe, gây trễ ca sạc, giảm doanh thu và tắc nghẽn cục bộ hầm xe. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Tôi đang rà soát các điểm nghẽn vận hành dịch vụ và kỹ thuật tại các khu đô thị lớn như Vinhomes. Hãy gợi ý thêm các pain points thường gặp theo 4 lăng kính: Lặp lại, Tốn thời gian, AI có thể làm tốt hơn, Pain từ người khác. Yêu cầu có actor và số liệu thực tế."
- Ý dùng được: Bổ sung bài toán phân luồng sự cố P1 (cháy nổ/ngập nước) bị nghẽn trong hàng đợi FIFO và bài toán xung đột trụ sạc xe điện V-Green với xe xăng.
- Ý bỏ vì không phải pain thật: Ý tưởng "Xây dựng AI Agent tự động ra lệnh đóng/ngắt aptomat điện tầng hầm từ xa" bị loại bỏ ngay vì vi phạm nghiêm trọng quy chuẩn an toàn vật lý và PCCC (bắt buộc phải có kỹ sư hiện trường kiểm tra).

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể (đạt 8 dòng)
- [x] Dùng ít nhất 3/4 lăng kính (dùng đủ cả 4/4 lăng kính)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| **1** | **Triage & Dispatch phản ánh cư dân trên App Vinhomes Resident (kèm tách luồng P1)** | 1. Tần suất cực lớn (1.500–3.500 lượt/ngày), ROI rõ ràng.<br>2. Quy trình hiện tại có bước đọc và phân loại mất nhiều thời gian nhất.<br>3. Ranh giới vận hành rõ (AI phân loại & draft, lễ tân duyệt). | Độ chính xác của AI khi cư dân dùng tiếng lóng hoặc mô tả tối nghĩa bằng tiếng Việt địa phương. |
| **2** | **Thẩm định hồ sơ bản vẽ đăng ký thi công nội thất căn hộ** | 1. Thời gian chờ hiện tại quá dài (3–5 ngày), gây ức chế lớn cho cư dân mới nhận nhà.<br>2. Quy chuẩn checklist PCCC và kiến trúc đã có văn bản cụ thể. | Việc đọc và hiểu bản vẽ thiết kế CAD/PDF phức tạp đòi hỏi multimodal AI chuyên sâu, dữ liệu ảnh bản vẽ có thể chưa chuẩn hóa. |
| **3** | **Xử lý xe đỗ trái phép và gửi thông báo tự động cho chủ xe** | 1. Giảm thiểu xung đột trực tiếp giữa cư dân và đội bảo vệ.<br>2. Workflow ngắn gọn, dễ triển khai pilot tại 1 hầm xe. | Tỷ lệ nhận diện biển số qua ảnh chụp góc nghiêng/thiếu sáng của bảo vệ tuần tra. |

---

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Vinhomes Resident Triage & Dispatch AI

```text
Problem 1 câu:
Lễ tân / CSKH BQL tòa nhà Vinhomes mất 15-17 phút/ticket để đọc, tra căn hộ, phân loại phòng ban và gõ tin xác nhận cho 1.500-3.500 phản ánh/ngày, khiến hàng đợi trễ 4-12 tiếng và làm chậm xử lý các sự cố khẩn cấp P1.

Actor:
Lễ tân / Chuyên viên CSKH BQL tòa nhà Vinhomes (người trực tiếp xử lý hàng đợi ticket); Cư dân gửi phản ánh (người nhận kết quả); Đội Kỹ thuật MEP / An ninh / Vệ sinh (người nhận điều phối việc).

Thời điểm / bối cảnh:
Xảy ra liên tục hằng ngày, cao điểm từ 18h00 - 22h00 khi cư dân về nhà và phát hiện các sự cố tiện ích, kỹ thuật hoặc dịch vụ trong căn hộ và khu đô thị.

Current workflow 3-7 bước:
1. Tiếp nhận ticket phản ánh (văn bản / hình ảnh) từ hòm thư App Vinhomes Resident.
2. Tra cứu mã căn hộ trên phần mềm CRM để xác định thông tin chủ hộ và trạng thái phí.
3. Đọc mô tả, phân loại danh mục phòng ban (Kỹ thuật MEP, Vệ sinh, An ninh, CSKH) và gán cấp độ P1-P3.
4. Tạo lệnh điều phối công việc (work-order) chuyển cho trưởng đội hiện trường.
5. Soạn thảo tin nhắn phản hồi lịch sự xác nhận với cư dân và bấm gửi qua App.

Bottleneck:
Bước 3 (Phân loại danh mục & gán nhãn P1-P3: mất 7 phút) và Bước 5 (Soạn thảo tin phản hồi theo chuẩn văn phong Vinhomes: mất 5 phút). Tổng cộng chiếm 12/17 phút mỗi ticket.

Impact:
Tổng thời gian xử lý lên tới 375 - 875 giờ lao động của lễ tân/ngày/đại đô thị. Gây nghẽn hàng đợi từ 4-12 tiếng. Đặc biệt, sự cố khẩn cấp P1 (khét điện, kẹt thang) bị xếp hàng chung FIFO dẫn tới nguy cơ cháy nổ, thiệt hại tài sản hàng trăm triệu đồng và giảm chỉ số hài lòng cư dân (CSAT).

Success metric:
- Thời gian máy xử lý phân loại và sinh nháp: Giảm từ 12 phút xuống < 10 giây.
- Thời gian Lễ tân duyệt bản nháp: < 60 giây/ticket.
- Độ chính xác phân loại đúng phòng ban: Đạt ≥ 92%.
- Độ nhạy nhận diện sự cố khẩn cấp P1 (Recall/Safety): Đạt ≥ 99% (tuyệt đối không bỏ sót P1).
- Tỷ lệ phản hồi cư dân trong 15 phút giờ hành chính: Tăng từ mức thấp (<30%) lên ≥ 80%.

Non-AI alternative:
Dùng dropdown form bắt buộc cư dân tự chọn phân loại (Điện, Nước, Khẩn cấp...).
Nhược điểm: Cư dân thường chọn sai danh mục, hoặc luôn chọn mức "Khẩn cấp" để được phục vụ trước, gây nhiễu dữ liệu và không thể tự soạn tin phản hồi cá nhân hóa.

AI hypothesis:
Mô hình LLM đa phương thức (như Gemini 2.5 Flash) có thể đọc hiểu ngôn ngữ tự nhiên không chuẩn hóa (kể cả tiếng lóng, viết tắt) kèm hình ảnh hiện trường, trích xuất cấu trúc JSON (Phòng ban, Cấp độ P1-P3, Tóm tắt sự cố) và tự động tạo bản nháp tin nhắn phản hồi đạt chuẩn phong cách Vinhomes trong 3 giây.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ~17 phút/ticket (Thời gian chờ hàng đợi thực tế: 4–12 tiếng)

[1. Cư dân gửi ticket: 1']
        ↓
[2. Lễ tân tra cứu CRM căn hộ: 2']
        ↓
[3. Lễ tân đọc, phân loại phòng ban & gán P1-P3: 7']  <-- 🔴 BOTTLENECK CHÍNH
        ↓
[4. Lễ tân tạo work-order cho đội hiện trường: 2']
        ↓
[5. Lễ tân gõ tin nhắn phản hồi gửi cư dân: 5']       <-- 🔴 BOTTLENECK PHỤ
        ↓
[Cư dân nhận thông báo tiếp nhận]

────────────────────────────────────────────────────────────────────────────────────────

FUTURE STATE — ~1.5 phút/ticket (Thời gian xử lý của AI: < 5 giây)

[1. Cư dân gửi ticket qua App]
        ↓
[2. Hệ thống tự động liên kết dữ liệu CRM căn hộ: 1s]
        ↓
[3. LLM trích xuất JSON (Phòng ban, P1-P3) & sinh bản nháp tin nhắn: 3s]
        │
        ├──> [NẾU LÀ P1 KHẨN CẤP]: Bắn ngay SMS/Còi báo động đỏ cho Chỉ huy Trưởng ca An ninh
        ↓
[4. Lễ tân kiểm tra màn hình Triage, bấm "Phê duyệt" hoặc sửa nhanh: 60 - 90s]  <-- 🛡️ HUMAN BOUNDARY
        ↓
[5. Tự động gửi work-order sang đội hiện trường & phát tin phản hồi cho cư dân: 2s]

Fallback: Nếu độ tin cậy của AI (confidence score) < 80% hoặc ảnh mờ không phân tích được
          --> Chuyển thẳng vào hàng đợi thông thường để Lễ tân xử lý thủ công theo quy trình cũ.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Thẩm định hồ sơ thi công nội thất căn hộ

```text
Problem 1 câu:
Kỹ sư MEP và xây dựng của BQL mất 45-60 phút/bộ hồ sơ và kéo dài 3-5 ngày làm việc để rà soát thủ công hàng chục trang bản vẽ PDF đối chiếu tiêu chuẩn an toàn PCCC, làm chậm tiến độ nhận nhà và hoàn thiện của cư dân.

Actor:
Kỹ sư BQL tòa nhà Vinhomes (người thẩm định hồ sơ); Cư dân / Nhà thầu nội thất (người chờ cấp phép thi công).

Thời điểm / bối cảnh:
Giai đoạn đại đô thị bàn giao các phân khu mới, tiếp nhận từ 40 - 80 bộ hồ sơ đăng ký thi công sửa chữa mỗi tuần.

Current workflow 3-7 bước:
1. Tiếp nhận tệp hồ sơ PDF (bản vẽ mặt bằng, sơ đồ cấp thoát nước, điện, PCCC) từ cư dân.
2. Mở từng trang bản vẽ, đối chiếu thủ công với bảng checklist tiêu chuẩn quy định tòa nhà.
3. Ghi chép các điểm sai phạm (khoảng cách đầu phun sprinkler, công suất aptomat, đập tường chịu lực).
4. Tổng hợp biên bản và soạn thảo công văn phản hồi (Chấp thuận hoặc Yêu cầu sửa đổi).

Bottleneck:
Bước 2 & Bước 3: Đọc và rà soát thủ công từng thông số kỹ thuật trên bản vẽ PDF đối chiếu với danh mục quy định PCCC và kết cấu (chiếm 45/60 phút).

Impact:
Cư dân phải chờ đợi 3–5 ngày (thậm chí 7 ngày nếu phải nộp lại); kỹ sư BQL ngập trong giấy tờ, giảm thời gian giám sát an toàn thi công thực tế tại công trường.

Success metric:
- Rút ngắn thời gian thẩm định sơ bộ từ 3 ngày xuống < 15 phút.
- Tỷ lệ phát hiện đúng các điểm vi phạm an toàn PCCC cốt lõi đạt 100%.

Non-AI alternative:
Tạo checklist giấy bắt nhà thầu tự cam kết tích chọn trước khi nộp. Nhược điểm: Nhà thầu vẫn tích bừa để nộp cho nhanh, kỹ sư vẫn phải lật từng trang kiểm tra lại.

AI hypothesis:
Multimodal Document AI có thể quét tập tin bản vẽ PDF, nhận diện sơ đồ công năng và đối chiếu tự động với 25 tiêu chuẩn kỹ thuật của Vinhomes, xuất ra bảng báo cáo đối soát sơ bộ kèm các vị trí nghi ngờ sai phạm để kỹ sư duyệt.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 3 đến 5 ngày (Thời gian kỹ sư đọc trực tiếp: ~60 phút/bộ)

[1. Nhận tệp PDF bản vẽ: 5'] 
→ [2. Kỹ sư đọc từng trang đối chiếu quy chuẩn: 35'] <-- 🔴 BOTTLENECK
→ [3. Ghi chép danh sách lỗi vi phạm: 10']
→ [4. Soạn công văn phản hồi: 10']

FUTURE STATE — 15 phút (Thời gian AI rà soát: ~30 giây)

[1. Upload file PDF bản vẽ lên cổng dịch vụ] 
→ [2. AI Document Scan & đối chiếu tự động với 25 điều khoản an toàn: 30s] 
→ [3. Xuất bảng tổng hợp Pre-check (Pass/Fail từng mục kèm trang dẫn chứng): 10s] 
→ [4. Kỹ sư BQL kiểm tra lại các điểm cờ đỏ (Flagged items) và ký duyệt: 15'] <-- 🛡️ HUMAN BOUNDARY

Fallback: Nếu định dạng bản vẽ không nhận dạng được hoặc sai quy chuẩn scan --> Thông báo yêu cầu nhà thầu nộp lại đúng định dạng chuẩn.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Xử lý vi phạm đỗ xe trái phép trong đại đô thị

```text
Problem 1 câu:
Đội an ninh tuần tra mất 20-30 phút cho mỗi trường hợp ô tô đỗ sai quy định (chắn cửa hầm, đỗ đè vỉa hè) để chụp ảnh, tra cứu biển số thủ công trên hệ thống gửi xe và gọi điện nhắc nhở chủ phương tiện di dời.

Actor:
Bảo vệ tuần tra đại đô thị (người thực thi); Chủ phương tiện đỗ sai; Cư dân bị ách tắc giao thông.

Thời điểm / bối cảnh:
Xảy ra rải rác cả ngày nhưng đặc biệt nghiêm trọng vào giờ đưa đón học sinh (7h30-8h30) và giờ ăn tối (18h30-20h30) quanh các sảnh chung cư và khu shophouse.

Current workflow 3-7 bước:
1. Phát hiện phương tiện đỗ sai quy định tại khu vực cấm.
2. Chụp ảnh hiện trường bằng điện thoại cá nhân.
3. Gửi ảnh vào nhóm Zalo hoặc gọi bộ đàm về trung tâm điều hành đọc biển số xe.
4. Nhân viên trực máy tra cứu biển số trên cơ sở dữ liệu thẻ xe để lấy số điện thoại chủ hộ.
5. Gọi điện thoại liên hệ chủ xe yêu cầu xuống di dời phương tiện.

Bottleneck:
Bước 3 & Bước 4: Gọi bộ đàm đọc biển số và tra cứu thủ công trên danh sách thẻ xe để tìm thông tin liên lạc (mất 15-20 phút, dễ nghe nhầm số qua bộ đàm ồn ào).

Impact:
Ùn tắc giao thông cục bộ sảnh đón trả khách, cản trở xe rác và xe cứu thương; phát sinh mâu thuẫn cự cãi giữa cư dân và đội ngũ bảo vệ.

Success metric:
- Rút ngắn thời gian từ lúc phát hiện xe vi phạm đến lúc gửi thông báo đến chủ xe từ 25 phút xuống < 2 phút.
- Giảm số vụ bảo vệ phải gọi điện thủ công trực tiếp 70% (chủ xe tự giác di dời sau thông báo đẩy trên App).

Non-AI alternative:
Khóa bánh xe vi phạm ngay lập tức và dán giấy phạt. Nhược điểm: Gây bức xúc gay gắt cho cư dân, tăng xung đột vật lý và vẫn không giải tỏa được nút thắt giao thông ngay lúc đó.

AI hypothesis:
Ứng dụng App tuần tra tích hợp OCR biển số xe tức thì trên camera điện thoại của bảo vệ, tự động truy vấn API thông tin chủ hộ và kích hoạt thông báo cảnh báo đẩy (Push Notification) kèm hình ảnh vi phạm đến App Vinhomes Resident của chủ xe trong 5 giây.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ~25 phút

[1. Phát hiện xe đỗ sai: 1'] 
→ [2. Chụp ảnh: 1'] 
→ [3. Gọi bộ đàm đọc biển số về trung tâm: 5'] 
→ [4. Trực ban tra Excel tìm SĐT chủ xe: 10'] <-- 🔴 BOTTLENECK
→ [5. Gọi điện thoại giục chủ xe: 8']

FUTURE STATE — ~2 phút

[1. Bảo vệ giơ camera quét biển số trên App Tuần tra (OCR): 3s] 
→ [2. Hệ thống tự động truy vấn thông tin chủ xe & địa điểm vi phạm: 2s] 
→ [3. Bắn Push Notification tự động cảnh báo & yêu cầu di dời trong 10 phút: 1s] 
→ [4. Bảo vệ bấm xác nhận vi phạm trên màn hình: 30s] <-- 🛡️ HUMAN BOUNDARY

Fallback: Nếu OCR không đọc được biển số (do bùn đất, góc chụp quá nghiêng) --> Cho phép bảo vệ gõ tay 5 số cuối của biển số để truy vấn thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Triage & Dispatch phản ánh cư dân trên App Vinhomes Resident (kèm tách luồng khẩn cấp P1).
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là bài toán cốt lõi có tần suất xử lý lớn nhất toàn hệ sinh thái (1.500 - 3.500 lượt/ngày) với quy trình 5 bước cực kỳ chuẩn hóa. 
Việc ứng dụng AI giải quyết đúng 2 bước nghẽn nhất (phân loại danh mục và soạn tin phản hồi) giúp cắt giảm thời gian xử lý từ 17 phút xuống dưới 1.5 phút/ticket, tiết kiệm hàng trăm giờ lao động mỗi ngày cho Lễ tân. 
Quan trọng nhất, giải pháp này giải quyết được rủi ro chí mạng của tòa nhà: bảo vệ "15 phút vàng" cho sự cố khẩn cấp P1 (chập cháy, kẹt thang) nhờ cơ chế tách luồng ưu tiên tức thì thay vì để kẹt trong hàng đợi FIFO.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Cư dân phản ánh bằng tiếng Việt khẩu ngữ, viết tắt, không dấu ("thang máy tầng 10 rung lắc kêu cọc cọc", "mùi khét lẹt ở hộp gen") thì AI có phân loại nhầm phòng ban hoặc bỏ lọt sự cố P1 không?
2. Nếu lễ tân ỷ lại vào bản nháp của AI mà không đọc kỹ trước khi bấm duyệt gửi cho cư dân, rủi ro cam kết sai thời gian hoặc sai thẩm quyền giải quyết sẽ được kiểm soát như thế nào?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Ranh giới giữa P1 (khẩn cấp đe dọa an toàn) và P2 (hư hỏng bất tiện) rất mong manh trong câu từ cư dân; nếu AI đánh giá sai thì đội an ninh bị quá tải bởi báo động giả hoặc bỏ sót hiểm họa.
- Tôi sửa gì: Thiết kế cơ chế an toàn kép: Kết hợp Rule-based Keyword cứng (từ khóa nóng: cháy, nổ, khét, kẹt thang, máu) làm lớp lọc nhanh đầu tiên kích hoạt cảnh báo, sau đó mới đến LLM phân tích ngữ cảnh, và bắt buộc giữ Human-in-the-loop (Lễ tân/Trực ban phải bấm xác nhận thì lệnh can thiệp hiện trường mới chính thức lưu vết).

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
