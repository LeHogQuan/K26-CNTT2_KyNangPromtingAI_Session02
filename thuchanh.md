1.

mục tiêu: phân loại đánh giá thành tích cực, tiêu cực và trung lập

quy trình: kiểm tra dữ liệu -> phân loại -.> thống kê kết quả

kiến thức áp dụng: create, few-shot, JSON, table và prompt chaining

2.

prompt 1:

Bạn là trợ lý TechShop. Hãy kiểm tra danh sách đánh giá, phát hiện dữ liệu trống, trùng lặp hoặc sai định dạng. Trả kết quả bằng JSON.

prompt 2: 

Phân loại đánh giá thành tích cực, tiêu cực hoặc trung lập

Trả kết quả bằng JSON gồm ID, cảm xúc và lý do

prompt 3:

Dựa vào kết quả phân loại, hãy đếm số đánh giá theo từng loại. Xuất kết quả bằng JSON và bảng Markdown

3. kết quả chạy thử

| id | đánh giá | phân loại |
|---|---|---|
| 1 | Sản phẩm rất tốt | tích cực |
| 2 | Sản phẩm bị lỗi | tiêu cực |
| 3 | Sản phẩm đúng mô tả | trung lập |

kiểm tra: JSON đúng cú pháp, số lượng thống kê khớp với dữ liệu đầu vào
