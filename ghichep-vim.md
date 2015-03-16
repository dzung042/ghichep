﻿# Các chú ý về VIM
- Nơi tổng hợp các kỹ thuật sử dụng VIM hiệu quả hơn.
- Yêu cầu: Đã biết dùng VIM để làm việc, biết các mode trong VIM.

###  Mở file và nhảy đến 1 dòng cụ thể trong file.
```sh
# Cú pháp
vi   +so_dong   file_can_mo

# Ví dụ nhảy tới dòng số 9 trong file etc/passwd
vi +9  etc/passwd
```

###  Mở file và nhảy đến dòng có chứa ký tự chỉ định
```sh
# Cú pháp
vi   +/tu_khoa   file_can_mo

# Ví dụ nhảy tới dòng có từ khóa là `mail` trong file etc/passwd
vi +/mail  etc/passwd
```