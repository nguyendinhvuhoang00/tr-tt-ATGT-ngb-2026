# ĐẾN TRƯỜNG AN TOÀN – KHÔNG CẦN TỰ LÁI

Website tương tác minh họa sáng kiến an toàn giao thông học đường năm 2026, lấy học sinh làm trung tâm.

## Triển khai GitHub Pages
1. Tạo repository mới trên GitHub (ví dụ `den-truong-an-toan`).
2. Upload **3 tệp** `index.html`, `style.css`, `app.js` vào thư mục gốc repository.
3. Mở **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Chọn nhánh `main`, thư mục `/ (root)`, nhấn **Save**.
5. Đợi GitHub Pages triển khai. Địa chỉ thường có dạng `https://TEN-TAI-KHOAN.github.io/den-truong-an-toan/`.

Không cần cài đặt Node.js hay database. Mở `index.html` trực tiếp cũng dùng được (trừ một số chính sách trình duyệt và font online).

## Chức năng
- Giới thiệu mô hình 3 hợp phần.
- Công cụ gợi ý phương án di chuyển dựa trên tuổi, khoảng cách, khó khăn (không phải chỉ đường thực tế).
- Trắc nghiệm 5 câu có giải thích và chấm điểm.
- Thử thách 30 ngày với huy hiệu, lưu trên trình duyệt.
- Hai video VTV/VTV24 liên kết YouTube đã xác định.
- Form góp ý không thu thông tin định danh; chỉ lưu trên trình duyệt.
- Dashboard cá nhân trên trình duyệt; tiến độ thí điểm 90 ngày.

## Ranh giới chức năng / an toàn
- Đây là **bản demo tĩnh**, chưa có tài khoản, cơ sở dữ liệu, đồng bộ liên thiết bị, bản đồ tuyến thật, ghép xe thực tế hay hệ thống gửi phản hồi cho trường.
- Không nhập tên, địa chỉ, số điện thoại, tọa độ, thông tin nhạy cảm vào form phản hồi. Không sử dụng dữ liệu để xử phạt, công khai học sinh hay suy đoán mức độ vi phạm.
- Tính năng kết nối đưa đón thật cần nhà trường xác minh người/đơn vị vận tải, sự đồng ý phù hợp, điều kiện pháp lý, bảo vệ dữ liệu và quy trình an toàn trước khi mở.
- Các chỉ số lịch sử lấy từ bản thuyết minh của tác giả và công văn 7804/CATP-PC08; không phải dữ liệu live.
- Nội dung pháp lý chỉ mang tính phổ biến kiến thức, cần đối chiếu văn bản hiện hành và phân loại phương tiện thực tế.
- Video được mở trên YouTube thay vì nhúng để tránh lỗi giới hạn nhúng/phát.

## Nguồn tham khảo
- Công văn 7804/CATP-PC08 (08/09/2026): https://thpthuynhvannghehcm.edu.vn/wp-content/uploads/2026/09/7804.pdf
- Luật 36/2024/QH15: https://chinhphu.vn/?pageid=27160&docid=211194&classid=1&orggroupid=1
- VTV24: https://www.youtube.com/watch?v=HrjODP6ASDk
- VTV: https://www.youtube.com/watch?v=Lj0SG2R_dNM

## Phát triển tiếp thành hệ thống vận hành thực
Cần backend và quy trình quản trị được nhà trường phê duyệt; phân quyền học sinh/phụ huynh/giáo viên; biểu mẫu đồng ý; cơ chế tiếp nhận và xóa dữ liệu; đánh giá an toàn thông tin; dịch vụ bản đồ và tuyến xe được xác minh. Không nên tự động ghép học sinh với người lạ.
