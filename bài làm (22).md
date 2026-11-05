# Vấn đề :
Giải thích cơ chế Hacker sử dụng mật khẩu rò rỉ từ web nhỏ để chiếm đoạt các tài khoản lớn (domino effect).
# Yêu cầu :
-   Phân tích tại sao mật khẩu cảm tính lại dễ bị bẻ khóa hơn mật khẩu do máy tính sinh ra.
    
-   Sử dụng tiêu chuẩn **AES-256** để giải thích tại sao việc lưu mật khẩu trong Password Manager lại an toàn hơn ghi chép thủ công.
# Cách làm :
1 . Cơ chế tấn công "Domino Effect"

-   Khi diễn đàn nhỏ bị lộ dữ liệu, hacker thu thập cặp Email và Mật khẩu (ví dụ:  123456).
    
-   Do dùng chung một mật khẩu cho nhiều nơi, hacker dùng công cụ quét tự động thử hàng loạt lên các hệ thống lớn  để chiếm đoạt tài khoản.
    

 2. Mật khẩu cảm tính vs Mật khẩu máy tính sinh ra

-   Cảm tính: Dễ đoán, gắn liền với thông tin cá nhân hoặc chuỗi đơn giản (123456), bị bẻ khóa nhanh chóng bằng tấn công từ điển / vét cạn.
    
-   Máy tính sinh ra: Ngẫu nhiên hoàn toàn, kết hợp nhiều loại ký tự và độ dài lớn, giúp loại bỏ hoàn toàn khả năng đoán mò.
    

 3. Password Manager  vs Ghi chép thủ công

-   Ghi chép thủ công : Dễ bị nhìn trộm, mất cắp hoặc lộ lọt vật lý.
    
-   Password Manager (AES-256): Sử dụng chuẩn mã hóa đối xứng 256-bit với không gian khóa khổng lồ , mã hóa toàn bộ dữ liệu cục bộ và chỉ mở được bằng Master Password riêng của bạn.

