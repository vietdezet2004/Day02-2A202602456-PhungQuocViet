# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
| ----- | ----------- | ------------- | --------------------------------------------------------------- |
| 1 | Thái Phúc Tiến | 2A202602661 | Facilitator & Problem Owner (Candidate 1) |
| 2 | Phan Hoàng Vũ | 2A202602450 | Workflow |
| 3 | Nguyễn Công Duẩn | 2A202602716 | Market & Existing Solutions Researcher |
| 4 | Phùng Quốc Việt | 2A202602456 | Writer |
| 5 | Nguyễn Đức Long | 2A202602917 | Research |
| 6 | Chu Thùy Dương | 2A202602660 | Risk, Boundary & Human-in-the-loop Reviewer |

**Candidate problem nhóm chọn (1 câu):**

Lên kế hoạch di chuyển thông minh đa biến số (chuyến bay, giao thông real-time, thủ tục sân bay) bằng AI Agent linh hoạt cho sinh viên và người di chuyển xa không thường xuyên.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
| :---: | --- | --- | --- | --- | --- |
| 1 | Thái Phúc Tiến | Lên kế hoạch di chuyển (sân bay, vé, thủ tục, thời gian) | Người đi du lịch / công tác | Phải tự tính toán thủ công và trừ hao thời gian cho nhiều biến số (kẹt xe, check-in) | Pain thực tế, rủi ro cao nếu trễ, thích hợp dùng AI Agent |
| 2 | Thái Phúc Tiến | Ghi chép & phân loại thu chi cá nhân | Sinh viên cá nhân | Mất thời gian đọc lại từng dòng giao dịch và phân loại thủ công cuối tuần | Thường gặp nhưng ít cấp bách, có thể làm bằng OCR/Rule |
| 3 | Thái Phúc Tiến | Cập nhật CV và Cover Letter theo từng JD tuyển dụng | Sinh viên năm cuối | Mất thời gian suy nghĩ diễn đạt lại kinh nghiệm cho khớp keyword JD | Demand cao đối với sinh viên năm cuối, thiên về Prompting |
| 4 | Phan Hoàng Vũ | Thống kê chi tiêu chung/riêng của phòng trọ | Sinh viên / người ở ghép | Đọc bill, ghi chép và phân loại tiền trọ/điện nước thủ công | Thường gặp trong sinh hoạt nhóm, có thể giải quyết bằng App |
| 5 | Phan Hoàng Vũ | Lên thực đơn & danh sách đi chợ hàng tuần cho phòng trọ | Sinh viên / người ở ghép | Nhắn tin bàn bạc qua lại mỗi người một ý, khó chốt thực đơn | Nhóm nhỏ gặp, giải quyết được bằng Rule voting |
| 6 | Phan Hoàng Vũ | Kiểm tra khoản thanh toán & nhắc nợ tiền quỹ hàng tháng | Sinh viên / người ở ghép | Mất thời gian mở app ngân hàng, cuộn đọc lịch sử giao dịch | Pain nhập liệu, có thể xử lý bằng bot thông báo |
| 7 | Nguyễn Công Duẩn | Chọn và ưu tiên nguồn tài liệu khi có nhiều note, video | Học viên tự học ngoại ngữ | Tìm và so sánh nhiều nguồn để quyết định bài học ưu tiên | Phổ biến với người tự học, thuộc dạng Recommendation NLP |
| 8 | Nguyễn Công Duẩn | Lập lịch ôn tập cách quãng (Spaced Repetition) cho note | Học viên tự học ngoại ngữ | Quyết định ngày ôn tiếp theo cho từng mục, mất 10-20ph lập lịch | Rất hay về phương pháp học tập, giải quyết được bằng Rule |
| 9 | Nguyễn Công Duẩn | Đồng bộ và định dạng note khi xem video bài giảng | Học viên tự học ngoại ngữ | Phải chép lại và chuyển định dạng note ở nhiều nơi | Gián đoạn việc tiếp thu bài, xử lý được bằng Chrome Extension |
| 10 | Phùng Quốc Việt | Tự luyện đề TOEIC Reading (giải thích chi tiết câu sai) | Người học Tiếng Anh | Khi làm sai không có giải thích cặn kẽ, tự tra cứu mơ hồ | Nhu cầu lớn, thích hợp làm RAG/LLM Tutor |
| 11 | Phùng Quốc Việt | Lọc cấu hình & tạo bảng so sánh laptop tư vấn khách hàng | Nhân viên bán hàng (Sale) | So sánh thông số kỹ thuật nhiều dòng laptop thủ công | Bài toán B2C Sale, giải quyết tốt bằng RAG + Matrix table |
| 12 | Phùng Quốc Việt | Viết tài liệu Postman & giải thích payload cho Frontend | Developer (BE / FE) | Chuyển đổi endpoint từ BE sang doc dễ hiểu cho FE | Pain kỹ thuật của Dev, thích hợp làm AI Code Doc Generator |
| 13 | Nguyễn Đức Long | Tổng đài 115: Xử lý thoại & trích xuất thông tin cuộc gọi | Người gặp sự cố, Tổng đài viên | Người gọi hoảng loạn, khai báo không chính xác, nghẽn thoại 60-180s | Impact xã hội cực lớn, bài toán khẩn cấp đòi hỏi độ chính xác cao |
| 14 | Nguyễn Đức Long | Tổng đài 115: Phân loại sai mức độ ưu tiên ca cấp cứu | Tổng đài viên 115 | Phụ thuộc cảm tính; 10-15% ca bị phân loại sai xe cấp cứu | Rủi ro tính mạng cao, thích hợp dùng Classification Model |
| 15 | Nguyễn Đức Long | Tự động phát hiện & phát tín hiệu cấp cứu người ở 1 mình | Người già / Nạn nhân ở 1 mình | Độ trễ phát hiện sự cố 2-12h (bỏ lỡ thời gian vàng) | Rất nhân văn nhưng phụ thuộc cứng vào phần cứng/cảm biến IoT |
| 16 | Chu Thùy Dương | Hiểu flow code của người khác khi tiếp nhận task mới | Developer nhận task | Đọc code và lần theo flow thủ công mất nhiều thời gian | Pain phổ biến của Dev, làm bằng Code Knowledge Graph |
| 17 | Chu Thùy Dương | Kiểm tra regression/impact khi sửa code theo spec mới | Developer / Code Reviewer | Khó xác định đầy đủ các flow cũ có thể bị phá hỏng | Pain kỹ thuật lớn, có thể làm bằng Static Analysis + AI |
| 18 | Chu Thùy Dương | Phát hiện sớm dependency giữa các task trong team | Thành viên trong dev team | Dependency thường chỉ phát hiện khi task đã bắt đầu | Quản lý dự án Agile, giải quyết được bằng Task Graph AI |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
| :---: | --- | --- | --- |
| A | 1, 4, 5, 6 | Lập kế hoạch di chuyển & Sinh hoạt phòng trọ | Tập trung vào quản lý thời gian, lịch trình di chuyển và chi tiêu nhóm |
| B | 7, 8, 9, 10 | Hỗ trợ học tập & Ôn thi ngoại ngữ | Trích xuất ghi chú, lập lịch ôn tập cách quãng (Spaced Repetition) và AI Tutor |
| C | 13, 14, 15 | Y tế & Cấp cứu khẩn cấp 115 | Xử lý thoại khẩn cấp, phân loại ưu tiên ca bệnh và cảnh báo rủi ro người ở 1 mình |
| D | 2, 3, 11, 12, 16, 17, 18 | Công cụ Lập trình viên & Tuyển dụng / Bán hàng | Phân tích code flow, kiểm tra regression, CV matching theo JD và sinh API doc |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
| --- | --- | --- |
| Lên kế hoạch di chuyển ra sân bay | - Actor & Workflow di chuyển 5 bước rõ ràng.<br>- Impact lớn: loại bỏ căng thẳng & mệt mỏi đi quá sớm.<br>- Phù hợp phát triển AI Agent theo dõi real-time. | Khả năng truy cập API dữ liệu giao thông & trạng thái chuyến bay thời gian thực. |
| Thống kê chi tiêu chung/riêng phòng trọ | - Pain point sinh hoạt hàng ngày rất phổ biến.<br>- Bottleneck rõ ở bước đọc bill & phân loại thu chi.<br>- Dễ đo lường thời gian tiết kiệm (từ 30ph xuống 5ph). | Độ chính xác khi đọc ảnh chụp bill bị mờ hoặc chữ viết tay; rủi ro sót giao dịch. |
| Viết tài liệu Postman & giải thích payload cho Frontend | - Pain point kỹ thuật thực tế của dân Dev (BE mất thời gian giải thích cho FE).<br>- Input/Output cấu trúc rõ ràng (API Endpoint -> Postman doc).<br>- Tiết kiệm lớn thời gian giao tiếp & handoff giữa BE/FE. | Phụ thuộc vào chất lượng comment/code của Backend; Rủi ro rò rỉ secret/token trong payload. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Lên kế hoạch di chuyển ra sân bay | 5 | 5 | 4 | 5 | 4 | 5 | 4 | **32** |
| Thống kê chi tiêu phòng trọ | 4 | 4 | 5 | 4 | 4 | 4 | 5 | **30** |
| Viết tài liệu Postman cho FE | 4 | 4 | 4 | 4 | 3 | 4 | 4 | **27** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Lên kế hoạch di chuyển thông minh đa biến số (chuyến bay, giao thông real-time, thủ tục sân bay) bằng AI Agent linh hoạt cho sinh viên và người di chuyển xa không thường xuyên.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn bài toán này vì có đối tượng sử dụng rất rõ ràng (người đi công tác/du lịch, đặc biệt là sinh viên ít khi đi máy bay) và điểm nghẽn có rủi ro cực kỳ cao: việc phải tự tính toán, trừ hao thời gian thủ công qua nhiều biến số (tình trạng kẹt xe, thời gian ký gửi hành lý, xếp hàng an ninh) rất dễ dẫn đến nguy cơ trễ chuyến bay và thiệt hại lớn về tài chính.
Quy trình di chuyển có các mốc thời gian cố định (giờ đóng quầy, giờ mở cổng ra máy bay), giúp nhóm dễ dàng xác định baseline và đo lường thành công bằng các chỉ số cụ thể như thời gian lên kế hoạch (giảm từ 60 phút xuống dưới 10 phút) và xác suất đến sân bay đúng khung giờ an toàn đạt trên 95%.
Đặc biệt, đây là bài toán lý tưởng để so sánh giữa Rule, Workflow và Agent: bài toán vừa có quy tắc tĩnh (quy định giờ của hãng bay), vừa có yếu tố động theo ngữ cảnh thời gian thực (mật độ giao thông, hoãn chuyến, thời tiết), tạo đất diễn hoàn hảo để phân tích ranh giới can thiệp của AI.
Cuối cùng, đây là trải nghiệm thực tế mà mọi thành viên trong nhóm đều từng gặp hoặc chứng kiến, giúp nhóm thuận lợi trong việc phỏng vấn kiểm chứng nhanh (quick validation) và hoàn thành tốt trong phạm vi buổi lab.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Thống kê chi tiêu phòng trọ: Bài toán chủ yếu giải quyết khâu nhập liệu OCR và phân loại đơn giản, thiên về giải pháp app di động/Excel thông thường hơn là bài toán AI Agent phức tạp cần khả năng thích ứng động.
- Viết tài liệu Postman cho FE: Mặc dù giải quyết đúng pain point thực tế của đội ngũ Dev, nhưng quy trình này mang tính chất một đường thẳng (Input code -> Output doc). Do đó, nó phù hợp để tự động hóa bằng Workflow hoặc một Prompt kỹ thuật thay vì cần đến sự linh hoạt của Agent.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
- Thành viên Đức Long lo ngại tần suất đi xa của sinh viên không quá cao (1-3 lần/năm). Nhóm chốt mở rộng bối cảnh di chuyển sang du lịch nhóm và công tác xa, đồng thời tập trung vào chất lượng sự an tâm và độ chính xác ở mỗi chuyến đi quan trọng.
- Thành viên Việt lo lắng người dùng sẽ không tin tưởng AI để quyết định giờ ra sân bay vì rủi ro trễ chuyến là cực kỳ nghiêm trọng. Nhóm chốt: Thiết kế hệ thống theo dạng Bán tự động (Human-in-the-loop) — AI đưa ra các phương án kèm phân tích rủi ro (độ rủi ro trễ 5%, 15%) để người dùng chủ động bấm xác nhận phương án phù hợp nhất.
- Thành viên Dương đặt vấn đề rằng nếu AI Agent được phép tự động điều chỉnh giờ xuất phát dựa trên dữ liệu giao thông và chuyến bay, thì hệ thống sẽ phải xử lý lượng biến số cực lớn trong thời gian thực — điều này dễ dẫn đến “hiệu ứng domino” khi một sai lệch nhỏ ở đầu vào (ví dụ dữ liệu delay sân bay bị cập nhật chậm 5 phút) có thể khiến toàn bộ mô hình ra quyết định sai lệch. Nhóm chốt: Thiết lập chốt an toàn cứng (Hard Safety Boundary) — luôn có khoảng đệm tối thiểu bất biến và chỉ cho phép AI đưa khuyến nghị để người dùng duyệt chứ AI không tự ý đổi lịch trình mà không thông báo.
```

---

## Phase 4 — Quick Validation + Research (Phần 5: Kiểm chứng nhanh + Research giải pháp đã có)

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
| --- | ---: | --- | --- | --- |
| Interview (Skeptical Product Manager & Sinh viên đi xa) | 3 người | - "Pain thực sự không nằm ở khâu tính phép cộng trừ thời gian, mà là sự mơ hồ và lo sợ về các rủi ro không lường trước như tắc đường giờ cao điểm, trễ giờ đóng quầy check-in, đổi cổng ra máy bay."<br>- "Đi sớm trước 3 tiếng rất mệt mỏi. Chuyến bay lúc 6h sáng mà bắt thức từ 2h để ra ngồi vạ vật 3 tiếng ở sân bay thì cả ngày hôm đó coi như kiệt sức." | - "Metric loại bỏ 100% rủi ro trễ giờ là ảo vì AI không thể can thiệp được kẹt xe đột xuất do tai nạn giao thông hay thời tiết cực đoan."<br>- "Người đi quen họ chỉ mở Google Maps 2 phút rồi cộng đại 1-2 tiếng là xong." | - Thu hẹp Actor từ 'người đi du lịch/công tác' chung chung thành: **Sinh viên / Khách di chuyển xa không thường xuyên (1-3 lần/năm)**.<br>- Sửa metric: Đổi từ 'loại bỏ 100%' thành **Tỉ lệ hoàn thiện thủ tục đúng mốc an toàn đạt ≥ 95%**.<br>- Trọng tâm chuyển sang: **Giảm căng thẳng tâm lý và tối ưu tính linh hoạt của thời gian**. |
| Survey / Micro poll (Discord sinh viên) | 8 sinh viên | - 7/8 bạn (87.5%) xác nhận luôn bị căng thẳng cao độ trước mỗi chuyến bay, phải cài 4-5 chuông báo thức và mất 45-60 phút tự tra cứu, tính toán đường đi, trừ hao giờ kẹt xe.<br>- Điểm đánh giá mức độ đáng giải quyết trung bình: **4.6 / 5.0**. | - 1/8 bạn cho rằng nếu bay quen thì chỉ cần đặt xe công nghệ trước 2 tiếng theo thói quen là đủ, không cần công cụ mới. | Nhóm xác nhận tính cấp bách ở nhóm đối tượng "không thường xuyên di chuyển" và bổ sung tính năng đồng bộ trực tiếp vào Google Calendar thay vì bắt cài thêm một app độc lập cồng kềnh. |
| Log / ticket / review (Diễn đàn du lịch & sân bay) | 12 reviews | Hành khách thường xuyên than phiền về việc Google Maps chỉ dẫn đường tới cổng trả khách (drop-off), nhưng khi bước vào nhà ga thì gặp cảnh xếp hàng check-in và an ninh kéo dài hơn 40 phút, suýt trễ chuyến. | Các hãng bay giá rẻ ít khi cập nhật dữ liệu hàng chờ check-in nội bộ theo thời gian thực. | Nhóm bổ sung module ước lượng thời gian thủ tục nội bộ sân bay (Terminal & Security buffer) phân hóa theo loại vé (có hành lý ký gửi vs. chỉ có balo xách tay). |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không nằm ở việc làm phép tính cộng trừ thời gian đơn thuần, mà nằm ở sự mơ hồ và căng thẳng tâm lý trước các biến số rủi ro không lường trước (kẹt xe đường dẫn, hàng chờ an ninh quá tải, delay chuyến bay) và sự mệt mỏi lãng phí khi phải dùng Rule tĩnh cộng dồn 2-3 tiếng chờ đợi vô ích tại sân bay.
```

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| --- | --- | --- | --- | --- | --- |
| **TripIt** (Concur / SAP) | <https://www.tripit.com/> | Bước 1 & Bước 5: Tự động trích xuất thông tin vé từ email và tập trung thành 1 Master Itinerary | Tự động parse dữ liệu email phi cấu trúc rất mượt, tự động đồng bộ vào Calendar | Hoàn toàn tĩnh: Không kết nối dữ liệu giao thông đường bộ real-time, không tính thời gian thủ tục nội bộ sân bay | Tận dụng cơ chế trích xuất vé tự động (parse PNR) để giảm thao tác nhập liệu của người dùng, nhưng không dừng lại ở lịch trình tĩnh |
| **Google Maps / Waze** | <https://www.google.com/maps> | Bước 3 & một phần Bước 4: Tính toán thời gian di chuyển đường bộ theo traffic real-time & historical | Dữ liệu giao thông cực mạnh, có tính năng thông báo giờ khởi hành (Depart/Arrive time alert) | Chỉ tính đến cổng sân bay (drop-off point), hoàn toàn mù mờ về thời gian xếp hàng check-in, soi chiếu an ninh và di chuyển ra Gate | Tận dụng Google Maps Distance Matrix API cho chặng đường bộ, nhưng bắt buộc phải bổ sung module thời gian đệm nội khu sân bay |
| **FlightAware / App Hãng bay** (Vietjet, VNA) | <https://flightaware.com/> | Xử lý biến số real-time: Theo dõi trạng thái chuyến bay, cảnh báo delay, đổi cổng ra máy bay | Kết nối trực tiếp hệ thống radar hàng không, thông báo đẩy (push notification) rất nhanh | Chỉ dừng ở việc gửi cảnh báo (Alert) bị động; không tự động tính toán lại toàn bộ chuỗi lịch trình cá nhân khi có delay | Cần đóng vai trò AI Agent chủ động: Khi FlightAware báo delay 45 phút → Agent tự động suy luận và tính toán lại giờ xuất phát tối ưu mới |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Thị trường hiện bị phân mảnh nghiêm trọng (Fragmented Experience): người dùng phải tự mở cùng lúc 3 ứng dụng riêng biệt (TripIt để xem vé, Google Maps để xem kẹt xe, FlightAware để xem delay) nhưng không có bên nào xâu chuỗi thành một lộ trình hành động thích ứng thống nhất. Nhóm KHÔNG tự build lại bản đồ giao thông hay hệ thống radar hàng không, mà BUILD một AI Agent đóng vai trò nhạc trưởng điều phối: tích hợp 3 luồng dữ liệu này vào 1 Dynamic Adaptive Timeline, ước lượng thời gian thủ tục nội bộ sân bay và đưa ra khuyến nghị bán tự động (Human-in-the-loop).
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

```text
[1 Tra cứu vé & giờ bay: 5'] → [2 Tra quy định hành lý & thủ tục: 10'] → [3 Tìm phương tiện & tuyến đường: 10'] → [4 Tính toán trừ hao biến số kẹt xe/thủ tục: 25' - BOTTLENECK] → [5 Ghi chú lịch trình & cài báo thức: 10']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
| --- | --- | --- | --- | --- | --- |
| 1 | Hành khách | Email/SMS xác nhận đặt chỗ | Thông tin giờ bay, số hiệu, mã đặt chỗ | 5 phút / mỗi chuyến | Mất công tìm lại email giữa nhiều tin nhắn rác |
| 2 | Hành khách | Website hãng bay, thông tin hành lý | Nắm quy định giấy tờ, cân nặng hành lý | 10 phút / mỗi chuyến | Dễ nhầm lẫn giữa quy định xách tay và ký gửi |
| 3 | Hành khách | Google Maps, app gọi xe (Grab/Be) | Lộ trình và thời gian chạy xe ước tính | 10 phút / mỗi chuyến | Chỉ thấy thời gian đường thông, chưa tính giờ cao điểm |
| 4 | Hành khách | Trực giác cá nhân, hỏi bạn bè/người thân | Quyết định giờ rời nhà (trừ hao 2-3 tiếng) | 25 phút / mỗi chuyến | **BOTTLENECK CHÍNH**: Căng thẳng, tính toán cảm tính, sợ trễ |
| 5 | Hành khách | Điện thoại cá nhân, ứng dụng Note/Alarm | Danh sách việc cần làm, 3-4 báo thức | 10 phút / mỗi chuyến | Rời rạc, nếu chuyến bay delay phải tự chỉnh lại từ đầu |

**Bottleneck chính (2-3 câu):**

```text
Bước 4 là điểm nghẽn lớn nhất: Người dùng mất 25 phút trong trạng thái căng thẳng để tính toán thủ công và trừ hao thời gian cho hàng loạt biến số khó lường (kẹt xe đường Trường Sơn/Cộng Hòa, thời gian xếp hàng ký gửi hành lý, cửa an ninh quá tải). Việc trừ hao cảm tính dẫn đến hai thái cực tiêu cực: hoặc đi quá sớm gây mệt mỏi vạ vật 2-3 tiếng tại sân bay, hoặc đánh giá thấp rủi ro dẫn đến nguy cơ trễ chuyến bay và thiệt hại tài chính nặng nề.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Nhận thông tin vé & điểm đi: 1' - Máy/Rule]
→ [2 AI Agent tổng hợp đa biến số real-time: 1' - AI Engine]
→ [3 AI đề xuất 2-3 kịch bản di chuyển kèm rủi ro: 1' - AI]
→ [4 Hành khách review & bấm xác nhận kịch bản: 2' - HUMAN BOUNDARY]
→ [5 Sync Calendar & Giám sát thích ứng thông minh: Tự động - AI Agent]


Fallback: Nếu mất kết nối API hoặc AI gặp lỗi suy luận → Hệ thống tự động kích hoạt Rule tĩnh dự phòng: [Giờ xuất phát = Giờ bay - 120' (nội địa) / 150' (quốc tế) - Thời gian Google Maps + 20' buffer], đồng thời gửi thông báo cảnh báo để người dùng chủ động kiểm tra thủ công.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
| --- | ---: | ---: | --- |
| Tổng thời gian | 60 phút | 10-12 phút | Bấm giờ toàn bộ quá trình từ lúc nhập vé đến khi chốt lịch trình |
| Số bước | 5 bước | 5 bước | Số lượng màn hình/thao tác người dùng trải qua |
| Số bước thủ công | 5/5 bước | 1/5 bước | Đếm số bước đòi hỏi người dùng phải tự tính nhẩm/nhập liệu |
| Bottleneck chính | Tự tính toán trừ hao cảm tính (25') | Hành khách review và bấm chọn kịch bản (2') | Thời gian người dùng dừng lại ở bước ra quyết định |
| Risk mới | Không có AI ảo giác (nhưng sai do cảm tính) | Rủi ro dữ liệu API trễ / AI ảo giác thời gian đệm | Đánh giá sai lệch giữa dự báo của AI và thời gian thực tế |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
| --- | --- |
| **Actor** | Sinh viên và người di chuyển xa không thường xuyên (1-3 lần/năm), chưa có nhiều kinh nghiệm di chuyển máy bay, rất nhạy cảm với rủi ro trễ giờ nhưng có ngân sách eo hẹp và không muốn lãng phí thời gian ngồi chờ mệt mỏi. |
| **Workflow** | Tra cứu email lấy thông tin vé → kiểm tra quy định hành lý hãng bay → tra cứu Google Maps tìm tuyến đường → tự tính nhẩm thời gian trừ hao kẹt xe và thủ tục sân bay → ghi chú vào điện thoại và đặt báo thức thủ công. |
| **Bottleneck** | Bước tính toán thời gian xuất phát dự phòng (25 phút) do phải xử lý quá nhiều biến số động (giao thông giờ cao điểm, hàng chờ check-in, soi chiếu an ninh) một cách thủ công và đầy lo âu. |
| **Impact** | Tốn 60 phút chuẩn bị cho mỗi chuyến đi; gây căng thẳng tinh thần kéo dài; dẫn đến việc phải có mặt quá sớm 2-3 tiếng gây mệt mỏi kiệt sức, hoặc nếu tính sai sẽ bị trễ chuyến bay gây tổn thất tài chính lớn (mất vé, mua vé mới). |
| **Success Metric** | Giảm tổng thời gian lập kế hoạch từ 60 phút xuống dưới 10 phút; tỷ lệ hành khách hoàn thành thủ tục tại sân bay trong khung an toàn đạt ≥ 95%; sai số dự báo thời gian đến cửa an ninh trong khoảng ±15 phút. |
| **Boundary** | Hệ thống không tự động mua vé/đổi vé máy bay; không tự động book xe taxi khi chưa có sự đồng ý của người dùng; chỉ đưa ra khuyến nghị kịch bản và để người dùng tự xác nhận quyết định cuối cùng. |

**Câu hỏi AI phản biện v0 (nếu có):**

- Field nào mơ hồ: Metric "loại bỏ 100% rủi ro trễ giờ" ở bản nháp ban đầu quá ảo tưởng và thiếu thực tế trong bối cảnh giao thông phức tạp; ranh giới giữa việc AI tự quyết định và con người quyết định chưa rõ ràng.
- Tôi sửa gì: Nhóm đã hạ cam kết xuống "Tỷ lệ hoàn thành thủ tục trong khung an toàn đạt ≥ 95%", đồng thời bổ sung cơ chế Human-in-the-loop (AI đề xuất phương án kèm phân tích rủi ro 5%, 15% để con người duyệt).

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Dù mốc đóng quầy/đóng cổng là cố định theo quy định hàng không, nhưng việc xác định "thời gian đệm tối ưu" (buffer time), lựa chọn tuyến đường, cân bằng giữa rủi ro kẹt xe và sự mệt mỏi khi chờ đợi lâu tại sân bay phụ thuộc rất lớn vào khẩu vị rủi ro và ngữ cảnh cá nhân của hành khách (đi một mình vs. đi nhóm, có hành lý ký gửi hay chỉ có balo xách tay, chuyến bay sáng sớm 5h sáng vs. bay giờ cao điểm chiều). Không có một con số cố định duy nhất đúng cho mọi đối tượng.
- Độ phức tạp: [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Bài toán đòi hỏi tích hợp và tổng hợp liên tục ít nhất 3 nguồn dữ liệu thời gian thực biến động độc lập: (1) Radar hàng không & trạng thái chuyến bay (FlightAware API), (2) Mật độ giao thông và thời gian di chuyển đường bộ (Google Maps / Waze API), (3) Thời gian làm thủ tục nội bộ sân bay và tình hình thời tiết. Kết quả bước sau hoàn toàn phụ thuộc vào biến động của bước trước và kích hoạt chuỗi tính toán lại liên tục.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ phức tạp cao / Độ mơ hồ cao (Complex & Adaptive Context)
```

**Vì sao (2-3 câu):**

```text
Bài toán đòi hỏi phải xử lý nhiều luồng dữ liệu thời gian thực từ các nguồn không đồng nhất (chuyến bay, giao thông, thủ tục nội bộ) trong một môi trường biến động liên tục. Đồng thời, kết quả đầu ra không phải là một phép tính cộng trừ số học đơn thuần mà là một kịch bản thích ứng đa biến số (adaptive plan) cần cân bằng giữa an toàn tính mạng/chuyến bay và sự thuận tiện, thoải mái cho người dùng.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
| --- | --- | --- | --- | --- |
| **Rule** | Cố định công thức tĩnh: [Giờ xuất phát = Giờ bay - 120 phút (nội địa) hoặc 180 phút (quốc tế) - Thời gian di chuyển bình thường trên Google Maps]. | Đủ cho người đi quen, chuyến bay ban ngày điều kiện thời tiết lý tưởng, không có hành lý ký gửi và không gặp sự cố giao thông. | Cực kỳ cứng nhắc: bắt người bay chuyến 5h sáng phải dậy từ 2h chờ vật vờ 3 tiếng; hoàn toàn bất lực khi chuyến bay bị delay hoặc đường bị tắc nghẽn cục bộ. | **Dùng làm Fallback Safety Boundary**: Kích hoạt khi mất kết nối mạng hoặc hệ thống AI gặp sự cố. |
| **Workflow** | Chuỗi tự động hóa tuyến tính cố định: [Lấy vé từ email → tra Google Maps đường đi → tạo sự kiện trên Google Calendar và đặt báo thức]. | Đủ cho khâu khởi tạo lịch trình ban đầu nếu tất cả các yếu tố giữ nguyên không đổi suốt 24h trước giờ bay. | Thiếu khả năng thích ứng động (Dynamic adaptation): khi chuyến bay đổi giờ, dời cổng hoặc đường bị kẹt xe bất ngờ, workflow không tự suy luận để điều chỉnh chuỗi hành động mà phải chạy lại từ đầu. | **Dùng cho Bước 1 & Bước 5**: Parse dữ liệu vé và đồng bộ lịch trình vào Google Calendar. |
| **Agent** | AI Agent có vòng lặp (Perception - Reasoning - Action): Liên tục lắng nghe dữ liệu chuyến bay, thời tiết và giao thông; khi phát hiện biến cố, tự suy luận tác động domino, gọi tool tính lại thời gian đệm và đề xuất kịch bản thích ứng mới cho người dùng. | Cần thiết khi môi trường có nhiều biến số ngẫu nhiên thay đổi theo thời gian thực (delay, kẹt xe, đổi gate) cần phản ứng nhanh và thông minh. | Rủi ro ảo giác (hallucination), sai lệch dữ liệu API làm trễ chuyến bay; chi phí gọi LLM và gọi API liên tục. Giải quyết bằng: **Human-in-the-loop & Safety Guardrails**. | **CHỌN LÀM KIẾN TRÚC CỐT LÕI**: Dùng cho Bước 2, Bước 3 và cơ chế Giám sát thích ứng thông minh (Proactive Monitoring). |

**5 câu hỏi chốt (trả lời câu đầy đủ):**

1. **Rule có giải được 70-80% case không?**  
   Rule tĩnh (cộng cố định 2-3 tiếng) có thể giúp 70-80% trường hợp không bị trễ chuyến bay về mặt lý thuyết an toàn thô thiển, NHƯNG nó thất bại hoàn toàn trong việc giải quyết pain point cốt lõi: gây lãng phí 2-3 tiếng ngồi chờ mệt mỏi tại sân bay, phá vỡ giấc ngủ (đặc biệt với chuyến sáng sớm) và hoàn toàn tê liệt khi có biến số đột xuất (delay chuyến bay kéo dài hoặc kẹt xe nghiêm trọng). Vì vậy, Rule không giải quyết được bài toán trải nghiệm và tối ưu thời gian.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?**  
   Quy trình KHÔNG đi thẳng một đường mà rẽ nhánh liên tục theo sự kiện thời gian thực (Event-driven branching): Nếu chuyến bay delay > 30 phút → rẽ nhánh đánh giá lại mật độ giao thông ở khung giờ mới để lùi giờ đón xe; nếu tuyến đường chính kẹt đỏ → rẽ nhánh tìm phương tiện khác (ví dụ metro/xe máy thay vì taxi); nếu hành khách có hành lý ký gửi → rẽ nhánh cộng thêm 30-40 phút vào hàng chờ quầy check-in.
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?**  
   CÓ. Hệ thống cần khả năng Tool Calling để chủ động truy vấn FlightAware API (trạng thái bay), Google Maps Distance Matrix API (tình trạng kẹt xe) và Weather API. Khi nhận tín hiệu thay đổi, Agent phải tự lập luận (reasoning) về tác động domino và tự động lập lại kế hoạch (re-planning) để sinh ra các kịch bản hành động kịp thời.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?**  
   Nhờ thiết kế Bán tự động (Human-in-the-loop), hành khách là người phát hiện đầu tiên khi nhìn vào bảng so sánh kịch bản (hiển thị rõ mốc an toàn, mốc rủi ro và thời gian đệm dự phòng tối thiểu). Nếu thấy AI đề xuất giờ xuất phát quá sát, hành khách chỉ mất 5-10 giây để chọn kịch bản an toàn hơn hoặc tự điều chỉnh tăng thời gian đệm.
5. **Có hạ được từ Agent → Workflow → Rule không?**  
   HOÀN TOÀN CÓ THỂ (Graceful Degradation). Nếu hệ thống Agent mất kết nối hoặc hết quota gọi model, hệ thống tự động hạ cấp xuống Workflow (đồng bộ vé và lộ trình tĩnh), và nếu mất toàn bộ API bên ngoài thì hạ tiếp xuống Rule tĩnh dự phòng (áp dụng công thức chuẩn an toàn của hãng bay: có mặt trước 120 phút + 20 phút buffer kẹt xe).

**Mức chọn:**

```text
Agent (Cụ thể: AI Travel Agent với cơ chế Human-in-the-loop)
```

**Vì sao chọn (3-4 câu):**

```text
Nhóm chọn mức Agent vì môi trường di chuyển ra sân bay là một môi trường động đa biến số thời gian thực (chuyến bay hoãn/hủy, kẹt xe cục bộ, thay đổi cổng ra máy bay) đòi hỏi hệ thống phải có khả năng tự động cảm nhận, gọi công cụ tra cứu và lập lại kế hoạch thích ứng liên tục. Chỉ có kiến trúc Agent mới có thể xâu chuỗi liền mạch giữa thông tin vé bay tĩnh, tình hình giao thông biến động và quy trình nội bộ sân bay thành một kế hoạch hành động thống nhất. Đồng thời, việc kết hợp cơ chế Human-in-the-loop (AI đề xuất phương án kèm phân tích rủi ro, người dùng duyệt cuối cùng) giúp tận dụng tối đa sự linh hoạt thông minh của AI mà vẫn triệt tiêu được rủi ro hệ thống như thành viên Dương và Việt đã quan ngại.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Nhóm không chọn Rule vì quy tắc cố định "luôn đi trước 2-3 tiếng" quá thô sơ, gây lãng phí thời gian và không phản ứng được khi chuyến bay bị hoãn hoặc đổi lịch trình. Nhóm không chọn Workflow đơn thuần vì workflow chỉ chạy theo đường thẳng một chiều từ A đến B, không có khả năng tự động quan sát môi trường bên ngoài để rẽ nhánh và tự động tái tính toán lộ trình khi có sự cố phát sinh.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
| --- | --- |
| **Actor** | Sinh viên và người di chuyển xa không thường xuyên (1-3 lần/năm) tại các đô thị lớn (Hà Nội, TP.HCM), tự di chuyển ra sân bay bằng phương tiện cá nhân hoặc xe công nghệ, nhạy cảm cao với nguy cơ trễ giờ nhưng có ngân sách eo hẹp và mong muốn tối ưu hóa thời gian chờ đợi. |
| **Workflow** | Nhập mã vé/chụp ảnh vé → AI tự động đồng bộ giờ bay và quy định hành lý → AI giám sát giao thông real-time & chuyến bay → AI đề xuất 2-3 kịch bản giờ xuất phát kèm tỷ lệ rủi ro → Hành khách xác nhận kịch bản → AI sync lịch và theo dõi cảnh báo biến số đến khi lên tàu bay. |
| **Bottleneck** | Khâu tính toán thủ công và trừ hao cảm tính thời gian xuất phát (mất 25 phút), do người dùng không có đủ dữ liệu tổng hợp về mật độ giao thông theo giờ và thời gian xếp hàng thủ tục nội bộ sân bay dẫn đến tâm lý hoang mang, căng thẳng. |
| **Impact** | Tiết kiệm 50 phút chuẩn bị cho mỗi chuyến đi (từ 60' xuống 10'); loại bỏ tình trạng vật vờ mệt mỏi 2-3 tiếng tại sân bay cho các chuyến bay sáng sớm; đảm bảo an toàn chuyến bay với tỷ lệ rủi ro trễ giờ được kiểm soát chặt chẽ dưới 5%. |
| **Success Metric** | (1) Tổng thời gian lên lịch trình chi tiết < 10 phút;<br>(2) Tỷ lệ hoàn thành thủ tục tại sân bay trong mốc an toàn đạt ≥ 95%;<br>(3) Sai số dự báo thời gian di chuyển và làm thủ tục trong khoảng ±15 phút so với thực tế. |
| **Boundary** (làm / không làm) | **LÀM**: Phân tích vé, tích hợp API radar bay & giao thông, tính toán thời gian đệm thông minh, đề xuất kịch bản và cảnh báo chủ động.<br>**KHÔNG LÀM**: Không tự ý thay đổi vé bay; không tự động đặt xe hay thanh toán tiền khi người dùng chưa bấm duyệt; không thay thế quyết định của hành khách. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp ngay sau Bước 1 (khi có thông tin vé và điểm xuất phát) để tự động thu thập dữ liệu và tính toán, và can thiệp trước Bước 4 (trình bày các kịch bản trực quan cho hành khách bấm duyệt thay vì để họ phải tự tính nhẩm). |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Agent (Human-in-the-loop)**: Vì chỉ có Agent mới có khả năng tự động gọi tool và tái lập kế hoạch thích ứng theo đa biến số real-time, trong khi sự kiểm soát của con người đảm bảo tính an toàn tối thượng. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | **Rủi ro lớn nhất**: AI ảo giác thời gian đệm quá sát hoặc API giao thông bị chậm dẫn đến hành khách bị trễ chuyến bay.<br>**Người thật kiểm tra**: Hành khách trực tiếp review kịch bản trên giao diện trực quan trước khi xác nhận; hệ thống cài đặt chốt chặn an toàn cứng (Hard safety buffer: tối thiểu 45 phút trước giờ đóng quầy đối với nội địa). |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
| --- | --- | --- |
| Actor + workflow rõ chưa? | **Yes** | Actor là sinh viên/khách đi xa ít lần/năm; workflow 5 bước với ranh giới tự động hóa và điểm duyệt của người dùng được phân định rõ ràng. |
| Baseline + metric đo được chưa? | **Yes** | Baseline thời gian là 60 phút (trong đó bottleneck tính toán chiếm 25 phút); Target rõ ràng: thời gian < 10 phút, tỷ lệ đúng giờ ≥ 95%, sai số ±15 phút. |
| Data/input đủ dùng chưa? | **Yes** | Dữ liệu đầu vào từ người dùng đơn giản (mã vé/ảnh vé, địa chỉ nhà); các API bên thứ 3 (Google Maps Distance Matrix, FlightAware) đều có tài liệu kỹ thuật và khả năng tích hợp sẵn sàng. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Hậu quả được chặn đứng nhờ cơ chế Human-in-the-loop và Hard Safety Buffer tối thiểu; nếu AI sai sót thì người dùng vẫn có đủ thời gian đệm an toàn để không bị trễ chuyến. |
| Có người review/owner không? | **Yes** | Hành khách chính là người sở hữu và trực tiếp bấm phê duyệt phương án di chuyển cuối cùng. |
| Có cách non-AI đơn giản hơn không? | **Yes** | Có cách non-AI (Google Maps + Rule cộng đại 2-3 tiếng), nhưng nhóm đã chứng minh giải pháp này gây lãng phí lớn về thể lực/thời gian và không giải quyết được biến số thời gian thực. |

**Decision:**

```text
Go với phạm vi Pilot có kiểm soát (Human-in-the-loop Pilot)
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Bài toán có đối tượng sử dụng rõ ràng, nỗi đau thực tế đã được kiểm chứng qua phỏng vấn và survey, với baseline thời gian và chỉ số thành công đo lường được cụ thể. Kiến trúc AI Agent kết hợp Human-in-the-loop giải quyết triệt để khoảng trống thị trường mà các công cụ lớn (TripIt, Google Maps, FlightAware) đang bỏ sót, tạo ra một trải nghiệm liền mạch từ nhà ra đến cửa máy bay. Các rủi ro kỹ thuật về sai lệch dữ liệu hay ảo giác đã được kiểm soát hoàn toàn bằng các chốt chặn an toàn cứng (hard safety buffer) và cơ chế người dùng tự phê duyệt kịch bản. Do đó, dự án đủ điều kiện để triển khai thử nghiệm thực tế ngay trong phạm vi lab.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data sử dụng: Dữ liệu vé bay thật của 5-10 chuyến đi thực tế của các thành viên trong nhóm và bạn bè sinh viên trong tháng tới (bao gồm cả chặng Tân Sơn Nhất và Nội Bài).
- Cách chạy thử nghiệm: Chạy workflow bán tự động (Semi-automated): Dùng script gọi Google Maps API và FlightAware API để lấy dữ liệu thực, đưa vào Prompt Agent chuẩn hóa để sinh ra 2 kịch bản (An toàn vs. Tối ưu thời gian), sau đó gửi cho hành khách duyệt qua giao diện web đơn giản.
- Đo lường 3 chỉ số then chốt:
  1. Thời gian hành khách thao tác từ lúc gửi vé đến khi chốt lịch trình (Mục tiêu: < 5 phút).
  2. Độ lệch giữa thời gian Agent dự báo đến sân bay và thời gian thực tế ghi nhận (Mục tiêu: sai số < 15 phút).
  3. Mức độ an tâm và hài lòng của hành khách theo thang điểm 1-5 (Mục tiêu: đạt ≥ 4.5/5 điểm).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm đã chọn Go. Tuy nhiên nếu phải mở rộng ra quy mô lớn, nhóm sẽ cần kiểm chứng thêm độ trễ API của FlightAware trong các ngày bão lớn).
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng. Nếu quay về cách non-AI, nhóm sẽ xây dựng một bảng tính Excel thông minh tích hợp Google Calendar với các quy tắc cộng giờ cố định cho từng khung giờ bay).
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
- Nếu trong quá trình pilot phát hiện tỷ lệ dự báo sai lệch thời gian di chuyển > 25 phút vượt quá 10% tổng số lượt chạy.
- Nếu có bất kỳ trường hợp nào hành khách đến sân bay sát giờ đóng quầy dưới 15 phút do lỗi tính toán của Agent.
- Khi đó: Ngay lập tức ngắt quyền lập lịch tự động của Agent, hạ cấp toàn bộ hệ thống về Rule tĩnh cố định (Giờ bay - 120 phút nội địa + thời gian Google Maps + 20 phút buffer), đồng thời gửi SMS/thông báo khẩn cấp khuyến cáo người dùng tự theo dõi trực tiếp.
```

---

### Self-check nộp phần 02 (nhóm)

- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
