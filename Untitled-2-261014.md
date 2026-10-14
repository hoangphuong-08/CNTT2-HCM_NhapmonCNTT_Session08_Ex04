
# yêu cầu đầu ra
## ***Phần 1. Phân tích bài toán:***
***Giải thích tại sao Markdown lại giúp AI xử lý tài liệu nhanh hơn và chính xác hơn dựa trên số lượng Token.***

- Tiết kiệm số lượng Token: HTML chứa rất nhiều các thẻ bao bọc rườm rà.trong khi Markdown chỉ dùng các ký tự cú pháp cực kỳ tối giản
- Tốc độ và độ chính xác của AI: Vì số lượng token ít hơn, AI sẽ nạp dữ liệu (context window) nhanh hơn, ít bị quá tải bộ nhớ đệm và giảm thiểu hiện tượng "quên" thông tin ở các đoạn sau. Đồng thời, cấu trúc phẳng, rõ ràng của Markdown giúp mô hình ngôn ngữ lớn dễ dàng bóc tách tiêu đề, danh sách và đoạn mã mà không bị nhiễu bởi các thẻ định dạng rác của HTML.
### ***Phần 2. So sánh & Đánh giá:***
### ***Lập bảng so sánh Markdown và HTML. Đưa ra lựa chọn cuối cùng và lập luận tại sao lập trình viên luôn chọn Markdown để viết tài liệu README.***

| Markdown |HTML  |
|:---------|:---------|
| Tối giản,tiếp kiệm chí phí gọi API và bộ nhớ AI.Viết tài liệu kỹ thuật, ghi chú, file README.md trên GitHub   | rườm rà, nhiều thẻ đóng/mở,lãng phí token cho các thẻ cú pháp.Xây dựng giao diện trang web hiển thị trên trình duyệt

***vì sao lập trình viên luôn chọn Markdown để viết tài liệu README?*** 
- vì Markdown thân thiện với con người, tối ưu hóa cho AI và hệ thống và tương thích hoàn toàn với Github.