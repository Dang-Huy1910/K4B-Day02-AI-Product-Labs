# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đặng Quang Huy
- Mã học viên: 2A202602962
- Nhóm: Nhóm AI Product 02 — Vin Smart Future
- Candidate problem nhóm chọn: Tự động phân loại danh mục phòng ban, nhận diện sự cố khẩn cấp P1 và soạn nháp tin nhắn phản hồi tiếp nhận phản ánh của cư dân trên App Vinhomes Resident.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| **Scan cá nhân** | Quét 8 bài toán thực tế trong vận hành đại đô thị Vinhomes theo 4 lăng kính, đưa ra số liệu đo lường cụ thể về thời gian xử lý ticket của Lễ tân BQL. | Đóng góp bài toán hạt nhân (Triage & Dispatch) có tính khả thi và ROI cao nhất để nhóm lựa chọn. |
| **Pitch Problem Card** | Thuyết trình 2 phút về Card #1, phân tích rõ ràng nút thắt 12 phút tại bước đọc hiểu/gõ tin và nguy cơ chậm "15 phút vàng" đối với sự cố P1. | Thuyết phục toàn bộ thành viên đưa Card #1 vào danh sách Shortlist với số điểm cao nhất. |
| **Challenge bài của bạn khác** | Phản biện bài toán Trợ lý ảo giải đáp nội quy của Đức TM (nguy cơ AI hallucination cam kết sai chính sách) và bài thẩm định bản vẽ CAD của chính mình. | Giúp nhóm tỉnh táo loại bỏ các bài toán tiềm ẩn rủi ro pháp lý cao hoặc đòi hỏi công nghệ vượt quá phạm vi bài lab. |
| **Gom trùng / cluster** | Đề xuất phân loại 12 ý tưởng thành 4 cụm nghiệp vụ: Dịch vụ khách hàng, Thẩm định hồ sơ, Vận hành vật lý và Quản trị ERP nội bộ. | Giúp nhóm hệ thống hóa bức tranh toàn cảnh, tiết kiệm 15 phút tranh cãi lan man. |
| **Chọn candidate problem** | Khởi xướng và điều phối chấm điểm ma trận 7 tiêu chí (thang 1-5) để đánh giá khách quan 3 bài trong Shortlist. | Đạt được sự đồng thuận tuyệt đối của nhóm (35/35 điểm cho Candidate 1) dựa trên luận cứ định lượng. |
| **Validation / research** | Trực tiếp phỏng vấn 2 lễ tân ca tối tại tòa S2 và nghiên cứu đối chuẩn tính năng Intelligent Triage của Zendesk và ServiceNow. | Xác nhận điểm nghẽn là có thật tại bàn lễ tân và tìm ra khoảng trống giải pháp cho tiếng Việt đô thị. |
| **Workflow nhóm** | Thiết kế chi tiết sơ đồ Hiện tại (17 phút) vs Tương lai (1.5 phút), xác lập vị trí can thiệp của AI, ranh giới kiểm soát (Human boundary) và nhánh rẽ Fallback. | Cụ thể hóa luồng tương tác giữa người và máy, đảm bảo Lễ tân luôn là người bấm duyệt cuối cùng. |
| **Problem Statement** | Chắp bút xây dựng Problem Statement v0 và nâng cấp lên v1 bổ sung 3 trường kiểm soát rủi ro và trách nhiệm giải trình. | Đóng gói bài toán với các chỉ số đo lường sắc bén (Accuracy ≥ 92%, P1 Recall ≥ 99%, SLA < 15 phút). |
| **Rule / Workflow / Agent** | Lập luận dựa trên ma trận Độ mơ hồ × Độ phức tạp để chứng minh bài toán chỉ cần mức Workflow + LLM Feature, kiên quyết bác bỏ đề xuất làm Agent tự động. | Giữ dự án trong vùng an toàn vận hành, tránh lãng phí tài nguyên và loại trừ rủi ro AI phát ngôn sai lệch. |
| **Decision** | Xây dựng phương án Pilot chi tiết tại Tòa S2.01 Vinhomes Smart City trong 2 tuần và thiết lập 3 tiêu chí ngắt khẩn cấp (Rollback). | Đưa ra quyết định GO có trách nhiệm, có kế hoạch đo lường thực nghiệm rõ ràng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc thiết kế cơ chế bảo vệ "15 phút vàng" cho sự cố khẩn cấp P1 (kết hợp Rule lọc từ khóa nóng để kích hoạt còi báo động ngay lập tức) và kiên quyết thiết lập ranh giới Human-in-the-loop bắt buộc Lễ tân phải duyệt bản nháp trước khi gửi ra ngoài.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **Scan** | Gợi ý thêm các góc nhìn điểm nghẽn vận hành đại đô thị thông minh. | Mở rộng góc nhìn về xung đột trạm sạc xe điện V-Green với xe xăng tại hầm chung cư. | Đưa ra gợi ý viển vông kiểu "AI Agent tự động ngắt aptomat điện tòa nhà từ xa". | Loại bỏ ngay ý tưởng đó vì vi phạm nghiêm trọng quy chuẩn an toàn vật lý và PCCC của tòa nhà. |
| **Problem Card** | Đóng vai Skeptical PM để phản biện điểm yếu của Thẻ bài toán #1. | Chỉ ra lỗ hổng lớn: ranh giới giữa sự cố P1 (nguy hiểm) và P2 (hư hỏng thường) rất mong manh trong câu chữ cư dân. | Không đưa ra được giải pháp kỹ thuật cụ thể để xử lý rủi ro này ngoài câu khuyên chung chung "cần cẩn thận". | Tự tay thiết kế cơ chế an toàn kép: Rule bắt từ khóa nóng cực đoan + gắn cờ [CẦN XÁC MINH] khi điểm tin cậy < 80%. |
| **Workflow** | Hỗ trợ chuyển đổi sơ đồ tư duy thành cú pháp ASCII Art trực quan. | Định dạng nhanh, cân đối cấu trúc các hộp bước trong quy trình. | Bỏ qua hoàn toàn nhánh xử lý khi AI gặp lỗi (Fallback) và mặc định AI xử lý xong là gửi thẳng cho cư dân. | Bổ sung chốt chặn Human Boundary bắt buộc và vẽ thêm nhánh Fallback trả về hàng đợi thủ công. |
| **Research** | Tìm kiếm các giải pháp thương mại tương tự trên thế giới đã giải bài toán Triage. | Gợi ý chính xác 2 case-study tiêu biểu là Zendesk Intelligent Triage và Freshdesk Freddy Copilot. | Tự bịa số liệu thống kê về độ chính xác của các công cụ mà không dẫn được link nguồn chính thức. | Tự truy cập website gốc của Zendesk/ServiceNow kiểm tra tài liệu tính năng và chỉ trích dẫn thông tin đã xác thực. |
| **Problem Statement** | Kiểm tra độ chặt chẽ của 6 trường thông tin trong bản v0. | Phát hiện mục Boundary ban đầu còn mô tả chung chung, chưa đủ tính răn đe kỹ thuật. | Đề xuất viết lại toàn bộ nội dung theo văn phong đao to búa lớn nhưng thiếu số liệu thực tế. | Giữ nguyên văn phong thực tế của nhóm, chỉ bổ sung danh sách 4 điều CẤM tuyệt đối mà AI không được phép làm. |
| **Rule / Workflow / Agent** | Hỏi AI xem bài toán này có nên nâng cấp lên Multi-Agent System không. | Liệt kê được các công cụ (tools) mà một Agent có thể gọi trong tương lai (CRM API, Messaging API). | Bị bẫy "công nghệ ngầu": nhiệt tình khuyên nhóm nên làm Agent tự động toàn quyền để tối ưu hóa triệt để. | Nhận định đây là giải pháp tự sát về mặt vận hành đô thị; kiên quyết chọn mức Workflow (LLM Feature + HITL). |
| **Decision** | Gợi ý các điều kiện ngắt kết nối (Rollback criteria) cho kế hoạch thử nghiệm. | Gợi ý tiêu chí đo lường độ chính xác phân loại (<80% thì dừng). | Thiếu hoàn toàn góc nhìn về an toàn sinh mạng cư dân trong môi trường chung cư. | Bổ sung điều kiện dừng chí mạng: chỉ cần lọt đúng 01 sự cố P1 mà hệ thống không cảnh báo là dừng pilot ngay lập tức. |

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Quá trình làm việc cùng nhóm ở Day 2 đã mang lại cho tôi một bước chuyển biến rất lớn về tư duy sản phẩm: từ một người luôn hào hứng với công nghệ mới sang một Product Thinker biết hoài nghi và thực tế. 
Trong buổi thảo luận, nhóm tôi đã có thời điểm suýt rơi vào cái bẫy "solution-first" kinh điển khi một số bạn đề xuất xây dựng một hệ thống Multi-Agent tự động gọi API điều phối thợ kỹ thuật và tự trả lời cư dân cho "ngầu". 
Tuy nhiên, sau khi phân tích kỹ lưỡng ma trận độ phức tạp và đặt câu hỏi về trách nhiệm pháp lý nếu AI phát ngôn sai hoặc đóng nhầm sự cố rò rỉ khí gas, cả nhóm đã đồng thuận hạ mức giải pháp xuống Workflow (LLM Feature kết hợp Human-in-the-loop). 
Khi lắng nghe bài toán thẩm định bản vẽ thi công nội thất của bạn khác, tôi cũng học được rằng có những bài toán giá trị kinh tế rất cao nhưng rào cản dữ liệu phi cấu trúc quá lớn thì chưa thể là ứng viên phù hợp cho một pilot nhanh. 
Điều khó nhất và cũng là phần tôi để lại dấu ấn đậm nét nhất trong bản báo cáo cuối cùng chính là việc thiết lập Ranh giới (Boundary) và cơ chế Còi báo động đỏ cho sự cố P1. 
Tôi đã kiên quyết bảo vệ nguyên tắc: AI chỉ là người trợ lý đọc hiểu và soạn nháp văn bản, quyền bấm nút gửi và quyền phân công thợ bắt buộc phải thuộc về Lễ tân BQL để bảo đảm an toàn tuyệt đối. 
Nếu có cơ hội làm lại buổi lab, tôi sẽ challenge nhóm sớm hơn ở khâu phỏng vấn xác thực thực địa để có thêm dữ liệu định lượng từ các nhà thầu thi công, giúp bức tranh vận hành đô thị trở nên đa chiều hơn nữa.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
