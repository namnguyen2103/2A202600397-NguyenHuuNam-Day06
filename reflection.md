# Individual reflection Nguyen Huu Nam (2A202600397)

## 1. Role
Phụ trách thiết kế logic agent của chatbot và viết system prompt.

## 2. Đóng góp cụ thể
- Thiết kế ReAct agent
- Tích hợp tool calling
- Viết và tinh chỉnh system prompt để guardrail agent
- Test agent trên CLI

## 3. SPEC mạnh/yếu
- Mạnh nhất: failure modes — nhóm nghĩ ra được case "triệu chứng chung chung"
  mà AI gợi ý quá rộng, và có mitigation cụ thể (hỏi thêm câu follow-up)
- Yếu nhất: 2 feature không có đủ 4 paths trong User Stories

## 4. Đóng góp khác
- Tham gia brainstorm để sửa lại workflow sau khi được cô Blue góp ý.
- Update User Stories từ D5 dựa trên các features final của D6.

## 5. Điều học được
Trước khi xây dựng prototype, suy nghĩ đơn giản về workflow của chatbot.
Sau khi được cô Blue góp ý prototype, nhận ra điểm bất hợp lý về mặt thiết kế, 
đặc biệt là chưa xử lý tốt các tình huống thực tế (người dùng không thể nhận ra 
rằng thông tin chatbot đưa ra là sai). Điều này giúp hiểu rõ hơn rằng thiết kế 
chatbot không chỉ là logic đúng mà còn phải phù hợp với hành vi người dùng và 
các tình huống phát sinh.

## 6. Nếu làm lại
Nếu làm lại, sẽ dành nhiều thời gian hơn cho việc phân tích use case và edge cases 
trước khi implement, đồng thời thiết kế flow theo hướng linh hoạt hơn.

## 7. AI giúp gì / AI sai gì
- **Giúp:** dùng AI để giúp brainstorm, gen diagram mermaid, tinh chỉnh lại idea,
xây dựng prototype nhanh chóng, hoàn thiện codebase.
- **Sai/mislead:** AI gợi ý tính năng nhắc lịch - có vẻ hợp lý nhưng thực chất chưa
được agent fit (có thể dễ dàng dùng rule-based)

