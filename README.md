# 1. Thiết kế giải pháp (I/O)

**Bài toán:** Tự động kiểm tra thông tin đơn hàng.

**Input:**
- Tên khách hàng, mã đơn hàng.
- Tên sản phẩm, số lượng, đơn giá.
- Địa chỉ giao hàng.

**Output:**
- Thông tin đơn hàng.
- Tổng tiền.
- Lỗi dữ liệu (nếu có).
- Trạng thái đơn hàng.

# 2. Prompt thực thi

Bạn là AI quản lý đơn hàng. Hãy thực hiện:
1. Kiểm tra thông tin đơn hàng.
2. Tính tổng tiền = Số lượng × Đơn giá.
3. Phát hiện dữ liệu thiếu hoặc sai.
4. Xuất kết quả thành báo cáo.

**Yêu cầu:**
- Nếu thiếu dữ liệu, ghi rõ thông tin còn thiếu.
- Nếu dữ liệu sai, thông báo lỗi.
- Không tự ý đoán dữ liệu.
- Trình bày ngắn gọn bằng gạch đầu dòng.

# 3. Kết quả chạy thử

**Input:** Khách hàng Nguyễn Văn A, đơn DH001, sản phẩm Áo thun, số lượng 2, đơn giá 100.000 đồng, địa chỉ Hà Nội.

**Output:**
- Mã đơn: DH001.
- Khách hàng: Nguyễn Văn A.
- Sản phẩm: Áo thun.
- Tổng tiền: 200.000 đồng.
- Trạng thái: Hợp lệ.
- Lỗi: Không có.

# 4. Kỹ thuật áp dụng
- **CoT:** Chia việc kiểm tra thành từng bước logic.
- **Prompt Chaining:** Nối các bước kiểm tra, tính tiền và báo cáo.
- **Rolling Summary:** Tóm tắt thông tin quan trọng để tránh mất ngữ cảnh.
