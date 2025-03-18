# Dự án Kiểm Thử Website Thương Mại Điện Tử

## Giới thiệu

Dự án này tập trung vào việc kiểm thử chất lượng (Quality Assurance - QA) cho website thương mại điện tử. Mục tiêu chính là đảm bảo website hoạt động ổn định, đáp ứng đúng yêu cầu nghiệp vụ, có giao diện thân thiện với người dùng và không có lỗi nghiêm trọng.

## Mục tiêu

*   Đảm bảo chất lượng sản phẩm: Phát hiện và báo cáo các lỗi (bugs) một cách chi tiết và kịp thời.
*   Tối ưu trải nghiệm người dùng: Đảm bảo giao diện trực quan, dễ sử dụng và tương tác mượt mà trên các thiết bị khác nhau.
*   Xác minh tính năng: Kiểm tra tất cả các chức năng chính của website hoạt động đúng như thiết kế.
*   Đóng góp vào sự thành công của sản phẩm: Nâng cao độ tin cậy và sự hài lòng của khách hàng.

## Phạm vi kiểm thử

Dự án này tập trung vào các khía cạnh kiểm thử sau:

*   **Kiểm thử chức năng (Functional Testing):** Xác minh các chức năng cốt lõi của website hoạt động chính xác theo đặc tả yêu cầu.
*   **Kiểm thử giao diện người dùng (UI Testing):** Đảm bảo giao diện trực quan, thân thiện, thống nhất và đáp ứng tốt trên các trình duyệt và thiết bị khác nhau.
*   **Kiểm thử hồi quy (Regression Testing):** Đảm bảo các chức năng hiện có không bị ảnh hưởng sau khi có thay đổi (sửa lỗi, thêm tính năng mới).
*   **Kiểm thử khả năng sử dụng (Usability Testing):** Đánh giá mức độ dễ sử dụng, dễ học và hiệu quả của website. (Có thể thực hiện ở mức độ cơ bản).

## Công việc đã thực hiện

1.  **Nghiên cứu và phân tích yêu cầu:**
    *   Nghiên cứu tài liệu đặc tả yêu cầu của website .
    *   Phân tích các use case, user story để hiểu rõ nghiệp vụ.
    *   Xác định phạm vi kiểm thử, các chức năng cần kiểm tra, các loại kiểm thử cần thực hiện.

2.  **Thiết kế test case:**
    *   Xây dựng bộ test case chi tiết, bao phủ các chức năng chính của website, bao gồm:
        *   **Đăng ký/Đăng nhập/Đăng xuất:** Kiểm tra các trường hợp hợp lệ, không hợp lệ, quên mật khẩu, v.v.
        *   **Tìm kiếm sản phẩm:** Kiểm tra tìm kiếm theo tên, danh mục, bộ lọc, v.v.
        *   **Giỏ hàng:** Thêm sản phẩm, sửa số lượng, xóa sản phẩm, áp dụng mã giảm giá, v.v.
        *   **Thanh toán:** Chọn phương thức thanh toán, nhập thông tin giao hàng, xác nhận đơn hàng, v.v.
        *   **Quản lý tài khoản:** Cập nhật thông tin cá nhân, xem lịch sử mua hàng, v.v.
        * Test case được thiết kế theo các kỹ thuật như: equivalence partitioning, boundary value analysis,...

3.  **Thực hiện kiểm thử:**
    *   Thực hiện kiểm thử thủ công trên các trình duyệt (Chrome, Firefox, Edge, Safari).
    *   Ghi nhận kết quả test (pass/fail), chụp ảnh màn hình lỗi, mô tả chi tiết các bước tái hiện lỗi.

4.  **Báo cáo và theo dõi lỗi:**
    *   Sử dụng Jira để báo cáo lỗi (bug) với đầy đủ thông tin:
        *   Tiêu đề rõ ràng, mô tả ngắn gọn.
        *   Các bước tái hiện lỗi chi tiết.
        *   Mức độ nghiêm trọng (Severity) và độ ưu tiên (Priority).
        *   Môi trường kiểm thử (trình duyệt, hệ điều hành, thiết bị).
        *   Ảnh chụp màn hình/video minh họa.
    * Sử dụng Zephyr để quản lý test case, thực thi test run và theo dõi tiến độ.

## Công cụ

*   **Quản lý lỗi và dự án:** Jira
*   **Quản lý Test Case:** Zephyr (tích hợp trong Jira)
*   **Ghi màn hình:** (Tùy chọn) Các công cụ như: Loom, ...
*   **Chụp ảnh màn hình**: MacOS
*   Trình duyệt: Chrome, Firefox, Edge, Safari (và các công cụ Developer Tools của trình duyệt).

## Kết quả

*   **Phát hiện và báo cáo hơn 50+ lỗi**
*   **Giảm 20% lỗi nghiêm trọng** so với các phiên bản trước. Các loại lỗi nghiêm trọng đã được giảm, ví dụ:
    *   Lỗi không thể thanh toán.
    *   Lỗi hiển thị sai thông tin sản phẩm.
    *   Lỗi mất dữ liệu giỏ hàng.
*   **Tối ưu hóa trải nghiệm người dùng:**
    *   Đề xuất cải thiện giao diện (ví dụ: nút bấm, bố cục, màu sắc).
    *   Đề xuất cải thiện quy trình (ví dụ: giảm số bước thanh toán).
*   **Nâng cao chất lượng sản phẩm:** Góp phần tạo ra một website  ổn định, đáng tin cậy và dễ sử dụng hơn.