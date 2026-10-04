# Track1_Day17_2A202602499_LeThanhTung

## 1. Thông tin cá nhân và nhóm

- **MHV:** 2A202602499
- **Họ tên:** Lê Thanh Tùng
- **Tên nhóm:** Aura
- **Thành viên nhóm:**
  - Lê Thanh Tùng — 2A202602499
  - Nguyễn Khánh Duy — 2A202602403
  - Cao Đức Hiệp — 2A202602550
- **Case đã chọn:** Case B — AI Notes: Personal Learning Notes

> Solution directive (nguyên văn): Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu "Chưa hiểu", hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu.
>
> Trigger: học viên hoàn thành bài học · Input: nội dung bài, highlights, điểm "Chưa hiểu", câu hỏi và ghi chú cá nhân · AI action: chọn lọc, nhóm và tổ chức thông tin · Output: bản ghi chú cá nhân có cấu trúc · User control: học viên chỉnh sửa và xác nhận trước khi lưu.

## 2. Problem Hypothesis Brief (Chặng 1 — của nhóm)

> **Bản nháp cá nhân của Lê Thanh Tùng**, sẽ gộp với Nguyễn Khánh Duy và Cao Đức Hiệp. Mọi nội dung dưới đây là hypothesis, chưa phải fact về user.

### 2.1 Solution → capability trung tính

- **Capability trung tính:** sau khi học xong một bài, học viên có trong tay một bản ghi lại những gì mình cần nhớ và cần quay lại, được tổ chức từ chính những gì họ đã chú ý trong lúc học, để dùng lại sau này.
- **Phần đang gắn với cách triển khai:** "AI Notes", nút highlight, nút "Chưa hiểu", bước AI tự chọn lọc và nhóm, bước xác nhận trước khi lưu. Nhóm chưa chứng minh đây là cách duy nhất.
- **Giả định ngầm cần kiểm tra:** học viên đã có dấu vết (highlight, ghi chú) để AI dùng, và họ thật sự cần một bản ghi chú có cấu trúc.

### 2.2 Change: chuỗi thay đổi kỳ vọng

Solution → học viên highlight, đánh dấu, ghi chú trong lúc học → AI tạo bản ghi chú sau bài → học viên đọc, sửa, lưu → học viên quay lại ôn bằng ghi chú này → nhớ và hiểu bài tốt hơn → **Outcome**

1. **Output (nhóm tạo ra):** bản ghi chú có cấu trúc sau mỗi bài.
2. **Hành vi phải đổi:** học viên để lại dấu vết trong lúc học và dành thời gian xác nhận sau bài; sau đó thực sự mở lại ghi chú khi ôn.
3. **Outcome (chỉ ảnh hưởng được):** học viên ôn lại hiệu quả hơn, nhớ được nội dung, giải quyết được chỗ chưa hiểu.
4. **Điểm yếu của chuỗi:** nếu học viên không highlight, không bao giờ mở lại ghi chú, hoặc đã có cách ghi riêng, solution không tạo ra outcome.

### 2.3 Actor

| Actor | Đang làm gì | Pain / hậu quả có thể có | Hưởng lợi thế nào |
|---|---|---|---|
| Learner | Học bài, tự ghi chú ở ngoài (vở, Notion, Docs), thỉnh thoảng ôn lại | Ghi chú rời rạc, mất công tổng hợp, không quay lại được chỗ chưa hiểu | Có sẵn tư liệu ôn, tiết kiệm công sắp xếp |
| Instructor | Dạy và trả lời câu hỏi | Học viên quên nội dung, hỏi lại điều đã dạy | Học viên chuẩn bị tốt hơn cho buổi sau |
| Coach / mentor | Hỗ trợ học viên chưa theo kịp | Không biết học viên đang vướng ở đâu | Có bối cảnh về chỗ học viên chưa hiểu (hưởng lợi gián tiếp) |

- **Actor điều tra trước: Learner.**
- **Lý do:** learner vừa là người dùng trực tiếp, vừa là người mang pain và là người phải đổi hành vi (để lại dấu vết, xác nhận, ôn lại). Instructor và coach chỉ hưởng lợi gián tiếp nên điều tra sau.

### 2.4 Situation & Job

- **Tình huống:** học viên vừa học xong một bài, hoặc vài ngày sau cần nhớ lại bài đó (để làm bài tập, trước buổi tiếp theo, hoặc trước kiểm tra).
- **Mô tả:** Khi vừa học xong một bài có nhiều nội dung, học viên đang cố giữ lại những gì cần nhớ và đánh dấu những chỗ còn chưa hiểu, bằng cách tự ghi chú, chụp màn hình hoặc nhớ trong đầu, rồi tự quay lại xem khi cần.
- **JTBD:** Khi tôi học xong một bài, tôi muốn giữ lại những điều quan trọng và những chỗ tôi chưa hiểu ở dạng dễ xem lại, để có thể ôn và hỏi đúng chỗ khi cần mà không phải học lại từ đầu.

### 2.5 Pain: hai cách giải thích cạnh tranh

- **Pain A (ghi chú tốn công và rời rạc):** Khi học xong một bài, học viên khó giữ lại và tổ chức được những điều quan trọng vì vừa nghe vừa ghi nên bị phân tâm, ghi chú rời rạc và mất công sắp xếp lại, dẫn đến việc không ôn lại được hoặc phải xem lại cả bài.
- **Pain B (cạnh tranh, không có thói quen hoặc động lực quay lại):** Khi học xong một bài, học viên đã có ghi chú đủ dùng nhưng ít khi mở lại vì không có lịch ôn, không có áp lực, hoặc việc ôn không gắn với việc phải làm, dẫn đến việc quên dù ghi chú vẫn còn đó.
- **Khả năng thứ ba cần giữ:** học viên không cần ghi chú riêng vì đã dùng slide, bản ghi có sẵn hoặc hỏi lại giảng viên khi cần.
- **Chọn điều tra trước (bản cá nhân): A.**

**Gộp với Duy và Hiệp.** Pain của 3 thành viên gom thành 4 nhánh giải thích, chưa phải 4 pain độc lập:

| Nhánh | Barrier | Nguồn |
|---|---|---|
| **P1. Dấu vết rải rác, không có bản tập hợp** | Highlight, comment, ảnh chụp, link, giấy nằm nhiều nơi; cuối buổi không gom được thành một bản | Tùng A; Duy 1; Hiệp 1, 4, 5 |
| **P2. Quá tải lúc nghe giảng** | Vừa hiểu vừa chép nên chỉ kịp ký hiệu, viết tắt hoặc bỏ lỡ câu hỏi; sau đó đọc lại không hiểu | Duy 3; Hiệp 2, 3 |
| **P3. Không có thói quen hoặc động lực ôn lại** | Ghi chú có sẵn nhưng không có nhắc nhở hay gắn với việc phải làm, nên bị bỏ xó | Tùng B; Hiệp 6; Duy 1 |
| **P4. Không biết ưu tiên ôn chỗ nào** | Không phân biệt được chỗ hiểu rõ và chỗ lơ mơ, nên ôn dàn trải từ đầu | Duy 2 |

Quan hệ giữa các nhánh: P2 có thể là nguyên nhân thượng nguồn của P1 (ghi vội nên rời rạc); P3 và P4 là hạ nguồn (có bản ghi rồi nhưng không dùng). Cả 4 đều giả định học viên **cần** ghi chú tốt hơn. Chưa ai viết giả thuyết ngược lại: học viên đã đủ dùng với slide, bản ghi hoặc tra lại khi cần (khả năng thứ ba ở trên). Giữ khả năng này để Big 3 có thể bác bỏ.

- **Chọn điều tra trước (nhóm): P1 làm Pain A, P3 làm Pain B cạnh tranh.**
- **Lý do:** solution (gom và cấu trúc ghi chú) chỉ có giá trị nếu P1 thật. Câu hỏi đáng sợ là P3: nếu học viên có ghi chú tạm đủ dùng nhưng không bao giờ mở lại, một bản ghi chú đẹp hơn cũng không đổi được hành vi. P2 và P4 giữ làm câu hỏi đào sâu vì chúng giải thích vì sao P1 xảy ra.

### 2.6 Evidence

| Cần kiểm tra | Làm nhóm tin hơn | Làm nhóm nghi ngờ / bác bỏ |
|---|---|---|
| Situation có thật | Kể được một bài học gần đây, mô tả cụ thể cách họ ghi lại hoặc đánh dấu | Không ghi gì, hoặc chỉ học để làm xong bài |
| Pain có ý nghĩa | Từng không tìm được thứ cần nhớ, hoặc phải xem lại cả bài để tìm | Ghi nhanh là đủ dùng, không có gì thất lạc |
| Workaround tồn tại | Tự ghi bằng Notion, Docs, vở; chụp màn hình; dành thời gian sắp xếp lại | Không có workaround, không bận tâm |
| Consequence tồn tại | Làm bài sai hoặc bị trễ vì không nhớ; phải hỏi lại điều đã học | Quên thì tra lại nhanh, không để lại hậu quả |
| Pattern có lặp | Xảy ra với nhiều bài và nhiều khóa | Chỉ một lần, bài đặc biệt |

### 2.7 Chốt Problem Hypothesis

- **Problem Hypothesis mang sang Chặng 2 (bản nhóm):** Sau buổi học, học viên có dấu vết ở nhiều nơi (highlight, comment, ảnh chụp, giấy, link) nhưng không có một bản tập hợp dùng được để ôn, nên phải mất công gom lại hoặc bỏ xó, dẫn đến quên điều cần nhớ và các câu hỏi chưa được làm rõ.
- **Điều phải đúng để đứng vững:**
  - Học viên thực sự từng cần tìm lại một điều đã học và gặp khó.
  - Họ có để lại dấu vết trong lúc học (highlight, ghi chú, đánh dấu).
  - Họ đã tự bỏ công sức cho một workaround.
  - Họ có mở lại ghi chú khi ôn (loại trừ B).
- **Điều khiến nhóm sửa hoặc bác bỏ:**
  - Học viên kể rằng họ gần như không ghi chú hoặc không ôn lại.
  - Ghi chú hiện tại họ dùng là đủ, không thấy khó.
  - Họ không muốn dành thêm thời gian xác nhận một bản AI tạo ra.
  - Khi cần nhớ, họ chỉ cần mở slide hoặc hỏi lại là xong.

### 2.8 Solution Parking Lot

| # | Hướng giải quyết | AI / Không AI |
|---|---|---|
| 1 | Bản ghi chú có cấu trúc do AI tạo từ highlight và ghi chú (directive hiện tại) | AI |
| 2 | Mẫu ghi chú trống theo cấu trúc cố định (3 ý chính, 1 chỗ chưa hiểu, 1 câu hỏi) để học viên tự điền cuối bài | Không AI |
| 3 | Cuối bài, hỏi nhanh: "Chỗ nào chưa hiểu nhất?" rồi gom lại thành danh sách | Không AI |
| 4 | Nhắc ôn lại theo lịch ngắt quãng, gắn với các điểm "Chưa hiểu" | AI hoặc không AI |
| 5 | AI chỉ trả lời đúng chỗ chưa hiểu khi học viên hỏi, không tạo ghi chú tổng | AI |

### 2.9 Checkpoint 1 (tự kiểm)

- Đi đủ chuỗi Solution → Evidence: đã có.
- Hai cách giải thích cạnh tranh (A, B): đã có.
- Điều có thể làm giả thuyết sai: đã nêu ở 2.7.
- **Cần nhóm góp ý:** Duy và Hiệp có thể chọn actor khác hoặc Pain khác. Khi gộp, cần giữ những cách giải thích khác nhau.

## 3. Conversation Guide phiên bản cuối (sau khi luyện)

### 3.1 Big 3 (nháp)

| # | Điều cần học | Evidence cần tìm | Điều gì khiến nhóm xem lại giả thuyết |
|---|---|---|---|
| 1 | Sau buổi học họ thực sự giữ lại gì, ở bao nhiêu nơi, và có từng không tìm lại được thứ cần không (P1) | Chuỗi hành động cụ thể ở buổi gần nhất, công sức gom, một lần mất hoặc thiếu thông tin có hậu quả | Họ chỉ dùng một nơi, hoặc gom lại nhanh và chưa từng mất gì |
| 2 | **(Đáng sợ)** Lần gần nhất họ mở lại ghi chú là khi nào, vì lý do gì, và có mở không (P3) | Hành vi mở lại gắn với việc phải làm (bài tập, kiểm tra); hoặc ghi chú bị bỏ xó | Họ ôn bằng slide gốc hoặc bản ghi chứ không bằng ghi chú; không mở lại cũng không sao |
| 3 | Lúc đang học họ đã làm gì khi có câu hỏi hoặc điều chưa hiểu, và điều đó đi đâu sau buổi học (P2, P4) | Câu hỏi bị quên, hoặc được làm rõ bằng cách cụ thể nào | Họ hỏi ngay trong lớp hoặc tra ngay nên không tồn đọng |

### 3.2 Tiêu chí tuyển

Chúng tôi cần nói chuyện với người đã **học một bài hoặc buổi học (trên lớp hoặc online) và có ghi lại hay đánh dấu gì đó** trong vòng **14 ngày** gần đây.

**Recruitment check (không tính là evidence):** "Trong 2 tuần qua bạn có buổi học nào mà bạn đã ghi chú, highlight hoặc chụp lại gì đó không?" Nếu không thì đổi người.

### 3.3 Lời mở đầu

"Cảm ơn bạn đã dành thời gian. Mình đang tìm hiểu cách mọi người học và giữ lại những gì đã học. Mình không có đáp án đúng hay sai, và không có gì để bán hay đánh giá. Mình chỉ muốn nghe chuyện thật của bạn. Mình có thể ghi âm để xem lại cho chính xác, chỉ dùng cho bài học này, không chia sẻ công khai. Bạn đồng ý cho mình ghi âm không? Nếu bạn muốn dừng hoặc bỏ qua câu nào, cứ nói."

_Chỉ bấm ghi sau khi họ đồng ý._

### 3.4 Story opener

"Kể mình nghe về **buổi học gần nhất** mà bạn có ghi chú hoặc đánh dấu gì đó. Hôm đó bạn học cái gì, và bạn đã ghi lại như thế nào?"

### 3.5 Big 3 Questions

| # | Điều cần học | Câu hỏi sẽ dùng |
|---|---|---|
| 1 | Giữ lại gì, ở bao nhiêu nơi, có lần nào tìm không ra (P1) | "Sau buổi đó, những thứ bạn ghi lại đang nằm ở đâu?" → "Kể mình nghe lần gần nhất bạn cần tìm lại một điều đã học. Bạn làm gì, mất bao lâu, kết quả ra sao?" |
| 2 | **(Đáng sợ)** Lần gần nhất mở lại ghi chú (P3) | "Lần gần nhất bạn mở lại ghi chú của một buổi học là khi nào? Lúc đó bạn đang làm gì, và bạn mở để tìm gì?" → nếu chưa từng: "Vậy lần gần nhất bạn cần nhớ lại một nội dung đã học, bạn dựa vào đâu?" |
| 3 | Câu hỏi hoặc chỗ chưa hiểu lúc học đi đâu (P2, P4) | "Trong buổi đó có lúc nào bạn chưa hiểu hoặc nảy ra câu hỏi không? Lúc đó bạn làm gì? Sau đó chuyện đó ra sao?" |

### 3.6 Probe bank

- "Lúc đó chuyện gì xảy ra tiếp theo?"
- "Bạn đã làm gì?"
- "Vì sao bạn chọn cách đó?"
- "Phần nào khó nhất?"
- "Bạn đã thử cách nào khác chưa?"
- "Việc đó kéo theo hậu quả gì?"
- "Lần gần nhất trước đó là khi nào?"

Probe riêng theo chủ đề:
- Ký hiệu, viết tắt (P2): "Bạn đưa mình xem ghi chú đó được không? Cái ký hiệu này nghĩa là gì? Sau đó bạn đọc lại có hiểu không?"
- Công sức gom (P1): "Bạn mất khoảng bao lâu để gom lại? Bạn làm ở đâu?"
- Ưu tiên ôn (P4): "Khi ôn, bạn bắt đầu từ đâu? Làm sao bạn biết nên ôn phần nào?"

### 3.7 Ba phản xạ khi data lệch

| User đưa ra | Phản xạ | Cách quay lại evidence |
|---|---|---|
| Lời khen ("hay đấy") | Deflect | Cảm ơn ngắn rồi hỏi: "Hiện tại bạn đang làm việc đó thế nào?" |
| Chung chung, hứa tương lai ("mình hay ghi lắm", "sau này mình sẽ ôn") | Anchor | "Lần gần nhất chuyện đó xảy ra là khi nào?" |
| Ý tưởng, feature request ("giá mà có app tự tổng hợp") | Dig | "Điều đó giúp bạn làm được gì? Hiện tại bạn xử lý thế nào?" |

### 3.8 Nhắc bản thân khi phỏng vấn

- Không nhắc tên feature, AI, "ghi chú tự động". Không hỏi "bạn có muốn / có dùng không".
- Nói ít, nghe nhiều. Im lặng 3 giây sau câu trả lời trước khi hỏi tiếp.
- Ghi lại exact quote và hành vi cụ thể (thứ họ đã làm, không phải thứ họ nghĩ).
- Ít nhất một câu có thể làm giả thuyết yếu đi: câu Big 3 số 2 và nhánh "chưa từng mở lại".

### 3.9 Tự rà soát (checklist)

- [x] Có câu nào làm lộ solution? Không.
- [x] Có câu nào hỏi ý kiến hoặc dự đoán tương lai? Không.
- [x] Story opener neo vào "buổi học gần nhất".
- [x] Ba câu chính nối với ba điều cần học.
- [x] Có câu làm giả thuyết yếu đi (Big 3 số 2).
- [x] Interviewee đáp ứng tiêu chí tuyển (P01: học offline về cloud và CPU trong 7 ngày gần đây, có ghi chú trên Zalo).
- [x] Phân công: mỗi thành viên tự phỏng vấn một người ngoài nhóm trong buổi luyện (Tùng phỏng vấn P01).

### 3.10 Bản đã sửa sau khi luyện (phiên bản cuối)

Các chỗ sửa dựa trên lượt phỏng vấn P01 (xem mục 4 và [interview/notes.md](interview/notes.md)).

| # | Sửa ở đâu | Trước | Sau | Vì sao |
|---|---|---|---|---|
| 1 | Story opener và câu mở | Hỏi một chuỗi câu đóng ("Em có tham gia khóa học không? Có note không? Online hay offline?") rồi mới hỏi "kể lần gần nhất" | Dùng recruitment check ngay trước buổi phỏng vấn; vào thẳng story opener "Kể mình nghe về buổi học gần nhất, bạn học gì và đã làm gì lúc đó" | Câu đóng chỉ nhận "Có / Không", mất gần 1 phút đầu mà chưa có câu chuyện |
| 2 | Big 3 số 2 (mở lại ghi chú) | "Lần gần nhất bạn mở lại ghi chú là khi nào?" (ngầm giả định ghi chú dùng để ôn) | "Sau buổi học, những thứ bạn ghi lại được dùng vào việc gì?" rồi "Lần gần nhất bạn mở chúng là khi nào, để làm gì?" | P01 dùng ghi chú để hỏi chat, không để ôn. Câu cũ khóa họ vào khung "ôn lại" |
| 3 | Hậu quả | "Nếu không xem lại thì ảnh hưởng gì đến các buổi sau?" (câu giả định) | "Lần gần nhất bạn thiếu kiến thức của buổi trước nên gặp khó ở buổi sau là khi nào? Chuyện gì xảy ra?" | Câu giả định cho ra "hổng kiến thức, mất gốc", không phải sự kiện |
| 4 | Cấm hỏi về tính năng hiện có | Hỏi "Em thấy tính năng note hoặc AI Tutor hiện tại thế nào?" và "Sau khi AI tổng hợp xong…" | Bỏ cả hai. Nếu user tự nhắc đến công cụ: "Lần gần nhất bạn dùng nó là khi nào, bạn làm gì với nó?" | Hỏi ý kiến và nhắc AI tổng hợp làm lộ solution, và nhận được nhận xét giao diện, không phải evidence |
| 5 | Cách tóm tắt lại | Hay mở đầu bằng "Tức là em…" rồi diễn đạt lại theo ý mình | Chỉ nhắc lại đúng từ của họ rồi dừng: "Bạn nói 'chưa kịp hiểu', rồi sao nữa?" | Tóm tắt kiểu "Tức là em sẽ note chung và không quan tâm slide nào" dẫn dắt; P01 chỉ trả lời "Không" |
| 6 | Probe thêm | Chưa có probe cho dấu hiệu mất dữ liệu hay workaround | Thêm: "Chuyện đó xảy ra thế nào? Sau đó bạn làm gì?"; "Bạn đã làm gì để xử lý?"; "Bạn mất bao lâu?"; "Cái 'mấy bài trước' đó là bài nào, lần gần nhất là khi nào?" | Bỏ lỡ câu "slide bị xóa" và "mấy bài trước cũng có" |
| 7 | Big 3 số 1 | Chỉ hỏi ghi ở đâu | Thêm "Bạn ghi những thứ đó để làm gì sau đó?" | Để lộ mục đích thật của ghi chú (ở P01: đầu vào cho chat) |
| 8 | Câu đóng "có lần nào… không?" | "Có lần nào chat không hiểu ký hiệu của bạn không?" | "Kể mình nghe lần gần nhất bạn viết ghi chú nhanh rồi đọc lại. Bạn thấy sao?" | Câu đóng chỉ ra "Gần như là không" |

**Cập nhật nhánh giả thuyết sau 1 buổi phỏng vấn (chưa đủ để kết luận):**
- P1 (rải rác) và P3 (bỏ xó) yếu đi với P01. Ghi chú được dùng ngay làm đầu vào hỏi chat.
- P2 (thuật ngữ trôi qua lúc giảng, phải tra sau) có bằng chứng: 5–10 phút mỗi phần, 30–40 phút mỗi bài.
- Thêm nhánh **P5: ghi chú là bước đệm để hỏi AI, không phải tài liệu ôn.** Cần kiểm tra thêm với người khác.
- Cần phỏng vấn thêm người ghi chú ở nhiều nơi để kiểm tra P1.

## 4. Practice Reflection

1. **Câu hỏi nào đã giúp user kể một tình huống cụ thể?**
   "Hãy kể lần gần nhất em học bài, lúc đó đang học chủ đề gì và trong hoàn cảnh nào?" (01:06). P01 kể ngay buổi cloud và CPU, mục tiêu tạo tài khoản cloud. Hai câu sau cũng ra chi tiết hành vi: "Khi học một đoạn phức tạp mà không hiểu ngay thì em làm gì?" (ra workaround copy lên chat) và "Em đã mất bao nhiêu thời gian và công sức để tra phần chưa hiểu?" (ra 5–10 phút mỗi phần, 30–40 phút mỗi bài).
2. **Chỗ nào cần làm tốt hơn ở lần phỏng vấn thật?**
   - **Mở đầu bằng câu đóng:** gần 1 phút đầu là "Em có tham gia khóa học không?", "Em có note không?", "Online hay offline?" chỉ nhận "Có / Không", đến 01:06 mới có story opener.
   - **Lộ solution và hỏi ý kiến:** hỏi "Em thấy tính năng note hoặc AI Tutor hiện tại thế nào?" (05:52) và "Sau khi AI tổng hợp xong thì em có check lại không?" (06:31). Nhận được nhận xét giao diện, không phải evidence về pain.
   - **Dẫn dắt khi tóm tắt:** "Tức là em chưa kịp hiểu cái khái niệm đấy, em note lại và chưa hiểu thì thầy đã lướt qua rồi" và "Tức là em sẽ note chung và em cũng không quan tâm lắm đến nó thuộc slide nào". Tôi nói thay ý của P01, và họ chỉ đáp "Vâng", "Không".
   - **Câu giả định:** "Nếu không tổng hợp hay xem lại được thì ảnh hưởng gì đến các buổi sau?" cho ra "hổng kiến thức, mất gốc", là dự đoán chứ không phải sự kiện.
   - **Bỏ lỡ tín hiệu:** P01 nói "người ta xóa mất cái slide em tương tác" (mất dữ liệu thật) và "mấy bài trước cũng có" nhưng tôi không hỏi tiếp. Ghi chú được dùng làm đầu vào cho chat ("Em note lại em phải hỏi chat mà") cũng chưa đào sâu mà quay sang hỏi ký hiệu viết tắt.
   - **Câu "có lần nào… không?":** dễ nhận "Gần như là không", không có câu chuyện.
3. **Nhóm đã sửa Conversation Guide ở đâu và vì sao?**
   Chi tiết ở mục 3.10. Tóm tắt: (a) bỏ chuỗi câu đóng, vào thẳng story opener; (b) đổi câu "mở lại ghi chú" thành "ghi chú được dùng vào việc gì" vì P01 dùng ghi chú để hỏi chat, không để ôn; (c) thay câu hậu quả giả định bằng "lần gần nhất thiếu kiến thức nền gây khó ở buổi sau"; (d) cấm hỏi ý kiến về tính năng hiện có và cấm nhắc AI tổng hợp; (e) chỉ nhắc lại đúng từ của user thay vì "Tức là…"; (f) thêm probe cho mất dữ liệu và workaround. Mục đích chung là giảm dẫn dắt và lấy sự kiện thật thay vì dự đoán.

## 5. AI Support Log

| AI đã giúp gì | Điểm sai / hời hợt | Mình đã tự sửa thế nào |
|---|---|---|
| Dựng cấu trúc repo và khung README theo yêu cầu nộp bài | Lần đầu dựng theo Case C vì đề bài ban đầu là Case C; sau đó đổi sang Case B nên phải viết lại phần Problem Hypothesis | Đổi toàn bộ phần mô tả case và giả thuyết sang Case B |
| Soạn nháp Problem Hypothesis cho Case B | Nháp chọn actor và Pain A, B là suy luận từ đề bài, chưa có evidence. Cả 4 nhánh pain đều ngầm giả định học viên cần ghi chú tốt hơn | Đưa thêm khả năng "học viên đã đủ dùng" để Big 3 có thể bác bỏ, và đối chiếu với kết quả phỏng vấn (mục 3.10) |
| Gộp pain của Duy và Hiệp thành 4 nhánh P1–P4 và đề xuất Big 3 | Việc gom 9 pain thành 4 nhánh là phán đoán của AI. Hiệp 3 (ký hiệu viết tắt) bị gộp vào P2 mà chưa hỏi nhóm | Giữ ghi chú nguồn của từng nhánh để nhóm có thể tách lại |
| Soạn Conversation Guide | Big 3 số 2 ("lần gần nhất mở lại ghi chú") giả định ghi chú dùng để ôn, và có các câu đóng kiểu "có lần nào… không?" và câu giả định về hậu quả. Cả 3 đều cho ra câu trả lời nông khi phỏng vấn thật | Sửa các câu này sau buổi luyện (mục 3.10) |
| Phân tích transcript phỏng vấn P01 và soạn Interview Record, Reflection | AI chỉ có transcript chữ, không nghe được ngữ điệu hay ngập ngừng; transcript không có đoạn xin phép ghi âm nên AI không tự xác nhận được consent | Đối chiếu lại từng câu trích với transcript; tự xác nhận và điền consent (đã xin phép trước khi ghi); đánh dấu rõ chỗ nào là kết quả từ 1 người, chưa đủ để kết luận |
