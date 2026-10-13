# Track 1 - Day 25 - AI Team Lab

- **Team:** TeamVinTay (bản hiện tại do Dương Hải Minh thực hiện một mình; cần giảng viên chấp thuận quy mô cá nhân).
- **Thành viên:** Dương Hải Minh.
- **Tên dự án:** Trợ lý học tập AI hỏi đáp PDF có trích dẫn (dự án mẫu, cần xác nhận đúng dự án thực tế).
- **Link sản phẩm/demo:** Chưa có.

## Bài nộp

- **PDF:** [Day25_AI-Team-Lab_TeamVinTay.pdf](Day25_AI-Team-Lab_TeamVinTay.pdf) (tối đa 4 trang).
- **GitHub repository:** [Track1_Day25_TeamVinTay_DuongHaiMinh](https://github.com/minhdh329/Track1_Day25_TeamVinTay_DuongHaiMinh) (trang mở được nhưng hiện repository đang trống).

## Phase 0 - Chốt phạm vi và cách làm

> **Lưu ý:** README này dùng dự án mẫu **Trợ lý học tập AI** vì chưa có thông tin về dự án AI thực tế của người học. Hãy thay nội dung dự án và mục tiêu nếu dự án thật khác.

### Thông tin nhóm

- **Thành viên:** 1 người (hình thức làm cá nhân)
- **Họ tên:** Dương Hải Minh
- **Người tổng hợp/phụ trách repo:** Dương Hải Minh

### Dự án áp dụng

- **Tên dự án:** Trợ lý học tập AI
- **Mô tả:** Công cụ cho phép người học tải tài liệu bài giảng dạng PDF, đặt câu hỏi và nhận câu trả lời dựa trên tài liệu, kèm trích dẫn nguồn để kiểm chứng.
- **Phạm vi của lab:** Chỉ phân tích và lập kế hoạch cho dự án này; không tạo một case study khác để làm lab.

### Mục tiêu hiện tại (1-3 tháng)

Xây dựng và kiểm thử một MVP có thể tải tài liệu PDF, trả lời câu hỏi dựa trên nội dung tài liệu và hiển thị nguồn tham chiếu. Đánh giá MVP bằng bộ 20 câu hỏi mẫu, ghi nhận câu trả lời được hỗ trợ đầy đủ, hỗ trợ một phần hoặc không được tài liệu hỗ trợ; dùng kết quả để xác định các cải thiện tiếp theo.

**Tiêu chí hoàn thành đề xuất:** MVP thực hiện được luồng tải PDF -> đặt câu hỏi -> nhận câu trả lời có nguồn; hoàn tất đánh giá 20 câu hỏi và lưu kết quả để xem xét.

### Cách làm và nơi lưu artefact

- **Format làm bài:** Google Slides; xuất bản cuối thành một file PDF theo yêu cầu của bài lab.
- **Nơi lưu bản làm việc:** Repository GitHub này. Cập nhật README và artefact xuyên suốt lab.
- **Người chịu trách nhiệm cập nhật:** Người thực hiện repository.

### Gate 0 - Scope đã rõ

- [x] Đã chọn một dự án áp dụng (dự án mẫu, cần xác nhận/thay bằng dự án thật nếu có).
- [x] Đã xác định mục tiêu hiện tại và tiêu chí hoàn thành đề xuất.
- [x] Đã chỉ định người tổng hợp và phụ trách repository.
- [ ] Đã được giảng viên chấp thuận hình thức làm cá nhân.

**Trạng thái:** Phạm vi dự thảo đã xác định; Gate 0 chỉ hoàn tất sau khi xác nhận dự án thực tế và được chấp thuận làm cá nhân.

## Phase 1 - Stakeholder Map và chiến lược

> **Cách làm cá nhân:** Tự lập danh sách stakeholder trước, sau đó rà soát lại như một bước phản biện. Các stakeholder và stance dưới đây là giả định cho dự án mẫu Trợ lý học tập AI, chưa phải thông tin đã xác minh từ người thật.

### 1. Danh sách stakeholder cụ thể

| Stakeholder | Vai trò/liên hệ cụ thể với dự án | Ảnh hưởng | Quan tâm | Quadrant tạm xếp | Stance tạm tính |
|---|---|---|---|---|---|
| Giảng viên hướng dẫn/mentor đang review MVP | Góp ý chất lượng học thuật và có thể giới thiệu lớp thử nghiệm | Cao | Cao | Champion | Ủng hộ mạnh (giả định, cần xác nhận) |
| Đại diện nhóm sinh viên sẽ dùng thử MVP | Dùng thử luồng tải tài liệu và hỏi đáp, cung cấp phản hồi | Thấp | Cao | Supporter | Ủng hộ mạnh (giả định, cần xác nhận) |
| Trưởng bộ môn/người phê duyệt pilot trong một lớp | Có thể cho phép hoặc từ chối thử nghiệm trong lớp | Cao | Thấp | Blocker | Trung lập/chưa xác minh; có rủi ro trì hoãn |
| Cán bộ phụ trách CNTT hoặc bảo vệ dữ liệu của trường | Rà soát nơi lưu PDF, dữ liệu người dùng và quyền truy cập | Cao | Thấp | Blocker | Thận trọng/chưa xác minh; có thể yêu cầu điều kiện bảo mật |
| Giảng viên sở hữu tài liệu môn học được dùng để thử nghiệm | Quyết định có cho phép dùng tài liệu và trích dẫn nội dung hay không | Cao | Cao | Champion theo quadrant; stance cần kiểm tra riêng | Chưa xác minh |
| Cán bộ thư viện/phụ trách hỗ trợ học tập số | Có thể góp ý nguồn tài liệu và cách sinh viên tiếp cận công cụ | Thấp | Thấp | Bystander | Chưa xác minh |

**Quy ước:** Influence và Interest dùng để đặt stakeholder vào quadrant. Stance là thái độ thực tế (ủng hộ, trung lập, chưa ủng hộ/phản đối), cần xác minh riêng qua trao đổi; nhãn quadrant không chứng minh stance.

### 2. Stakeholder Map

|  | Interest thấp | Interest cao |
|---|---|---|
| **Influence cao** | **Blocker:** Trưởng bộ môn/người phê duyệt pilot; cán bộ CNTT/bảo vệ dữ liệu. Giữ liên hệ và xử lý sớm yêu cầu phê duyệt, bảo mật. | **Champion:** Giảng viên hướng dẫn/mentor; giảng viên sở hữu tài liệu. Làm việc sát, xin phản hồi và tận dụng hỗ trợ nếu stance thực tế xác nhận điều đó. |
| **Influence thấp** | **Bystander:** Cán bộ thư viện/hỗ trợ học tập số. Theo dõi, chỉ cập nhật khi có nội dung liên quan. | **Supporter:** Đại diện nhóm sinh viên dùng thử. Cập nhật tiến độ và khai thác phản hồi của người dùng. |

### 3. Bốn stakeholder ưu tiên và hành động 1-2 tuần tới

Hai stakeholder được giả định đang ủng hộ mạnh và hai stakeholder có rủi ro cản trở được chọn dưới đây. Đây là giả thuyết làm việc; cần thay bằng stance thực tế sau khi trao đổi.

| Stakeholder ưu tiên | Họ quan tâm điều gì? | Có thể giúp/cản trở thế nào? | Hành động cụ thể trong 1-2 tuần tới |
|---|---|---|---|
| Giảng viên hướng dẫn/mentor (**ủng hộ mạnh - giả định**) | Tính hữu ích cho học tập, độ chính xác và khả năng kiểm chứng câu trả lời | Có thể góp ý MVP, kết nối lớp thử nghiệm hoặc giới thiệu người duyệt pilot | Gửi bản demo và 3 câu trả lời có trích nguồn; xin một buổi review 20 phút và đề nghị giới thiệu người có thể duyệt pilot nếu thấy phù hợp. |
| Đại diện nhóm sinh viên dùng thử (**ủng hộ mạnh - giả định**) | Câu trả lời dễ hiểu, tiết kiệm thời gian, nguồn trích dẫn đúng | Có thể thử luồng sử dụng thật và chỉ ra lỗi hoặc nhu cầu chưa đáp ứng | Mời 3-5 sinh viên thử cùng một bộ câu hỏi mẫu; ghi lại điểm gây khó hiểu và xin phép dùng phản hồi ẩn danh để cải thiện MVP. |
| Trưởng bộ môn/người duyệt pilot (**rủi ro cần thuyết phục**) | Rủi ro ảnh hưởng lớp học, thời lượng thử nghiệm và giá trị sư phạm | Có thể cho phép hoặc trì hoãn thử nghiệm trong lớp | Gửi đề xuất pilot một trang nêu rõ mục tiêu, phạm vi nhỏ, thời lượng, cách đo phản hồi và phương án dừng; xin quyết định hoặc yêu cầu cần bổ sung. |
| Cán bộ CNTT/bảo vệ dữ liệu (**rủi ro cần xử lý**) | Dữ liệu PDF được lưu ở đâu, ai truy cập, thời hạn lưu và thông tin cá nhân | Có thể yêu cầu giới hạn dữ liệu hoặc không cho dùng hệ thống hiện tại | Chuẩn bị sơ đồ luồng dữ liệu và danh sách dữ liệu thu thập; hỏi trước yêu cầu về lưu trữ, xóa dữ liệu và tài liệu được phép dùng, chưa đưa dữ liệu nhạy cảm vào pilot khi chưa được duyệt. |

### Gate 1 - Stakeholder Map có thể hành động

- [x] Có ít nhất 6 stakeholder cụ thể gắn với dự án mẫu.
- [x] Đã xếp từng stakeholder theo Influence x Interest.
- [x] Đã ghi stance riêng với quadrant và đánh dấu các stance chưa được xác minh.
- [x] Có 4 hành động cụ thể cho 4 stakeholder ưu tiên, gồm thời hạn 1-2 tuần.
- [ ] Xác minh danh tính, mức ảnh hưởng, mức quan tâm và stance với stakeholder thực tế của dự án.

**Trạng thái:** Đạt yêu cầu trên bản giả định để tiếp tục lab; chỉ xem là kết quả thực tế sau khi thay/kiểm chứng stakeholder của dự án thật.

## Phase 2 - Pitch Conclusion First và RACI Matrix

> **Cách làm cá nhân:** Soạn pitch, tự nêu phản biện có khả năng xảy ra, viết lại pitch theo cách của mình rồi kiểm tra RACI. Vì đây là bài làm cá nhân, Dương Hải Minh có thể vừa là Responsible vừa là Accountable ở một công việc; mỗi hàng vẫn chỉ có đúng một Accountable.

### 1. Pitch nháp gửi giảng viên hướng dẫn/mentor

**Kết luận/đề xuất:** Xin một buổi review 20 phút để góp ý kế hoạch thử nghiệm giới hạn cho Trợ lý học tập AI trước khi xin phép dùng trong lớp.

**Lý do:** MVP tập trung vào một luồng rõ ràng: hỏi đáp trên tài liệu bài giảng được phép sử dụng và hiển thị nguồn để người học kiểm tra. Thử nghiệm nhỏ giúp phát hiện lỗi về câu trả lời, trích dẫn và trải nghiệm trước khi cân nhắc mở rộng.

**Bằng chứng:** Hiện đã có phạm vi MVP và kế hoạch đánh giá bằng 20 câu hỏi mẫu. Chưa có kết quả kiểm thử thực tế hoặc số liệu chứng minh độ chính xác; vì vậy chưa khẳng định hệ thống đã đáng tin cậy hay sẵn sàng triển khai.

**Small ask:** Trong buổi review, xin mentor góp ý bộ tiêu chí đánh giá và cho biết ai cần phê duyệt tài liệu/pilot trước khi mời người học thử.

### 2. Phản biện có khả năng xảy ra và cách xử lý

**Phản biện:** “Chưa có bằng chứng AI trả lời chính xác; tài liệu môn học và dữ liệu người dùng cũng có thể gặp rủi ro.”

**Trả lời dựa trên bằng chứng và giảm rủi ro:** Đồng ý rằng hiện chưa có kết quả kiểm thử để kết luận về độ chính xác. Trước khi thử nghiệm, chỉ dùng tài liệu công khai hoặc đã được chủ sở hữu cho phép; hỏi cán bộ CNTT/bảo vệ dữ liệu về lưu trữ và xóa dữ liệu. Chạy bộ 20 câu hỏi, đối chiếu câu trả lời với nguồn, ghi rõ câu đúng/thiếu/sai; không đưa dữ liệu nhạy cảm vào pilot. Nếu chưa có phê duyệt hoặc không truy được nguồn cho câu trả lời, chưa triển khai pilot.

### 3. Pitch cá nhân sau phản biện

> Em xin một buổi review 20 phút để kiểm tra kế hoạch thử nghiệm giới hạn cho Trợ lý học tập AI. MVP dự kiến trả lời câu hỏi dựa trên tài liệu được phép dùng và kèm nguồn để người học đối chiếu; tuy nhiên, hiện nhóm chưa có kết quả kiểm thử thực tế nên em chưa khẳng định độ chính xác. Em sẽ đánh giá bằng 20 câu hỏi mẫu, chỉ dùng tài liệu đã được cho phép và hỏi bộ phận phụ trách về yêu cầu dữ liệu trước khi thử nghiệm. Trong buổi review, em mong nhận góp ý cho tiêu chí đánh giá và xác định người cần phê duyệt bước pilot.

### 4. RACI Matrix cho 1-2 tháng tới

| Công việc | Dương Hải Minh (PM/Builder) | Giảng viên hướng dẫn | Giảng viên sở hữu tài liệu | Cán bộ CNTT/bảo vệ dữ liệu | Sinh viên dùng thử | Người duyệt pilot |
|---|---|---|---|---|---|---|
| Chốt use case và tiêu chí nghiệm thu MVP | R/A | C | C | I | C | I |
| Xin phép dùng tài liệu môn học cho thử nghiệm | R | C | A | C | I | I |
| Chốt cách lưu trữ, truy cập và xóa dữ liệu | R | I | C | A | I | C |
| Xây MVP hỏi đáp PDF và hiển thị trích dẫn | R/A | C | C | C | I | I |
| Kiểm thử bằng 20 câu hỏi và ghi nhận usability | R/A | C | C | I | C | I |
| Phê duyệt và thực hiện pilot giới hạn | R | C | C | C | I | A |

**Chú giải:** R = Responsible (người trực tiếp thực hiện); A = Accountable (người chịu trách nhiệm cuối); C = Consulted (cần hỏi ý kiến); I = Informed (cần được thông báo). Mỗi công việc có đúng một A. Với vai trò duyệt pilot, người có thẩm quyền thực tế cần được xác định trước khi bắt đầu công việc đó.

### Gate 2 - Pitch rõ, RACI không mơ hồ

- [x] Pitch mở đầu bằng đề xuất, có lý do, nêu đúng bằng chứng hiện có và đưa ra small ask cụ thể.
- [x] Có một phản biện thực tế và câu trả lời dựa trên giới hạn bằng chứng cùng hành động giảm rủi ro.
- [x] Đã viết lại pitch cá nhân sau phản biện.
- [x] RACI có 6 công việc quan trọng, mỗi công việc có đúng một Accountable.
- [ ] Xác nhận người có thẩm quyền phê duyệt pilot và các yêu cầu dữ liệu/tài liệu thực tế.

**Trạng thái:** Bản Phase 2 đã hoàn chỉnh theo dự án mẫu; các phê duyệt và dữ liệu thực tế vẫn cần được xác minh trước khi triển khai pilot.

## Phase 3 - Thiết kế AI Team

> **Bối cảnh:** Dự án hiện được lập kế hoạch như một MVP do một người phụ trách. Thiết kế dưới đây chọn năng lực cần có ở giai đoạn này, không giả định người phụ trách đã có đầy đủ chuyên môn và không tạo thêm chức danh chỉ để làm sơ đồ đẹp.

### 1. AI Team Architecture

**Lựa chọn: Embedded (năng lực AI nằm trong team sản phẩm).** Với một MVP và một người phụ trách, không cần lập AI hub phục vụ nhiều team như mô hình Centralized, cũng chưa có nhiều team cần phối hợp theo Hybrid. Dương Hải Minh phụ trách sản phẩm và tích hợp AI trong cùng một squad; chuyên gia bên ngoài tham gia theo nhu cầu review, không phải một team AI riêng.

### 2. Core Roles và capability gap

| Năng lực/vai trò | Phân loại | Người phụ trách hiện tại | Ghi chú |
|---|---|---|---|
| Product owner / điều phối pilot | Core - cần ngay | Dương Hải Minh | Chốt use case, tiêu chí MVP, trao đổi với mentor và xin phê duyệt pilot. |
| AI application / RAG builder | Core - cần ngay | Dương Hải Minh | Xây luồng hỏi đáp tài liệu và trích dẫn nguồn; cần tự đánh giá kỹ năng triển khai, chưa có dữ liệu để kết luận mức thành thạo. |
| Evaluation và quản lý chất lượng dữ liệu | Core - cần ngay | Dương Hải Minh thực hiện; mentor và người dùng thử phản biện | Tạo bộ 20 câu hỏi, kiểm tra câu trả lời theo nguồn và ghi nhận lỗi; cần người độc lập review trước pilot. |
| Chuyên gia nội dung/giáo dục | Extended - cần khi kiểm chứng nội dung | Chưa có người xác nhận | Giảng viên sở hữu tài liệu hoặc mentor xác nhận tài liệu và tiêu chí câu trả lời phù hợp. |
| Bảo mật và quản trị dữ liệu | Extended - cần trước khi dùng dữ liệu không công khai | Chưa có người xác nhận | Cán bộ CNTT/bảo vệ dữ liệu rà soát lưu trữ, quyền truy cập và xóa dữ liệu. |
| MLOps/monitoring production | Chưa ưu tiên ở giai đoạn MVP | Chưa phân công | Xem xét lại nếu pilot được duyệt và có nhu cầu vận hành liên tục; chưa cần tuyển vai trò riêng lúc này. |

### 3. Priority Resourcing

| Capability gap ưu tiên | Cách bổ sung | Vì sao chọn cách này | Khi nào cần |
|---|---|---|---|
| Review độc lập về tính đúng đắn và hữu ích trong học tập | **Partner:** nhờ giảng viên/mentor review bộ câu hỏi và kết quả; mời sinh viên dùng thử để góp ý trải nghiệm | MVP nhỏ, nhu cầu review theo đợt; hợp tác với người hiểu nội dung và người dùng phù hợp hơn tuyển một chuyên gia toàn thời gian. | Trước pilot; nếu chưa có reviewer hoặc người dùng thử, chưa kết luận MVP đáp ứng nhu cầu. |
| Rà soát quyền dùng tài liệu và cách xử lý dữ liệu | **Partner:** làm việc với giảng viên sở hữu tài liệu và cán bộ CNTT/bảo vệ dữ liệu của trường | Quyền cho phép và quy định lưu trữ phụ thuộc vào tài liệu/hệ thống của trường; người trong tổ chức phù hợp hơn thuê ngoài hoặc tự suy đoán. | Trước khi tải tài liệu không công khai hoặc dữ liệu cá nhân lên hệ thống. Chỉ dùng tài liệu công khai/được phép trong lúc chờ xác nhận. |

**Quyết định nguồn lực:** Chưa Hire vì chưa có nhiều sản phẩm hoặc workload để biện minh cho nhân sự toàn thời gian. Chưa Outsource dữ liệu nhạy cảm; ưu tiên Partner để nhận review chuyên môn và phê duyệt đúng bối cảnh. Nếu tự đánh giá cho thấy thiếu năng lực xây RAG, thu hẹp MVP hoặc tìm mentor/đối tác kỹ thuật trước khi cam kết pilot.

### 4. Squad Goal

> Squad cá nhân do Dương Hải Minh phụ trách sở hữu MVP trợ lý học tập hỏi đáp PDF có trích dẫn và chịu trách nhiệm đưa dự án từ phạm vi hiện tại đến MVP được đánh giá bằng 20 câu hỏi, sẵn sàng cho pilot giới hạn khi có đủ phê duyệt.

### Gate 3 - Team Design phù hợp thực tế

- [x] Đã chọn và giải thích một kiến trúc phù hợp với squad một người và một MVP.
- [x] Đã xác định các năng lực cốt lõi cần ngay, cùng năng lực mở rộng/chưa ưu tiên.
- [x] Đã nêu capability gap và cách bổ sung bằng Partner, kèm lý do và thời điểm cần.
- [x] Đã chốt Squad Goal gắn với đầu ra có thể đánh giá và điều kiện pilot.
- [ ] Tự đánh giá năng lực RAG hiện tại và xác nhận người review nội dung, dữ liệu, bảo mật trước pilot.

**Trạng thái:** Thiết kế dự thảo phù hợp với quy mô cá nhân; Gate 3 hoàn tất khi xác nhận capability gap thực tế và các đối tác/reviewer cần thiết.

## Phase 4 - Team Health và Growth Plan 30 ngày

> **Cách làm cá nhân:** Vì squad có một người, đây là tự đánh giá ban đầu, không phải điểm trung bình của một team. Chưa có số liệu vận hành hoặc đầu ra MVP trong README, nên các điểm phản ánh mức độ có bằng chứng hiện tại; cần cập nhật sau khi chạy thử.

### 1. Tự chấm Team Health

Thang điểm: 1 = rất yếu/chưa có bằng chứng; 3 = đang hình thành; 5 = ổn định, có bằng chứng lặp lại.

| Khía cạnh | Điểm 1-5 | Cơ sở tự đánh giá hiện tại |
|---|---:|---|
| Chất lượng AI | 1 | Chưa có kết quả chạy bộ câu hỏi hoặc dữ liệu xác nhận câu trả lời/trích dẫn đúng và ổn định. Điểm thấp thể hiện chưa được kiểm chứng, không khẳng định chất lượng thực tế chắc chắn kém. |
| Tiến độ | 2 | Đã chốt phạm vi và lập kế hoạch các phase; chưa có bằng chứng trong repo về MVP chạy được hoặc milestone kỹ thuật hoàn thành. |
| Tinh thần team | 3* | Squad chỉ có một người nên không thể đo tinh thần/phối hợp giữa thành viên. Điểm 3 là proxy tạm cho khả năng tự điều phối; cần tự điều chỉnh theo trải nghiệm thật. |
| Tốc độ ra sản phẩm | 2 | Chưa có bản phát hành hoặc số đo thời gian từ thay đổi đến bản người dùng thử được; cần thiết lập baseline. |

\* Không thể so sánh độ chênh giữa các thành viên trong bài làm cá nhân. Khía cạnh thấp nhất là **chất lượng AI**; điểm này cũng có mức độ bất định cao vì chưa có eval. Vấn đề ưu tiên là thiếu bằng chứng về độ đúng và khả năng truy nguồn, có thể chặn pilot tiếp theo.

### 2. Năng lực cần nâng

| Role cụ thể | Level hiện tại/gần nhất | Competency cần nâng tiếp theo | Hành động thực hành trong 30 ngày |
|---|---|---|---|
| AI Application / RAG Builder | L1 - AI Literate (tạm tính; cần Dương Hải Minh tự xác nhận vì chưa có bằng chứng triển khai trong repo) | Evaluation / quality evaluation, hướng tới thực hành ở mức L2 - AI Practitioner | Tạo bộ 20 câu hỏi có đáp án/nguồn kỳ vọng; chạy thử, phân loại câu đúng/thiếu/sai/không có nguồn và dùng kết quả để chọn lỗi ưu tiên sửa. |

### 3. Growth Plan

| Vấn đề ưu tiên | Hành động trong 30 ngày | Owner | Deadline | Dấu hiệu hoàn thành |
|---|---|---|---|---|
| Chưa có eval đáng tin cậy cho chất lượng câu trả lời và trích dẫn | Tạo 20 golden cases từ tài liệu công khai/được phép, mỗi case có câu hỏi, đáp án hoặc bằng chứng kỳ vọng và nguồn tham chiếu. | Dương Hải Minh | 2026-10-20 | Có đủ 20 case được ghi nguồn và tiêu chí chấm; không dùng tài liệu chưa được phép. |
| Chưa biết MVP trả lời đúng và truy nguồn ổn định đến đâu | Chạy eval trên MVP khi có bản chạy được; ghi kết quả đúng/thiếu/sai/không có nguồn, sửa lỗi lặp lại nhiều nhất và chạy lại bộ kiểm thử. Nếu MVP chưa chạy được, ưu tiên hoàn tất một luồng demo hỏi PDF -> trả lời -> trích dẫn trước. | Dương Hải Minh | 2026-11-02 | Có demo luồng chính và báo cáo 20 case trước/sau; mọi câu trả lời không có nguồn được đánh dấu để xử lý, không tuyên bố đạt độ chính xác nếu chưa có số liệu. |
| Chưa xác nhận quyền tài liệu và yêu cầu dữ liệu trước pilot | Gửi mô tả luồng dữ liệu và đề nghị review cho giảng viên sở hữu tài liệu cùng cán bộ CNTT/bảo vệ dữ liệu; ghi lại điều kiện được phép và các việc còn chờ. | Dương Hải Minh | 2026-11-12 | Có phản hồi hoặc follow-up được ghi lại; checklist quyền tài liệu, lưu trữ, truy cập và xóa dữ liệu hoàn thành trước khi dùng dữ liệu không công khai. |

### Gate 4 - Growth Plan có thể thực thi

- [x] Đã tự chấm đủ 4 khía cạnh và ghi rõ giới hạn của đánh giá solo.
- [x] Đã chọn vấn đề ưu tiên có ảnh hưởng trực tiếp đến pilot tiếp theo.
- [x] Đã chọn một role, level hiện tại tạm tính, competency cần nâng và hành động thực hành.
- [x] Growth Plan có 3 hành động trở xuống; mỗi hành động có owner, deadline và dấu hiệu hoàn thành.
- [ ] Cập nhật điểm số theo tình trạng MVP thực tế và xác nhận level năng lực bằng trải nghiệm của người thực hiện.

**Trạng thái:** Kế hoạch 30 ngày đã có thể theo dõi; điểm Team Health và level năng lực là tự đánh giá tạm thời, cần hiệu chỉnh theo bằng chứng thật.

## Phase 5 - Tự rà soát và hoàn thiện repository

### Thông tin nộp bài

- **Tên nhóm:** TeamVinTay (bản hiện tại do Dương Hải Minh thực hiện một mình; cần giảng viên chấp thuận hình thức này vì đề bài gốc quy định team 3-5 người).
- **Thành viên:** Dương Hải Minh.
- **Dự án:** Trợ lý học tập AI hỏi đáp PDF có trích dẫn (dự án mẫu; thay bằng dự án thật nếu khác).
- **Demo:** Chưa có link demo.
- **PDF artefact:** [Day25_AI-Team-Lab_TeamVinTay.pdf](Day25_AI-Team-Lab_TeamVinTay.pdf) - PDF local đã được kiểm tra có đúng 4 trang.
- **HTML nguồn có thể chỉnh sửa:** [Day25_AI-Team-Lab_TeamVinTay.html](Day25_AI-Team-Lab_TeamVinTay.html).
- **URL GitHub:** [Track1_Day25_TeamVinTay_DuongHaiMinh](https://github.com/minhdh329/Track1_Day25_TeamVinTay_DuongHaiMinh) - trang truy cập được nhưng repository hiện đang trống; cần push file trước khi nộp.

### Kiểm tra artefact và consistency

- [x] **Stakeholder:** Có 6 stakeholder, map theo Influence x Interest, dùng nhãn quadrant và tách stance; 4 stakeholder ưu tiên có hành động cụ thể.
- [x] **Pitch & RACI:** Pitch có kết luận trước, lý do, bằng chứng trung thực, small ask và phản biện; 6 công việc RACI, mỗi việc có đúng một A.
- [x] **AI Team:** Chọn Embedded theo quy mô MVP một người; nêu core roles, capability gaps và lý do chọn Partner.
- [x] **Team Health & Growth:** Đủ 4 khía cạnh, nêu vấn đề ưu tiên, năng lực cần nâng và 3 hành động có owner, deadline, dấu hiệu hoàn thành.
- [x] Stakeholder mentor/chủ tài liệu/IT/người duyệt pilot xuất hiện hợp lý giữa Stakeholder Map, Pitch và RACI.
- [x] Capability gap về evaluation và quyền/dữ liệu nối với vấn đề Team Health và Growth Plan; owner các hành động phù hợp với RACI.
- [x] PDF có đúng 4 trang; đã xem cả 4 trang và không thấy nội dung bị tràn khỏi trang.
- [x] README có tên người thực hiện, thành viên và tên dự án; demo được ghi là chưa có.
- [ ] Xác nhận tên/dự án/stakeholder mẫu có khớp dự án thật và xin phép giảng viên làm cá nhân.
- [ ] Push lên GitHub, xác nhận repository có README và PDF, rồi kiểm tra link có thể truy cập.

### Gate 5 - Repository sẵn sàng nộp

**Trạng thái:** Nội dung README và PDF đã hoàn tất ở local. Chưa thể xác nhận Gate 5 cuối cùng cho đến khi repository được push lên GitHub, link truy cập được và hình thức làm cá nhân được chấp thuận.
