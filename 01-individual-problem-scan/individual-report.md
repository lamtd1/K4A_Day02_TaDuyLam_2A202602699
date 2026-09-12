# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Tạ Duy Lâm
- Mã học viên: 2A202602699
- Vai trò / bối cảnh: intern tại công ty startup (quy mô khoảng 50 người), làm việc với team phát triển sản phẩm AI nội bộ, hỗ trợ các team khác trong công ty tích hợp AI vào workflow.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    - Thực hiện weekly standup với các anh chị trong team và báo cáo tiến độ công việc
    - Thực hiện các task được giao, research và analyze data
    - Thực hiện research kiến thức mới về AI, data và các công cụ mới mà công ty sẽ tích hợp vào workflow
    - Thực hiện build và maintain các ứng dụng AI (đã có CI/CD tự động build/deploy)
    - Trả lời và giải quyết các vấn đề phát sinh liên quan đến việc ứng dụng workflow AI team mình phát triển của các team khác
    - Họp và báo cáo tiến độ công việc cùng các mentor với cấp trên

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Pain từ người khác + Lặp lại | Khi team khác gặp lỗi/thắc mắc về AI workflow đã triển khai, xử lý theo kiểu FIFO: nghe/đọc mô tả, lao vào sửa ngay, không phân loại mức độ ưu tiên, không lưu lại log | Tạ Duy Lâm (bị gián đoạn liên tục) + team khác (chờ fix) | Gần như ngày nào cũng có ít nhất 1 lượt hỏi/báo lỗi (vì sản phẩm chưa hoàn thiện); thời gian xử lý 1 lỗi dao động 30 phút – 2 ngày tùy độ khó, không có SLA |
| 2 | Tốn thời gian | Research kiến thức mới về AI/data/tool không được lưu lại có cấu trúc, nên khi cần dùng lại phải research lại gần như từ đầu | Tạ Duy Lâm | Mất 3–7 ngày để tìm/dựng lại kiến thức đã từng research trước đó (nhanh nhất 3 ngày, chậm thì cả tuần) |
| 3 | Lặp lại + AI có thể tốt hơn | CI/CD đã tự động build/deploy và có security scan (Semgrep, Trivy, npm audit, pip-audit, Bandit), nhưng khi scan fail chỉ báo lỗi rồi dừng — chưa có bước tự fix. Phải tự đọc log, copy lỗi, paste sang agent riêng để hỏi cách sửa, rồi tự áp fix và push lại | Tạ Duy Lâm | Có push lên tới 13 lỗi cần xử lý cùng lúc, trung bình ~30 lỗi/tuần phải xử lý thủ công qua vòng lặp đọc log → copy → paste → fix → push; đáng chú ý có lúc sau khi agent sửa xong, số lỗi lại **tăng thêm** thay vì giảm (agent fix không ổn định) |
| 4 | Tốn thời gian | 1 buổi họp/tuần báo cáo tiến độ cùng cấp trên nhưng bản thân tự đánh giá là "đi cho có", không thấy giá trị/quyết định rõ ràng rút ra sau buổi họp | Tạ Duy Lâm | 1 buổi cố định/tuần, kéo dài 1.5–2 tiếng/buổi, có khi lâu hơn nếu nhiều vấn đề phát sinh |
| 5 | Lặp lại + Tốn thời gian | Mỗi task research/analyze data mới đều phải viết lại script load + clean data từ đầu, vì mỗi nguồn (DB nội bộ, file Excel team gửi, API) có format riêng, chưa có connector/pipeline dùng chung | Tạ Duy Lâm | *(cần bổ sung: bao nhiêu task/tuần cần viết lại từ đầu, mất bao lâu mỗi lần)* |
| 6 | AI có thể tốt hơn | Khi app AI đang chạy gặp lỗi/production incident, phải tự đọc log rải rác ở nhiều service/nơi khác nhau để tìm nguyên nhân, chưa có nơi tổng hợp log hay alert tự phân loại theo mức độ | Tạ Duy Lâm | *(cần bổ sung: bao nhiêu lần/tháng gặp incident phải lần log thủ công, trung bình mất bao lâu để tìm ra nguyên nhân)* |
| 7 | Pain từ người khác | Trước mỗi buổi standup hằng tuần, phải tự nhớ lại và tổng hợp việc đã làm từ nhiều nguồn rời rạc (task tracker, Slack, code commit) vì không ghi chú theo ngày | Tạ Duy Lâm | *(cần bổ sung: mất bao nhiêu phút để chuẩn bị mỗi tuần)* |
| 8 | Lặp lại | Mỗi lần cần đánh giá 1 tool AI mới để xem có tích hợp được vào hệ thống công ty không, phải tự cài đặt/test (POC) thủ công từng tool, chưa có checklist đánh giá chuẩn (chi phí, bảo mật, khả năng tích hợp) | Tạ Duy Lâm | *(cần bổ sung: bao nhiêu tool/tháng phải POC thủ công kiểu này, mỗi lần mất bao lâu)* |
| 9 | Pain từ người khác + Tốn thời gian | Tài liệu hướng dẫn cho các AI workflow đã bàn giao cho team khác dùng bị viết thủ công và không cập nhật kịp mỗi khi feature thay đổi, khiến team khác hỏi lại những câu lẽ ra doc đã trả lời được (liên hệ trực tiếp tới vấn đề #1) | Tạ Duy Lâm + các team khác | *(cần bổ sung: bao nhiêu % câu hỏi ở vấn đề #1 là do doc lỗi thời, so với lỗi thật sự)* |
| 10 | Lặp lại + Tốn thời gian | Mỗi khi startup muốn tích hợp AI vào 1 quy trình mới của 1 team, phải tự research + làm POC lại từ đầu để xác định "việc này AI làm được không", vì chưa có framework/checklist chung để đánh giá trước khi bắt tay làm | Tạ Duy Lâm | *(cần bổ sung: bao nhiêu POC/tháng bị làm rồi bỏ vì hoá ra task không hợp AI, mất bao lâu mỗi POC)* |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Từ mô tả công việc hằng tuần, brainstorm giúp các problem theo 4 lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác), rồi phản biện xem đã đủ actor + số đo chưa.
- Ý dùng được: (1) xử lý lỗi FIFO không phân loại ưu tiên từ team khác, (2) security scan trong CI/CD chỉ dừng lại chứ chưa tự fix, (3) research không lưu note có cấu trúc — cả 3 đều đúng thực tế và có số đo cụ thể.
- Ý bỏ vì không phải pain thật: ý ban đầu AI đề xuất "mỗi task phải tự build biểu đồ phân tích dữ liệu từ đầu" — thực tế công việc không có bước plot data này, nên loại bỏ khỏi bảng scan.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng (đã có 10), mỗi dòng có actor cụ thể — *riêng dòng #5-10 vẫn thiếu số đo thật, cần tự điền trước khi nộp (mình chỉ brainstorm được mô tả workflow, không thể bịa số)*
- [x] Dùng ít nhất 3/4 lăng kính (đã dùng cả 4: Lặp lại, Tốn thời gian, AI có thể tốt hơn, Pain từ người khác)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian" — mỗi dòng đều gắn với 1 workflow cụ thể

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Security scan trong CI/CD chỉ báo lỗi và dừng, chưa có bước tự fix | Workflow đã có sẵn (dễ vẽ 3-7 bước); bottleneck rõ ràng ở 1 bước (copy-paste thủ công); tần suất cao và đo được (~30 lỗi/tuần, có push tới 13 lỗi) | Agent fix hiện tại không ổn định — có lúc sửa xong lỗi lại tăng thêm; chưa rõ nguyên nhân (agent hiểu sai context, hay fix 1 lỗi lại phát sinh lỗi khác) và có nên giới hạn phạm vi auto-fix hay không |
| 2 | Xử lý lỗi/thắc mắc AI workflow từ team khác theo kiểu FIFO, không phân loại ưu tiên | Actor rõ, tần suất cao (gần như hằng ngày), impact rõ (gián đoạn công việc chính liên tục), có range thời gian đo được (30 phút–2 ngày) | Chưa tách được lỗi nào là lặp lại (có thể phòng trước) và lỗi nào là mới hoàn toàn — cần thêm dữ liệu để biết tỷ lệ |
| 3 | Research kiến thức mới không lưu trữ có cấu trúc, phải research lại từ đầu | Đo được thời gian rõ (3-7 ngày); pain có thật, lặp lại nhiều lần | Chưa chắc đây có phải ưu tiên cao nhất so với 2 vấn đề trên, hay chỉ là inconvenience vì chưa hình thành thói quen ghi chú |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — CI/CD security scan chưa có bước tự fix

```text
Problem 1 câu: Pipeline CI/CD đã tự động build/deploy và có security scan (Semgrep, Trivy, npm audit, pip-audit, Bandit), nhưng khi scan phát hiện lỗi thì chỉ dừng pipeline và báo lỗi — chưa có bước tự sửa, phải copy lỗi thủ công sang agent khác để fix rồi push lại.

Actor: Tạ Duy Lâm

Thời điểm / bối cảnh: Mỗi khi push code và pipeline chạy đến bước security scan, gặp vulnerability/finding.

Current workflow 3-7 bước:
1. Push code → CI/CD chạy security scan (Semgrep/Trivy/npm audit/pip-audit/Bandit)
2. Scan fail → pipeline dừng, chỉ in ra log lỗi
3. Lâm đọc log, xác định vị trí và nguyên nhân lỗi
4. Lâm copy nội dung lỗi, paste thủ công sang một AI agent riêng để hỏi cách fix
5. Lâm áp code fix agent gợi ý, tự review lại
6. Push lại code, pipeline chạy lại từ đầu

Bottleneck: Bước 3-4 — không có cầu nối tự động giữa output của scan và agent fix, toàn bộ khâu đọc log + copy + paste đều làm thủ công.

Impact: Trung bình ~30 lỗi/tuần cần xử lý thủ công (có push lên tới 13 lỗi cùng lúc), mỗi lỗi tốn thêm 1 vòng lặp đọc log → copy → paste → fix → push, làm chậm thời gian merge/deploy và gây gián đoạn giữa các task khác đang làm; đáng lo hơn là có lúc sau khi agent sửa, số lỗi lại **tăng thêm** thay vì giảm — cho thấy bước fix hiện tại (làm thủ công, không có review chuẩn hoá) không ổn định.

Success metric: Số bước thủ công từ lúc scan fail đến lúc code được push lại giảm từ 4 bước (đọc log, copy, paste, review) xuống còn 1 bước (review & approve PR do agent tạo sẵn).

Non-AI alternative: Một số tool có auto-fix suggestion sẵn (vd Dependabot cho dependency bump), nhưng không cover được các finding từ Semgrep/Bandit (lỗi trong code logic).

AI hypothesis: Xây agent tự động lấy output của scan (Semgrep/Trivy/npm audit/pip-audit/Bandit), generate patch tương ứng, mở PR kèm giải thích — Lâm chỉ cần review & approve thay vì tự copy-paste và fix tay.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — biến động theo độ khó lỗi

[1 Push code: 1'] → [2 Scan fail, dừng: 1'] → [3 Đọc log tìm nguyên nhân: __'] → [4 Copy/paste vào agent hỏi fix: __']  <-- bottleneck → [5 Áp fix + review: __'] → [6 Push lại: 1']

FUTURE STATE

[1 Push code: 1'] → [2 Scan fail, agent tự đọc log + generate patch + mở PR: __'] → [3 Lâm review & approve PR: __']  <-- human boundary

Fallback: nếu agent fix sai/không chắc chắn (vd đụng vào business logic) thì agent chỉ comment gợi ý trong PR, không tự apply — Lâm vẫn tự sửa như hiện tại.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Xử lý lỗi/thắc mắc AI workflow từ team khác (FIFO, không phân loại ưu tiên)

```text
Problem 1 câu: Khi team khác gặp lỗi hoặc thắc mắc về AI workflow đã triển khai, mọi yêu cầu được xử lý theo kiểu FIFO — trả lời trực tiếp bằng lời và sửa ngay khi phát hiện, không có bước phân loại mức độ ưu tiên hay ghi nhận lại.

Actor: Tạ Duy Lâm (người trực tiếp xử lý)

Thời điểm / bối cảnh: Gần như hằng ngày, bất cứ lúc nào có team khác báo lỗi qua chat/trực tiếp, xen giữa công việc đang làm dở.

Current workflow 3-7 bước:
1. Team khác phát hiện lỗi/thắc mắc → nhắn/gọi trực tiếp
2. Lâm dừng việc đang làm để nghe/đọc mô tả
3. Lâm tự đánh giá mức độ nghiêm trọng bằng cảm tính (không có tiêu chí rõ)
4. Lâm vào code/log tìm nguyên nhân
5. Lâm sửa và deploy lại
6. Lâm báo lại kết quả bằng lời (không lưu log)

Bottleneck: Bước 2-3 — không có hàng đợi/phân loại ưu tiên, mọi việc bị gián đoạn ngay lập tức theo thứ tự đến trước, không theo mức độ nghiêm trọng.

Impact: Công việc chính (research, build) bị ngắt quãng gần như mỗi ngày; thời gian xử lý 1 lỗi dao động 30 phút – 2 ngày, không dự đoán được, không track lại được lỗi nào đã từng gặp.

Success metric: Giảm số lần gián đoạn giữa giờ làm việc chính; có thời gian xử lý trung bình theo mức ưu tiên rõ ràng thay vì FIFO ngẫu nhiên; có log để biết lỗi nào lặp lại.

Non-AI alternative: Lập kênh ticket (vd 1 form/board đơn giản) + bảng phân loại mức độ ưu tiên thủ công (severity levels), quy định khung giờ xử lý support thay vì xử lý ngay lập tức.

AI hypothesis: Dùng agent tiếp nhận báo lỗi đầu tiên (qua form/chatbot), tự phân loại mức độ nghiêm trọng dựa trên mô tả + log đính kèm, tra cứu xem lỗi có từng gặp chưa (dựa trên lịch sử), rồi mới route tới Lâm theo đúng độ ưu tiên.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 30 phút đến 2 ngày/lỗi

[1 Team khác báo lỗi trực tiếp] → [2 Lâm dừng việc đang làm] → [3 Đánh giá mức độ bằng cảm tính]  <-- bottleneck → [4 Tìm nguyên nhân + sửa]

FUTURE STATE

[1 Báo lỗi qua form/kênh chung] → [2 Agent phân loại mức độ + check lỗi cũ] → [3 Lâm xử lý theo hàng đợi ưu tiên: review]  <-- human boundary

Fallback: nếu agent phân loại sai mức độ ưu tiên hoặc không nhận diện được lỗi, mặc định đẩy về mức "cần Lâm xem trực tiếp" như hiện tại.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Research kiến thức mới không lưu trữ có cấu trúc

```text
Problem 1 câu: Khi research kiến thức mới về AI/data/tool, thông tin không được lưu lại có cấu trúc, nên khi cần dùng lại phải research lại gần như từ đầu.

Actor: Tạ Duy Lâm

Thời điểm / bối cảnh: Xảy ra khi nhận task mới cần áp dụng lại kiến thức đã từng research trước đây.

Current workflow 3-7 bước:
1. Nhận task cần kiến thức đã từng research trước đây
2. Nhớ mang máng đã đọc ở đâu đó nhưng không tìm lại được note cũ
3. Research lại gần như từ đầu (search, đọc docs/paper lại)
4. Tổng hợp lại hiểu biết (vẫn không lưu lại có cấu trúc)
5. Áp dụng vào task

Bottleneck: Bước 2-3 — không có hệ thống lưu trữ/tra cứu lại, nên phải research lại toàn bộ thay vì tra cứu trong vài phút.

Impact: Mất 3–7 ngày để tìm/dựng lại kiến thức đã từng biết, làm chậm tiến độ của task liên quan.

Success metric: Thời gian tra cứu lại kiến thức cũ giảm từ 3-7 ngày xuống còn vài phút đến vài giờ.

Non-AI alternative: Tự lập note bằng tay (Notion/Obsidian) có tag/cấu trúc rõ ràng ngay sau mỗi lần research.

AI hypothesis: Dùng AI tự động tóm tắt + gắn tag nội dung research ngay sau khi đọc, xây knowledge base có thể search semantic (hỏi bằng ngôn ngữ tự nhiên thay vì nhớ chính xác từ khóa/tên file).

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 3-7 ngày/lần cần dùng lại

[1 Nhận task cần kiến thức cũ] → [2 Không tìm được note cũ] → [3 Research lại từ đầu: 3-7 ngày]  <-- bottleneck

FUTURE STATE

[1 Nhận task cần kiến thức cũ] → [2 Search trong knowledge base có tag/tóm tắt AI] → [3 Đọc lại tóm tắt, review nhanh: vài giờ]  <-- human boundary

Fallback: nếu không tìm thấy trong knowledge base (research thật sự mới), quay lại quy trình research từ đầu như hiện tại.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — CI/CD security scan chưa có bước tự fix
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Pipeline CI/CD hiện tại tự động build/deploy và chạy security scan (Semgrep, Trivy, npm audit, pip-audit, Bandit), nhưng mỗi lần scan fail đều phải xử lý thủ công qua 4 bước (đọc log, copy, paste vào agent, review) trước khi push lại được. Đây là workflow đã có sẵn, dễ đo (số bước thủ công, thời gian từ lúc fail đến lúc push lại), và có AI hypothesis rất cụ thể: agent tự đọc output scan, generate patch, mở PR — giảm phần việc của Lâm từ 4 bước thủ công xuống còn 1 bước review & approve.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Hiện tại có lúc agent sửa lỗi xong thì số lỗi lại tăng thêm thay vì giảm — nếu để agent tự động mở PR fix mà không có bộ test/guardrail chuẩn, làm sao đảm bảo fix không tạo ra lỗi mới hoặc phá logic hiện tại?
2. Với tần suất ~30 lỗi/tuần (có push tới 13 lỗi), có nên giới hạn phạm vi auto-fix (chỉ dependency bump/config đơn giản, không để agent tự sửa logic phức tạp) để giảm rủi ro, hay nên đầu tư làm guardrail tốt hơn để agent tự fix được cả lỗi phức tạp?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: bản draft ban đầu của Card #1 giả định agent tự fix rồi tạo PR là đủ an toàn, nhưng khi có số liệu thật thì lộ ra vấn đề lớn hơn: agent fix hiện tại không ổn định (đôi khi sửa xong lỗi lại tăng thêm) — nếu không xử lý điểm này, AI hypothesis ban đầu (agent tự mở PR) là rủi ro, không chỉ là "convenience".
- Tôi sửa gì: điều chỉnh Impact và câu hỏi challenge để nêu rõ rủi ro agent fix gây tăng lỗi, và đổi hướng pitch từ "để agent tự động mở PR" sang "cần thêm guardrail/giới hạn phạm vi trước khi tin tưởng agent tự fix hoàn toàn".

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge