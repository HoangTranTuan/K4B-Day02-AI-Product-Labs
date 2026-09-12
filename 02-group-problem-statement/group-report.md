# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Trần Tuấn Hoàng | 2A202602832 | facilitator                                                   |
| 2   | Nguyễn Minh Ngọc | 2A202602530 | workflow                                                      |
| 3   | Nguyễn Tiến Lượng | 2A202602378 | research                                                      |
| 4   | Lục Tiến Đạt | 2A202602969 | writer                                                        |

**Candidate problem nhóm chọn (1 câu):**
Sau mỗi buổi họp online 45-60 phút, nhóm đồ án không có người ghi chép Meeting Minutes dẫn đến bỏ sót 30% công việc thảo luận và tốn 25 phút sau họp để nhắn hỏi lại "ai làm gì, deadline khi nào".

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Lục Tiến Đạt | Tự động hóa tóm tắt họp nhóm online và trích xuất Action Items | Thành viên nhóm đồ án môn học (3-5 sinh viên) | Sau họp 45-60 phút không ghi chép Meeting Minutes, tốn 25 phút nhắn hỏi lại "ai làm gì", bỏ sót 30% công việc | Rất thiết thực, pain point chung cho mọi nhóm đồ án online |
| 2 | Lục Tiến Đạt | Bot tự động gom và tra cứu quyết định chốt đồ án trong nhóm chat | Thành viên nhóm đồ án môn học | Quyết định deadline, convention code, API contract bị trôi trong 100+ tin nhắn/ngày, tốn 15-20 phút scroll lội tin cũ | Tốt nhưng rủi ro AI trích xuất nhầm từ tin nhắn tán gẫu |
| 3 | Lục Tiến Đạt | Tự động hóa gom file, chuẩn hóa văn phong và định dạng Báo cáo đồ án nhóm | Sinh viên nộp báo cáo nhóm (Leader/Assembler) | Tốn 3-4 tiếng cận deadline ghép 4-5 file rời rạc, sửa lệch văn phong, font chữ, đánh lại số hình/bảng | Rất nhức nhối cận deadline nhưng phạm vi formatting rộng |
| 4 | Nguyễn Tiến Lượng | Bug report thiếu thông tin khi handoff (log, timestamp, thiết bị) | Member đội monitor (báo lỗi), Dev software/hardware (nhận) | Report ban đầu thiếu log/bối cảnh, dev phải hỏi lại 2-3 lượt, mất 10-20 phút bổ sung thông tin/lỗi | Rõ ràng, phù hợp bối cảnh monitoring/dev chuyên nghiệp |
| 5 | Nguyễn Tiến Lượng | Phát hiện bất thường từ trạng thái hệ thống và log | Member đội monitor | Đọc và đối chiếu thủ công nhiều dòng log 3-5 lần/ngày, tốn 30-60 phút/ngày | Thách thức về dữ liệu log thực tế và rule-based alert |
| 6 | Nguyễn Tiến Lượng | Tổng hợp daily note về tiến độ, issue và action item cho team software/hardware | Member monitor, PM & dev | Gom thông tin rải rác và viết lại thành note ngắn 15-20 phút/lần, lặp lại 5 lần/tuần | Quy trình chuẩn nhưng có thể giải quyết bằng template |
| 7 | Nguyễn Minh Ngọc | Tự động hóa tùy chỉnh CV theo Job Description (JD) cho từng vị trí | Fresher / Junior Developer đang tìm việc | Mất 45 phút/lần nộp (~8 tiếng/tuần) đọc JD và sửa tay key skill trong CV | Thú vị cho cá nhân tìm việc nhưng chưa gắn kết quy trình nhóm |
| 8 | Nguyễn Minh Ngọc | Tự động hóa chẩn đoán và gợi ý sửa lỗi code / cấu hình khi làm Pet Project | Dev tự học / Sinh viên làm project cá nhân | Mất 1.5-2 tiếng/lỗi, nghẽn ở bước tra cứu log, search Google/StackOverflow | Rất phổ biến khi học dev nhưng dễ trùng lặp với Copilot |
| 9 | Nguyễn Minh Ngọc | Tự động tạo Troubleshooting Guide hỗ trợ setup môi trường chạy project local cho nhóm | Leader / Thành viên nhóm làm project sinh viên | Hướng dẫn setup thiếu chi tiết, giải thích lặp đi lặp lại & debug thủ công từng máy 30-45 phút/lần | Đau thực tế khi bắt đầu đồ án mới, rất tiềm năng |
| 10 | Trần Tuấn Hoàng | Tự động hóa theo dõi tiến độ task và cảnh báo rủi ro trễ deadline đồ án | Trưởng nhóm / Facilitator đồ án môn học | Thành viên im lặng không cập nhật progress, sát hạn mới báo chưa xong, tốn 1-2 tiếng nhắn nhắc nhở | Đúng vai trò Facilitator, giải quyết bài toán giao tiếp nhóm |
| 11 | Trần Tuấn Hoàng | Tổng hợp và phân loại các yêu cầu/feedback từ Giảng viên hướng dẫn sau buổi review | Cả nhóm đồ án môn học | Phản hồi của GVHD ghi chép rải rác, không rõ ai chịu trách nhiệm sửa phần nào | Thiết thực trong các buổi làm việc với GVHD |
| 12 | Trần Tuấn Hoàng | Tự động sinh Ma trận Phân công Công việc (RACI Matrix) từ Yêu cầu Đồ án | Facilitator / Leader đồ án | Tốn 1-2 tiếng đầu dự án để chia nhỏ bài toán thành các task và phân vai cho từng người | Ý tưởng hay nhưng việc phân công vẫn cần bàn bạc trực tiếp |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A | #1, #2, #11 | Quản lý & Tóm tắt Giao tiếp/Họp nhóm đồ án | Gom thông tin họp online, quyết định chốt và feedback GVHD thành tri thức nhóm |
| B | #4, #5, #6, #9 | Hỗ trợ Quy trình & Handoff kỹ thuật/Monitoring | Chuẩn hóa thông tin handoff giữa các vai trò (Monitor - Dev, Lead - Member) |
| C | #3, #7, #12 | Tổng hợp, Biên tập & Chuẩn hóa Tài liệu/Báo cáo | Tự động ingest dữ liệu thô và định dạng lại thành báo cáo/CV chuẩn mực |
| D | #8, #10 | Quản lý Tiến độ & Chẩn đoán Lập trình cá nhân | Hỗ trợ giải quyết nghẽn cá nhân trong quá trình làm project và chạy deadline |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| Candidate #1: Tóm tắt họp nhóm online & trích xuất Action Items | 1. Actor vô cùng rõ (sinh viên làm đồ án).<br>2. Workflow 4 bước khép kín, bottleneck mất 25 min trôi tin nhắn.<br>3. Impact đo được (tiết kiệm ~50 min/tuần, giảm 30% sót task). | Rủi ro AI gán sai Assignee/Deadline nếu phần thảo luận trong họp mơ hồ. |
| Candidate #4: Bug report thiếu thông tin khi handoff | 1. Actor rõ (Monitor / Dev).<br>2. Bottleneck rõ ở khâu dev hỏi lại 2-3 lượt (mất 10-20 min/lỗi).<br>3. Giảm gián đoạn công việc của developer. | Khó demo thực tế trong buổi lab nếu thiếu dữ liệu log thật từ hệ thống monitoring. |
| Candidate #3: Gom file & chuẩn hóa văn phong Báo cáo đồ án nhóm | 1. Pain point cực lớn cận deadline (tốn 3-4 tiếng biên tập).<br>2. Workflow 5 bước rõ ràng.<br>3. Giảm 75% thời gian format thủ công. | Phạm vi định dạng báo cáo rộng; rủi ro AI làm sai lệch thuật ngữ kỹ thuật chuyên sâu. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Candidate #1 (Tóm tắt họp nhóm & Action Items) | 5 | 5 | 5 | 5 | 5 | 4 | 5 | 34 |
| Candidate #4 (Bug report handoff) | 5 | 4 | 4 | 4 | 3 | 4 | 4 | 28 |
| Candidate #3 (Biên tập báo cáo nhóm) | 4 | 4 | 5 | 4 | 4 | 4 | 4 | 29 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Candidate #1 — Tự động hóa tóm tắt họp nhóm online và trích xuất Action Items (kèm Assignee & Deadline) cho sinh viên làm đồ án môn học.
```

**Vì sao chọn (4-5 câu):**

```text
Bài toán giải quyết trực tiếp điểm nghẽn lớn nhất trong giao tiếp nhóm đồ án là sự bất đồng và bỏ sót công việc sau các buổi họp online 45-60 phút. Actor là sinh viên đồ án rất cụ thể và nhóm hoàn toàn làm chủ domain context. Workflow 4 bước rõ ràng, cho phép đo đạc trực tiếp hiệu quả tiết kiệm 25 phút/buổi họp và giảm 30% tỷ lệ sót task. Phương án AI Workflow kết hợp Human Review (Trưởng nhóm confirm checklist) có tính khả thi cực cao để xây dựng và kiểm thử MVP ngay trong buổi lab.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Candidate #4 (Bug report handoff): Mặc dù pain point của đội monitor rất rõ, nhưng bối cảnh hạ tầng monitoring phức tạp và khó thu thập dữ liệu log thật để demo trong môi trường học tập.
- Candidate #3 (Biên tập báo cáo nhóm): Bài toán có phạm vi quá rộng do văn phong và định dạng tài liệu đa dạng, dễ gặp rủi ro AI làm biến đổi thuật ngữ kỹ thuật chuyên môn nếu không có prompt guardrail phức tạp.
- Candidate #7 (Tùy chỉnh CV): Đây là bài toán mang tính cá nhân cao, chưa thể hiện được sự phối hợp workflow làm việc nhóm trong bài tập lớn.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Nhóm từng băn khoăn liệu có nên hạ mức xuống Rule (bắt buộc phân công 1 bạn gõ Google Docs trong lúc họp) thay vì dùng AI. Tuy nhiên, nhóm thống nhất rằng thành viên vừa thảo luận vừa ghi chép gõ tay rất dễ mất tập trung và bỏ sót ý chính. AI Workflow là lựa chọn tối ưu để vừa lưu lại thông tin vừa đảm bảo trải nghiệm họp tự nhiên.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 3 sinh viên đồ án | "Họp xong 60 phút ai cũng mệt thoát room ngay, đến hôm sau làm task mới nhắn nhó hỏi nhau hôm qua ai làm phần nào." | "Nếu cuộc họp nói chuyện đùa nhiều quá thì AI ghi lại hết tin rác." | Bổ sung bước lọc rác và thêm bảng Draft cho Leader review trước khi chốt. |
| Survey / poll | 10 sinh viên CNTT | 8/10 người trả lời từng bỏ sót task hoặc quên deadline trao đổi trong cuộc họp online. | 2/10 người nói nhóm họ nhỏ (2 người) nên tự nhớ được. | Giữ nguyên scope cho nhóm đồ án từ 3-5 thành viên. |
| Log / ticket / review (nếu có) | 5 đoạn chat Zalo nhóm | 15+ tin nhắn dạng "Hôm qua chốt ai làm phần backend vậy mọi người?" | Không có. | Giữ nguyên giả định về thời gian lãng phí nhắn hỏi lại. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không nằm ở việc họp dài hay ngắn, mà nằm ở khoảng trống handoff sau họp: thiếu một danh sách Action Items được xác nhận chính thức với tên người phụ trách và deadline rõ ràng.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `02-group-problem-statement-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Otter.ai | https://otter.ai | Ingest âm thanh & tóm tắt meeting | Tóm tắt nhanh, giao diện hiện đại | Không tối ưu tiếng Việt pha tiếng Anh IT; không push vào Discord nhóm | Cần prompt chuyên cho tiếng Việt + export dạng checklist Discord |
| Notion AI Meeting Notes | https://notion.so | Tóm tắt ghi chú trong Notion | Tích hợp sẵn trong workspace | Cần copy-paste transcript thủ công | Tự động hóa bước ingest transcript từ file ghi âm/text |
| Zoom AI Companion | https://zoom.us | Summary trực tiếp trên app Zoom | Không cần cài app ngoài | Thiếu bước Human Confirm trước khi giao task | Bắt buộc có Human Boundary để Leader kiểm duyệt |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nên build: AI Workflow ingest file transcript tiếng Việt + xuất Draft Action Items (Task, Assignee, Deadline) cho Leader review và tự động push vào Discord. Không build: Tính năng âm thanh live-streaming phức tạp hoặc hệ thống tự động giao task lên Jira mà không qua kiểm duyệt.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png`

```text
[1. Họp online thảo luận: 45' - Thành viên] → [2. Trao đổi ý tưởng không ghi chép: 10'] → [3. Thoát room họp: 2'] → [4. Nhắn hỏi lại "ai làm gì" trên Zalo: 15' - BOTTLENECK] → [5. Leader gõ lại recap theo trí nhớ: 10' - BOTTLENECK]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Thành viên | Mở room họp online | Thảo luận tiến độ đồ án | 45 min / 2 lần/tuần | Trao đổi bằng lời nói |
| 2 | Thành viên | Ý tưởng & phân công miệng | Không có file note | 10 min / 2 lần/tuần | Thiếu công cụ ghi chép |
| 3 | Thành viên | Kết thúc buổi họp | Rời room online | 2 min / 2 lần/tuần | Gãy context handoff |
| 4 | Thành viên | Trí nhớ cá nhân | Tin nhắn nhắn hỏi lại trên Zalo | 15 min / 2 lần/tuần | BOTTLENECK — Trôi tin nhắn, lãng phí thời gian |
| 5 | Leader | Trí nhớ & tin nhắn hỏi đáp | Recap ngắn gõ tay trên Zalo | 10 min / 2 lần/tuần | BOTTLENECK — Thiếu chính xác, bỏ sót 30% task |

**Bottleneck chính (2-3 câu):**

```text
Bottleneck chính nằm ở Bước 4 & 5 (mất 25 phút/buổi họp). Việc không có công cụ ghi chép thời gian thực khiến quyết định bị trôi trong tin nhắn chat, buộc các thành viên phải nhắn hỏi lại và Leader phải gõ recap thủ công theo trí nhớ.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1. Họp online (Record/Transcript): 45' - Người] → [2. AI tóm tắt & trích xuất Checklist Task/Assignee: 1' - AI] → [3. Leader review & confirm checklist: 2' - Người (HUMAN BOUNDARY)] → [4. Bot push Action Items vào Discord: 0' - Rule]

Fallback: Nếu AI trích xuất thiếu/sai task hoặc gán sai Assignee, Leader chỉnh sửa thủ công trên giao diện Draft Checklist trước khi bấm Confirm.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | 82 min | 48 min | Bấm giờ từ khi bắt đầu họp đến khi có checklist chính thức |
| Số bước | 5 bước | 4 bước | Đếm số bước quy trình |
| Số bước thủ công | 3 bước | 1 bước (review) | Đếm số bước thao tác tay thủ công |
| Bottleneck chính | 25 min trôi tin nhắn | 2 min review draft | Thời gian xác nhận task sau họp |
| Risk mới | Sót task 30% | AI hallucinate gán sai task | Tỷ lệ phải sửa tay ở bước review |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Thành viên nhóm đồ án môn học (3-5 sinh viên ngành Khoa học Máy tính / IT). |
| **Workflow** | Sau các buổi họp online 45-60 phút trên Google Meet/Discord, nhóm thảo luận phân công công việc nhưng không có người ghi chép Meeting Minutes. |
| **Bottleneck** | Tốn 25 phút sau họp để nhắn hỏi lại "ai làm gì, deadline khi nào" và bỏ sót 30% công việc thảo luận. |
| **Impact** | Lãng phí ~50 phút/tuần/nhóm và gây trễ deadline bài tập lớn do quên task. |
| **Success Metric** | Giảm thời gian xác nhận task xuống < 3 phút; 100% buổi họp có checklist Action Items đính kèm Assignee & Deadline. |
| **Boundary** | Làm tóm tắt meeting & trích xuất task từ transcript; Không làm tự động phân công task mà không có Leader review. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Field Boundary chưa nêu rõ cách xử lý khi transcript bị nhiễu hoặc sai tên người.
- Tôi sửa gì: Bổ sung bước Human-in-the-loop (Leader review & edit draft) trước khi xuất bản checklist.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Nội dung thảo luận trong họp online không theo cấu trúc cố định, ngôn ngữ tự do tiếng Việt pha thuật ngữ IT.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Cần ingest transcript -> phân tích ngữ cảnh -> trích xuất entity (Task, Assignee, Deadline) -> sinh checklist.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô [Độ mơ hồ Cao + Độ phức tạp Cao] — Phù hợp giải quyết bằng AI Workflow kết hợp Human Review.
```

**Vì sao (2-3 câu):**

```text
Dữ liệu đầu vào là hội thoại tự nhiên thiếu cấu trúc nên Rule-based không thể bóc tách được. Tuy nhiên, quy trình xử lý theo luồng các bước cố định nên chưa cần dùng đến AI Agent tự chủ lập kế hoạch.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Bắt buộc phân công 1 bạn mở Google Docs gõ tay checklist trong lúc họp | Khi cuộc họp rất ngắn (< 10 phút) và chỉ có 1-2 task đơn giản | Thành viên ngại làm thư ký, vừa họp vừa gõ dễ bị sót ý kiến | Không |
| **Workflow** | Ingest transcript -> AI trích xuất Draft Checklist -> Leader review -> Bot push Discord | Đủ cho 95% cuộc họp nhóm đồ án online | AI nhận diện sai Assignee nếu cuộc họp trao đổi không rõ tên | CÓ (Dùng cho toàn bộ quy trình) |
| **Agent** | AI Agent tự tham gia cuộc họp, tự phỏng vấn từng người và tự gán task lên Trello | Không cần thiết ở quy mô bài tập nhóm sinh viên | AI Agent tự ý giao sai task mà không ai kiểm soát, gây xung đột | Không |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? Không, vì ngôn ngữ trao đổi trong họp online rất tự do và thiếu cấu trúc.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? Đi thẳng một đường từ Transcript -> AI Extract -> Review -> Push Discord.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? Không, vì quy trình đã cố định sẵn các bước xử lý.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? Trưởng nhóm phát hiện ngay ở bước Review Draft và sửa lại trong 30 giây.
5. Có hạ được từ Agent → Workflow → Rule không? Có, hạ từ Agent xuống Workflow là mức tối ưu nhất cho bài toán này.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Quy trình có trình tự 4 bước rõ ràng và cố định. Việc chọn mức Workflow giúp kết hợp sức mạnh của AI (tóm tắt & trích xuất ngôn ngữ tự nhiên) với sự an toàn của con người (Leader review draft), tránh rủi ro AI giao nhầm task hoặc tạo thông tin giả.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Không chọn Rule vì quy tắc cứng không thể hiểu và phân loại được đoạn hội thoại nói chuyện tự do của sinh viên trong buổi họp. Việc bắt gõ tay thủ công vẫn tạo ra cảm giác phiền phức và dễ bị lười không thực hiện.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Thành viên nhóm đồ án môn học (3-5 sinh viên ngành Khoa học Máy tính / IT). |
| **Workflow** | Sau buổi họp online 45-60 phút, file transcript/audio được ingest vào hệ thống AI để tự động tóm tắt và trích xuất Action Items. |
| **Bottleneck** | Bước xác nhận và tổng hợp Action Items sau họp tốn 25 phút và dễ bỏ sót 30% công việc thảo luận. |
| **Impact** | Tiết kiệm ~50 phút/tuần/nhóm; đảm bảo 100% công việc được ghi nhận và theo dõi đúng hạn. |
| **Success Metric** | Thời gian tạo checklist chốt < 3 phút; độ chính xác trích xuất Task & Assignee > 85%. |
| **Boundary** (làm / không làm) | Làm: Ingest transcript, tóm tắt quyết định, trích xuất checklist Task/Assignee/Deadline, export sang Discord. Không làm: Tự động gán task lên Jira/Trello mà chưa qua Leader duyệt; không tự sửa code hay chạy test. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp sau bước kết thúc cuộc họp (có file transcript) và trước bước đăng Action Items chính thức vào nhóm chat. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow — Vì quy trình đi theo luồng cố định có bước Human Boundary kiểm duyệt bắt buộc. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất: AI nhận diện sai Assignee hoặc hiểu lầm câu nói trêu đùa thành task. Người thật kiểm tra: Trưởng nhóm đọc & xác nhận/chỉnh sửa trên giao diện Draft trước khi chốt. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor sinh viên đồ án và workflow 4 bước đã được xác minh rõ ràng. |
| Baseline + metric đo được chưa? | Yes | Baseline 25 phút sau họp; metric mục tiêu < 3 phút xác nhận. |
| Data/input đủ dùng chưa? | Yes | Input là file transcript/audio cuộc họp Google Meet/Discord. |
| AI sai, hậu quả chấp nhận được không? | Yes | AI sai chỉ tạo draft lệch, Leader sửa lại trong 30 giây ở bước Review. |
| Có người review/owner không? | Yes | Leader nhóm chịu trách nhiệm review và duyệt checklist. |
| Có cách non-AI đơn giản hơn không? | No | Phương án gõ tay thủ công trong họp gây lười và hay bỏ sót. |

**Decision:**

```text
Go
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Bài toán đáp ứng đầy đủ 7 câu hỏi trong worksheet. Actor và pain point thực tế của nhóm sinh viên rất rõ ràng. Giải pháp AI Workflow kết hợp ranh giới Leader kiểm duyệt loại bỏ hoàn toàn rủi ro hallucination, đem lại ROI cao và hoàn toàn khả thi để xây dựng bản demo trong buổi lab.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data: 3 file transcript cuộc họp nhóm đồ án thật (30-45 phút/buổi).
- Chạy tay ra sao: Ingest transcript vào app Streamlit/Python -> AI sinh JSON draft -> Leader check/edit -> Push webhook Discord.
- Đo 3 số: (1) Thời gian sinh & duyệt checklist (< 3 min), (2) Số task bị sót (0 task), (3) Tỷ lệ gán đúng Assignee (> 85%).
```

**Nếu Not Yet — cần validate gì trước:**

```text
N/A
```

**Nếu No-Go — làm gì thay AI:**

```text
N/A
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nếu file âm thanh/transcript chất lượng quá kém làm AI trích xuất sai > 50% thông tin, hệ thống rollback về dạng Form nhập liệu checklist bán thủ công do Leader điền.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
