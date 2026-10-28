# BÀI LÀM – HACKATHON 01

- **Mã đề:** 19
- **Họ tên:** Võ Phan Đăng Khoa
- **Lớp:** CNTT1
- **Link repository:** https://github.com/khoavo050408-crypto/CNTT1_Nhap-mon-CNTT_Hackathon01.git
- **Hệ điều hành (Windows/macOS):** Window

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
pwd
 move-item lich_trinh.txt docs 
 move-item logo_du_lich.PNG media 
 remove-item *.tmp 
  cd.. 
   ls -force

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
 get-content logs/travel.log | select-string "ERROR"                           

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-08-28 08:30:34 [ERROR] Khong tim thay trang /tour-he (404)
2026-08-28 08:36:34 [ERROR] Giu cho that bai

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
 E:\starter-kit\du-lich-website\logs> get-content travel.log | select-string "ERROR" | measure-object                                                 

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
Count    : 6
Average  :
Sum      :
Maximum  :
Minimum  :
Property :

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dat_tour_thang_8.xlsx`, không cần ghi vào đây.
