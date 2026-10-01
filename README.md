# NOAH boards
Board dàn ý cho team xem và góp ý. Link: https://dontuty123.github.io/noah-boards/

- Mỗi board = 1 thư mục (`magic-world/`), có `BOARD_ID` riêng trong script góp ý → góp ý lưu ở Firestore `boards/<BOARD_ID>/comments`.
- Mỗi ô góp ý có mã cố định (`data-cid`). Cảnh dùng mã `canh-N` gán lúc tạo: KHÔNG đổi, KHÔNG dùng lại; cảnh mới dùng mã mới. Góp ý của mục đã bỏ hiện ở nhóm "Góp ý cho mục đã bỏ".
- `firebase-config.js`: cấu hình dùng chung. `firestore.rules`: dán vào Firebase Console → Firestore → Rules khi thay đổi.
- Xóa góp ý: chỉ qua Firebase Console.
