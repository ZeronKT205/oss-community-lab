# 🤝 Hướng dẫn đóng góp mã nguồn cho dự án

Chào mừng bạn đã đến với dự án! Chúng tôi rất hào hứng khi nhận được sự hỗ trợ từ phía cộng đồng. Để đảm bảo chất lượng mã nguồn, vui lòng tuân thủ quy trình sau.

## 🚀 Quy trình làm việc (Workflow)

1. **Fork** kho lưu trữ này về tài khoản cá nhân của bạn.
2. Tạo một nhánh tính năng mới đi ra từ nhánh `main` sạch:

   ```bash
   git checkout -b feat/ten-tinh-nang
   ```

3. Tiến hành viết code, đảm bảo code đã chạy qua hệ thống test cục bộ. Với chương trình hiện tại, biên dịch và chạy theo README, kiểm tra kết quả là `OSS Community Lab`.
4. Commit mã nguồn theo chuẩn Conventional Commits. Ví dụ:

   ```text
   feat(core): add json support
   ```

5. Đẩy nhánh lên GitHub của bạn và mở một Pull Request hướng về nhánh `main` của kho gốc.

## 🎨 Quy chuẩn viết code (Coding Standards)

- Ngôn ngữ C: Thụt lề bằng 4 khoảng trắng, không sử dụng Tab.
- Đặt tên biến theo chuẩn `snake_case`, ví dụ: `user_id`, `max_length`.
- Mọi hàm mới bổ sung cần có comment đặc tả giải thích rõ chức năng.
