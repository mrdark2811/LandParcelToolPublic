<p align="center"><img src="logo.png" width="128" alt="LandParcelTool"></p>

# LandParcelTool – Xử lý hồ sơ thửa đất

Đọc Đơn đăng ký, Thông báo và thẻ căn cước từ file PDF scan, đối chiếu chéo, rồi xuất file PDF theo
thửa và biểu mẫu bàn giao Excel.

## Tải về

| | |
|---|---|
| **Bản giải nén là chạy (khuyên dùng)** | [LandParcelTool.App-win-Portable.zip](https://github.com/mrdark2811/LandParcelToolPublic/releases/latest/download/LandParcelTool.App-win-Portable.zip) |
| Bản cài đặt | [LandParcelTool.App-win-Setup.exe](https://github.com/mrdark2811/LandParcelToolPublic/releases/latest/download/LandParcelTool.App-win-Setup.exe) |

Cả hai bản đều tự cập nhật khi có phiên bản mới.

## Cài lần đầu (bản giải nén)

1. Tải file `LandParcelTool.App-win-Portable.zip` ở trên về.
2. **Chuột phải vào file zip → Properties (Thuộc tính) → đánh dấu ô "Unblock" (Bỏ chặn) ở góc dưới → OK.**
   Làm bước này thì Windows sẽ không hiện cảnh báo khi mở phần mềm.
3. Chuột phải → Extract All (Giải nén tất cả) vào một thư mục cố định, ví dụ `D:\LandParcelTool`.
   Đừng chạy thẳng từ trong file zip, và đừng để trong thư mục Downloads rồi xoá mất.
4. Mở thư mục vừa giải nén, bấm đúp **LandParcelTool.exe**.

**Nếu quên bước 2** và Windows hiện màn hình xanh "Windows đã bảo vệ máy tính của bạn":
bấm **"Thông tin bổ sung" (More info)** rồi bấm **"Vẫn chạy" (Run anyway)**. Chỉ cần làm một lần;
các bản cập nhật về sau phần mềm tự tải nên không hiện cảnh báo nữa.

Cảnh báo này xuất hiện với mọi phần mềm nhỏ chưa mua chứng thư ký số của Microsoft, không có nghĩa
là phần mềm có virus.

## Sau khi mở

1. Vào **Cấu hình → Dịch vụ AI**, chọn một dịch vụ và dán API key. Nên dùng **FPT AI** (máy chủ ở
   Việt Nam). Bấm **Kiểm tra kết nối** rồi **Lưu**.
2. Vào **Cấu hình → Thông tin đợt**, điền mã xã và thông tin đợt.
3. Vào **Nhập hồ sơ**, chọn file PDF của từng loại giấy, bấm chạy.

## Mua key và hỗ trợ

Mỗi key dùng cho một máy tính. Cần mua key, chuyển key sang máy mới, hay gặp lỗi khi dùng:
**Zalo / điện thoại 0828 112 955**. Khi nhắn, gửi kèm **mã máy** hiện trên màn hình Kích hoạt.

## Yêu cầu máy

- Windows 10 (bản 2004 trở lên) hoặc Windows 11, 64-bit.
- RAM 8 GB trở lên, ổ đĩa trống khoảng 1 GB cộng thêm chỗ cho file scan.
- Có Internet nếu dùng AI trên mạng (FPT AI, Gemini, OpenAI).

## Dữ liệu của bạn nằm ở đâu

Hồ sơ, giá trị đã sửa và cấu hình nằm ở `%LocalAppData%\LandParcelTool\Data`, tách riêng khỏi thư
mục phần mềm. Cập nhật hay xoá phần mềm đều không đụng tới dữ liệu này.

Nên sao lưu định kỳ: **Cấu hình → Sao lưu dữ liệu → Sao lưu ngay**. Phần mềm cũng tự sao lưu khi
đóng và trước mỗi lần cập nhật.

Hồ sơ không được gửi tới người bán phần mềm. Ảnh hồ sơ chỉ đi từ máy bạn tới dịch vụ AI do chính
bạn chọn trong Cấu hình.
