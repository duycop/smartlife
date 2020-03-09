# smartlife
Đây là tool để đọc file xml ra yaml cho Hass
Read xml of smartlife (tuya) to Hass

--Đoạn này copy từ tinhte-- 
[tinhte.vn/thread/hass-dieu-khien-cong-tac-wifi-tuya-qua-mang-noi-bo-khong-can-flash-tasmota.3049786/]

1. Trước tiên bạn cần xác định được LocalKey và DeviceId của từng công tắc trong nhà bạn

Phương pháp 1: Sử dụng điện thoại Android

1.1 Sử dụng điện thoại Android đã được Root (Bắt buộc phải là điện thoại đã Root) Hoặc hãy cài Bluestacks trên máy tính

1.2 Root Bluestacks theo hướng dẫn sau: [youtu.be/watch?v=zDdWGBljSsg]

1.3 Cài đặt phiên bản SmartLife v3.6.1 using an APK (Phiên bản mới đã giấu key này nên các bạn nhớ cài phiên bản cũ nhé) - APK tải tại đây: [apkpure.com/smart-life-smart-living/com.tuya.smartlife/download/70-APK]

1.4 Cài đặt ES File Explorer

1.5 Chọn nút có 3 dấu gạch ngang và kéo xuống dưới để enable "Root Explorer" và chọn Allow permission from Supper User.

1.6 Di chuyển đến thư mục chứa dữ liệu "/data/data/com.tuya.smartlife/shared_prefs" và mở file preferences_global_key.xml (nếu bạn không thấy file này thì thử tìm file preferences_global_keyabcxyz12345.xml - trong đó abcxyz12345 là một chuỗi bất kỳ nhé.
bạn sẽ tìm thấy localKey và devId

Phương pháp 2: đọc trong link gốc ở tinhte

--hết copy--

Ở bước 1.4 trên windows có thể dùng tool ngoài là: BlueStacks Tweaker tại [bstweaker.tk] để copy file xml ra
sau khi có file XML rồi thì dùng tool smartlife.html
