Phần 1 - Kiến trúc mô hình

- Các module quy trình:
    + Module 1 - Nền tảng giá trị (4 giá trị Agile + 3 trụ cột Scrum): đây là phần định hướng cách suy nghĩ của cả đội, gồm ưu tiên con người, sản phẩm chạy được, hợp tác với khách hàng và sẵn sàng thay đổi; cùng với minh bạch, kiểm tra và thích ứng => cần xác định để các đội không áp dụng Scrum một cách hình thức, và có căn cứ để xử lý những tình huống quy trình không quy định sẵn
    + Module 2 - Vai trò (Product Owner, Scrum Master, Developers): xác định ai chịu trách nhiệm điều gì, PO quyết định làm gì và ưu tiên gì, SM giữ cho quy trình chạy đúng, Developers trực tiếp làm ra sản phẩm => cần xác định để trách nhiệm không bị chồng chéo hay bỏ trống, nhất là khi có 3 đội chạy song song
    + Module 3 - Artifacts (Product Backlog, Sprint Backlog, Increment): là những thứ thể hiện công việc một cách rõ ràng gồm danh sách yêu cầu, phần việc của Sprint và sản phẩm chạy được sau Sprint => cần xác định để mọi người cùng nhìn thấy một bức tranh về công việc và tiến độ, không ai hiểu mỗi kiểu
    + Module 4 - Sự kiện Scrum (Sprint, Planning, Daily Scrum, Review, Retrospective): là nhịp làm việc lặp lại gồm lập kế hoạch, theo dõi hằng ngày, trình bày kết quả và nhìn lại cách làm => cần xác định vì mỗi sự kiện là một thời điểm để kiểm tra và điều chỉnh, thiếu nó thì sẽ không có phản hồi và cải tiến
    + Module 5 - Tiêu chuẩn "xong" (Definition of Done): quy định điều kiện để một hạng mục được coi là hoàn thành => cần xác định để "xong" có cùng một nghĩa với tất cả mọi người, đồng thời đội Đối soát có thể thêm "cổng tuân thủ" (đối chiếu quy định thuế, kiểm thử đầy đủ) mà không phải thay đổi các module còn lại

- Đội Đối soát có áp dụng mô hình chung hay không:
    + Có áp dụng nhưng có điều chỉnh: dùng chung Module 1 đến 4 để giữ được sự minh bạch và kiểm tra đều đặn
    + Chỉ khác ở Module 5, DoD của đội có thêm cổng tuân thủ vì yêu cầu thuế rõ ràng, ổn định và làm sai sẽ bị phạt => phù hợp với lựa chọn làm tuần tự ở Bài 4

- Luồng giá trị từ nhu cầu người dùng đến cải tiến tiếp theo:

---------------------------------------------------------------------------

Nhu cầu người dùng (hành khách, tài xế, quy định thuế) <br>
        ↓<br>
PO thu thập, sắp xếp → Product Backlog<br>
        ↓<br>
Sprint Planning → Sprint Goal + Sprint Backlog<br>
        ↓<br>
Sprint: Developers làm, Daily Scrum kiểm tra mỗi ngày<br>
        ↓<br>
Increment đạt Definition of Done<br>
        ↓<br>
Sprint Review → khách hàng/stakeholder phản hồi<br>
        ↓<br>                          ↓
Phản hồi vào Product Backlog    Retrospective → cải tiến cách làm<br>
        ↓<br>                          ↓
        Sprint Planning kế tiếp (vòng mới)
---------------------------------------------------------------------------

    + Vòng phản hồi sản phẩm: Review → Product Backlog
    + Vòng cải tiến quy trình: Retrospective → Sprint kế tiếp


Phần 2 - Xử lý tình huống

- Tình huống 1: Đến Sprint Review nhưng không có hạng mục nào đạt "xong":
    + Phát hiện ở đâu: sớm nhất là ở Daily Scrum khi thấy tiến độ lệch so với Sprint Goal, chắc chắn nhất là ở Sprint Review khi đối chiếu Increment với DoD
    + Ai xử lý: Developers báo cáo trung thực, PO quyết định sắp xếp lại ưu tiên, SM điều phối buổi Retrospective
    + Xử lý như thế nào:
        + Không tính hạng mục chưa đạt DoD là xong và cũng không hạ DoD xuống để cho qua
        + Vẫn tổ chức Review, trình bày minh bạch phần đã làm để lấy phản hồi từ khách hàng
        + Đưa các hạng mục quay về Product Backlog để PO đánh giá lại
        + Ở Retrospective tìm nguyên nhân gốc (hạng mục quá lớn, cam kết quá nhiều, DoD chưa rõ) rồi đưa hành động cải tiến vào Sprint sau

- Tình huống 2: Đội Thanh toán muốn kéo dài riêng Sprint thêm 1 tuần:
    + Phát hiện ở đâu: ở Daily Scrum khi Developers thấy Sprint Goal có nguy cơ không đạt, hoặc khi đề xuất này được đưa ra
    + Ai xử lý: SM giữ nhịp Sprint, PO quyết định phần việc còn lại, Developers điều chỉnh phạm vi
    + Xử lý như thế nào:
        + Từ chối kéo dài vì độ dài Sprint là cố định, nếu kéo riêng một đội sẽ làm lệch nhịp Planning/Review so với các đội còn lại và che mất vấn đề thật sự
        + Trong Sprint, Developers và PO thu hẹp phạm vi, nếu Sprint Goal không còn giá trị thì PO có quyền hủy Sprint
        + Sprint vẫn kết thúc đúng hạn, phần chưa xong quay về Product Backlog để đưa vào Sprint kế tiếp
        + Ở Retrospective xử lý gốc rễ của vấn đề (ước lượng sai, phụ thuộc bên ngoài)