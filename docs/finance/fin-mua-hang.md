# **Quy trình nghiệp vụ**

Quản lý toàn bộ quy trình Mua hàng từ bước Lập đơn hàng, nhận hóa đơn và trả tiền cho nhà cung cấp. Phân hệ mua hàng liên kết với phân hệ Kho để tự động sinh phiếu nhập kho ứng với Đơn mua hàng.

**Quy trình**

![](images/fin_muahang_quytrinh.png)

**Các luồng quy trình**

·     Lập yêu cầu báo giá gửi Nhà cung cấp. Chi tiết nghiệp vụ **[tại đây](#yeu-cau-bao-gia)**

·     Lập hợp đồng mua hàng. Chi tiết nghiệp vụ **[tại đây](#hop-ong-mua-hang)**

·     Lập đơn mua hàng từ yêu cầu báo giá. Chi tiết nghiệp vụ **[tại đây](#on-mua-hang)**

·     Nhập kho đơn mua hàng. Chi tiết nghiệp vụ **[tại đây](#nhap-kho-on-mua-hang)**

·     Tạo hóa đơn mua hàng. Chi tiết nghiệp vụ [**tại đây**](#hoa-on-mua-hang)

·     Ghi nhận thanh toán từ nhà cung cấp. Chi tiết nghiệp vụ [**tại đây**](#thanh-toan-cho-nha-cung-cap)

·     Tạo hóa đơn giảm giá/trả hàng. Chi tiết nghiệp vụ [**tại đây**](#hoa-on-giam-giatra-lai-hang-mua)

## **Yêu cầu báo giá**

### **Mô tả nghiệp vụ**

Khi đơn vị có nhu cầu mua hàng, lập yêu cầu mua hàng thì quy trình thực hiện như sau:

- Trưởng bộ phận có nhu cầu mua hàng trình Giám đốc đề nghị mua hàng kèm với đề xuất về nhà cung cấp (nếu có.
- Ban giám đốc duyệt đề nghị mua hàng và chuyển lại cho bộ phận mua hàng; kế toán mua hàng.
- Bộ phận mua hàng đàm phán giá cả với nhà cung cấp và đề xuất lựa chọn nhà cung cấp tới Ban giám đốc.
- Kế toán mua hàng kiểm tra lại giá cả, thông tin nhà cung cấp để tư vấn thêm cho giám đốc về lựa chọn nhà cung cấp
- Ban giám đốc phê duyệt về kế hoạch mua hàng
- Bộ phận Mua hàng thực hiện Lập yêu cầu báo giá và gửi thông tin đến Nhà cung cấp

**Luồng chức năng chính**

·     Lập yêu cầu báo giá gửi Nhà cung cấp. Chi tiết nghiệp vụ **[tại đây](#lap-yeu-cau-bao-gia-gui-nha-cung-cap)**

·     Xác nhận Đơn hàng từ Nhà cung cấp. Chi tiết nghiệp vụ [**tại đây**](#xac-nhan-on-hang-tu-nha-cung-cap)

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Báo giá" 
    src="https://www.youtube.com/embed/y5kwkafXO5I?list=PLcdARb5pnnj9pfGcrvZ16mj-aXdfnNQJe"
></iframe>

### **Lập yêu cầu báo giá gửi Nhà cung cấp**

**Lập yêu cầu báo giá**

Khi Ban GĐ/Quản lý phê duyệt kế hoạch mua hàng; bộ phận mua hàng thực hiện lập Yêu cầu báo giá gửi cho Nhà cung cấp. Theo dõi phản hồi của nhà cung cấp về yêu cầu báo giá.

**Đối tượng thực hiện :** Nhân viên bộ phận mua hàng 

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Yêu cầu báo giá** hoặc chọn **Báo giá** trên quy trình 

![](images/fin_muahang_baogia_menu.png)

 Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống

![](images/fin_muahang_baogia_timkiem.png)

Danh sách báo giá được hiển thị



![](images/fin_MuaHang_YCBG_1.png)

**Bước 2:** Khai báo các thông tin chi tiết của **Yêu cầu báo giá:**

- Chọn thông tin Nhà cung cấp

- Chọn tiền tệ giao dịch trong Đơn hàng

- Khai báo thông tin về Hạn chốt, Ngày nhận

- Khai báo thông tin về Sản phẩm đặt từ Nhà Cung cấp: 
  - Chọn các sản phẩm yêu cầu báo giá từ nhà cung cấp
  - Nhập thông tin Số lượng, Đơn giá, Chiết khấu và mức Thuế đối với từng Sản phẩm
  - Với nội dung cần Lưu ý đối với Yêu cầu báo giá, thực hiện Thêm ghi chú è Thông tin nội dung sẽ được in trên file gửi nhà Cung cấp

**Bước 3**: Nhấn **Lưu**

**Bước 4**: Thực hiện In yêu cầu báo giá: kiểm tra thông tin dữ liệu trên mẫu yêu cầu báo giá và tùy chỉnh thông tin Mẫu yêu cầu

**Bước 5**: Thực hiện Gửi Email đến nhà cung cấp sau khi hoàn thành Yêu cầu báo giá

### **Xác nhận Đơn hàng từ Nhà cung cấp**

**Xác nhận Đơn hàng**

·     Các đơn hàng được Nhà cung cấp trả hàng theo Yêu cầu báo giá đã gửi, bộ phận mua hàng/kho thực hiện xác nhận về kho của công ty

**Đối tượng thực hiện :** Nhân viên bộ phận mua hàng

**Bước 1**: Vào phân hệ **Mua hàng**, trên **Danh sách Yêu cầu báo giá**, tìm thông tin Yêu cầu đã được Nhà cung cấp xác nhận và thực hiện trả 

![](images/fin_MuaHang_YCBG_2.png)

**Bước 2**: Thực hiện xác nhận thông tin Số lượng sản phẩm mà Nhà cung cấp bàn giao

·     Trường hợp Nhà cung cấp trả hàng theo đúng Yêu cầu báo giá: Thực hiện Xác nhận thông tin toàn bộ Đơn hàng mà không cần xác nhận từng Sản phẩm nhận được

·     Trường hợp Nhà cung cấp trả hàng còn thiếu/thừa so với Yêu cầu: Khi đó người dùng cần Vào từng sản phẩm để xác nhận theo đúng số lượng thực tế nhận về

![](images/fin_MuaHang_YCBG_3.png)

**Bước 3**: Nhấn nút **Xác nhận**

**<u>Lưu ý:</u>**

- Sau khi thực hiện Xác nhận đơn hàng, chương trình tự động tạo ra một Phiếu nhập kho bên Phân hệ Quản lý kho
- Yêu cầu báo giá được thực hiện Xác nhận đơn hàng: Sẽ không được hiển thị trên Danh sách Yêu cầu báo giá.

## **Hợp đồng mua hàng**

### **Mô tả nghiệp vụ**

Hợp đồng mua hàng được thực hiện sau luồng Yêu cầu báo giá gửi nhà cung cấp được hoàn thành:

- Ban giám đốc phê duyệt về kế hoạch mua hàng; phê duyệt Nhà cung cấp mua hàng cùng với Hàng hóa, số lượng, đơn giá cho đợt mua
- Bộ phận mua hàng thực hiện Lập hợp đồng mua hàng theo Đơn mua đã gửi và đã được phê duyệt theo các điều khoản về Giá, chiết khấu của các mặt hàng đã thỏa thuận với bên Nhà cung cấ
- Nhà cung cấp thực hiện cung cấp hàng hóa, dịch vụ cho đơn vị theo các điều khoản trên hợp đồng. Bộ phận mua hàng chuyển lại hợp đồng cho kế toán theo dõi, đồng thời làm các đề nghị thanh toán để thanh toán tiền hàng cho nhà cung cấp.
- Kế toán làm thủ tục nhập hàng, đồng thời theo dõi tình hình cung cấp hàng theo hợp đồng, tình hình thanh toán tiền và nhận các hóa đơn mua vào. Từ đó lập các báo cáo liên quan như Báo cáo tình hình thực hiện và công nợ hợp đồng.
- Bộ phận mua hàng lập phụ lục hợp đồng xin phê duyệt bổ sung theo các trình tự trên nếu có phát sinh các yêu cầu khác với hợp đồng chính và trong thời gian hợp đồng chính còn hiệu lực.
- Sau khi hai bên đã hoàn tất nghĩa vụ hợp đồng, bộ phận mua hàng lập thanh lý hợp đồng để bên mua và bên bán ký

**Luồng chức năng chính**

·     Lập Hợp đồng mua hàng. Chi tiết nghiệp vụ **[tại đây](#lap-hop-ong-mua-hang)**

·     Quản lý Hợp đồng mua. Chi tiết nghiệp vụ [**tại đây**](#quan-ly-hop-ong-mua)

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

### **Lập Hợp đồng mua hàng**

**Hợp đồng mua hàng**

·     Hợp đồng mua hàng được lập để theo dõi tình hình cung cấp hàng, tình hình thanh toán cho Nhà cung cấp

**Đối tượng thực hiện :** Nhân viên bộ phận mua hàng và Kế toán thanh toán

**Bước 1**: Vào phân hệ **Mua hàng**, Chọn **Hợp đồng mua hàng** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

![](images/fin_MuaHang_HDM_1.png)

**Bước 2:** Tại phần **Thông tin chung** của Hợp đồng

- Mục **Nhà cung cấp**: Chọn thông tin Nhà cung cấp và Tiền tệ trong giao dịch mua hàng cùng với các điều khoản về Ngày ký, Đơn vị thực hiện

- Mục **Giá trị hợp đồng**: Tự khai báo hoặc chương trình sẽ tự động lấy lên theo Tổng tiền thanh toán của các mặt hàng tại mục **Danh sách hàng hóa**.

  **Lưu ý:**

  - *Với các hợp đồng đã được thanh lý (có trạng thái **Đã thanh lý**), nếu giá trị khi thanh lý khác với giá trị của hợp đồng, Kế toán sẽ thực hiện sửa hợp đồng mua để cập nhật lại **Giá trị thanh lý**.*
  - *Tích chọn **Là hợp hợp đồng phát sinh trước khi sử dụng phần mềm**, nếu vẫn có nhu cầu quản lý các hợp đồng này. => Khi đó, Kế toán sẽ khai báo thêm thông tin về **Giá trị đã thực hiện** và **Số đã trả**.* 

- Mục **Danh sách hàng hóa**: Khai báo thông tin chi tiết của hàng hóa, dịch vụ mua

**Bước 3:** Nhấn **Lưu**

**Lưu ý:**

- Để nhập nhanh Hợp đồng: Kế toán thực hiện chọn **Đơn đặt hàng**: Khi đó thông tin về Nhà cung cấp và Danh sách hàng hóa được lấy mặc định theo Đơn đặt hàng

### **Quản lý hợp đồng mua**

**Quản lý Hợp đồng mua hàng**

·     Kế toán theo dõi và cập nhật thông tin Trạng thái của Hợp đồng, đồng thời theo dõi tình hình cung cấp hàng theo hợp đồng, tình hình thanh toán tiền và nhận các hóa đơn mua vào

**Đối tượng thực hiện :** Kế toán thanh toán

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Hợp đồng mua hàng** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

![](images/fin_MuaHang_HDM_1.png)

**Bước 2:** Tại phần Xem thông tin của Hợp đồng

- Thực hiện cập nhật trạng thái thực của Hợp đồng theo từng đơn hàng: Chưa thực hiện, Đang thực hiện, Thanh lý hoặc Huỷ bỏ
- Theo dõi các thông tin về Tổng thu/Tổng chi tương ứng của Hợp đồng; Xem chi tiết theo từng giao dịch

## ***Đơn mua hàng***

### **Mô tả nghiệp vụ**

Khi đơn vị có nhu cầu mua hàng, lập yêu cầu mua hàng thì quy trình thực hiện như sau:

- Sau khi lựa chọn và chốt giá cả với Nhà cung cấp được lựa chọn: người mua hàng thực hiện lập đơn mua hàng theo thỏa thuận với nhà cung cấp để chốt lại hàng hóa, số lượng, giá cả, hạn thanh toán, hạn giao hàng, địa điểm giao hàng....
- Sau khi lập xong đơn hàng, người mua chuyển đơn mua hàng cho nhà cung cấp để nhà cung cấp kiểm tra, ký đơn mua hàng.Người mua thực hiện xác nhận đơn hàng và lưu trữ chứng từ.
- Đơn mua hàng có thể được lập mới từ đầu hoặc được lập từ: đơn bán hàng

**Luồng chức năng chính**

·     Lập đơn mua hàng gửi Nhà cung cấp. Chi tiết nghiệp vụ **[tại đây](#lap-on-mua-hang-gui-nha-cung-cap)**

·     Xác nhận Đơn hàng từ Nhà cung cấp. Chi tiết nghiệp vụ [**tại đây**](#xac-nhan-on-hang-tu-nha-cung-cap)

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Lập đơn mua hàng" 
    src="https://www.youtube.com/embed/Wm-AUbA7n-w?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


### Hướng dẫn trên phần mềm

#### **Lập đơn mua hàng gửi Nhà cung cấp**

**Đối tượng thực hiện :** Nhân viên bộ phận mua hàng 

Có hai cách để thực hiện lập đơn mua hàng

*<u>Cách 1:</u>* Nhập thêm mới trực tiếp trên giao diện. Hướng dẫn cụ thể **[tại đây](#nhap-truc-tiep-tren-giao-dien)**

*<u>Cách 2:</u>* Lập đơn mua hàng từ việc import dữ liệu. Hướng dẫn cụ thể **[tại đây](#lap-on-mua-hang-tu-viec-import-du-lieu)**

##### **Nhập trực tiếp trên giao diện**

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Đơn mua hàng** 

![](images/fin_muahang_donmh.png)

Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống

![](images/fin_muahang_donmh_timkiem.png)

**Bước 2:** Nhấn nút **Tạo** ![](images/fin_banhang_taomoi.png)trên chức năng để thực hiện thêm một đơn hàng mới. Khai báo các thông tin chi tiết trên đơn mua hàng. Lưu ý: Các ô màu hồng là những thông tin cần bắt buộc nhập

![](images/fin_muahang_donmh_them.png)

- Chọn đơn vị cần mua hàng. 

- Chọn thông tin Nhà cung cấp. Nếu chưa có nhà cung cấp thì có thể nhập bổ sung thêm bằng cách nhập tên nhà cung cấp và chọn tạo mới 

  ![](images/fin_muahang_donmh_ncc.png)

  hoặc vào đường dẫn **Danh mục/Nhà cung cấp** và thực hiện thêm mới

  ![](images/fin_muahang_dm_ncc.png)

- Khai báo thông tin về Hạn đặt hàng, Ngày đơn hàng, nội dung chi tiết đơn hàng

- Khai báo thêm thông tin về Sản phẩm/dịch vụ tại chi tiết đơn hàng bằng cách nhấn chọn thêm sản phẩm
  
- ![](images/fin_banhang_themsanpham.png)
  
  - Chọn các sản phẩm yêu cầu báo giá từ nhà cung cấp
  - Nhập thông tin Số lượng, Đơn giá, Chiết khấu và mức Thuế đối với từng Sản phẩm
  - ![](images/fin_banhang_chitiet.png)
  - Khi thực hiện Thêm ghi chú --> Thông tin nội dung sẽ được in trên file gửi nhà cung cấp

**Bước 3**: Nhấn **Lưu**

##### **Lập đơn mua hàng từ việc Import dữ liệu**

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Đơn mua hàng** 

![](images/fin_muahang_donmh.png)

Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống

![](images/fin_muahang_donmh_timkiem.png)

**Bước 2:** Trên danh sách đơn hàng, nhấn biểu tượng hình ngôi sao, chọn **Thêm bản ghi**

![](images/fin_muahang_import.png)

Sau khi mở màn hình import thông tin, thực hiện xuất file mẫu bằng cách chọn **Mẫu nhập khẩu đơn mua hàng** để thực hiện xuất file mẫu excel

![](images/fin_muahang_import_tem.png)

Trên file excel vừa xuất, người dùng thực hiện nhập thông tin đơn hàng tương ứng tại các cột, hướng dẫn cụ thể có trong phần commnent tại hàng đầu tiên của mỗi cột

![](images/fin_muahang_import_tem2.png)

Đơn vị: Bắt buộc nhập, nhập tên đơn vị
Ngày đơn hàng: Nhập ngày theo định dạng ngày-tháng-năm	
Ngày giao hàng: Nhập ngày theo định dạng ngày-tháng-năm		
Hạn đặt hàng: Nhập ngày theo định dạng ngày-tháng-năm	
Nhà cung cấp: Bắt buộc nhập, Nhập tên khách hàng	
Nội dung: Nhập nội dung đơn hàng
Tiền tệ: Nhập tên tiền tệ
Tỷ giá: Nhập tỷ giá
Nhân viên mua hàng: Nhập tên nhân viên mua hàng	
Chi tiết đơn hàng/Sản phẩm: Bắt buộc nhập, nhập tên hàng hóa cần bán	
Chi tiết đơn hàng/Đơn vị tính: Nhập tên đơn vị tính	
Chi tiết đơn hàng/Số lượng: Bắt buộc nhập, Nhập số lượng	
Chi tiết đơn hàng/Đơn giá: Bắt buộc nhập, 	nhập đơn giá
Chi tiết đơn hàng/Thuế: Nhập tên loại thuế

Sau khi nhập thông tin vào file, thực hiện nhập dữ liệu bằng cách nhấn chọn **Nạp tập tin**

![](images/fin_muahang_naptaptin.png)

Chọn file vừa nhập thông tin, đợi hệ thống tải file, sau đó nhấn nút **Kiểm thử** để kiểm tra thông tin trong file có chính xác không.

Nếu như có lỗi thì sẽ hiển thị thông báo lỗi cụ thể tại cột nào, dòng nào. 

Lưu ý: Những thông báo màu hồng là thông tin cần sửa lại, thông báo màu cam có thể bỏ qua

Nếu như cần sửa chữa thông tin trong file nhập liệu thì người dùng chọn lại **Nạp tập tin** và chọn file vừa sửa

Nếu đã chính xác thì sẽ hiển thị thông báo màu xanh : "Mọi thứ dường như hợp lệ". Người dùng nhấn **Nhập** để bắt đầu import dữ liệu vào hệ thống

![](images/fin_muahang_kiemthu.png)

Khi import thành công, hệ thống  sẽ tự động quay về màn hình danh sách và hiển thị thông báo số lượng bản ghi đã được import, các bản ghi được import thành công ở trạng thái báo giá

#### Thực hiện gửi đơn hàng cho nhà cung cấp

**Bước 1**: Sau khi đã có đơn hàng báo giá để gửi khách hàng, Thực hiện **In** đơn hàng bằng cách chọn chức năng In

![](images/fin_muahang_donmh_in.png)

**Bước 2:** Thực hiện **Gửi qua Email** đến nhà cung cấp sau khi hoàn thành  đơn hàng, có thể tùy chỉnh thông tin mẫu gửi báo giá theo yêu cầu

![](images/fin_BanHang_donhang_GuiEmail.png)



#### **Xác nhận Đơn hàng từ Nhà cung cấp**

Tại đơn hàng đã tạo, sau khi đã thỏa thuận được báo giá với nhà cung cấp và nhà cung cấp trả hàng theo đúng yêu cầu, người mua hàng nhấn nút **Xác nhận** để hoàn thành đơn hàng

Nếu không còn nhu cầu mua hàng, người bán nhấn **Hủy** hoặc thực hiện xóa đơn hàng đã tạo

Sau khi có đơn hàng, sản phẩm sẽ được nhận từ nhà cung cấp và nhập vào kho

![](images/fin_muahang_donmh_xoa.png)

## *Nhập kho đơn mua hàng*

### Mô tả nghiệp vụ

Sau khi thực hiện Xác nhận đơn hàng, chương trình tự động sinh ra một phiếu nhập kho. Người dùng có thể theo dõi tình trạng nhận hàng của sản phẩm trên phiếu nhập kho đã sinh ra và xác nhận số lượng sản phẩm bàn giao theo đơn hàng 

![](images/fin_muahang_donmh_nhap.png)



**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Nhập kho đơn mua hàng" 
    src="https://www.youtube.com/embed/GWLQKRX8Ils?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


### **Hướng dẫn trên phần mềm**

**Bước 1**: Chọn **Nhân hàng** hoặc nhấn nút **Nhận sản phẩm**, hệ thống chuyển sang chức năng phiếu nhập kho. 

![](images/fin_muahng_donmh_nhapkho.png)

Nếu người dùng muốn sửa ngày chứng từ và ngày hạch toán, nhấn nút **Sửa**, thay đổi lại thông tin và nhấn **Lưu**

**Bước 2**: Thực hiện nhập số lượng hàng đã hoàn thành nhận từ nhà cung cấp

- Nếu Số lượng nhận về kho đủ theo Số lượng của Đơn mua hàng: Thực hiện nhấn **Xác nhận** để xác nhận toàn bộ Đơn hàng

  ![](images/fin_muahang_donmh_xacnhannhap.png)

- Nếu Số lượng nhập kho Chưa đủ theo Số lượng của Đơn mua hàng: Thực hiện nhập số lượng theo thực tế bằng cách nhấn **Sửa**, vào nhóm **Vật tư, hàng hóa chi tiết**, nhập số lương **hoàn thành**, sau đó nhấn **Lưu**

  ![](images/fin_muahang_donmh_slnhap.png)

Nhấn **Xác nhận** để hoàn thành nhập hàng về kho

Khi đó có 2 hướng thực hiện :

- Nếu chọn **Tạo phần dở dang**: Với Số lượng còn thiếu, hệ thống tạo sẵn 1 chứng từ Phiếu nhập kho, để Khi nhập kho với Số lượng còn lại, bộ phận Kho tiếp tục vào Phiếu nhập kho (đã tạo phần dở dang) để thực hiện Xác nhận Số lượng nhập kho còn lại.
- Nếu chọn **Không tạo phần dở dang**: Khi đó hệ thống Tách Số lượng nhu cầu ban đầu Bằng đúng Số lượng thực nhập, còn Số lượng chênh chưa nhận được thì Số lượng hoàn thành = 0

Như vậy **Phiếu nhập kho** đã **Hoàn thành** .

## ***Hóa đơn mua hàng***

### **Mô tả nghiệp vụ**

- Sau khi nhập hàng về kho đẩy đủ, người mua hàng hạch toán chi phí và kê khai hóa đơn đầu vào.
- Trường hợp nhân viên mua hàng thanh toán ngay (bằng tiền mặt hoặc chuyển khoản) cho nhà cung cấp sau khi nhận được hàng, khi về đến doanh nghiệp sẽ thực hiện các thủ tục để thanh toán với Kế toán
- Trường hợp còn nợ nhà cung cấp, sau khi nhận được chứng từ của nhân viên mua hàng, kế toán mua hàng hạch toán công nợ với nhà cung cấp

### Hướng dẫn trên phần mềm

Người dùng có thể lập hóa đơn mua hàng theo hai cách khác nhau

Cách 1:Lập hóa đơn mua hàng từ đơn mua hàng. Chi tiết nghiệp vụ **[tại đây](#Lap-hoa-don-mua-hang-tu-don-mua-hang)**

Cách 2: Lập hóa đơn mua hàng không từ đơn mua hàng. Chi tiết nghiệp vụ **[tại đây](#Lap-hoa-don-mua-hang-khong-tu-don-mua-hang)**

#### Lập hóa đơn mua hàng từ đơn mua hàng

**Tạo hóa đơn**

·     Sau khi hàng hóa được nhận từ Nhà cung cấp, Kế toán mua hàng căn cứ vào hóa đơn chứng từ của Nhà cung cấp để thực hiện Tạo hóa đơn mua hàng

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Lập hóa đơn mua hàng từ đơn mua hàng" 
    src="https://www.youtube.com/embed/IfSiV4kECUQ?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>
**Đối tượng thực hiện :** Nhân viên kế toán

**Bước 1:**Vào phân hệ **Mua hàng**, Chọn **Đơn mua hàng** đã hoàn thành Nhận hàng từ Nhà cung cấp và Nhấn **Tạo hóa đơn** 

![](images/fin_muahang_donmh_taohoadon.png)

**Bước 2:** Trên thông tin Hóa đơn mua hàng, Nhân viên kế toán thực hiện nhập các dữ liệu về:

- Hóa đơn: Ngày hóa đơn, Mẫu số, Ký hiệu hóa đơn và Số hóa đơn

  ![](images/fin_muahang_hoadon.png)

- Chọn và nhập thông tin về Thuế và Chiết khấu tương ứng của Đơn hàng

  ![](images/fin_muahang_hoadon_ct.png)

**Bước 3: **Nếu hóa đơn có nhu cầu liên kết với chứng từ khác để theo dõi, vào mục Tham chiếu, thêm chứng từ tham chiếu và thực hiện tìm kiếm chứng từ

![](images/fin_banhang_hoadon_thamchieu.png)

![](images/fin_banhang_hoadon_thamchieu_popup.png)



**Bước 4:** Nhân viên thực hiện nhấn **Xác nhận** 

**Lưu ý:** Để nhìn lại tình trạng hóa đơn của đơn bán hàng, người dùng có thể vào chức năng đơn bán hàng, nhấn chọn **Hóa đơn** tại góc phải màn hình 

![](images/fin_muahang_hoadon_button.png)

#### Lập hóa đơn mua hàng không từ đơn mua hàng

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Hóa đơn mua hàng" 
    src="https://www.youtube.com/embed/7Q0RmFLX3Mg?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>
Đối tượng thực hiện: Người bán hàng

**Bước 1**: Vào phân hệ **Mua hàng**, Chọn **Hóa đơn** , chọn **Hóa đơn mua hàng** 

![](images/fin_muahang_hdmh.png)

Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống

![](images/fin_muahang_hdmh_timkiem.png)

![](images/fin_muahang_hdmh_ds.png)

**Bước 2**: Nhấn nút **tạo** ![](images/fin_banhang_taomoi.png) để thêm hóa đơn. Có hai lựa chọn để tạo hóa đơn: Hóa đơn hàng hóa và Hóa đơn dịch vụ. 

Hóa đơn hàng hóa sẽ thực hiện thanh toán cho các sản phẩm là hàng hóa, thành phẩm, nguyên vật liệu

Hóa đơn dịch vụ sẽ thực hiện thanh toán cho các sản phẩm là chi phí, dịch vụ

Trên thông tin Hóa đơn mua hàng, Nhân viên kế toán thực hiện nhập các dữ liệu về:

- Chọn thông tin ***nhà cung cấp***. Nếu chưa có nhà cung cấp thì có thể nhập bổ sung thêm bằng cách nhập tên khách hàng và chọn tạo mới ![](images/fin_muahang_donmh_ncc.png)

hoặc vào đường dẫn **Danh mục/Nhà cung cấp** và thực hiện thêm mới

![](images/fin_muahang_dm_ncc.png)

- Nhập bổ sung thông tin gồm: Ngày hóa đơn, Mẫu số, Ký hiệu hóa đơn ,Số hóa đơn, hạn thanh toán

  ![](images/fin_muahang_hoadon.png)

- Chọn và nhập thông tin về sản phẩm, số lượng, giá thành bán,Thuế và Chiết khấu của sản phẩm cần lập hóa đơn

  ![](images/fin_muahang_hoadon_ct.png)

**Bước 3**: Nhân viên Kế toán thực hiện nhấn **Lưu** . Hệ thống lưu thông tin chi tiết hóa đơn đã nhập và tự động sinh ra các chi tiết bút toán phát sinh

Thông tin dữ liệu bút toán phát sinh:

- Căn cứ thông tin Thuế  đã lựa chọn cùng với thông tin Chiết khấu, Đơn giá, Số lượng đã nhập bên chi tiết hóa đơn, hệ thống thực hiện mặc định thông tin các bút toán tương ứng

![](images/fin_muahang_hd_buttoan.png)

**Bước 4**: Nhân viên Kế toán thực hiện nhấn **Xác nhận** để hoàn thành xuất hóa đơn mua hàng

Sau khi xác nhận hóa đơn, hệ thống sẽ sinh dữ liệu vào chức năng "Thanh toán cho nhà cung cấp", người dùng kiểm tra thông tin sẽ thanh toán bằng cách vào **Ngân quỹ/Tiền mặt/Thanh toán cho nhà cung cấp** hoặc **Ngân quỹ/Tiền gửi/Thanh toán cho nhà cung cấp** để kiểm tra lại số tiền sẽ được thanh toán

![](images/fin_muahang_xacnhan.png)

#### Lập hóa đơn mua hàng Kiêm Phiếu nhập kho

Chức năng được áp dụng đối với trường hợp thông tin Thiết lập được cấu hình tại phần Kho có tích chọn **'Mua hàng kiêm phiếu nhập kho'** 

![](images/fin_ThietLap_Kho.png)

**Với thiết lập Mua hàng kiêm phiếu nhập kho:**

- Khi Xác nhận Chứng từ mua hàng: Hệ thống tự động tạo ra Phiếu nhập kho và tự động Hoàn thành thông tin Phiếu nhập kho
- Người dùng không phải tác động đến Thông tin Phiếu nhập kho: Hệ thống tự động xác nhận thông tin Vật tư hàng hóa được mua vào Tồn kho

- Trường hợp: Chứng từ mua hàng được lập từ Đơn mua hàng: Tại bước **Xác nhận** của Đơn mua hàng **KHÔNG** tạo ra Phiếu nhập kho để Nhận hàng, mà Chỉ tạo ra Chứng từ Mua hàng

Đối tượng thực hiện: Người bán hàng

**Bước 1**: Vào phân hệ **Mua hàng**, Chọn **Mua hàng** , chọn **Chứng từ mua hàng** 

![](images/fin_Muahang_Danhsach.png)

**Bước 2**: Nhấn nút **tạo** ![](images/fin_banhang_taomoi.png) để thêm chứng từ. Có hai lựa chọn để tạo chứng từ: Chứng từ mua hàng hóa và Chứng từ mua dịch vụ 

Chứng từ mua hàng hóa sẽ thực hiện thanh toán cho các sản phẩm là hàng hóa, thành phẩm, nguyên vật liệu

Chứng từ mua dịch vụ sẽ thực hiện thanh toán cho các sản phẩm là chi phí, dịch vụ

Liên quan đến luồng Mua hàng kiêm phiếu nhập kho: Thực hiện chọn Tạo Chứng từ mua hàng hóa

![](images/fin_Muahang_Tao.png)

==> Màn hình Khai báo thông tin Chứng từ mua hàng hóa

![](images/fin_Muahang_Tao_02.png)

**Bước 3**: Khai báo thông tin trên chứng từ

Người dùng nhập các thông tin trên Chứng từ

- Nhà cung cấp: Chọn thông tin Nhà cung cấp đã được khai báo tại **Danh mục Nhà cung cấp**
- Loại nhập/Kho nhập: Hệ thống lấy mặc định theo thông tin Kiểu giao nhận đã được khai báo.
  - Loại nhập: Mặc định là Nhập mua hàng hóa
  - Kho nhập: Mặc định thông tin Kho của Loại nhập

![](images/fin_Muahang_Tao_Thongtinchung.png)

- Khai báo thông tin Vật tư hàng hóa được mua: 
  - Gồm thông tin về Mặt hàng; Số lượng; Đơn vị tính; Đơn giá và Chiết khấu/Thuế GTGT (Nếu có)
  - Với Mua hàng kiêm phiếu nhập kho: Có thêm 2 thông tin về Ngày hết hạn và Số lô|Se-ri để nhập. 
    - Nếu người dùng không nhập thông tin Số lô: Khi tạo Phiếu nhập kho Hệ thống sẽ tự động tạo ra theo dữ liệu mặc định
    - Nếu người dùng nhập thông tin: Thông tin Phiếu nhập kho sẽ lấy theo thông tin Người dùng đã nhập.

![](images/fin_Muahang_Tao_Thongtinchitiet.png)

**Bước 4**: Nhấn nút **Lưu** để hoàn thành việc khai báo

**Bước 5**: Nhấn nút **Xác nhận** sau khi kiểm tra thông tin đã đúng và đủ

![](images/fin_Muahang_Tao_XacNhan.png)

**Khi đó:**

- Trạng thái của Chứng từ mua hàng là Đã vào Sổ
- Hệ thống tự động tạo ra 1 Phiếu nhập kho để Nhận hàng vào kho. Người dùng nhấn nút 'Nhận hàng' trên Chứng từ mua hàng để kiểm tra thông tin Phiếu nhập kho

![](images/fin_Muahang_Tao_XacNhan_NhanHang.png)

- Trạng thái của Phiếu nhập kho là Hoàn thành, và vật tư hàng hóa của Chứng từ đã được ghi nhận Vào kho

![](images/fin_Muahang_Tao_XacNhan_Kho.png)

**<u>*Lưu ý:*</u>**

- Với Phiếu nhập kho được tạo ra từ Chứng từ mua hàng: Không lên bút toán tại Phiếu nhập kho

**Bước 6**: Trường hợp Người dùng muốn đưa thông tin chứng từ về trạng thái dự thảo: Nhấn nút **Đưa về dự thảo**

![](images/fin_Muahang_DuThao.png)

Khi đó xảy ra các trường hợp sau:

- **Nếu mặt hàng trong Phiếu nhập kho đã tham gia vào quá trình xuất hàng/trả hàng:** hệ thống sẽ báo lỗi khi đưa Chứng từ mua hàng về Dự thảo.

  Người dùng phải thực hiện xử lý dữ liệu thông tin Phiếu được hệ thống báo lỗi.

![](images/fin_Muahang_DuThao_baoLoi.png)

- **Nếu mặt hàng trong Phiếu nhập kho Chưa tham gia vào quá trình xuất hàng/trả hàng:** hệ thống đưa Chứng từ mua hàng về Dự thảo thành công. Đồng thời thông tin Phiếu nhập kho được tạo ra từ Chứng từ sẽ bị xóa khỏi hệ thống, và số lượng tồn kho sẽ giảm tương ứng.

## ***Thanh toán cho Nhà cung cấp***

### **Mô tả nghiệp vụ**

- Sau khi thực hiện Nhận hàng từ Nhà cung cấp, đơn vị thực hiện kiểm tra thông tin đơn hàng và tiến hành Thanh toán cho Nhà cung cấp.

- Việc thanh toán có thể ghi nhận thực hiện nhiều lần.

**Đối tượng thực hiện :** Nhân viên kế toán

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Ghi nhận thanh toán từ hóa đơn mua hàng" 
    src="https://www.youtube.com/embed/u_LaWfSuX_A?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


### Hướng dẫn trên phần mềm

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Hóa đơn mua hàng** đã hoàn thành **Vào sổ** 

![](images/fin_muahang_hd_thanhtoan.png)

**Bước 2**: Chọn hóa đơn cần thanh toán, Nhấn nút **Ghi nhận thanh toán**. 

![](images/fin_muahang_hd_ghinhantt.png)

Tại màn hình **Ghi nhận thanh toán** kế toán thanh toán thực hiện:

- Chọn Phương thức thanh toán, nếu thanh toán chuyển khoản thì thông tin Tài khoản được hiển thị mặc định theo Tài khoản của Nhà cung cấp đã được khai báo tại Danh mục **Nhà cung cấp**

- Nhập thông tin về Số tiền thanh toán, Ngày thanh toán của hóa đơn cho Đơn hàng

![](images/fin_BanHang_HoaDon_GhiNhanThanhToan_Popup.png)

**Bước 3**: Nhấn **Tạo thanh toán**, hệ thống sinh phiếu chi tiền  để thu tiền khách hàng đã thực hiện trả

Trường hợp nếu số tiền chi thanh toán  vượt quá số tiền còn tồn thì phần mềm sẽ báo lỗi 'Số tiền chi vượt quá số dư tài khoản'

![](images/fin_muahang_hd_ttvuot.png)

Để kiểm tra lại phiếu chi tiền, người dùng có thể tìm phiếu chi bằng cách:

Nếu Tại thông tin **Ghi nhận thanh toán**, **Sổ nhật ký** được chọn là **tiền mặt** thì người dùng vào chức năng **Ngân quỹ/Tiền mặt/Phiếu chi**. 

![](images/fin_muahang_phieuchi.png)

Nếu Tại thông tin **Ghi nhận thanh toán**, **Sổ nhật ký** được chọn là **tiền gửi** thì người dùng vào chức năng **Ngân quỹ/Tiền gửi/Báo nợ**. 

![](images/fin_muahang_baono.png)

Người dùng có thể tìm thấy phiếu chi tiền dựa trên ngày thanh toán, đối tác thanh toán, tổng tiền, nội dung giao dịch

![](images/fin_muahang_pc.png)



## ***Hóa đơn giảm giá/trả lại hàng mua*** - *Không thiết lập Mua hàng kiêm phiếu nhập kho*

### **Mô tả nghiệp vụ**

Khi phát hiện hàng mua về không đúng quy cách, chất lượng như đã thỏa thuận ban đầu.... thì đơn vị thực hiện trả lại hàng:

- Đơn vị và nhà cung cấp sẽ thỏa thuận với nhau và lập biên bản về việc trả lại hàng.
- Sau khi thống nhất với Nhà cung cấp, Nhân viên kế toán thực hiện Luồng trả hàng Ngay tại Đơn mua hàng tương ứng
- Thông tin Kho hàng và Hóa đơn trả hàng sẽ được tạo tại thời điểm thực hiện Trả hàng

Luồng mô tả Chức năng được áp dụng đối với trường hợp thông tin Thiết lập được cấu hình tại phần Kho Không được tích chọn **'Mua hàng kiêm phiếu nhập kho'** 

![](images/fin_ThietLap_Kho_Khongchon.png)

Có 2 cách thức thực hiện:

**<u>*Cách 1*</u>**: Người mua hàng lập hóa đơn giảm giá hàng đã mua để giao cho nhà cung cấp và ghi sổ kế toán.Chi tiết nghiệp vụ **[tại đây](#tao-hoa-on-giam-gia-hang)**

**<u>*Cách 2*</u>**: Người mua hàng chuyển đổi hóa đơn bán hàng thành khoản hoàn tiền/công nợ giảm. Chi tiết nghiệp vụ **[tại đây](#chuyen-oi-thanh-khoan-hoan-tiencong-no-giam)**

### Hướng dẫn trên phần mềm

#### **Tạo hóa đơn giảm giá hàng**

Sau khi hoàn thành việc thỏa thuận với Nhà cung cấp về các mặt hàng không đảm bảo, kế toán thực hiện Lập Hóa đơn giảm giá/trả lại hàng cho Nhà cung cấp

**Đối tượng thực hiện :** Nhân viên kế toán

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Hóa đơn mua hàng** đã hoàn thành Nhận hàng từ Nhà cung cấp. Trên danh sách hóa đơn mua hàng, kế toán tìm tới các hóa đơn đã được ghi sổ, nhấn chọn **Tạo HĐ giảm giá**

![](images/fin_muahang_hdgg.png)

**Bước 2**: Nhập Lý do tạo hóa đơn, Nhấn **Đảo ngược**

![](images/fin_BanHang_HoaDon_TaoHDGiamGia_popup.png)

Hệ thống tự sinh hóa đơn giảm giá với thông tin tương ứng với hóa đơn bán hàng. 

Trên hóa đơn giảm giá được sinh ra, kế toán khai báo  các thông tin trên chứng từ giảm giá hàng bán như: số lượng hàng được giảm, giá trị giảm

![](images/fin_muahang_hdgg_them.png)

Nhấn **xác nhận** để ghi sổ thông tin hóa đơn. 

Sau đó, người dùng sẽ **xuất hóa đơn** để gửi lại cho khách hàng và **ghi nhận lại thanh toán**

![](images/fin_banhang_hoadon_giamgia_ghinhantt.png)

#### Chuyển đổi thành khoản hoàn tiền/công nợ giảm

Bước 1: Vào phân hệ **Mua hàng**, chọn **Hóa đơn**, chọn **Hóa đơn mua hàng**. Trên danh sách hóa đơn mua hàng, kế toán tìm tới hóa đơn có nhu cầu hoàn hàng, nhấn chọn tiện ích/chuyển đổi thành khoản hoàn tiền/công nợ giảm

![](images/fin_muahang_hdmh_chuyendoi.png)

Hệ thống chuyển đổi từ hóa đơn mua hàng thành hóa đơn giảm giá/trả hàng, các thông tin được giữ nguyên

## ***Hóa đơn giảm giá/trả lại hàng mua*** - *Có thiết lập Mua hàng kiêm phiếu nhập kho*

### **Chứng từ trả hàng**

#### Mô tả nghiệp vụ

Chức năng Trả hàng áp dụng trong trường hợp phát hiện thông tin Vật tư hàng hóa không đảm bảo theo yêu cầu, lỗi hoặc nhập thừa..., người dùng thực hiện tính năng trả hàng tại chức năng 'Chứng từ trả hàng'

Luồng mô tả Chức năng được áp dụng đối với trường hợp thông tin Thiết lập được cấu hình tại phần Kho có tích chọn **'Mua hàng kiêm phiếu nhập kho'** 

![](images/fin_ThietLap_Kho.png)

**Với thiết lập Mua hàng kiêm phiếu nhập kho:** Có 2 trường hợp xảy ra

**<u>Trường hợp 1</u>**: Nếu **tích** chọn **'Trả hàng trong kho'** trên giao diện:

- Khi Xác nhận Chứng từ trả hàng: Hệ thống tự động tạo ra Phiếu Xuất kho và tự động Hoàn thành thông tin Phiếu xuất kho
- Người dùng không phải tác động đến Thông tin Phiếu xuất kho: Hệ thống tự động xác giảm trừ tồn kho của Vật tư hàng hóa
- Trên thông tin Phiếu xuất kho: Không có thông tin bút toán hạch toán

**<u>Trường hợp 2</u>**: Nếu **Không** tích chọn **'Trả hàng trong kho'** trên giao diện:

- Khi Xác nhận Chứng từ trả hàng: Hệ thống không tạo ra Phiếu xuất kho, không giảm trừ hàng trong kho. Chỉ ghi nhận giảm giá trị tại Chứng từ trả hàng

Đối tượng thực hiện: Người bán hàng

#### Hướng dẫn trên phần mềm

Có 2 cách thực hiện chức năng Chứng từ trả hàng

***<u>Cách 1</u>*:** Tạo chứng từ trả hàng từ Chứng từ mua hàng. Hướng dẫn cụ thể **[tại đây](#tao-chung-tu-tra-hang-tu-chung-tu-mua-hang)**

***<u>Cách 2</u>:*** Thêm mới từ Chức năng Chứng từ Trả hàng. Hướng dẫn cụ thể **[tại đây](#them-moi-tu-chuc-nang-chung-tu-tra-hang)**

##### **Tạo chứng từ Trả hàng từ Chứng từ mua hàng**

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Chứng từ mua hàng** , Chọn Chứng từ cần thực hiện Trả hàng, trạng thái của Chứng từ mua phải là 'Đã vào sổ'

![](images/fin_Muahang_Trahang.png)

**Bước 2**: Nhấn nút **'Tạo CT trả hàng/giảm giá'** và chọn **'Chứng từ trả hàng'**

![](images/fin_Muahang_Trahang_Chon.png)

==> Hệ thống tạo thông tin Chứng từ trả hàng với dữ liệu lấy mặc định theo thông tin trên Chứng từ mua hàng đang chọn

![](images/fin_Muahang_Trahang_Sua.png)

**<u>Lưu ý:</u>**

- Nếu **bỏ** tích chọn **'Trả hàng trong kho'**: Khi Xác nhận Chứng từ trả hàng hệ thống sẽ không tạo ra Phiếu xuất tương ứng

**Bước 3**: Thực hiện thay đổi Số lượng thông tin hàng hóa cần trả hàng

![](images/fin_Muahang_Trahang_Sua_Vthh.png)

**Bước 4**: Nhấn nút **'Xác nhận'** sau khi đã hoàn thành nhập dữ liệu

![](images/fin_Muahang_Trahang_xacNhan.png)

**Khi đó:**

- Trạng thái của Chứng từ trả hàng là Đã vào Sổ
- Hệ thống tự động tạo ra 1 Phiếu xuất kho để Trả hàng cho Nhà cung cấp. Người dùng nhấn nút 'Giao hàng' trên Chứng từ trả hàng để kiểm tra thông tin Phiếu xuất kho

![](images/fin_Muahang_Trahang_GiaoHang.png)

- Trạng thái của Phiếu xuất kho là Hoàn thành, Số lượng tồn của vật tư hàng hóa được tự động giảm trừ trong kho.

![](images/fin_Muahang_Trahang_Kho.png)

**Bước 5**: Trường hợp Người dùng muốn đưa thông tin chứng từ về trạng thái dự thảo: Nhấn nút **Đưa về dự thảo**

![](images/fin_Muahang_Trahang_DuThao.png)

Khi đó xảy ra các trường hợp sau:

- **Nếu mặt hàng trong Phiếu xuất kho đã tham gia vào quá trình nhập hàng về (Tính năng thực hiện tại Phiếu xuất kho)** hệ thống sẽ báo lỗi khi đưa Chứng từ trả hàng về Dự thảo.

  Người dùng phải thực hiện xử lý dữ liệu thông tin Phiếu được hệ thống báo lỗi trước khi tiếp tục thực hiện chuyển Phiếu trả về Dự thảo

![](images/fin_Muahang_Trahang_DuThao_baoLoi.png)

- **Nếu mặt hàng trong Phiếu xuất kho Chưa tham gia vào quá trình nhập hàng về:** hệ thống đưa Chứng từ trả hàng về Dự thảo thành công. Đồng thời thông tin Phiếu xuất kho được tạo ra từ Chứng từ sẽ bị xóa khỏi hệ thống, và số lượng tồn kho sẽ được hoàn lại tương ứng.

![](images/fin_Muahang_Trahang_DuThao_ThanhCong.png)

##### **Thêm mới từ Chức năng Chứng từ Trả hàng**

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Thêm mới chứng từ trả hàng" 
    src="https://www.youtube.com/embed/uZBBGd-lGkg?list=PLcdARb5pnnj9pfGcrvZ16mj-aXdfnNQJe"
></iframe>

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Chứng từ trả hàng** 

![](images/fin_Muahang_Trahang_trucTiep.png)

**Bước 2**: Nhấn nút **tạo** ![](images/fin_banhang_taomoi.png) để thêm chứng từ.

![](images/fin_Muahang_Trahang_tao.png)

==> Màn hình khai báo thông tin Chứng từ trả hàng

![](images/fin_Muahang_Trahang_tao_02.png)

**Bước 3**: Khai báo thông tin trên chứng từ

Người dùng nhập các thông tin trên Chứng từ

- Nhà cung cấp: Chọn thông tin Nhà cung cấp đã được khai báo tại **Danh mục Nhà cung cấp**
- Loại xuất/Kho xuất: Hệ thống lấy mặc định theo thông tin Kiểu giao nhận đã được khai báo.
  - Loại xuất: Mặc định là Xuất trả lại hàng hóa NCC
  - Kho xuất: Mặc định thông tin Kho của Loại xuất
- Lập từ: Người dùng cũng có thể chọn thông tin chứng từ Trả hàng được tạo ra bởi chứng từ Phiếu xuất hoặc Chứng từ mua hàng. Khi chọn giá trị trên Lập từ hệ thống tự động đẩy dữ liệu của chứng từ đã chọn tương ứng xuống phần Chi tiết

![](images/fin_Muahang_Trahang_tao_ThongtinChung.png)

- Khai báo thông tin Vật tư hàng hóa trả hàng cho NCC: 
  - Gồm thông tin về Mặt hàng; Số lượng; Đơn vị tính; Đơn giá và Chiết khấu/Thuế GTGT (Nếu có)
  - Với Mua hàng kiêm phiếu nhập kho: Số lô|Se-ri của mặt hàng cần trả. Hệ thống sẽ tự động view các Lô serial đang còn của Mặt hàng thực hiện trả. 
    - Nếu người dùng nhập thông tin: Thông tin Phiếu xuất kho sẽ xuất trả hàng của Lô đã chọn
    - Nếu người dùng không chọn thông tin: Hệ thống tự động lấy 1 Lô của mặt hàng để xuất trả

![](images/fin_Muahang_Trahang_tao_Chitiet.png)

**<u>Lưu ý:</u>**

- Nếu **bỏ** tích chọn **'Trả hàng trong kho'**: Khi Xác nhận Chứng từ trả hàng hệ thống sẽ không tạo ra Phiếu xuất tương ứng

**Bước 4**: Nhấn nút **'Xác nhận'** sau khi đã hoàn thành nhập dữ liệu

![](images/fin_Muahang_Trahang_xacNhan.png)

**Khi đó:**

- Trạng thái của Chứng từ trả hàng là Đã vào Sổ
- Hệ thống tự động tạo ra 1 Phiếu xuất kho để Trả hàng cho Nhà cung cấp. Người dùng nhấn nút 'Giao hàng' trên Chứng từ trả hàng để kiểm tra thông tin Phiếu xuất kho

![](images/fin_Muahang_Trahang_GiaoHang.png)

- Trạng thái của Phiếu xuất kho là Hoàn thành, Số lượng tồn của vật tư hàng hóa được tự động giảm trừ trong kho.

![](images/fin_Muahang_Trahang_Kho.png)

**Bước 5**: Trường hợp Người dùng muốn đưa thông tin chứng từ về trạng thái dự thảo: Nhấn nút **Đưa về dự thảo**

![](images/fin_Muahang_Trahang_DuThao.png)

Khi đó xảy ra các trường hợp sau:

- **Nếu mặt hàng trong Phiếu xuất kho đã tham gia vào quá trình nhập hàng về (Tính năng thực hiện tại Phiếu xuất kho)** hệ thống sẽ báo lỗi khi đưa Chứng từ trả hàng về Dự thảo.

  Người dùng phải thực hiện xử lý dữ liệu thông tin Phiếu được hệ thống báo lỗi trước khi tiếp tục thực hiện chuyển Phiếu trả về Dự thảo

![](images/fin_Muahang_Trahang_DuThao_baoLoi.png)

- **Nếu mặt hàng trong Phiếu xuất kho Chưa tham gia vào quá trình nhập hàng về:** hệ thống đưa Chứng từ trả hàng về Dự thảo thành công. Đồng thời thông tin Phiếu xuất kho được tạo ra từ Chứng từ sẽ bị xóa khỏi hệ thống, và số lượng tồn kho sẽ được hoàn lại tương ứng.

![](images/fin_Muahang_Trahang_DuThao_ThanhCong.png)

### **Chứng từ giảm giá**

#### Mô tả nghiệp vụ

Chức năng Giảm giá trị áp dụng trong trường hợp cần giảm giá trị tiền của Vật tư hàng hóa đã thực hiện xác nhận.

Luồng mô tả Chức năng được áp dụng đối với trường hợp thông tin Thiết lập được cấu hình tại phần Kho có tích chọn **'Mua hàng kiêm phiếu nhập kho'** 

![](images/fin_ThietLap_Kho.png)

**Với thiết lập Mua hàng kiêm phiếu nhập kho:** Có 2 trường hợp xảy ra

**<u>Trường hợp 1</u>**: Nếu **tích** chọn **'Giảm giá trị hàng nhập kho'** trên giao diện:

- Khi Xác nhận Chứng từ giảm giá: Hệ thống tự động tạo ra Phiếu Xuất kho và tự động Hoàn thành thông tin Phiếu xuất kho
- Phiếu xuất kho tự động ở trạng thái Hoàn thành: Sinh Phiếu xuất kho không có số lượng xuất, chỉ có giá trị âm tương ứng với giá trị giảm giá trên chứng từ giảm giá. Tức Thông tin Số lượng xuất = 0; Ghi nhận Âm giá trị tiền
- Trên thông tin Phiếu xuất kho: Không có thông tin bút toán hạch toán

**<u>Trường hợp 2</u>**: Nếu **Không** tích chọn **'Giảm giá trị hàng nhập kho'** trên giao diện:

- Khi Xác nhận Chứng từ giảm giá: Hệ thống không tạo ra Phiếu xuất kho. Chỉ ghi nhận giảm giá trị tại Chứng từ giảm giá.

Đối tượng thực hiện: Người bán hàng

#### Hướng dẫn trên phần mềm

Có 2 cách thực hiện chức năng Chứng từ trả hàng

**<u>*Cách 1*</u>:** Tạo chứng từ Giảm giá từ Chứng từ mua hàng. Hướng dẫn cụ thể **[tại đây](#tao-chung-tu-giam-gia-tu-chung-tu-mua-hang)**

***<u>Cách 2</u>:*** Thêm mới từ Chức năng Chứng từ Giảm giá. Hướng dẫn cụ thể **[tại đây](#them-moi-tu-chuc-nang-chung-tu-giam-gia)**

##### **Tạo chứng từ Giảm giá từ Chứng từ mua hàng**

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Chứng từ mua hàng** , Chọn Chứng từ cần thực hiện Giảm giá, trạng thái của Chứng từ mua phải là 'Đã vào sổ'

![](images/fin_Muahang_Trahang.png)

**Bước 2**: Nhấn nút **'Tạo CT trả hàng/giảm giá'** và chọn **'Chứng từ giảm giá'**

![](images/fin_Muahang_GiamGia_Chon.png)

==> Hệ thống tạo thông tin Chứng từ giảm giá với dữ liệu lấy mặc định theo thông tin trên Chứng từ mua hàng đang chọn

![](images/fin_Muahang_GiamGia_Sua.png)

**<u>Lưu ý:</u>**

- Nếu **bỏ** tích chọn **'Giảm giá trị hàng nhập kho'**: Khi Xác nhận Chứng từ Giảm giá hệ thống sẽ **không** tạo ra Phiếu xuất tương ứng

**Bước 3**: Thực hiện thay đổi Đơn giá của hàng hóa cần Giảm giá

![](images/fin_Muahang_Giamgia_Sua_Vthh.png)

**Bước 4**: Nhấn nút **'Xác nhận'** sau khi đã hoàn thành nhập dữ liệu

![](images/fin_Muahang_GiamGia_xacNhan.png)

**Khi đó:**

- Trạng thái của Chứng từ trả hàng là Đã vào Sổ
- Hệ thống tự động tạo ra 1 Phiếu xuất kho để Giảm giá hàng đã nhập. Người dùng nhấn nút 'Giao hàng' trên Chứng từ giảm giá để kiểm tra thông tin Phiếu xuất kho

![](images/fin_Muahang_GiamGia_GiaoHang.png)

- Trạng thái của Phiếu xuất kho là Hoàn thành, Số lượng tồn của vật tư hàng hóa được giữ nguyên, hệ thống ghi nhận Số tiền Âm

![](images/fin_Muahang_GiamGia_Kho.png)

**Bước 5**: Trường hợp Người dùng muốn đưa thông tin chứng từ về trạng thái dự thảo: Nhấn nút **Đưa về dự thảo**

![](images/fin_Muahang_GiamGia_DuThao.png)

Hệ thống đưa Chứng từ trả hàng về Dự thảo thành công. Đồng thời thông tin Phiếu xuất kho được tạo ra từ Chứng từ sẽ bị xóa khỏi hệ thống

![](images/fin_Muahang_GiamGia_DuThao_ThanhCong.png)

##### **Thêm mới từ Chức năng Chứng từ Giảm giá**

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Thêm mới chứng từ giảm giá" 
    src="https://www.youtube.com/embed/uZBBGd-lGkg?list=PLcdARb5pnnj9pfGcrvZ16mj-aXdfnNQJe"
></iframe>

**Bước 1:** Vào phân hệ **Mua hàng**, Chọn **Chứng từ Giảm giá** 

![](images/fin_Muahang_GiamGia_trucTiep.png)

**Bước 2**: Nhấn nút **tạo** ![](images/fin_banhang_taomoi.png) để thêm chứng từ.

![](images/fin_Muahang_GiamGia_trucTiep_Tao.png)

==> Màn hình khai báo thông tin Chứng từ trả hàng

![](images/fin_Muahang_GiamGia_trucTiep_Tao_02.png)

**Bước 3**: Khai báo thông tin trên chứng từ

Người dùng nhập các thông tin trên Chứng từ

- Nhà cung cấp: Chọn thông tin Nhà cung cấp đã được khai báo tại **Danh mục Nhà cung cấp**
- Loại xuất/Kho xuất: Hệ thống lấy mặc định theo thông tin Kiểu giao nhận đã được khai báo.
  - Loại xuất: Mặc định là Giảm giá trị hàng nhập kho
  - Kho xuất: Mặc định thông tin Kho của Loại xuất
- Lập từ: Người dùng cũng có thể chọn thông tin chứng từ Trả hàng được tạo ra bởi chứng từ Phiếu xuất hoặc Chứng từ mua hàng. Khi chọn giá trị trên Lập từ hệ thống tự động đẩy dữ liệu của chứng từ đã chọn tương ứng xuống phần Chi tiết

![](images/fin_Muahang_GiamGia_trucTiep_TTchung.png)

- Khai báo thông tin Vật tư hàng hóa trả hàng cho NCC: 
  - Gồm thông tin về Mặt hàng; Số lượng; Đơn vị tính; Đơn giá và Chiết khấu/Thuế GTGT (Nếu có)
  - Với Mua hàng kiêm phiếu nhập kho: Số lô|Se-ri của mặt hàng cần trả. Hệ thống sẽ tự động view các Lô serial đang còn của Mặt hàng thực hiện trả. 
    - Nếu người dùng nhập thông tin: Thông tin Phiếu xuất kho sẽ xuất trả hàng của Lô đã chọn
    - Nếu người dùng không chọn thông tin: Hệ thống tự động lấy 1 Lô của mặt hàng để xuất trả

![](images/fin_Muahang_Trahang_tao_Chitiet.png)

**<u>Lưu ý:</u>**

- Nếu **bỏ** tích chọn **'Giảm giá trị hàng nhập kho'**: Khi Xác nhận Chứng từ trả hàng hệ thống sẽ không tạo ra Phiếu xuất tương ứng

**Bước 4**: Nhấn nút **'Xác nhận'** sau khi đã hoàn thành nhập dữ liệu

![](images/fin_Muahang_GiamGia_xacNhan.png)

**Khi đó:**

- Trạng thái của Chứng từ trả hàng là Đã vào Sổ
- Hệ thống tự động tạo ra 1 Phiếu xuất kho để Giảm giá hàng đã nhập. Người dùng nhấn nút 'Giao hàng' trên Chứng từ giảm giá để kiểm tra thông tin Phiếu xuất kho

![](images/fin_Muahang_GiamGia_GiaoHang.png)

- Trạng thái của Phiếu xuất kho là Hoàn thành, Số lượng tồn của vật tư hàng hóa được giữ nguyên, hệ thống ghi nhận Số tiền Âm

![](images/fin_Muahang_GiamGia_Kho.png)

**Bước 5**: Trường hợp Người dùng muốn đưa thông tin chứng từ về trạng thái dự thảo: Nhấn nút **Đưa về dự thảo**

![](images/fin_Muahang_GiamGia_DuThao.png)

Hệ thống đưa Chứng từ trả hàng về Dự thảo thành công. Đồng thời thông tin Phiếu xuất kho được tạo ra từ Chứng từ sẽ bị xóa khỏi hệ thống

![](images/fin_Muahang_GiamGia_DuThao_ThanhCong.png)
