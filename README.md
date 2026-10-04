# Đế Chế Bỏ Túi

Game chiến thuật kiểu Đế chế rút gọn cho điện thoại, chơi ngay trên trình duyệt. Bản đồ dựng theo xã Diễn Thái (Diễn Châu, Nghệ An).

- Chơi với máy (3 độ khó) hoặc 2 người qua mạng bằng mã phòng 4 số.
- Một người bấm **Tạo phòng**, gửi mã cho bạn; người kia nhập mã rồi bấm **Vào**.
- Hai máy nối trực tiếp qua WebRTC (PeerJS). Máy tạo phòng chạy trận, nên đừng tắt màn hình giữa chừng.

Toàn bộ game nằm trong một file `index.html`, không cần build.

Dữ liệu bản đồ: © những người đóng góp cho OpenStreetMap (giấy phép ODbL), lấy qua Nominatim và Overpass API ngay trên trình duyệt người chơi.

## Phiên bản

- **Bản 4**: bản đồ dựng từ dữ liệu thật của OpenStreetMap (đường, sông, kênh, ao hồ, ruộng, trường, chợ, đình chùa, nhà thờ, tên xóm). Diễn Thái tự tải đường thật khi mở game; mục "Xã khác" cho nhập tên một xã bất kỳ để tải bản đồ về chơi. Khi chơi 2 người, chủ phòng gửi luôn bản đồ cho người vào sau.
- **Bản 3**: thêm âm thanh (chặt cây, đào vàng, gặt lúa, xây nhà, đánh nhau, kèn báo động, nhạc lên đời và thắng thua) và nút tắt tiếng. Tiếng được tạo ngay trong trang, không kèm file nào.
- **Bản 2**: vẽ lại dân, lính, nhà cửa và các địa điểm trong xã. Dân đội nón lá và cầm đúng dụng cụ khi chặt cây, đào vàng, gặt lúa, xây nhà. Lính và nhà đổi dáng khi lên đời.
- **Bản 1** (tag `v1.0`): chơi với máy, bản đồ xã Diễn Thái, 2 người qua mã phòng.
