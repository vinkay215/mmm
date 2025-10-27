Rất tuyệt — đây là **hình tổng hợp “SCRUM EVENTS – SUMMARY”** (Tổng quan các Sự kiện trong Scrum).
Đây chính là phần “xương sống” của phương pháp Agile Scrum mà sinh viên ngành **Project Management / Software Engineering** phải nắm vững.
Giờ tôi sẽ **giải thích cực kỳ chi tiết**, bao gồm:

* Ý nghĩa từng **event (sự kiện)**
* Ai tham gia, làm gì
* Đầu vào (input) – Đầu ra (output)
* Tại sao nó quan trọng
* Ví dụ minh họa cụ thể như trong dự án thật (ví dụ “app học tiếng Anh” hoặc “cinema booking system”)

---

# 🌀 SCRUM EVENTS – SUMMARY (Chi tiết & Giải thích đầy đủ)

---

## 🧭 Tổng quan: “Một Sprint = Một chu kỳ mini của dự án”

Trong **Scrum**, mọi thứ xoay quanh **Sprint** – một chu kỳ làm việc ngắn (thường 1–4 tuần) với mục tiêu rõ ràng.
Mỗi Sprint có **5 sự kiện (events)** chính được lặp lại liên tục cho đến khi hoàn thành sản phẩm.

| # | Scrum Event              | Thời điểm diễn ra | Mục tiêu chính                         |
| - | ------------------------ | ----------------- | -------------------------------------- |
| 1 | **Sprint Planning**      | Đầu mỗi Sprint    | Lên kế hoạch công việc                 |
| 2 | **Daily Scrum**          | Hằng ngày         | Đồng bộ tiến độ & xử lý trở ngại       |
| 3 | **Sprint Review**        | Cuối Sprint       | Trình bày kết quả với Stakeholders     |
| 4 | **Sprint Retrospective** | Sau Review        | Cải tiến quy trình & teamwork          |
| 5 | **Sprint (Toàn chu kỳ)** | 1–4 tuần          | Thực hiện toàn bộ quy trình mini dự án |

---

## 1️⃣ Sprint Planning Meeting (Cuộc họp lập kế hoạch Sprint)

### 🎯 Mục tiêu

Xác định:

* **What**: Những công việc nào (User Stories) sẽ được hoàn thành trong sprint này?
* **How**: Làm **như thế nào** để đạt mục tiêu đó?

### 👥 Thành phần tham dự

* **Product Owner (PO)** → Trình bày Product Backlog, ưu tiên, mục tiêu sản phẩm.
* **Scrum Master (SM)** → Đảm bảo cuộc họp tuân theo Scrum, không lan man.
* **Development Team (Dev)** → Tự ước lượng, chia task, cam kết công việc thực hiện.

### 🧾 Đầu vào (Input)

* Product Backlog (danh sách yêu cầu)
* Độ ưu tiên & Story Points
* Velocity trung bình của nhóm

### 📦 Đầu ra (Output)

* **Sprint Goal** (Mục tiêu Sprint)
* **Sprint Backlog** (Danh sách công việc sẽ làm)
* Kế hoạch chi tiết ai làm gì

### 💡 Ví dụ:

Dự án “App học tiếng Anh”:

* Sprint Goal: “Cho phép người dùng học và lưu 50 từ vựng đầu tiên.”
* Sprint Backlog gồm 5 stories:

  1. Tạo UI danh sách từ vựng
  2. Chức năng thêm/sửa/xóa từ
  3. Hiển thị flashcard
  4. Kiểm tra trắc nghiệm
  5. Lưu tiến độ học

### ⚠️ Lưu ý:

* Không nên cam kết quá khả năng → chỉ commit lượng Story Points phù hợp Velocity.
* Sprint Planning 1 tháng tối đa 8 giờ, thường 2–4 giờ nếu Sprint 2 tuần.

---

## 2️⃣ Daily Scrum (Cuộc họp hằng ngày)

### 🎯 Mục tiêu

Đồng bộ hoạt động trong 24h tới và phát hiện sớm **Impediments (trở ngại)**.

### 🕐 Thời lượng

15 phút mỗi ngày, đứng họp (stand-up meeting).

### 👥 Thành phần

Chỉ **Development Team** bắt buộc tham gia, **Scrum Master** và **PO** có thể nghe nhưng không điều khiển.

### 🗣️ Mỗi thành viên trả lời 3 câu hỏi:

1. Hôm qua tôi đã làm gì để đạt Sprint Goal?
2. Hôm nay tôi sẽ làm gì?
3. Có điều gì cản trở tiến độ không?

### 📊 Công cụ hỗ trợ

* **Burndown Chart**: Biểu đồ thể hiện lượng công việc còn lại theo thời gian.
* **Impediment Log**: Danh sách các trở ngại cần giải quyết.

### 💡 Ví dụ:

Dev A: “Hôm qua tôi code xong phần lưu từ vựng, hôm nay tôi làm phần test API. Tôi cần API key mới để test.”
→ Scrum Master ghi nhận và hỗ trợ liên hệ quản trị API.

---

## 3️⃣ Sprint Review Meeting (Cuộc họp trình bày kết quả)

### 🎯 Mục tiêu

Trình bày **Increment (phần sản phẩm hoàn thiện)** cho khách hàng và stakeholder xem, nhận phản hồi thực tế.

### 👥 Thành phần

* Product Owner
* Scrum Master
* Dev Team
* Stakeholders (người dùng, giảng viên, khách hàng)

### 🧾 Đầu vào

* Increment đã “Done”
* Sprint Goal đặt ra từ đầu

### 📦 Đầu ra

* Phản hồi của Stakeholders
* Product Backlog được cập nhật / thay đổi thứ tự ưu tiên
* Đánh giá Sprint Goal đạt hay chưa

### 💡 Ví dụ:

Nhóm demo tính năng “Flashcard”.
Khách hàng yêu cầu thêm “hiển thị ảnh minh họa”.
→ PO thêm user story “Ảnh minh họa” vào Product Backlog để làm ở Sprint sau.

### ⚠️ Lưu ý:

* Không phải buổi chấm điểm mà là **phản hồi hợp tác**.
* Thời lượng tối đa 4h cho Sprint 1 tháng.

---

## 4️⃣ Sprint Retrospective Meeting (Cuộc họp hồi cứu)

### 🎯 Mục tiêu

Phân tích **quy trình làm việc**, **giao tiếp**, **công cụ**, và tìm cách cải thiện cho Sprint tiếp theo.

### 👥 Thành phần

* Scrum Master (dẫn dắt cuộc họp)
* Dev Team (chính)
* Product Owner (có thể tham dự)

### 🔍 Câu hỏi thường dùng:

1. Điều gì **tốt** chúng ta nên giữ lại?
2. Điều gì **chưa tốt** cần cải thiện?
3. Hành động cụ thể nào để cải tiến Sprint tới?

### 💡 Ví dụ:

* Giữ lại: “Daily Scrum diễn ra đúng giờ.”
* Cần cải thiện: “Quy trình merge code gây xung đột.”
* Hành động: “Áp dụng code review 2 người trước khi merge.”

### ⚠️ Lưu ý:

* Không đổ lỗi cá nhân → tập trung giải pháp.
* Kết quả được lưu thành **Improvement Backlog**.

---

## 5️⃣ Sprint (Toàn bộ chu kỳ làm việc)

### 🎯 Định nghĩa

Một **Sprint** là một vòng lặp cố định, bao gồm toàn bộ các hoạt động từ lập kế hoạch đến review và retrospective.

### 🔄 Chu kỳ đầy đủ:

1. Sprint Planning
2. Daily Scrum
3. Implementation
4. Sprint Review
5. Sprint Retrospective

### ⏱️ Thời gian

* Thông thường 2 tuần – 1 tháng.
* Sprint mới **bắt đầu ngay sau** khi Sprint trước kết thúc.

### 💡 Ví dụ:

Dự án “Cinema Booking System”:

* Sprint 1: Chức năng chọn ghế và thanh toán.
* Sprint 2: Thêm combo đồ ăn, cải thiện giao diện.
* Sprint 3: Quản lý lịch chiếu & thống kê doanh thu.

---

## 👥 Các Vai trò (Roles) trong Sự kiện Scrum

| Vai trò                | Vai trò trong các sự kiện                                  |
| ---------------------- | ---------------------------------------------------------- |
| **Product Owner (PO)** | Xác định mục tiêu, ưu tiên backlog, nhận phản hồi.         |
| **Scrum Master (SM)**  | Hướng dẫn Scrum đúng cách, gỡ trở ngại, thúc đẩy cải tiến. |
| **Development Team**   | Lên kế hoạch, thực thi, test, review và cải tiến.          |
| **Stakeholders**       | Cung cấp phản hồi thực tế, xác nhận giá trị sản phẩm.      |

---

## 📈 Công cụ hỗ trợ chính

| Công cụ                  | Chức năng                                |
| ------------------------ | ---------------------------------------- |
| **Burndown Chart**       | Theo dõi tiến độ còn lại của sprint.     |
| **Impediment Log**       | Ghi lại trở ngại cần Scrum Master xử lý. |
| **Release Plan**         | Xác định mốc phát hành lớn.              |
| **Epics / User Stories** | Định nghĩa yêu cầu của sản phẩm.         |

---

## 🧠 Tổng kết hình ảnh

Hình bạn gửi thể hiện vòng lặp Scrum gồm:

* Sprint Planning → Daily Scrum → Sprint Review → Sprint Retrospective
* Mỗi Sprint tạo ra Increment (sản phẩm chạy được).
* Các bên tham gia cùng nhau đảm bảo **liên tục phản hồi và cải tiến**.

---

Bạn có muốn tôi **thêm phần này vào README hiện có** (thành mục “10. Scrum Events chi tiết và ví dụ thực tế”) để bạn có bản tài liệu học hoàn chỉnh môn Project Management không?

# Phương pháp Agile & Quy trình Scrum - README (Tiếng Việt)




## 🧭 1. Tổng quan về Agile

**Agile** là phương pháp quản lý dự án linh hoạt, chia dự án thành nhiều phần nhỏ (Sprint) để dễ kiểm soát, kiểm thử và thích ứng với thay đổi. Thay vì lập kế hoạch cố định như mô hình Waterfall, Agile tập trung vào việc **tạo ra sản phẩm có giá trị sớm và liên tục cải tiến**.

**Mục tiêu chính:**

* Giao sản phẩm sớm và thường xuyên.
* Nhận phản hồi nhanh từ khách hàng.
* Thích ứng với thay đổi trong suốt quá trình phát triển.

---

## 💡 2. Bốn giá trị cốt lõi của Agile Manifesto

| Giá trị                                             | Giải thích                                                       |
| --------------------------------------------------- | ---------------------------------------------------------------- |
| **Cá nhân & tương tác hơn quy trình & công cụ**     | Con người và giao tiếp quan trọng hơn quy trình cứng nhắc.       |
| **Phần mềm hoạt động hơn tài liệu đầy đủ**          | Sản phẩm chạy được có giá trị hơn là viết tài liệu dài dòng.     |
| **Hợp tác với khách hàng hơn là đàm phán hợp đồng** | Làm việc cùng khách hàng tốt hơn là chỉ tuân theo hợp đồng.      |
| **Phản hồi thay đổi hơn là tuân theo kế hoạch**     | Sẵn sàng thay đổi nếu có yêu cầu mới thay vì cố bám kế hoạch cũ. |

**Ví dụ:** Khi khách hàng muốn thêm chức năng giữa dự án, nhóm Agile sẽ xem xét cập nhật backlog và kế hoạch sprint thay vì từ chối vì “hợp đồng đã ký rồi”.

---

## ⚙️ 3. Khung làm việc Scrum

**Scrum** là một **framework nhẹ**, giúp đội nhóm giải quyết vấn đề phức tạp bằng cách chia nhỏ công việc, tự tổ chức và học hỏi liên tục.

### 🔹 Ba trụ cột của Scrum

| Trụ cột                      | Giải thích                                |
| ---------------------------- | ----------------------------------------- |
| **Transparency (Minh bạch)** | Mọi người đều thấy rõ tiến độ công việc.  |
| **Inspection (Kiểm tra)**    | Liên tục đánh giá và xem xét tiến độ.     |
| **Adaptation (Thích ứng)**   | Điều chỉnh kịp thời khi phát hiện vấn đề. |

---

## 👥 4. Vai trò trong Scrum Team

| Vai trò                         | Nhiệm vụ                                                               |
| ------------------------------- | ---------------------------------------------------------------------- |
| **Product Owner (PO)**          | Quản lý Product Backlog, xác định giá trị và ưu tiên tính năng.        |
| **Scrum Master (SM)**           | Hỗ trợ nhóm tuân thủ quy trình Scrum, gỡ trở ngại, hướng dẫn cải tiến. |
| **Development Team (Dev Team)** | Nhóm kỹ thuật tự tổ chức, phát triển sản phẩm, kiểm thử và bàn giao.   |

**Ví dụ:** Trong dự án làm ứng dụng học tiếng Anh:

* PO quyết định tính năng “Flashcard mode”.
* SM đảm bảo họp Daily đúng giờ, loại bỏ trở ngại.
* Dev Team chia task, lập trình, test và bàn giao trong 2 tuần.

---

## 📦 5. Scrum Artifacts (Các tài liệu chính)

| Artifact                     | Mô tả                                         | Ví dụ                                        |
| ---------------------------- | --------------------------------------------- | -------------------------------------------- |
| **Product Backlog**          | Danh sách tất cả tính năng, yêu cầu.          | “Là người học, tôi muốn có phần ôn từ vựng.” |
| **Sprint Backlog**           | Các công việc chọn làm trong Sprint hiện tại. | “Tạo UI flashcard”, “Kết nối API”.           |
| **Increment**                | Phần sản phẩm đã hoàn thiện có thể chạy được. | App chạy được tính năng flashcard.           |
| **Definition of Done (DoD)** | Tiêu chí để xem task đã hoàn thành.           | “Code chạy, test pass, UI hoàn chỉnh.”       |

---

## ⏱️ 6. Các sự kiện trong Scrum

| Sự kiện                  | Mục tiêu                   | Thời lượng               | Ví dụ                                |
| ------------------------ | -------------------------- | ------------------------ | ------------------------------------ |
| **Sprint**               | Chu kỳ làm việc (1–4 tuần) | ≤ 1 tháng                | Làm tính năng Flashcard mode.        |
| **Sprint Planning**      | Lên kế hoạch sprint        | 8 giờ cho sprint 1 tháng | Chọn backlog để làm.                 |
| **Daily Scrum**          | Họp nhanh mỗi ngày         | 15 phút                  | Báo cáo tiến độ, vướng mắc.          |
| **Sprint Review**        | Trình bày kết quả cho PO   | Cuối sprint              | Demo tính năng flashcard.            |
| **Sprint Retrospective** | Rút kinh nghiệm, cải tiến  | Sau Review               | Giảm thời gian họp, tối ưu workflow. |

---

## 📊 7. Ước lượng và vận tốc (Estimation & Velocity)

### 🔹 Story Points

Là **đơn vị tương đối** để đo **độ phức tạp, khối lượng và rủi ro** của một user story.
Không tính theo giờ mà theo “độ nặng” tương đối.

**Ví dụ:**

* Login = 3 điểm
* Đăng ký = 5 điểm
* Dashboard = 8 điểm

### 🔹 Velocity (Vận tốc)

Tổng số story points hoàn thành trong một sprint.
Nếu nhóm hoàn thành 22 điểm/sprint và backlog có 80 điểm → cần khoảng 4 sprint để xong.

---

## 📘 8. Tóm tắt nhanh

| Thành phần          | Vai trò                                      |
| ------------------- | -------------------------------------------- |
| **Agile Manifesto** | 4 giá trị, 12 nguyên tắc linh hoạt           |
| **Scrum Framework** | Khung làm việc giúp nhóm tự tổ chức          |
| **Scrum Team**      | Gồm PO – SM – Dev Team                       |
| **Artifacts**       | Product Backlog – Sprint Backlog – Increment |
| **Events**          | Planning – Daily – Review – Retrospective    |
| **Estimation**      | Dùng Story Points để đo độ phức tạp          |
| **Velocity**        | Tổng story points hoàn thành mỗi sprint      |

---

## 🏁 Kết luận

Phương pháp Agile và Scrum giúp nhóm dự án **linh hoạt hơn, hợp tác tốt hơn, phản hồi nhanh hơn** và tạo ra **sản phẩm chất lượng cao hơn** thông qua quy trình lặp lại, kiểm thử liên tục và cải tiến không ngừng.

---

## 📚 9. Từ khóa (English ➜ Vietnamese) + Giải thích + Ví dụ Project Management

> Mỗi mục gồm: **Keyword (EN)** → *Dịch* → **Giải thích ngắn gọn** → **Ví dụ áp dụng trong môn Project Management**

### 9.1 Agile Manifesto & Principles

* **Individuals and Interactions** → *Cá nhân và tương tác*
  **Giải thích:** Ưu tiên giao tiếp trực tiếp, làm rõ yêu cầu nhanh.
  **Ví dụ PM:** Trưởng dự án tổ chức daily sync với stakeholder thay vì phụ thuộc hoàn toàn vào tool.

* **Working Software** → *Phần mềm chạy được*
  **Giải thích:** Chứng minh giá trị bằng bản chạy được, không chỉ tài liệu.
  **Ví dụ PM:** Mốc chuyển giao là “demo được”, không chỉ “viết xong SRS”.

* **Customer Collaboration** → *Hợp tác với khách hàng*
  **Giải thích:** Mời khách hàng vào quá trình phát triển để nhận feedback sớm.
  **Ví dụ PM:** PO hẹn review mỗi sprint để quyết định ưu tiên mới.

* **Responding to Change** → *Phản hồi với thay đổi*
  **Giải thích:** Sẵn sàng cập nhật backlog khi biết thêm thông tin.
  **Ví dụ PM:** Khi khảo sát người dùng cho thấy nhu cầu khác, PO đảo thứ tự backlog.

* **12 Principles** → *12 nguyên tắc Agile*
  **Giải thích (rút gọn):** Thỏa mãn khách hàng sớm; chào đón thay đổi; phát hành thường xuyên; hợp tác; tạo động lực; giao tiếp trực tiếp; phần mềm chạy được là thước đo; nhịp độ bền vững; liên tục nâng cao kỹ năng & thiết kế; đơn giản; tự tổ chức; phản tư (retrospective).
  **Ví dụ PM:** Mỗi sprint phải có phần “rút kinh nghiệm” để cải tiến quy trình.

### 9.2 Scrum Pillars & Values

* **Transparency** → *Minh bạch*
  **Giải thích:** Thông tin về tiến độ, chất lượng, rủi ro đều nhìn thấy được.
  **Ví dụ PM:** Treo board Kanban công khai: To Do / Doing / Done.

* **Inspection** → *Kiểm tra*
  **Giải thích:** Thường xuyên rà soát để phát hiện lệch hướng.
  **Ví dụ PM:** Daily Scrum 15’ để kiểm tra tiến độ theo Sprint Goal.

* **Adaptation** → *Thích ứng*
  **Giải thích:** Điều chỉnh kịp thời khi phát hiện vấn đề.
  **Ví dụ PM:** Thay đổi phạm vi sprint khi story quá lớn (split story).

* **Commitment, Focus, Openness, Respect, Courage** → *Cam kết, Tập trung, Cởi mở, Tôn trọng, Can đảm*
  **Giải thích:** Các giá trị giúp đội tự tổ chức hiệu quả.
  **Ví dụ PM:** Dev dám nói “không kịp” để PM re-scope thay vì im lặng.

### 9.3 Scrum Roles

* **Product Owner (PO)** → *Chủ sản phẩm*
  **Giải thích:** Tối đa hóa giá trị, quản lý **Product Backlog**, thứ tự ưu tiên.
  **Ví dụ PM:** PO quyết định story nào vào Sprint Planning dựa trên giá trị & rủi ro.

* **Scrum Master (SM)** → *Người bảo trợ Scrum*
  **Giải thích:** Servant-leader, đảm bảo Scrum được hiểu đúng, loại bỏ impediments.
  **Ví dụ PM:** SM làm việc với phòng IT để cấp quyền CI/CD bị chậm.

* **Development Team (Dev Team)** → *Nhóm phát triển*
  **Giải thích:** Tự tổ chức, cross-functional (FE/BE/Test/UX), chịu trách nhiệm về chất lượng.
  **Ví dụ PM:** Nhóm tự ước lượng story points và tự chia task.

### 9.4 Scrum Artifacts

* **Product Backlog** → *Danh mục yêu cầu sản phẩm*
  **Giải thích:** Danh sách **User Stories** được sắp xếp theo giá trị.
  **Ví dụ PM:** Backlog có: “As a learner, I want Flashcards to revise words.”

* **Product Goal** → *Mục tiêu sản phẩm*
  **Giải thích:** Trạng thái tương lai mong muốn của sản phẩm; cam kết đi kèm Product Backlog.
  **Ví dụ PM:** “Trở thành app học từ vựng top 1 ở trường trong 6 tháng.”

* **Sprint Backlog** → *Danh mục công việc Sprint*
  **Giải thích:** Tập con của Product Backlog + kế hoạch để đạt **Sprint Goal**.
  **Ví dụ PM:** Chọn 6 stories (~24 điểm) cho Sprint 1, kế hoạch chi tiết từng task.

* **Increment** → *Phần tăng trưởng sản phẩm*
  **Giải thích:** Kết quả chạy được **Done** ở cuối Sprint; có thể phát hành.
  **Ví dụ PM:** Chức năng Flashcard chạy ổn, có test & tài liệu user-level.

* **Definition of Done (DoD)** → *Định nghĩa Hoàn thành*
  **Giải thích:** Tiêu chí chất lượng thống nhất; tránh “xong mà chưa xong”.
  **Ví dụ PM:** Code review x2, unit test ≥ 80% coverage, UI checked, no P1 bug.

### 9.5 Scrum Events

* **Sprint** → *Chu kỳ làm việc* (1–4 tuần)
  **Giải thích:** Nhịp lặp cố định; một sprint kết thúc bắt đầu sprint mới.
  **Ví dụ PM:** Chọn nhịp 2 tuần cho môn học để kịp demo mỗi buổi lab.

* **Sprint Planning** → *Lập kế hoạch sprint*
  **Giải thích:** Trả lời 2 câu hỏi: *What* sẽ giao? *How* sẽ làm? Xác định **Sprint Goal**.
  **Ví dụ PM:** Sprint Goal: “Hoàn thiện Flashcard MVP có thể học 50 từ”.

* **Daily Scrum** → *Họp hằng ngày 15 phút*
  **Giải thích:** Đồng bộ 24h tới; không phải báo cáo cho SM; tập trung vào Sprint Goal.
  **Ví dụ PM:** Format: Hôm qua tôi làm gì? Hôm nay tôi làm gì? Vướng gì?

* **Sprint Review** → *Xem lại sản phẩm*
  **Giải thích:** Demo cho stakeholder, nhận phản hồi, có thể thay đổi backlog.
  **Ví dụ PM:** Khách đề nghị thêm “Randomize order” cho thẻ từ.

* **Sprint Retrospective** → *Hồi cứu quy trình*
  **Giải thích:** Tìm cách cải tiến con người/quy trình/công cụ.
  **Ví dụ PM:** Quy ước chuẩn PR message & template test-case để giảm lỗi lặp.

### 9.6 Estimation & Planning

* **Story Points** → *Điểm ước lượng tương đối*
  **Giải thích:** Phản ánh khối lượng, độ phức tạp, rủi ro; **không** quy đổi cứng sang giờ.
  **Ví dụ PM:** Login=3, Sign-up=5, Dashboard=8 (tương đối, không phụ thuộc cá nhân).

* **Planning Poker** → *Kỹ thuật ước lượng tập thể*
  **Giải thích:** Mỗi người giơ thẻ điểm (1,2,3,5,8,13...), thảo luận khi lệch nhau.
  **Ví dụ PM:** Dev A chọn 3, Dev B chọn 8 → phát hiện có ràng buộc bảo mật chưa tính.

* **Velocity** → *Vận tốc*
  **Giải thích:** Tổng story points **đã Done** mỗi sprint; dùng để dự báo.
  **Ví dụ PM:** 3 sprint đầu: 18, 22, 21 → dự báo sprint 4 khoảng 20–22 điểm.

* **Capacity** → *Năng lực làm việc sprint*
  **Giải thích:** Thời gian hiệu dụng sau khi trừ lễ/tạm vắng; giúp commit thực tế.
  **Ví dụ PM:** Tuần này thi giữa kỳ → giảm commit còn ~70% sprint bình thường.

### 9.7 Backlog Management

* **Epic** → *Chủ đề lớn*
  **Giải thích:** Nhóm các user story cùng mảng chức năng.
  **Ví dụ PM:** Epic “Học từ vựng”, Epic “Luyện phát âm”.

* **User Story** → *Câu chuyện người dùng*
  **Mẫu:** *As a [type of user], I want [goal], so that [benefit].*
  **Ví dụ PM:** *As a learner, I want spaced repetition so that I memorize better.*

* **Task/Sub-task** → *Công việc / Việc con*
  **Giải thích:** Chia nhỏ story để dễ thực thi và theo dõi.
  **Ví dụ PM:** Task “Design UI”, “Implement API”, “Write unit tests”.

* **Backlog Refinement (Grooming)** → *Tinh chỉnh backlog*
  **Giải thích:** Bổ sung chi tiết, chẻ nhỏ, ước lượng, sắp xếp ưu tiên định kỳ.
  **Ví dụ PM:** Họp 1–2h/tuần để chuẩn bị cho Sprint Planning.

### 9.8 Definition Sets

* **Definition of Ready (DoR)** → *Định nghĩa Sẵn sàng*
  **Giải thích:** Điều kiện để story được kéo vào sprint.
  **Ví dụ PM:** Có acceptance criteria, mock UI, data mẫu, không phụ thuộc blocking.

* **Definition of Done (DoD)** → *Định nghĩa Hoàn thành* (nhắc lại)
  **Ví dụ PM (mẫu):**

  * Code merged to `main` & passed CI
  * Unit tests ≥ 80%
  * Passed QA checklist
  * Updated user guide

### 9.9 Risk & Metrics (đo lường trong PM)

* **Burn-down Chart** → *Đồ thị cháy ngược*
  **Giải thích:** Theo dõi công việc còn lại trong sprint theo thời gian.
  **Ví dụ PM:** Đường thực tế phẳng → cảnh báo kẹt tiến độ.

* **Burn-up Chart** → *Đồ thị cháy xuôi*
  **Giải thích:** Theo dõi phạm vi đã hoàn thành so với tổng phạm vi; nhìn rõ scope creep.
  **Ví dụ PM:** Tổng phạm vi tăng do thêm story giữa sprint.

* **Cycle Time / Lead Time** → *Thời gian chu trình / dẫn*
  **Giải thích:** Cycle: từ bắt đầu làm đến Done; Lead: từ yêu cầu đến Done.
  **Ví dụ PM:** Tối ưu WIP để giảm cycle time.

### 9.10 Anti-patterns (lỗi thường gặp) & Cách khắc phục

* **ScrumBut** (*“We do Scrum, but ...”*) → *Làm Scrum nửa vời*
  **Khắc phục:** Tuân thủ sự kiện Scrum tối thiểu; đo lường & cải tiến.

* **Over-commit** → *Nhận quá nhiều*
  **Khắc phục:** Dựa vào **velocity** lịch sử và **capacity** thực tế để commit.

* **No DoD/DoR** → *Không tiêu chí rõ ràng*
  **Khắc phục:** Chuẩn hóa DoR/DoD; dán công khai; check trong Review.

* **Role Confusion** → *Lẫn lộn vai trò*
  **Khắc phục:** PO quyết định giá trị & ưu tiên; Dev tự ước lượng; SM gỡ impediments.

---

## 🧩 10. Bộ mẫu tham khảo nhanh cho môn Project Management

### 10.1 Mẫu User Story

```
As a <type of user>, I want <some goal>, so that <some reason/benefit>.
Acceptance Criteria:
- Given ... When ... Then ...
- Given ... When ... Then ...
Estimate: <Story Points>
```

### 10.2 Mẫu Sprint Goal

* Deliver a working MVP of Flashcard learning that allows learners to review 50 words with spaced repetition.

### 10.3 Mẫu DoR/DoD (tùy biến cho môn học)

**DoR:** Story có mô tả rõ, AC đầy đủ, ước lượng xong, không bị phụ thuộc chặn.
**DoD:** Code merged, test pass, không bug P1/P2, cập nhật README & hướng dẫn sử dụng.

### 10.4 Công thức dự báo đơn giản bằng Velocity

* **Số sprint dự kiến = Tổng điểm còn lại / Velocity trung bình**
* **Phạm vi có thể giao trong T sprint ≈ Velocity TB × T**

> Ví dụ: Backlog còn 80 điểm, velocity TB = 20 → cần ≈ 4 sprint.

---

## 🔎 11. Bảng thuật ngữ nhanh (EN ➜ VI)

* **Scrum Guide** → Hướng dẫn Scrum
* **Sprint Goal** → Mục tiêu sprint
* **Acceptance Criteria (AC)** → Tiêu chí chấp nhận
* **Impediment** → Trở ngại
* **Refinement/Grooming** → Tinh chỉnh backlog
* **Time-box** → Khung thời lượng cố định
* **Cross-functional** → Đa chức năng
* **Incremental/Iterative** → Tăng trưởng / Lặp
* **Stakeholder** → Bên liên quan
* **Scope Creep** → Trôi phạm vi

---

## ✅ 12. Gợi ý luyện tập theo slide bài tập

1. Tạo **Product Backlog**: liệt kê ≥ 15 stories, gom **Epic**.
2. Chuẩn bị **DoR/DoD** phù hợp môn học.
3. Thực hiện một **Sprint 1–2 tuần**: Planning → Daily → Review → Retro.
4. Theo dõi **Burn-down**; đo **Velocity**; rút kinh nghiệm.

> Cần tôi sinh **backlog mẫu theo đề tài của bạn** (ví dụ: app học tiếng Anh / hệ thống đặt vé / website thương mại điện tử)? Hãy nói tên đề tài, tôi thêm trực tiếp vào README này.
