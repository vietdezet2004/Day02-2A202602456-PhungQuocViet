# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Phùng Quốc Việt
- Mã học viên: 2A202602456
- Nhóm: C2
- Candidate problem nhóm chọn: Lên kế hoạch di chuyển thông minh đa biến số (chuyến bay, giao thông real-time, thủ tục sân bay) bằng AI Agent linh hoạt cho sinh viên và người di chuyển xa không thường xuyên.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
| --- | --- | --- |
| Scan cá nhân | Tự scan 7 vấn đề thực tế từ 3 vai trò: sinh viên làm đồ án, sale laptop part-time và dev backend. | Đưa ra được 3 Problem Card có số liệu đo đếm cụ thể (tính bằng phút), không bị rơi vào bẫy chung chung. |
| Pitch Problem Card | Pitch bài "Viết tài liệu Postman cho FE" với bằng chứng mất 30 phút/endpoint và dev FE phải hỏi lại 3-4 lần. | Bài lọt vào top 3 shortlist của cả nhóm nhờ mô tả bottleneck và input/output rất rõ ràng. |
| Challenge bài của bạn khác | Bắt bẻ thẳng bài "Ra sân bay" của Tiến: "Nếu AI tính toán sai giờ làm khách trễ chuyến bay mất tiền triệu thì ai chịu trách nhiệm?". | Kéo cả nhóm thoát khỏi ý định tự động hóa 100%, ép nhóm phải chuyển sang hướng Bán tự động (Human-in-the-loop). |
| Gom trùng / cluster | Đề xuất gom các bài của tôi và Dương vào Cụm D (Dev Tool), hỗ trợ phân loại các bài sinh hoạt/học tập vào Cụm A và B. | Giúp nhóm nhanh chóng nhận diện những bài mang tính Workflow tuyến tính để loại bớt ở vòng sau. |
| Chọn candidate problem | Tranh luận giữa bài Postman (bài của tôi) và bài Ra sân bay; chủ động vote bài Sân bay vì nhận ra bài mình thiếu tính thích ứng động. | Giúp nhóm đạt đồng thuận tuyệt đối chọn bài Sân bay với điểm số cao nhất (32 điểm). |
| Validation / research | Cùng nhóm mổ xẻ phản hồi từ 3 bài phỏng vấn và survey 8 sinh viên; bóc tách điểm yếu của TripIt, Google Maps, FlightAware. | Chỉ ra khoảng trống cốt lõi: thị trường chưa có công cụ nào kết nối được giao thông đường bộ với hàng chờ thủ tục nội bộ sân bay. |
| Workflow nhóm | Trong vai trò Writer, cùng Vũ chuẩn hóa Current Workflow 5 bước, cô lập bước 4 (tính nhẩm 25 phút) là bottleneck chính. | Dựng xong khung Before/After hoàn chỉnh, đưa Human Boundary vào bước 4 ở Future Workflow để kiểm soát rủi ro. |
| Problem Statement | Trực tiếp chắp bút viết PS v0 và nâng cấp lên v1; sửa metric "loại bỏ 100% trễ giờ" thành "tỷ lệ an toàn ≥ 95%". | Đóng khung Boundary chặt chẽ: AI chỉ gợi ý kịch bản rủi ro, tuyệt đối không tự ý book xe hay can thiệp vào tiền/vé. |
| Rule / Workflow / Agent | Phân tích 5 câu hỏi cốt lõi để bảo vệ phương án Agent; chứng minh Rule tĩnh gây mệt mỏi vạ vật, còn Workflow thì tê liệt khi có delay. | Nhóm thống nhất chọn kiến trúc AI Agent kết hợp Human-in-the-loop, có cơ chế Fallback về Rule khi mất mạng. |
| Decision | Cùng nhóm chốt quyết định "Go với phạm vi Pilot có kiểm soát", đề xuất chạy thử trên 5-10 chuyến bay thật của nhóm và bạn bè. | Hoàn thiện trọn vẹn kịch bản pilot, tiêu chí rollback và 3 chỉ số đo lường thực tế trong phạm vi buổi lab. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là đề xuất loại bỏ việc "AI tự động hóa 100%": tôi là đưa ra gợi ý nhóm phải đặt Human Boundary ở bước 4 (AI chỉ đưa ra 2-3 kịch bản kèm tỷ lệ rủi ro, quyền bấm chốt giờ đi thuộc về con người) và thiết lập chốt an toàn cứng (hard buffer tối thiểu 45 phút) để triệt tiêu nguy cơ trễ chuyến bay.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| --- | --- | --- | --- | --- |
| Scan | Prompt AI gợi ý các pain point lặp đi lặp lại của sinh viên CNTT kiêm làm sale laptop part-time. | Gợi ý được góc nhìn hay về sự đứt gãy giao tiếp giữa Dev Backend và Frontend khi bàn giao API. | Đưa ra hàng loạt ý tưởng sáo rỗng kiểu "quản lý thời gian cá nhân", "cân bằng cuộc sống", toàn thứ chung chung không đo đếm được. | Gạt bỏ toàn bộ các ý mơ hồ, chỉ giữ lại những việc đo được bằng phút cụ thể (viết doc Postman mất 30p, so sánh 2 laptop mất 10p). |
| Problem Card | Nhờ AI viết thử draft workflow và gợi ý success metric cho bài Postman doc. | Giúp dàn nhanh khung sườn các bước và format bảng markdown sạch sẽ, tiết kiệm thời gian gõ. | Quá màu hồng: mặc định AI đọc code DTO là hiểu hết business logic, bỏ qua chuyện enum hoặc logic ngầm không có comment sẽ khiến AI bịa (hallucinate). | Tự tay bổ sung bước Fallback: nếu gặp logic quá đặc thù thì dev phải tự sửa tay, AI chỉ đóng vai trò sinh khung mô tả ban đầu. |
| Convergence | Không dùng | không dùng | không dùng | Cả nhóm tự ngồi tranh luận trực tiếp trên Discord vì chỉ con người mới cảm nhận được độ "chạm" và năng lực thực thi của nhóm. |
| Research | Nhờ AI tóm tắt nhanh tính năng và hạn chế của TripIt, Google Maps và FlightAware. | Tóm tắt nhanh điểm mạnh cốt lõi (TripIt parse vé qua email, FlightAware bắt dữ liệu radar bay rất nhạy). | AI chỉ dừng ở việc khen ngợi các app này, không nhìn ra sự phân mảnh và khoảng trống trải nghiệm giữa đường bộ với hàng không. | Tự bóc tách điểm mù: Google Maps chỉ dẫn đến cổng ngoài sân bay rồi "mù tịt", FlightAware báo hoãn chuyến nhưng không tự tính lại giờ xuất phát mới. |
| Problem Statement | Đóng vai một Product Manager khó tính (Skeptical PM) để vặn vẹo bản Problem Statement v0. | Bắt bẻ rất trúng cái metric "loại bỏ 100% rủi ro trễ chuyến" là ảo tưởng và hỏi dồn vào ranh giới an toàn của hệ thống. | Khi được hỏi cách khắc phục, AI lại tiếp tục vẽ vời "xây dựng mô hình học sâu thích ứng với mọi rủi ro" — một kiểu bánh vẽ công nghệ khác. | Bác bỏ gợi ý viển vông đó, tự tay ghìm metric xuống mức thực tế: tỷ lệ an toàn ≥ 95%, sai số ±15 phút và chốt chặt ranh giới: AI không đụng vào tiền/vé. |
| Rule / Workflow / Agent | Không dùng | Không dùng | Không dùng | Tự vận dụng kiến thức buổi học để phân tích: bài toán có đa biến số ngẫu nhiên thời gian thực nên Rule và Workflow đều bất lực, bắt buộc phải dùng Agent. |
| Decision | Không dùng | Không dùng | Không dùng | Cả nhóm tự thảo luận dựa trên nguồn lực thật để chốt Go ở mức Pilot có kiểm soát, tự lên kịch bản test trên vé bay thật của bạn bè. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

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
Lúc đầu khi pitch bài của mình, tôi khá tự tin với bài toán sinh tài liệu Postman cho Frontend vì nó xuất phát từ nỗi đau hàng ngày khi code Backend của tôi, nhưng khi cả nhóm mổ xẻ thì tôi mới vỡ lẽ: bài đó phạm vi quá hẹp và ít bước đi, ép dùng AI Agent vào chỉ là "dùng dao mổ trâu giết gà". Nhóm tôi sau đó cũng không tránh khỏi cái bẫy "solution-first" khi vừa chuyển sang bài di chuyển ra sân bay, lúc đầu đưa ra lựa chọn AI phải tự động 100%, từ theo dõi chuyến bay cho đến tự động đặt xe đón khách. Tôi sau khi đặt câu hỏi: "Nếu đường tắc nghẽn đột xuất hoặc AI ảo giác tính thiếu giờ làm thủ tục khiến khách lỡ chuyến bay, thì ai sẽ chịu trách nhiệm?". Tranh luận này đã giúp nhóm thống nhất chuyển sang mô hình Bán tự động vẫn cần có sự can thiệp của con người, định hình việc AI chỉ tổng hợp dữ liệu để gợi ý 2-3 phương án rủi ro, còn người dùng là người bấm chốt giờ đi cuối cùng. Dấu tay rõ nhất của tôi trong bản báo cáo nhóm chính là việc đề xuất AI tuyệt đối không tự mua vé hay trừ tiền, đồng thời cài đặt chốt an toàn cứng (hard buffer tối thiểu 45 phút) để phòng khi mất mạng hay API lỗi. Khi làm Problem Statement, điều làm tôi toát mồ hôi nhất là viết Success Metric sao cho thực tế chứ không phải vẽ vời ra. Bản thân nhóm từng viết chỉ số "loại bỏ 100% trễ giờ", nhưng nhìn lại tình trạng tắc đường ở đường thì thấy vô lý hết sức, nên tôi đã kéo về mức tỷ lệ an toàn ≥ 95% với sai số dự báo ±15 phút. Nhìn lại toàn bộ quá trình, nếu được làm lại, tôi nghĩ nhóm sẽ cần đi phỏng vấn thực tế ở quy mô rộng hơn thay vì chỉ khảo sát mấy bạn sinh viên cùng lớp. Việc phỏng vấn những người đi công tác sát giờ bay thường xuyên sẽ cho nhóm những con số chuẩn và thực tế hơn rất nhiều về thời gian nghẽn ở khâu soi chiếu an ninh. Quan trọng nhất, bài lab giúp một sinh viên IT như tôi hiểu rằng: giải pháp giá trị không nằm ở việc cố nhồi nhét chữ "Agent" cho hợp thời, mà là biết rõ khi nào nên dùng máy, khi nào dùng rule, và lúc nào phải nhường quyền quyết định lại cho con người.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [v] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [v] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [v] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [v] [15đ] Nhóm có workflow trước/sau
- [v] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [v] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [v] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [v] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [v] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
