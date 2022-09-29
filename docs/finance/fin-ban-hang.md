# *Quy trình nghiệp vụ*

Phân hệ **Bán hàng** quản lý toàn bộ quy trình bán hàng từ bước lên đơn hàng, xuất hóa đơn và ghi nhận thanh toán từ khách hàng. Phân hệ **Bán hàng** liên kết với phân hệ **Kho** để kiểm tra số lượng tồn khả dụng của sản phẩm, đồng thời tự động sinh phiếu nhập xuất và ghi nhận giá vốn hàng hóa sau khi xuất hóa đơn bán hàng.

 **Quy trình**

![](images/fin_banhang_quytrinh.png)



**Các luồng quy trình**

·     Lập yêu cầu báo giá gửi khách hàng. Chi tiết nghiệp vụ **[tại đây](#yeu-cau-bao-gia)**

·     Lập đơn bán hàng gửi khách hàng. Chi tiết thao tác chức năng **[tại đây](#lap-on-ban-hang)**

·     Xuất kho từ đơn bán hàng. Chi tiết thao tác chức năng [**tại đây**](#xuat-kho-on-ban-hang)

·     Tạo chứng từ bán hàng. Chi tiết thao tác chức năng **[tại đây](#hoa-on-ban-hang)**

·     Tạo chứng từ bán hàng - Giảm thuế 20%. Chi tiết thao tác chức năng **[tại đây](#hoa-on-ban-hang-giam-thue-20)**

·     Xuất kho từ chứng từ bán hàng. Chi tiết thao tác chức năng [**tại đây**](#xuat-kho-on-ban-hang)

·     Ghi nhận thanh toán từ khách hàng. Chi tiết thao tác chức năng **[tại đây](ghi-nhan-thanh-toan-tu-khach-hang)**

·     Xuất hóa đơn điện tử. Chi tiết thao tác chức năng **[tại đây](xuat-hoa-on-ien-tu)**

·     Tạo hóa đơn giảm giá/Trả hàng. Chi tiết thao tác chức năng **[tại đây](hoa-on-giam-giatra-hang)**

·     Nhập hàng trả lại từ chứng từ trả hàng. Chi tiết thao tác chức năng **[tại đây](hoa-on-giam-giatra-hang)**

## *Yêu cầu báo giá*

### Mô tả nghiệp vụ

**Nghiệp vụ**

Nhân viên kinh doanh tìm kiếm khách hàng thông qua khách hàng tiềm năng, khách hàng cũ, đối tác, nhà phân phối

Nhân viên kinh doanh sẽ tiếp thị, giới thiệu sản phẩm dịch vụ để chào hàng

Đối với những khách hàng có nhu cầu mua sản phẩm/dịch vụ, nhân viên kinh doanh sẽ tiến hành:

- Lập báo giá
- Gửi báo giá cho khách hàng

**Hướng dẫn trên phần mềm**

Phần mềm hỗ trợ nhân viên kinh doanh lập và gửi báo giá cho nhân viên kinh doanh theo các bước sau:

Bước 1: Lập báo giá. Chi tiết nghiệp vụ [tại đây](#lap-bao-gia)

Bước 2: Gửi báo giá cho khách hàng. Chi tiết nghiệp vụ [tại đây](#thuc-hien-gui-bao-gia-cho-khach-hang)

Bước 3: Xác nhận đơn bán hàng. Chi tiết nghiệp vụ [tại đây](#xac-nhan-on-ban-hang)

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Lập báo giá" 
    src="https://www.youtube.com/embed/HG7dM6czpjw?list=PLcdARb5pnnj9pfGcrvZ16mj-aXdfnNQJe"
></iframe>

### Hướng dẫn trên phần mềm

#### Lập báo giá

Nhân viên kinh doanh tiến hành lập báo giá sản phẩm/dịch vụ cho khách hàng có nhu cầu

Đối tượng thực hiện: Nhân viên kinh doanh

**Bước 1**: Vào phân hệ **Bán hàng**, Chọn **Đơn bán hàng**, chọn **Báo giá**  hoặc chọn **Báo giá** trên quy trình

![](images/fin_banhang_baogia_menu.png)

Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống

![](images/fin_banhang_baogia_timkiem.png)

![](images/fin_BanHang_BaoGia_TabChung.png)

![](images/fin_BanHang_BaoGia_TabChiTiet.png)

**Bước 2**: Khai báo các thông tin chi tiết trên báo giá

·     Chọn thông tin đơn vị, khách hàng

·     Chọn tiền tệ giao dịch trong Đơn hàng

·     Khai báo thông tin về Ngày báo giá, hiệu lực đến

·     Khai báo thông tin về Sản phẩm/dịch vụ : 

​			Chọn các sản phẩm yêu cầu báo giá cho khách hàng

​			Nhập thông tin Số lượng, Đơn giá, Chiết khấu và mức Thuế đối với từng Sản phẩm

​			Khi thực hiện Thêm ghi chú --> Thông tin nội dung sẽ được in trên file gửi khách hàng

**Bước 3**: Nhấn **Lưu** để lưu lại thông tin báo giá đã nhập

![](images/fin_banhang_baogia_luu.png)

#### **Thực hiện gửi báo giá cho khách hàng**

Bước 1: Sau khi đã có tài liệu báo giá để gửi khách hàng, Thực hiện **In** yêu cầu báo giá: kiểm tra thông tin dữ liệu trên mẫu yêu cầu báo giá và tùy chỉnh thông tin Mẫu yêu cầu

Bước 2: Thực hiện **Gửi qua Email** đến nhà cung cấp sau khi hoàn thành  báo giá, có thể tùy chỉnh thông tin mẫu gửi báo giá theo yêu cầu

![](images/fin_BanHang_BaoGia_GuiEmail.png)

#### Xác nhận đơn bán hàng

Khi có nhu cầu mua sản phẩm, khách hàng sẽ liên hệ với nhân viên bán hàng để đặt hàng. Nhân viên bán hàng thực hiện lập đơn hàng dựa trên báo giá đã gửi

Bước 1: Vào phân hệ **Bán hàng**, trên danh sách **Báo giá**, tìm thông tin các báo giá đã gửi cho khách hàng 

![](images/fin_BanHang_BaoGia_XacNhanDonHang.png)

Bước 2: Nhấn nút **Xác nhận**

**<u>Lưu ý:</u>**

Báo giá được thực hiện Xác nhận đơn hàng: Sẽ không được hiển thị trên Danh sách Báo giá

#### Sinh chứng từ giao hàng

Nếu hệ thống không có thiết lập chứng từ bán hàng kiêm phiếu xuất kho thì sau khi thực hiện Xác nhận đơn hàng, chương trình tự động sinh ra một yêu cầu giao hàng gửi tới kế toán kho/thủ kho (Phân hệ Quản lý kho/Phiếu xuất kho) Nhân viên có thể theo dõi tình trạng giao hàng của sản phẩm trên phiếu xuất kho đã sinh ra

![](images/fin_BanHang_DonBanHang.png)

## *Hợp đồng bán hàng*

### Mô tả nghiệp vụ

Đối với trường hợp bán hàng có giá trị lớn, sau khi tiếp nhận được yêu cầu mua hàng của khách hàng, nhân viên kinh doan tiến hành lập hợp đồng bán hàng  theo đơn hàng, theo dõi thanh toán và thanh lý hợp đồng

### Hướng dẫn trên phần mềm

Đối tượng thực hiện: Nhân viên kinh doanh

**Bước 1:** Vào phân hệ **Bán hàng**,  chọn chức năng **Hợp đồng bán** hoặc chọn **Hợp đồng bán** trên quy trình (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

![](images/fin_banhang_hopdongban_menu.png)

Danh sách hợp đồng sẽ hiển thị các hợp đồng bán đã được khách hàng phản hồi có nhu cầu mua sản phẩm và xác nhận tạo đơn bán hàng

![](images/fin_BanHang_HopDongBan.png)

**Bước 2**: Thực hiện **Tạo mới** hợp đồng Trên giao diện, nhập đủ các thông tin:Tên hợp đồng, khách hàng, ngày ký, giá trị hợp đồng,giá trị thanh lý, hạn giao hàng,hạn thanh toán

![](images/fin_BanHang_HopDongBanThemMoi.png)

Thực hiện chọn đơn bán hàng dùng để ký kết hợp đồng

![](images/fin_banhang_hopdongban_donhang.png)

Sau khi chọn đơn hàng, hệ thống tự động sinh dữ liệu tại tab danh sách hàng hóa bằng cách lấy các mặt hàng từ đơn hàng đã chọn hoặc tự thêm tay các mặt hàng sử dụng trong hợp đồng

![](images/fin_banhang_hopdongban_VTHH.png)

Nhấn **Lưu** để lưu lại thông tin hợp đồng

![](images/fin_banhang_hopdongban_luu.png)



## *Lập đơn bán hàng*

### Mô tả nghiệp vụ

**Nghiệp vụ**

Khi có nhu cầu mua sản phẩm, khách hàng sẽ liên hệ với hộ kinh doanh để đặt hàng. Người bán hàng thực hiện lập đơn hàng dựa trên nhu cầu của khách hàng

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Lập đơn bán hàng" 
    src="https://www.youtube.com/embed/4lI_lo2RDvU?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


### Hướng dẫn trên phần mềm

**Đối tượng thực hiện:** Người bán hàng

#### Thêm mới đơn hàng

**Bước 1:** Vào phân hệ **Bán hàng**, Chọn **Đơn bán hàng**, chọn **Báo giá** 

![](images/fin_banhang_vaochucnang.png)

Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống

![](images/fin_banhang_vaochucnang_nhanh.png)

![](images/fin_banhang_danhsach.png)

**Bước 2:** Nhấn nút **Tạo** ![](images/fin_banhang_taomoi.png)trên chức năng để thực hiện thêm một đơn hàng mới. Khai báo các thông tin chi tiết trên đơn bán hàng. 

**Lưu ý**: Các ô màu hồng là những thông tin cần bắt buộc nhập

![](images/fin_banhang_tabchung.png)

·     Chọn thông tin ***khách hàng***. Nếu chưa có khách hàng thì có thể nhập bổ sung thêm bằng cách nhập tên khách hàng và chọn tạo mới 

![](images/fin_banhang_khachhang.png)

hoặc vào đường dẫn **Danh mục/Khách hàng** và thực hiện thêm mới

![](images/fin_banhang_danhmuc_khachhang.png)

·     Chọn ***bảng giá***,  là tiền tệ giao dịch trong Đơn hàng

·     Khai báo thêm thông tin về ***Ngày đặt hàng, hiệu lực đến, điều khoản thanh toán*** (Xác định thời gian để thanh toán), ***nội dung*** chi tiết đơn hàng

Mục **Điều khoản thanh toán**: Nếu có thỏa thuận về điều kiện thanh toán với khách hàng, thực hiện chọn thông tin Điều khoản đã được khai báo trên Danh mục **Điều khoản thanh toán** . Trường hợp đã thiết lập điều khoản thanh toán cho từng khách hàng tại danh mục **Khách hàng** thì chương trình sẽ tự động hiển thị sẵn thông tin này theo nhà cung cấp được chọn

·     Khai báo thêm thông tin về Sản phẩm/dịch vụ tại chi tiết đơn hàng bằng cách nhấn chọn **Thêm sản phẩm**   ![](images/fin_banhang_themsanpham.png)

​			Chọn các sản phẩm bán hàng cho khách hàng

​			Nhập thông tin Số lượng, Đơn giá,  mức Thuế đối với từng Sản phẩm

![](images/fin_banhang_chitiet.png)

​			Khi thực hiện Thêm ghi chú --> Thông tin nội dung sẽ được in trên file gửi khách hàng

**Bước 3**: Nhấn **Lưu**

#### **Thực hiện gửi đơn hàng cho khách hàng**

**Bước 1**: Sau khi đã có đơn hàng để gửi khách hàng, Thực hiện **In đơn hàng** bằng cách chọn chức năng **In**

![](images/fin_banhang_donhang_in.png)

**Bước 2:** Thực hiện **Gửi qua Email** đến khách hàng sau khi hoàn thành  báo giá, có thể tùy chỉnh thông tin mẫu gửi báo giá theo yêu cầu

![](images/fin_BanHang_donhang_GuiEmail.png)

#### Xác nhận đơn bán hàng

Tại đơn hàng đã tạo, nếu khách hàng thực sự có nhu cầu mua hàng, người bán hàng nhấn nút **Xác nhận** để hoàn thành đơn hàng

Sau khi đơn hàng được xác nhận, sẽ có hai luồng xử lý:

Nếu thiết lập kho không chọn "**Chứng từ bán hàng kiêm phiếu xuất kho**" thì hệ thống sinh phiếu xuất kho. Sản phẩm sẽ được giao cho khách hàng

Nếu thiết lập kho chọn "**Chứng từ bán hàng kiêm phiếu xuất kho**" thì hệ thống **không** sinh phiếu xuất kho. Người dùng cần tạo chứng từ bán hàng để sinh phiếu xuất kho, sản phẩm sẽ được giao cho khách hàng

![](images/fin_DBH_thietlap.png)

Nếu không còn nhu cầu bán hàng, người bán nhấn **Hủy** hoặc thực hiện xóa đơn hàng đã tạo

![](images/fin_banhang_donhang_xoa.png)



## *Xuất kho đơn bán hàng*

### Mô tả nghiệp vụ

Khi thiết lập kho không chọn "**Chứng từ bán hàng kiêm phiếu xuất kho**" thì hệ thống sinh phiếu xuất kho. Sản phẩm sẽ được giao cho khách hàng

![](images/fin_DBH_thietlap.png)

Sau khi thực hiện **Xác nhận đơn hàng**, chương trình tự động sinh ra một yêu cầu giao hàng. Người dùng có thể theo dõi tình trạng giao hàng của sản phẩm trên phiếu xuất kho đã sinh ra và xác nhận số lượng sản phẩm bàn giao theo đơn hàng 

![](images/fin_banhang_donhang_phieuxuat.png)

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Xuất kho đơn bán hàng" 
    src="https://www.youtube.com/embed/MiV1NLnGVbM?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


### **Hướng dẫn trên phần mềm**

**Bước 1**: Kiểm tra lại thiết lập kho, yêu cầu  không chọn "**Chứng từ bán hàng kiêm phiếu xuất kho**" 

![](images/fin_DBH_thietlap.png)

**Bước 2**: Tại đơn bán hàng, nhấn **xác nhận** đơn hàng, chương trình tự động sinh ra một yêu cầu giao hàng

![](images/fin_banhang_donhang_phieuxuat.png)

**Bước 3**: Chọn **Phiếu xuất kho**, hệ thống chuyển sang chức năng phiếu xuất kho. 

![](images/fin_banhang_donhang_pxk.png)

**Bước 2**: Thực hiện nhập số lượng hàng đã hoàn thành giao cho khách hàng 

- Nếu Số lượng xuất kho đủ theo Số lượng của Đơn bán hàng: Thực hiện nhấn **Xác nhận** để xác nhận toàn bộ Đơn hàng

  ![](images/fin_banhang_donhang_pxk_xacnhan.png)

- Nếu Số lượng xuất kho Chưa đủ theo Số lượng của Đơn bán hàng: Thực hiện nhập số lượng theo thực tế bằng cách nhấn **Sửa**, vào nhóm **Vật tư, hàng hóa chi tiết**, nhập số lương **hoàn thành**, sau đó nhấn **Lưu**

  ![](images/fin_banhang_donhang_nhapslhoanthanh.png)

Nhấn **Xác nhận** để hoàn thành xuất hàng giao cho khách hàng

Khi đó có 2 hướng thực hiện :

- Nếu chọn **Tạo phần dở dang**: Với Số lượng còn thiếu, hệ thống tạo sẵn 1 chứng từ Phiếu xuất kho, để Khi nhập kho với Số lượng còn lại, bộ phận Kho tiếp tục vào Phiếu xuất kho (đã tạo phần dở dang) để thực hiện Xác nhận Số lượng xuất kho còn lại.
- Nếu chọn **Không tạo phần dở dang**: Khi đó hệ thống Tách Số lượng nhu cầu ban đầu Bằng đúng Số lượng thực xuất, còn Số lượng chênh chưa nhận được thì Số lượng hoàn thành = 0

Như vậy **Phiếu xuất kho** đã **Hoàn thành** .

## *Hóa đơn bán hàng*

### Mô tả nghiệp vụ

Sau khi xác nhận đơn hàng thành công, người dùng thực hiện  lập hóa đơn bán hàng và gửi hóa đơn cho khách hàng

### Hướng dẫn trên phần mềm

Người dùng có thể lập hóa đơn bán hàng theo các cách khác nhau

**Cách 1**:Lập hóa đơn bán hàng từ đơn bán hàng không sinh phiếu xuất kho. Chi tiết nghiệp vụ **[tại đây](#Lap-hoa-don-ban-hang-tu-don-ban-hang)**

**Cách 2**:Lập hóa đơn bán hàng từ đơn bán hàng sinh phiếu xuất kho. Chi tiết nghiệp vụ **[tại đây](#Lap-hoa-don-ban-hang-tu-don-ban-hang)**

**Cách 3**: Lập hóa đơn bán hàng không từ đơn bán hàng. Chi tiết nghiệp vụ **[tại đây](#Lap-hoa-don-ban-hang-khong-tu-don-ban-hang)**

#### Lập hóa đơn bán hàng từ đơn bán hàng (không sinh phiếu xuất kho)

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Lập hóa đơn bán hàng từ đơn bán hàng" 
    src="https://www.youtube.com/embed/-6xgVLYA9Ys?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


Đối tượng thực hiện: Người bán hàng

**Điều kiện**: Thiết lập kho không chọn "**Chứng từ bán hàng kiêm phiếu xuất kho**" 

![](images/fin_DBH_thietlap.png)

**Bước 1**: Vào phân hệ **Bán hàng**, Chọn **Đơn bán hàng** đã hoàn thành Giao hàng cho khách hàng và Nhấn **Tạo hóa đơn**

![](images/fin_banhang_donhang_taohoadon.png)



**Bước 2**: Trên thông tin **Hóa đơn bán hàng** vừa được tạo , Nhân viên thực hiện nhập các dữ liệu về:

- Hóa đơn: **Ngày hóa đơn, Mẫu số hóa đơn,  Số hóa đơn**

  ![](images/fin_banhang_donhang_hoadon_tabchung.png)

- Chọn và nhập thông tin về Thuế và Chiết khấu tương ứng của Đơn hàng (Nếu có)

  ![](images/fin_banhang_donhang_hoadon_tabchitiet.png)

**Bước 3**: Nhân viên thực hiện nhấn **Xác nhận**

**Lưu ý:** Để nhìn lại tình trạng hóa đơn của đơn bán hàng, người dùng có thể vào chức năng đơn bán hàng, nhấn chọn **Hóa đơn** tại góc phải màn hình 

![](images/fin_banhang_donhang_hoadon_button.png)

#### Lập hóa đơn bán hàng từ đơn bán hàng (sinh phiếu xuất kho)

Đối tượng thực hiện: Người bán hàng

**Điều kiện**: Thiết lập kho chọn "**Chứng từ bán hàng kiêm phiếu xuất kho**" 

![](images/fin_DBH_thietlap1.png)

**Bước 1**: Vào phân hệ **Bán hàng**, Chọn **Đơn bán hàng** đã xác nhận và Nhấn **Tạo chứng từ**

![](images/fin_banhang_donhang_taochungtu.png)

**Bước 2**: Trên thông tin **Chứng từ bán hàng** vừa được tạo , hệ thống tự động sinh bổ sung thông tin liên quan đến xuất kho bao gồm:

- Loại xuất kho: Mặc định loại xuất bán hàng hóa
- Kho xuất: Mặc định là kho chính của hệ thống, lấy theo loại xuất kho đang chọn

Nhân viên thực hiện nhập các dữ liệu về:

- Hóa đơn: **Ngày hạch toán, Mẫu số hóa đơn,  Số hóa đơn**

  ![](images/fin_banhang_donhang_hoadon_tabchung1.png)

- Chọn và nhập thông tin về  Chiết khấu tương ứng của Đơn hàng (Nếu có)

  ![](images/fin_banhang_donhang_hoadon_tabchitietCK.png)

**Bước 4**: Nhân viên thực hiện nhấn **Xác nhận** để hoàn thành chứng từ

Nếu như đủ hàng còn tồn trong kho, hệ thống sẽ xác nhận thành công và sinh một phiếu xuất kho ở trạng thái đã ghi sổ với loại xuất bằng loại xuất tương ứng đã chọn tại chứng từ bán hàng. Sản phẩm sẽ được giao cho khách hàng

![](images/fin_banhang_HDBH_PXK.png)

**Bước 5**: Nhấn chọn **Giao hàng**, hệ thống chuyển sang chức năng phiếu xuất kho. Người dùng có thể kiểm tra lại thông tin hàng hóa đã xuất kho

![](images/fin_banhang_donhang_pxk_chung.png)

**Bước 6**: Tại chứng từ bán hàng, khi người dùng nhấn **Chuyển về nháp**, hệ thống thực hiện đưa chứng từ bán hàng về trạng thái dự thảo, đồng thời sẽ xóa phiếu xuất kho tương ứng

![](images/fin_banhang_donhang_hoadon_tabchung2.png)

**Lưu ý:** Để nhìn lại tình trạng hóa đơn của đơn bán hàng, người dùng có thể vào chức năng đơn bán hàng, nhấn chọn **Hóa đơn** tại góc phải màn hình 

![](images/fin_banhang_donhang_hoadon_button1.png)

#### Lập hóa đơn bán hàng không qua đơn bán hàng

Đối tượng thực hiện: Người bán hàng

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Lập hóa đơn bán hàng không từ đơn bán hàng" 
    src="https://www.youtube.com/embed/-6xgVLYA9Ys?list=PLcdARb5pnnj9pfGcrvZ16mj-aXdfnNQJe"
></iframe>

**Bước 1**: Vào phân hệ **Bán hàng**, Chọn **Hóa đơn** , chọn **Hóa đơn bán hàng** 

![](images/fin_banhang_hoadon.png)

Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống

![](images/fin_banhang_hoadon_timkiemnhanh.png)

![](images/fin_banhang_hoadon_viewdanhsach.png)

**Bước 2**: Nhấn nút **tạo** ![](images/fin_banhang_taomoi.png) để thêm hóa đơn. 

Trên thông tin Hóa đơn bán hàng, Nhân viên kế toán thực hiện nhập các dữ liệu về:

- Chọn thông tin ***khách hàng***. Nếu chưa có khách hàng thì có thể nhập bổ sung thêm bằng cách nhập tên khách hàng và chọn tạo mới ![](images/fin_banhang_khachhang.png)

hoặc vào đường dẫn **Danh mục/Khách hàng** và thực hiện thêm mới

![](images/fin_banhang_danhmuc_khachhang.png)

- Nhập bổ sung thông tin gồm: Ngày hóa đơn, Mẫu số, Ký hiệu hóa đơn ,Số hóa đơn, hạn thanh toán

  ![](images/fin_banhang_donhang_hoadon_tabchung.png)

- Chọn và nhập thông tin về sản phẩm, số lượng, giá thành bán,Thuế và Chiết khấu của sản phẩm cần lập hóa đơn

  ![](images/fin_banhang_donhang_hoadon_tabchitiet.png)

**Bước 3**: Nhân viên Kế toán thực hiện nhấn **Lưu** . Hệ thống lưu thông tin chi tiết hóa đơn đã nhập và tự động sinh ra các chi tiết bút toán phát sinh

Thông tin dữ liệu bút toán phát sinh:

- Căn cứ thông tin Thuế  đã lựa chọn cùng với thông tin Chiết khấu, Đơn giá, Số lượng đã nhập bên chi tiết hóa đơn, hệ thống thực hiện mặc định thông tin các bút toán tương ứng

![](images/fin_banhang_hoadon_buttoan.png)

**Bước 4**: Nhân viên Kế toán thực hiện nhấn **Xác nhận** để hoàn thành xuất hóa đơn bán hàng

Sau khi xác nhận hóa đơn, hệ thống sẽ sinh dữ liệu vào chức năng "Thu tiền từ khách hàng", người dùng kiểm tra thông tin sẽ thanh toán bằng cách vào **Ngân quỹ/Tiền mặt/Thu tiền từ khách hàng** hoặc **Ngân quỹ/Tiền gửi/Thu tiền từ khách hàng** để kiểm tra lại số tiền sẽ được thanh toán

![](images/fin_banhang_xacnhan.png)

**Chú ý**: Nếu thiết lập kho chọn "**Chứng từ bán hàng kiêm phiếu xuất kho**" thì sau khi xác nhận thành công chứng từ bán hàng,  hệ thống **tự sinh** phiếu xuất kho ở trạng thái đã ghi sổ nhằm thực hiện xuất luôn hàng bán cho khách hàng. 

![](images/fin_DBH_thietlap1.png)

![](images/fin_banhang_HDBH_PXK1.png)

Nhấn chọn **Giao hàng**, hệ thống chuyển sang chức năng phiếu xuất kho. Người dùng có thể kiểm tra lại thông tin hàng hóa đã xuất kho

![](images/fin_banhang_donhang_pxk_chung1.png)

Tại chứng từ bán hàng, khi người dùng nhấn **Đưa về dự thảo**, hệ thống thực hiện đưa chứng từ bán hàng về trạng thái dự thảo, đồng thời sẽ xóa phiếu xuất kho tương ứng

![](images/fin_banhang_donhang_hoadon_tabchung3.png)

## *Chứng từ bán hàng - Giảm thuế 20%*

### Mô tả nghiệp vụ

Sau khi giao hàng thành công, người dùng thực hiện kiểm tra dữ liệu và lập hóa đơn bán hàng cho những mặt hàng được quy định giảm thuế 20% theo Nghị quyết số 43/2022/QH15 và gửi hóa đơn cho khách hàng. 

**Giảm thuế 20%** Chỉ áp dụng với Công ty có **Thiết lập** tại nhóm **Kế toán** với **Phương pháp tính thuế GTGT** = **Trực tiếp trên doanh thu**

(Đối với Hộ kinh doanh cá thể: Thông tin thiết lập này được mặc định là  **Trực tiếp trên doanh thu**)

### Hướng dẫn trên phần mềm

#### Lập hóa đơn bán hàng có Giảm thuế 20%

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Hóa đơn giảm thuế" 
    src="https://www.youtube.com/embed/T-Gz3db3b-M?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>




Đối tượng thực hiện: Người bán hàng

**Bước 1**: Vào Màn hình qua 2 cách :

- **Cách 1**: Lập hóa đơn từ Đơn bán hàng bằng cách: Vào phân hệ **Bán hàng**, Chọn **Đơn bán hàng** đã hoàn thành Giao hàng cho khách hàng và Nhấn **Tạo hóa đơn**

![](images/fin_banhang_donhang_taohoadon.png)

Trên màn hình **Tạo Hóa đơn**, kế toán thực hiện chọn loại hóa đơn thanh toán dựa trên số tiền khách hành thanh toán

![](images/fin_banhang_donhang_taohoadon_popup.png)

- Hóa đơn thông thường: Hệ thống tạo 1 hóa đơn với số lượng, số tiền tương ứng với đơn bán hàng

- Tiền đặt cọc (Theo phần trăm): Hệ thống tạo 1 hóa đơn với số tiền thanh toán theo tỷ lệ phần trăm với số tiền bên đơn bán hàng

- Tiền đặt cọc (Số tiền cố định): Hệ thống tạo 1 hóa đơn với số tiền thanh toán bằng số tiền đã nhập sẵn trên giao diện

  Chọn **Tạo & xem hóa đơn** hoặc **Tạo hóa đơn** để thực hiện sinh hóa đơn theo yêu cầu

- **Cách 2**: Lập Hóa đơn bán hàng không từ Đơn bán hàng (Lập trực tiếp) bằng cách: Vào phân hệ **Bán hàng**, Chọn **Hóa đơn** , chọn **Hóa đơn bán hàng** 

![](images/fin_banhang_hoadon.png)

Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống

![](images/fin_banhang_hoadon_timkiemnhanh.png)

![](images/fin_banhang_hoadon_viewdanhsach.png)

* Nhấn nút **tạo** ![](images/fin_banhang_taomoi.png) để thêm hóa đơn. 

**Bước 2**: Trên thông tin **Hóa đơn bán hàng** vừa được tạo , Nhân viên thực hiện nhập các dữ liệu về:

- Hóa đơn: **Ngày hóa đơn, Mẫu số hóa đơn,  Số hóa đơn** và **Tích chọn 'Giảm 20% thuế GTGT theo NQ 43** (Khi tích chọn giá trị này chương trình sẽ tự động tính phần giảm của Thuế GTGT )

  ![](images/fin_banhang_taohoadon_giamthue.png)

  

- Chọn và nhập thông tin về Mặt hàng và Chiết khấu tương ứng của Đơn hàng (Nếu có), thông tin Thuế GTGT được giảm sẽ tính trực tiếp trên từng dòng mặt hàng

  ![](images/fin_banhang_taohoadon_giamthue_tabChitiet.png)



**Bước 3**: Nhân viên thực hiện nhấn **Xác nhận**

## *Ghi nhận thanh toán từ khách hàng*

### Mô tả nghiệp vụ

Người dùng thực hiện ghi nhận và theo dõi việc thanh toán của hóa đơn sau khi xác nhận xuất hóa đơn thành công

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Ghi nhận thanh toán" 
    src="https://www.youtube.com/embed/3vKDOm9ja5I?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>



### Hướng dẫn trên phần mềm

Đối tượng thực hiện: Người bán hàng

**Bước 1**: Vào phân hệ **Bán hàng**, chọn **Hóa đơn**, chọn **Hóa đơn bán hàng**. Trên danh sách hóa đơn bán hàng, kế toán tìm tới các hóa đơn đã được ghi sổ

![](images/fin_banhang_hoadon_danhsach.png)

**Bước 2**: Chọn hóa đơn cần thanh toán, Nhấn nút **Ghi nhận thanh toán**. 

![](images/fin_BanHang_HoaDon_GhiNhanThanhToan.png)

Người dùng nhập và sửa thông tin Tài khoản ngân hàng người nhận, khách hàng, ngày thanh toán tiền, số tiền khách hàng đã trả

![](images/fin_BanHang_HoaDon_GhiNhanThanhToan_Popup.png)

**Bước 3**: Nhấn **Tạo thanh toán**, hệ thống sinh phiếu thu tiền  để thu tiền khách hàng đã thực hiện trả

**Bước 4**: Để kiểm tra lại phiếu thu tiền, người dùng có thể tìm phiếu thu bằng cách:

Nếu Tại thông tin **Ghi nhận thanh toán**, **Sổ nhật ký** được chọn là **tiền mặt** thì người dùng vào chức năng **Ngân quỹ/Tiền mặt/Phiếu thu**. 

![](images/fin_banhang_hoadon_phieuthu.png)

Nếu Tại thông tin **Ghi nhận thanh toán**, **Sổ nhật ký** được chọn là **tiền gửi** thì người dùng vào chức năng **Ngân quỹ/Tiền gửi/Báo có**. 

![](images/fin_banhang_hoadon_baoco.png)

Người dùng có thể tìm thấy phiếu thu tiền dựa trên ngày thanh toán, đối tác thanh toán, tổng tiền, nội dung giao dịch

![](images/fin_banhang_hoadon_phieuthu_danhsach.png)

## *Chứng từ trả hàng*

### Mô tả nghiệp vụ

Khi phát sinh nghiệp vụ trả lại hàng đã bán, thông thường sẽ có các hoạt động sau:

Nếu phát hiện hàng mua về không đúng quy cách, phẩm chất theo hợp đồng đã ký, khách hàng thoả thuận với doanh nghiệp trả lại hàng đã mua.

Cách 1: Người bán hàng lập hóa đơn trả hàng bán để giao cho khách hàng và ghi sổ kế toán.Chi tiết nghiệp vụ **[tại đây](#tao-hoa-on-tra-hang)**

Cách 2: Người bán hàng chuyển đổi hóa đơn bán hàng thành khoản hoàn tiền/công nợ giảm. Chi tiết nghiệp vụ **[tại đây](#chuyen-oi-thanh-khoan-hoan-tiencong-no-giam)**

### Hướng dẫn trên phần mềm

Đối tượng thực hiện: Nhân viên kế toán

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Tạo hóa đơn giảm giá" 
    src="https://www.youtube.com/embed/fV4wocdQ2HY?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


#### Tạo hóa đơn trả hàng không có thiết lập bán hàng kiêm phiếu xuất kho

**Bước 1**: Vào phân hệ **Bán hàng**, chọn **Hóa đơn**, chọn **Hóa đơn bán hàng**. Trên danh sách hóa đơn bán hàng, kế toán tìm tới các hóa đơn đã được ghi sổ, nhấn chọn **Tạo CT trả hàng/giảm giá**

![](images/fin_BanHang_HoaDon_TaoHDGiamGia1.png)

**Bước 2**: Chọn **chứng từ trả hàng** nếu muốn thực hiện trả hàng

Hệ thống tự sinh chứng từ trả hàng với thông tin tương ứng với hóa đơn bán hàng. 

Trên hóa đơn trả hàng được sinh ra, kế toán khai báo  các thông tin trên chứng từ trả hàng hàng bán như: số lượng hàng được trả, giá trị trả

![](images/fin_BanHang_HoaDon_HDGiamGia.png)

Nhấn **xác nhận** để ghi sổ thông tin hóa đơn. 

Sau đó, người dùng sẽ **xuất hóa đơn** để gửi lại cho khách hàng và **ghi nhận lại thanh toán**

![](images/fin_banhang_hoadon_giamgia_ghinhantt.png)

#### Tạo hóa đơn trả hàng có thiết lập bán hàng kiêm phiếu xuất kho

Nếu thiết lập kho chọn "**Chứng từ bán hàng kiêm phiếu xuất kho**" thì khi nhấn tạo chứng từ trả hàng từ chứng từ bán hàng, hệ thống tự sinh chứng từ trả hàng với thông tin tương ứng với hóa đơn bán hàng và bổ sung thêm một số thông tin sau:

![](images/fin_DBH_thietlap1.png)

![](images/fin_BanHang_HoaDon_HDGiamGia1.png)

- Loại nhập: Mặc định là Nhập hàng bán trả lại
- Kho nhập: Mặc định kho chính của hệ thống, lấy theo loại nhập

Trên hóa đơn trả hàng được sinh ra, kế toán khai báo  các thông tin trên chứng từ trả hàng hàng bán như: số lượng hàng được trả, giá trị trả. Nhấn **xác nhận** để ghi sổ thông tin hóa đơn.

Sau khi xác nhận thành công chứng từ trả hàng,  hệ thống **tự sinh** phiếu nhập kho ở trạng thái đã ghi sổ nhằm thực hiện nhập lại hàng đã trả

![](images/fin_banhang_HDTH_PNK.png)

Nhấn chọn **Nhận hàng**, hệ thống chuyển sang chức năng phiếu nhập kho. Người dùng có thể kiểm tra lại thông tin hàng hóa đã nhập lại vào kho

![](images/fin_banhang_HDTH_PNK_tabchung.png)

Tại chứng từ trả hàng, khi người dùng nhấn **Đưa về dự thảo**, hệ thống thực hiện đưa chứng từ trả hàng về trạng thái dự thảo, đồng thời sẽ xóa phiếu nhập kho tương ứng

![](images/fin_banhang_HDTH_Nhap.png)

#### Chuyển đổi thành khoản hoàn tiền/công nợ giảm

Bước 1: Vào phân hệ **Bán hàng**, chọn **Hóa đơn**, chọn **Hóa đơn bán hàng**. Trên danh sách hóa đơn bán hàng, kế toán tìm tới hóa đơn có nhu cầu hoàn hàng, nhấn chọn tiện ích/chuyển đổi thành khoản hoàn tiền/công nợ giảm

![](images/fin_BanHang_HoaDon_ButtonChuyenDoi.png)

Hệ thống chuyển đổi từ hóa đơn bán hàng thành hóa đơn giảm giá/trả hàng, các thông tin được giữ nguyên

## *Chứng từ giảm giá*

### Mô tả nghiệp vụ

Khi phát sinh nghiệp vụ giảm giá hàng bán hoặc trả lại hàng đã bán, thông thường sẽ có các hoạt động sau:

Nếu phát hiện hàng mua về không đúng quy cách , phẩm chất theo hợp đồng đã ký, khách hàng thoả thuận với doanh nghiệp thực hiện làm hóa đơn giảm giá hàng đã mua.

Cách 1: Người bán hàng lập hóa đơn giảm giá hàng bán để giao cho khách hàng và ghi sổ kế toán.Chi tiết nghiệp vụ **[tại đây](#tao-hoa-on-giam-gia)**

Cách 2: Người bán hàng chuyển đổi hóa đơn bán hàng thành khoản hoàn tiền/công nợ giảm. Chi tiết nghiệp vụ **[tại đây](#chuyen-oi-thanh-khoan-hoan-tiencong-no-giam)**

### Hướng dẫn trên phần mềm

Đối tượng thực hiện: Nhân viên kế toán

**Xem video hướng dẫn**

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Tạo hóa đơn giảm giá" 
    src="https://www.youtube.com/embed/fV4wocdQ2HY?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>



#### Tạo hóa đơn giảm giá

**Bước 1**: Vào phân hệ **Bán hàng**, chọn **Hóa đơn**, chọn **Hóa đơn bán hàng**. Trên danh sách hóa đơn bán hàng, kế toán tìm tới các hóa đơn đã được ghi sổ, nhấn chọn **Tạo HĐ giảm giá**

![](images/fin_BanHang_HoaDon_TaoHDGiamGia.png)

**Bước 2**: Nhập Lý do tạo hóa đơn, Nhấn **Đảo ngược**

![](images/fin_BanHang_HoaDon_TaoHDGiamGia_popup.png)

Hệ thống tự sinh hóa đơn giảm giá với thông tin tương ứng với hóa đơn bán hàng. 

Trên hóa đơn giảm giá được sinh ra, kế toán khai báo  các thông tin trên chứng từ giảm giá hàng bán như: số lượng hàng được giảm, giá trị giảm

![](images/fin_BanHang_HoaDon_HDGiamGia.png)

Nhấn **xác nhận** để ghi sổ thông tin hóa đơn. 

Sau đó, người dùng sẽ **xuất hóa đơn** để gửi lại cho khách hàng và **ghi nhận lại thanh toán**

![](images/fin_banhang_hoadon_giamgia_ghinhantt.png)

#### Chuyển đổi thành khoản hoàn tiền/công nợ giảm

Bước 1: Vào phân hệ **Bán hàng**, chọn **Hóa đơn**, chọn **Hóa đơn bán hàng**. Trên danh sách hóa đơn bán hàng, kế toán tìm tới hóa đơn có nhu cầu hoàn hàng, nhấn chọn tiện ích/chuyển đổi thành khoản hoàn tiền/công nợ giảm

![](images/fin_BanHang_HoaDon_ButtonChuyenDoi.png)

Hệ thống chuyển đổi từ hóa đơn bán hàng thành hóa đơn giảm giá/trả hàng, các thông tin được giữ nguyên

## Chứng từ điều chỉnh

### Mô tả nghiệp vụ

Khi thông tin hóa đơn bán hàng có sự sai lệch, người dùng vào chức năng Chứng từ điều chỉnh để chỉnh lại thông tin hóa đơn đã xuất ra

### Hướng dẫn trên phần mềm

Đối tượng thực hiện: Người bán hàng

**Bước 1**: Vào phân hệ **Bán hàng**, Chọn **Bán hàng**, chọn **Chứng từ điều chỉnh**  

![](images/fin_banhang_CTDC_menu.png)

Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống

![](images/fin_banhang_CTDC_timkiem.png)

![](images/fin_banhang_CTDC_danhsach.png)

**Bước 2**: Khai báo các thông tin chi tiết trên chứng từ điều chỉnh

Nhấn nút **tạo** ![](images/fin_banhang_taomoi.png) để thêm hóa đơn, chọn loại chứng từ điều chỉnh tăng hoặc chứng từ điều chỉnh giảm

![](images/fin_banhang_CTDC_chon.png)



![](images/fin_banhang_CTDC_tabchung.png)



Trên thông tin chứng từ, Nhân viên kế toán thực hiện nhập các dữ liệu về:

Chọn **Đơn vị** cần điều chỉnh chứng từ

Chọn hóa đơn cần điều chỉnh tại trường **Điều chỉnh cho**. Hệ thống sẽ hiển thị toàn bộ các chứng từ bán hàng đã được phát hành hóa đơn điện tử

![](images/fin_banhang_CTDC_dieuchinhcho.png)

Sau khi chọn chứng từ cần điều chỉnh, hệ thống tự động hiển thị các thông tin khách hàng, ngày hạch toán, hạn thanh toán, .. và các thông tin chi tiết hóa đơn được lấy từ chi tiết hóa đơn của chứng từ bán hàng

![](images/fin_banhang_CTDC_fillDL.png)

Nhập thông tin gồm:  Mẫu số, Ký hiệu hóa đơn ,Số hóa đơn, hạn thanh toán.Thay đổi lại các thông tin cần xuất hóa đơn thay thế như sản phẩm, số lượng, giá thành bán,Thuế và Chiết khấu của sản phẩm cần lập hóa đơn

![](images/fin_banhang_donhang_hoadon_tabchitiet.png)

**Bước 3**: Nhân viên Kế toán thực hiện nhấn **Lưu** . Hệ thống lưu thông tin chi tiết hóa đơn đã nhập và tự động sinh ra các chi tiết bút toán phát sinh

Thông tin dữ liệu bút toán phát sinh:

- Căn cứ thông tin Thuế  đã lựa chọn cùng với thông tin Chiết khấu, Đơn giá, Số lượng đã nhập bên chi tiết hóa đơn, hệ thống thực hiện mặc định thông tin các bút toán tương ứng

![](images/fin_banhang_CTDC_Hachtoan.png)



**Bước 4**: Nhân viên Kế toán thực hiện nhấn **Xác nhận** để hoàn thành  hóa đơn điều chỉnh

![](images/fin_banhang_CTDC_ButtonXacnhan.png)

![](images/fin_banhang_CTDC_Button.png)

Các chức năng ghi nhận thanh toán, tạo chứng từ giảm/trả hàng, đưa về dự thảo tương tự với chứng từ bán hàng

Sau khi xác nhận thành công, người dùng có thể xuất hóa đơn điện tử điều chỉnh  bằng cách nhấn nút **Xuất hóa đơn điều chỉnh**, hệ thống mở một cửa sổ để nhập thông tin xuất hóa đơn thay thế hóa đơn gốc, thông tin  tương tự với chức năng xuất hóa đơn điện tử

