# Quy trình nghiệp vụ

- Quản lý thông tin nhân viên: Thông tin cá nhân, thông tin công việc, quá trình làm việc, thông tin BHXH, phụ cấp
- Quản lý hiệu quả kế hoạch nghỉ phép cho tất cả nhân viên bằng cách tự động tính toán số ngày nghỉ phép theo Luật lao động hiện hành. Quản lý ngày nghỉ phép, làm thêm giờ của nhân viên linh hoạt
- Nhân viên phụ trách tính lương thực hiện nhập các dữ liệu đầu vào cấu thành bảng lương như: dữ liệu chấm công nhật, dữ liệu tính công làm thêm, công theo ca, các khoản phụ cấp, các khoản khấu trừ,...Bên cạnh đó, nhân viên phụ trách cần tạo các thông số mặc định liên quan đến bảng lương như: Lương chức danh, lương bảo hiểm, thuế TNCN, người phụ thuộc, ... ở trong phân hệ Quản lý Nhân viên
- Nhân viên tính lương xây dựng dữ liệu phần tử lương, cấu trúc lương áp dụng cho toàn công ty hoặc áp dụng cho từng bộ phận nhân viên của công ty. Mỗi cấu trúc lương thì bao gồm các thành phần (phần tử) lương khác nhau, phụ thuộc vào từng vị trí công việc

**Các luồng quy trình**

·	Nhân viên. Chi tiết nghiệp vụ **[tại đây](#nhan-vien)**

·	Tổng hợp công. Chi tiết nghiệp vụ **[tại đây](#tong-hop-cong)**

·	Ca làm việc. Chi tiết nghiệp vụ **[tại đây](#ca-lam-viec)**

·	Phân ca chi tiết. Chi tiết nghiệp vụ **[tại đây](#phan-ca-chi-tiet)**

·	Đề nghị đổi ca. Chi tiết nghiệp vụ **[tại đây](#de-nghi-doi-ca)**

·	Đăng ký công. Chi tiết nghiệp vụ **[tại đây](#dang-ky-cong)**

·	Đăng ký phân bổ. Chi tiết nghiệp vụ **[tại đây](#dang-ky-phan-bo)**

·	Cấu trúc lương. Chi tiết nghiệp vụ **[tại đây](#cau-truc-luong)**

·	Bảng lương. Chi tiết nghiệp vụ **[tại đây](#bang-luong)**

## *Nhân viên*

### Tạo mới nhân viên

**Đối tượng thực hiện:**

***Bước 1:*** Nhân viên quản trị nhân lực Vào **Tiền lương > Nhân viên>Tạo**

![](images\Ảnh kế toán lương\fin_tienluong_nhanvien01.png)

***Bước 2:*** Thực hiện khai báo thông tin của nhân viên:

- Khai báo thông tin cá nhân cơ bản về nhân viên (căn cứ vào Sơ yếu lý lịch) như: họ tên, giới tính, ngày sinh, nơi sinh, nguyên quán, hộ khẩu thường trú, số CMND, ngày cấp, nơi cấp, trình trạng hôn nhân, dân tộc, tôn giáo, …

- Khai báo thông tin công việc của nhân viên: chức danh, phòng ban, người quản lý, tài khoản đăng nhập của nhân viên

- Khai báo các thông tin về Phụ cấp, Thông tin BHXH (nếu có)

![](images\Ảnh kế toán lương\fin_tienluong_nhanvien02.png)

### Tạo quá trình làm việc

**Các bước thực hiện**

**Bước 1:** Tìm kiếm nhân viên cần cập nhật thông tin tại màn hình **Danh sách nhân viên**

**Bước 2:** Tại tab **Quá trình làm việc** chọn **Sửa>Thêm mới**, thực hiện cập nhật thông tin về sự thay đổi về chức danh của nhân viên trong quá trình làm việc như: Bổ nhiệm, Miễn nhiệm, Điều chuyển, Tiếp nhận,….

·     Tuyển mới: Nhân viên nhân sự tạo mới quá trình làm việc cho người lao động

·     Bổ nhiệm: Nhân viên nhân sự được phép thay đổi thông tin về Chức danh - đơn vị

·     Tiếp nhận: Nhân viên nhân sự không được phép thay đổi thông tin trong hợp đồng

·     Điều chuyển: Nhân viên nhân sự được phép thay đổi thông tin về Chức danh - đơn vị, Lương và bảo hiểm

·     Nghỉ thai sản: Nhân viên nhân sự không được phép thay đổi thông tin trong hợp đồng

·     Nghỉ ốm dài ngày: Nhân viên nhân sự không được phép thay đổi thông tin trong hợp đồng

·     Nghỉ chờ hưu: Nhân viên nhân sự không được phép thay đổi thông tin trong hợp đồng

·     Nghỉ tạm hoãn hợp đồng: Nhân viên nhân sự không được phép thay đổi thông tin trong hợp đồng

![](images\Ảnh kế toán lương\fin_tienluong_nhanvien03.png)

### Nhập dữ liệu từ excel

**Nhập dữ liệu nhân viên mới**

**Mục đích sử dụng**

Trong trường hợp người dùng muốn thực hiện nhập nhiều nhân viên thì sử dụng tính năng "Thêm bản ghi" trên hệ thống.

**Các bước thực hiện**

***Bước 1:*** Vào menu Tiền lương >> Yêu thích >> Thêm bản ghi!

![img](images\Ảnh kế toán lương\fin_tienluong_nhanvien04.png)

***Bước 2:***

- Tại đây, người dùng bấm "Tải biểu mẫu danh sách nhân viên" để tải xuống file mẫu nhập dữ liệu 

  ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien05.png)

- Người dùng nhập dữ liệu thông tin nhân viên vào file excel.

  ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien06.png)

***Bước 3:*** Trên giao diện phần mềm, người dùng bấm nút ![](fin_tienluong_naptaptin_btn.png) >> hệ thống hiển thị màn hình như sau ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien07.png)

 Tại đây người dùng kiểm tra thông tin dữ liệu, và bấm nút ![](images\Ảnh kế toán lương\fin_tienluong_kiemthu_btn.png)để hệ thống kiểm tra dữ liệu trước khi nhập >> Hệ thống tự động kiểm tra và thông báo kết quả lỗi dữ liệu lên màn hình >> Người dùng đọc thông báo và điều chỉnh dữ liệu trên file excel để chính xác, sau đó bấm ![](images\Ảnh kế toán lương\fin_tienluong_naptaptin_btn.png)) để tải lại file sau khi chỉnh sửa dữ liệu >> Tiếp tục bấm **Kiểm thử** để kiểm tra cho đến khi kết quả hệ thống kiểm tra thông báo là ![](images\Ảnh kế toán lương\fin_tienluong_tbaohople.png)

***Bước 4:*** Người dùng bấm nút ![](images\Ảnh kế toán lương\fin_tienluong_nhap_btn.png) để thực hiện nạp dữ liệu vào hệ thống >> Hệ thống ghi nhận dữ liệu và hiển thị thông báo Thêm bản ghi thành công.

***Các lỗi thường gặp và cách xử lý:***

1. ***Thiếu dữ liệu các trường bắt buộc:***

   - Nguyên nhân: Không nhập thông tin cho các trường bắt buộc

   - Cách xử lý: Nhập đầy đủ thông tin cho các trường

     ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien08.png)

2. ***Mã nhân viên không tồn tại:***

   - Nguyên nhân: Mã nhân viên đã tồn tại trong hệ thống.
   - Cách xử lý: Mã nhân viên là duy nhất, kiểm tra và nhập lại mã chưa có trong hệ thống

   ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien09.png)

3. ***Nhập hộ khẩu thường trú không hợp lệ:***

   - Nguyên nhân: Nhập không đầy đủ đơn vị hành chính. Ví dụ: Hà Nội, Đống Đa, Dịch Vọng Hậu

   - Cách xử lý: Nhập đầy đủ đơn vị hành chính: Hà Nội, Quận Đống Đa,  P.Dịch Vọng Hậu. Nên tải file dữ liệu mẫu đơn vị hành chính từ hệ thống về để nhập dữ liệu chính xác 

     ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien10.png)

4. ***Trường ngày tháng không đúng định dạng:***

   - Nguyên nhân: Nhập ngày không có, ví dụ 29/2/2022; nhập định dạng ngày tháng khác định dạng dd/mm/yyyy

   - Cách xử lý: Nhập đúng ngày, đúng định dạng

     ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien11.png)

**Nhập dữ liệu quá trình trong hồ sơ của nhân viên** 

**Mục đích sử dụng**

Nhập hàng loạt thông tin các quá trình trong hồ sơ nhân viên. Các thông tin có thể nhập bao gồm: Thông tin công việc, Quá trình làm việc, Phụ cấp, Hồ sơ, Đăng ký công, Thông tin BHXH, Thu nhập.

**Đối tượng thực hiện**

Cán bộ Quản lý Nhân sự, (tức là người dùng được phân quyền Quản trị tại module Nhân viên).

**Các bước thực hiện:**

***Bước 1:*** Người dùng truy cập vào menu Tiền lương : Màn hình hiển thị Danh sách Nhân viên.

![img](images\Ảnh kế toán lương\fin_tienluong_nhanvien01.png)

***Bước 2:*** Vào mục Yêu thích > Chọn mục **Import dữ liệu thông tin nhân viên**

![img](images\Ảnh kế toán lương\fin_tienluong_nhanvien12.png)

***Bước 3***: Hoàn thành thông tin cần nhập liệu

- *Tải file mẫu:* Người dùng thực hiện tải file mẫu bằng cách bấm vào dòng chữ "Mẫu nhập cho thông tin nhân viên"![](images\Ảnh kế toán lương\fin_tienluong_nhanvien13.png)

* *Hoàn thiện dữ liệu cần nhập:* Người dùng thực hiện điền dữ liệu vào file theo mẫu vừa tải về (nhập đúng trang tính và đầy đủ thông tin theo cột). Lưu lại thông tin đã nhập.

![](images\Ảnh kế toán lương\fin_tienluong_nhanvien14.png)

***Bước 4:*** Trên màn hình hệ thống, nhấn vào Nạp tập tin ![](images\Ảnh kế toán lương\fin_tienluong_naptaptin_btn.png) và tải lên tập tin vừa lưu

- Lựa chọn trang dữ liệu cần import: Biểu mẫu tải về chứa nhiều trang thông tin, người dùng có thể nhập một trong các trang dữ liệu đó và chọn đúng trang tính cần nhập dữ liệu để tải lên

  ![](![](images\Ảnh kế toán lương\fin_tienluong_nhanvien15.png)

- Kiểm tra việc gắn dữ liệu theo cột trên file excel với các cột dữ liệu trên hệ thống

- Sau đó, bấm nút ![](images\Ảnh kế toán lương\fin_tienluong_kiemthu_btn.png) để hệ thống kiểm tra dữ liệu trước khi nhập >> Hệ thống tự động kiểm tra và thông báo kết quả lỗi dữ liệu lên màn hình >> Người dùng đọc thông báo và điều chỉnh dữ liệu trên file excel để chính xác, sau đó bấm ![](images\Ảnh kế toán lương\fin_tienluong_naptaptin_btn.png) để tải lại file sau khi chỉnh sửa dữ liệu >> Tiếp tục bấm **Kiểm thử** để kiểm tra cho đến khi kết quả hệ thống kiểm tra thông báo là ![](images\Ảnh kế toán lương\fin_tienluong_tbaohople.png)

- Người dùng bấm vào nút ![](images\Ảnh kế toán lương\fin_tienluong_nhap_btn.png) để tải lên dữ liệu. Hệ thống sẽ hiển thị thông báo Thêm bản ghi thành công sau khi hoàn tất nạp dữ liệu.

**Các lỗi thường gặp và cách xử lý:**

1. ***Tệp dường như không có nội dung:***

   - Nguyên nhân: Tập tin tải lên chứa nhiều trang tính. Người dùng chỉ có thể chọn 01 trang tính để nhập dữ liệu vào hệ thống, và chọn trang tính chưa nhập thông tin

   - Cách xử lý: Chọn đúng trang tính đã nhập thông tin và cần nhập dữ liệu

     ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien16.png)

2. ***Mã nhân viên không tồn tại:***

   - Nguyên nhân: Mã nhân viên chưa có trong hệ thống, nhập sai mã nhân viên.
   - Cách xử lý: Kiểm tra lại mã nhân viên, sửa lại trong file và nạp lại tập tin

   ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien17.png)

3. ***Không phải số tự nhiên* đối với trường Tỷ lệ hưởng lương:***

   - Nguyên nhân: Thêm dấu % phía sau tỉ lệ

   - Cách xử lý: Chỉ nhập số tự nhiên, không thêm các kí tự đặc biệt khác

     ![](images\Ảnh kế toán lương\fin_tienluong_nhanvien18.png)

## *Chấm công - Đăng ký công*

#### Thiết lập ký hiệu công

***Đối tượng thực hiện: Người quản trị hệ thống hoặc người quản trị phân hệ Chấm công***

Ký hiệu công (hay còn gọi là "Loại ngày làm"), là danh sách các ký hiệu hiển thị lên bảng chấm công tương ứng cho các loại ngày làm, ví dụ như công đi làm (X), công nghỉ phép (P), công làm tăng ca (OT),...

Dữ liệu ký hiệu công (loại ngày làm) này được sử dụng để thiết lập các loại đăng ký công thì thiết lập tương ứng.

Hiện tại, khi người dùng cài đặt thành công phân hệ Chấm công, hệ thống đã tạo sẵn bộ dữ liệu các ký hiệu công phổ biến, thường dùng cho tất cả các doanh nghiệp. Người dùng kiểm tra dữ liệu trên hệ thống và điều chỉnh dữ liệu phù hợp bằng cách thao tác như sau:

- Vào menu **Chấm công** >> Chọn **Ký hiệu công**. Hệ thống hiển thị màn hình sau

![](images\Ảnh kế toán lương\fin_tienluong_chamcong01.png)

***Lưu ý***: *Các dữ liệu có sẵn này không được phép xoá. Người dùng có thể tạo thêm ký hiệu công mới bằng cách bấm Tạo và nhập dữ liệu phù hợp, sau đó thực hiện Lưu.*

#### Thiết lập loại đăng ký công

***Đối tượng thực hiện: Người quản lý công hoặc Người quản trị phân hệ Đăng ký công.***

**Mục đích:** Thiết lập các loại đăng ký công tương ứng với các ký hiệu công, để khi nhân viên đăng ký công thuộc loại đăng ký công nào thì khi cán bộ chấm công tổng hợp công, hệ thống tự động hiển thị đúng loại ký hiệu công tương ứng lên bảng công.

**Thực hiện trên hệ thống:** Người dùng vào menu **Đăng ký công** >> Chọn **Loại đăng ký**. Hệ thống hiển thị màn hình sau

![](images\Ảnh kế toán lương\fin_tienluong_loaidangkycong.png)

Ngay khi người dùng cài đặt thành công phân hệ "Đăng ký công", hệ thống tự động tạo sẵn bộ dữ liệu các loại đăng ký với bộ ký hiệu công khởi tạo. Người dùng có thể thêm loại đăng ký mới bằng cách bấm nút **Tạo**, nhập các thông tin yêu cầu, bấm **Lưu** để hoàn tất.

![](images\Ảnh kế toán lương\fin_tienluong_loaidangkycong01.png)

**Lưu ý 1 :** ***Các thông tin cần nhập***

- Loại ngày làm: Chọn 1 trong số các loại ngày làm đã khai báo ở bước **Thiết lập đăng ký công**
- Ngày xác nhận: Nhập khoảng thời gian cho phép đăng ký công với loại đăng ký này
- Công trong: Chọn Ngày/Nửa ngày/Giờ tương ứng với đơn vị thời gian nghỉ cho loại đăng ký này. Ví dụ như hình trên, thì với loại đăng ký công là "Nghỉ dưỡng năm 2021", nhân viên được phép đăng ký nghỉ theo ngày (1 ngày, 2 ngày, ...)
- Đăng ký phân bổ: Tích chọn chế độ đăng ký phân bổ phù hợp, cụ thể
- Không giới hạn: Tức là với phân bổ kế hoạch đăng ký công thuộc loại đăng ký này thì không cần người phê duyệt. Có thể hiểu là nhân viên có thể tuỳ ý đăng ký kế hoạch cho loại đăng ký này.
- Thiết lập bởi người quản lý công: Tức là người quản lý công mới có quyền cấp phát phân bổ thời gian cho loại đăng ký công này
- Đăng ký công: Tích chọn chế độ phê duyệt đăng ký công phù hợp, cụ thể
- Không phê duyệt: Tức là các đơn đăng ký công thuộc loại đăng ký công này thì không cần phê duyệt, đơn có hiệu lực được duyệt ngay tại thời điểm nhân viên đăng ký
- Người quản lý công: Tức là đơn đăng ký công thuộc loại này phải được phê duyệt bởi người quản lý công mới có tính hiệu lực
- Quản lý nhân viên: Tức là đơn đăng ký công thuộc loại này phải được phê duyệt bởi quản lý cấp trên trực tiếp của nhân viên
- Quản lý nhân viên và quản lý công: Tức là đơn đăng ký công thuộc loại này phải được phê duyệt lần 1 bởi quản lý nhân viên, và phê duyệt lần 2 bởi người quản lý công mới có hiệu lực.

***Lưu ý 2:*** ***Các loại đăng ký có sẵn trên hệ thống thì không cho phép người dùng xoá.***

#### Tổng hợp công

***Đối tượng thực hiện: Người quản trị phân hệ Chấm công (Cán bộ chấm công)***

##### Chấm công nhanh

Hằng ngày, hệ thống sẽ tự động đồng bộ và chấm công cho nhân viên dựa dựa theo hình thức chấm công đã được thiết lập ở bước [này](https://guide.vess.vn/hrm/attendance/#Thiết lập hình thức chấm công) và các dữ liệu lịch sử vào/ra, lịch sử đăng ký công nghỉ, công làm thêm của nhân viên đã được duyệt. Thông tin chấm công sẽ hiển thị lên bảng công cho tất cả nhân viên.

Người dùng xem bảng tổng hợp công trên hệ thống bằng cách vào menu **Chấm công** >> Chọn **Tổng hợp công** >> Hệ thống hiển thị dữ liệu chấm công của tất cả nhân viên tại tháng hiện tại như hình sau:

![](images\Ảnh kế toán lương\fin_tienluong_tonghopcong01.png)

***Lưu ý:***

- *Để chấm công được cho nhân viên, thì bắt buộc cán bộ nhân sự phải thiết lập quá trình làm việc cho nhân viên tại bước Quản trình làm việc*
- **Hệ thống tự động chấm công hàng đêm, nên nhân viên bắt đầu làm việc ngày n thì ngày n + 1 có dữ liệu chấm công.*
- *Trong trường hợp ngày n, cán bộ chấm công muốn chốt công luôn; để lấy được cả dữ liệu chấm công ngày hiện tại, người dùng thực hiện đồng bộ công bằng cách bấm Đồng bộ >> Chọn thời gian cần đồng bộ >> Hệ thống hiển thị cảnh báo sẽ xoá toàn bộ dữ liệu trên bảng công trong khoảng thời gian được chọn và tự động đồng bộ lại >> Người dùng xác nhận Đồng ý >> Hệ thống thực hiện đồng bộ và hiển thị lại bảng công.*
- *Cán bộ chấm công có thể thực hiện xuất dữ liệu bảng công bằng cách bấm Xuất báo cáo*

##### Chấm công thủ công

Vào menu **Chấm công** >> Chọn **Tổng hợp công** >> Màn hình hiển thị bảng tổng hợp công. Cán bộ chấm công có thể sửa, hoặc thêm mới công cho nhân viên bằng cách click đúp vào ô công của nhân viên, màn hình hiện ra như sau:

![](images\Ảnh kế toán lương\fin_tienluong_tonghopcong02.png)

Cán bộ chấm công thực hiện nhập/ sửa công vào ô **Thời gian làm** theo quy tắc: **[Ký hiệu công 1]:[Số giờ công]; [Ký hiệu công 2]: [Số giờ công]** và bấm **Lưu & Đóng**

Trong trường hợp muốn xoá công của nhân viên, cán bộ chấm công click vào ô công của nhân viên, chọn biểu tượng "x" để xoá công.

Ví dụ: CB chấm công chấm cho đ/c Trần Bảo Châu đi làm thêm giờ (Ký hiệu: OT), cả ngày 14/05/2022 (8 tiếng). CB chấm công nhập OT:8, cụ thể:

![](images\Ảnh kế toán lương\fin_tienluong_tonghopcong03.png)

Sau khi bấm **Lưu & Đóng**, màn hình sẽ hiển thị DS như dưới và ghi nhận thành công.

![](images\Ảnh kế toán lương\fin_tienluong_tonghopcong04.png)

##### Import công từ file excel

**Mục đích sử dụng**: Công ty không sử dụng quy trình chấm công theo quy trình hướng dẫn ở trên, nhưng muốn Import dữ liệu chấm công quản lý từ file excel lên hệ thống, phục vụ làm dữ liệu đầu vào để tính lương.

**Các bước thực hiện:**

***Bước 1***: Tải file mẫu import

Trên màn hình tổng hợp công, người dùng bấm vào nút **Nhập dữ liệu** để mở ra hộp thoại import công >> Bấm **Xuất biểu mẫu** để tải file mẫu dữ liệu chấm công

![](images\Ảnh kế toán lương\fin_tienluong_tonghopcong05.png)

***Bước 2***: Nhập dữ liệu vào file excel

Người dùng thực hiện nhập liệu công vào file excel theo mẫu vừa tải xuống ở bước 1, ví dụ minh hoạ ở ảnh sau

Lưu ý: Bắt buộc nhập Tháng, Năm, Mã nhân viên và dữ liệu chấm công. Dữ liệu công nhập theo quy tắc: **[Ký hiệu công]:[Số giờ công]**

![](images\Ảnh kế toán lương\fin_tienluong_tonghopcong06.png)

***Bước 3***: Nhập file lên hệ thống

Trên màn hình ở bước 1, người dùng bấm **Tải lên tập tin của bạn**, chọn file excel cần nhập, bấm **Nhập tệp** để xác nhận >> Hệ thống kiểm tra dữ liệu trên file excel

- Nếu có lỗi: Hệ thống hiển thị màn hình thông báo lỗi như minh hoạ

![](images\Ảnh kế toán lương\fin_tienluong_tonghopcong07.png)

- Nếu không có lỗi: Hệ thống thực hiện import, và tự tải lại trang màn hình tổng hợp công sau khi đã ghi nhận dữ liệu trên file excel
- Người dùng bắt buộc nhập mã nhân viên (dạng text), nhập dữ liệu chấm công; tên nhân viên không bắt buộc nhập.

**Một số cảnh báo lỗi nhập tệp thường gặp và cách xử lý**

1. ***"Nhân viên không hợp lệ"***

   - Nguyên nhân: Mã nhân viên không tồn tại, hoặc không thuộc quyền quản lý của người dùng đang thao tác hoặc nhân viên chưa có quá trình làm việc tại ngày chấm công.

   - Xử lý: Kiểm tra lại mã nhân viên tại dòng cảnh báo, điều chỉnh phù hợp.

2. ***"Thời gian làm việc không hợp lệ"***

   - Nguyên nhân: Dữ liệu chấm công sai quy tắc hoặc sai ký hiệu công, hoặc tổng số giờ làm trong ngày vượt quá giờ công chuẩn theo cấu hình lịch làm việc cho nhân viên

   - Xử lý: Kiểm tra lại dữ liệu chấm công theo dòng và cột, đảm bảo đúng ký hiệu công, đúng quy tắc. Tiếp đến kiểm tra thêm tổng số giờ công làm việc (Bao gồm loại công Nghỉ có lương & Nghỉ không lương & Chấm công) và số giờ làm việc chuẩn trên lịch làm việc của nhân việc.

     Xem lịch làm việc của nhân viên: Vào menu **Nhân viên**, bấm xem chi tiết 1 nhân viên, tab **Thông tin công việc**, trường **Giờ làm việc**

     ![](images\Ảnh kế toán lương\fin_tienluong_tonghopcong08.png)

     ![](images\Ảnh kế toán lương\fin_tienluong_tonghopcong09.png)

   - Ví dụ ngày thứ 2, theo lịch làm việc, tổng số giờ làm chuẩn là 8h. Nếu người dùng nhập dữ liệu chấm công ngày thứ 2 cho nhân viên có tổng công nghỉ có lương + nghỉ không lương + chấm công vượt quá 8h thì hệ thống cảnh báo. Người dùng thực hiện điều chỉnh dữ liệu chấm công hoặc điều chỉnh giờ làm việc phù hợp.

3. ***"Tháng ... không có ngày ..."***

   - Nguyên nhân: Nhập thừa dữ liệu chấm công. Ví dụ tháng 6 chỉ có 30 ngày nhưng lại nhập cả dữ liệu chấm công của ngày 31.

   - Xử lý: Xoá bỏ dữ liệu chấm công không hợp lệ, và import lại file.

### Chấm công phân ca

Chức năng này phục vụ cho các công ty, đơn vị có nhiều ca làm việc, và phân bổ ca làm việc khác nhau cho các nhân viên.

#### Thiết lập phân ca

**Đối tượng sử dụng:** Cán bộ Nhân sự, Cán bộ chấm công

**Mục đích sử dụng:**

·     Người dùng tạo ca làm việc, chi tiết phân ca, đổi ca làm việc cho nhân viên để phù hợp với tình hình hoạt động của công ty.

·     Nhân viên có hình thức làm việc theo ca thì người dùng mới có thể phân ca cho nhân viên đó. Hình thức làm việc của nhân viên được thiết lập trong mục **Người quản lý** >> **Nhân viên** >> **Thông tin công việc** >> **Lịch làm việc** >> **Hình thức làm việc**

![](images\Ảnh kế toán lương\fin_tienluong_thietlapphanca.png)

#### Thiết lập ký hiệu công

Kí hiệu công là kí hiệu hiển thị trong bảng tổng hợp công, qua kí hiệu đó người dùng biết được loại ngày làm việc của các nhân viên để dễ dàng tổng hợp theo loại công và tính lương, ví dụ: ký hiệu **X** thể hiện công ngày thường, kí hiệu **OT**: công tăng ca.

***Các bước thực hiện:\***

***Bước 1:*** Người dùng truy cập vào ứng dụng **Chấm công** > Chọn **Ký hiệu công**: Hiển thị danh sách kí hiệu công > Nhấn nút **Tạo**

![](images\Ảnh kế toán lương\fin_tienluong_thietlapkyhieucong01.png)

***Bước 2:*** Nhập tên công, mã công, loại công > Nhấn **Lưu**

![](images\Ảnh kế toán lương\fin_tienluong_thietlapkyhieucong02.png)

#### Thiết lập ca làm việc

***Bước 1:*** Người dùng truy cập vào ứng dụng **Chấm công** > Chọn  **Ca làm việc**: Hiển thị danh sách ca làm việc > Nhấn nút **Tạo**

![](images\Ảnh kế toán lương\fin_tienluong_thietlapcalamviec01.png)

***Bước 2:*** Điền đầy đủ thông tin vào các trường bắt buộc > Nhấn **Lưu**

![](images\Ảnh kế toán lương\fin_tienluong_thietlapcalamviec02.png)

Tại màn hình Danh sách ca làm việc, thêm mới một bản ghi Ca làm việc vừa tạo

**Lưu ý:** *Các ca làm việc khác nhau, nhưng cùng tính chất thì người dùng có thể thiết lập chung 1 ký hiệu công*

![](images\Ảnh kế toán lương\fin_tienluong_thietlapcalamviec03.png)

*Tuỳ vào mục đích người sử dụng muốn hiển thị lên bảng tổng hợp chấm công là ký hiệu công gì, tương ứng với ca làm việc nào, thì người dùng chọn Ký hiệu công tương ứng tại trường "Ký hiệu". Ví dụ, nếu muốn nhân viên đi làm "Ca 3" khi hiển thị lên bảng tổng hợp công với ký hiệu công là "Tăng ca 3 (TC3)" thì thực hiện thiết lập như sau*:

- Thiết lập kí hiệu công với tên: ***Tăng ca 3\***, mã: ***TC3\***, loại công: ***Chấm công\***.

![](images\Ảnh kế toán lương\fin_tienluong_thietlapcalamviec04.png)

- Thiết lập ca làm việc với tên: ***Ca 3\***, mã: ***TC3\***, kí hiệu: ***TC3\***

![](images\Ảnh kế toán lương\fin_tienluong_thietlapcalamviec05.png)

*Sau đó thực hiện phân ca như các bước dưới đây*.

#### Phân ca chi tiết

**Đối tượng sử dụng:** Cán bộ nhân sự.

**Các bước thực hiện:**

***Bước 1:*** Người dùng truy cập vào ứng dụng **Chấm công** > Chọn **Phân ca chi tiết:** Hiển thị danh sách chi tiết phân ca > Nhấn nút **Tạo**

![](images\Ảnh kế toán lương\fin_tienluong_phancachitiet01.png)

***Bước 2:*** Điền đầy đủ thông tin Chi tiết phân ca vào các trường bắt buộc:

![](images\Ảnh kế toán lương\fin_tienluong_phancachitiet02.png)

***Lưu ý:***

- *Nếu chọn phòng ban áp dụng, hệ thống sẽ hiển thị tất cả nhân viên trong phòng ban đó và áp dụng ca làm việc này (người dùng có thể xoá nhân viên không áp dụng ca làm việc):*

![](images\Ảnh kế toán lương\fin_tienluong_phancachitiet03.png)

- *Người dùng cũng có thể chọn nhân viên từ các đơn vị khác nhau để phân ca bằng cách không chọn phòng ban áp dụng mà chọn cụ thể từng nhân viên:*

![](images\Ảnh kế toán lương\fin_tienluong_phancachitiet04.png)

- *Người dùng không thể Tạo chi tiết phân ca với các ca làm việc có thời gian trùng nhau. Trường hợp người dùng chưa muốn duyệt Chi tiết phân ca thì nhấn Lưu để Lưu bản nháp.*

- *Phải có ít nhất 1 nhân viên được phân ca làm việc mới có thể Duyệt Chi tiết phân ca*

***Bước 3:***

Bấm nút **Duyệt** <img src="images\Ảnh kế toán lương\fin_tienluong_duyet_btn.png" style="zoom:75%;" /> để duyệt Chi tiết phân ca. Chi tiết phân ca sau khi được duyệt sẽ xuất hiện tại Bảng tổng hợp phân ca.

Người dùng xem Bảng tổng hợp phân ca bằng cách vào mục **Chấm công** >> **Bảng tổng hợp phân ca**

#### Đề nghị đổi ca

#### Thiết lập đề nghị đổi ca

**Mục đích sử dụng:** Nhân viên đã được phân ca có thể tạo đề nghị đổi ca để đổi sang ca làm việc khác.

**Đối tượng sử dụng:** Nhân viên được phân ca làm việc

*Bước 1:* Người dùng truy cập vào ứng dụng **Chấm công** > Chọn mục **Ca làm việc** > Nhấn chọn **Đề nghị đổi ca**: Hiển thị danh sách Đề nghị đổi ca > Nhấn nút **Tạo**

![](images\Ảnh kế toán lương\fin_tienluong_denghidoica01.png)

*Bước 2:* Điền thông tin vào các trường bắt buộc

![](images\Ảnh kế toán lương\fin_tienluong_denghidoica02.png)

Sau đó nhấn **Lưu**, bản ghi ở trạng thái Nháp, chờ duyệt.

#### Phê duyệt/Từ chối đổi ca

**Mục đích sử dụng:** Các yêu cầu đổi ca được tạo phải được phê duyệt mới có thể đổi ca trên Bảng tổng hợp phân ca. Người có quyền duyệt có thể phê duyệt hoặc từ chối yêu cầu đổi ca.

**Đối tượng sử dụng:**

Quản lý của nhân viên, quản lý phân ca hoặc người quản trị phân hệ chấm công

Với mỗi yêu cầu đổi ca, người được chọn duyệt trong yêu cầu đổi ca mới có thể phê duyệt yêu cầu đổi ca đó.

**Cách thực hiện:**

- Tại tài khoản của người duyệt, màn hình hiển thị 02 nút: Duyệt và Từ chối

- Người dùng chấp thuận đề nghị đổi ca thì nhấn **Duyệt**, bản ghi chuyển về trạng thái Duyệt. Tại Bảng tổng hợp phân ca, ca của hai nhân viên đó sẽ được thay đổi cho nhau

  ![](images\Ảnh kế toán lương\fin_tienluong_denghidoica03.png)

- Ngược lại, người dùng nhấn **Từ chối**, bản ghi chuyển về trạng thái Từ chối. Không có sự thay đổi nào ở Bảng tổng hợp phân ca. Người duyệt có thể chuyển bản ghi về trạng thái Nháp bằng cách nhấn vào **Chuyển về Nháp** để người đề nghị đổi ca có thể chỉnh sửa.

  ![](images\Ảnh kế toán lương\fin_tienluong_denghidoica04.png)

#### Tổng hợp phân ca

Các nghiệp vụ, lưu ý trên bảng tổng hợp công, người dùng xem thêm tại [đây](#tong-hop-cong)

Người dùng xem bảng tổng hợp công trên hệ thống bằng cách vào menu **Chấm công** >> Chọn **Tổng hợp công**: Hệ thống hiển thị dữ liệu chấm công của tất cả nhân viên (bao gồm cả nhân viên làm theo giờ hành chính, và các nhân viên làm theo ca) tại tháng hiện tại như hình sau:

![](images\Ảnh kế toán lương\fin_tienluong_tonghopphanca.png)

### Đăng ký công

**Đối tượng thực hiện:** Nhân viên trong công ty

#### Nhân viên đăng ký công 

Vào menu **Đăng ký công** >> Chọn **Đăng ký công** >> Bấm **Tạo**, nhập liệu và bấm **Lưu** để hoàn tất (chờ người có thẩm quyền duyệt) hoặc bấm **Tạo bản nháp** để lưu đơn với trạng thái Nháp

![](images\Ảnh kế toán lương\fin_tienluong_dangkycong01.png)

*Lưu ý: Người quản lý công có thể thực hiện tạo đơn đăng ký công cho từng nhân viên, cả công ty, cả 1 phòng/ban, theo nhóm nhân viên chung nhãn bằng cách lựa chọn phù hợp chế độ đăng ký ở hình trên.*

#### Phê duyệt/Từ chối đăng ký công

Đối với các loại đăng ký công cần phê duyệt thì quản lý của nhân viên hoặc quản lý công hoặc người quản trị phân hệ Đăng ký công có quyền vào duyệt tương ứng.

Hướng dẫn các bước thực hiện trên hệ thống theo các đối tượng như sau:

- Người phụ trách: Đối tượng này được phép duyệt đơn đăng ký phân bổ của nhân viên mình quản lý

***Cách thực hiện:***

- Người dùng vào menu **Đăng ký công** >> Chọn **Đăng ký công** >> Hệ thống hiển thị danh sách đơn đăng ký công của nhân viên do người dùng phụ trách quản lý trực tiếp
- Người dùng tìm thực hiện bấm **Duyệt** nếu chấp thuận đơn đăng ký công, hoặc ngược lại thì bấm **Từ chối**. Người dùng có thể tích chọn nhiều đơn để duyệt/ từ chối 1 lần

![](images\Ảnh kế toán lương\fin_tienluong_dangkycong02.png)

- Quản lý công: Đối tượng này được phép duyệt tất cả đơn đăng ký công của nhân viên trừ đơn của bản thân
- Người dùng vào menu **Đăng ký công** >> Chọn **Đăng ký công** >> Hệ thống hiển thị mặc danh sách đơn đăng ký công của nhân viên do người dùng phụ trách quản lý trực tiếp, người dùng có thể xoá bộ lọc trên thanh tìm kiếm để xem đơn đăng ký của tất cả các nhân viên trong công ty
- Người dùng tìm thực hiện bấm **Duyệt** nếu chấp thuận đơn đăng ký công, hoặc ngược lại thì bấm **Từ chối**
- Người quản trị phân hệ Đăng ký công: Đối tượng này được duyệt tất cả đơn đăng ký công, kể cả đơn của bản thân
- Người dùng vào menu **Đăng ký công** >> Chọn **Đăng ký công** >> Hệ thống hiển thị mặc danh sách đơn đăng ký công của nhân viên do người dùng phụ trách quản lý trực tiếp, người dùng có thể xoá bộ lọc trên thanh tìm kiếm để xem đơn đăng ký của tất cả các nhân viên trong công ty
- Người dùng tìm thực hiện bấm **Duyệt** nếu chấp thuận đơn đăng ký công, hoặc ngược lại thì bấm **Từ chối**
- Ngoài ra, người quản trị phân hệ Đăng ký công có thể chuyển 1 đơn đăng ký ở trạng thái từ "Bị từ chối" về "Nháp" để nhân viên đó có thể kiểm tra, chỉnh sửa lại thông tin và trình người có thẩm quyền duyệt lại. Thực hiện bằng cách bấm **Tạo bản nháp** tại màn hình chi tiết đơn đăng ký công có trạng thái *Bị từ chối*.

### Đăng ký phân bổ

**Đối tượng thực hiện:** Nhân viên trong công ty

#### Nhân viên đăng ký công 

Với các loại đăng ký cấu hình đăng kỳ phân bổ theo chế độ: Thiết lập bởi người quản lý công, trước khi tạo đăng ký công phải tạo 1 đăng ký phân bổ và được duyệt bở người quản lý công

Vào menu **Đăng ký công** >> Chọn **Đăng phân bổ** >> Bấm **Tạo**, nhập liệu và bấm **Lưu** để hoàn tất (chờ người có thẩm quyền duyệt) hoặc bấm **Tạo bản nháp** để lưu đơn với trạng thái Nháp

![](images\Ảnh kế toán lương\fin_tienluong_dangkyphanbo01.png)

*Lưu ý: Người quản lý công có thể thực hiện tạo đơn đăng ký phânboor cho từng nhân viên, cả công ty, cả 1 phòng/ban, theo nhóm nhân viên chung nhãn bằng cách lựa chọn phù hợp chế độ đăng ký ở hình trên.*

#### Phê duyệt/Từ chối đăng ký công

Đối với các loại đăng ký phân bổ cần phê duyệt thì quản lý của nhân viên hoặc quản lý công hoặc người quản trị phân hệ Đăng ký công có quyền vào duyệt tương ứng.

Hướng dẫn các bước thực hiện trên hệ thống theo các đối tượng như sau:

- Người phụ trách: Đối tượng này được phép duyệt đơn đăng ký phân bổ của nhân viên mình quản lý

***Cách Thực hiện:***

- Người dùng vào menu **Đăng ký công** >> Chọn **Đăng ký phân bổ** >> Hệ thống hiển thị danh sách đơn đăng ký phân bổ của nhân viên do người dùng phụ trách quản lý trực tiếp
- Người dùng tìm thực hiện bấm **Duyệt** nếu chấp thuận đơn đăng ký công, hoặc ngược lại thì bấm **Từ chối**. Người dùng có thể tích chọn nhiều đơn để duyệt/ từ chối 1 lần

![](images\Ảnh kế toán lương\fin_tienluong_dangkyphanbo02.png)

- Quản lý công: Đối tượng này được phép duyệt tất cả đơn đăng ký công của nhân viên trừ đơn của bản thân
- Người dùng vào menu **Đăng ký công** >> Chọn **Đăng ký phân bổ** >> Hệ thống hiển thị mặc danh sách đơn đăng ký công của nhân viên do người dùng phụ trách quản lý trực tiếp, người dùng có thể xoá bộ lọc trên thanh tìm kiếm để xem đơn đăng ký của tất cả các nhân viên trong công ty

·     Người dùng tìm thực hiện bấm **Duyệt** nếu chấp thuận đơn đăng ký công, hoặc ngược lại thì bấm **Từ chối**

·     Người quản trị phân hệ Đăng ký công: Đối tượng này được duyệt tất cả đơn đăng ký công, kể cả đơn của bản thân

·     Người dùng vào menu **Đăng ký công** >> Chọn **Đăng ký phân bổ** >> Hệ thống hiển thị mặc danh sách đơn đăng ký công của nhân viên do người dùng phụ trách quản lý trực tiếp, người dùng có thể xoá bộ lọc trên thanh tìm kiếm để xem đơn đăng ký của tất cả các nhân viên trong công ty

·     Người dùng tìm thực hiện bấm **Duyệt** nếu chấp thuận đơn đăng ký công, hoặc ngược lại thì bấm **Từ chối**

·     Ngoài ra, người quản trị phân hệ Đăng ký công có thể chuyển 1 đơn đăng ký ở trạng thái từ "Bị từ chối" về "Nháp" để nhân viên đó có thể kiểm tra, chỉnh sửa lại thông tin và trình người có thẩm quyền duyệt lại. Thực hiện bằng cách bấm **Tạo bản nháp** tại màn hình chi tiết đơn đăng ký công có trạng thái *Bị từ chối*.

## *Bảng lương*

### Tạo dữ liệu

Để lập được bảng lương, nhân viên phụ trách cần tạo dữ liệu tính lương trước, các dữ liệu này bao gồm dữ liệu đầu vào và thông số mặc định.

**Đối tượng thực hiện:** Nhân viên phụ trách tính lương

#### Tạo thông số mặc định

Các thông số mặc định của một nhân viên bao gồm: Lương chức danh, lương bảo hiểm, người phụ thuộc. Những thông tin này đã được khai báo tại Hồ sơ nhân viên trước đó, nếu chưa được bổ sung, nhân viên phụ trách vào phân hệ Nhân viên để bổ sung đầy đủ thông số. Quy trình nghiệp vụ, xem tại đây.

#### Tạo dữ liệu châm công đầu vào

Các dữ liệu về chấm công sẽ được lấy từ phân hệ Chấm công (quy trình nghiệp vụ xem tại đây), bao gồm các loại công như sau:

- Công tiêu chuẩn: Số ngày công tiêu chuẩn đi làm trong tháng
- Công đi làm: Số ngày công đi làm thực tế trên công ty
- Công làm online: Số ngày công đi làm online đã được ghi nhận
- Công tăng ca: Số ngày công tăng ca đã được phê duyệt
- Công tăng ca đêm: Số ngày công làm tăng ca đêm
- Công tăng ca lễ: Số ngày công làm tăng ca ngày lễ
- Công công tác: Số ngày công đi công tác
- Công nghỉ dưỡng: Số ngày công nghỉ dưỡng
- Công nghỉ không lương: Số ngày công nghỉ không lương
- Công nghỉ lễ: Số ngày công nghỉ lễ
- Công nghỉ ốm: Số ngày công nghỉ ốm
- Công nghỉ phép: Số ngày công nghỉ phép
- Công nghỉ tai nạ: Số ngày công nghỉ tai nạn
- Công nghỉ thai sản: Số ngày công nghỉ thai sản
- Công nghỉ việc riêng hưởng lương: Số ngày công nghỉ việc riêng hưởng lương

### Tạo cấu trúc tính lương

**Đối tượng thực hiện:** Nhân viên phụ trách tính lương.

**Các bước thực hiện:***

***Bước 1:*** Người dùng truy cập vào hệ thống, chọn **Tiền lương > Bảng lương > Cấu trúc lương**

![](images\Ảnh kế toán lương\fin_tienluong_bangluong01.png)

***Bước 2***: Người dùng thực hiện nhập các thông tin chung về cấu trúc lương

- Tên: Tên cấu trúc lương
- Mã: Mã cấu trúc lương

Tại bảng phần tử lương, người dùng thực hiện khai báo các phần tử cấu thành nên cấu trúc lương, dựa trên công thức tính lương của công ty và sử dụng các từ khóa tham số ở bảng bên cạnh

![](images\Ảnh kế toán lương\fin_tienluong_bangluong02.png)

- Cột tên: nhập tên phần tử lương sao cho dễ gợi nhớ
- Cột mã: nhập mã tương ứng với mỗi phần tử, sao cho các phần tử không bị lặp lại mã, và đảm bảo tính chất dễ hiểu, dễ ghi nhớ trong quá trình tạo phần tử và tạo công thức
- Cột mã Python: là cột lưu giá trị của phần tử lương, hệ thống cung cấp các hàm tính toán đảm bảo việc tính lương bao gồm: 
  - Các phép tính toán: cộng, trừ, nhân, chia
  - Round
  - If
  -  ......

- Nút mũi tên 4 chiều: dùng để di chuyển các phần tử lương sao cho đảm bảo các phần tử thỏa mãn điều kiện: Phần tử sau là kết quả phép tính của các phần tử trước.

### Tạo bảng lương

**Đối tượng thực hiện:** Nhân viên phụ trách tính lương.

Nhân viên phụ trách tính lương tạo xong các dữ liệu tính lương cho nhân sự công ty, thì mới có thể tạo được bảng lương hàng tháng dựa trên các dữ liệu đã tạo.

**Các bước thực hiện:**

***Bước 1:*** Người dùng truy cập vào hệ thống, chọn phân hệ **Tiền lương > Bảng lương > Tạo**

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong03.png)

- Tên: Nhập tên bảng lương cần tạo.
- Chu kỳ: Chọn thời gian để thực hiện tính toán.
- Cấu trúc lương: Chọn một cấu trúc lương đã cấu hình sẵn.
- Đơn vị áp dụng: Chọn đơn vị để tính lương

***Bước 2:*** Chọn **Chi tiết phiếu lương**, lúc này sẽ chuyển sang màn hình phiếu lương cho nhân viên.

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong04.png)

- Nếu chọn 1 hoặc 1 nhóm nhân viên thì thực hiện tích chọn vào các ô đầu dòng, chọn **Tính toán phiếu lương**

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong05.png)

- Hệ thống tự tính toán phiếu lương cho nhân viên dựa vào các dữ liệu công, phụ cấp,.. từ dữ liệu chấm công , đăng ký công đã nhập trước đó

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong06.png)

- Để xem chi tiết phiếu lương của từng nhân viên double-click vào1 phiếu lương đã tính toán, sẽ chuyển sang màn hình chi tiết phiếu lương của nhân viên

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong07.png)

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong08.png)

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong09.png)

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong10.png)

- Sau khi kiểm tra xong tất cả cá phiếu lương đã tính toán, dữ liệu lương đúng, sẽ Duyệt phiếu lương
- Tại màn hình Chi tiết phiếu lương, chọn 1 hoặc 1 nhóm nhân viên thì thực hiện tích chọn vào các ô đầu dòng, chọn Duyệt phiếu lương

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong11.png)

***Bước 3:*** Chọn **Hạch toán lương**, lúc này sẽ sinh ra Bút toán cho bảng lương

**Lưu ý**: Để sinh Hạch toán các Phiếu lương phải ở trạng thái “Đã phê duyệt” hoặc “Bị từ chối”

![](images\Ảnh kế toán lương\fin_tienluong_bangluong_hachtoan01.png)

- Click “Bút toán”, sẽ chuyển sang màn hình Bút toán sinh ra.

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong12.png)

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong13.png)

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong14.png)

- Chi tiết bút toán phát sinh sẽ lấy lên các đầu tài khoản và giá trị tương ứng .

***Bước 3:*** Bảng lương đã sinh Bút toán, Chọn “**Đóng**”

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong15.png)

***Bước 4:*** Chọn “**Ghi nhận thanh toán**”, hiển thị ra popup thanh toán

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong16.png)

- NSD chọ Sổ nhật ký: Cách thanh toán theo tiền mặt hay tiền gửi .
- Ngày thanh toán: Lấy mặc định ngày tạo thanh toán, có thể sửa lại ngày theo mong muốn
- Nội dung giao dịch: Lấy theo tên bảng lương

- Chọn Lý do thanh toán: Chi thanh toán cho nhân viên, Chi thanh toán BHXH, Chi thanh toán BTYT, Chi thanh toán BHTN

- Khi chọn lý do thanh toán, hệ thống sẽ tự lấy lên đầu tài khoản và số tiền tương ứng với đầu tài khoản đó.

- Sau khi kiểm tra thông tin chính xác, chọn **Tạo thanh toán** để thanh toán lương cho nhân viên, khi đó phiếu chi tiền mặt/phiếu chi tiền gửi sẽ được sinh ra

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong17.png)

- Chọn Phiếu chi, để xem chi tiết thông tin phiếu chi tiền được sinh ra khi ghi nhận thanh toán. Mỗi bảng lương có thể thanh toán nhiều lần, mỗi lần sẽ sinh ra 1 phiếu chi tiền tương ứng

![img](images\Ảnh kế toán lương\fin_tienluong_bangluong18.png)

 