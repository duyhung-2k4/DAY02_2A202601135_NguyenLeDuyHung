# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1   | Nguyễn Lê Duy Hưng          |  2A202601135            |     Nhóm trưởng               |
| 2   |  Hồ Phạm Đức Linh         | 2A202601533            |     Thành viên               |
| 3   | Trương Công Đạt          | 2A202601449            |   Thành viên                 |
| 4   | Nguyễn Thị Phương          |  2A202601315           |  Thành viên                  |
| 5   | Nguyễn Văn Minh         |  2A202601972           |   Thành viên                 |


# 02 — Group Problem Statement

## Group convergence

Nhóm 3-4 người, mỗi người share top 3. Tổng cộng khoảng 9-12 candidates.

| Cluster | Candidate examples | Pattern chung |
|---|---|---|
| Báo cáo / tổng hợp thông tin | Tổng hợp deadline và yêu cầu bài tập từ nhiều nguồn, người xem k có kiên nhẫn xem video dài; Sinh viên từ 18-22 khi làm báo cáo vẫn chưa biết cách trích dẫn và chưa biết nguồn đáng tin cậy để trích dẫn | Gom thông tin từ nhiều nguồn rồi viết lại cho người khác đọc |
| Tìm kiếm / hỏi đáp tài liệu | Sinh viên mất nhiều thời gian để hiểu yêu cầu của một buổi lab vì tài liệu dài, phân tán và nhiều thuật ngữ mới; Tìm lại clarification của giảng viên; Sinh viên muốn dùng các tiện ích còn lại của VinUni như thư viện, sân bóng chuyền nhưng không rõ quy trình đặt lịch, vị trí và cách book; Sinh viên năm nhất vẫn chưa hiểu cách học tập trên đại học, còn mơ hồ về cách học và cách học như thế nào; Học viên VINAI phải liên tục check thông tin từ codelab, vlearn, discord nên dễ bị quá tải vì nhiều nền tảng | Tìm đúng thông tin trong nhiều nguồn rời rạc |
| Review / feedback | Kiểm tra bài nộp thiếu thành phần| Đọc bản nháp và chỉ ra thiếu sót |
| Planning / follow-up | Action item tracking, deadline reminder; Sinh viên trọ xa nhà cần lên kế hoạch cho bữa ăn tiếp theo và cân đối chi tiêu để chọn nguyên liệu vừa đủ dinh dưỡng vừa phù hợp ngân sách | Sau cuộc họp/lab có nhiều việc bị rơi |

## Shortlist và score

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Sinh viên VinUni AI thực chiến phải hiểu yêu cầu lab, tìm clarification, nắm quy trình book tiện ích VinUni, hiểu cách học đại học và liên tục check codelab / vlearn / discord | 5 | 5 | 5 | 4 | 5 | 4 | 5 | 33 |
| Tổng hợp deadline và yêu cầu bài tập từ nhiều nguồn, người xem k có kiên nhẫn xem video dài | 4 | 3 | 4 | 3 | 5 | 3 | 4 | 26 |
| Trích dẫn và nguồn đáng tin cậy khi làm báo cáo | 4 | 4 | 4 | 3 | 5 | 4 | 4 | 28 |

Nhóm chọn: **Sinh viên VinUni AI thực chiến phải hiểu yêu cầu lab, tìm clarification, nắm quy trình book tiện ích VinUni, hiểu cách học đại học và liên tục check codelab / vlearn / discord**.

Vì sao chọn:

- Đây là pain point cụ thể của sinh viên VinUni AI thực chiến, không phải problem chung chung.
- Workflow rõ: đọc lab, hỏi clarification, tìm quy trình book tiện ích, tự học cách học đại học, và kiểm tra nhiều nền tảng học tập.
- Có thể đo được thời gian tìm thông tin, số lần bỏ sót update, và số lần phải hỏi lại.
- Có thể validate nhanh với chính sinh viên đang học.
- Có thể research các pattern gom/tóm tắt thông tin từ nhiều nguồn có sẵn.

Vì sao không chọn các bài khác:

- Câu hỏi học đại học cho sinh viên năm nhất: pain có thật nhưng workflow quá rộng, dễ trượt sang coaching hoặc content library.
- Trích dẫn và nguồn đáng tin cậy khi làm báo cáo: nhu cầu rõ nhưng không gắn trực tiếp với use case VinUni AI thực chiến.

## Quick validation

Nhóm hỏi nhanh 3 học viên / sinh viên quen biết.

| Nguồn | Số người | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Quick interview | 3 | 2/3 người phải check nhiều nguồn như codelab, vlearn, discord mỗi lần cần thông tin; đều đau ở việc bị phân tán | 1 người chỉ theo dõi một nguồn chính nên ít bị rối | Thu hẹp problem: không phải "tìm kiếm chung chung", mà là "gom đúng thông tin học tập từ nhiều nền tảng" |
| Mini poll trong lớp | 6 | 4/6 từng bỏ sót thông báo hoặc phải hỏi lại vì thông tin nằm rải rác | Một số lớp có một nguồn tổng hợp sẵn nên ít đau hơn | Thêm hướng giải pháp: một lớp tóm tắt / tổng hợp thay vì để sinh viên tự check nhiều nơi |

Insight sau validation:

```text
Pain thật không nằm ở việc "thiếu thông tin". Pain nằm ở đoạn phải liên tục ghép nhiều nguồn rời rạc thành một bức tranh rõ để biết mình cần làm gì tiếp theo.
```

## Research giải pháp

Nhóm tìm các hướng đã có sẵn, không giả định phải tự build từ đầu.

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| VLEARN / course announcements | — | Nguồn thông báo chính thức về lịch học, yêu cầu và tài liệu | Official source, ít sai lệch | Vẫn phải tự mở nhiều nơi để kiểm tra | Cần một lớp gom và tóm tắt từ nguồn chính thức |
| Discord search / pinned messages | https://support.discord.com/hc/en-us/articles/115002668172-Search-Your-Chat-History | Tìm lại clarification, Q&A và thông báo trong chat | Tra nhanh theo ngữ cảnh | Info dễ bị trôi trong chat dài | Cần khả năng lọc và nhắc lại thông tin quan trọng |
| Codelab / worksheet docs | — | Nội dung bài tập, hướng dẫn và ví dụ code | Gần với task thực hành | Tài liệu phân tán, dễ bỏ sót update | Cần hợp nhất tài liệu theo tuần / theo chủ đề |
| Gemini in Drive | https://support.google.com/drive/answer/15141241 | Tóm tắt nội dung file và draft câu trả lời | Tốt cho draft nhanh | Cần kiểm nguồn, không nên tin tuyệt đối | AI chỉ nên hỗ trợ draft, không thay thế kiểm tra của sinh viên |

Research takeaway:

```text
Không nên build một agent tự giải hết mọi thứ ngay. Hướng hợp lý hơn là một workflow tóm tắt và gom thông tin từ codelab, vlearn, discord ở các bước rõ, rồi để sinh viên tự kiểm tra lại trước khi hành động.
```

## Workflow before/after

Nội dung workflow:

```text
CURRENT STATE — 7 bước, 90 phút

[1 Mở codelab / worksheet: 10']
→ [2 Kiểm tra VLEARN: 10']
→ [3 Đọc Discord recap / pinned messages: 15']
→ [4 Tìm clarification của giảng viên: 15']
→ [5 Tìm hiểu về các tiện ích của trường: 10']
→ [6 Tự ghép lại thông tin vào note cá nhân: 25']  <-- bottleneck
→ [7 Kiểm tra lại quy trình book tiện ích VinUni nếu cần: 10']
→ [8 Hỏi lại / xác nhận với bạn bè hoặc TA: 5']

FUTURE STATE — 5 bước, 24 phút

[1 Auto-pull codelab / VLEARN / Discord summary: 2']  -- Rule/script
→ [2 QA chatbot hỏi đáp về tiện ích của trường: 3']
→ [3 AI cấu trúc input theo tuần / theo chủ đề: 1']    -- Workflow step
→ [4 AI draft câu trả lời / checklist cần làm: 1']     -- Workflow step
→ [5 Sinh viên review + edit: 15']                    -- Human boundary
→ [6 Sinh viên xác nhận và thực hiện: 2']

Fallback:
AI draft sai, thiếu nguồn, hoặc quá mơ hồ → sinh viên bỏ draft và tự kiểm tra lại từ nguồn gốc.

Bottleneck mới:
Sinh viên review + edit. Đây là bottleneck chấp nhận được vì đó là điểm kiểm soát chất lượng.
```

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Tổng thời gian | 90 phút | Dưới 30 phút | Target chính |
| Số bước | 7 | 5 | Không chỉ giảm bước, mà giảm effort ở bước tự ghép thông tin |
| Bước thủ công | 7/7 | 2/5 | Sinh viên vẫn review và xác nhận |
| Bottleneck chính | Tự tổng hợp thông tin | Review/edit | Human boundary |
| Risk mới | Không có AI hallucination | Có hallucination risk | Cần kiểm tra trước khi dùng |

## Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên VinUni AI thực chiến cần tự theo kịp tài liệu, thông báo và clarification trong lớp. |
| **Workflow** | Mỗi lần học sinh viên phải mở codelab, kiểm VLEARN, đọc Discord, tìm clarification của giảng viên, tự ghép lại note cá nhân và xác nhận thêm khi cần. |
| **Bottleneck** | Bước tự ghép thông tin mất nhiều thời gian vì dữ liệu nằm rải rác ở nhiều nền tảng và nhiều thuật ngữ mới. |
| **Impact** | Workflow chuẩn bị / tra cứu thông tin có thể mất khoảng 90 phút; sinh viên dễ bỏ sót update và phải hỏi lại nhiều lần. |
| **Success Metric** | Giảm tổng thời gian xuống dưới 30 phút; giảm số lần bỏ sót thông tin hoặc hỏi lại cùng một nội dung. |
| **Boundary** | Không tự bịa thông tin; không tự thay sinh viên quyết định nội dung cuối; chỉ dùng dữ liệu được cung cấp từ nguồn học tập chính thức. |

## Rule / Workflow / Agent

| Mức | Phương án | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Template note, pin messages, checklist theo tuần | Đủ nếu nội dung ít thay đổi | Không giải quyết việc thông tin nằm rải rác và khó ghép | Không chọn làm toàn bộ, nhưng dùng cho bước gom nguồn |
| **Workflow** | Script lấy summary từ codelab / VLEARN / Discord → AI cấu trúc → AI draft checklist / answer → sinh viên review | Hợp vì workflow tuyến tính, AI chỉ hỗ trợ vài bước ngôn ngữ | Draft sai, thiếu nguồn, cần sinh viên review | Chọn |
| **Agent** | Agent tự tìm nhiều nguồn, phân tích, hỏi thêm, rồi đề xuất hành động | Chỉ cần nếu workflow nhiều nhánh, nhiều tool, tự quyết bước tiếp theo | Quá rộng, nhiều permission/risk | Chưa chọn |

Mức chọn:

```text
Workflow.
```

Vì sao:

- Data collection có thể dùng rule/script.
- Phần ghép và diễn giải thông tin cần AI hỗ trợ ngôn ngữ.
- Sinh viên vẫn review nên risk kiểm soát được.
- Chưa cần agent vì workflow không cần tự lập kế hoạch động.

## Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên VinUni AI thực chiến cần theo dõi và hiểu thông tin học tập từ codelab, VLEARN, Discord. Muốn sử dụng tiện ích của trường mà không biết hỏi ai|
| **Workflow** | Mở nhiều nguồn → đọc thông báo / clarification → tự ghép note → kiểm tra lại → thực hiện. |
| **Bottleneck** | Ghép thông tin từ nhiều nguồn rời rạc làm sinh viên mất thời gian và dễ bỏ sót update. |
| **Impact** | Có thể mất khoảng 90 phút/tuần cho việc tra cứu / tổng hợp; sinh viên dễ chậm deadline hoặc hiểu sai yêu cầu. |
| **Success Metric** | Giảm tổng thời gian xuống dưới 30 phút; giảm số lần bỏ sót update và số lần phải hỏi lại. |
| **Boundary** | AI không tự quyết nội dung cuối, không tự bịa clarification, không thay sinh viên kiểm chứng nguồn. |
| **AI intervention point** | Sau khi các nguồn codelab / VLEARN / Discord đã được gom lại, trước bước sinh viên tự ghép note cuối. |
| **Mức chọn** | Workflow: rule/script lấy dữ liệu, AI cấu trúc và draft, sinh viên review. |
| **Rủi ro & người thật kiểm tra** | Risk: hallucination, bỏ sót nguồn, diễn giải sai. Người thật review: sinh viên phải kiểm nguồn gốc trước khi dùng. |

## Final decision

Decision:

```text
Go với scope nhỏ.
```

Pilot nhỏ nhất:

- Dùng data mẫu từ 2 tuần học gần nhất.
- Chạy workflow bán thủ công: sinh viên paste codelab / VLEARN / Discord summary vào prompt chuẩn.
- AI draft checklist / summary.
- Sinh viên đo thời gian edit và số lỗi phải sửa.

Exit / rollback:

- Nếu sinh viên vẫn phải viết lại hơn 70% draft trong 2 tuần liên tiếp, hạ xuống template + checklist thủ công.
- Nếu AI bịa thông tin hoặc trích sai nguồn, không cho dùng trực tiếp.

Decision rationale:

- Problem rõ, workflow rõ, metric rõ.
- Có non-AI components.
- AI nằm ở một bước cụ thể, không ôm toàn bộ workflow.
- Human review rõ.