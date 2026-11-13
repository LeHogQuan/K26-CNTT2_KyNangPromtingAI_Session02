- Vấn đề: 
Phát triển tư duy sản phẩm. Sinh viên tự thiết kế cấu trúc hoạt động của một chatbot AI giải quyết nhu cầu thực tế về CREATE, Few-shot, Ép định dạng JSON/Table.
Thiết kế một chatbot AI đóng vai chuyên gia tư vấn thông minh có phân hệ giao tiếp rõ ràng và bảo mật cao

- Yêu cầu:
+ Lập bảng thiết kế endpoint:
+ Viết system prompt: 

- Cách làm:

Bước 1:
| Method | Endpoint | Mục đích |
|---|---|---|
| GET | /api/v1/list | Lấy danh sách dữ liệu |
| GET | /api/v1/detail | Xem chi tiết phần tử |
| POST | /api/v1/create | Thêm dữ liệu mới | 
| PUT | /api/v1/update | Cập nhật thông tin | 
| DELETE | /api/v1/delete | Xóa phần tử | 
| GET | /api/v1/stats | Xem thống kê hoạt động | 

Bước 2: 
- Read: cho tôi xem các sản phẩm về bút bi
- Read: cho tôi xem chi tiết hơn về sản phẩm này như hãng sản xuất, màu bút, ...
- Create: thêm sản phẩm giấy kiểm tra c2
- Update: tăng sản phẩm bút bi lên 10k
- Delete: Xóa sản phẩm ngòi bút bi bán lẻ
- Stats: thống kê vốn và giá bán từng sản phẩm hiện có
