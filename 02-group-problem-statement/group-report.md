# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Trần Anh Vũ | 2A202602570 | facilitator |
| 2   | Nguyễn Hoang Duy | 2A202602751 | writer |
| 3   | Nguyễn Minh Hiển | 2A202602759 | research |
| 4   | Nguyễn Đặng Nam Khánh | 2A202602741 | research |

**Candidate problem nhóm chọn (1 câu):**

Đọc, dịch và tóm tắt paper/tài liệu kỹ thuật tiếng Anh khi viết báo cáo đồ án.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nam Khánh | So sánh log/metric giữa nhiều lần train/finetune model CV | Người tự học/finetune model | Đọc log và copy tay số liệu vào bảng so sánh (~10 phút/lần) | Workflow rõ, dễ hiểu, ít phụ thuộc domain sâu |
| 2 | Nam Khánh | Convert/deploy model CV lên thiết bị edge rồi test tay | Người tự học deploy model edge (Jetson/RPi/mobile) | Convert lỗi (thiếu layer/op hỗ trợ) phải làm lại từ đầu | Rõ nhưng khá đặc thù kỹ thuật edge |
| 3 | Nam Khánh | Verify cảnh báo agent giám sát có phải false positive | Người tự thử nghiệm hệ thống agent giám sát | Tua video xem tay từng cảnh báo để xác nhận đúng/sai | Trực quan, dễ hiểu, nhưng cần có sẵn hệ thống giám sát mới trải nghiệm được |
| 4 | Anh Vũ | Gom báo cáo tuần của thành viên nhóm đồ án rồi tổng hợp gửi GVHD | Trưởng nhóm đồ án tốt nghiệp | Ghép nội dung rải rác và căn chỉnh format thủ công | Actor rõ, workflow rất rõ, ai làm nhóm cũng từng trải |
| 5 | Anh Vũ | Đọc, dịch và tóm tắt paper/tài liệu kỹ thuật tiếng Anh dài | Cả nhóm đồ án tốt nghiệp | Đọc-dịch chi tiết và tự nhặt ý chính (~2 giờ/bài) | Rất phổ biến với sinh viên làm đồ án/nghiên cứu |
| 6 | Anh Vũ | Tìm lại quyết định/góp ý của GVHD bị trôi trong chat Zalo/Messenger | Cả nhóm, đặc biệt trưởng nhóm | Lục tìm tin nhắn cũ trong box chat hỗn độn | Dễ hiểu, nhiều người gặp khi làm việc nhóm qua chat |
| 7 | Minh Hiển | Debug lỗi code: copy error lên Google/AI rồi thử nhiều solution | Sinh viên làm project cá nhân | Tìm và đánh giá solution phù hợp với context project | Rất phổ biến, nhưng AI coding assistant hiện tại đã hỗ trợ mạnh phần này |
| 8 | Minh Hiển | Tìm tài liệu/documentation phù hợp vì quá nhiều kết quả tràn lan | Sinh viên làm project | Đọc/lọc nhiều kết quả để xác định nguồn phù hợp | Dễ hiểu nhưng có thể chỉ là vấn đề search skill |
| 9 | Minh Hiển | Thành viên nhóm hỏi lại task/deadline nhiều lần vì thông tin phân tán trong chat | Sinh viên làm project nhóm | Tìm lại thông tin task/deadline trong lịch sử chat | Rất phổ biến với mọi nhóm học tập |
| 10 | Hoàng Duy | Tổng hợp bằng chứng/hoạt động để viết báo cáo thực tập | Sinh viên năm cuối viết báo cáo thực tập | Tìm lại ghi chú/file rồi tái dựng hoạt động đã làm | Actor rõ nhưng số liệu hiện là giả định, cần xác nhận thật |
| 11 | Hoàng Duy | Thu hẹp phạm vi đề tài sau khi bị phản biện (actor/pain chưa rõ, scope quá rộng) | Học viên AI Product đề xuất đề tài | Diễn giải feedback thành thay đổi cụ thể | Sát với chính hoạt động Day 02, nhưng khá meta/trừu tượng |
| 12 | Hoàng Duy | Chuyển kiến thức lý thuyết lab thành bước triển khai thực tế | Học viên AI Thực chiến làm lab | Chuyển yêu cầu thành kế hoạch triển khai ban đầu | Cụ thể nhưng số liệu vẫn là giả định, cần kiểm chứng |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A | #1 So sánh log/metric train, #4 Gom báo cáo tuần gửi GVHD, #10 Tổng hợp bằng chứng báo cáo thực tập | Gom thông tin rải rác từ nhiều nguồn/nhiều lần chạy rồi tổng hợp thủ công thành một output chuẩn hóa (bảng, báo cáo) | Workflow giống nhau: thu thập → đọc/copy tay → tổng hợp; actor rõ, dễ đo bằng phút/tuần |
| B | #6 Tìm lại quyết định GVHD trong chat, #9 Hỏi lại task/deadline nhóm | Thông tin quan trọng (quyết định, task, deadline) bị trôi/thất lạc trong chat, phải tìm lại hoặc hỏi lại nhiều lần | Pain từ giao tiếp nhóm qua chat, rất phổ biến với mọi nhóm học tập/dự án |
| C | #5 Đọc/tóm tắt paper tiếng Anh, #8 Tìm tài liệu/documentation phù hợp, #12 Chuyển lý thuyết lab thành triển khai | Đọc hiểu tài liệu dài hoặc kiến thức mới rồi tự trích xuất/chuyển hóa thành thứ dùng được | Cần hiểu ngữ cảnh sâu, AI có thể hỗ trợ tóm tắt nhưng vẫn cần người kiểm chứng |
| D (nếu có) | #2 Convert/deploy model edge, #3 Verify cảnh báo agent giám sát, #7 Debug lỗi code | Kiểm tra/đánh giá kết quả kỹ thuật thủ công để xác nhận đúng/sai | Đặc thù kỹ thuật hơn; #11 mang tính meta nên để riêng, không gom cưỡng ép |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #5 Đọc, dịch và tóm tắt paper/tài liệu kỹ thuật tiếng Anh (Anh Vũ) | Actor rõ; workflow rõ 5 bước; bottleneck khoanh đúng vào đọc-dịch chi tiết và nhặt ý; impact đo được bằng giờ/bài (~2 giờ/bài, ~2 bài/tuần) | AI có nắm đúng thuật ngữ chuyên ngành không; rủi ro hallucination khi trích dẫn từ PDF dài |
| #8 Tìm tài liệu/documentation phù hợp (Minh Hiển) | Actor rõ, workflow rõ 7 bước; bottleneck cụ thể; impact đo bằng phút/vấn đề (30-60 phút) | Có thể chỉ là vấn đề search skill; pattern khá giống #5 nên cần làm rõ điểm khác biệt |
| #12 Chuyển kiến thức lý thuyết thành bước triển khai lab (Hoàng Duy) | Actor rõ, sát bối cảnh học hiện tại; bottleneck ở bước chuyển yêu cầu thành kế hoạch triển khai | Số liệu 70 phút và 3 lần đổi hướng là giả định, chưa có bằng chứng thật |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #5 Đọc/dịch/tóm tắt paper tiếng Anh | 5 | 5 | 4 | 5 | 5 | 4 | 5 | 33 |
| #8 Tìm tài liệu/documentation phù hợp | 4 | 4 | 3 | 4 | 4 | 3 | 4 | 26 |
| #12 Chuyển lý thuyết lab thành triển khai | 4 | 4 | 2 | 3 | 4 | 3 | 4 | 24 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Đọc, dịch và tóm tắt paper/tài liệu kỹ thuật tiếng Anh khi viết báo cáo đồ án (Candidate #5 của Anh Vũ).
```

**Vì sao chọn (4-5 câu):**

```text
Workflow rõ nhất trong 3 candidate: 5 bước từ tìm PDF đến viết lại tiếng Việt, bottleneck khoanh đúng vào bước đọc-dịch chi tiết và nhặt ý (bước 3-4). Pain có evidence cụ thể: ~2 giờ/bài, ~2 bài/tuần, tổng 4 giờ/tuần cho cả nhóm đồ án; số liệu được ước lượng từ trải nghiệm thật, không phải giả định. Impact dễ đo bằng giờ/bài trước và sau, đồng thời so sánh được giữa Rule, Workflow và Agent. Domain quen thuộc với cả 4 thành viên vì ai cũng từng đọc paper/tài liệu kỹ thuật cho đồ án/lab.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#8 Tìm tài liệu/documentation: pain gốc chưa chắc chắn; có thể chỉ là vấn đề search skill hoặc documentation chưa tốt. Pattern cũng khá trùng #5 (đều là đọc/lọc nội dung dài), nên nhường chỗ cho candidate có evidence mạnh hơn.

#12 Chuyển lý thuyết thành triển khai: toàn bộ số liệu (70 phút, 3 lần đổi hướng) là giả định, chưa có bằng chứng thật. Impact và pain-evidence yếu nhất trong 3 candidate nên rủi ro cao nếu chọn làm bài chính trong thời gian lab có hạn.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Không có disagreement lớn — điểm số giữa #5 và #8 cách nhau khá xa (33 vs 26) nên nhóm đồng thuận nhanh. Điểm cần lưu ý: #5 dựa trên trải nghiệm của một thành viên (Anh Vũ), nên ở Phase 4 nhóm sẽ hỏi thêm 2-3 người khác để xác nhận đây không phải pain riêng của một người.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | Chưa thực hiện | Chưa có quote nguyên văn. Cần phỏng vấn 2-3 sinh viên đang làm đồ án, hỏi thời gian đọc/dịch paper và bước gây mất thời gian nhất. | Chưa có dữ liệu để kết luận. | Chưa chốt số liệu trước/sau; chỉ giữ candidate nếu ít nhất 2/3 người xác nhận pain tương tự. |
| Survey / poll | Chưa thực hiện | Chưa có mẫu khảo sát. Có thể hỏi 5-10 người về số paper/tuần, thời gian/bài và mức độ cần kiểm tra thuật ngữ. | Chưa có dữ liệu để kết luận. | Dùng median thay vì ước lượng của một thành viên nếu mẫu đủ lớn. |
| Log / ticket / review (nếu có) | 1 trải nghiệm nhóm, chưa phải log chính thức | Quan sát ban đầu: một paper mất khoảng 2 giờ để đọc-dịch-tóm tắt; đây là self-report, chưa phải bằng chứng độc lập. | Chưa có log thời gian chi tiết và chưa kiểm tra độ chính xác bản tóm tắt. | Tạo bảng đo cho 3 paper tiếp theo: thời gian, số đoạn phải sửa, số thuật ngữ cần tra lại. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Insight tạm thời: pain tập trung ở việc đọc kỹ, tra thuật ngữ và tự chọn ý quan trọng, không chỉ ở thao tác dịch. Kết luận này chưa đủ để gọi là validation; nhóm cần phỏng vấn/survey trước khi chốt baseline và success metric.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Google Scholar | [scholar.google.com](https://scholar.google.com/) | Tìm paper theo từ khóa, tác giả và trích dẫn | Phổ biến, dễ tìm nguồn và lần theo tài liệu liên quan | Kết quả nhiều; không tự đánh giá paper có phù hợp với đề tài hay không | Giữ bước tìm paper do người dùng thực hiện, chỉ hỗ trợ chuẩn hóa từ khóa và tiêu chí chọn |
| Semantic Scholar | [semanticscholar.org](https://www.semanticscholar.org/) | Lọc và khám phá paper liên quan, xem trích dẫn và paper tương tự | Có gợi ý paper liên quan và thông tin tóm tắt nhanh | Tóm tắt/gợi ý có thể thiếu ngữ cảnh; vẫn phải mở và kiểm tra paper gốc | Có thể dùng như nguồn phụ để đối chiếu, không coi abstract tự động là bằng chứng đầy đủ |
| Zotero | [Zotero Quick Start Guide](https://www.zotero.org/support/quick_start_guide) | Lưu PDF, metadata, ghi chú và trích dẫn trong quá trình nghiên cứu | Quản lý nguồn và trích dẫn tập trung, giảm việc tìm lại file | Không giải quyết việc hiểu thuật ngữ hay kiểm chứng nội dung; cần người cấu hình thư viện | Nên lưu paper gốc và nguồn trích dẫn trước khi AI tóm tắt, để có thể truy ngược từng ý |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm nên build một workflow hẹp: nhận PDF hợp lệ → trích xuất theo khung cố định (mục tiêu, phương pháp, dữ liệu, kết quả, hạn chế) → hiển thị đoạn nguồn → người review và viết lại. Không nên build công cụ tìm kiếm paper mới, không tự sinh citation, và không cho AI thay người dùng kết luận tính đúng đắn của paper.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 Tìm paper: 10-15' - sinh viên] → [2 Chọn/tải PDF: 5' - sinh viên] → [3 Đọc và dịch chi tiết: 45-60' - sinh viên] → [4 Nhặt ý chính, tra thuật ngữ: 15-20' - sinh viên, bottleneck] → [5 Viết tóm tắt tiếng Việt: 15-20' - sinh viên] → [6 Kiểm tra số liệu/trích dẫn: 5-10' - sinh viên] → [7 Đưa vào báo cáo và review: 5-10' - nhóm]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Sinh viên | Từ khóa/nhu cầu của đề tài | Danh sách paper tiềm năng | 10-15 phút/paper | Tìm thủ công; có thể phải đổi từ khóa |
| 2 | Sinh viên | Danh sách paper | PDF được chọn và tải về | 5 phút | Handoff từ tìm kiếm sang đọc; cần kiểm tra paper đúng chủ đề |
| 3 | Sinh viên | PDF tiếng Anh | Bản dịch/ghi chú theo từng phần | 45-60 phút | Đọc-dịch chi tiết, phụ thuộc thuật ngữ; bắt đầu bottleneck |
| 4 | Sinh viên | Bản dịch/ghi chú | Ý chính và danh sách thuật ngữ cần tra | 15-20 phút | Bottleneck chính: vừa hiểu ngữ cảnh vừa quyết định ý nào cần giữ |
| 5 | Sinh viên | Ý chính đã chọn | Tóm tắt tiếng Việt để đưa vào báo cáo | 15-20 phút | Dễ bỏ sót điều kiện, hạn chế hoặc làm sai sắc thái câu |
| 6 | Sinh viên | Tóm tắt và paper gốc | Bản đã kiểm tra số liệu/trích dẫn | 5-10 phút | Cần quay lại paper gốc để đối chiếu |
| 7 | Nhóm đồ án | Bản tóm tắt đã kiểm tra | Nội dung đưa vào báo cáo | 5-10 phút | Handoff cuối; thành viên khác review nếu có thời gian |

**Bottleneck chính (2-3 câu):**

```text
Bottleneck chính nằm ở bước 3-4: người đọc phải dịch câu tiếng Anh, hiểu thuật ngữ và đồng thời tự quyết định ý nào quan trọng. Một paper hiện mất khoảng 2 giờ theo ước lượng ban đầu, nhưng nhóm chưa có log thời gian độc lập; đây là baseline cần đo lại trong pilot.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Kiểm tra PDF và trích xuất text: 2-3' - máy/rule] → [2 AI trích xuất theo khung + dẫn đoạn/trang: 10-15' - AI] → [3 Người review thuật ngữ, số liệu và ý chính: 15-20' - người, boundary] → [4 Người viết lại tiếng Việt: 20-30' - người] → [5 Checklist trích dẫn và đưa vào báo cáo: 5-10' - rule + người] → [6 Nhóm review cuối: 10' - người]

Fallback: nếu PDF lỗi/OCR kém, AI không dẫn được đoạn nguồn hoặc người review phát hiện sai, quay về đọc paper gốc và quy trình hiện tại; không dùng bản tóm tắt AI làm căn cứ duy nhất.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | ~120 phút/paper (ước lượng) | 60-75 phút/paper (giả định cần pilot) | Bấm giờ từng bước trên ít nhất 3 paper tương đương |
| Số bước | 7 | 6 | Đếm bước có output riêng trong workflow |
| Số bước thủ công | 7 | 4-5 | Đếm bước do người thực hiện, không tính trích xuất/checklist tự động |
| Bottleneck chính | Đọc-dịch và tự nhặt ý | Review thuật ngữ, số liệu và đoạn nguồn | Ghi thời gian và số lần sửa ở từng bước |
| Risk mới | Bỏ sót ý hoặc dịch sai do đọc thủ công | AI bỏ sót, bịa hoặc diễn giải sai nội dung | Review ngẫu nhiên từng claim và đối chiếu paper gốc |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên làm đồ án, đặc biệt thành viên phụ trách đọc tài liệu và viết phần related work. |
| **Workflow** | Người dùng cung cấp PDF paper hợp lệ; hệ thống trích xuất nội dung theo khung cố định, kèm đoạn/trang nguồn; người dùng kiểm tra rồi viết lại bản tiếng Việt cho báo cáo. |
| **Bottleneck** | Đọc-dịch chi tiết và nhặt ý chính tốn nhiều thời gian vì phải xử lý thuật ngữ, ngữ cảnh và các điều kiện của kết quả cùng lúc. |
| **Impact** | Baseline ban đầu khoảng 2 giờ/paper và khoảng 2 paper/tuần theo tự ước lượng của nhóm; con số này cần được đo lại bằng log trong pilot. |
| **Success Metric** | Giảm thời gian hoàn thành một paper ít nhất 25% so với baseline, trong khi 100% claim được đưa vào báo cáo có đoạn/trang nguồn và người review chấp nhận. |
| **Boundary** | Làm: trích xuất, dịch nháp, tóm tắt có dẫn nguồn. Không làm: tự quyết định paper đúng/sai, tự sinh citation không có trong PDF, hoặc thay người dùng kiểm chứng kết quả chuyên môn. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Impact và Success Metric còn dựa trên self-report, chưa phải số đo độc lập.
- Tôi sửa gì: Trong pilot, nhóm sẽ đo thời gian thực tế, số claim bị sửa và số thuật ngữ cần tra lại trên cùng loại paper.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: một paper có thể được tóm tắt theo nhiều mức độ, và việc chọn ý quan trọng phụ thuộc vào mục tiêu báo cáo.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: workflow gồm tìm/chọn PDF, trích xuất, dịch, kiểm chứng và viết lại; các bước phụ thuộc paper cụ thể.

**Bài toán nhóm nằm ở ô nào:**

```text
Bài toán nhóm nằm ở ô độ mơ hồ cao, độ phức tạp cao. AI cần hỗ trợ nhiều bước có liên kết nhưng vẫn phải có boundary rõ để người dùng kiểm tra thuật ngữ, số liệu và claim trước khi đưa vào báo cáo.
```

**Vì sao (2-3 câu):**

```text
Độ mơ hồ cao vì không có một bản tóm tắt duy nhất đúng cho mọi mục tiêu viết báo cáo. Độ phức tạp cao vì cần xử lý PDF, ngữ cảnh kỹ thuật, thuật ngữ và trích dẫn qua nhiều bước; tuy nhiên workflow này vẫn có khung tương đối ổn định nên chưa cần Agent tự lập kế hoạch.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Checklist cố định để kiểm tra PDF, các mục bắt buộc và citation có đoạn/trang nguồn | Đủ cho kiểm tra định dạng và nhắc người dùng không bỏ sót mục | Không giúp hiểu thuật ngữ hoặc chọn ý quan trọng | Dùng cho bước 1 và bước 5 |
| **Workflow** | Chuỗi trích xuất theo khung → AI tạo bản nháp có dẫn nguồn → người review → viết lại → checklist | Đủ khi paper đi theo luồng tương đối ổn định và luôn có người review | AI có thể bỏ sót hoặc diễn giải sai nếu PDF/OCR kém | **Chọn** cho toàn bộ luồng đọc-dịch-tóm tắt |
| **Agent** | Tự tìm paper, chọn nguồn, đọc nhiều tài liệu và quyết định nội dung báo cáo | Chỉ đáng dùng khi cần xử lý nhiều nguồn và rẽ nhánh phức tạp | Khó kiểm soát nguồn, dễ tự quyết định sai và khó truy vết | Chưa chọn; vượt quá nhu cầu pilot |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không?
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?
5. Có hạ được từ Agent → Workflow → Rule không?

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Nhóm chọn Workflow vì các bước chính đã biết trước và có thể chuẩn hóa bằng một khung tóm tắt cố định. AI chỉ tạo bản nháp có dẫn đoạn/trang nguồn, còn người đọc chịu trách nhiệm kiểm tra thuật ngữ, số liệu và claim. Rule được dùng kèm cho kiểm tra đầu vào và checklist cuối. Agent chưa cần thiết vì pilot chưa phải bài toán tự tìm kiếm và lập kế hoạch qua nhiều nguồn.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Nhóm không chọn Rule thuần túy vì Rule chỉ kiểm tra được cấu trúc và sự hiện diện của thông tin, không xử lý được bản dịch nháp hay trích xuất ý từ paper. Nhóm cũng không chọn Agent vì mức tự chủ và rủi ro truy vết cao hơn nhu cầu hiện tại; có thể nâng cấp sau nếu workflow chứng minh được dữ liệu và boundary ổn định.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên làm đồ án, người phụ trách đọc paper và viết related work hoặc phần nền tảng kỹ thuật. |
| **Workflow** | Từ PDF hợp lệ, hệ thống trích xuất mục tiêu, phương pháp, dữ liệu, kết quả và hạn chế kèm đoạn/trang nguồn; sinh viên review rồi viết lại bản tiếng Việt đưa vào báo cáo. |
| **Bottleneck** | Đọc-dịch và nhặt ý chính hiện chiếm phần lớn thời gian, khoảng 2 giờ/paper theo self-report ban đầu. |
| **Impact** | Nếu được xác nhận, bottleneck làm chậm tiến độ viết báo cáo và khiến nhóm phải quay lại paper nhiều lần để kiểm tra thuật ngữ, số liệu và điều kiện của claim. |
| **Success Metric** | Sau pilot, thời gian trung vị giảm ít nhất 25% so với baseline của cùng loại paper; ít nhất 95% claim được dùng có đoạn/trang nguồn; người review đánh dấu pass nội dung trước khi gửi. |
| **Boundary** (làm / không làm) | Làm: hỗ trợ trích xuất, dịch nháp và tóm tắt có nguồn. Không làm: tự kết luận paper đúng/sai, tự tạo citation không có nguồn, hoặc tự gửi nội dung chưa được người review kiểm tra. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp sau khi người dùng chọn và tải PDF, trước bước người dùng đọc-dịch chi tiết; AI tạo bản nháp có trích dẫn đoạn/trang để người dùng review. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow, vì chuỗi bước và điểm review đã xác định, còn nội dung trích xuất cần khả năng hiểu ngữ cảnh nhưng chưa cần Agent tự lập kế hoạch. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI bịa hoặc làm sai sắc thái claim. Thành viên phụ trách paper đối chiếu từng claim quan trọng với PDF gốc, đánh dấu pass/fail và sửa trước khi nhóm đưa vào báo cáo. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor, input PDF, các bước xử lý và điểm review đã được mô tả cụ thể. |
| Baseline + metric đo được chưa? | Not Yet | Có self-report khoảng 2 giờ/paper nhưng chưa có log độc lập; cần đo ít nhất 3 paper tương đương. |
| Data/input đủ dùng chưa? | Not Yet | Cần kiểm tra paper có text/OCR tốt, thuật ngữ chuyên ngành và format khác nhau trước khi kết luận. |
| AI sai, hậu quả chấp nhận được không? | Yes, có điều kiện | Có thể chấp nhận ở pilot nếu mọi claim đều được đối chiếu với PDF và không dùng bản nháp AI làm output cuối tự động. |
| Có người review/owner không? | Yes | Thành viên phụ trách paper là owner; nhóm review nội dung trước khi đưa vào báo cáo. |
| Có cách non-AI đơn giản hơn không? | Yes | Checklist và template thủ công có thể giải quyết một phần; AI chỉ đáng dùng nếu pilot chứng minh giảm thời gian mà không tăng lỗi. |

**Decision:**

```text
Not Yet
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Nhóm đã có actor, workflow và một hướng can thiệp có boundary rõ, nhưng validation hiện chưa có quote thật và baseline 2 giờ/paper mới là self-report của một thành viên. Vì vậy chưa đủ bằng chứng để triển khai rộng hoặc kết luận mức giảm 25%. Nhóm chỉ nên làm pilot nhỏ có người review, sau đó quyết định Go hay No-Go dựa trên thời gian và tỷ lệ claim bị sửa.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Chưa áp dụng Go cho đến khi hoàn tất validation. Khi đủ điều kiện, pilot nhỏ nhất là chọn 3 paper kỹ thuật có độ dài và chủ đề tương đương, chạy thủ công workflow trên cùng một template. Đo 3 số: tổng thời gian/paper, tỷ lệ claim có đoạn/trang nguồn, và số claim/thuật ngữ bị người review sửa.
```

**Nếu Not Yet — cần validate gì trước:**

```text
Phỏng vấn 2-3 sinh viên và khảo sát 5-10 người để xác nhận tần suất đọc paper, thời gian thực tế và pain ở bước nào. Sau đó chạy pilot có đối chứng với cách cũ trên ít nhất 3 paper, ghi log từng bước và kiểm tra xem AI có làm tăng số lỗi thuật ngữ hoặc claim không có nguồn hay không.
```

**Nếu No-Go — làm gì thay AI:**

```text
Nếu validation cho thấy thời gian không giảm, chất lượng không ổn định hoặc người review phải sửa phần lớn bản nháp, nhóm sẽ không dùng AI. Khi đó quay về template tóm tắt thủ công, checklist citation và công cụ quản lý nguồn như Zotero.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng AI và quay về workflow cũ nếu PDF không trích xuất được, AI không cung cấp được đoạn/trang nguồn, có claim sai nghiêm trọng, hoặc tỷ lệ claim bị sửa vượt ngưỡng nhóm đặt ra. Bản nháp AI phải được lưu riêng; chỉ bản đã người review kiểm tra mới được đưa vào báo cáo.
```

---

### Self-check nộp phần 02 (nhóm)
- [ ] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được)
- [ ] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [ ] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [ ] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
