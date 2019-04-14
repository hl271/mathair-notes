# Khóa học MathAir - Bài 1
> **Họ và tên**: Đặng Hoàng Lan
> **Lớp**: 11

## Câu 1 (Trí tuệ)
### Trí tuệ là gì
Khả năng học và áp dụng kiến thức, kỹ năng

### 9 loại hình thông minh
1. Trí thông minh tự nhiên
2. Trí thông minh Logic & Toán học
3. Trí thông minh Âm nhạc & Thính giác
4. Trí thông minh Triết học
5. Trí thông minh Tương tác & Giao tiếp
6. Trí thông minh Thể chất
7. Trí thông minh Ngôn ngữ
8. Trí thông minh Nội tâm
9. Trí thông minh Không gian & Thị giác

## Câu 2 (Trí tuệ nhân tạo)

### Trí tuệ nhân tạo là gì
Là máy tính với một số chức năng về **trí tuệ** giống với con người

## Những cuộc Cách Mạng nào góp phần cho sự phát triển của AI
- Phát minh ra những khái niệm/ mô hình toán học cơ bản 
  - Đại số
  - Xác suất thống kê
- Ngành khoa học mới ra đời: Trí tuệ nhân tạo
  - Thuật toán Perceptron
- Big Data


## Câu 3
### Học là gì
Là thu thập kiến thức, kỹ năng thông qua trải nghiệm, giáo dục, nghiên cứu
### Học máy (Machine Learning) là gì?
ML là khả năng thực hiện 1 tác vụ nào đó của máy tính mà không cần lập trình sẵn. Khả năng này giống với khả năng tự học của con người, thể hiện ở việc máy tính có thể tích lũy thêm kinh nghiệm để cải thiện tác vụ của mình qua nhiều lần chạy
### Vị trí của Machine Learning trong AI?
- Machine Learning chỉ là một phần nhỏ trong cả ngành công nghiệp AI
### Kiến thức, kỹ năng có thể được biểu diễn trong máy tính ra sao?
Kiến thức, kỹ năng trong Machine Learning có thể được biểu diễn dưới dạng **các mô hình toán học, các hàm số được tối ưu hóa** để thực hiện tốt nhất, chính xác nhất 1 tác vụ nào đó

## Câu 4
### Mô hình TEFPA
- T (Task)
- E (Experience)
- F (Function Space): Không gian hàm số
  - f*: hàm ẩn tối ưu, giúp kết quả đầu ra đạt độ chính xác cao nhất
  - f^: hàm trong không gian hàm
- P (Performance): Chuẩn đánh giá hiệu quả của hàm số học
- A (Algorithms): Thuật toán giải hàm số học

=> Nhiệm vụ: Tìm giả thuyết hàm $f \in F$  sao cho f có độ khái quát hóa cao nhất

##  Câu 5: Mô tả "cách học" trong Machine Learning thông qua ví dụ
### a) Máy tính chuyển 1 tấm ảnh chất lượng kém (mờ, low-resolution) lên thành ảnh rõ nét (high-resolution)
- **Bài toán**:
  - Đầu vào: Bức ảnh có độ phân giải thấp
  - Đầu ra: Bức ảnh có độ phân giải cao hơn
- **Cách thu thập kinh nghiệm**: Xem rất nhiều cặp ảnh [phân giải thấp, phân giải cao] (cùng chụp 1 cảnh vật)
  - Cách thu thập dữ liệu: Có thể tự làm giảm độ phân giải của 1 tập ảnh có độ phân giải cao được cho trước
- **Chuẩn đánh giá**: độ trùng khớp giữa ảnh thật và ảnh được phục hồi
### b) máy tính xử lý ảnh chụp X-quang và dự đoán bệnh; 
- **Bài toán**:
  - Đầu vào: Ảnh chụp X-quang của 1 bệnh nhân
  - Đầu ra: Một mảng giá trị chứa những bệnh mà người bệnh có thể mắc phải, cùng với xác suất bị bệnh của người đó
- **Cách thu thập kinh nghiệm**: Xem rất nhiều cặp dữ liệu `[ảnh X-quang, bệnh của người được chụp]`. Các yếu tố liên quan đến hồ sơ bệnh lý cũng được xử lý
  - Cách thu thập dữ liệu: Dữ liệu lấy từ các bệnh viện
- **Chuẩn đánh giá**: Độ sai lệch giữa những bệnh được máy chuẩn đoán với bệnh lý thật sự của người bệnh được chuẩn đoán qua xét nghiệm
### c) máy tính đọc một email của khách hàng và tự chuyển đến thư mục tương ứng như "cảm ơn", "khiếu nại", "hỏi thông tin", "xin việc", v.v.
- **Bài toán**:
  - Đầu vào: Email của khách hàng
  - Đầu ra: Phân loại của email đó
- **Cách thu thập kinh nghiệm**: Xem rất nhiều cặp dữ liệu `[email, phân loại] `
  - Cách thu thập dữ liệu: Có thể thu thập từ những email dataset hợp pháp ở trên mạng dưới dạng các file `.csv`
- **Chuẩn đánh giá**: Độ lệch chuẩn của phân loại do máy dự đoán vs phân loại thật của email đó
## Cấu 6: Ý nghĩa câu phát biểu sau: 
> Máy tính "học" bằng cách tìm kiếm trong không gian các hàm số (chương trình máy tính). 

**Câu nói trên có ý nghĩa là:** Khi máy tính "học" để xử lý 1 tác vụ, tức là máy tính đang cố gắng tìm một mô hình toán học (một hàm số f*) tối ưu nhất trong không gian hàm số, sao cho khi áp dụng $f*$ vào để giải tác vụ đó ta cho ra kết quả chính xác nhất.

## Câu 7: Hai vấn đề chính về không gian hàm mà ta cần đặc biệt chú ý để giúp máy tính tự tìm kiếm hàm có độ khái quát hoá cao là gì?
- Vấn đề biểu diễn không gian hàm
- Vấn đề tìm kiếm/ huấn luyện không gian hàm

## Câu 8: Một số điều lý thú qua bài học
- Khám phá 9 trí thông minh khác nhau của con người
- Hiểu hơn về quy trình "học" của máy để hoàn thành các tác vụ





