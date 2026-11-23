# BÀI TẬP: SỬA ĐỔI PROMPT THIẾU CẤU TRÚC RÀNG BUỘC ĐỊNH DẠNG

## Bước 1: Phân tích lỗi

**Prompt cũ:**

```text
Hãy giải thích ngắn gọn các nội dung của Custom Instructions, Prompt Library, Prompt Injection.
```

```
Xin chào! Chắc chắn rồi, mình sẽ giúp bạn.

Đây là những khái niệm quan trọng trong quản trị Prompt:

Custom Instructions (Hướng dẫn tùy chỉnh): Là thiết lập cho phép người dùng lưu sẵn bối cảnh cá nhân và quy tắc phản hồi cố định (ví dụ: giọng văn, định dạng đầu ra, trình độ chuyên môn). Hệ thống sẽ tự động áp dụng các chỉ dẫn này cho mọi cuộc hội thoại mới mà không cần nhập lại từ đầu.

Prompt Library (Thư viện câu lệnh): Là kho lưu trữ tập hợp các mẫu câu lệnh (prompt) đã được tối ưu hóa và phân loại theo từng mục đích cụ thể (viết lách, lập trình, phân tích dữ liệu...). Công cụ này giúp tiết kiệm thời gian soạn thảo và đảm bảo chất lượng đầu ra đồng đều khi tái sử dụng.

Prompt Injection (Tấn công tiêm nhiễm câu lệnh): Là một lỗ hổng bảo mật trong các ứng dụng AI, xảy ra khi kẻ tấn công chèn các chỉ thị độc hại (trực tiếp qua ô nhập liệu hoặc gián tiếp qua dữ liệu bên ngoài như trang web, tài liệu) nhằm đánh lừa mô hình bỏ qua các quy tắc an toàn ban đầu, từ đó thực hiện hành vi trái phép hoặc làm rò rỉ dữ liệu nhạy cảm.

Nếu Custom Instructions giúp cá nhân hóa và Prompt Library giúp chuẩn hóa quy trình sử dụng AI hiệu quả, thì Prompt Injection chính là rủi ro bảo mật cốt lõi cần phòng tránh để đảm bảo hệ thống vận hành an toàn.

Hy vọng phần giải thích trên sẽ giúp bạn hiểu rõ hơn.
```
**3 nội dung thừa thãi trong câu trả lời cũ của AI:**

1. **Lời chào xã giao:** "Xin chào! Chắc chắn rồi, mình sẽ giúp bạn."
2. **Lời dẫn nhập:** "Đây là những khái niệm quan trọng trong quản trị Prompt."
3. **Lời kết:** "Hy vọng phần giải thích trên sẽ giúp bạn hiểu rõ hơn."

**Nguyên nhân:**

- Prompt chưa quy định định dạng đầu ra.
- Chưa bắt buộc sử dụng gạch đầu dòng.
- Chưa cấm lời chào, lời dẫn nhập và lời kết xã giao.

## Bước 2: Viết Prompt tối ưu

**Prompt sau khi sửa:**

```text
Bạn là AI Assistant hỗ trợ giải thích kiến thức Công nghệ thông tin.

Yêu cầu:
Hãy giải thích ngắn gọn 3 nội dung:
1. Custom Instructions.
2. Prompt Library.
3. Prompt Injection.

Quy tắc phản hồi:
- Không viết lời chào hỏi xã giao.
- Không viết lời dẫn nhập ngoài yêu cầu.
- Không viết lời cảm ơn hoặc lời kết xã giao.
- Không trình bày lan man.

Quy định đầu ra:
- Bắt buộc trình bày bằng gạch đầu dòng.
- Mỗi khái niệm có một tiêu đề riêng.
- Mỗi khái niệm giải thích tối đa 2 câu.
- Sử dụng tiếng Việt đơn giản, dễ hiểu.
- Nội dung ngắn gọn, rõ ràng, dễ sao chép vào báo cáo.

Chỉ xuất ra kết quả theo đúng định dạng trên.
```

## Bước 3: Kết quả phản hồi sau khi tối ưu Prompt

**Custom Instructions**
- Là nơi lưu các chỉ dẫn cố định để AI duy trì vai trò, quy tắc và phong cách phản hồi trong các cuộc trò chuyện.
- Giúp tiết kiệm thời gian và đảm bảo câu trả lời nhất quán.

**Prompt Library**
- Là thư viện lưu trữ các mẫu prompt để sử dụng lại nhiều lần.
- Giúp tiết kiệm thời gian, quản lý prompt khoa học và chuẩn hóa công việc.

**Prompt Injection**
- Là hình thức tấn công bằng cách chèn câu lệnh độc hại nhằm đánh lừa AI bỏ qua các quy tắc ban đầu.
- Có thể khiến AI tiết lộ thông tin hoặc thực hiện những hành động trái phép.

## Bước 4: Đánh giá kết quả

- **Prompt cũ:** Chưa có quy định cụ thể về định dạng và nội dung không được xuất hiện.
- **Prompt mới:** Đã bổ sung Behavioral Constraints và Output Standard.
- **Kết quả:** AI trả lời bằng gạch đầu dòng, ngắn gọn, không có lời chào, lời dẫn nhập và lời kết thừa thãi.
