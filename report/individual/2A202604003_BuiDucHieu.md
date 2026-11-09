# Báo cáo cá nhân — 2A202604003_BuiDucHieu

## 1. Thông tin học viên

- Họ tên: Bùi Đức Hiếu
- MSSV: 2A202604003 
- Email trường (không bắt buộc, repo có thể để public): 26ai.hieubd2@vinuni.edu.vn
- Tên nhóm: Nhóm 2
- Link repo nhóm: https://github.com/HieuData/K5-L3B-Day02-Nhom2-DiscoveryProblemFraming/tree/main

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Tốn thời gian |Khi nhận một đề bài nhóm có nhiều yêu cầu, tôi muốn chia nhỏ yêu cầu thành các đầu việc có người phụ trách và deadline, để cả nhóm hiểu rõ trách nhiệm và không bỏ sót deliverable |Team leader, Team members |Thời gian phân chia công việc 20-25p, số task bị bỏ sót 2-3 task, số lần phải phân công lại 1-2 lần |
| 2 |Tốn thời gian |Khi kết thúc một cuộc họp nhóm, tôi muốn xác định các quyết định, công việc được giao và deadline, để mọi người có thể tiếp tục công việc mà không phải hỏi lại |Team leader, Thư ký/Project coordinator, Team members |Thời gian viết recap 10-15p, thiếu 3-5 request và thường phải hỏi lại bạn bè 1 - 2 lần  |
| 3 |Lặp lại |Khi gặp lại một khái niệm hoặc dạng bài đã học, tôi muốn tìm được ghi chú và lời giải liên quan trước đó, để không phải đọc lại toàn bộ tài liệu |Sinh viên có nhiều tài liệu và bài tập |Thời gian tìm một kiến thức 10-15p, tỷ lệ tìm được tài liệu phù hợp ngay lần đầu khoảng 50%, tổng thời gian tìm kiếm 1 tuần ôn tập khoảng 1h30 |
| 4 |Tốn thời gian |Khi nhận một task phát triển có mô tả chưa rõ ràng, tôi muốn xác định các yêu cầu, điều kiện hoàn thành và những điểm chưa được giải thích, để tránh hiểu sai yêu cầu và phải sửa lại sau khi hoàn thành |Manager, Developer |Làm rõ task tốn 10-15p, trao đổi lại với manager 1-2 lần, 1 task mỗi sprint phải chỉnh sửa do hiểu sai yêu cầu |
| 5 |Cần đọc, tổng hợp nhiều thông tin |Khi tìm hiểu một công nghệ hoặc thư viện mới để phục vụ dự án, tôi muốn tổng hợp được những thông tin quan trọng từ tài liệu và các nguồn hướng dẫn khác nhau, để hiểu cách sử dụng và lựa chọn được phương án phù hợp |Developer |Mất 30-60p để tìm hiểu một công nghệ mới, phải tham khảo 3–5 nguồn khác nhau, mất thêm 15-20p để đối chiếu thông tin giữa các nguồn |
| 6 |Tốn thời gian |Khi cần mua một sản phẩm có nhiều lựa chọn trên thị trường, tôi muốn so sánh giá cả, đánh giá và đặc điểm của các sản phẩm, để lựa chọn được sản phẩm phù hợp với nhu cầu và ngân sách |Buyer |Mất 20–30p để so sánh, tham khảo 3–5 shop và 2 platform, cân nhắc 5 alternatives |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Tôi dùng AI gợi ý ý #2, #4 và không bỏ ý nào

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Tổng hợp ND họp (#2) |Quy trình ảnh hưởng trực tiếp đến khả năng phối hợp và thực hiện công việc của các thành viên, có baseline |Baseline này có thực sự đo được hiệu quả không |
| 2 |Phân chia yêu cầu (#1) |Vấn đề nhiều người gặp, quy trình khá rõ ràng, chia thành từng bước cụ thể |Có nên thêm tỷ lệ hoàn thành của công việc làm metric không |
| 3 |Lookup kiến thức (#3) |Vấn đề nhiều người gặp, cách xử lý rõ ràng, đơn giản, dễ đánh giá kết quả |Chưa rõ vấn đề nằm ở bước nào để tối ưu |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story |Khi kết thúc một cuộc họp nhóm, tôi muốn xác định các quyết định, công việc được giao và deadline, để mọi người có thể tiếp tục công việc mà không phải hỏi lại |
| Actor |Team leader, Thư ký/Project coordinator, Team members |
| Thời điểm / bối cảnh |Khi kết thúc một cuộc họp nhóm |
| Quy trình hiện tại (3–7 bước) |Xem lại ghi chú -> Xác định các quyết định đã thống nhất -> List task, người phụ trách, deadline -> Viết recap -> Gửi recap cho các member -> Trao đổi thêm nếu còn khúc mắc |
| Bottleneck (bước nào, mất bao nhiêu phút) |Xác định đầy đủ task, member phụ trách và dl từ ND thảo luận |
| Impact (nếu không giải thì sao) |Mất 10-15p sau mỗi cuộc họp, thiếu 3-5 request, phải trao đổi lại với member 1-2 lần để confirm info |
| Success metric (baseline → target) |Giảm thời gian viết recap còn 5p, không bỏ sót request và max 1 lần trao đổi lại (nếu thực sự cần)|
| Phương án không dùng AI |Sử dụng template recap dùng chung |
| Giả thuyết về AI (nếu có) |Sử dụng AI ghi chú cuộc họp của các platform họp trực tuyến, dùng AI hỗ trợ tổng kết nội dung ghi chú |
| Cảm nhận nhanh | Workflow tích hợp AI platform|

Quy trình nháp hiện tại:

```text
Hiện tại - max 15p, thiếu 3-5 request, cần trao đổi 1-2 lần
[1. Xem lại ghi chú: 2-3p] -> [2. Xác định các quyết định đã thống nhất: 1-2p]
-> [3. List task, người phụ trách, deadline: 5-7p] <- Bottleneck
-> [4. Viết recap: 2-3p] -> [5. Gửi cho member: 1p]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story |Khi nhận một đề bài nhóm có nhiều yêu cầu, tôi muốn chia nhỏ yêu cầu thành các đầu việc có người phụ trách và deadline, để cả nhóm hiểu rõ trách nhiệm và không bỏ sót deliverable|
| Actor |Team leader, Team members |
| Thời điểm / bối cảnh |Khi nhận một đề bài nhóm có nhiều yêu cầu |
| Quy trình hiện tại (3–7 bước) |Đọc và phân tích yêu cầu -> List deliverables và chia nhỏ thành các task cụ thể -> Phân công người phụ trách -> Trao đổi lại với member để thống nhất |
| Bottleneck (bước nào, mất bao nhiêu phút) |Convert yêu cầu tổng quát thành deliverable, task cụ thể, có scope và trách nhiệm rõ ràng |
| Impact (nếu không giải thì sao) |Tốn 20-25p xác định và chia việc, để sót 1-2 task, phân công chồng chéo, conflict |
| Success metric (baseline → target) |Giảm thời gian xuống max 10p, không bỏ sót task và hạn chế conflict trong phân công |
| Phương án không dùng AI |Dùng problem solving framework để xác định task, lên checklist để rà soát phân công |
| Giả thuyết về AI (nếu có) |Dùng chatbot (ChatGpt) hỗ trợ việc define và ranking task |
| Cảm nhận nhanh |Workflow|

Quy trình nháp hiện tại:

```text
Hiện tại - max 25p, thiếu 1-2 task, phân công lại 1-2 lần
[1. Đọc và phân tích các yêu cầu: 3-5p]
-> [2. List deliverables và chia nhỏ thành các task cụ thể: 10-15p] <- Bottleneck
-> [3. Phân công người phụ trách: 2-3p] -> [4. Trao đổi lại với member để thống nhất: 2p]
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story |Khi gặp lại một khái niệm hoặc dạng bài đã học, tôi muốn tìm được ghi chú và lời giải liên quan trước đó, để không phải đọc lại toàn bộ tài liệu hoặc giải quyết lại vấn đề từ đầu|
| Actor |Sinh viên có nhiều tài liệu, ghi chú và bài tập được lưu trữ ở nhiều nơi |
| Thời điểm / bối cảnh |Khi gặp lại một khái niệm hoặc dạng bài đã học |
| Quy trình hiện tại (3–7 bước) |Xác định khái niệm hoặc dạng bài cần tìm lại -> Nhớ lại môn học, chủ đề hoặc thời điểm đã học -> Tìm kiếm trong các kho lưu trữ -> Mở và kiểm tra các tài liệu tìm được -> Nếu không tìm thấy, tìm kiếm trên Internet hoặc hỏi bạn bè |
| Bottleneck (bước nào, mất bao nhiêu phút) |Tìm kiếm và xác định tài liệu phù hợp trong số lượng lớn tài liệu được lưu trữ, đặc biệt khi không nhớ chính xác tên file hoặc vị trí lưu (có thể chiếm 5 - 10p)|
| Impact (nếu không giải thì sao) |Mất khoảng 10–15 phút để tìm lại một kiến thức hoặc lời giải cũ, khoảng 1h30 mỗi tuần, còn có thể tốn thêm thời gian nếu không tìm được, cần google hoặc hỏi bạn bè |
| Success metric (baseline → target) |Giảm thời gian tìm kiếm xuống còn 3-5p, tăng tỷ lệ thành công trong lần đâu tìm kiếm |
| Phương án không dùng AI |Chuẩn hóa file name, phân loại theo topic/môn, sử dụng mục lục/tree/tag system hỗ trợ tìm kiếm |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh |Workflow|

Quy trình nháp hiện tại:

```text
Hiện tại - 90p/tuần
[1. Xác định khái niệm hoặc dạng bài cần tìm lại: 1p]
-> [2. Nhớ lại môn học, chủ đề hoặc thời điểm đã học: 1-2p]
-> [3. Tìm kiếm trong các thư mục, file ghi chú hoặc tài liệu đã lưu: 5-10p] <- Bottleneck
-> [4. Mở và kiểm tra các tài liệu tìm được: 2-3p]
-> [Nếu không tìm thấy, tìm kiếm trên Internet hoặc hỏi bạn bè: vary~]

```

### Card muốn pitch nhất

- Card số: #3
- Vì sao: Tuy pain point này không quá nổi bật so với 2 lựa chọn kia, tôi đánh giá cao sự rõ ràng, đơn giản và dễ đo lường, so sánh của vấn đề.
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Actor chưa đủ cụ thể: "Sinh viên có nhiều tài liệu..." vẫn khá rộng, chưa xác định nhóm sinh viên nào thực sự gặp vấn đề |Đồng ý |Thu hẹp thành sinh viên thường xuyên học nhiều môn, có thói quen lưu trữ tài liệu và ghi chú ở nhiều nền tảng khác nhau |
|Bottleneck chưa được xác định đủ rõ: Bước tìm kiếm 5–10 phút đang gộp cả thao tác tìm file và xác định file nào phù hợp |Đồng ý |Tách thành tìm kiếm tài liệu theo từ khóa/vị trí và kiểm tra nội dung để xác định tài liệu phù hợp |
|Có thể giải quyết bằng No AI hoặc Rule: Chuẩn hóa tên file, phân loại thư mục, tag và mục lục có thể giảm đáng kể thời gian tìm kiếm |Đồng ý |Ưu tiên thử chuẩn hóa cách lưu trữ và sử dụng tag system trước, sau đó đánh giá phần vấn đề còn tồn tại |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card |Tham gia debate với teammate |Chốt được shortlist card |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Việc tổng hợp báo cáo tiến độ mất khoảng 20 phút mỗi ngày có thực sự là bottleneck đáng ưu tiên giải quyết, hay phần lớn thời gian này vẫn cần thiết để Team Leader kiểm tra và xác nhận thông tin? Nếu rút ngắn thời gian tổng hợp, liệu có cải thiện đáng kể hiệu quả quản lý tiến độ của team không?| |
| Nhận phản biện | Câu hỏi tôi nhận được: Việc không rõ người phụ trách có thường xuyên xảy ra không? Hay các thành viên vẫn tự hiểu và chủ động nhận việc?| Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem |Tham gia đánh giá shortlist |Chốt được final card |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan |Gợi ý 1 vài vấn đề |Đem lại cho tôi góc nhìn mới |Vấn đề không quá sâu sắc |Tôi thay đổi 1 số vấn đề được gợi ý cho phù hợp |
| CP2 Problem Card |Ranking card |Giúp tôi sắp xép tầm quan trọng của card |Chưa thấy |Bảng ranking |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
