# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 |  Nguyễn Lương Nguyên | Khi kết thúc mỗi ngày làm việc, tôi muốn tổng hợp tiến độ công việc của từng thành viên trong team dev, để nắm bắt tình hình thực hiện công việc và kịp thời phát hiện các vấn đề ảnh hưởng đến tiến độ chung. | Team Leader, Team Members | Tổng hợp thông tin báo cáo (Bước 2 -> 4) mất 25 phút | Việc tổng hợp báo cáo tiến độ mất khoảng 20 phút mỗi ngày có thực sự là bottleneck đáng ưu tiên giải quyết, hay phần lớn thời gian này vẫn cần thiết để Team Leader kiểm tra và xác nhận thông tin? Nếu rút ngắn thời gian tổng hợp, liệu có cải thiện đáng kể hiệu quả quản lý tiến độ của team không? (Bùi Đức Hiếu) |
| 2 | Nguyễn Lương Nguyên | Khi hoàn thành code một chức năng, tôi muốn cập nhật đầy đủ thông tin chức năng đó vào tài liệu đặc tả, để đảm bảo tài liệu phản ánh đúng trạng thái hiện tại của hệ thống và hỗ trợ các thành viên team dev trong quá trình phát triển, bảo trì. | Team Members, Team Leader | Bước 3, cập nhật nội dung: 15 phút | |
| 3 | Nguyễn Lương Nguyên | Khi đến cuối mỗi tháng, tôi muốn tổng hợp phản hồi và kết quả khảo sát người dùng từ nhiều ứng dụng, để xác định các vấn đề, nhu cầu cần thêm và hạng mục cần cải thiện cho từng ứng dụng. | Team Leader | Phân tích kết quả (Bước 1->5 ) | |
| 4 | Bùi Đức Hiếu | Khi kết thúc một cuộc họp nhóm, tôi muốn xác định các quyết định, công việc được giao và deadline, để mọi người có thể tiếp tục công việc mà không phải hỏi lại | Team leader, Thư ký/Project coordinator, Team members | Xác định đầy đủ task, member phụ trách và dl từ ND thảo luận | |
| 5 | Bùi Đức Hiếu | Khi nhận một đề bài nhóm có nhiều yêu cầu, tôi muốn chia nhỏ yêu cầu thành các đầu việc có người phụ trách và deadline, để cả nhóm hiểu rõ trách nhiệm và không bỏ sót deliverable | Team leader, Team members | Convert yêu cầu tổng quát thành deliverable, task cụ thể, có scope và trách nhiệm rõ ràng | Việc không rõ người phụ trách có thường xuyên xảy ra không? Hay các thành viên vẫn tự hiểu và chủ động nhận việc? (Nguyễn Lương Nguyên) |
| 6 | Bùi Đức Hiếu | Khi gặp lại một khái niệm hoặc dạng bài đã học, tôi muốn tìm được ghi chú và lời giải liên quan trước đó, để không phải đọc lại toàn bộ tài liệu hoặc giải quyết lại vấn đề từ đầu | Sinh viên có nhiều tài liệu, ghi chú và bài tập được lưu trữ ở nhiều nơi | Tìm kiếm và xác định tài liệu phù hợp trong số lượng lớn tài liệu được lưu trữ, đặc biệt khi không nhớ chính xác tên file hoặc vị trí lưu (có thể chiếm 5 - 10p) | |
| 7 | Hoàng Nhật Minh | Khi nhân viên mới vào team, tôi muốn họ tự tìm được tài liệu và quy trình nội bộ, để người cũ không phải trả lời cùng một câu nhiều lần | Người cũ / mentor bị hỏi; nhân viên mới (người hỏi) | Bước 2–3: tự tìm mất 20 phút rồi vẫn phải hỏi, vì tài liệu rải rác và nhân viên mới không biết từ khóa nội bộ. Bước 5: người cũ mất 10-15 phút mỗi lần bị hỏi | |
| 8 | Hoàng Nhật Minh | Khi nhận thông báo của trường từ nhiều nhóm chat, sổ liên lạc và email, phụ huynh muốn nắm được việc nào cần làm và hạn khi nào, để không lỡ hạn nộp tiền hay lịch họp | Phụ huynh có con tiểu học/THCS, ở nhiều nhóm chat (lớp, trường, ban đại diện) | Bước 3: tìm ra vài tin cần hành động giữa hàng chục đến hàng trăm tin khác. Mất 30-60 phút/ngày, hoặc bỏ qua luôn khi đã tắt thông báo | |
| 9 | Hoàng Nhật Minh | Khi khách nhắn hỏi lặp lại về giá, size, phí ship, chủ shop online muốn trả lời nhanh và đúng, để không mất khách vì phản hồi chậm | Chủ shop hoặc nhân viên trực inbox của shop nhỏ (1–3 người) bán qua Facebook/Zalo | Bước 2: thời gian từ lúc khách nhắn đến lúc shop trả lời là 90 phút vào giờ cao điểm. Bước 4–5: gõ lại cùng một nội dung 20 lần/ngày | |
| 10 | Trần Trung Kiên | Bệnh nhân được yêu cầu mua thuốc ngoài khi bệnh viện hết, nhưng không nắm rõ mình có thuộc diện được bệnh viện thanh toán tiền thuốc hay không, hoặc thuộc diện được thanh toán nhưng chưa được thanh toán | Bệnh nhân, nhân viên tài chính bệnh viện | tổng lượng request thanh toán, tổng giá trị request chưa được xử lý | |
| 11 | Trần Trung Kiên | Khách hàng tìm mua/thuê nhà nhưng có nhiều sales/ đơn vị sales cùng môi giới một căn, dẫn đến trùng căn, mất thời gian liên hệ, hẹn xem, nhân lực sales phân bổ không tối ưu | Khách hàng, sales | số sales môi giới cùng một căn cho cùng 1 khách hàng | |
| 12 | Trần Trung Kiên | Shipper di chuyển theo tuyến đường không tối ưu, gây lãng phí tài nguyên | shipper/ đơn vị vận chuyển | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Nhân viên mới thường xuyên gặp khó khăn trong việc tìm kiếm tài liệu và quy trình nội bộ khi bắt đầu công việc. | Value | 5 | 1 | Có |
| 2 | Nhân viên cũ đang mất nhiều thời gian trả lời những câu hỏi lặp lại từ nhân viên mới. | Viability | 5 | 3 | Có |
| 3 | Các tài liệu và quy trình nội bộ hiện đang phân tán ở nhiều nơi, khó tìm kiếm hoặc chưa được tổ chức thống nhất. | Feasibility | 4  | 2 | Có |
| 4 | Nếu có một nơi tập trung tài liệu, quy trình và hướng dẫn, nhân viên mới sẽ chủ động tìm kiếm trước khi hỏi người cũ. | Desirability | 5 | 1 | Có |
| 5 | Team có thể duy trì, cập nhật tài liệu và quy trình thường xuyên để đảm bảo thông tin luôn chính xác, hữu ích. |  Feasibility | 3 | 2 | Không |

Giả định nhóm kiểm chứng trong buổi này: 1, 2 ,3 ,4

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn | 3 | 3/3 người nói họ sẽ tự chủ động tìm thông tin nếu có tài liệu đầy đủ | 1/3 người nói họ không gặp khó khăn gì trong quá trình onboarding |
| Phỏng vấn | 2 | 1/2 người nói trả lời intern làm mất nhiều thời gian của họ | 1/2 người nói tài liệu, quy trình onboarding của họ đã chuẩn |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
Sửa từ "Chuẩn hóa quy trình onboarding nhân viên" sang thành "Xây dựng kho tài liệu onboarding tập trung.", có thể mở rộng thêm sang "Xây dựng hệ thống hỗ trợ onboarding" sau khi hoàn thành xây dựng kho tài liệu.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Nhân viên cũ / mentor trong team, là người thường xuyên bị nhân viên mới hỏi trong 2 tuần đầu onboarding |
| **Quy trình** | Nhân viên mới cần làm một việc (xin quyền truy cập, setup môi trường, nộp chứng từ…) → tự tìm trên Drive / wiki / kênh chat → không tìm ra hoặc không chắc tài liệu còn đúng → nhắn hỏi người cũ → người cũ dừng việc để tìm link hoặc giải thích lại → nhân viên mới làm tiếp |
| **Bottleneck** | Bước tự tìm: tài liệu nằm rải rác nhiều nơi, nhân viên mới không biết từ khóa nội bộ hay bản nào mới nhất, nên chuyển sang hỏi người |
| **Impact** | Người cũ bị ngắt việc 5 lần/tuần, mất 60 phút/tuần cho các câu đã từng trả lời. Nhân viên mới chờ trung bình 20 phút mỗi câu và có lúc bị chặn việc |
| **Success Metric** (baseline → target, cách đo) | Số câu hỏi lặp lại người cũ nhận mỗi tuần, tính trên mỗi nhân viên mới: ⟨baseline⟩ → giảm ≥ 50%. Đo bằng cách đếm tin nhắn hỏi trong chat/DM của người cũ, 2 tuần trước pilot và 4 tuần pilot. Một câu được tính là "lặp lại" nếu câu trả lời đã có trong tài liệu hoặc đã từng được trả lời |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không trả lời ngoài tài liệu nội bộ đã duyệt, không trả lời thiếu link nguồn, không tự cấp quyền hay duyệt yêu cầu. Chuyển cho người phụ trách khi: không tìm thấy nguồn, các nguồn mâu thuẫn, hoặc câu hỏi về quyền truy cập, bảo mật, HR, lương |


Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:
Tại sao không sử dụng các ứng dụng tổng hợp nội dung như noteLM?

-
Phản biện: Chi phí mỗi lần truy xuất lớn hơn, tính bảo mật thấp hơn.

---


## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: Độ phức tạp thấp × độ mơ hồ cao

Vì sao:
- Độ mơ hồ cao ở đầu vào: nhân viên mới hỏi bằng ngôn ngữ tự nhiên, mỗi người hỏi một kiểu và không biết từ khóa nội bộ. Đầu ra thì có đúng/sai rõ: câu trả lời phải khớp với tài liệu.
- Độ phức tạp thấp: chỉ có 1 bước chính (tìm đúng tài liệu rồi tóm tắt kèm link), 1 nguồn là kho tài liệu nội bộ, không có bước nào phụ thuộc bước trước.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Gom tài liệu về 1 trang onboarding, có mục lục và FAQ top câu hỏi. Có checklist tuần đầu. Người cũ trả lời bằng link, gặp câu mới thì bổ sung vào FAQ | Câu hỏi tập trung vào một nhóm nhỏ, nhân viên mới tìm được bằng mục lục | FAQ lỗi thời nếu không ai giữ. Nhân viên mới vẫn không tìm ra vì không biết từ khóa | **Có, làm nền.** Workflow cũng cần kho tài liệu sạch |
| **Rule** | Bot trả lời theo từ khóa trong kênh onboarding: câu hỏi chứa từ khóa thì gửi link FAQ tương ứng | Câu hỏi dùng từ khóa ổn định, ít cách diễn đạt | Khớp sai hoặc không khớp khi nhân viên mới dùng từ khác | Không, vì bottleneck chính là không biết từ khóa |
| **Workflow** | Câu hỏi → tìm trong kho tài liệu đã duyệt → AI trả lời ngắn kèm link nguồn → Rule chặn chủ đề nhạy cảm và câu không có nguồn, chuyển cho người phụ trách → nhân viên mới bấm "đã giải quyết / chưa" → câu "chưa" được đưa vào FAQ | Các bước cố định, AI chỉ làm phần hiểu câu hỏi và tóm tắt | Trả lời sai hoặc trích tài liệu cũ, nhân viên mới làm sai | **Chọn**, có điều kiện (xem dưới) |
| **Agent** | AI tự tìm trên nhiều hệ thống, tự tạo ticket, tự xin hoặc cấp quyền thay nhân viên mới | Khi bước tiếp theo không đoán trước được | Quyền truy cập rộng, khó kiểm soát, sai thì hậu quả thật (cấp quyền sai) | Không. Bài toán không cần AI tự quyết bước tiếp theo |


**Mức chọn:** Workflow, đặt trên nền No AI (gom và dọn tài liệu trước). Nếu bảng research 3.3 cho thấy công cụ nhóm đang dùng đã có sẵn tính năng hỏi đáp trên tài liệu, thì dùng công cụ đó thay vì tự xây.


**Vì sao không chọn mức đơn giản hơn:** No AI và Rule giải được phần tài liệu rải rác, nhưng không giải được phần nhân viên mới không biết từ khóa nội bộ. Workflow chỉ cần thiết khi CP4 cho thấy câu trả lời **đã có** trong tài liệu mà nhân viên mới vẫn không tìm ra: ⟨X / Y câu hỏi trong log hoặc phỏng vấn⟩. Nếu đa số câu hỏi chưa có trong tài liệu, thì vấn đề là thiếu tài liệu và nhóm dừng ở No AI.


### 6.3. AI Canvas rút gọn


| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Tài liệu nào trả lời câu hỏi, kèm câu trả lời ngắn và link nguồn. Hoặc "không tìm thấy" |
| **Judgment** — con người cân nhắc, quyết định gì? | Nhân viên mới quyết định câu trả lời đã giải quyết được việc chưa. Người phụ trách tài liệu quyết định nội dung nào đúng, câu nào cần bổ sung hoặc sửa tài liệu |
| **Action** — hành động cuối cùng là gì, ai làm? | Nhân viên mới làm theo tài liệu gốc. Nếu chưa giải quyết thì hỏi người phụ trách. Người phụ trách cập nhật tài liệu hoặc FAQ |
| **Outcome** — đo kết quả bằng gì? | Số câu hỏi lặp lại người cũ nhận mỗi tuần; tỉ lệ câu trả lời đúng nguồn; tỉ lệ nhân viên mới bấm "đã giải quyết" |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Câu hỏi của nhân viên mới; kho tài liệu nội bộ đã duyệt (wiki, Drive, FAQ), mỗi tài liệu có người phụ trách và ngày cập nhật; danh sách chủ đề nhạy cảm kèm người phụ trách. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Nút "đã giải quyết / chưa"; các câu bị chuyển cho người; người cũ báo câu AI trả lời sai |


### 6.4. Hai câu hỏi của Google PAIR


- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: **Augment.** Giao cho AI phần *tìm và tóm tắt*, còn nhân viên mới vẫn tự làm theo tài liệu gốc. Việc cấp quyền và các câu hỏi nhạy cảm vẫn do người làm. *Giả thuyết, cần CP4 xác nhận:* ⟨câu nói hoặc hành vi từ phỏng vấn, ví dụ nhân viên mới đã từng ngại hỏi nên tự đoán, hoặc người cũ đã từng gửi lại cùng một link⟩.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: **Báo nhầm tệ hơn**, tức AI trả lời tự tin nhưng sai, ví dụ quy trình đã cũ hoặc thiếu bước. Nhân viên mới chưa đủ kinh nghiệm để nhận ra mình đang làm sai. Bỏ sót (AI nói "không tìm thấy") chỉ đưa quy trình về như hiện tại là hỏi người cũ. Vì vậy thiết kế chọn: không chắc thì chuyển cho người, bắt buộc kèm link nguồn, không trích tài liệu quá hạn.


---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)


| Trường | Nội dung |
|---|---|
| **Actor** | Nhân viên cũ / mentor trong team, là người thường xuyên bị nhân viên mới hỏi trong 2 tuần đầu onboarding, ở team **mà câu trả lời đã có trong tài liệu** |
| **Quy trình** | Nhân viên mới cần làm một việc → tự tìm trên Drive / wiki / kênh chat → không tìm ra hoặc không chắc tài liệu còn đúng → nhắn hỏi người cũ → người cũ dừng việc để tìm link hoặc giải thích lại → nhân viên mới làm tiếp |
| **Bottleneck** | Bước tự tìm: tài liệu nằm rải rác, nhân viên mới không biết từ khóa nội bộ hay bản nào mới nhất, nên chuyển sang hỏi người |
| **Impact** | Người cũ bị ngắt việc 5 lần/tuần, mất 60 phút/tuần. Nhân viên mới chờ trung bình 20 phút mỗi câu |
| **Success Metric** (baseline → target, cách đo) | (1) Số câu hỏi lặp lại người cũ nhận mỗi tuần, tính trên mỗi nhân viên mới: ⟨baseline⟩ → giảm ≥ 50%. Đếm trong chat/DM, 2 tuần trước pilot và 4 tuần pilot. (2) **Tỉ lệ câu trả lời đúng nguồn ≥ 90%.** Người phụ trách kiểm ngẫu nhiên 20 câu mỗi tuần theo tiêu chí bên dưới. (3) **Không có sự cố** nhân viên mới làm sai do câu trả lời sai |
| **Boundary** | AI không trả lời ngoài tài liệu nội bộ đã duyệt, không trả lời thiếu link nguồn, **không trích tài liệu quá hạn hoặc chưa có người phụ trách**, không tự cấp quyền hay duyệt yêu cầu. Chuyển cho người phụ trách khi: không tìm thấy nguồn, các nguồn mâu thuẫn, hoặc câu hỏi về quyền truy cập, bảo mật, HR, lương |
| **AI intervention point** | Giữa bước "nhân viên mới tự tìm" và bước "hỏi người cũ": AI tìm tài liệu và tóm tắt kèm link trước khi câu hỏi đến tay người |
| **Mức chọn** | Workflow, trên nền No AI (gom tài liệu về 1 nơi, gắn người phụ trách và ngày cập nhật) |
| **Rủi ro & người kiểm tra** | Trả lời sai hoặc dùng bản cũ → người phụ trách tài liệu kiểm mẫu hằng tuần. Nhân viên mới làm theo sai → câu trả lời luôn kèm link để đối chiếu với bản gốc. Tài liệu lỗi thời → người phụ trách nhận nhắc rà lại sau ⟨X⟩ tháng |


**Thay đổi so với v0 và lý do:**


| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Success Metric | Chỉ đếm số câu hỏi lặp lại | Thêm tỉ lệ đúng nguồn và số sự cố | Nếu chỉ đếm số câu hỏi, AI trả lời sai vẫn làm metric "đẹp" vì nhân viên mới không hỏi lại.|
| Boundary | Không nói tới độ mới của tài liệu | Không trích tài liệu quá hạn hoặc chưa có người phụ trách | Bottleneck có nguyên nhân "không biết bản nào mới nhất". AI trích bản cũ sẽ lặp lại đúng lỗi đó |
| Actor | Mọi team có nhân viên mới | Chỉ team mà câu trả lời đã có trong tài liệu | Team thiếu tài liệu thì cần viết tài liệu (No AI), AI không giúp được |


**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**


| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đúng nguồn | Có link tới tài liệu đã duyệt và nội dung khớp tài liệu đó | Không có link, hoặc link không chứa nội dung được trả lời |
| 2 | Không bịa | Mọi bước và thông tin đều có trong nguồn | Có bước, tên người, deadline hay con số không có trong nguồn |
| 3 | Biết chuyển cho người | Câu ngoài tài liệu hoặc thuộc chủ đề nhạy cảm (quyền truy cập, HR, lương, bảo mật) được chuyển cho người phụ trách | AI vẫn trả lời, hoặc đoán câu trả lời |
| 4 | Tài liệu hiện hành | Trích bản mới nhất, còn trong hạn rà soát | Trích bản cũ hoặc tài liệu đã hết hạn |
| 5 | Làm theo được ngay | ≤ 5 câu hoặc các bước rõ ràng, nhân viên mới làm tiếp mà không phải hỏi thêm | Dài, lan man, hoặc nhân viên mới vẫn phải hỏi người cũ cùng câu đó |


---


## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
