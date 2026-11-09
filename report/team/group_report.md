# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: NiceTry
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Chuyển đổi tài liệu thành slide thuyết trình trực quan
- Quyết định cuối: Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Vũ Thành | Khi chuẩn bị nộp bài tập trước deadline, tôi muốn đối chiếu toàn bộ các file trong thư mục bài nộp với yêu cầu nộp của bài để đảm bảo không bị thiếu file, sai định dạng | Sinh viên nộp bài cá nhân hoặc nhóm | Bước 4: Mở từng file đối chiếu yêu cầu và danh sách file cần nộp (30-40 phút), rất dễ thiếu file hoặc đổi sai cú pháp tên | Nếu có checklist cố định trên Excel/Notion từ đầu kỳ để tick chọn trước khi nộp, có giải quyết được vấn đề mà không cần làm công cụ tự động không? (Thành Nam hỏi) |
| 2 | Vũ Thành | Khi làm slide cho bài tập lớn, tôi muốn chuyển đổi các đoạn văn và thông tin từ tài liệu thành các gạch đầu dòng ngắn gọn và sơ đồ trực quan để bài thuyết trình sinh động, người nghe dễ nắm bắt mà không mất cả buổi ngồi chọn nội dung | Sinh viên làm slide | Bước 3: Tóm tắt ý thành bullet points (60 phút) và Bước 4: Tìm ảnh/vẽ sơ đồ minh họa (40–45 phút) | Làm thế nào để đánh giá slide AI gợi ý là đủ tốt, và làm sao đảm bảo AI lấy đúng nội dung theo tài liệu? (Thành Nam hỏi) |
| 3 | Vũ Thành | Khi tổng hợp bài làm chung của nhóm trước hạn nộp, tôi muốn các phần do thành viên khác viết có đủ nội dung, đồng bộ format về lề, font và đúng theo yêu cầu đề bài để không phải sửa lại hoặc viết bù nội dung sát giờ nộp | Trưởng nhóm | Bước 2: Viết bù nội dung thiếu/sơ sài (45–60 phút) và Bước 3: Chuẩn hóa format lộn xộn (40 phút) | Làm sao để hệ thống chỉ ra được phần nào chưa được kiểm chứng hay sai format? (Thành Nam hỏi) |
| 4 | Thành Nam | Khi làm bài tập nhóm hoặc dự án, tôi muốn tổng hợp nhanh các tài liệu và bài tham khảo từ nhiều nguồn rời rạc (Zalo, Docs, Drive), để không phải lội tìm thủ công từng nơi | Thành viên nhóm | Bước 2–4: Lội tìm tin nhắn Zalo cũ và mở nhiều link Drive/Docs rời rạc (10–15 phút/lần) | Nếu có một kênh chung, quy trình chung ngay từ đầu thì có giải quyết được vấn đề này mà không cần dùng đến AI không? (Vũ Thành hỏi) |
| 5 | Thành Nam | Khi họp nhóm có bạn vắng mặt hoặc không nhớ việc, tôi muốn tóm tắt nhanh nội dung họp và danh sách công việc, để báo cáo lại mà không mất nhiều thời gian giải thích | Trưởng nhóm | Bước 2–4: Soạn bản tóm tắt và nhắn riêng giải thích cho thành viên vắng mặt (15–20 phút/buổi) | Bản tóm tắt tự động có đủ chi tiết và chuẩn theo ý định của người nói để người vắng làm đúng việc không? (Vũ Thành hỏi) |
| 6 | Thành Nam | Khi có nhiều bài tập và task làm việc hàng tuần, tôi muốn xem nhanh lịch làm việc và deadline sắp tới, để không bị bỏ sót hoặc quên lịch | Sinh viên | Bước 1–4: Tổng hợp thông tin deadline từ nhiều kênh Zalo, LMS, note cá nhân (15–20 phút/lần) | Mỗi người có một ứng dụng quản lý lịch khác nhau, làm sao đồng bộ chung với nhau? (Vũ Thành hỏi) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| **A — Chuyển đổi & Trực quan hóa tài liệu** | Vũ Thành #2 (Làm slide — 180 phút), Thành Nam #1 (Tìm tài liệu rải rạc — 10-15 phút), Vũ Thành #3 (Tổng hợp bài nhóm — 110 phút) | Đọc hiểu, chắt lọc ý chính và chuyển đổi tài liệu thô thành sản phẩm đầu ra hoàn chỉnh (slide thuyết trình, báo cáo nộp) |
| **B — Kiểm soát deadline & Rà soát bài nộp** | Vũ Thành #1 (Checklist nộp bài — 50 phút), Thành Nam #3 (Theo dõi deadline tuần — 15-20 phút) | Kiểm tra các công việc cần hoàn thành, thiếu file hoặc trễ hạn nộp do thông tin nằm và áp lực thời gian sát deadline 
| **C — Điều phối & Giao tiếp nhóm** | Thành Nam #2 (Recap họp nhóm — 15-20 phút), Vũ Thành #3 (Tổng hợp bài nhóm — 110 phút) | Chi phí thời gian cho việc đồng bộ thông tin, đôn đốc tiến độ và khắc phục sự thiếu chủ động của các thành viên |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian chuẩn bị slide thuyết trình từ 180 phút xuống dưới 65 phút và thời gian tổng hợp bài nhóm từ 110 phút xuống dưới 30 phút mà vẫn đảm bảo tính chính xác và thẩm mỹ
├── Opportunity A: Khó chọn lọc ý chính và tốn 180 phút để chuẩn bị, chuyển đổi nội dung tài liệu thành slide thuyết trình trực quan
├── Opportunity B: Mất 30–40 phút đối chiếu thủ công và dễ sót file khi nộp bài sát deadline
└── Opportunity C: Mất 10–15 phút mỗi lần lội tìm tài liệu tham khảo rải rác trên Zalo và Google Drive
```

### 2.4. Chấm điểm shortlist (1–5)

Nhóm chọn ra 3 candidate đại diện cho 3 cluster để chấm điểm:
1. **Candidate 1:** Chuyển đổi tài liệu báo cáo thành slide thuyết trình (Vũ Thành #2)
2. **Candidate 2:** Đối chiếu và kiểm tra bài nộp trước deadline (Vũ Thành #1)
3. **Candidate 3:** Tìm kiếm tài liệu học tập và bài làm nhóm rải rạc (Thành Nam #1)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **1. Chuyển tài liệu thành slide (Thành #2)** | 5 | 5 | 5 | 5 | 4 | 5 | 5 | **34** |
| **2. Checklist bài nộp trước deadline (Thành #1)** | 5 | 5 | 4 | 4 | 4 | 5 | 5 | **32** |
| **3. Tìm tài liệu nhóm rải rạc (Nam #1)** | 4 | 4 | 4 | 4 | 4 | 3 | 4 | **27** |

**Candidate được chọn:**
> **Bài toán: Chuyển đổi tài liệu báo cáo thành slide thuyết trình trực quan (Candidate 1)**

**Vì sao chọn:**
- Đây là bài toán có thời gian lãng phí lớn nhất (180 phút mỗi bài thuyết trình, baseline đo lường cụ thể), ảnh hưởng trực tiếp đến điểm số thuyết trình và bảo vệ đồ án của cả nhóm
- Pain point rất rõ: sinh viên đọc nội dung dài 25–30 trang dễ bị sai sót và lạc giữa nhiều nội dung cần thiết, không biết chắt lọc ý nào bỏ vào slide dẫn đến slide ngập ngụa chữ và thuyết trình quá giờ
- AI có thế mạnh vượt trội ở việc tóm tắt và đề xuất cấu trúc nội dung, đồng thời nhóm dễ dàng so sánh giữa *No AI (Canva template) - Rule (Marp Markdown to slide) - Workflow (AI tóm tắt + gợi ý sơ đồ) - Agent (tự sinh slide)* ở CP6

**Vì sao loại các candidate còn lại:**
- **Loại Candidate 3 (Tìm tài liệu rải rạc):** Bản chất vấn đề nằm ở thói quen quản lý file của nhóm; chỉ cần giải pháp No AI (quy ước một folder Drive chung và ghim link trên Zalo) là đã giải quyết được phần lớn mà không cần đến AI, khả năng phân tích các mức can thiệp AI kém
- **Loại Candidate 2 (Checklist bài nộp):** Dù quy trình rất rõ nhưng bài toán này nghiêng nhiều về mức **Rule** (viết script kiểm tra tên file/folder), ít đất diễn cho việc phân tích AI Workflow sâu sắc bằng bài toán làm slide

**Xử lý bất đồng:**
- Ban đầu Thành Nam muốn chọn bài toán *Tìm tài liệu rải rạc* vì Nam gặp vấn đề này nhiều lần trong quá trình học tập. Tuy nhiên, Vũ Thành đã phản biện rằng bài toán này có thể giải quyết được bằng cách thêm quy trình chung cho việc gửi, lưu trữ tài liệu (No AI)
- Khi thảo luận kỹ về bài toán làm slide (Candidate 1), Nam nhận thấy đây là nút thắt chung mà cả hai bạn đều sợ nhất mỗi khi đến đợt thuyết trình (thường tốn 3–4 tiếng làm slide). Cả nhóm đã đồng thuận 100% chọn bài toán **Làm slide thuyết trình** để đi tiếp vào CP4.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên mất nhiều thời gian nhất ở khâu đọc chắt lọc ý từ văn bản dài chứ không phải khâu chọn màu sắc/hiệu ứng slide | Value | 5 | 5 | Không |
| 2 | AI có thể đọc hiểu file dài 25–30 trang và giữ đúng thuật ngữ kỹ thuật, không bịa nội dung | Feasibility | 5 | 2 | Có |
| 3 |  Sinh viên không muốn AI tự động làm hết 100% slide vì sợ không hiểu bài để trả lời phản biện trước hội đồng| Usability | 5 | 2 | Có |
| 4 | Các công cụ tạo slide AI hiện nay thường tự sinh nội dung chung chung từ mạng chứ không bám sát file báo cáo cụ thể của sinh viên	 | Viability | 4 | 3 | Có |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:Sinh viên mất nhiều thời gian nhất ở khâu đọc chắt lọc ý từ văn bản dài chứ không phải khâu chọn màu sắc/hiệu ứng slide

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn 1 sinh viên và 1 cựu sinh viên (ở nhóm khác): chỉ hỏi về trải nghiệm quá khứ khi cần phải chọn lọc nội dung và hình ảnh khi làm slide

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | sinh viên ra trường 1 năm, trước kia thường xuyên phải làm slide để báo cáo môn học cuối kỳ |
| Câu nói đáng nhớ nhất (nguyên văn) | 	"Mỗi lần được giao làm slide là anh phải mất 1 ngày để tổng hợp, tóm tắt nội dung, chọn hình ảnh để thêm vào báo cáo" |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Lúc còn là sinh viên, làm slide mất 2 ngày cho môn triết học Mác Lênin |
| Hiện đang xử lý bằng cách nào (workaround)? | Đọc từng mục, copy đoạn mở đầu của mỗi phần sang PowerPoint rồi bôi đen vài từ khóa chính |
| Mất bao lâu, bao lần? | 1-2 ngày |
| Insight / opportunity rút ra | Nút thắt lớn nhất là khâu lọc ý và cô đọng văn bản thành luận điểm, chứ sinh viên không thiếu template mẫu (Google/Canva/PPT có sẵn) |

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên sắp ra trường |
| Câu nói đáng nhớ nhất (nguyên văn) | "Nếu công cụ tự động làm hết cả slide lẫn hình ảnh thì mình sẽ không dùng vì sẽ không đúng ý thẩm mỹ của mình, nhiều lúc hình ảnh tìm được không phù hợp với nội dung" |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Lúc làm slide cho môn Công nghệ Phần mềm |
| Hiện đang xử lý bằng cách nào (workaround)? | Làm thủ công từng trang theo template trên mạng |
| Mất bao lâu, bao lần? | Mất 4-5 tiếng để hoàn thành slide |
| Insight / opportunity rút ra | Không thể để hệ thống tự động hóa mọi thứ từ nội dung đến hình ảnh |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn sinh viên kỹ thuật | 2/2 | 100% (2/2) khẳng định mất nhiều thời gian làm slide : khâu tóm tắt, tìm kiếm nội dung, hình ảnh và trình bày nội dung ra slide là bước gây khó khăn nhất | Cả 2 người đều không muốn AI tự động xuất ra file slide hoàn chỉnh vì sợ AI tự chèn hình ảnh sai lệch và nội dung bị thiếu, không theo ý mình |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** Thay đổi kỳ vọng mức độ can thiệp: Nhóm từ bỏ ý tưởng làm một hệ thống tự động sinh toàn bộ slide từ A đến Z. Thay vào đó, định hình lại giải pháp theo mô hình Workflow (Human-in-the-loop): AI chỉ đóng vai trò trợ lý đọc hiểu báo cáo, gợi ý khung dàn ý và tóm tắt đoạn văn thành các gạch đầu dòng ngắn gọn, sinh viên vẫn là người kiểm duyệt nội dung, lựa chọn hình ảnh kỹ thuật và trực tiếp căn chỉnh lần cuối.
Thiết lập giới hạn nghiêm ngặt: AI chỉ được làm việc trên dữ liệu được cấp (chính là file báo cáo do nhóm tải lên), cấm tuyệt đối việc tự ý tìm kiếm ảnh ngẫu nhiên trên mạng hoặc tự bổ sung các kiến thức không có trong bài làm của sinh viên

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Gamma App	 | https://gamma.app | Nhận outline/văn bản thô, tự động tạo slide kèm bố cục và hình ảnh minh họa | Giao diện cực đẹp, trực quan hóa dữ liệu nhanh (vài phút là có bản nháp), nhiều dạng card/bố cục sinh động | Tóm tắt quá nông khi đưa tài liệu chuyên ngành dài vào; dễ bịa thông tin; hình ảnh sinh tự động không khớp với sơ đồ kỹ thuật | Cần bước lọc ý và kiểm duyệt trước khi đẩy sang giao diện slide; không để AI tự quyết hình ảnh minh họa kỹ thuật |
| Marp | https://marp.app| Chuyển đổi trực tiếp tài liệu Markdown sang slide trình chiếu theo template | Chạy offline, chuẩn xác 100%, kiểm soát hoàn toàn bằng Rule | Không có khả năng tóm tắt văn bản; người dùng vẫn phải tự cắt gọt chữ thủ công | Dùng Rule để chuẩn hóa template slide; chỉ dùng AI ở bước tóm tắt nội dung thô |
| Canva |https://www.canva.com | Nhập chủ đề hoặc dàn ý ngắn, tự động tạo bộ slide có thiết kế đồng bộ | Kho template khổng lồ, thẩm mỹ cao, dễ chỉnh sửa kéo thả trực tiếp trên trình duyệt | Chỉ nhận prompt ngắn, không có khả năng đọc và hiểu trọn vẹn file báo cáo 25–30 trang có sẵn để trích xuất nội dung | Trọng tâm của bài toán là xử lý tài liệu có sẵn (Document-to-Slide) chứ không phải sinh ý tưởng mới từ hư vô |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — 180 phút

[1. Đọc lại báo cáo lọc ý: 30 phút] 
  ──▶ [2. Lập khung dàn ý slide: 20 phút] 
  ──▶ [3. Tóm tắt thành gạch đầu dòng: 60 phút] ◀── BOTTLENECK
  ──▶ [4. Tìm ảnh & vẽ sơ đồ minh họa: 45 phút] ◀── BOTTLENECK
  ──▶ [5. Căn chỉnh bố cục & format: 25 phút ]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Sinh viên làm slide | File báo cáo | Các đoạn văn bản được gạch chân/highlight | 30 phút / mỗi bài thuyết trình |  |
| 2 | Sinh viên làm slide | Các ý trọng tâm đã highlight | Dàn ý phân bổ nội dung cho 20–25 slide | 20 phút / mỗi bài thuyết trình | Phải cân đối số lượng slide cho từng chương và phù hợp với giới hạn thời gian thuyết trình |
| 3 | Sinh viên làm slide | Các đoạn văn dài trong báo cáo | Các gạch đầu dòng ngắn gọn trên slide | 60 phút / mỗi bài thuyết trình	 | Bottleneck: Rất khó tóm tắt mà không làm cụt ý, dễ chép nguyên cả đoạn văn dài |
| 4 | Sinh viên làm slide | Nội dung các slide | Hình ảnh tải từ Google | 45 phút / mỗi bài thuyết trình | Bottleneck: Mất thời gian tìm kiếm ảnh phù hợp hoặc tự ghép các khối hình |
| 5 | Sinh viên làm slide | Bản nháp slide sơ khai | File slide hoàn chỉnh (PPTX/PDF) | 25 phút / mỗi bài thuyết trình | Chỉnh sửa font chữ, cỡ chữ, căn lề và hiệu ứng cho đồng bộ |

**Bottleneck chính:** Bước 3 (Tóm tắt đoạn văn thành gạch đầu dòng — 60 phút): Sinh viên bị quá tải nhận thức khi phải đọc tài liệu dài, không biết bỏ ý nào giữ ý nào, dẫn đến tình trạng chép quá nhiều chữ lên slide
Bước 4 (Tìm ảnh & vẽ sơ đồ minh họa — 45 phút): Mất nhiều thời gian tìm kiếm hình ảnh rời rạc trên mạng hoặc tự vẽ tay
### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.
[Rule]: Trích xuất text từ file tài liệu, áp dụng template chuẩn/có sẵn (khóa font chữ, màu sắc, bố cục slide)
[AI]: Đọc hiểu tài liệu, gợi ý cấu trúc dàn ý theo số lượng slide; tóm tắt các đoạn văn thành bullet points theo nguyên tắc có trước, đề xuất dạng sơ đồ trực quan tương ứng với nội dung
[Con người (HITL)]: Kiểm duyệt tính chính xác của thuật ngữ kỹ thuật, phê duyệt dàn ý, chọn lọc ảnh kỹ thuật thực tế của đồ án, chỉnh sửa để hoàn thiện duyệt bản slide cuối trước khi thuyết trình
[Phương án quay về (Fallback)]: Nếu AI tóm tắt sai hoặc bị lỗi hệ thống, sinh viên chuyển sang dùng template có sẵn trên Canva/PowerPoint và tự gõ dàn ý theo các đề mục lớn của báo cáo

```text
TƯƠNG LAI — Tổng thời gian: ~55 phút (Tiết kiệm ~70% thời gian)

[1. Tải tài liệu lên hệ thống]
  ──▶ [2. RULE: Trích xuất text theo heading chương/mục: 1']
  ──▶ [3. AI: Đề xuất dàn ý slide + tóm tắt bullet points + gợi ý sơ đồ: 4']
  ──▶ [4. CON NGƯỜI (HITL): Kiểm duyệt nội dung, chỉnh sửa thuật ngữ chuyên ngành: 20'] ◀── ĐIỂM KIỂM SOÁT
        │
        ├─▶ [AI sai / Hallucination] ──▶ [FALLBACK: Người tự sửa lại bullet points dựa trên heading gốc]
        │
  ──▶ [5. CON NGƯỜI: Chèn hình ảnh/biểu đồ kỹ thuật thực tế từ bài báo cáo: 20']
  ──▶ [6. RULE: Áp dụng template chuẩn hóa bố cục, xuất file PPTX/PDF: 5']
  ──▶ [7. CON NGƯỜI: Duyệt lại lần cuối và chuẩn bị thuyết trình: 5']
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 | 7 bước (trong đó 2 bước tự động, 1 bước AI hỗ trợ, 4 bước con người) | Quy trình chặt chẽ hơn nhờ có bước kiểm duyệt trung gian |
| Tổng thời gian | >=180 phút (3 tiếng) | ~55 phút (dưới 65 phút) | Tiết kiệm 125 phút (giảm gần 70% thời gian) |
| Số bước thủ công | 5 bước (100% người làm) | 3 bước (kiểm duyệt, chèn ảnh thật, duyệt cuối) | Giảm tải khâu tóm tắt và căn chỉnh định dạng |
| Bottleneck chính | Bước 3 tóm tắt ý (60') + Bước 4 Tìm ảnh & vẽ sơ đồ minh họa (45') | Bước 4 con người kiểm duyệt thuật ngữ (20') | |
| Rủi ro mới phát sinh | Slide quá nhiều chữ, cháy giờ thuyết trình, mệt mỏi | Rủi ro AI bịa thông tin (hallucination) hoặc làm mất thuật ngữ kỹ thuật quan trọng | Giải quyết triệt để bằng bước kiểm duyệt HITL bắt buộc trước khi xuất slide |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên phụ trách làm slide thuyết trình |
| **Quy trình** | Đọc tài liệu → Lập dàn ý cho slide → Đọc văn bản thành gạch đầu dòng → Tìm ảnh và vẽ sơ đồ minh họa → Căn chỉnh bố cục và định dạng, trình bày trên slide |
| **Bottleneck** | Khâu đọc chắt lọc các đoạn văn dài thành gạch đầu dòng ngắn gọn (mất 60 phút) và khâu tự vẽ/tìm sơ đồ trực quan (mất 45 phút); sinh viên dễ bị nhầm lẫn và lan man, đưa quá nhiều chữ lên slide |
| **Impact** | Mất từ 3–4 tiếng buổi tối cho mỗi bài thuyết trình; slide ngập tràn chữ khiến người nghe mất tập trung, buổi thuyết trình bị quá thời gian quy định và nhóm bị giảng viên trừ điểm kỹ năng trình bày |
| **Success Metric** (baseline → target, cách đo) | - Thời gian: Giảm từ 180 phút (baseline) xuống dưới 65 phút (target) cho một bài 20–25 slide đo bằng đồng hồ bấm giờ. Chất lượng trực quan: 100% slide tuân thủ nguyên tắc được đề ra trước, ví dụ : 6x6 (tối đa 6 gạch đầu dòng, mỗi dòng không quá 6 từ), số lượng sơ đồ/biểu đồ trực quan tăng ít nhất 30%; không có phản ánh bị trừ điểm vì slide nhiều chữ từ giảng viên |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | - AI không được: Tự ý bịa thêm thông tin ngoài file báo cáo được cung cấp; không được tự động chèn các hình ảnh tải ngẫu nhiên trên mạng, không được tự ý sửa đổi các thuật ngữ kỹ thuật và công thức chuyên ngành. HITL (Bắt buộc người kiểm tra): Con người phải kiểm duyệt và xác nhận dàn ý gạch đầu dòng trước khi áp dụng template, con người tự lựa chọn ảnh chụp mô hình/kết quả thực tế từ đồ án để chèn vào slide |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:
-Phản biện 1: "Nếu tài liệu báo cáo của sinh viên viết quá sơ sài hoặc câu cú lủng củng thì AI có tóm tắt đúng được không?"
Nhóm đồng ý: Nếu đầu vào quá tệ thì đầu ra slide sẽ không thể chuẩn xác. Nhóm bổ sung giải pháp: AI sẽ cảnh báo các đoạn văn bản thiếu số liệu hoặc diễn đạt tối nghĩa để người làm slide yêu cầu thành viên viết phần đó giải thích thêm kĩ càng hơn
-Phản biện 2: "Liệu sinh viên có quá ỷ lại vào AI mà không thèm đọc lại báo cáo của các bạn cùng nhóm không?"
Nhóm đồng ý một phần: Nhóm có thể thiết lập quy trình 2 bước : bắt buộc sinh viên phải đọc qua dàn ý tóm tắt của AI và xác nhận từng mục (Human-in-the-loop) thì hệ thống mới cho phép xuất file hoàn chỉnh


## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
