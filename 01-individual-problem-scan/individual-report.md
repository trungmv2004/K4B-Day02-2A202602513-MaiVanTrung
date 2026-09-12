# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên:
- Mã học viên:
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...):
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số ví dụ minh hoạ — CẦN THAY BẰNG SỐ THẬT) |
|---|---|---|---|---|
| 1 | Lặp lại | Điền lại thông tin cá nhân/CV trên mỗi trang tuyển dụng khác nhau | Sinh viên tìm việc (bạn) | Bấm giờ 1 lần nộp đơn: 8 phút. Số đơn/tuần: 5. Tổng phút/tuần = 40 phút |
| 2 | Lặp lại | Thao tác pause – crop – đặt tên file lặp lại khi gắn nhãn ảnh lỗi | Bạn (người labeling) | Đếm khung hình xử lý trong 30 phút: 90 khung → suy ra ~180 khung/giờ, đo 3 lần lấy trung bình |
| 3 | Tốn thời gian | Dò lại xem đã ứng tuyển công ty nào, tới bước nào | Bạn | Số lần/tuần phải tra lại: 3 lần. Mỗi lần mất: 5 phút → 15 phút/tuần |
| 4 | Tốn thời gian | Thời gian chờ load video/tool trong lúc gắn nhãn | Bạn | Tổng thời gian chờ trong 1 buổi 2 tiếng: 20 phút, đo 3 buổi |
| 5 | Tốn thời gian | "10 phút nữa thôi" nhưng kéo dài hàng giờ | Bạn | 5 lần gần nhất: dự định 10p → thực tế 45p, 10p → 30p, 10p → 60p, 10p → 25p, 10p → 50p |
| 6 | AI có thể tốt hơn | Phải xem toàn bộ video để tìm khung lỗi dù phần lớn là khung bình thường | Bạn | Tỉ lệ khung lỗi/tổng khung trong 1 video mẫu: 12 / 3000 (~0.4%) |
| 7 | AI có thể tốt hơn | Phải tự đọc từng tin tuyển dụng để biết có phù hợp không | Bạn | Số tin đọc/buổi: 30, số tin thực sự nộp: 4 (~13% tỉ lệ chuyển đổi) |
| 8 | Pain từ người khác | HR/nhà tuyển dụng khó so sánh CV vì mỗi người 1 định dạng | Nhà tuyển dụng | (Không có ví dụ hợp lý — cần quote/log thật, nếu không có nên xoá dòng) |
| 9 | Pain từ người khác | QA/quản lý khó kiểm soát vì mỗi labeler hiểu tiêu chí lỗi khác nhau | Quản lý/QA nhóm labeling | (Không có ví dụ hợp lý — cần số lần bị yêu cầu làm lại thật, nếu làm 1 mình nên xoá dòng) |
| 10 | Pain từ người khác | Bàn giao ca thiếu thông tin, người sau phải dò lại từ đầu | Đồng nghiệp ca sau | (Không có ví dụ hợp lý — cần thời gian bắt kịp thật, nếu không làm ca nên xoá dòng) |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

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
| 1 | Điền lại thông tin cá nhân/CV trên mỗi trang tuyển dụng khác nhau | 1. Tần suất cao nhất trong 3 vấn đề (xảy ra mỗi lần nộp đơn, nhiều đơn/tuần). 2. Có thể giải bằng cách đơn giản (CV mẫu, autofill) để test nhanh trước khi làm gì phức tạp hơn. 3. Dễ đo nhất — chỉ cần bấm giờ vài lần nộp đơn là có số thật ngay | Chưa biết bước nào trong quy trình mới là bottleneck thật (gõ chữ, tìm lại thông tin cũ, hay định dạng khác nhau giữa các trang) |
| 2 | Dò lại xem đã ứng tuyển công ty nào, tới bước nào | 1. Vấn đề tổ chức thông tin — sửa dễ, chi phí thấp (1 file Sheet/Notion). 2. Có khả năng liên quan trực tiếp đến vấn đề #1 (nếu quản lý tốt thông tin ứng tuyển, có thể giảm cả thời gian điền lại). 3. Dễ kiểm chứng bằng cách tự đếm số lần phải tra lại trong 1 tuần | Chưa rõ mức độ nghiêm trọng thật sự — có thể chỉ 1-2 lần/tuần thì không đáng ưu tiên |
| 3 | "10 phút nữa thôi" nhưng kéo dài hàng giờ | 1. Ảnh hưởng thời gian tổng thể có thể lớn nhất nếu đo ra số giờ mất/tuần. 2. Dữ liệu dễ thu thập (so sánh dự định vs thực tế) | Đây là vấn đề hành vi cá nhân, không chắc giải bằng "sản phẩm/tool" sẽ hiệu quả hơn thay đổi thói quen; xếp cuối vì rủi ro chọn sai hướng giải pháp cao nhất trong 3 vấn đề |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu:
Mỗi lần ứng tuyển trên 1 trang mới, mình phải gõ lại tay thông tin cá nhân/kinh nghiệm dù chúng gần như giống hệt lần trước.

Actor:
Mình (sinh viên mới ra trường, đang ứng tuyển nhiều nơi cùng lúc) — [CHƯA XÁC NHẬN đây có phải pain chung của nhóm sinh viên tìm việc hay chỉ riêng mình]

Thời điểm / bối cảnh:
Xảy ra mỗi khi tìm thấy tin tuyển dụng phù hợp và quyết định nộp đơn — không cố định giờ, thường rải rác trong ngày khi lướt các trang tuyển dụng.

Current workflow 3-7 bước:
1. Tìm thấy tin tuyển dụng phù hợp trên 1 trang (VD: TopCV, LinkedIn, VietnamWorks...)
2. Mở form ứng tuyển của trang đó
3. Gõ lại thông tin cá nhân (tên, SĐT, email, học vấn)
4. Gõ/điều chỉnh phần kinh nghiệm, kỹ năng cho phù hợp với JD
5. Đính kèm CV (file có sẵn hoặc phải điều chỉnh lại)
6. Trả lời thêm câu hỏi riêng của trang đó (nếu có)
7. Submit và không có nơi nào lưu lại tổng hợp đã nộp ở đâu

Bottleneck:
[CHƯA RÕ] — nghi ngờ nằm ở bước 3-4 (gõ lại thông tin cố định), nhưng chưa tách được bao nhiêu thời gian là do thông tin lặp lại (autofill được) vs bao nhiêu là do phải tuỳ chỉnh riêng cho từng job (không autofill được)

Impact:
[CẦN SỐ THẬT] — thời gian ước tính theo số liệu ví dụ trước là ~40 phút/tuần, nhưng đây là số minh hoạ, chưa đo thật

Success metric:
Giảm số phút trung bình/1 lần nộp đơn (đo bằng bấm giờ trước/sau khi áp dụng fix), giữ nguyên số lượng đơn nộp/tuần

Non-AI alternative:
- Lưu sẵn 1 file "master info" (tên, SĐT, học vấn, kinh nghiệm, mô tả bản thân ngắn) để copy-paste
- Dùng tính năng autofill có sẵn của trình duyệt hoặc extension autofill form
- 1 CV master + chỉnh nhẹ theo từng job thay vì viết lại từ đầu

AI hypothesis:
[CHƯA CẦN THIẾT Ở BƯỚC NÀY] — nếu sau khi áp dụng non-AI alternative mà vẫn còn tốn nhiều thời gian (do phải tuỳ biến nội dung theo từng JD), có thể cân nhắc AI hỗ trợ viết/điều chỉnh phần kinh nghiệm theo JD — nhưng cần dữ liệu thật trước khi giả định điều này

Quick gut:
[x] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 8 phút (ví dụ minh hoạ, cần đo thật)

[1 Tìm job & mở form: 1'] → [2 Gõ lại thông tin cá nhân/học vấn: 3'] → [3 Chỉnh kinh nghiệm/kỹ năng theo JD: 3'] → [4 Đính CV + trả lời câu hỏi riêng + submit: 1']  <-- bottleneck (bước 2+3 chiếm ~75% thời gian, nhưng CHƯA TÁCH được bước 2 do lặp lại thật hay bước 3 do phải tuỳ biến)

FUTURE STATE — 4 phút (ước tính nếu fix bước 2, vẫn CHƯA CÓ số thật)

[1 Autofill thông tin cá nhân/học vấn từ file master: 0.5'] → [2 Điều chỉnh kinh nghiệm/kỹ năng theo JD (vẫn làm tay): 3'] → [3 Review lại trước khi submit: 0.5']  <-- human boundary (con người luôn là người review cuối trước khi bấm submit, không để tool tự nộp đơn thay mình)

Fallback: nếu autofill điền sai/thiếu thông tin thì dừng lại, tự kiểm tra và sửa tay trước khi submit — không submit khi chưa review.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu:
Không có nơi lưu tập trung tình trạng ứng tuyển, nên mỗi khi cần biết đã nộp công ty nào/tới bước nào, mình phải lục lại email hoặc tin nhắn để nhớ lại.

Actor:
Mình (đang ứng tuyển nhiều nơi cùng lúc) — [CHƯA XÁC NHẬN mức độ phổ biến với sinh viên khác]

Thời điểm / bối cảnh:
Xảy ra khi: (a) có nhà tuyển dụng liên hệ lại và mình cần nhớ đã nộp gì/trao đổi gì trước đó, hoặc (b) trước khi nộp đơn mới, muốn kiểm tra tránh nộp trùng công ty.

Current workflow 3-7 bước:
1. Nhận tin nhắn/email phản hồi từ nhà tuyển dụng, hoặc tự nhớ ra cần kiểm tra
2. Không nhớ chính xác đã trao đổi tới đâu
3. Mở email, tìm theo tên công ty hoặc từ khoá
4. Không thấy ngay (email có thể nằm rải rác nhiều thread) → mở thêm Zalo/tin nhắn để tìm
5. Ghép lại thông tin từ nhiều nguồn để nhớ ra trạng thái
6. Trả lời/quyết định bước tiếp theo dựa trên thông tin vừa ghép lại được
7. Không lưu lại thành nơi tập trung nào → lần sau lại phải lặp lại từ bước 1

Bottleneck:
[CHƯA RÕ] — nghi ngờ là bước 1: gốc rễ nằm ở việc KHÔNG GHI LẠI ngay từ đầu (không phải khó tìm kiếm), nên mỗi lần cần đều phải dựng lại thông tin từ đầu

Impact:
[CẦN SỐ THẬT] — số ví dụ trước đó (3 lần/tuần x 5 phút = 15 phút/tuần) là minh hoạ, chưa đo thật. Ngoài ra impact thật có thể lớn hơn con số thời gian, nếu tính cả rủi ro nộp trùng công ty hoặc quên follow-up

Success metric:
Số lần/tuần phải "dò lại" giảm về gần 0 (vì thông tin đã có sẵn), đo bằng cách tự đếm trong 1-2 tuần sau khi áp dụng fix

Non-AI alternative:
- 1 Google Sheet/Notion đơn giản: Công ty | Ngày nộp | Trạng thái | Ghi chú/next step
- Cập nhật ngay sau mỗi lần nộp đơn hoặc có phản hồi mới (thói quen, không cần tool)
- Không cần bất kỳ công nghệ nào ngoài 1 bảng tính

AI hypothesis:
[CHƯA CẦN Ở BƯỚC NÀY] — đây gần như chắc chắn là vấn đề thói quen ghi chép, không phải thiếu công cụ. AI chỉ có thể cân nhắc sau này nếu việc tự động đọc email để cập nhật trạng thái tiết kiệm được thời gian đáng kể — nhưng cần thử sheet thủ công trước và đo xem còn pain không

Quick gut:
[x] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 5 phút (ví dụ minh hoạ, cần đo thật)

[1 Nhớ ra cần kiểm tra trạng thái 1 công ty: 0.5'] → [2 Lục lại email/tin nhắn theo tên công ty: 3'] → [3 Ghép thông tin từ nhiều nguồn để nhớ lại trạng thái: 1.5']  <-- bottleneck (bước 2: KHÔNG CÓ nơi lưu tập trung nên phải lục nhiều nguồn, không phải do tìm kiếm chậm)

FUTURE STATE — 1 phút (ước tính nếu có sheet cập nhật đều đặn)

[1 Mở sheet theo dõi ứng tuyển: 0.2'] → [2 Tìm dòng theo tên công ty: 0.3'] → [3 Đọc trạng thái + ghi chú, review lại có đúng/mới nhất không: 0.5']  <-- human boundary (con người luôn tự kiểm tra thông tin trong sheet có được cập nhật kịp thời không, vì sheet chỉ đúng khi mình chăm cập nhật)

Fallback: nếu thông tin trong sheet bị thiếu/cũ (do quên cập nhật) thì quay lại lục email/tin nhắn như cách cũ cho riêng công ty đó, sau đó cập nhật ngay vào sheet để lần sau không lặp lại.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu:
Khi định "chơi/xem 10 phút nữa thôi" để nghỉ ngơi, mình thường không dừng đúng lúc và kéo dài thành 30-60 phút.

Actor:
Mình — [CHƯA XÁC NHẬN xảy ra trong hoàn cảnh nào cụ thể: sau khi mệt, để né việc khó, hay chỉ là thói quen buổi tối]

Thời điểm / bối cảnh:
[CHƯA RÕ] — cần quan sát thêm: thường xảy ra sau khi làm việc căng thẳng để "xả hơi", hay là lúc trì hoãn 1 việc cụ thể (VD: né tránh ngồi vào làm nốt CV/gắn nhãn ảnh)?

Current workflow 3-7 bước:
1. Cảm thấy mệt/muốn nghỉ, tự nhủ "chơi/xem 10 phút thôi"
2. Mở app (game/video)
3. Hết 10 phút nhưng không có tín hiệu nhắc rõ ràng (không đặt hẹn giờ thật)
4. [CHƯA RÕ] — tại đây có nhận ra thời gian đã hết nhưng chọn tiếp tục, hay hoàn toàn mất khái niệm thời gian?
5. App/nội dung tự động dẫn tiếp (autoplay video kế tiếp, ván game mới bắt đầu không dừng giữa chừng được)
6. Nhận ra đã trễ (thường do việc khác nhắc, hoặc tự giật mình nhìn đồng hồ)
7. Dừng lại, có thể thấy tiếc thời gian nhưng không ghi nhận lại để rút kinh nghiệm

Bottleneck:
[CHƯA RÕ — quan trọng nhất cần xác định trước khi làm gì tiếp]. 3 khả năng: (a) không có tín hiệu nhắc giờ, (b) có nhận ra giờ nhưng chọn phớt lờ, (c) cơ chế của app (autoplay, matchmaking) khiến khó dừng giữa chừng

Impact:
[CẦN SỐ THẬT] — số ví dụ trước (dự định 10p → thực tế 25-60p, x5 lần) là minh hoạ. Cần biết thêm: xảy ra mấy lần/tuần, và có gây hậu quả cụ thể nào không (trễ deadline, mất giờ ngủ) hay chỉ là cảm giác khó chịu

Success metric:
Chênh lệch giữa thời gian dự định và thời gian thực tế giảm dần (đo bằng tự ghi lại 5-10 lần liên tiếp sau khi áp dụng fix)

Non-AI alternative:
- Đặt hẹn giờ vật lý (đồng hồ báo thức riêng, không dùng điện thoại đang chơi để canh giờ)
- Tắt autoplay (video, số lượt chơi tiếp theo)
- Dùng tính năng giới hạn thời gian có sẵn của hệ điều hành (Screen Time/Digital Wellbeing)
- Để điện thoại/thiết bị ở xa ngay khi hết giờ dự định

AI hypothesis:
[CHƯA PHÙ HỢP] — đây là vấn đề hành vi/quyết định cá nhân trong khoảnh khắc, không phải thiếu thông tin hay thiếu tự động hoá. 1 agent nhắc nhở hoặc chặn ứng dụng thường thất bại vì người dùng có thể tự tắt agent đó khi muốn tiếp tục. Cách hiệu quả hơn thường là tăng "ma sát" vật lý (rule), không phải làm hệ thống thông minh hơn.

Quick gut:
[x] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 42 phút trung bình (dựa trên số ví dụ minh hoạ trước: 45+30+60+25+50 / 5 lần, chưa phải số thật)

[1 Tự nhủ "10 phút thôi", không đặt hẹn giờ thật: 0'] → [2 Chơi/xem, không có tín hiệu nhắc rõ ràng, nội dung tự động nối tiếp: 30-40'] → [3 Giật mình nhận ra đã trễ (thường do việc khác nhắc)]  <-- bottleneck (bước 2: KHÔNG RÕ là do thiếu tín hiệu hay do biết mà vẫn phớt lờ — cần xác định trước khi fix)

FUTURE STATE — ước tính 10-15 phút (nếu tín hiệu nhắc giờ là nguyên nhân chính)

[1 Đặt hẹn giờ vật lý ngay khi bắt đầu: 0.2'] → [2 Chơi/xem như bình thường, tắt autoplay để giảm lực kéo: 10'] → [3 Chuông reo → tự dừng lại, review: có thực sự cần dừng ngay không, hay cho phép gia hạn 1 lần có ý thức?]  <-- human boundary (quyết định dừng hay tiếp tục LUÔN là của bạn, hẹn giờ chỉ tạo tín hiệu chứ không tự động khoá app — vì khoá cứng dễ bị lách và không giải quyết gốc rễ)

Fallback: nếu chuông reo mà vẫn không dừng được (tức là bottleneck thật ra là "biết mà vẫn phớt lờ" chứ không phải "thiếu tín hiệu"), thì fix bằng hẹn giờ là sai hướng — cần quay lại xác nhận lại Bottleneck, có thể chuyển sang giải pháp tăng ma sát vật lý mạnh hơn (để thiết bị ở phòng khác, nhờ người khác giữ hộ) thay vì tin vào tín hiệu nhắc nhở.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**
Khi định "chơi/xem 10 phút nữa thôi" để nghỉ ngơi, mình thường không dừng đúng lúc và kéo dài thành 30-60 phút — lặp lại nhiều lần/tuần, khiến thời gian dành cho tìm việc và làm nhiệm vụ gắn nhãn ảnh bị co lại đáng kể.

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**
Workflow: mở app không đặt hẹn giờ thật → không có tín hiệu nhắc rõ ràng → nội dung tự động nối tiếp (autoplay/matchmaking) → chỉ dừng khi có việc khác nhắc, không phải tự nhận ra.
Số đo: 5 lần gần nhất, dự định 10 phút nhưng thực tế 25-60 phút (trung bình ~42 phút), tức gấp 3-4 lần dự định mỗi lần xảy ra.
Impact: nếu xảy ra vài lần/tuần, đây có thể là "rò rỉ thời gian" lớn nhất trong 3 problem đã phân tích — lớn hơn nhiều so với 40 phút/tuần (điền CV) hay 15 phút/tuần (dò lại trạng thái ứng tuyển).

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**
1. Bottleneck thật sự là "không có tín hiệu nhắc giờ" hay "biết giờ đã hết nhưng vẫn chọn tiếp tục"? Vì 2 nguyên nhân này dẫn tới 2 hướng giải hoàn toàn khác nhau (nhắc nhở vs tăng ma sát vật lý).
2. Đây có phải vấn đề "sản phẩm/tool giải được" hay là vấn đề hành vi cá nhân mà bất kỳ ai cũng có thể tự fix bằng rule đơn giản (hẹn giờ, tắt autoplay) — nếu vậy, có đáng để pitch thành 1 project không?

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Toàn bộ số liệu (42 phút, 5 lần) là ví dụ minh hoạ tự đặt ra để hình dung format, chưa phải log thật — pitch dựa trên số này sẽ không đứng vững nếu ai hỏi "log đâu?". Ngoài ra bottleneck chưa được xác nhận (thiếu tín hiệu hay phớt lờ tín hiệu), nên bất kỳ giải pháp nào đề xuất lúc này đều là đoán, chưa có cơ sở.
- Tôi sửa gì: Trước khi pitch chính thức, sẽ tự ghi log thật 7-10 ngày (dự định vs thực tế + có đặt hẹn giờ hay không + có phớt lờ tín hiệu hay không) để: (1) thay số ví dụ bằng số thật, (2) xác nhận rõ bottleneck là (a) thiếu tín hiệu hay (b) biết mà vẫn tiếp tục. Đây là điều kiện bắt buộc trước khi trình bày card này với nhóm.

### Self-check nộp phần 01
- [X] Có 5+ problems + top 3 Cards đủ field
- [X] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [X] Đã chọn 1 card pitch + câu hỏi challenge
