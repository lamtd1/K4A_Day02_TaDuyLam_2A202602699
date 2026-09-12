# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Tạ Duy Lâm
- Mã học viên: 2A202602699
- Nhóm: Khuê, Dương, Việt, Phong, Lương
- Candidate problem nhóm chọn: Hỗ trợ bác sĩ chẩn đoán hình ảnh khoanh vùng bất thường trên ảnh MRI (não) nhanh và nhất quán hơn so với đọc phim hoàn toàn thủ công, trong khi bác sĩ vẫn là người quyết định chẩn đoán cuối cùng.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Có 1 candidate cá nhân, nêu ra trong buổi thảo luận nhưng tự bỏ giữa chừng vì thấy khó phát triển đủ chặt để so sánh Rule/Workflow/Agent | Nhóm tập trung thời gian vào 11 candidate còn lại của 5 bạn, không sa đà vào hướng khó |
| Pitch Problem Card | Không áp dụng — candidate cá nhân đã bỏ, không đi tới bước làm Problem Card riêng | — |
| Challenge bài của bạn khác | Lúc Dương đề xuất chọn candidate MRI vì thấy "ngầu", tôi đồng ý ngay tại chỗ, không phản biện gì. Sau đó khi ngồi gõ báo cáo, tôi tự chấm lại bảng điểm 3.4 và thấy MRI thua hẳn 2 candidate kia (20 so với 33 và 31), nên tôi chủ động viết thêm đoạn "Flag trung thực" ở mục 3.4 | Rủi ro "chọn vì thấy ngầu" được ghi thành văn bản rõ ràng thay vì trôi qua, buộc cả nhóm phải nêu lý do chấp nhận rủi ro và điều kiện rollback |
| Gom trùng / cluster | Là người trực tiếp gõ máy, tổng hợp 12 ý kiến của cả nhóm thành 4 cluster A/B/C/D ở mục 3.2 | Nhóm nhìn rõ pattern trùng lặp (cluster A, C) và loại được 2 candidate lạc loài (tiếng Nhật, sensor cây) khỏi shortlist |
| Chọn candidate problem | Gõ bảng điểm 3.4 và viết đoạn "Flag trung thực" nêu rõ candidate MRI chấm thấp hơn hẳn nhưng nhóm vẫn chọn | Quyết định chọn candidate có ghi rõ lý do và rủi ro thay vì chỉ chốt theo cảm tính |
| Validation / research | Tự viết thẳng "đây là phần yếu nhất" ở Phase 4.1 khi thấy nhóm chưa phỏng vấn được ai; sau đó dùng AI để search các nguồn thật (PubMed, PMC, arXiv) bổ sung 5 nguồn định lượng cho Phase 4.2 | Nâng được baseline/impact từ chỗ hoàn toàn trống lên có số liệu thật, có link kiểm được, dù vẫn thiếu phỏng vấn actor thật |
| Workflow nhóm | Dùng AI vẽ lại 2 sơ đồ current-state và future-state chi tiết hơn (icon, bottleneck, human boundary, fallback) dựa trên đúng nội dung bảng đã có | Ảnh workflow rõ ràng, dễ đọc hơn để đưa vào báo cáo cuối |
| Problem Statement | Đưa số liệu research mới (thời gian khoanh vùng thủ công, % giảm khi có AI, Dice score benchmark) vào field Impact và Success Metric ở PS v0/v1 | PS v1 có ngưỡng cụ thể để so sánh thay vì để trống "(cần đo thật)" |
| Rule / Workflow / Agent | Không trực tiếp làm — phần này chủ yếu do Khuê và Phong phụ trách, tôi đọc lại và đồng ý với kết luận | Không có đóng góp trực tiếp ở phần này |
| Decision | Giữ quyết định cuối là "Not Yet" dù đã có thêm bằng chứng mới, và từ chối để AI bịa quote phỏng vấn giả chỉ để hoàn thành checklist | Báo cáo phản ánh đúng thực trạng bằng chứng, không thổi phồng thành "Go" |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Đoạn "Flag trung thực" ở mục 3.4 và "Ghi chú của Lâm" ở cuối group-report.md. Đó là chỗ tôi tự ép mình và cả nhóm nhìn thẳng vào sự thật khó nghe (chọn MRI dù điểm thấp hơn hẳn 2 candidate kia, và quyết định cuối là "Not Yet" chứ không phải "Go") thay vì để nó trôi qua như lúc tôi đồng ý ngay tại chỗ trong buổi thảo luận.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Không dùng | — | — | Candidate cá nhân tôi tự nghĩ và tự đánh giá là khó, không cần AI để quyết định bỏ |
| Problem Card | Không dùng | — | — | Không áp dụng vì đã bỏ candidate cá nhân |
| Workflow | Dùng AI để vẽ lại 2 sơ đồ current/future state (SVG rồi xuất PNG) | Bố cục, icon, xuất ảnh nhanh hơn tự vẽ tay | Bản đầu tiên AI vẽ bị lỗi: nhãn "human boundary" đè chồng lên dòng phụ đề, nhìn rối | Tôi yêu cầu AI xuất ảnh ra xem trước, phát hiện lỗi chồng chữ và bắt sửa lại vị trí trước khi chấp nhận |
| Research | Dùng AI để search các nguồn thật (PubMed, PMC, arXiv) bổ sung số liệu định lượng còn thiếu ở Phase 4.2 | Tìm nhanh 5 nguồn có link kiểm được: thời gian khoanh vùng thủ công, % giảm khi có AI hỗ trợ, Dice score benchmark, tình trạng thiếu radiologist ở Việt Nam | Tôi có yêu cầu AI "cứ bịa" quote phỏng vấn cho xong Phase 4.1, AI từ chối và giải thích đó sẽ là dữ liệu ngụy tạo | Tôi chấp nhận không fake quote, giữ đúng phần research thật và đánh dấu rõ phỏng vấn thật vẫn còn thiếu, không tự nhận là đã xong |
| Problem Statement | Dùng AI để đưa số liệu research mới vào đúng field Impact/Success Metric theo đúng format bảng | Diễn đạt lại số liệu cho gọn, đúng field | AI ban đầu viết số liệu như thể là số đo thật của nhóm, dễ gây hiểu lầm | Tôi bắt ghi rõ đây là "literature-based estimate" / "ước tính thứ cấp", không phải số đo thật của nhóm |
| Rule / Workflow / Agent | Không dùng | — | — | Phần này do Khuê và Phong làm trực tiếp, tôi chỉ đọc lại và đồng ý |
| Decision | Dùng AI để viết lại đoạn lý do quyết định cho khớp với bằng chứng mới bổ sung | Diễn đạt mạch lạc hơn bản nháp của tôi | Không có lỗi rõ, nhưng nếu tôi không để ý thì AI có thể đã viết theo hướng lạc quan hơn thực tế | Tôi tự giữ quyết định cuối là "Not Yet", không để AI đổi thành "Go" dù đã có thêm số liệu |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Tôi chọn 4 câu: đóng góp thật của tôi, có thay đổi ý kiến sau khi bị challenge không, điều khó nhất khi viết Problem Statement, và nếu làm lại tôi sẽ challenge nhóm mạnh hơn ở điểm nào.

Trong đợt làm bài này, tôi là người trực tiếp ngồi gõ và tổng hợp toàn bộ file group-report.md — từ gom 12 candidate của cả nhóm thành 4 cluster, chấm điểm ở bảng 3.4, cho tới viết đoạn "Flag trung thực" và ghi chú quyết định cuối. Tôi cũng có một candidate cá nhân nhưng bỏ giữa chừng vì thấy khó phát triển đủ chặt, nên chuyển hẳn sang vai trò tổng hợp cho cả nhóm. Điều thú vị là tôi không hề bị ai challenge trực tiếp trong buổi thảo luận — khi Dương đề xuất chọn candidate MRI vì thấy "ngầu", tôi đồng ý ngay tại chỗ, không phản biện gì cả. Chỉ đến khi ngồi một mình chấm lại bảng điểm 3.4 và thấy MRI thua hẳn hai candidate kia (20 so với 33 và 31), tôi mới tự nhận ra vấn đề và chủ động viết thẳng sự thật đó vào báo cáo thay vì để nó trôi qua. Nếu làm lại, tôi nghĩ tôi nên nói ngay lúc đó trong buổi họp, thay vì đợi tới lúc ngồi viết một mình mới dám ép cả nhóm nhìn vào rủi ro đã bỏ qua. Điều khó nhất với tôi khi viết Problem Statement là phần Impact: không ai trong nhóm học y, cũng không phỏng vấn được bác sĩ thật, nên số liệu impact ban đầu hoàn toàn để trống. Tôi phải tự đi tìm nghiên cứu công khai (PubMed, PMC, arXiv) để có số liệu tạm thay thế, nhưng vẫn phải ghi rõ đó là ước tính thứ cấp chứ không phải số đo thật của nhóm, để không biến báo cáo thành tự huyễn hoặc. Việc chấp nhận giữ quyết định cuối là "Not Yet" thay vì cố kéo lên "Go" cũng không dễ, vì nhóm đã bỏ khá nhiều công sức làm workflow và research — nhưng tôi thấy giữ đúng hiện trạng bằng chứng quan trọng hơn là làm đẹp báo cáo cho có vẻ hoàn chỉnh. Bài học lớn nhất của tôi là: đồng thuận ngay tại chỗ trong lúc thảo luận nhóm dễ hơn nhiều so với việc nói thẳng sự thật khi ngồi viết báo cáo một mình — nhưng nếu chỉ dám nói thật lúc viết báo cáo thì cơ hội để cả nhóm bàn lại quyết định ngay từ đầu đã mất.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [ ] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [ ] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

