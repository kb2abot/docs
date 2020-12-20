# HƯỚNG DẪN CÀI ĐẶT KB2ABOT
Bạn cần đọc kĩ để có thể cài đặt được kb2abot (dễ thôi không khó lắm đâu)
## PHẦN MỀM BẮT BUỘC
Bạn buộc phải có các phần mềm dưới để có thể chạy được kb2abot!<br>
**Với máy tính:**
* [NodeJs](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)

**Với điện thoại:**  (ứng dụng termux)
```
pkg install nodejs
```
```
pkg install git
```
## CÀI ĐẶT
```
npm install
```

## CẬP NHẬT
```
npm start
```
Bot sẽ tự động kiểm tra các bản cập nhật và tải về.
<br>
Hoặc cập nhật thông qua dòng lệnh:
```
npm run update
```
**Lưu ý: Nếu trong quá trình cập nhật bị lỗi thì bạn chạy file [CLEAN-SETUP.sh] nhé!**
## CHẠY BOT

### Bước 1: Tải cookie về /bots
**Nếu bạn đang xài máy tính:**
Tải extension [J2TEAM Cookies](https://chrome.google.com/webstore/detail/j2team-cookies/okpidcojinmlaakglciglbpcpajaibco) về, sau đó bấm nút **export** trong tiện ích trên khi đang ở trang **facebook.com**.

**Nếu bạn đang xài điện thoại:**
Cài trình duyệt **Kiwi** trên Playstore hay Appstore gì đó rồi lại tải extension [J2TEAM Cookies](https://chrome.google.com/webstore/detail/j2team-cookies/okpidcojinmlaakglciglbpcpajaibco) về và bấm nút **export** trong lúc  đang ở trang **m.facebook.com**. Hoặc bạn cũng có thể export cookie trên máy tính rồi lưu ở chỗ nào đó sao cho điện thoại bạn có thể copy được đoạn cookie đó.
Sau khi có được đoạn cookie trên, bạn hãy copy nó rồi cài vim (trong termux):
```
pkg install vim
```
Sau đó mount vào /bots và tạo file cookie bằng vim:
```
cd bots
vim <tên gì đó>.json
```
Vim sẽ mở lên, bạn chỉ việc paste hết đoạn cookie nãy vào chỗ đó, sau đó **bấm ESC** (ở phía trên bàn phím) và gõ **:wq** để thoát vim và lưu lại (**:qa** để thoát và không lưu)
### Bước 2: Đổi tên cookie (không bắt buộc)
Đổi tên file bạn mới tải về đó (www.facebook.com_xx-xx-xxxx.json) thành tên mà bạn muốn (vd: khoakomlem.json) và đặt vào thư mục /bots.
**Note:** nếu có nhiều file cookie ở trong /bots thì bot sẽ hỏi bạn chọn những file nào để chạy bot thì bạn bấm **space để chọn** và **enter để xác nhận** nhé!
### Bước 3: Chạy bot
Chạy file **[WINDOW] START.bat** nếu máy bạn là window, **START.sh** nếu máy bạn không phải là window (hoặc cũng có thể chạy bot thông qua lệnh: **npm start**
<br><br>
# Cảm ơn đã sử dụng kb2abot ♥
