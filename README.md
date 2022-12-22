# docs_note
- Detail Book => {
  + User chọn số lượng, thời gian thuê rồi ấn thuê
  => Trả ra trang thanh toán, có tiền cọc = tiền sách, tiền thuê * số lượng * (thời gian trả - thời gian thuê) 
  => Chia ra 2 cột là tổng tiền cọc và tổng tiền thuê. Tiền thuê sẽ thanh toán Paypal (*) còn tiền cọc sẽ lưu vào Wallet(Ví) của User (*)

}

- Notification => {
  + Khi vào trang thanh toán tiền thuê. Thì phải hiện ra dòng chữ cảnh báo người dùng về các nội quy trả sách  (*)
  + Có 2 case chính cần follow
    1) Quá hạn 30 ngày sẽ trừ 100% tiền cọc trong Ví Usser
    2) Quá hạn 1 tuần thì sẽ trừ 20% số tiền cọc trong ví
  + Sách khi trả bị rách hay bẩn so với ban đầu có thể trừ ? % tùy theo đánh giá của Admin. (*)
  + Sau khi đến hạn trả mà chưa trả thì phải thông báo qua mail hay sdt cho người thuê.  (*)
}

- Transacsion History {
  + Admin có thể xem lịch sử thanh toán và order của User.
  + Có thể thay đổi Wallet User trong trường hợp trả sách lấy tiền hoặc k trả sách (trừ cọc)  (*)
}

- Về phần thanh toán làm như bình thường
