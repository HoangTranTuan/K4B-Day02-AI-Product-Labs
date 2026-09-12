# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Tiến Lượng
- Mã học viên: 2A202602378
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Monitoring Engineer
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): Xuống line giám sát hệ thống, theo dõi dữ liệu

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được                                                                                                                    | Ai chịu ảnh hưởng?  | Dấu hiệu thật (số + bằng chứng)                                     |
|---|------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|---------------------|---------------------------------------------------------------------|
| 1 | Lặp lại                                                                      | Mỗi ngày member phải tổng hợp tiến độ, vấn đề phát sinh và action item để gửi daily note cho  team software/hardware.                    | PM, member trong đội software và đội hardware, monitor | 5 lần/tuần, khoảng 15–20 phút/lần.                                  |
| 2 | Lặp lại                                                                      | Mỗi ngày member đội monitor phải kiểm tra trạng thái hệ thống và log để phát hiện bất thường, sau đó tổng hợp thông tin lỗi gửi đội software/hardware điều tra. | Member trong đội monitor, software, hardware | Kiểm tra 3–5 lần/ngày, tổng khoảng 30–60 phút/ngày.                 |
| 3 | Tốn thời gian                                                                | Mỗi cuối tuần PM phải tổng hợp báo cáo tiến độ từ các member, xác định vấn đề còn tồn đọng và lập plan tuần tiếp theo để gửi đối tác.    | PM, member trong đội software và hardware, đối tác | Lặp lại một tuần một lần                                            |
| 4 | Tốn thời gian                                                                | Trong weekly meeting, PM phải ghi chú nội dung cuộc họp; sau cuộc họp tiếp tục tổng hợp, chỉnh sửa và dịch biên bản sang tiếng Việt để gửi team. | PM, Communication   | 1 buổi/tuần: 45 phút để note                                        |
| 5 | Pain từ người khác                                                           | Khi team monitor phát hiện lỗi và báo cho developer, thông tin đôi khi chưa đầy đủ như log, thời điểm xảy ra lỗi, thiết bị hoặc điều kiện gây lỗi, khiến developer phải hỏi lại trước khi có thể điều tra| Dev, software, hardware, member đội monitor | Mỗi lỗi phải hỏi lại khoảng 2–3 lần, mất thêm khoảng 10–20 phút/lỗi |
| 6 |                                                                              |                                                                                                                                          |                     |                                                                     |
| 7 |                                                                              |                                                                                                                                          |                     |                                                                     |
| 8 |                                                                              |                                                                                                                                          |                     |                                                                     |
| 9 |                                                                              |                                                                                                                                          |                     |                                                                     |
| 10 |                                                                              |                                                                                                                                          |                     |                                                                     |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Không dùng AI để tạo danh sách ban đầu; tự scan từ công việc monitoring rồi dùng worksheet để kiểm tra actor, workflow và dấu hiệu thật.
- Ý dùng được: Giữ lại 5 problem có bối cảnh công việc cụ thể; ưu tiên các problem có số phút/lần hoặc số lần/ngày/tuần.
- Ý bỏ vì không phải pain thật: Không thêm các ý tưởng chung chung kiểu “xây trợ lý AI giám sát toàn bộ hệ thống” vì chưa có workflow và bằng chứng tương ứng.

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | #5 — Thông tin báo lỗi gửi developer chưa đầy đủ | Pain từ stakeholder rõ; mỗi lỗi phát sinh 2–3 lượt hỏi lại và mất thêm 10–20 phút; workflow có thể cải thiện bằng form bắt buộc + AI kiểm tra thiếu trường. | Chưa có số lỗi/tuần và chưa biết bộ trường tối thiểu được developer thống nhất là gì. |
| 2 | #2 — Kiểm tra trạng thái hệ thống và log để phát hiện bất thường | Lặp lại 3–5 lần/ngày, tốn tổng 30–60 phút/ngày; bottleneck là đọc và đối chiếu thủ công; có thể so sánh Rule cảnh báo với Workflow có AI hỗ trợ tóm tắt. | Chưa có baseline về số cảnh báo đúng/sai, thời gian phát hiện và tỷ lệ bỏ sót. |
| 3 | #1 — Tổng hợp daily note về tiến độ, vấn đề và action item | Có tần suất 5 lần/tuần và thời gian 15–20 phút/lần; workflow báo cáo rõ; AI có thể hỗ trợ cấu trúc/tóm tắt nhưng vẫn cần member kiểm tra. | Chưa đo riêng thời gian thu thập thông tin so với thời gian viết; chưa biết daily note hiện được gửi qua kênh nào. |

> #3 — Weekly progress report được giữ lại như candidate dự phòng nhưng chưa vào top 3 vì mô tả hiện tại chưa có baseline thời gian và có khả năng trùng với phần tổng hợp daily note. Cần đo thêm trước khi chọn.

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Bug report thiếu thông tin khi handoff

```text
Problem 1 câu: Khi team monitor báo lỗi cho developer, report ban đầu thường thiếu log, thời điểm, thiết bị hoặc điều kiện xảy ra nên developer phải hỏi lại trước khi điều tra.

Actor: Member đội monitor (người phát hiện và báo lỗi), developer/software và hardware (người tiếp nhận điều tra).

Thời điểm / bối cảnh: Khi phát hiện một lỗi hoặc bất thường cần chuyển cho developer/software/hardware.

Current workflow 3-7 bước:
1. Member monitor phát hiện lỗi trong khi theo dõi hệ thống.
2. Member ghi nhận và gửi mô tả ban đầu cho developer.
3. Developer kiểm tra report và phát hiện thiếu thông tin cần thiết.
4. Developer hỏi lại 2–3 lượt về log, thời điểm, thiết bị hoặc điều kiện xảy ra lỗi.
5. Member bổ sung thông tin; developer mới bắt đầu điều tra.

Bottleneck: Bước kiểm tra độ đầy đủ của report và hỏi lại thông tin sau handoff; mỗi lỗi mất thêm khoảng 10–20 phút.

Impact: Developer bị gián đoạn và thời gian từ lúc phát hiện đến lúc bắt đầu điều tra kéo dài. Member monitor cũng phải quay lại tìm dữ liệu cũ; chất lượng handoff phụ thuộc vào người lập report.

Success metric: Trong pilot, giảm số lượt hỏi lại từ 2–3 xuống tối đa 1 lượt/lỗi; giảm thời gian bổ sung thông tin từ 10–20 phút xuống dưới 5 phút/lỗi; đạt đủ 100% trường bắt buộc trước khi gửi. Các target này cần đo lại trên log lỗi thật.

Non-AI alternative: Dùng bug-report template/form có trường bắt buộc: timestamp, thiết bị, log, điều kiện xảy ra, bước tái hiện và mức độ ảnh hưởng; dùng checklist trước khi gửi.

AI hypothesis: AI đọc mô tả tự do, trích xuất các trường đã có, đánh dấu trường còn thiếu và tạo tối đa 3 câu hỏi bổ sung. AI không tự chẩn đoán nguyên nhân hoặc tự đóng/mở ticket.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 10–20 phút bổ sung/lỗi

[1 Phát hiện lỗi] → [2 Gửi report thiếu trường] → [3 Developer hỏi lại 2–3 lượt]  <-- bottleneck
→ [4 Bổ sung log/thông tin] → [5 Developer bắt đầu điều tra]

FUTURE STATE — mục tiêu dưới 5 phút bổ sung/lỗi

[1 Form/checklist bắt buộc] → [2 AI kiểm tra và hỏi trường thiếu] → [3 Monitor review + gửi]  <-- human boundary
→ [4 Developer nhận report đủ trường]

Fallback: nếu AI không đọc được log hoặc không chắc trường nào thiếu thì không tự điền; chuyển về form/checklist thủ công và để developer/monitor xác nhận.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Phát hiện bất thường từ trạng thái hệ thống và log

```text
Problem 1 câu: Mỗi ngày member đội monitor phải nhiều lần đọc trạng thái hệ thống và log để phát hiện bất thường rồi tổng hợp thông tin lỗi gửi software/hardware, khiến việc kiểm tra thủ công tốn 30–60 phút/ngày.

Actor: Member đội monitor (người theo dõi và phát hiện bất thường), đội software và hardware (người nhận thông tin để điều tra).

Thời điểm / bối cảnh: Trong ca trực, khoảng 3–5 lần/ngày hoặc khi có tín hiệu bất thường.

Current workflow 3-7 bước:
1. Member mở trạng thái hệ thống và các nguồn log liên quan.
2. Đọc, đối chiếu timestamp/trạng thái và tìm tín hiệu bất thường.
3. Ghi nhận dấu hiệu, log và điều kiện quan sát được.
4. Tổng hợp thông tin rồi gửi cho đội software/hardware.
5. Đội phụ trách tiếp nhận và điều tra nguyên nhân.

Bottleneck: Đọc và đối chiếu thủ công nhiều dòng log ở mỗi lượt kiểm tra; tổng effort hiện được ước lượng 30–60 phút/ngày.

Impact: Tốn thời gian trực monitor, có nguy cơ bỏ sót hoặc báo trễ bất thường; software/hardware nhận thông tin không đồng nhất nếu mỗi người tổng hợp một cách khác nhau.

Success metric: Pilot giảm thời gian kiểm tra/tổng hợp từ 30–60 phút xuống dưới 20 phút/ngày; 100% alert được ghi nhận timestamp và nguồn log; không tăng số cảnh báo sai hoặc bỏ sót so với baseline cần đo trước pilot.

Non-AI alternative: Rule-based alert theo ngưỡng trạng thái/log, dashboard tập trung và checklist xử lý alert. Đây là lớp nên làm trước cho tín hiệu có cấu trúc.

AI hypothesis: Sau khi Rule lọc tín hiệu, AI tóm tắt log liên quan, nhóm các dấu hiệu có cùng timestamp và tạo draft incident note cho monitor kiểm tra. AI không kết luận root cause và không tự thay đổi trạng thái hệ thống.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 30–60 phút/ngày

[1 Mở trạng thái/log] → [2 Đọc và đối chiếu] → [3 Ghi nhận bất thường]  <-- bottleneck
→ [4 Tổng hợp] → [5 Gửi software/hardware]

FUTURE STATE — mục tiêu dưới 20 phút/ngày

[1 Rule lọc alert] → [2 AI nhóm/tóm tắt log] → [3 Monitor review]  <-- human boundary
→ [4 Gửi incident note chuẩn hóa]

Fallback: nếu alert không đủ dữ liệu, log mâu thuẫn hoặc AI confidence thấp thì giữ alert ở hàng đợi Human Review; monitor quay về dashboard và checklist thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tổng hợp daily note cho software/hardware

```text
Problem 1 câu: Mỗi ngày member phải tổng hợp tiến độ, vấn đề phát sinh và action item thành daily note để gửi cho team software/hardware, mất khoảng 15–20 phút/lần và lặp lại 5 lần/tuần.

Actor: Member monitor (người soạn note), PM và member đội software/hardware (người đọc, bổ sung hoặc xử lý action item).

Thời điểm / bối cảnh: Cuối ngày hoặc thời điểm cần gửi cập nhật trong tuần làm việc.

Current workflow 3-7 bước:
1. Member rà lại tiến độ và các vấn đề đã theo dõi trong ngày.
2. Thu thập action item/cập nhật liên quan từ team software và hardware.
3. Chọn thông tin cần đưa vào daily note.
4. Viết, format và gửi note cho các team liên quan.
5. Người nhận đọc và phản hồi nếu còn thiếu thông tin.

Bottleneck: Gom thông tin rải rác và viết lại thành note ngắn, rõ; công việc mất khoảng 15–20 phút/lần.

Impact: 5 lần/tuần tương đương khoảng 75–100 phút/tuần cho một member; note thiếu hoặc không đồng nhất có thể làm PM/dev phải hỏi lại tiến độ và action item.

Success metric: Giảm thời gian soạn từ 15–20 phút xuống dưới 7 phút/lần; note có đủ các trường tiến độ, issue, owner và action item trong ít nhất 95% lần gửi; không tăng số lượt hỏi lại của người nhận. Target cần kiểm chứng bằng bấm giờ và review note.

Non-AI alternative: Dùng template daily note cố định, checklist trường bắt buộc và một bảng chung cho tiến độ/issue/action item.

AI hypothesis: AI nhận các cập nhật đã được cung cấp, sắp xếp theo template, tóm tắt issue và nhắc trường còn thiếu. Member monitor phải review nội dung và gửi; AI không tự gán owner hoặc tự cam kết deadline nếu input không có.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 15–20 phút/lần, 5 lần/tuần

[1 Rà tiến độ] → [2 Gom update] → [3 Chọn nội dung]  <-- bottleneck
→ [4 Viết/format note] → [5 Gửi và chờ phản hồi]

FUTURE STATE — mục tiêu dưới 7 phút/lần

[1 Template + input chuẩn] → [2 AI sắp xếp/tóm tắt] → [3 Member review]  <-- human boundary
→ [4 Gửi daily note]

Fallback: nếu input thiếu context hoặc AI tóm tắt sai, member bỏ draft AI và dùng template/checklist để viết thủ công; không gửi bản chưa review.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Bug report thiếu thông tin khi handoff
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Tôi chọn card này vì actor và điểm nghẽn rõ: developer phải hỏi lại 2–3 lượt sau khi nhận report. Tác động có thể đo bằng số lượt hỏi lại và thời gian bổ sung 10–20 phút/lỗi. Bài toán cũng có phương án không dùng AI là form/checklist bắt buộc; AI chỉ nên hỗ trợ kiểm tra thiếu trường trong workflow.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Bộ trường tối thiểu nào là bắt buộc để developer có thể bắt đầu điều tra mà không hỏi lại?
2. Số liệu 2–3 lượt hỏi lại và 10–20 phút/lỗi được đo trên bao nhiêu lỗi; có khác nhau giữa lỗi software và hardware không?
3. Khi AI trích xuất sai log hoặc timestamp, ai sẽ xác nhận và fallback về form thủ công như thế nào?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Chưa có số lỗi/tuần, chưa chốt bộ trường bắt buộc và dễ nhảy sang “AI tự chẩn đoán” nếu không đặt boundary.
- Tôi sửa gì: Giữ scope ở kiểm tra độ đầy đủ và hỏi trường còn thiếu; thêm form/checklist làm phương án non-AI; ghi rõ các target là giả định cần kiểm chứng.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
