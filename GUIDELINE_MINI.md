# Mini guideline — bài làm cá nhân

> Điền nội dung này trước khi bắt đầu gán nhãn. Giữ lại các quyết định sau khi self-QC.

## Định nghĩa lớp

| Lớp | Định nghĩa của bạn | Ví dụ/điểm phân biệt |
| --- | --- | --- |
| `car` |Xe con |Những xe nhỏ có gầm thấp hoặc vừa, đuôi xe thấp hơn nóc xe, có 2-3 cửa kính dọc theo thân xe |
| `truck` |Xe tải |Những xe to có cabin lái tách biệt với thùng chở hàng, gầm từ trung bình đến cao, đuôi xe cao bằng nóc xe,   |
| `bus` |Xe Buýt | Những xe to có kích thước rất dài, có rất nhiều cửa kính dọc theo thân xe |
| `van` |Xe bán tải | Những xe có kích thước trung bình, đầu giống xe con, có thùng chở hàng phía sau|

## Quy tắc chung

- Box bám sát vật thể nghĩa là: box phải bao gồm toàn bộ vật thể, không để thừa hoặc thiếu pixel của vật thể
- Vật thể bị che khuất: vật thể chính bị vật thể khác đè lên, khiến vật thể chính không có toàn bộ hình ảnh
- Vật thể bị cắt bởi rìa ảnh: là vật thể ở góc ảnh, xuất hiện không đầy đủ 
- Vật thể rất nhỏ/mơ hồ: vật thể ở xa, không thể xác định rõ 100% phân loại

## Ghi lại quyết định cho ít nhất ba ca mơ hồ

| Ảnh | Tình huống | Quyết định cuối | Lý do theo schema |
| --- | --- | --- | --- |
| `drive_001.jpg` | Xe góc trên bên phải quá mờ | không label | |
| `drive_002.jps` | Các xe ở giữa phía trên quá mờ không thể xác định category | không label | |
| `drive_003.jpg` | các xe ở góc trên bên trái quá mờ không thể xác định category | không label | |
