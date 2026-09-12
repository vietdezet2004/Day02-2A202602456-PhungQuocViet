# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Phùng Quốc Việt
- Mã học viên: 2A202602456
- Vai trò / bối cảnh: Sinh viên năm cuối PTIT
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Sinh viên năm cuối PTIT
  - Sale laptop part time

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
| --- | --- | --- | --- | --- |
| 1 | Lặp lại | Viết tài liệu postman và giải thích payload cho Dev Frontend khi Dev Backend viết các endpoint mới | Dev BE, dev FE | 30 phút mỗi lần viết endpoint mới của Dev BE, có thể hỏi miệng khảong 3-4 lần của Dev FE, Nhóm có 5 Dev thì cả 5/5 đều đã gặp phải trường hợp này |
| 2 | Tốn thời gian | Điều chỉnh CV cho từng công ty khác nhau | Tôi | Có khi để viết CV vào 1 công ty hết 1 tiếng nhưng khi apply thì báo cần có kinh nghiệm 3 năm |
| 3 | Pain từ người khác | Thành viên nhóm đồ án gửi bài báo cáo không theo format | Leader | Mất 30 phút để ngồi đọc lại và sửa lại cho đúng format của bài |
| 4 | Pain từ người khác | Sắp xếp 1 lịch họp nhóm đồ án với nhau qua mess nhưng mỗi người 1 việc làm khác nhau lệch giờ | cả nhóm | 30-40 phút trao đổi qua lại và gần chốt thì có thành viên mới bắt đầu vào |
| 5 | Tốn thời gian | Viết meeting note trong các cuộc họp nhóm đồ án | cả nhóm | 30-40 phút mỗi cuộc họp |
| 6 | AI có thể tốt hơn | Xem và so sánh tìm laptop phù hợp cho khách hàng | Sale | tìm cấu hình, so sánh cấu hình của 2 máy hết 10 phút, chưa kể khách hàng chọn so sánh nhiều laptop tìm cái ok nhất |
| 7 | AI có thể tốt hơn | Tự luyện đề IELTS/TOEIC Reading, khi làm sai thì không có ai giải thích cặn kẽ tại sao câu đó sai, tự tra cứu rất mơ hồ. | Đa số người học tiếng anh | Làm xong đề 2 tiếng, nhưng tốn thêm 2 tiếng nữa chỉ để tra lời giải không có giải thích chi tiết để hiểu. |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**

- Prompt đã hỏi: "Tôi là sinh viên năm cuối IT và có làm part-time Sale. Hãy liệt kê giúp tôi 5-10 vấn đề thường gặp lặp đi lặp lại và tốn thời gian trong công việc hàng ngày."
- Ý dùng được: Vấn đề viết doc API cho Frontend, vấn đề so sánh laptop, luyện đề IELTS/TOEIC.
- Ý bỏ vì không phải pain thật: Vấn đề quản lý task cá nhân (vì đã có thói quen dùng Notion/Trello rất tốt rồi, không phải pain lớn).

**Self-check Phase 1:**

- [v] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [v] Dùng ít nhất 3/4 lăng kính
- [v] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
| --- | --- | --- | --- |
| 1 | Tự luyện đề IELTS/TOEIC Reading, khi làm sai thì không có ai giải thích cặn kẽ tại sao câu đó sai, tự tra cứu rất mơ hồ. | 1. Nỗi đau thật (mất 2 tiếng tra cứu không hiểu).<br>2. Workflow rõ: Làm bài -> Check key -> Tra logic.<br>3. AI mạnh về giải thích ngôn ngữ. | AI có ảo giác và đưa ra suy luận logic sai để phù hợp với đáp án  hay không? |
| 2 | Xem và so sánh tìm laptop phù hợp cho khách hàng | 1. Workflow lặp lại, tốn thời gian lọc cấu hình.<br>2. Impact đo lường được bằng thời gian phản hồi. | Dữ liệu giá cả và tồn kho thay đổi liên tục, làm sao cung cấp đủ context cho AI phân tích? |
| 3 | Viết tài liệu postman và giải thích payload cho Dev Frontend khi Dev Backend(Tôi) viết các endpoint mới | 1. Actor (tôi) & bottleneck (gõ mô tả) rõ ràng.<br>2. Lặp lại mechanic 100%.<br>3. Rất dễ kiểm chứng output. | AI có tự hiểu được business logic sâu bên trong để giải thích các field chuẩn xác không? |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Giải thích chi tiết câu sai Reading

```text
Problem 1 câu: Mất quá nhiều thời gian tự tra cứu và hiểu lý do sai các câu hỏi IELTS/TOEIC Reading, nhưng giải thích tìm được vẫn mơ hồ.

Actor: Người học tiếng Anh (đang tự luyện đề)

Thời điểm / bối cảnh: Khi vừa hoàn thành một bài test Reading, đang check key và cần sửa lỗi sai.

Current workflow 3-7 bước:
1. Hoàn thành bài kiểm tra Reading (ví dụ 60 phút).
2. So sánh đáp án với answer key (5 phút).
3. Xác định các câu làm sai.
4. Tự tra cứu lý do sai trên các trang web, diễn đàn (30-60 phút).
5. Vẫn mơ hồ không hiểu logic cốt lõi.

Bottleneck: Bước 4 (Tra cứu tốn thời gian nhưng nguồn giải thích không chi tiết / không cá nhân hoá).

Impact: Tốn thêm 2 tiếng đồng hồ sau mỗi bài test chỉ để hiểu vì sao sai, gây nản chí, mệt mỏi.

Success metric: Giảm thời gian tìm hiểu giải thích mỗi câu sai từ 15-30 phút xuống còn 1-2 phút, hiểu rõ 100% logic câu trả lời.

Non-AI alternative: Lên các group tiếng Anh hỏi và chờ người khác rep, hoặc thuê gia sư chữa bài.

AI hypothesis: AI có thể nhận bài đọc (text) + câu hỏi + đáp án học viên chọn, từ đó phân tích logic, trích dẫn đúng câu trong đoạn văn và giải thích tại sao đáp án của học viên sai một cách cực kỳ chi tiết.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 120 phút tra cứu

[1 Làm bài: 60'] → [2 Check key: 5'] → [3 Tự tra cứu giải thích: 120']  <-- bottleneck

FUTURE STATE — 15 phút tra cứu

[1 Làm bài: 60'] → [2 Check key: 5'] → [3 Nhập câu sai cho AI giải thích: 10'] → [4 Review & Note: 5']  <-- human boundary

Fallback: Nếu AI giải thích không phục, yêu cầu AI giải thích lại bằng tiếng Việt đơn giản hơn hoặc trích dẫn lại.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Lọc và so sánh laptop cho khách hàng

```text
Problem 1 câu: Tốn thời gian lọc cấu hình và tạo bảng so sánh laptop thủ công mỗi khi tư vấn cho khách hàng.

Actor: Nhân viên tư vấn Sale (Tôi)

Thời điểm / bối cảnh: Khi khách hàng cung cấp yêu cầu (nhu cầu sử dụng, ngân sách) và đang chờ tư vấn các mẫu laptop phù hợp.

Current workflow 3-7 bước:
1. Lắng nghe và ghi nhận nhu cầu của khách hàng.
2. Tìm kiếm trên hệ thống các mẫu laptop đáp ứng tiêu chí (10-15 phút).
3. Chọn ra 2-3 mẫu nổi bật.
4. So sánh thông số cấu hình, ưu nhược điểm từng mẫu thủ công (10 phút).
5. Gửi cho khách hàng và đợi phản hồi.

Bottleneck: Bước 2 và Bước 4 (Tra cứu phân mảnh trên hệ thống và tự tổng hợp bảng so sánh).

Impact: Mất 15-20 phút cho mỗi khách hàng. Khách hàng phải chờ đợi lâu, làm giảm tỷ lệ chốt sale.

Success metric: Rút ngắn thời gian từ lúc nhận nhu cầu đến lúc đưa ra được bảng so sánh xuống dưới 5 phút.

Non-AI alternative: Chuẩn bị sẵn file excel hoặc template so sánh các dòng máy phổ biến để copy-paste.

AI hypothesis: AI (được cung cấp database/context về sản phẩm) nhận đầu vào là nhu cầu của khách, tự động chọn ra 2-3 máy và sinh ra bảng so sánh dễ đọc kèm lời khuyên.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 25 phút

[1 Nhận nhu cầu: 5'] → [2 Tìm mẫu laptop: 10'] <-- bottleneck → [3 So sánh thủ công: 10'] <-- bottleneck

FUTURE STATE — 8 phút

[1 Nhận nhu cầu: 5'] → [2 AI tự lọc và gen bảng so sánh: 1'] → [3 Human check lại giá/tồn kho: 2'] <-- human boundary

Fallback: Nếu AI gợi ý máy sai nhu cầu, tự lấy mã máy nhập vào yêu cầu AI gen lại bảng so sánh.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Gen Doc & Giải thích API Payload

```text
Problem 1 câu: Tốn thời gian lặp đi lặp lại việc viết mô tả Postman và phải giải thích lại payload cho Frontend.

Actor: Dev Backend (Tôi)

Thời điểm / bối cảnh: Vừa code xong 1 endpoint mới, cần cập nhật tài liệu để bàn giao cho Dev Frontend ghép nối.

Current workflow 3-7 bước:
1. Code xong logic của API endpoint.
2. Mở Postman, tạo request mới (URL, Auth, Header).
3. Chạy thử, copy Response và điền JSON Body.
4. Viết mô tả ý nghĩa cho từng field thủ công (15 phút).
5. Frontend đọc không hiểu lại chat hỏi (5-10 phút).

Bottleneck: Bước 4 (Viết mô tả thủ công rất lặp lại).

Impact: Mất thêm 30 phút rườm rà sau mỗi endpoint. Đôi khi lười viết thiếu doc làm Frontend phải hỏi đi hỏi lại 3-4 lần.

Success metric: Thời gian hoàn thiện doc Postman < 5 phút; số lần Frontend hỏi lại giảm xuống 0.

Non-AI alternative: Dùng Swagger gen doc tự động (nhưng vẫn phải viết annotation mỏi tay).

AI hypothesis: Chỉ cần ném file code (DTO/Controller) vào, AI sẽ tự hiểu logic và gen ra đoạn JSON mô tả đầy đủ các trường (hoặc format Markdown), có thể import thẳng vào Postman.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 30 phút

[1 Code endpoint] → [2 Tạo request Postman: 5'] → [3 Viết mô tả từng field: 15'] <-- bottleneck → [4 Trả lời FE: 10']

FUTURE STATE — 5 phút

[1 Code endpoint] → [2 Ném DTO vào AI gen mô tả JSON: 1'] → [3 Review lại và đưa vào Postman: 2'] <-- human boundary

Fallback: Tự bổ sung field nếu AI nhận diện sót, hoặc sửa lại mô tả bằng tay nếu business logic quá đặc thù.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #3: Gen Doc & Giải thích API Payload cho Frontend
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là công việc tôi phải làm hàng ngày, tính chất lặp lại 100%. Nếu có công cụ tự động hóa việc này, tôi tiết kiệm được ít nhất 30 phút cho mỗi API mới, và giảm hoàn toàn thời gian phải chat support giải thích cho Frontend, giúp cả team tăng tốc độ làm việc. Ngoài ra, việc dùng AI đọc code DTO để sinh ra doc rất khả thi và có thể đánh giá tính chính xác ngay lập tức.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Làm sao để AI hiểu được các business logic phức tạp không thể hiện trực tiếp qua tên biến (ví dụ: status = 2 nghĩa là 'Đang xử lý') để sinh doc cho đúng?
2. Nếu dự án có hàng chục file DTO lồng nhau, làm thế nào để workflow gom đủ context cho AI mà không bị miss trường thông tin?
```

**AI phản biện Card (nếu có):**

- Điểm yếu AI chỉ ra: Quá trình truyền context cho AI (các file DTO liên quan lồng nhau) có thể dễ bị sót, dẫn đến AI "bịa" ra mô tả sai lệch với business logic đặc thù.
- Tôi sửa gì: Đã bổ sung fallback rõ ràng là người dùng bắt buộc phải review lại và sửa thủ công nếu gặp logic quá đặc thù.

### Self-check nộp phần 01

- [v] Có 5+ problems + top 3 Cards đủ field
- [v] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [v] Đã chọn 1 card pitch + câu hỏi challenge
