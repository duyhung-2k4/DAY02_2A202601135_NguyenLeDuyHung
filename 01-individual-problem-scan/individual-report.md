# Individual Report - Day 02

**Học viên:** Nguyễn Lê Duy Hưng  
**Mã học viên:** DAY02_2A202601135  
**Phần nộp:** 01 - Individual Problem Scan

> Ghi chú trung thực: bản này được viết thành một bản nháp có cấu trúc đầy đủ theo README và worksheet. Trước khi nộp cuối, tôi cần tự kiểm lại các con số thời gian/tần suất bên dưới bằng trải nghiệm thật của mình.

---

# 1. Scan rộng: 10 problems

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật / cách đo |
|---|---|---|---|---|
| 1 | Lặp lại, tốn thời gian | Khi làm lab, tôi mất thời gian tìm lại yêu cầu nộp bài nằm rải rác trong README, worksheet, Discord và ghi chú riêng | Học viên trong lab | Mỗi buổi lab phải đọc lại 2-4 nguồn, mất khoảng 15-30 phút để chắc mình không thiếu file |
| 2 | Tốn thời gian, AI có thể tốt hơn | Đọc tài liệu dài để rút ra đúng các field cần điền cho bài nộp | Học viên | README/worksheet dài, dễ bỏ sót metric, boundary, workflow trước/sau |
| 3 | Pain từ người khác | Thành viên nhóm dễ quên action item sau khi thảo luận, vì việc nằm trong chat và không có owner rõ | Nhóm 3-4 học viên | Sau meeting cần hỏi lại "ai làm phần này?", "deadline lúc nào?" |
| 4 | Lặp lại | Mỗi lần làm bài phải tạo cấu trúc thư mục và file đúng quy ước | Học viên | Dễ đặt sai tên file hoặc bỏ sót thư mục nộp bài |
| 5 | AI có thể tốt hơn | Tìm câu trả lời cũ trong Discord/chat khó vì keyword không trùng với cách mình nhớ | Học viên, mentor | Tìm bằng keyword thủ công, phải đọc nhiều thread |
| 6 | Tốn thời gian | Tổng hợp feedback của mentor/bạn học để sửa bài nộp | Học viên | Feedback nằm ở nhiều chỗ, dễ sửa cái nhỏ mà bỏ qua vấn đề chính |
| 7 | Lặp lại, pain từ người khác | Nhóm khó thống nhất một Problem Statement vì mỗi người pitch theo cách khác nhau | Thành viên nhóm | Thảo luận dài nhưng vẫn solution-first, chưa rõ actor/workflow/metric |
| 8 | Tốn thời gian | Chuyển workflow từ ghi chú tay sang Mermaid/Markdown sạch để nộp bài | Học viên | Tốn 15-20 phút format lại, dễ sai thứ tự bước |
| 9 | AI có thể tốt hơn | Kiểm tra xem Problem Card có quá rộng hay đã có metric đo được chưa | Học viên | Tự đọc dễ bị thiên lệch, cần người phản biện |
| 10 | Lặp lại | Theo dõi deadline và trạng thái nộp bài qua nhiều ngày học | Học viên | Cần nhớ file nào đã xong, file nào còn thiếu |

---

# 2. Chọn top 3 problems

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tìm lại yêu cầu, câu trả lời và quyết định cũ trong các kênh học tập | Actor rõ, workflow lặp lại, pain thật trong mỗi lab, có thể đo bằng thời gian tìm thông tin và số lần hỏi lại | Cần đo baseline chính xác hơn: mỗi buổi thật sự mất bao nhiêu phút |
| 2 | Rút yêu cầu nộp bài từ README/worksheet dài thành checklist hành động | Workflow rõ, có nhiều nguồn input, AI có thể hỗ trợ đọc và tóm tắt nhưng người học vẫn phải kiểm | Chất lượng checklist cần đo bằng tỉ lệ bỏ sót field, không chỉ đo thời gian |
| 3 | Theo dõi action item và owner của nhóm sau khi thảo luận | Pain liên quan nhóm, impact rõ nếu trễ deadline, có thể so sánh Rule/Workflow/Agent | Cần có log meeting/chat thật để validate |

---

# 3. Problem Card #1 - Tìm lại thông tin trong các kênh học tập

## Problem 1 câu

Khi làm lab, học viên mất nhiều thời gian tìm lại yêu cầu, câu trả lời và quyết định cũ nằm rải rác trong README, worksheet, Discord/chat và ghi chú riêng, dẫn đến hỏi lại hoặc nộp thiếu field.

## Actor

Học viên tham gia AI in Action Lab, cần hoàn thành bài nộp đúng cấu trúc và đúng rubric.

## Thời điểm / bối cảnh

Trong và sau buổi lab, đặc biệt trước khi nộp bài hoặc khi cần sửa artifact theo feedback.

## Current workflow

```text
CURRENT STATE - 30 đến 45 phút/lab

[1 Mở README: 5']
-> [2 Mở worksheet để đọc yêu cầu chi tiết: 10']
-> [3 Tìm trong Discord/chat các câu trả lời liên quan: 10']
-> [4 So sánh với file mình đang làm: 10']
-> [5 Hỏi lại bạn/mentor nếu không chắc: 5-10']  <-- bottleneck
-> [6 Sửa file nộp bài: 5']
```

## Bottleneck

Bottleneck nằm ở bước 3-5: thông tin nằm rải rác và không được gắn thành checklist theo ngữ cảnh hiện tại. Học viên phải vừa tìm, vừa đọc, vừa tự suy luận xem điều nào áp dụng cho bài của mình.

## Impact

- Mất khoảng 30-45 phút mỗi lab chỉ để chắc mình hiểu đúng yêu cầu.
- Dễ hỏi lại những câu đã có câu trả lời.
- Dễ nộp thiếu field quan trọng như metric, boundary, workflow before/after.
- Nếu nhiều học viên cùng hỏi lại, mentor bị tăng tải support.

## Success metric

- Giảm thời gian tìm lại thông tin từ 30-45 phút xuống dưới 10 phút mỗi lab.
- Giảm số lần hỏi lại các câu đã có trong README/worksheet/chat.
- Checklist cuối cùng phải đặt trên nguồn có dẫn chiếu, không tự bịa thêm yêu cầu.

## Non-AI alternative

- Tạo một FAQ cố định trong README.
- Pin các câu trả lời quan trọng trên Discord.
- Đặt quy ước tên file và checklist nộp bài thật rõ.

Non-AI alternative có ích cho các câu hỏi lặp lại, nhưng chưa giải quyết tốt trường hợp học viên hỏi bằng ngôn ngữ khác hoặc cần tổng hợp từ nhiều nguồn.

## AI hypothesis

Dùng một workflow hỗ trợ truy vấn và tóm tắt theo nguồn:

1. Người học nhập câu hỏi hoặc mục tiêu hiện tại.
2. Hệ thống tìm trong README, worksheet, example và notes đã được phép dùng.
3. AI tóm tắt câu trả lời thành checklist ngắn.
4. AI trả kèm nguồn để người học tự kiểm.
5. Người học vẫn chốt cách nộp bài và chịu trách nhiệm với nội dung.

## Quick gut

**Workflow**, chưa cần Agent ở scope đầu.

---

# 4. Draft workflow cho Problem Card #1

## Future workflow

```text
FUTURE STATE - dưới 10 phút/lab

[1 Học viên đặt câu hỏi/mục tiêu: 1']
-> [2 Workflow tìm trong README/worksheet/example: 1']     -- retrieval/rule
-> [3 AI tóm tắt thành checklist theo bài hiện tại: 1']    -- AI support
-> [4 Học viên kiểm nguồn và bổ sung context cá nhân: 5']  -- human boundary
-> [5 Cập nhật file nộp bài: 2']

Fallback:
Nếu AI tóm tắt sai hoặc không có nguồn -> quay lại đọc README/worksheet gốc và hỏi mentor.
```

## Boundary

- AI không được tự thêm yêu cầu nếu không có trong nguồn.
- AI không thay học viên viết reflection cá nhân.
- AI chỉ được đưa checklist và gợi ý câu hỏi tự kiểm.
- Người học phải kiểm lại nguồn trước khi nộp.

---

# 5. Problem Card #2 - Biến README/worksheet thành checklist nộp bài

## Problem 1 câu

Học viên dễ bỏ sót yêu cầu nộp bài vì README và worksheet dài, gồm nhiều phase, rubric và ghi chú về cách dùng AI.

## Actor

Học viên cần nộp repo cá nhân đúng cấu trúc Day 02.

## Current workflow

```text
CURRENT STATE - 45 đến 60 phút

[1 Đọc README tổng quan: 10']
-> [2 Đọc worksheet theo phase: 25']
-> [3 Mở example để so sánh: 10']
-> [4 Tự lập checklist: 10']  <-- bottleneck
-> [5 Đối chiếu với file của mình: 5']
```

## Bottleneck

Tự biến tài liệu dài thành checklist hành động. Người học dễ đọc hiểu từng phần nhưng vẫn bỏ sót liên kết giữa problem -> workflow -> metric -> boundary -> AI decision.

## Impact

- Mất nhiều thời gian đọc lại tài liệu.
- Dễ tập trung vào format mà quên logic bài.
- Có nguy cơ nộp đủ file nhưng thiếu metric hoặc boundary.

## Success metric

- Giảm thời gian lập checklist từ 60 phút xuống 20 phút.
- Checklist phải bao phủ đủ 3 phần: individual scan, group statement, reflection.
- Sau khi đối chiếu, không còn field trong rubric bị bỏ trống.

## Non-AI alternative

Tạo checklist mẫu cố định ngay trong README. Cách này nhanh và ít rủi ro, nhưng không cá nhân hóa theo trạng thái file hiện tại của từng học viên.

## AI hypothesis

AI đọc các file hướng dẫn và tạo checklist theo repo hiện có, nhưng chỉ đưa ra những mục có căn cứ trong README/worksheet.

## Quick gut

**Rule + Workflow**. Rule đủ cho checklist cố định; AI workflow hữu ích khi cần đối chiếu với file hiện tại.

## Draft future workflow

```text
FUTURE STATE - 20 phút

[1 Quét README/worksheet/example: 2']
-> [2 Tạo checklist theo rubric: 3']
-> [3 Quét repo để xem phần nào còn thiếu: 3']
-> [4 Học viên tự đọc lại mục cần sửa: 10']  <-- human check
-> [5 Cập nhật file: 2']

Fallback:
Nếu checklist mâu thuẫn với README -> ưu tiên README/worksheet gốc.
```

---

# 6. Problem Card #3 - Theo dõi action item và owner trong nhóm

## Problem 1 câu

Sau khi nhóm thảo luận, action item và owner dễ bị rơi vì nằm trong chat/ghi chú rời rạc, khiến thành viên hỏi lại và chậm tiến độ nộp bài.

## Actor

Nhóm 3-4 học viên làm chung `02-group-problem-statement`.

## Current workflow

```text
CURRENT STATE - 25 đến 35 phút sau mỗi lần họp

[1 Nhóm thảo luận candidate problems: 15']
-> [2 Mỗi người ghi chú riêng: 5']
-> [3 Chốt việc bằng miệng/chat: 5']
-> [4 Một người tổng hợp lại owner/deadline: 10']  <-- bottleneck
-> [5 Các thành viên hỏi lại khi làm: 5']
```

## Bottleneck

Không có một danh sách action item chuẩn gồm việc, owner, deadline, artifact liên quan và trạng thái.

## Impact

- Nhóm dễ chậm ở các phần cần ghép nối như validation, workflow, Problem Statement.
- Một người phải nhắc lại nhiều lần.
- Decision cuối có thể thiếu bằng chứng vì action research bị rơi.

## Success metric

- Sau mỗi lần họp, có action list trong dưới 5 phút.
- 100% action item có owner và deadline.
- Giảm số lần hỏi lại "ai làm phần này?" xuống 0-1 lần mỗi buổi.

## Non-AI alternative

Dùng template Notion/Google Sheet với cột Task, Owner, Deadline, Status. Cách này có thể đủ nếu nhóm kỷ luật cập nhật.

## AI hypothesis

AI có thể tóm tắt meeting notes/chat thành action item, nhưng thành viên nhóm phải xác nhận lại owner và deadline.

## Quick gut

**Rule** cho template, hoặc **Workflow** nếu cần AI tóm tắt note.

## Draft future workflow

```text
FUTURE STATE - 5 đến 10 phút

[1 Nhóm ghi notes chung trong lúc họp: 10']
-> [2 Workflow/AI trích action item: 1']
-> [3 Nhóm review từng action: 3']  <-- human boundary
-> [4 Gán owner + deadline vào bảng: 2']
-> [5 Check trạng thái trước deadline: 1']

Fallback:
Nếu AI trích sai action -> nhóm dùng notes gốc và sửa bảng task.
```

---

# 7. Card tôi muốn pitch nhất

**Card muốn pitch:** Problem Card #1 - Tìm lại thông tin trong các kênh học tập.

**Vì sao:**  
Bài này gần với trải nghiệm thật của học viên trong lab, có workflow rõ, có bottleneck cụ thể, và có thể làm pilot nhỏ bằng chính các file trong repo. Nó cũng giúp tránh lỗi hay gặp: dùng AI để viết thay bài, trong khi cách dùng đúng là dùng AI để tìm nguồn, lập checklist và phản biện.

**Câu hỏi tôi muốn nhóm challenge:**

1. Baseline 30-45 phút có đúng với đa số học viên không?
2. FAQ/rule có giải quyết đủ 70-80% trường hợp không, hay cần AI workflow?
3. Nếu AI tóm tắt sai yêu cầu nộp bài, người học sẽ phát hiện bằng cách nào?
4. Có nên giới hạn nguồn chỉ trong README, worksheet và example để giảm hallucination không?

---

# 8. Tự kiểm phần cá nhân

- [x] Có ít nhất 5 problems từ trải nghiệm học/lab.
- [x] Có 10 problems để scan rộng hơn yêu cầu tối thiểu.
- [x] Có top 3 Problem Cards đủ actor, workflow, bottleneck, impact, metric.
- [x] Có draft current workflow và future workflow cho top 3.
- [x] Có so sánh sơ bộ No AI / Rule / Workflow / Agent.
- [x] Có boundary rõ: AI hỗ trợ tìm, tóm tắt, checklist; người học vẫn kiểm nguồn và tự quyết định.
