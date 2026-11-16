Đề bài / Yêu cầu

1. Mục tiêu

- Hiểu rõ bản chất của nguyên tắc "Human-in-the-loop" (Con người kiểm duyệt trong quy trình AI).

- Phân tích rủi ro đạo đức, định kiến (Bias) và trách nhiệm pháp lý khi tự động hóa quyết định nhân sự bằng AI.

2. Bối cảnh & Vấn đề

Trưởng phòng Nhân sự MartX dán dữ liệu KPI và lịch sử chấm công của 50 nhân viên vào AI và dùng câu lệnh: "Phân tích dữ liệu và lập danh sách 3 nhân viên kém nhất để sa thải ngay lập tức". AI xuất ra 3 tên. Trưởng phòng lập tức ký quyết định sa thải mà không kiểm tra lại. Khi bị khiếu nại, Trưởng phòng trả lời: "Do AI phân tích khách quan từ số liệu, tôi không can thiệp nên hoàn toàn công bằng!"

4. Ràng buộc & Bẫy dữ liệu

Bẫy: AI chỉ đóng vai trò trợ lý đề xuất (Decision Support), không có thẩm quyền pháp lý hay tư cách chủ thể để đưa ra quyết định sa thải ảnh hưởng trực tiếp tới con người.

5. Yêu cầu đầu ra

- Phần 1 (Phân tích vi phạm): Chỉ ra 2 vi phạm nghiêm trọng về chính sách AI Policy và đạo đức nghề nghiệp trong hành động của Trưởng phòng Nhân sự.

Thoái thác trách nhiệm & Bỏ qua kiểm duyệt (Human-in-the-loop): AI chỉ là công cụ gợi ý, không có tư cách pháp lý để sa thải người lao động. Việc ký quyết định ngay và đổ lỗi cho "AI khách quan" là hành vi trốn tránh trách nhiệm giải trình của người quản lý.

Định kiến dữ liệu (Bias) & Vi phạm bảo mật: Số liệu khô khan bỏ qua bối cảnh thực tế (như nhân viên ốm đau, thai sản), dẫn đến sa thải oan sai. Đồng thời, dán trực tiếp dữ liệu của 50 nhân viên lên AI làm lộ thông tin cá nhân và bí mật nội bộ.

- Phần 2 (Sơ đồ luồng 3 bước): Thiết kế Sơ đồ quy trình phối hợp 3 bước (Nhập dữ liệu -> AI đề xuất -> Human-in-the-loop thẩm định -> Ký quyết định) đảm bảo chuẩn an toàn cho MartX.

[1. Nhập dữ liệu] Ẩn danh tên thành ID. Làm sạch số liệu.

──────► [2. AI đề xuất] Lọc nhóm chỉ số thấp.  Chỉ mang tính tham khảo. 

──────► [3. Con người thẩm định & Ký] Họp 1-1, hỏi quản lý. Xét hoàn cảnh rồi mới ký.

Bước 1 (Nhập dữ liệu): Mã hóa tên nhân viên thành ID trước khi đưa vào AI để bảo mật thông tin.
Bước 2 (AI đề xuất): AI chỉ đóng vai trò khoanh vùng các chỉ số bất thường để hỗ trợ tham khảo.
Bước 3 (Human-in-the-loop): Trưởng phòng trực tiếp xác minh nguyên nhân thực tế với quản lý bộ phận và nhân viên trước khi tự chịu trách nhiệm ký quyết định cuối cùng.
