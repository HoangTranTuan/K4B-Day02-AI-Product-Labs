# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Lục Tiến Đạt
- Mã học viên: 2A202602969
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên ngành Khoa học Máy tính
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): 
  1. Học tập (làm bài tập, đọc tài liệu, tra cứu kiến thức mới)
  2. Điểm danh, kiểm tra kiến thức
  3. Tham gia hoạt động của lớp và câu lạc bộ
  4. Tự học các môn học yêu thích
  5. Sử dụng, tiếp cận các phần mềm mới

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Tra cứu lại các quyết định chốt deadline, quy chuẩn code, format nộp bài bị trôi trong 100+ tin nhắn nhóm Zalo/Discord đồ án. | Thành viên nhóm đồ án môn học (3-5 sinh viên/nhóm). | Nhóm chat 150+ tin/ngày; 2-3 ngày lại có bạn nhắn hỏi "Chốt nộp file .zip hay link Git?", "Gửi file cho ai?"; mất 15-20 phút scroll tìm tin nhắn pinned cũ. |
| 2 | Pain từ người khác | Thành viên "im lặng" không cập nhật tiến độ task được giao, đến sát deadline mới báo chưa làm xong hoặc chưa chạy được code. | Trưởng nhóm đồ án (Group Leader) / Sinh viên gánh team. | 2 đợt đồ án/kỳ; 1-2 ngày trước hạn phải nhắn tag tên thúc 4-5 lần; 2/4 thành viên báo nghẽn code làm cả nhóm thức đêm từ 11h đêm - 4h sáng làm bù. |
| 3 | Tốn thời gian | Thành viên commit/push code sai thư mục quy định trên GitHub nhóm (ví dụ bỏ sai vị trí file report/code) làm gãy Autograder chấm 0 điểm. | Git Maintainer / Trưởng nhóm đồ án. | Xảy ra 1-2 lần/milestone; tốn 45-60 phút mò `git log`, gỡ conflict và sửa lại cấu trúc thư mục repo cho đúng quy định nộp bài trước giờ G. |
| 4 | Lặp lại | Tân binh / thành viên mới trong CLB Lập trình liên tục hỏi trùng lặp các câu hỏi về lịch sinh hoạt, cách cài môi trường VS Code/Git, link drive mẫu. | Ban Chuyên môn CLB IT / Mentor sinh viên khóa trên. | Nhận 10-15 câu hỏi giống nhau mỗi tuần trên kênh Discord CLB; tốn 10-15 phút/lần gõ lại câu trả lời hoặc tìm link cũ dán lại; tổng mất ~3 tiếng/tuần. |
| 5 | Pain từ người khác | Hai bạn làm Frontend & Backend ghép code bị lỗi integration do lệch quy chuẩn API contract (JSON response field name) không được ghi chép rõ. | Sinh viên CS làm đồ án tích hợp Fullstack / AI Web App. | Xảy ra ở 100% buổi ghép code nhóm; mất 2-3 tiếng ngồi refactor lại DTO/API payload và debug lỗi `500 Internal Server Error` do lệch tên biến. |
| 6 | AI có thể tốt hơn | Nhóm họp online (Google Meet/Teams) 45-60 phút thảo luận nhiều ý tưởng nhưng không ai ghi chép Meeting Minutes, sau họp không nhớ rõ Action Items. | Tất cả thành viên nhóm đồ án môn học. | Họp 2 buổi/tuần (45 phút/buổi); sau họp tốn thêm 20 phút nhắn hỏi lại "Hôm nay chốt ai làm gì?"; 30% công việc thảo luận bị bỏ sót không ai thực hiện. |
| 7 | Pain từ người khác | Lớp trưởng / Ban cán sự phải đi nhắn inbox riêng thúc giục từng bạn nộp bài tập lớn/file điểm danh và kiểm tra thủ công xem có nộp thiếu file không. | Lớp trưởng / Trợ giảng (TA) / Trưởng nhóm lớn. | 10-15/40 sinh viên chưa nộp khi còn 2 tiếng đến deadline; Lớp trưởng mất 1.5 - 2 tiếng nhắn tin riêng thúc giục và check từng link nộp bài. |
| 8 | Tốn thời gian | Tổng hợp và biên tập lại phần Báo cáo đồ án nhóm (Word/Markdown) từ 4-5 đoạn văn rời rạc, lệch font chữ và văn phong của các thành viên. | Người chịu trách nhiệm gom & nộp Báo cáo đồ án. | 2-3 báo cáo/học kỳ; tốn 3-4 tiếng trước hạn nộp chỉ để căn chỉnh margin, sửa lỗi chính tả, đánh lại số hình ảnh và gom 4 file lẻ thành 1 file chuẩn. |
| 9 | AI có thể tốt hơn | CLB cần tái sử dụng tính năng/code mẫu dự án cũ (bot điểm danh, form đăng ký) nhưng tài liệu và repo bị thất lạc trong Drive cá nhân của cựu thành viên. | Ban Dự án / Ban Kỹ thuật CLB Lập trình. | 3-4 lần/năm khi mở event mới; mất 2-3 ngày nhắn tin nhờ cựu thành viên tìm lại link repo/drive; nếu không tìm được phải tốn 15-20 tiếng code lại từ đầu. |
| 10 | Tốn thời gian | Review Pull Request (PR) đồ án nhóm nhưng thành viên tạo PR không ghi mô tả (Description), làm người review phải tự pull code về máy đoán logic. | Người review code / Leader đồ án. | 5-7 PRs/tuần; tốn 25-30 phút/PR tự pull code về chạy thử để đoán xem bạn mình đã sửa gì; 2/5 PRs bị lọt lỗi do review qua loa vì thiếu context. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Tôi là Sinh viên CS năm 2-3, vừa làm đồ án nhóm vừa tham gia ban chuyên môn CLB IT. Hãy gợi ý 10 problem thực tế về giao tiếp nhóm, quản lý task đồ án, review code và hỗ trợ thành viên CLB kèm số đo cụ thể."
- Ý dùng được: Phân tích pain point về việc trôi tin nhắn chốt API contract/deadline trong Zalo nhóm (Problem 1 & 5) và bài toán họp nhóm không ghi chép Action Items (Problem 6).
- Ý bỏ vì không phải pain thật: Ý tưởng "Tự động phân công task đồ án mà không cần họp nhóm" (bỏ vì thiếu tính tương tác thực tế và nhóm vẫn phải bàn bạc trực tiếp).

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Nhóm họp online (Google Meet/Teams) 45-60 phút thảo luận nhiều ý tưởng nhưng không ai ghi chép Meeting Minutes, sau họp không nhớ rõ Action Items (Problem #6). | 1. Actor rõ (thành viên đồ án), workflow 4 bước rõ ràng.<br>2. Bottleneck lớn ở bước ghi chép & trích xuất Action Items (bỏ sót 30% công việc).<br>3. AI fit rất cao (tóm tắt transcript & xuất checklist công việc tự động). | Khả năng nhận diện đúng người chịu trách nhiệm (assignee) và deadline nếu thông tin trao đổi trong buổi họp mơ hồ. |
| 2 | Tra cứu lại các quyết định chốt deadline, quy chuẩn code, format nộp bài bị trôi trong 100+ tin nhắn nhóm Zalo/Discord đồ án (Problem #1). | 1. Tần suất lặp lại cao (150+ tin/ngày, xảy ra 2-3 lần/tuần).<br>2. Workflow tra cứu rõ ràng, đo được tác động (giảm từ 20 min xuống < 1 min).<br>3. Dễ triển khai thử nghiệm dạng Bot gom tin chốt trong Discord. | Phân biệt tự động giữa tin nhắn tán tán/trêu đùa và tin nhắn chốt quyết định chính thức (tránh AI gom nhầm tin rác). |
| 3 | Tổng hợp và biên tập lại phần Báo cáo đồ án nhóm (Word/Markdown) từ 4-5 đoạn văn rời rạc, lệch font chữ và văn phong của các thành viên (Problem #8). | 1. Pain point cực lớn ở cận deadline (tốn 3-4 tiếng biên tập trước giờ nộp).<br>2. Workflow 5 bước rõ ràng (Gom file -> Thống nhất văn phong -> Format Markdown -> Đánh số hình).<br>3. Giảm 80% thời gian định dạng thủ công của người nộp báo cáo. | AI có thể làm sai lệch hoặc tóm tắt quá đà các đoạn giải thích kỹ thuật chuyên sâu của từng thành viên (cần Human Review). |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tự động hóa tóm tắt họp nhóm online và trích xuất Action Items

```text
Problem 1 câu: Sau mỗi buổi họp online 45-60 phút, nhóm đồ án không có người ghi chép Meeting Minutes dẫn đến bỏ sót 30% công việc thảo luận và tốn 25 phút sau họp để nhắn hỏi lại "ai làm gì, deadline khi nào".

Actor: Thành viên nhóm đồ án môn học (3-5 sinh viên ngành Khoa học Máy tính).

Thời điểm / bối cảnh: Sau các buổi họp online định kỳ 2 lần/tuần trên Google Meet / Microsoft Teams / Discord để báo cáo tiến độ và phân công task đồ án.

Current workflow 3-7 bước:
1. Nhóm mở room họp online thảo luận tiến độ và phân công công việc (45 phút).
2. Các thành viên trao đổi ý tưởng và nhận task miệng (không ai mở file ghi chép Meeting Minutes) (10 phút).
3. Kết thúc buổi họp, mọi người thoát room mà không có bản tóm tắt công việc chính thức (2 phút).
4. Sau họp 1-2 tiếng, thành viên quên task nhắn lại vào nhóm chat hỏi "Hôm nay chốt ai làm phần nào nhỉ?" (15 phút) <-- BOTTLENECK.
5. Trưởng nhóm phải ngồi gõ lại tin nhắn tóm tắt ngắn các đầu việc theo trí nhớ (10 phút).

Bottleneck: Bước 4 & 5 (mất 25 phút/buổi họp) — Không có ghi chép thời gian thực làm trôi quyết định và bỏ sót công việc thảo luận.

Impact: Tiết kiệm 25 phút/buổi họp x 2 buổi/tuần = ~50 phút/tuần/nhóm; giảm tỷ lệ bỏ sót task từ 30% xuống dưới 5%.

Success metric: 
1. Giảm thời gian xác nhận task sau họp từ 25 phút xuống dưới 3 phút (chỉ cần xem & duyệt checklist AI tạo).
2. Đảm bảo 100% buổi họp có danh sách Action Items gắn kèm Assignee và Deadline cụ thể.

Non-AI alternative: Phân công xoay vòng 1 bạn trong nhóm làm "Thư ký buổi họp" bắt buộc mở Google Docs ghi chép tay trong lúc họp. (Rủi ro: Thành viên ngại làm thư ký, vừa thảo luận vừa gõ gõ dễ bị sót ý kiến quan trọng).

AI hypothesis: Sử dụng AI (LLM / Audio Transcript Summarizer) đọc file ghi âm/transcript buổi họp để tự động phân loại: (1) Tóm tắt các quyết định chính, (2) Trích xuất Action Items (Task + Người phụ trách + Deadline) dưới dạng checklist tự động.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 82 phút

[1. Họp online thảo luận: 45'] → [2. Trao đổi ý tưởng không ghi chép: 10'] → [3. Thoát room họp: 2'] → [4. Nhắn hỏi lại "ai làm gì" trên Zalo: 15'] <-- bottleneck → [5. Trưởng nhóm gõ lại recap theo trí nhớ: 10']

FUTURE STATE — 48 phút

[1. Họp online (bật Record/Transcript): 45'] → [2. AI tự động tóm tắt & trích xuất Checklist Task + Assignee: 1'] → [3. Trưởng nhóm review & confirm danh sách Task: 2'] <-- human boundary → [4. Bot tự động post Action Items vào nhóm Discord: 0']

Fallback: Nếu AI trích xuất thiếu/sai task, Trưởng nhóm chỉnh sửa thủ công trên giao diện Draft trước khi bấm Confirm gửi nhóm.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Bot tự động gom và tra cứu quyết định chốt đồ án trong nhóm chat

```text
Problem 1 câu: Thành viên nhóm đồ án tốn 15-20 phút scroll lội 100+ tin nhắn rác/ngày để tìm lại các quyết định chốt về deadline, format nộp file, hay quy chuẩn đặt tên biến/API contract.

Actor: Thành viên nhóm đồ án môn học (3-5 sinh viên/nhóm).

Thời điểm / bối cảnh: Trong quá trình thực hiện bài tập lớn/đồ án môn học khi nhóm nhắn tin trao đổi liên tục mỗi ngày trên Discord/Zalo.

Current workflow 3-7 bước:
1. Thành viên cần tìm lại thông tin quy định (vd: "Hạn nộp file .zip hay link Git?", "Tên field API là gì?").
2. Mở ứng dụng chat (Zalo/Discord) và gõ từ khóa vào thanh search thủ công (3 phút).
3. Lướt qua 50-100 tin nhắn thảo luận rải rác, tán tán để tìm câu trả lời (10 phút) <-- BOTTLENECK.
4. Nếu không thấy, nhắn lại vào nhóm hỏi "Có ai nhớ hôm trước chốt thế nào không?" (2 phút).
5. Chờ thành viên khác đọc tin nhắn và trả lời lại (5 phút).

Bottleneck: Bước 3 (mất 10 phút/lượt) — Tin nhắn quan trọng bị vùi lấp bởi tin nhắn thảo luận tự do và hình ảnh meme.

Impact: Giảm thời gian tìm kiếm thông tin chốt từ 20 phút xuống dưới 1 phút; giảm 90% các câu hỏi lặp đi lặp lại trong nhóm chat.

Success metric:
1. Thời gian tra cứu thông tin quyết định thành công < 1 phút/lượt.
2. Độ chính xác của câu trả lời trích xuất từ lịch sử chat đạt > 90%.

Non-AI alternative: Quy định thành viên mỗi khi chốt cái gì phải ghim tin nhắn (Pin Message) hoặc tự copy vào 1 file Notion chung. (Rủi ro: Mọi người hay quên ghim, file Notion không được cập nhật thường xuyên).

AI hypothesis: Xây dựng AI Bot (Discord Bot / Chat Assistant) tự động phân loại các tin nhắn chứa từ khóa chốt (`chốt:`, `deadline:`, `convention:`) lưu vào DB và cho phép gõ lệnh `/find [câu hỏi]` để AI RAG tổng hợp câu trả lời chính xác kèm link tin nhắn gốc.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 20 phút

[1. Nhớ ra cần tìm quyết định cũ: 1'] → [2. Gõ từ khóa search trên Chat: 3'] → [3. Scroll lội 100+ tin nhắn rác: 10'] <-- bottleneck → [4. Nhắn hỏi lại cả nhóm trên chat: 2'] → [5. Chờ bạn khác vào trả lời: 4']

FUTURE STATE — 1 phút

[1. Gõ lệnh `/find [câu hỏi]` trên Discord: 0.1'] → [2. AI RAG tra cứu trong DB tin nhắn đã lọc: 0.4'] → [3. Bot trả về ngay câu trả lời + link tin nhắn gốc: 0.1'] → [4. Người dùng xem & confirm thông tin: 0.4'] <-- human boundary

Fallback: Nếu AI không tìm thấy hoặc độ tin cậy < 80%, Bot phản hồi "Chưa có quyết định chốt về mục này" và gợi ý tag Trưởng nhóm.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tự động hóa gom file, chuẩn hóa văn phong và định dạng Báo cáo đồ án nhóm

```text
Problem 1 câu: Người chịu trách nhiệm nộp báo cáo nhóm tốn 3-4 tiếng cận deadline để ghép 4-5 file riêng lẻ của các thành viên, sửa lỗi lệch font chữ, sai văn phong và đánh lại số thứ tự hình ảnh/bảng biểu.

Actor: Sinh viên nộp báo cáo nhóm (Report Assembler / Leader).

Thời điểm / bối cảnh: 1-2 ngày trước deadline nộp bài tập lớn / đồ án môn học.

Current workflow 3-7 bước:
1. Nhận 4-5 file Markdown/Word rời rạc từ các thành viên trong nhóm qua chat (15 phút).
2. Copy-paste toàn bộ nội dung vào 1 file Báo cáo tổng (15 phút).
3. Đọc và sửa từng đoạn văn bị lệch văn phong (người viết ngôi "tôi", người viết "nhóm em", người gõ tiếng Anh) (90 phút) <-- BOTTLENECK.
4. Căn chỉnh margin, font chữ, sửa heading và đánh lại số thứ tự Hình 1, Hình 2, Bảng 1 (60 phút) <-- BOTTLENECK.
5. Xuất file PDF/Markdown cuối cùng và rà soát lỗi chính tả trước khi nộp (30 phút).

Bottleneck: Bước 3 & 4 (mất 150 phút/báo cáo) — Đọc và chỉnh sửa thủ công định dạng & văn phong từ nhiều nguồn khác nhau.

Impact: Tiết kiệm 75% thời gian biên tập báo cáo (từ 3.5 tiếng xuống dưới 45 phút); báo cáo chuyên nghiệp, đồng nhất 100%.

Success metric:
1. Thời gian tổng hợp & biên tập báo cáo giảm từ 210 phút xuống < 45 phút.
2. 100% các mục heading, hình ảnh, bảng biểu và văn phong đạt chuẩn quy định của giảng viên.

Non-AI alternative: Tạo sẵn 1 template Google Docs / Latex chung, bắt buộc các thành viên tự điền đúng định dạng ngay từ đầu. (Rủi ro: Các thành viên vẫn copy-paste văn phong riêng, viết sai format heading).

AI hypothesis: AI tự động ingest các file đóng góp của thành viên, thực hiện 2 việc: (1) Chuẩn hóa văn phong sang dạng kỹ thuật khách quan, (2) Export ra file Markdown/PDF chuẩn khung mẫu với số thứ tự hình ảnh/bảng tự động.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 210 phút

[1. Thu gom 4-5 file riêng lẻ: 15'] → [2. Copy-paste vào file chung: 15'] → [3. Sửa lệch văn phong & câu từ: 90'] <-- bottleneck → [4. Định dạng font, margin, số hình: 60'] <-- bottleneck → [5. Review & xuất PDF nộp: 30']

FUTURE STATE — 35 phút

[1. Upload 4-5 file thành viên vào công cụ: 2'] → [2. AI tự động đồng nhất văn phong kỹ thuật: 3'] → [3. System auto-format khung Markdown/PDF & số hình: 2'] → [4. Người biên tập đọc review & duyệt câu từ: 25'] <-- human boundary → [5. Export file PDF/MD chính thức: 3']

Fallback: Nếu AI làm sai lệch thuật ngữ kỹ thuật, người dùng chọn "Restore original paragraph" để giữ nguyên đoạn văn gốc của thành viên.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Tự động hóa tóm tắt họp nhóm online và trích xuất Action Items (Problem #6 trong bảng scan)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Bài toán này giải quyết trực tiếp điểm nghẽn lớn nhất trong giao tiếp nhóm đồ án là sự bất đồng và bỏ sót công việc sau mỗi buổi họp online. Với workflow 4 bước rõ ràng, đo đạc giảm được 25 phút/buổi họp và loại bỏ 30% công việc bị lãng quên, đây là bài toán có ROI cực kỳ cao và hoàn toàn khảthi để xây dựng MVP trong buổi lab.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. "Nếu các thành viên trong buổi họp nói xen ngang hoặc trao đổi không rõ tên task/người nhận task, làm sao AI phân biệt được chính xác ai là Assignee?"
2. "Liệu một quy trình quản lý đơn giản như bắt buộc Trưởng nhóm gõ checklist ngay sau họp có đủ giải quyết vấn đề không, tại sao lại cần đến giải pháp AI Workflow?"
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Phụ thuộc vào chất lượng file âm thanh/transcript. Nếu mic bị rè hoặc sinh viên nói tiếng Việt lẫn thuật ngữ tiếng Anh chuyên ngành (vd: "deploy backend", "refactor DTO"), AI có thể nhận diện sai từ khóa hoặc gán sai người chịu trách nhiệm.
- Tôi sửa gì: Đưa vào ranh giới người kiểm duyệt bắt buộc (Human-in-the-loop): AI chỉ xuất bản "Draft Checklist", Trưởng nhóm có bảng điều khiển chỉnh sửa nhanh Assignee/Task trong 2 phút trước khi bấm xác nhận để Bot gửi tin nhắn chính thức vào nhóm.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
