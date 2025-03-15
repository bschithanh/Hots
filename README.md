# File hots chuẩn và cách chặn web bằng file hots
## [Bấm vào đây để xem](https://bsngchithanh.blogspot.com/2025/03/file-hots-chuan-va-chan-web-bang-file.html)

- Bạn mở **NotePad** bằng quyền **Run as Administrator**, nếu bạn không mở bằng quyền này thì không thể chỉnh sửa được.
- ![image](https://github.com/user-attachments/assets/b902aa90-ff7b-4156-800c-d2191d8f55b4)
- Chọn **File** rồi chọn **Open**, chọn đường dẫn tới file hots là **C:\Windows\System32\Drivers\etc**
- ![image](https://github.com/user-attachments/assets/e391e715-86e4-4689-b05c-ac6142c174c5)
- Nội dụng File hots chuẩn:
  ```php
  # Copyright (c) 1993-2009 Microsoft Corp.
  #
  # This is a sample HOSTS file used by Microsoft TCP/IP for Windows.
  #
  # This file contains the mappings of IP addresses to host names. Each
  # entry should be kept on an individual line. The IP address should
  # be placed in the first column followed by the corresponding host name.
  # The IP address and the host name should be separated by at least one
  # space.
  #
  # Additionally, comments (such as these) may be inserted on individual
  # lines or following the machine name denoted by a '#' symbol.
  #
  # For example:
  #
  #      102.54.94.97     rhino.acme.com          # source server
  #       38.25.63.10     x.acme.com              # x client host
  
  # localhost name resolution is handled within DNS itself.
  #	127.0.0.1       localhost
  #	::1             localhost
  ```

## Chặn một trang web:

Ví dụ: Muốn chặn facebook.com ta thêm dòng lệnh sau đây phía dưới cùng file hots rồi bấm Save là xong:

```php
127.0.0.1 facebook.com
```

Hoặc khi người dùng sử dụng một phần mềm lậu, không muốn cập nhật hoặc không muốn phát hiện thì dùng cách này.

Để phục hồi file hots chúng ta mở Notepad bằng cách trên, rồi copy nội dung file hots nguyên bản phía trên, Save đè lên file hots theo đường dẫn C:\Windows\System32\Drivers\etc là xong Hoặc có thể [download file hots chuẩn](https://raw.githubusercontent.com/bschithanh/nguon/blob/main/hosts) ghi đè vào đường dẫn **C:\Windows\System32\Drivers\etc** là xong!
