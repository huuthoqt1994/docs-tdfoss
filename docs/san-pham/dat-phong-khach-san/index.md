---
title: Website đặt phòng khách sạn
---

## Ngôn ngữ

Hệ thống quản lý sẽ có 2 mục ngôn ngữ đó là:

- **Lang interface**:
Lang interface chỉ thể hiện ngôn ngữ của hệ thống nhưng không thể hiện ngôn ngữ của module.

- **Lang data**:
Lang data thể hiện ngôn ngữ data mà người dùng chọn.

Ngôn ngữ ngoài site: Khi người dùng chọn ngôn ngữ nào thì trang web sẽ thể hiện theo ngôn ngữ người dùng đã chọn.

## 1. Quản lý phòng
### 1.1. Hiển thị danh sách phòng
- Từ giao diện chính truy cập vào mục **Quản lý phòng**, người dùng sẽ thấy danh sách thông tin các phòng được hiển thị.

![](images/1.png) 

- Trên giao diện danh sách, ở phần tên gọi khi người dùng click vào tên phòng sẽ hiện ra thông tin chi tiết phòng, click vào nút **Xem ngoài site** để mở trang chi tiết phòng ở khu vực site (khu vực mà khách hàng sẽ nhìn thấy).

![](images/2.png) 

![](images/3.png) 

### 1.2. Tìm kiếm thông tin phòng
- Để tìm kiếm thông tin phòng người dùng có thể tìm kiếm theo từ khóa hoặc lọc theo loại phòng. 

![](images/4.png) 

- Sau khi nhập thông tin người dùng chọn tìm kiếm, thông tin tìm kiếm sẽ hiển thị dưới danh sách.

### 1.3. Sửa, xóa thông tin phòng

- Để sửa thông tin phòng, trên danh sách, bạn chọn liên kết **Sửa**, ở cuối dòng. Tương tự cho việc **Xóa**

![](images/5.png) 

- Để xóa nhiều thông tin phòng cùng 1 lúc người dùng tick vào checkbox đầu thông tin phòng và chọn lênh xóa và bấm thực hiện.
	- (1): Chọn phòng muốn xóa.
	- (2): Chọn tác vụ xóa.
	- (3): Chọn thực hiện để xóa.

![](images/6.png) 

### 1.4. Trạng thái phòng và hoạt động phòng
Trạng thái phòng quy định trạng thái của khi thể hiện với khách hàng bên ngoài khu vực site.
- **Tự động:** Khi khách đặt phòng và xác nhận thanh toán thì hệ thống sẽ thông báo phòng đã hết, các ngày đã thanh toán của phòng sẽ được ẩn đi và không chọn được.
- **Còn phòng:** Phòng luôn còn, kể cả khách trước đã thanh toán thì khách sau vẫn đặt và thanh toán được.
- **Hết phòng:** Phòng sẽ bị khóa chức năng đặt phòng.

![](images/7.png) 

- Sau khi chọn thay đổi trạng thái, hệ thống hiển thị hộp thoại xác nhận lại hành động của bạn, chọn **"OK"** để xác nhận thay đổi hoặc **"Cancel"** để hủy hành động. Bạn cũng có thể thay đổi lại trạng thái khác sau khi đã thay đổi trạng thái thành công.

### 1.5. Thêm phòng
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Thêm phòng (2)**

![](images/9.png) 

- Trong giao diện tiếp theo, bạn điền đầy đủ các trường thông tin, sau đó nhấn Lưu lại ở cuối trang để hoàn tất. 
	- (1): Tên gọi của phòng.
	- (2): Liên kết tĩnh của phòng.
	- (3): Giới thiệu ngắn gọn.
	- (4): Nội dung chi tiết.
	- (5): Loại phòng chọn từ nhóm loại phòng.
	- (6): Giá phòng chọn theo đơn vị tiền tệ.
	- (7): Chọn tạo phòng để tạo phòng sau khi điền đủ thông tin.
![](images/10.png) 

- Mục block phòng sẽ chọn từ nhóm phòng.
- Mục tiện nghi sẽ lấy thông tin từ quản lý tiện nghi.
- Mục chương trình giảm giá sẽ lấy thông tin quản lý mã giảm giá.
- Mục loại phòng sẽ lấy thông tin nhóm quản lý loại phòng.
- Giá phòng chọn loại giá theo cấu hình đơn vị tiền tệ, hệ thống sẽ tự động chuyển đổi thành giá ở ngôn ngữ hiện tại.

**Chú ý:** Những thông tin được đánh dấu sao <span class="red">(*)</span> bắt buộc nhập người dùng phải nhập đầy đủ, tab ngôn ngữ hiển thị các ngôn ngữ  mà người dùng đã cài đặt.

## 2. Quản lý loại phòng
### 2.1. Hiển thị thông tin loại phòng
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Quản lý loại phòng (2)**.

![](images/11.png)

### 2.2. Thêm thông tin loại phòng
- Trong giao diện tiếp theo, bạn điền đầy đủ các trường thông tin, sau đó nhấn Lưu lại ở cuối trang để hoàn tất. 
	- (1): Tên gọi của loại phòng.
	- (2): Chọn chủ đề của phòng.
	- (3): Chọn lưu lại sau khi điền đầy đủ thông tin phòng.

![](images/12.png)

- Nhóm được phép xem chỉ định nhóm đó được xem loại phòng khi thêm vào.

**Chú ý:** Những thông tin <span class="red">(*)</span> bắt buộc nhập người dùng phải nhập đầy đủ, tab ngôn ngữ hiển thị các ngôn ngữ  mà người dùng đã cài đặt.

### 2.3. Sửa, xóa thông tin loại phòng
- Để sửa thông tin loại phòng, trên danh sách, bạn chọn liên kết **Sửa**, ở cuối dòng. Tương tự cho việc **Xóa**.

![](images/13.png)

### 2.4. Tùy chỉnh tác vụ thông tin loại phòng

| STT | Thông tin | Mô tả |
|-----|-----------|-------|
| 1 | Vị trí | Chọn vị trí để sắp xếp, hể hiện trên danh sách |
| 2 | Hiển thị trang chủ | Chọn có hoặc không để thể hiện trên trang chủ |
| 3 | Cách thể hiện loại sản phẩm | chọn cách thể hiện để thể hiện sản phẩm ngoài trang chủ |
| 4 | Số liên kết | Chọn số liên kết cho loại phòng|
| 5 | Hoạt động | Chọn checkbox để chỉnh sửa thông tin sản phẩm |

![](images/14.png)

## 3. Quản lý tiện nghi
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Quản lý tiện nghi (2)**.
 
![](images/15.png)

### 3.1. Thêm tiện nghi
- Trong giao diện dưới đây, bạn điền đầy đủ các trường thông tin, sau đó nhấn Lưu lại ở cuối trang để hoàn tất. 
	- (1): Tên gọi của tiện nghi.
	- (2): Chọn lưu lại để lưu tiền nghi.

![](images/16.png)

**Chú ý: những thông tin <span class="red">(*)</span> bắt buộc nhập người dùng phải nhập đầy đủ, tab ngôn ngữ hiển thị các ngôn ngữ  mà người dùng đã cài đặt**.

### 3.2. Sửa, xóa thông tin tiện nghi

- Để sửa thông tin tiện nghi, trên danh sách, bạn chọn liên kết Sửa, ở cuối dòng. Tương tự cho việc Xóa.

![](images/17.png)

### 3.3. Tùy chỉnh tác vụ tiện nghi

![](images/18.png)

| STT | Thông tin | Mô tả |
|-----|-----------|-------|
| 1 | Vị trí | Chọn vị trí để thể hiện trên danh sách |
| 2 | Chọn mặc định khi thêm | Chọn có hoặc không để thể hiện khi thêm|
| 3 | Hoạt động | Chọn checkbox để chỉnh sửa thông tin tiện nghi |

### 3.4. Tìm kiếm tiện nghi

- Để tìm kiếm thông tin tiện nghi người dùng có thể nhập từ khóa và bấm tìm kiếm, thông tin tìm kiếm sẽ hiện ra dưới bảng.
 
![](images/19.png) 

## 4. Quản lý giảm giá
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Quản lý giảm giá (2)**.
 
![](images/20.png)

### 4.1. Thêm giảm giá
- Trong giao diện dưới đây, bạn điền đầy đủ các trường thông tin, sau đó nhấn Lưu lại ở cuối trang để hoàn tất lưu lại thông tin giảm giá. 
	- (1): Tên gọi mã giảm giá.
	- (2): Chỉ số phần trăm của giảm giá.
	- (3): Ngày bắt đầu hoạt động của mã giảm giá.

![](images/21.png)

**Chú ý: những thông tin <span class="red">(*)</span> bắt buộc nhập người dùng phải nhập đầy đủ, tab ngôn ngữ hiển thị các ngôn ngữ  mà người dùng đã cài đặt**.

### 4.2. Sửa, xóa thông tin giảm giá

- Để sửa thông tin giảm giá, trên danh sách, bạn chọn liên kết Sửa, ở cuối dòng. Tương tự cho việc Xóa.

![](images/22.png)

- Chỉnh sửa thông tin hoạt động người dùng chọn checkbox để điều chỉnh trạng thái còn hoạt động hay không.

![](images/23.png)

### 4.3. Tìm kiếm thông tin giảm giá

- Để tìm kiếm thông tin giảm giá người dùng có thể nhập từ khóa và bấm tìm kiếm, thông tin tìm kiếm sẽ hiện ra dưới bảng.

![](images/24.png)

## 5. Quản lý nhóm phòng
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Quản lý nhóm phòng (2)**.
 
![](images/25.png)

### 5.1. Thêm nhóm phòng
- Trong giao diện dưới đây, bạn điền đầy đủ các trường thông tin, sau đó nhấn Lưu lại ở cuối trang để hoàn tất lưu lại thông tin nhóm phòng.
	- (1): Tên gọi nhóm phòng.
	- (2): Từ khóa nhóm phòng. 

![](images/26.png)

**Chú ý: những thông tin <span class="red">(*)</span> bắt buộc nhập người dùng phải nhập đầy đủ, tab ngôn ngữ hiển thị các ngôn ngữ  mà người dùng đã cài đặt**.

### 5.2. Sửa, xóa thông tin nhóm phòng

- Để sửa thông tin nhóm phòng, trên danh sách, bạn chọn liên kết Sửa, ở cuối dòng. Tương tự cho việc Xóa.

![](images/27.png)

- Chỉnh sửa thông tin chọn mặc định khi thêm. Nếu chọn có khi thêm phòng mặc định mục chọn sẽ được tick vào checkbox và ngược lại.

![](images/28.png)

## 6. Quản lý đánh giá
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Quản lý đánh giá (2)**.
 
![](images/29.png)

- Khi click vào tên gọi đánh giá thì sẽ hiện ra thông tin phòng đánh giá.
### 6.1. Tìm kiếm đánh giá
- Để tìm kiếm thông tin đánh giá người dùng có thể nhập từ khóa và bấm tìm kiếm hoặc người dùng có thể chọn tìm kiếm theo trạng thái, thông tin tìm kiếm sẽ hiện ra dưới bảng.

![](images/30.png)

### 6.2. Sửa, xóa thông tin nhóm phòng

- Để xóa thông tin nhóm phòng, trên danh sách, bạn chọn liên kết xóa ở cuối dòng, click vào biểu tượng xóa và xóa thông tin đánh giá.

![](images/31.png)

- Hiển thị nhóm phòng hoặc không hoặc xóa nhóm phòng theo lựa chọn người dùng chọn theo hoạt động rồi chọn thực hiện.

![](images/32.png)

## 7. Quản lý đặt phòng
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Quản lý đặt phòng (2)**.
 
![](images/33.png)

- Ở table hiển thị danh sách đặt phòng click mã đặt phòng sẽ hiện ra thông tin chi tiết đặt phòng, người dùng có thể xác nhận đơn, hủy đơn và in thông tin đặt phòng.

![](images/34.png)


### 7.1. Tìm kiếm danh sách phòng đặt
- Để tìm kiếm thông tin phòng đã đặt người dùng có thể tìm kiếm theo từ khóa, mã đặt phòng, thời gian đặt phòng, email người đặt và trạng thái thanh toán. 

![](images/35.png)

### 7.2. Hiển thị tổng số đơn hàng và tổng tiền
- Để giúp người dùng nắm khái quát về số đơn hàng và tổng tiền, 2 mục số đơn hàng và tổng đơn tiền sẽ được hiển thị bên phải trên bảng hiển thị.

![](images/36.png)

### 7.3. Xóa thông tin đặt phòng
- Để xóa thông tin đặt phòng, người dùng checkbox theo mục cần chọn và chọn xóa mục chọn để xóa thông tin các mục đã chọn.

![](images/37.png)

## 8. Đơn vị tiền tệ
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Đơn vị tiền tệ (2)**.
 
![](images/38.png)

### 8.1. Thêm đơn vị tiền tệ
- Trong giao diện dưới đây, bạn điền đầy đủ các trường thông tin, sau đó nhấn Lưu lại ở cuối trang để hoàn tất lưu lại thông tin đơn vị tiền tệ. 

![](images/39.png)

### 8.2. Sửa, xóa đơn vị tiền tệ

- Để sửa thông tin đơn vị tiền tệ, trên danh sách, bạn chọn liên kết Sửa, ở cuối dòng. Tương tự cho việc Xóa.

![](images/40.png)

- Xóa nhiều người dùng check box theo thông tin mục cần xóa và chọn xóa mục chọn.

![](images/41.png)

## 9. Cấu hình nội dung
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Cấu hình nội dung (2)**.
 
![](images/42.png)

- Có 3 mục người dùng cần cấu hình, xác nhận đặt phòng, xác nhận thanh toán, và thông báo nhận phòng, người dùng chọn từ khóa gợi ý và soạn nội dung.

## 10. Cấu hình
- Từ giao diện chính, truy cập menu **Quản lý phòng (1) / Cấu hình (2)**.

![](images/43.png)

- Mục cấu hình giúp người dùng cấu hình chức năng theo ý muốn, gồm 2 mục chính cấu hình chức năng và cấu hình giao diện.

- Dưới đây là cấu hình theo chức năng:

![](images/44.png)

| STT | Thông tin | Mô tả |
|-----|-----------|-------|
| 1 | Cho phép đánh giá phòng | Khi người dùng chọn thì sẽ hiện ra mục đánh giá, bao gồm điểm đánh giá (sao) và các thông tin đánh giá. |
| 2 | Kiểm duyệt đánh giá | Người dùng chọn mục này thì tất cả các đánh giá phải được kiểm duyệt mới hiển thị lên trang chủ. |
| 3 | Sử dụng mã bảo mật đánh giá phòng | Khi người dùng tick vào chọn thì mã bảo mật sẽ hiện ra ở mục đánh giá và ngược lại là không nếu không chọn. |
| 4 | Sử dụng mã bảo mật đặt phòng | Khi người dùng tick vào mục này thì khi đặt phòng người dùng sẽ thấy mã xác nhận đặt phòng ở ngoài site.|
| 5 | Y/c đăng nhập đặt phòng | Người dùng chọn mục này sẽ hiện ra thông báo phải đăng nhập mới được đặt phòng. |
| 6 | Các nhóm nhận thông báo từ hệ thống | Chọn muc này người dùng sẽ quyết định nhóm người dùng nào nhận được thông báo từ hệ thống. |
| 7 | Định dạng mã phòng |Người dùng tự quy định mã phòng theo mẫu gợi ý có sẵn của nhà phát triển. |
| 8 | Định dạng mã đặt phòng | Người dùng tự quy định mã đặt phòng theo mẫu gợi ý có sẵn của nhà phát triển. |
| 9 | Đơn vị tiền tệ | Người dùng chọn đơn vị tiền tệ để quy ước đơn vị giá cả của module. |
| 10 | Sử dụng bản đồ | Người dùng chọn google map để hiển thị địa điểm. |
| 11 | Cách hiển thị tại trang chủ module | Khi người dùng chọn cách hiển thị theo loại phòng , tất cả hoặc không hiển thị. |
| 12 | Số lượng phòng hiển thị | Người dùng điền thông tin vào mục để hiển thị ngoài site. |
| 13 | Số sản phẩm được hiển thị trên một hàng (hiển thị dạng lưới) | Khi người dùng chọn thì số sản phẩm sẽ được hiển thị theo ý người dùng. |
| 14 | Lưu | Lưu cấu hình. |

## 11. Trang chủ website

- Khi đến với trang chủ website khách hàng sẽ thấy ngay mục tìm kiếm thông tin loại phòng.

![](images/45.png) 

- Phía dưới mục tìm kiếm thông tin phòng là 2 mục gợi ý **"Căn hộ đề xuất"** và **"Căn hộ mới"**.

### 11.1. Tìm kiếm thông tin phòng

- Người dùng có thể tìm kiếm thông tin phòng qua **Loại phòng**, thời gian và từ khóa tìm kiếm.

![](images/46.png)

- Sau khi tìm kiếm thông tin người dùng tìm kiếm sẽ được hiển thị dưới danh sách, danh sách sẽ hiển thị thông tin giá cả, dịch vụ tiện ích, loại phòng , tình trạng...

![](images/47.png)

### 11.2. Đặt phòng
- Sau khi tìm kiếm được thông tin phòng thích hợp người dùng click vào Đặt phòng.

![](images/48.png)

- Ở mục đặt phòng sẽ có thông tin chi tiết, đặt phòng và đánh giá người dùng có thể tham khảo và lựa chọn cho mình sự lựa chọn tốt nhất.

- Người dùng điền tất cả thông tin vào để đắt phòng, hoàn tất click vào gửi thông tin.

![](images/49.png)

- Loại phòng lấy thông từ danh sách loại phòng phần quản lý loại phòng.
- Ngày nhận phòng là thời gian người dùng chọn, thời gian này chi được chọn từ ngày hiện tại trở đi, sau ngày hiện tại sẽ không chọn được.
- Ngày trả phòng là thời gian người dùng trả phòng và tiến hành thanh toán.
	- Khi phòng ở trạng thái tự động.
		- Hệ thống sẽ tự động xác nhận phòng đã thanh toán từ ngày - đến ngày và sẽ thông báo hết phòng khi đặt phòng.
		- Khi tìm kiếm trong những ngày phòng đó đã thanh toán thì trạng thái phòng sẽ là hết phòng, ngược lại thì trạng thái sẽ là còn phòng.
	- Khi phòng ở trạng thái còn phòng thì người dùng sẽ luôn luôn đặt được phòng.
	- Khi phòng ở trạng thái hết phòng chức năng đặt phòng sẽ bị khóa lại.
- Khi người dùng gửi thông tin đặt phòng thì sẽ nhận được thông tin phòng vừa đặt người dùng có thể thanh toán và in đơn đặt phòng tại đây.

**Chú ý: những thông tin <span class="red">(*)</span> bắt buộc nhập người dùng phải nhập đầy đủ** .

### 11.3. Đánh giá phòng
- Người dùng sau khi sử dụng xong có thể vào phần đánh giá, đánh giá chất lượng phòng.

![](images/50.png)

### 11.4. Đăng ký đặt phòng hôm nay

- Để đăng ký đặt phòng trong ngày người dùng có thế kéo xuống phía dưới website, form đặt phòng hôm nay sẽ hiện ra, người dùng điền thông tin và gửi thông tin để đặt phòng trong ngày.

![](images/51.png)

**Chú ý: những thông tin <span class="red">(*)</span> bắt buộc nhập người dùng phải nhập đầy đủ** 
