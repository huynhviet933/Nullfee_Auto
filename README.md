# Nullfee_Auto
# HƯỚNG DẪN SỬ DỤNG TOOL NULLFEE V2

### 1. Cài đặt thư viện (Chạy lệnh Terminal)
npm install 
### 2. Các File đầu vào (Input - Để cùng thư mục tool)
- proxy.txt: Mỗi dòng 1 proxy (Định dạng: http://user:pass@ip:port)
- user_agents.txt: Danh sách User-Agent (mỗi dòng 1 cái)
- ref.txt: Mã mời của bạn (mỗi dòng 1 mã)
- Mail.txt: Định dạng Mail|pasmail|tokenmail ( mỗi dòng 1 mail )
- config.json: Cấu hình luồng và delay:
{
  "threads": 5,
  "numAccounts": 100,
  "delayAction": [5, 10],
  "delayAccount": [30, 60],
  "threadStarterDelay": [1, 3]
}

### 3. Dữ liệu đầu ra (Output - Tool tự tạo)
- license.txt: Lưu Key bản quyền đã nhập.
- profiles.json: Lưu phiên đăng nhập và trạng thái swap.
- taikhoan.txt: Lưu Username | Password | SID (để login lại).
- EVM.txt: Lưu Private Key | Địa chỉ ví (của acc mới tạo).
- balance.txt: Tổng hợp số dư $NON và $BNB của từng ví.

### 4. Cách chạy
Mở CMD/Terminal tại thư mục tool và gõ:
node main.js
