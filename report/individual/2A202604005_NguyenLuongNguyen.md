# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Lương Nguyên
- MSSV: 2A202604005
- Email trường (không bắt buộc, repo có thể để public): nglngnguyen
- Tên nhóm: Nhóm 2
- Link repo nhóm: https://github.com/HieuData/K5-L3B-Day02-Nhom2-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Mỗi cuối ngày, tôi muốn tổng hợp báo cáo tiến độ của team dev | Team Leader, Team Members | Mỗi ngày, khoảng 45 phút |
| 2 | Tốn thời gian | Cuối tháng, tôi muốn tổng hợp được số liệu tiến độ để làm slide báo cáo tháng | Team Leader | Mỗi tháng khoảng 1 tiếng |
| 3 | Tốn thời gian | Tôi cần tìm và gửi các thông tin onboarding cho intern sau khi họ bắt đầu đi làm | Intern, Team Leader | 10 phút/intern |
| 4 | Tốn thời gian | Sau buổi họp hàng tháng, tôi cần danh sách các ý chính của buổi họp, các ý kiến, đóng góp được đưa ra cho team dev | Team Leader, Team Members | 30 phút/buổi họp |
| 5 | Pain từ người khác | Sau khi hoàn thành code một chức năng, dev cần phải cập nhật chức năng trong tài liệu đặc tả | Team Members | 30 phút/chức năng |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Mỗi tháng, tôi cần tổng hợp khảo sát từ người dùng cho nhiều ứng dụng để lên kế hoạch cải thiện | Team Leader | 1 tiếng/ứng dụng, công ty đang có 4 ứng dụng |
| 7 | Công việc lặp lại |	Khi có thành viên trong team nghỉ phép hoặc vắng mặt, tôi muốn nắm được các công việc đang phụ trách và mức độ ảnh hưởng đến tiến độ chung, để duy trì hoạt động của team. | Team Leader, Team Members | 1 - 2 lần 1 tháng, 15 phút rà soát một lần  |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Sau khi tự scan 6 ý, ý 7 được giữ lại, ý "Khi QA phát hiện lỗi trong quá trình kiểm thử, tôi muốn team nắm được đầy đủ bối cảnh, bước tái hiện và mức độ ảnh hưởng của lỗi, để dev có đủ thông tin xử lý." được loại bỏ do quy trình đã chuẩn, QA cần có các thông tin cần thiết và điền form gửi cho team dev.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp báo cáo tiến độ ngày (#1) | Công việc lặp lại mỗi ngày, có baseline | Chưa có thước đo đánh giá báo cáo |
| 2 | Cập nhật tài liệu đặc tả (#5) | Pain xuất phát từ công việc thật của dev, có baseline | Số chức năng hoàn thành mỗi tháng là bao nhiêu? |
| 3 | Tổng hợp khảo sát người dùng (#6) | Phải tổng hợp thông tin từ 4 ứng dụng | Chất lượng khảo sát được đánh giá thế nào? |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi kết thúc mỗi ngày làm việc, tôi muốn tổng hợp tiến độ công việc của từng thành viên trong team dev, để nắm bắt tình hình thực hiện công việc và kịp thời phát hiện các vấn đề ảnh hưởng đến tiến độ chung. |
| Actor | Team Leader, Team Members |
| Thời điểm / bối cảnh | Cuối mỗi ngày làm việc, khi cần nắm tình hình tiến độ của toàn team. |
| Quy trình hiện tại (3–7 bước) |
1. Yêu cầu và chờ thành viên cập nhật tiến độ công việc. 2. Thu thập thông tin tiến độ từ các thành viên. 3. Kiểm tra và tổng hợp tình hình tiến độ của từng thành viên. 4. Ghi nhận các vấn đề phát sinh. 5. Lập báo cáo tiến độ.
|
| Bottleneck (bước nào, mất bao nhiêu phút) | Tổng hợp thông tin báo cáo (Bước 2 -> 4) mất 25 phút|
| Impact (nếu không giải thì sao) | Team Leader mất 30 phút một ngày nếu không tính thời gian chờ. |
| Success metric (baseline → target) | Thời gian giảm xuống còn 15 phút |
| Phương án không dùng AI | Team dùng chung định dạng báo cáo, dùng script để tổng hợp |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ đọc thông tin tiến độ, nhận diện task chậm hoặc bị vướng mắc và tổng hợp thẳng thành báo cáo hằng ngày. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```

[1 Chờ thành viên cập nhật tiến độ: 10'] -> [2 Thu thập thông tin tiến độ: 5'] -> [3 Kiểm tra và tổng hợp tình hình tiến độ 15'] -> [4 Ghi nhận các vấn đề phát sinh: 5'] -> [5 Làm báo cáo tiến độ: 10']

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi hoàn thành code một chức năng, tôi muốn cập nhật đầy đủ thông tin chức năng đó vào tài liệu đặc tả, để đảm bảo tài liệu phản ánh đúng trạng thái hiện tại của hệ thống và hỗ trợ các thành viên team dev trong quá trình phát triển, bảo trì. |
| Actor | Team Members, Team Leader |
| Thời điểm / bối cảnh | Sau khi Developer hoàn thành code một chức năng và chuẩn bị bàn giao hoặc kết thúc công việc. |
| Quy trình hiện tại (3–7 bước) | 
1. Developer đọc lại nội dung tài liệu hiện tại. 2. Đối chiếu sự khác biệt giữa chức năng đã code và tài liệu đặc tả. 3. Cập nhật nội dung còn thiếu hoặc thay đổi. 4. Lưu và hoàn tất việc cập nhật tài liệu.
|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, cập nhật nội dung: 15 phút |
| Impact (nếu không giải thì sao) | Một ngày developer sẽ mất 30 phút cho mỗi chức năng để viết tài liệu |
| Success metric (baseline → target) | Giảm 15 phút cho mỗi chức năng cần cập nhật |
| Phương án không dùng AI | Xây dựng checklist các nội dung cần cập nhật sau khi hoàn thành chức năng |
| Giả thuyết về AI (nếu có) | AI hỗ trợ đối chiếu và đề xuất phần mô tả bổ sung. |
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```

[1 Developer đọc lại nội dung tài liệu hiện tại: 5'] -> [2 Đối chiếu sự khác biệt giữa chức năng đã code và tài liệu đặc tả: 5'] -> [3 Cập nhật nội dung còn thiếu hoặc thay đổi: 15'] -> [4 Lưu và hoàn tất việc cập nhật tài liệu: 5']

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến cuối mỗi tháng, tôi muốn tổng hợp phản hồi và kết quả khảo sát người dùng từ nhiều ứng dụng, để xác định các vấn đề, nhu cầu cần thêm và hạng mục cần cải thiện cho từng ứng dụng.|
| Actor | Team Leader |
| Thời điểm / bối cảnh | Cuối mỗi tháng, khi Team Leader cần tổng hợp khảo sát người dùng của 4 ứng dụng để phục vụ việc lập kế hoạch cải thiện sản phẩm. |
| Quy trình hiện tại (3–7 bước) | 	
1. Thu thập kết quả khảo sát. 2. Đọc các phản hồi và ý kiến của người dùng. 3. Phân loại phản hồi theo nhóm vấn đề hoặc chức năng. 4. Xác định các vấn đề được người dùng đề cập nhiều lần. 5. Tổng hợp các nhận xét và nhu cầu nổi bật. 6. Sử dụng kết quả tổng hợp để lên kế hoạch cải thiện.
|
| Bottleneck (bước nào, mất bao nhiêu phút) | Phân tích kết quả (Bước 1->5 ) |
| Impact (nếu không giải thì sao) | Team Leader mất thời gian đọc và tổng hợp nhiều phản hồi. |
| Success metric (baseline → target) | Giảm 30 phút cho mỗi ứng dụng cần tổng hợp phản hồi |
| Phương án không dùng AI | Sử dụng biểu mẫu khảo sát thống nhất; chuẩn hóa các nhóm vấn đề |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ đọc và phân loại phản hồi của người dùng |
| Cảm nhận nhanh | Chưa biết |

Quy trình nháp hiện tại:

```
[1 Thu thập kết quả khảo sát: 10'] -> [2 Đọc các phản hồi và ý kiến của người dùng: 10'] -> [3 Phân loại phản hồi theo nhóm vấn đề hoặc chức năng: 10'] -> [4 Xác định các vấn đề được người dùng đề cập nhiều lần 10'] -> [5 Tổng hợp các nhận xét và nhu cầu nổi bật 5'] [6 Sử dụng kết quả tổng hợp để lên kế hoạch cải thiện. 15']

```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Công việc lặp lại hằng ngày, muốn giải quyết
- Câu hỏi muốn nhóm phản biện: Làm thế nào để đánh giá một báo cáo tiến độ là đầy đủ và hữu ích, thay vì chỉ đo thời gian tạo báo cáo?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Có sự chưa thống nhất giữa Bottleneck 25 phút và Impact 30 phút/ngày. | Đồng ý | Làm rõ 25 phút là thời gian xử lý từ bước 2–4, còn 30 phút là tổng thời gian làm việc thực tế mỗi ngày, không tính thời gian chờ. Cần xác định 5 phút chênh lệch thuộc bước nào. |
| Gợi ý xây dựng Agent tự động gửi báo cáo mà không cần người kiểm tra. | Không đồng ý | Không cho phép AI tự gửi báo cáo. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày vấn đề và giải pháp | 1 trong 4 vấn đề cuối cùng để chọn làm slide |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Việc không rõ người phụ trách có thường xuyên xảy ra không? Hay các thành viên vẫn tự hiểu và chủ động nhận việc? | |
| Nhận phản biện | Câu hỏi tôi nhận được: Việc tổng hợp báo cáo tiến độ mất khoảng 25 phút mỗi ngày có thực sự là bottleneck đáng ưu tiên giải quyết, hay phần lớn thời gian này vẫn cần thiết để Team Leader kiểm tra và xác nhận thông tin? Nếu rút ngắn thời gian tổng hợp, liệu có cải thiện đáng kể hiệu quả quản lý tiến độ của team không? | Tôi đã sửa gì: Phần lớn thời gian dành cho việc tổng hợp tay. Nếu có công cụ tổng hợp, Team Leader chỉ cần kiểm tra, thì sẽ rút ngắn đáng kể thời gian |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | Thực hiện làm assumption map, thực hiện phỏng vấn khảo sát, sửa lại problem | Problem đã được sửa lại theo kết quả khảo sát |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Tạo thêm các problem | 1 problem được đánh giá hợp lý và đưa vào bài làm | 1 problem chưa hợp lý | Loại bỏ problem chưa hợp lý |
| CP2 Problem Card | Phản biện lại problem | 1 phản biện hữu ích để sửa lại problem | 1 gợi ý không phù hợp | Loại bỏ gợi ý không phù hợp |
| CP4 Research | Kiểm tra các assumption đưa ra đã hợp lý hay chưa | 1 assumption được phản biện hữu ích | 1 assumption có phản biện nhưng đã bảo vệ được luận điểm | Giữ nguyên assumption đã bảo vệ |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Qua các problem, tôi thấy pain point thể xuất hiện trong rất nhiều lĩnh vực khác nhau như giáo dục, y tế, bất động sản và vận chuyển. Chúng thường có điểm chung là mất thời gian do phải tìm kiếm, thu thập, xử lý hoặc tổng hợp thông tin từ nhiều nguồn. Tôi học thêm dược rằng một problem được define tốt cần có bối cảnh cụ thể, actor rõ ràng và có thể đo lường mức độ ảnh hưởng.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có. Khi lựa chọn vấn đề tổng hợp báo cáo tiến độ hằng ngày, tôi đã nghĩ đến việc sử dụng AI để đọc thông tin tiến độ, nhận diện task bị chậm và tự động tạo báo cáo. Tuy nhiên, sau khi xem xét lại, tôi nhận ra mình chưa xác định rõ nguyên nhân khiến việc tổng hợp mất thời gian: do thu thập thông tin, kiểm tra dữ liệu hay thực sự do viết báo cáo.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã được hỏi một câu phản biện như sau: "Việc tổng hợp báo cáo tiến độ mất khoảng 25 phút mỗi ngày có thực sự là bottleneck đáng ưu tiên giải quyết, hay phần lớn thời gian này vẫn cần thiết để Team Leader kiểm tra và xác nhận thông tin? Nếu rút ngắn thời gian tổng hợp, liệu có cải thiện đáng kể hiệu quả quản lý tiến độ của team không?". Tôi không sửa problem mà phản biện lại: "Phần lớn thời gian dành cho việc tổng hợp tay. Nếu có công cụ tổng hợp, Team Leader chỉ cần kiểm tra, thì sẽ rút ngắn đáng kể thời gian".

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Có, phỏng vấn cho thấy có nhiều doanh nghiệp đã có quy trình onboarding rõ ràng, file tập trung, nhưng vẫn xảy ra tình trạng intern hỏi lại nhân sự. 

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất là xác định đúng vấn đề cốt lõi mà không đưa giải pháp vào trong cách mô tả vấn đề. Ngoài ra, việc xác định Impact và Success Metric cũng khó vì cần phân biệt giữa những gì đã có số liệu thực tế và những gì mới chỉ là giả định.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, tôi sẽ dành nhiều thời gian hơn để tìm hiểu quy trình hiện tại trước khi nghĩ đến giải pháp. Tôi cũng sẽ đo đạc lại số liệu cụ thể cho từng bước để có baseline tốt hơn. Tôi sẽ phản biện nhóm mạnh hơn về các vấn đề như tính cần thiết của AI, nguyên nhân gốc rễ của vấn đề do đâu, và khả năng chứng minh vấn đề đã được cải thiện ngoài giảm thời gian.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Problem: Người cũ phải trả lời nhiều câu hỏi của intern do quy trình và tài liệu onboarding chưa hoàn thiện
Quy trình: Intern tìm tài liệu -> Intern đọc tài liệu -> Intern chưa chắc -> Intern hỏi người cũ 
Metric: Giảm số câu hỏi cho người cũ 30%, nâng thời gian tự tìm kiếm trước khi hỏi lên 20%, tỉ lệ không cần hỏi lớn hơn baseline.
Boundary: AI không được làm lộ tài liệu mật, AI không trả lời các câu hỏi không liên quan
Mức can thiệp AI: No AI cho chuẩn hóa nguồn dữ liệu, Rule dành cho các câu hỏi ổn định, Workflow cho các câu hỏi Rule không trả lời được, không dùng Agent

---

## 7. Tài liệu tham khảo

-
