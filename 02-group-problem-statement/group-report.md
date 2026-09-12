# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Tạ Duy Lâm | 2A202602699 | |
| 2   | Nguyễn Xuân Khuê | 2A202602999 | |
| 3   | Lê Nguyễn Thái Dương | 2A202602383 | |
| 4   | Nguyễn Văn Quốc Việt | 2A202602973 | |
| 5   | Nguyễn Duy Phong | 2A202602834 | |
| 6   | Nguyễn Phát Thịnh | 2A202602645 | |

**Candidate problem nhóm chọn (1 câu):**

Hỗ trợ bác sĩ chẩn đoán hình ảnh khoanh vùng bất thường trên ảnh MRI (não) nhanh và nhất quán hơn so với đọc phim hoàn toàn thủ công, trong khi bác sĩ vẫn là người quyết định chẩn đoán cuối cùng.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Lâm | Viết báo cáo/bài tập bằng tiếng Nhật mất ~2 tiếng thay vì 30 phút | Sinh viên (bản thân) | Vừa nghĩ nội dung vừa dịch thuật ngữ chính xác | Đo được rõ, nhưng khó so sánh Rule/Workflow/Agent vì bản chất chỉ là dịch thuật |
| 2 | Khuê | Note đồ án viết tay khi thầy giảng nhanh (4-5 buổi/tuần), ảnh hưởng chất lượng | Sinh viên (bản thân) | Tốc độ ghi tay không theo kịp tốc độ giảng | Pattern trùng với #6 (tóm tắt slide/recording) |
| 3 | Khuê | Vẽ diagram thủ công không đẹp + viết báo cáo BTL, 12 tiếng/tuần, nhiều lỗi ảnh/câu cú | Sinh viên (bản thân) | Trải dài nhiều bước (vẽ + viết + sửa), không rõ 1 điểm nghẽn | Khó làm nổi trong 1 buổi lab vì cần nhiều thành phần cùng lúc |
| 4 | Dương | Tổng hợp báo cáo BTL nhóm (11-12 BTL/3-4 tháng, 2-3 BTL song song), 4-15 tiếng/lần | Người tổng hợp trong nhóm | Ghép nối phần của từng người, format không đồng nhất | Cần dữ liệu mẫu thật từ nhiều người mới demo được trong lab |
| 5 | Dương | Báo cáo tiến độ hàng tuần với thầy, lặp lại cấu trúc nhưng vẫn soạn lại từ đầu, 3 tiếng | Sinh viên (bản thân) | Không có template/nguồn ghi log sẵn để tự điền | Lặp lại cao nhưng quy mô nhỏ, ít ấn tượng để làm case chính |
| 6 | Dương | Tóm tắt lại slide + recording sau buổi học, tốn thời gian, nghe khó | Sinh viên (bản thân) | Nghe lại recording chất lượng kém + đối chiếu slide thủ công | Pattern trùng #2, gộp thành 1 candidate mạnh |
| 7 | **Việt** | **Hỗ trợ khoanh vùng/chẩn đoán trên ảnh MRI** | **Bác sĩ chẩn đoán hình ảnh (radiologist)** | **Khoanh vùng nghi ngờ bằng mắt, thủ công, phụ thuộc kinh nghiệm** | **→ Candidate nhóm chọn (xem lý do ở 3.3-3.4)** |
| 8 | Việt | Số hoá bệnh án, tóm tắt, note lại thông tin bệnh nhân | Nhân viên y tế (giả định) | Chưa xác định | Cùng cụm domain y tế với #7, #9 — có thể làm hướng mở rộng sau |
| 9 | Việt | Bệnh nhân tái khám phải lật lại thông tin cũ, tốn thời gian | Bác sĩ/bệnh nhân (giả định) | Chưa xác định | Cùng cụm domain y tế với #7, #8 — liên quan trực tiếp đến bước 4 trong workflow của #7 |
| 10 | Phong | Cây trồng ở nhà héo/chết vì không giám sát được khi đi học | Bản thân (chủ nhà trồng cây) | Không phát hiện sớm tình trạng đất/cây | Cần phần cứng sensor + dữ liệu ảnh, khó demo trong 1 buổi lab |
| 11 | Thịnh | Tổng hợp tin tức từ nhiều kênh để nắm hết trong ngày, 11.5 tiếng/tuần, cần viết báo cáo tóm tắt trích nguồn giống định dạng chung | Bản thân (bản thân) | Đọc trùng lặp nhiều nguồn, không có bản tóm tắt + trích dẫn sẵn | Đo được rõ, dễ demo, nhưng cần nguồn tin ổn định trong lúc lab |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A | #2 Note đồ án viết tay (Khuê), #6 Tóm tắt slide/recording (Dương) | Bắt thông tin từ nguồn audio/live rồi tóm tắt lại thành note có cấu trúc | Điểm số cao nhất ở vòng chấm trước (33/35) — vẫn là phương án an toàn nếu cụm D gặp rủi ro |
| B | #3 Diagram + báo cáo BTL (Khuê), #5 Báo cáo hàng tuần với thầy (Dương) | Soạn thảo tài liệu định kỳ, tốn thời gian trình bày hơn nội dung | Bottleneck trải dài nhiều bước, khó gói gọn trong 1 buổi lab |
| C | #4 Tổng hợp BTL nhóm (Dương), #11 Tổng hợp tin tức (Thịnh) | Hợp nhất input rời rạc từ nhiều nguồn/nhiều người thành 1 output thống nhất | #11 khả thi hơn #4 vì không phụ thuộc phải có dữ liệu thật từ người khác nộp đúng hạn |
| D | #7 Khoanh vùng MRI, #8 số hoá bệnh án, #9 bệnh nhân tái khám (đều của Việt) | Hỗ trợ quy trình chẩn đoán/hồ sơ y tế bằng AI | **Nhóm chọn #7 làm candidate chính**; #8, #9 giữ làm hướng mở rộng tiềm năng (đặc biệt #9 liên quan trực tiếp đến bước "đối chiếu hồ sơ cũ" trong workflow của #7) |
| *(đứng riêng)* | #1 Tiếng Nhật (Khuê), #10 Sensor cây trồng (Phong) | — | Tiếng Nhật: ít so sánh được R/W/A. Sensor cây: cần phần cứng, không làm nổi trong lab |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **#7 (Việt) — Khoanh vùng MRI** | Bài toán có giá trị thực tế cao, actor (bác sĩ chẩn đoán hình ảnh) tồn tại rõ trong thực tế dù nhóm chưa phỏng vấn được; có sẵn dataset công khai (BraTS) và model pretrained (MONAI/nnU-Net) để demo kỹ thuật trong lab mà không cần dữ liệu bệnh viện thật | **Rủi ro lớn nhất của cả nhóm**: chưa có actor thật xác nhận, chưa có số liệu baseline thật (thời gian đọc phim, tần suất bỏ sót) — toàn bộ Problem Statement ở Phase 5 hiện dựa trên tài liệu tham khảo + suy luận, không phải quan sát/phỏng vấn trực tiếp |
| Cụm A — Ghi chép + tóm tắt bài giảng (Khuê + Dương) | Actor rõ, workflow 4 bước rõ, dễ demo trong lab, điểm số khách quan cao nhất (33/35) | Không phải rủi ro chọn candidate này — đây là phương án dự phòng nếu candidate MRI không validate được |
| Cụm C (#11, Thịnh) — Tổng hợp tin tức nhiều kênh | Impact đo được rất rõ (11.5 tiếng/tuần), actor rõ, nhóm hiểu domain | Cần nguồn tin ổn định (API/RSS) để demo trong lab |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Khoanh vùng MRI (Việt)** | 3 | 4 | 2 | 2 | 3 | 4 | 2 | **20** |
| Ghi chép + tóm tắt bài giảng | 5 | 5 | 4 | 4 | 5 | 5 | 5 | 33 |
| Tổng hợp tin tức nhiều kênh | 5 | 4 | 4 | 5 | 4 | 4 | 5 | 31 |

> **Flag trung thực (ép nói rõ theo đúng tinh thần worksheet):** candidate MRI chấm **thấp hơn hẳn** 2 candidate còn lại (20 so với 33 và 31), chủ yếu vì "Pain có evidence" (2đ — chưa ai trong nhóm là actor thật hoặc phỏng vấn được actor), "Impact đo được" (2đ — chưa có baseline số liệu thật, chỉ có số liệu tham khảo từ research y khoa) và "Nhóm hiểu domain" (2đ — không ai trong nhóm học y). Đây không phải lỗi tính điểm — nhóm chọn candidate này *dù biết điểm thấp hơn*, nên cần ghi rõ lý do chấp nhận rủi ro ở mục dưới, và bắt buộc phải làm Phase 4 (validate) nghiêm túc trước khi build.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Hỗ trợ bác sĩ chẩn đoán hình ảnh khoanh vùng bất thường trên ảnh MRI (não), giảm phần khoanh vùng thủ công tốn thời gian và phụ thuộc kinh nghiệm cá nhân, trong khi bác sĩ vẫn luôn là người review và quyết định chẩn đoán cuối cùng.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn candidate này dù điểm chấm khách quan thấp hơn 2 candidate còn lại, vì đây là bài toán có impact xã hội lớn nhất trong số các candidate (ảnh hưởng trực tiếp đến tốc độ và chất lượng chẩn đoán y tế) và có nền tảng kỹ thuật khả thi thật: có sẵn dataset công khai (BraTS) và model pretrained (MONAI/nnU-Net) để làm PoC mà không cần dữ liệu bệnh viện thật. Bài toán cũng cho phép so sánh rõ Rule/Workflow/Agent (điểm 4/5) vì có nhiều mức độ xử lý ảnh khác nhau (threshold cổ điển → pipeline model cố định → agent tự chọn model/giải thích). Nhóm ý thức rõ đây là candidate rủi ro cao hơn 2 candidate kia và cam kết dùng Phase 4 để bù đắp phần thiếu evidence trước khi đi tiếp — nếu không validate được, sẽ rollback về candidate "ghi chép + tóm tắt bài giảng" (xem Exit/rollback ở Phase 6.3).
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
Ghi chép + tóm tắt bài giảng (Khuê + Dương, 33 điểm): là candidate điểm cao nhất và an toàn nhất, nhưng nhóm đánh giá quy mô impact nhỏ hơn (chỉ ảnh hưởng việc học của chính nhóm) so với bài toán y tế. Giữ lại làm phương án dự phòng.

Tổng hợp tin tức nhiều kênh (Thịnh, 31 điểm): impact đo được tốt nhưng phụ thuộc nguồn tin ổn định để demo, và ít mang tính "công nghệ mới" hơn so với bài toán segmentation ảnh y tế mà nhóm muốn thử sức.

Y tế khác (#8 số hoá bệnh án, #9 tái khám) và sensor cây trồng (#10): không đủ điều kiện làm nổi trong 1 buổi lab (thiếu actor thật hoặc thiếu phần cứng) nên bị loại từ vòng shortlist (mục 3.3).
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Bảng chấm điểm 3.4 tự nó là 1 dạng "disagreement" giữa tiêu chí khách quan và lựa chọn thực tế của nhóm: điểm số nói candidate MRI yếu hơn hẳn 2 candidate kia, nhưng nhóm (theo đề xuất của Việt) vẫn chọn vì impact và hứng thú kỹ thuật. Nhóm thống nhất: chấp nhận rủi ro này có điều kiện — nếu Phase 4 validate không ra được ít nhất 1 nguồn evidence đáng tin (dù là dataset public thay vì phỏng vấn thật), nhóm sẽ quay lại candidate "ghi chép + tóm tắt bài giảng". Các thành viên còn lại (Khuê, Dương, Phong, Thịnh) cần xác nhận lại đồng thuận này khi họp nhóm thật.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | *(chưa thực hiện)* | *(cần 1 bác sĩ chẩn đoán hình ảnh hoặc sinh viên y khoa/điều dưỡng — nhóm chưa có kênh tiếp cận)* | | |
| Survey / poll | *(chưa thực hiện)* | | | |
| Log / ticket / review (nếu có) | *(không áp dụng — nhóm không có quyền truy cập hệ thống PACS/bệnh án thật)* | | | |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Cập nhật sau khi bổ sung research định lượng (xem 4.2 mở rộng): nhóm VẪN CHƯA phỏng vấn/khảo sát được actor thật (bác sĩ chẩn đoán hình ảnh) — đây vẫn là giới hạn thật của bản nộp này. Tuy nhiên, nhóm đã tìm được bằng chứng thứ cấp định lượng đủ mạnh để tạm ước tính baseline: (1) khoanh vùng pixel-level thủ công tốn 3-5 giờ/ca trong bối cảnh nghiên cứu (PMC9107172); (2) khi có AI hỗ trợ, thời gian contouring giảm 87-100% và thời gian viết báo cáo giảm 11-40% trong 1 nghiên cứu paired trước/sau (PubMed 42512069); (3) Việt Nam đang thiếu hụt radiologist, bác sĩ phải làm việc như "generalist" do thiếu nhân sự chuyên sâu (KJR 2023, PMC10613840) — củng cố trực tiếp giả định "quá tải". Những số liệu này là proxy thay thế tạm thời, KHÔNG thay được 1 phỏng vấn thật với actor tại đúng bối cảnh Việt Nam nhóm nhắm tới.
```

Bằng chứng đính kèm: research thứ cấp có trích dẫn ở bảng 4.2 mở rộng bên dưới (link kiểm được). Vẫn cần `02-group-problem-statement-interview-notes.md` sau khi phỏng vấn thật — quote nguyên văn từ 1 actor thật vẫn là mục còn thiếu duy nhất của Phase 4.

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Cortechs.ai — NeuroQuant Brain Tumor (đã FDA-clear) | [cortechs.ai](https://www.cortechs.ai/cortechs-ai-announce-next-gen-neuroquant-brain-tumor-ai-driven-metastasis-meningioma-segmentation/) | Tự động khoanh vùng + đo thể tích u não/di căn trên MRI — đúng bước 3 (khoanh vùng) trong workflow hiện tại | Đã được FDA clear, dùng lâm sàng thật, đo thể tích chính xác | Sản phẩm thương mại đóng, nhóm không tiếp cận được mã nguồn/dữ liệu huấn luyện | Xác nhận bài toán này khả thi và đã có tiền lệ lâm sàng — nhóm nên định vị là PoC học thuật, không cạnh tranh sản phẩm y tế thật |
| CorticoMetrics — THINQ (FDA 510(k) clearance) | [biospace.com](https://www.biospace.com/corticometrics-announces-fda-510-k-clearance-of-thinq-for-mri-brain-volumetric-reporting) | Tự động report thể tích não từ MRI — hỗ trợ cả bước 3 (khoanh vùng) và bước 5 (viết báo cáo) | Cũng đã FDA clear, tập trung vào tự động hoá báo cáo | Thương mại, không công bố chi tiết kỹ thuật | Gợi ý mở rộng future state sang cả bước viết báo cáo, không chỉ khoanh vùng |
| MONAI + nnU-Net — pretrained brain MRI segmentation model | [NVIDIA NGC catalog](https://catalog.ngc.nvidia.com/orgs/nvidia/monaitoolkit/models/monai_brats_mri_segmentation/-) | Model segmentation ảnh MRI não theo chuẩn BraTS — đúng bước 2 (AI khoanh vùng) trong future state nhóm vẽ | Mã nguồn mở, có pretrained model tải về dùng thử ngay, cộng đồng lớn (MONAI là framework y tế phổ biến) | Cần GPU + kiến thức deep learning để chạy/fine-tune; dataset BraTS là u não — có thể không khớp loại bệnh lý nhóm muốn nhắm tới | Đây là điểm bắt đầu kỹ thuật khả thi nhất cho PoC trong buổi lab — dùng pretrained model, không cần tự train từ đầu |
| Nghiên cứu tổng quan tải công việc radiologist | [PubMed — "The Radiologist Workload Increase"](https://pubmed.ncbi.nlm.nih.gov/34718316/) | Không phải tool — là bằng chứng thứ cấp cho thấy khối lượng công việc đọc phim của radiologist đang tăng | Nguồn học thuật, có thể trích dẫn được | Không có số liệu riêng cho MRI não hay cho bối cảnh Việt Nam — không dùng để suy ra con số cụ thể | Dùng làm bằng chứng bối cảnh chung (radiologist quá tải), KHÔNG dùng để suy ra số phút/ca cụ thể nếu chưa verify thêm |

**4.2 mở rộng — Research định lượng bổ sung (search 2026-09-12, thay thế tạm cho phỏng vấn thật):**

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Nghiên cứu segmentation thủ công pixel-level cho u não | [PMC9107172 — "An optimal brain tumor segmentation algorithm..."](https://pmc.ncbi.nlm.nih.gov/articles/PMC9107172/) | Định lượng đúng bước 3 (khoanh vùng) trong workflow hiện tại | Cho số liệu cụ thể: bác sĩ/chuyên gia mất **3-5 giờ** để trích đặc trưng thủ công và gán nhãn từng pixel thuộc vùng u trên 1 ca MRI | Đây là số cho segmentation chi tiết mức nghiên cứu (label từng pixel để làm dataset), cao hơn nhiều so với việc bác sĩ lâm sàng khoanh vùng nghi ngờ nhanh hằng ngày | Dùng làm **cận trên (upper bound)** cho "chi phí nếu làm segmentation thủ công đầy đủ", KHÔNG dùng làm số trung bình cho 1 ca đọc phim lâm sàng thông thường |
| AI-Assisted Brain Tumor MRI Reporting and Treatment-Planning Segmentation — nghiên cứu paired trước/sau (2024) | [PubMed 42512069](https://pubmed.ncbi.nlm.nih.gov/42512069/) · [PMC13407102](https://pmc.ncbi.nlm.nih.gov/articles/PMC13407102/) | Đo trực tiếp before/after khi có AI hỗ trợ ở cả bước khoanh vùng (contouring) và viết báo cáo | Thời gian **contouring giảm 87–100%** (vd 54.6→4.9 phút và 184→44 phút ở 2 reader khác nhau); thời gian **viết báo cáo giảm 11–40%** | Nghiên cứu quốc tế, cỡ mẫu nhỏ (2 reader), không phải dữ liệu/bối cảnh Việt Nam | **Bằng chứng định lượng mạnh nhất nhóm tìm được**: impact của AI tập trung chủ yếu ở bước khoanh vùng (đúng bottleneck nhóm xác định ở 5.1), không phải ở bước viết báo cáo — củng cố đúng vị trí "AI intervention point" đã chọn ở Phase 6.2 |
| Độ chính xác MRI thường quy trong phát hiện u não/glioma | [PMC7794124](https://pmc.ncbi.nlm.nih.gov/articles/PMC7794124/) | Cho baseline tỷ lệ bỏ sót/sai — liên quan trực tiếp risk "false negative" đã nêu ở Phase 6.2 | Sensitivity glioma ~89.3%; sensitivity tổng thể u não trên MRI thường quy dao động **72–90.7%**; discrepancy tại Neuro CT/MRI ghi nhận tới ~13% là "major discrepancy" trong review liên quan | Không tách riêng lỗi do khâu "khoanh vùng" và lỗi do "diễn giải/chẩn đoán", số liệu tổng hợp từ nhiều nghiên cứu khác bối cảnh | Cho thấy tỷ lệ bỏ sót không nhỏ (khoảng 10–30% tuỳ tiêu chí) — đúng với giả định "dễ bỏ sót ở ca phức tạp" tại Phase 5.1, dùng làm ngưỡng tham chiếu khi đánh giá false-negative rate của model ở PoC |
| nnU-Net — benchmark BraTS 2020 (hạng 1 competition) | [arXiv 2011.00848](https://arxiv.org/pdf/2011.00848) | Benchmark hiệu năng đúng model nhóm định dùng làm PoC (Phase 4.2 gốc) | Dice score: Whole Tumor **88.95**, Tumor Core **85.06**, Enhancing Tumor **82.03** trên tập BraTS | Benchmark trên glioma (BraTS), có thể không khớp hoàn toàn nếu nhóm đổi loại bệnh lý/dataset khác | Dùng làm **ngưỡng tham chiếu cho Success Metric**: nếu PoC của nhóm đạt Dice gần các mức này trên tập test công khai thì model đủ tin cậy để đề xuất bước pilot tiếp theo |
| Tình trạng thiếu hụt radiologist tại Việt Nam | [KJR 2023 — "The Growing Problem of Radiologist Shortage: Vietnam's Perspectives"](https://pmc.ncbi.nlm.nih.gov/articles/PMC10613840/) | Bằng chứng bối cảnh Việt Nam hoá cho Impact (khác với nguồn PubMed 34718316 chỉ nói chung chung, không phải VN) | Cả nước ~1500-2000 radiologist được đào tạo/năm nhưng vẫn thiếu; bác sĩ phải làm việc như "generalist" vì thiếu nhân sự chuyên sâu; chênh lệch lớn thành thị (HN 10.9, HCM 13.1 bác sĩ/vạn dân) so với nông thôn (<3/vạn dân) | Không có số liệu riêng cho MRI não hay thời gian đọc phim cụ thể tại Việt Nam | Bằng chứng bối cảnh mạnh nhất và **sát nhất với thị trường nhóm nhắm tới** — nên trích dẫn nguồn này thay vì nguồn PubMed cũ khi trình bày Impact |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nên build 1 PoC nhỏ: dùng model pretrained (MONAI/nnU-Net) chạy trên vài ảnh mẫu từ bộ dữ liệu công khai BraTS để demo khoanh vùng + hiển thị confidence score, đúng quy mô 1 buổi lab, và so sánh Dice score đạt được với ngưỡng benchmark ~85-89% của nnU-Net trên BraTS để tự đánh giá PoC có đáng tin không. KHÔNG nên cố gắng thay thế các sản phẩm đã FDA-clear (Cortechs.ai, CorticoMetrics) hay tự thu thập dữ liệu bệnh viện thật trong khuôn khổ môn học — rủi ro pháp lý/đạo đức dữ liệu y tế vượt quá phạm vi bài tập. Research thứ cấp (bảng mở rộng trên) đã đủ mạnh để tạm ước tính baseline/impact, nhưng KHÔNG thay được việc phỏng vấn 1 actor thật tại đúng bối cảnh Việt Nam trước khi coi Problem Statement là "chốt".
```

> Lưu ý: mọi số liệu trên đều lấy từ nguồn có link kiểm được (PubMed/PMC/arXiv), không phải AI tự bịa. Các số liệu là kết quả nghiên cứu quốc tế/khác bối cảnh — khi dùng cho Problem Statement của nhóm phải ghi rõ là ước tính thứ cấp (secondary evidence), không phải số đo thật của nhóm hay của bối cảnh Việt Nam cụ thể.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

![Current state workflow — hỗ trợ đọc/khoanh vùng MRI thủ công](../02-group-problem-statement-workflow-current.png)

Dán workflow hoặc link file: `../02-group-problem-statement-workflow-current.png`

```text
[1 Chụp MRI → lưu PACS: __' - KTV] → [2 Tải ảnh lên workstation: __' - bác sĩ] → [3 Khoanh vùng nghi ngờ thủ công: __' bottleneck] → [4 Đối chiếu hồ sơ cũ: __'] → [5 Viết báo cáo: __'] → [6 Gửi báo cáo: __']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Kỹ thuật viên MRI | Bệnh nhân đến chụp | Ảnh MRI lưu vào PACS | Theo lịch chụp *(cần hỏi thực tế)* | Đầu vào hệ thống |
| 2 | Bác sĩ chẩn đoán hình ảnh | Ảnh trên PACS | Ảnh mở trên workstation, xem nhiều lát cắt | Vài phút *(cần đo thật)* | Handoff từ KTV sang bác sĩ đọc |
| 3 | Bác sĩ chẩn đoán hình ảnh | Ảnh nhiều lát cắt | Vùng nghi ngờ được khoanh (bằng mắt) | *(cần đo thật — biến thiên theo độ phức tạp ca)* | **BOTTLENECK** — phụ thuộc kinh nghiệm cá nhân, dễ bỏ sót |
| 4 | Bác sĩ chẩn đoán hình ảnh | Hồ sơ bệnh án cũ (nếu tái khám) | So sánh tiến triển bệnh | Chỉ phát sinh nếu bệnh nhân tái khám | Liên hệ trực tiếp candidate #9 của Việt (bệnh nhân tái khám) |
| 5 | Bác sĩ chẩn đoán hình ảnh | Kết quả khoanh vùng + đối chiếu | Báo cáo chẩn đoán | *(cần đo thật)* | Viết tay/gõ thủ công |
| 6 | Bác sĩ chẩn đoán hình ảnh | Báo cáo chẩn đoán | Gửi cho bác sĩ điều trị | Ngay sau khi hoàn tất | Handoff sang bác sĩ điều trị |

**Bottleneck chính (2-3 câu):**

```text
Bước 3 (khoanh vùng nghi ngờ thủ công) là bottleneck: thời gian biến thiên mạnh theo độ phức tạp ca bệnh, phụ thuộc hoàn toàn vào kinh nghiệm cá nhân của bác sĩ, và dễ bỏ sót vùng bất thường nhỏ ở ca có nhiều lát cắt. Đây cũng là bước duy nhất nhóm chưa có số đo thật — cần phỏng vấn bác sĩ để lấy con số cụ thể trước khi chốt Problem Statement v1.
```

### 5.2. Future workflow bản nhóm

![Future state workflow — AI hỗ trợ khoanh vùng, bác sĩ review trước khi chốt](../02-group-problem-statement-workflow-future.png)

```text
[1 Ảnh MRI vào hệ thống: __' - máy/rule] → [2 AI khoanh vùng + confidence score: __' - model] → [3 Bác sĩ review & chỉnh sửa: __' - boundary] → [4 Viết báo cáo, gửi: __']

Fallback: nếu AI confidence thấp hoặc bác sĩ không đồng ý → quay lại đọc thủ công hoàn toàn (current state)
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | *(cần đo thật nội bộ — chưa có số của nhóm)* | Literature-based estimate: ở nghiên cứu paired trước/sau gần nhất (PubMed 42512069), thời gian **contouring giảm 87-100%**, thời gian viết báo cáo giảm 11-40% khi có AI hỗ trợ | Bấm giờ bác sĩ đọc 10 ca trước/sau khi dùng AI hỗ trợ (nhóm cần tự đo, số trên chỉ là tham chiếu quốc tế) |
| Số bước | 6 bước | 4 bước | Đếm bước trong quy trình |
| Số bước thủ công | 5/6 bước (trừ bước chụp máy) | 2/4 bước (review + viết báo cáo) | Đếm bước cần người thao tác tay |
| Bottleneck chính | Bước 3 — khoanh vùng thủ công, ước tính cận trên **3-5 giờ/ca** nếu label pixel-level đầy đủ (PMC9107172, xem 4.2 mở rộng) | Bước 3 mới — review AI (vẫn là người, nhưng nhanh hơn vì không khoanh từ đầu) | So sánh thời gian bước 3 cũ vs bước 3 mới |
| Risk mới | Không có risk AI | AI khoanh sai/bỏ sót (false negative) — nguy hiểm hơn cả việc chậm. Baseline tham chiếu: MRI thường quy đã có sensitivity ~72-90.7% và discrepancy ~13% ở Neuro MRI (PMC7794124) — model AI cần được benchmark không tệ hơn ngưỡng này | Theo dõi tỷ lệ bác sĩ phải sửa/bác bỏ kết quả AI trên tập test; so Dice score với benchmark nnU-Net trên BraTS (~85-89%, arXiv 2011.00848) |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Bác sĩ chẩn đoán hình ảnh (radiologist) đọc phim MRI não tại bệnh viện/phòng khám. |
| **Workflow** | Từ lúc nhận ảnh MRI trên PACS đến khi khoanh vùng bất thường thủ công và viết báo cáo chẩn đoán — 6 bước, trải qua cả bước đối chiếu hồ sơ cũ nếu bệnh nhân tái khám. |
| **Bottleneck** | Bước khoanh vùng nghi ngờ thủ công: tốn thời gian biến thiên, phụ thuộc kinh nghiệm cá nhân, dễ bỏ sót ở ca phức tạp nhiều lát cắt. |
| **Impact** | *(chưa đo thật nội bộ)* — literature-based estimate: khoanh vùng pixel-level thủ công có thể tốn tới 3-5 giờ/ca ở mức chi tiết nghiên cứu (PMC9107172); AI hỗ trợ contouring trong 1 nghiên cứu paired giảm 87-100% thời gian (PubMed 42512069). Bối cảnh Việt Nam: radiologist đang thiếu hụt, phải làm việc như "generalist" (KJR 2023). |
| **Success Metric** | Thời gian khoanh vùng/đọc phim giảm; tỷ lệ bỏ sót vùng bất thường giảm so với baseline bác sĩ tự đọc hoàn toàn; benchmark kỹ thuật tham chiếu: Dice score model đạt gần mức nnU-Net trên BraTS (WT 88.95 / TC 85.06 / ET 82.03, arXiv 2011.00848). |
| **Boundary** | AI chỉ đưa ra vùng khoanh gợi ý (draft) kèm confidence score; bác sĩ luôn là người review và quyết định chẩn đoán cuối cùng — AI không tự đưa ra kết luận chẩn đoán. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: **Impact** — hoàn toàn chưa có số liệu thật, chỉ là giả định dựa trên logic + research thứ cấp (Phase 4.2), chưa có baseline đo được.
- Tôi sửa gì: cần nhóm liên hệ tối thiểu 1 bác sĩ/sinh viên y khoa để lấy ước lượng thời gian đọc phim thật, hoặc dùng kết quả benchmark công khai của model trên BraTS làm proxy tạm thời trước khi chốt v1.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: ranh giới vùng bất thường trên MRI không có "đúng tuyệt đối" duy nhất — mức độ nghi ngờ, hình dạng, kích thước đều có thể có nhiều cách đánh giá hợp lý khác nhau tuỳ kinh nghiệm bác sĩ.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: cần tiền xử lý ảnh, chạy model deep learning trên nhiều lát cắt, hậu xử lý mask, rồi mới tới bước người review — nhiều bước phụ thuộc chuỗi nhau.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ mơ hồ CAO + Độ phức tạp CAO
```

**Vì sao (2-3 câu):**

```text
Ảnh MRI có nhiễu, giải phẫu mỗi người khác nhau, vùng bất thường không có ngưỡng pixel cố định để threshold đơn giản phân biệt đúng/sai — đây là lý do độ mơ hồ cao. Đồng thời cần chuỗi nhiều bước phụ thuộc nhau (tiền xử lý → model segmentation đã học sâu → hậu xử lý mask → review) chứ không phải 1-2 bước đơn giản — đây là lý do độ phức tạp cao. Ô này thường cần Workflow trở lên, không dùng được Rule đơn giản.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Threshold cường độ pixel cố định để tách vùng bất thường | Chỉ với ca rất điển hình, cấu trúc giải phẫu chuẩn | Bỏ sót hầu hết ca thực tế vì biến thiên giải phẫu/bệnh lý lớn | Không dùng làm bước chính — chỉ dùng cho bước tiền xử lý phụ (chuẩn hoá cường độ ảnh) |
| **Workflow** | Pipeline cố định: tiền xử lý ảnh → chạy model segmentation pretrained (MONAI/nnU-Net) → xuất mask + confidence → bác sĩ review | Khi model đã được validate đủ tốt trên tập dữ liệu tương tự, không cần tự điều chỉnh chiến lược theo từng ca | Model có thể sai với ca hiếm/khác phân bố dữ liệu train | **Chọn — dùng cho bước 2 (AI khoanh vùng) trong future state** |
| **Agent** | Agent tự đánh giá độ tin cậy, tự chọn model phù hợp theo loại bệnh lý, tự giải thích lý do khoanh vùng, tự đề xuất khi cần chụp thêm | Khi cần xử lý nhiều loại ca bệnh khác nhau và cần explainability, không chỉ ra kết quả | Phức tạp, khó kiểm soát, rủi ro y tế cao nếu agent tự quyết sai mà thiếu review | Không dùng ở mức pilot — để dành giai đoạn sau nếu workflow chứng minh hiệu quả |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? — Không. Threshold cường độ cố định chỉ đúng với ca rất điển hình; biến thiên giải phẫu và bệnh lý MRI quá lớn để 1 ngưỡng cố định giải quyết đa số ca.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? — Chủ yếu đi thẳng một đường (ảnh vào → model → review → báo cáo), chỉ rẽ nhánh nhỏ khi confidence thấp thì fallback về đọc thủ công hoàn toàn.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? — Ở giai đoạn PoC trong môn học thì chưa cần — 1 workflow cố định (pretrained model + review) đã đủ chứng minh giá trị; Agent phức tạp hơn nên để dành khi đã có baseline vững.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? — Bác sĩ review là người phát hiện đầu tiên, ngay tại bước 3 của future state, và sửa ngay lúc review trước khi báo cáo được gửi đi — không có case nào kết quả AI đi thẳng ra ngoài mà không qua người.
5. Có hạ được từ Agent → Workflow → Rule không? — Có, nhóm chủ động hạ từ Agent xuống Workflow: bài toán có độ mơ hồ cao nhưng KHÔNG cần agent tự ra quyết định/tự gọi nhiều tool — 1 model pretrained cố định + human review là đủ cho quy mô PoC.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Pipeline cố định (tiền xử lý → model segmentation pretrained → review) đã đủ giải quyết bottleneck chính (khoanh vùng thủ công chậm, phụ thuộc kinh nghiệm cá nhân) mà không cần độ phức tạp và rủi ro của agent. Dùng model pretrained có sẵn (MONAI/nnU-Net trên BraTS) giúp nhóm làm được PoC trong thời gian 1 buổi lab, đúng tiêu chí "làm trong lab được" đã chấm ở Phase 3.4. Workflow cũng giữ được ranh giới an toàn: mọi kết quả AI đều đi qua bước review của bác sĩ trước khi thành báo cáo cuối.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Không chọn Rule vì bài toán có độ mơ hồ cao — không có ngưỡng pixel cố định đúng cho mọi ca, rule-based sẽ bỏ sót phần lớn ca thực tế, không đáng tin cậy trong bối cảnh y tế nơi hậu quả của việc bỏ sót là nghiêm trọng.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Bác sĩ chẩn đoán hình ảnh (radiologist) đọc phim MRI não tại bệnh viện/phòng khám. *(chưa được xác nhận bởi 1 actor thật — xem cảnh báo Phase 4.1)* |
| **Workflow** | Từ lúc nhận ảnh MRI trên PACS đến khi khoanh vùng bất thường thủ công và viết báo cáo chẩn đoán — 6 bước (xem 5.1), trong đó bước đối chiếu hồ sơ cũ chỉ phát sinh khi bệnh nhân tái khám. |
| **Bottleneck** | Bước khoanh vùng nghi ngờ thủ công (bước 3): tốn thời gian biến thiên, phụ thuộc kinh nghiệm cá nhân, dễ bỏ sót ở ca phức tạp. |
| **Impact** | *(chưa đo thật nội bộ)* — nay có literature-based estimate cụ thể hơn v0: cận trên 3-5 giờ/ca cho khoanh vùng pixel-level thủ công (PMC9107172); AI hỗ trợ giảm 87-100% thời gian contouring trong nghiên cứu paired quốc tế (PubMed 42512069); bối cảnh Việt Nam có tình trạng thiếu hụt radiologist thật (KJR 2023, PMC10613840). Vẫn là ước tính thứ cấp, chưa phải số đo của chính actor mà nhóm nhắm tới. |
| **Success Metric** | Thời gian khoanh vùng/đọc phim giảm so với baseline; tỷ lệ bỏ sót vùng bất thường (false negative) đo được trên tập test (vd BraTS) không tăng so với bác sĩ đọc một mình; Dice score của model trên tập test không thấp hơn đáng kể so với benchmark nnU-Net trên BraTS (~85-89%, arXiv 2011.00848) — nếu thấp hơn nhiều thì chưa đủ tin cậy để đề xuất pilot. |
| **Boundary** (làm / không làm) | Làm: đưa ra vùng khoanh gợi ý + confidence score để bác sĩ tham khảo. Không làm: để AI tự đưa ra kết luận chẩn đoán cuối cùng hoặc tự động gửi báo cáo mà không qua review. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp ngay sau bước 1 (ảnh vào hệ thống) và trước bước "khoanh vùng thủ công" cũ — AI thực hiện khoanh vùng gợi ý thay cho việc bác sĩ tự khoanh từ đầu, trước khi bước viết báo cáo diễn ra. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow — vì cần pipeline nhiều bước cố định (tiền xử lý, model, review) nhưng không cần agent tự lập kế hoạch hay tự chọn công cụ. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất: AI bỏ sót vùng bất thường thật (false negative) khiến bác sĩ chủ quan tin theo gợi ý AI mà bỏ qua vùng khác. Người kiểm tra: bác sĩ chẩn đoán hình ảnh luôn phải tự đọc lại toàn bộ ảnh chứ không chỉ nhìn vùng AI khoanh; nhóm cần đo tỷ lệ false negative trên tập test công khai trước khi đề xuất dùng thử thật. |

---

## Phase 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Not Yet | Actor (bác sĩ chẩn đoán hình ảnh) và workflow đã mô tả rõ về mặt logic, nhưng chưa được xác nhận trực tiếp với 1 bác sĩ thật. |
| Baseline + metric đo được chưa? | Not Yet | Đã nâng từ "No" lên "Not Yet" sau khi bổ sung research định lượng thật có link kiểm được (thời gian khoanh vùng thủ công, % giảm thời gian khi có AI, benchmark Dice score, tỷ lệ thiếu hụt radiologist tại Việt Nam) — nhưng đây vẫn là số liệu thứ cấp/quốc tế, chưa phải số đo trực tiếp trên actor và bối cảnh nhóm nhắm tới. |
| Data/input đủ dùng chưa? | Yes | Có thể dùng dataset công khai BraTS để demo segmentation, dù không phải dữ liệu bệnh viện thật của actor cụ thể. |
| AI sai, hậu quả chấp nhận được không? | Not Yet | Đã thiết kế fallback (luôn có bác sĩ review trước khi báo cáo được gửi) nhưng chưa kiểm chứng thực tế mức độ tin cậy của model. |
| Có người review/owner không? | Yes (thiết kế) | Bác sĩ review là boundary rõ trong future state, nhưng nhóm chưa có ai đóng vai actor đó thật để xác nhận quy trình review khả thi. |
| Có cách non-AI đơn giản hơn không? | Yes | Đã có sản phẩm thương mại FDA-cleared (Cortechs.ai, CorticoMetrics) giải quyết vấn đề tương tự — nhóm cần định vị đây là bài tập học thuật/PoC, không phải sản phẩm thay thế lâm sàng. |

**Decision:**

```text
Not Yet
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Actor thật vẫn chưa được xác nhận trực tiếp — Phase 4.1 (phỏng vấn/quote thật) vẫn còn trống, và đây là giới hạn duy nhất còn lại của bản nộp sau khi nhóm đã bổ sung research định lượng ở Phase 4.2 mở rộng (thời gian khoanh vùng thủ công, % cải thiện khi có AI, benchmark Dice score, tình trạng thiếu radiologist tại Việt Nam — đều có link kiểm được). Đây là lĩnh vực y tế, nơi hậu quả của AI sai (bỏ sót vùng bất thường) nghiêm trọng hơn nhiều so với các candidate khác của nhóm, nên ngưỡng bằng chứng cần cao hơn trước khi "Go" — số liệu thứ cấp dù mạnh vẫn không thay được việc actor thật xác nhận đúng bối cảnh làm việc của họ. Bài toán có nền tảng kỹ thuật khả thi thật (model pretrained sẵn có, benchmark Dice score công khai, dataset public để test), nên không phải "No-Go" — chỉ cần thêm 1 vòng phỏng vấn thật trước khi cam kết build.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Chưa áp dụng — quyết định hiện tại là Not Yet, không phải Go. Khi đủ điều kiện Go, pilot nhỏ nhất dự kiến: chạy model pretrained (MONAI/nnU-Net) trên 15-20 ảnh mẫu từ BraTS, đo (1) thời gian model chạy/ảnh, (2) tỷ lệ overlap (Dice score) giữa mask AI và ground truth có sẵn trong dataset, (3) số ca cần bác sĩ (giả lập bởi thành viên nhóm có kiến thức) chỉnh sửa nhiều so với mask AI.
```

**Nếu Not Yet — cần validate gì trước:**

```text
(1) Phỏng vấn tối thiểu 1 bác sĩ chẩn đoán hình ảnh, sinh viên y khoa, hoặc giảng viên y khoa để xác nhận đúng bottleneck mô tả ở Phase 5.1 và lấy ước lượng thời gian thật cho bước khoanh vùng. (2) Chạy thử model pretrained (MONAI/nnU-Net) trên vài ảnh mẫu từ BraTS để đo sơ bộ Dice score/tỷ lệ bỏ sót trước khi cam kết pipeline. (3) Đọc kỹ thêm tài liệu về quy trình đọc phim MRI thực tế tại Việt Nam (workflow có thể khác tài liệu quốc tế đã tham khảo).
```

**Nếu No-Go — làm gì thay AI:**

```text
Không áp dụng ở thời điểm này (quyết định là Not Yet). Nếu sau khi validate mà quyết định chuyển thành No-Go, nhóm sẽ rollback sang candidate "Ghi chép + tóm tắt bài giảng" (33/35 điểm, đã đủ actor + workflow + evidence rõ từ chính nhóm) như đã thống nhất ở mục Disagreement (Phase 3.3).
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng và rollback nếu: (a) sau 1-2 tuần nhóm không tiếp cận được bất kỳ bác sĩ/sinh viên y khoa nào để phỏng vấn, hoặc (b) khi chạy thử model pretrained trên BraTS, Dice score quá thấp/tỷ lệ bỏ sót quá cao so với ngưỡng nhóm tự đặt trước khi thử (cần thống nhất ngưỡng cụ thể khi họp nhóm). Khi đó quay lại candidate "Ghi chép + tóm tắt bài giảng" đã có sẵn ở vị trí dự phòng.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được) — *research (4.2 + 4.2 mở rộng) đã đủ và định lượng (5 nguồn thật, có link, search ngày 2026-09-12); validation (4.1) vẫn còn thiếu quote thật từ 1 actor — đây là ô duy nhất chưa tick được, vì không thể tạo quote phỏng vấn giả thay cho phỏng vấn thật*
- [x] Có workflow trước/sau đủ handoff, bottleneck, boundary, fallback — *thời gian cụ thể từng bước vẫn cần đo thật nội bộ; đã có literature-based estimate làm tham chiếu tạm (3-5 giờ/ca cận trên, giảm 87-100% khi có AI)*
- [x] Có PS v0 → v1, boundary có làm/không làm — *metric có công thức đo + ngưỡng benchmark kỹ thuật cụ thể (Dice score nnU-Net ~85-89%); baseline "trước" nay có literature-based estimate, chưa phải số đo thật của nhóm*
- [x] Có so sánh Rule/Workflow/Agent + Decision (Not Yet, có lý do)
