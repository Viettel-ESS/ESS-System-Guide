# Quy trình nghiệp vụ

Phân hệ **Ngân quỹ** quản lý tình hình thu/chi tiền mặt và tiền gửi ngân hàng của doanh nghiệp, giúp kế toán hạn chế ghi nhận sai và chi âm tiền. Hỗ trợ kiểm soát những hóa đơn bán hàng/ hóa đơn mua hàng chưa thanh toán hoặc đã thanh toán một phần

**Quy trình**

![TM_2218](images/TM_2218.png)

**Các luồng quy trình**

·     Lập chứng từ Thu tiền mặt. Chi tiết nghiệp vụ **[Thu tiền mặt](#thu-tien-mat)**

·     Lập chứng từ Chi tiền mặt. Chi tiết nghiệp vụ **[Chi tiền mặt](#chi-tien-mat)**

·     Kiểm kê tiền mặt. Chi tiết nghiệp vụ **[Kiểm kê tiền mặt](#kiem-ke-tien-mat)**

·     Thanh toán lương cho nhân viên. Chi tiết nghiệp vụ **[Thanh toán lương cho nhân viên](#thanh-toan-luong-cho-nhan-vien)**

## Thu tiền mặt

### *Xem video hướng dẫn*

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Module Ngân quỹ - Thu tiền mặt" 
    src="https://www.youtube.com/embed/98JjKDjx5o8?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>

### Thu tiền mặt

#### Mô tả nghiệp vụ

Khi phát sinh các nghiệp vụ thu tiền mặt từ những nguồn thu ngoài các luồng nghiệp vụ đang có như Thu tiền nhượng bán TSCĐ, Thu tiền thanh lý TSCĐ, Rút tiền gửi về nhập quỹ hoặc từ một nguồn thu tiền mặt khác, người dùng sử dụng tính năng Thu tiền mặt để nhập dữ liệu

#### Hướng dẫn trên phần mềm

**Bước 1:** Vào phân hệ **Ngân quỹ**, Chọn **Tiền mặt**, Chọn **Thu tiền mặt ** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống), Nhấn **Tạo**

![fin_NganQuy_TM_PT_TAO](images/fin_NganQuy_TM_PT_TAO.png)

**Bước 2:** Khai báo các thông tin Tab chung của phiếu **Thu tiền mặt**

- Tại mục **Sổ nhật ký** : Chọn Sổ quỹ nhập tiền
- Chọn và nhập các thông tin về: Đối tượng, Người nộp tiền, Nhân viên thu, Chứng từ kèm theo và Nội dung giao dịch (Nếu có)

![fin_NganQuy_TM_PT_TabChung](images/fin_NganQuy_TM_PT_TabChung.png)

**Bước 3:** Tại Tab **Chi tiết** của phiếu **Thu tiền mặt** nhấn **Thêm một dòng**

- **Lý do**: Chọn Lý do thu tiền mặt
- **Số tiền**: Nhập số tiền thu được theo từng lý do thu
- Chọn và nhập các thông tin về Khoản mục phí, Công trình, Ngày đến hạn, Hợp đồng mua, Hợp đồng bán, Nội dung chi tiết (Nếu có)

![fin_NganQuy_TM_PT_TabChitiet](images/fin_NganQuy_TM_PT_TabChitiet.png)

**Bước 4:** Nhấn **Lưu**

Sau khi Lưu lại thông tin: Hệ thống tự động hiển thị thông tin bút toán với số tiền tương ứng đã nhập bên Tab **Hạch toán**

Để sửa lại dữ liệu: Người dùng nhấn nút **Sửa**

![fin_NganQuy_TM_PT_TabHachToan](images/fin_NganQuy_TM_PT_TabHachToan.png)

**Bước 4:** Nhấn **Xác nhận**: Sau khi dữ liệu đã nhập đúng và đủ. Hệ thống đưa các bút toán vào sổ và chuyển trạng thái chứng từ thành **Đã vào sổ**

Để sửa lại thông tin đã nhập Người dùng phải nhấn nút **Đưa về dự thảo** 

![fin_NganQuy_TM_PT_Xacnhan](images/fin_NganQuy_TM_PT_Xacnhan.png)

### Thu tiền từ khách hàng

#### Mô tả nghiệp vụ

Với những giao dịch khách hàng thanh toán bằng tiền mặt cho các đơn hàng, người dùng thực hiện nghiệp vụ thu tiền từ khách hàng và nhập vào hệ thống để ghi nhận thông tin.

#### *Xem video hướng dẫn*

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Module Ngân quỹ - Thu tiền từ khách hàng bằng tiền mặt" 
    src="https://www.youtube.com/embed/4XInLxXfr6s?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


#### Hướng dẫn trên phần mềm

**Bước 1:** Vào phân hệ **Ngân quỹ**, Chọn **Tiền mặt**, Chọn **Thu tiền từ khách hàng** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

![fin_NganQuy_TM_ThutienKH_Danhsach](images/fin_NganQuy_TM_ThutienKH_Danhsach.png)

- Tích chọn chứng từ khách hàng thanh toán tiền nợ
- Nhấn **Ghi nhận thanh toán**

![fin_NganQuy_TM_ThutienKH_GhinhanTT](images/fin_NganQuy_TM_ThutienKH_GhinhanTT.png)

**Bước 2:** Nhập các thông tin trên màn hình Ghi nhận thanh toán

- Tại mục Sổ nhật ký: Chọn **Tiền mặt**

- Với thông tin Số tiền:

  Nếu Khách hàng trả toàn bộ số tiền theo Hóa đơn: Giữ nguyên thông tin **Số trả**

  ![fin_NganQuy_TM_ThutienKH_PopupGhinhanTT](images/fin_NganQuy_TM_ThutienKH_PopupGhinhanTT.png)

  Nếu Khách hàng chưa trả đủ số tiền theo Hóa đơn: Thực hiện Sửa thông tin Số trả theo giá trị tiền thực tế. Với Số tiền còn lại có 2 lựa chọn

  - **Giữ vẫn mở**: Khi đó hệ thống Ghi nhận theo đúng giá trị đã trả trong đợt đầu, và đánh dấu chưa thanh toán đủ
  - **Đánh dấu đã trả đủ**: Hệ thống ghi nhận theo giá trị **Số trả** và đánh dấu đã thanh toán đủ cho Hóa đơn

  ![fin_NganQuy_TM_ThutienKH_PopupGhinhanTT01](images/fin_NganQuy_TM_ThutienKH_PopupGhinhanTT01.png)
  
  **Lưu ý**: Khi Đánh dấu đã trả đủ thực hiện nhập tài khoản để ghi nhận số tiền còn lại của hóa đơn tại trường **Vào sổ giá trị chệnh lệch vào**
  
  ![fin_NganQuy_TM_ThutienKH_PopupGhinhanTT02](images/fin_NganQuy_TM_ThutienKH_PopupGhinhanTT02.png)

**Bước 3**: Nhấn **Tạo Thanh toán** để tạo Phiếu thu tiền mặt

![fin_NganQuy_TM_ThutienKH_Taothanhtoan](images/fin_NganQuy_TM_ThutienKH_Taothanhtoan.png)

- Thông tin Phiếu thu tiền mặt được tạo với các thông tin đã chọn trên phần Ghi nhận thanh toán
- Hệ thống tự động hạch toán và lên bút toán 

![fin_NganQuy_TM_ThutienKH_SinhPTTM](images/fin_NganQuy_TM_ThutienKH_SinhPTTM.png)

- Hệ thống Ghi nhận Thanh toán 1 phần cho các Hóa đơn chưa thanh toán đủ

![fin_NganQuy_TM_ThutienKH_TinhtrangTT](images/fin_NganQuy_TM_ThutienKH_TinhtrangTT.png)

## Chi tiền mặt

### *Xem video hướng dẫn*

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Module Ngân quỹ - Chi tiền mặt" 
    src="https://www.youtube.com/embed/MV97BC-bLUE?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


### Thanh toán tiền điện nước, tiền internet, tiền thuê mặt bằng..

#### Mô tả nghiệp vụ

Kế toán thực hiện tạo Phiếu chi tiền mặt cho các dịch vụ phát sinh hàng tháng như : Điện, nước,internet. mặt bằng,......

#### Hướng dẫn trên phần mềm

**Bước 1:** Vào phân hệ **Ngân quỹ**, Chọn **Tiền mặt**, Chọn **Chi tiền mặt** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống), Nhấn **Tạo**

![fin_NganQuy_TM_PC_TAO](images/fin_NganQuy_TM_PC_TAO.png)

**Bước 2:** Khai báo các thông tin tab chung của **Chi tiền mặt**

- Tại mục **Sổ nhật ký**: Thực hiện chọn Sổ quỹ chi tiền

- Tại mục **Đối tượng**: Chọn Khách hàng/Nhà cung cấp.
- Tại mục **Tài khoản ngân hàng đối tượng** : Chọn tài khoản nhận tiền (Nếu có)
- Tại mục **Người nhận**: Nhập người nhận tiền (Nếu có)

![fin_Nganquy_TM_PC_Tabchung](images/fin_Nganquy_TM_PC_Tabchung.png)

**Bước 2:** Tại tab **Chi tiết** nhấn **Thêm một dòng** và khai báo

- **Lý do**: Chọn Lý do chi tiền (VD: Chi phí điện bằng tiền mặt, Chi tiền mua văn phòng phẩm, Chi trả cho nhà cung cấp, Chi tiền mặt khác........)
- **Số tiền**: Nhập số tiền chi cho từng lý do chi
- Nhập Nội dung chi tiết, Công trình, Hợp đồng mua, Hợp đồng bán (Nếu có)

![fin_nganquy_TM_PC_TabChitiet](images/fin_nganquy_TM_PC_TabChitiet.png)

**Bước 3:** Nhấn **Lưu**

![fin_nganquy_TM_PC_Luu](images/fin_nganquy_TM_PC_Luu.png)

**Bước 4:** Sau khi kiểm tra thông tin đã đầy đủ và chính xác , Nhấn **Xác nhận**: Khi đó thông tin bút toán được Hạch toán vào sổ

![fin_nganquy_TM_PC_Xacnhan](images/fin_nganquy_TM_PC_Xacnhan.png)

**Lưu ý:**

-  Muốn chuyển trạng thái từ Hoàn thành về Nháp thì Nhấn **Hủy xác nhận**

![fin_nganquy_TM_PC_Duaveduthao](images/fin_nganquy_TM_PC_Duaveduthao.png)

### Thanh toán các chi phí: BHXH, BHYT, BH thất nghiệp

#### Mô tả nghiệp vụ

Thực hiện chi trả các khoản liên quan đến Bảo hiểm xã hội, bảo hiểm y tế hoặc Chi trả thất nghiệp cho nhân viên

#### *Xem video hướng dẫn*

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Module Ngân quỹ - Nộp bảo hiểm bằng tiền mặt" 
    src="https://www.youtube.com/embed/ydW5MOnbLDA?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>

#### Hướng dẫn trên phần mềm

**Bước 1:** Vào phân hệ **Ngân quỹ**, Chọn **Tiền mặt**, Chọn **Nộp bảo hiểm** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

Khai báo Tab chung

- **Ngày nộp bảo hiểm**: Nhập ngày nộp bảo hiểm
- **Sổ nhật ký**: Chọn Tiền mặt

![fin_nganquy_TM_NopBH_TABCHUNG](images/fin_nganquy_TM_NopBH_TABCHUNG.png)

Khai báo Tab chi tiết

- **Số trả lần này**: Nhập số tiền sẽ chi trả bảo hiểm. 

![fin_nganquy_TM_NopBH_Tabchitiet](images/fin_nganquy_TM_NopBH_Tabchitiet.png)

**Lưu ý**: Dữ liệu Tab chi tiết lấy tổng tiền dư Có - Dư nợ > 0 tính đến Ngày nộp bảo hiểm của tài khoản Phải trả bảo hiểm được tích chọn trong Danh mục Hệ thống tài khoản

Nhấn **Lưu**

![fin_nganfin_nganquy_TM_NopBH_Luu](images/fin_nganfin_nganquy_TM_NopBH_Luu.png)

Nhấn **Ghi nhận thanh toán**

![fin_nganfin_nganquy_TM_NopBH_GhinhanTT](images/fin_nganfin_nganquy_TM_NopBH_GhinhanTT.png)

**Bước 2**: Sau khi Ghi nhận thanh toán hệ thống sinh bản ghi sang phiếu chi tiền mặt 

- **Lý do**: Chi phí bảo hiểm xã hội trích theo lương
- **Trạng thái**: Dự thảo

![fin_nganfin_nganquy_TM_NopBH_SinhPC](images/fin_nganfin_nganquy_TM_NopBH_SinhPC.png)

Nhấn **Xác nhận** để ghi nhận vào sổ chứng từ nộp bảo hiểm

![fin_nganfin_nganquy_TM_NopBH_PCXacnhan](images/fin_nganfin_nganquy_TM_NopBH_PCXacnhan.png)

Lưu ý: Muốn chuyển trạng thái từ Hoàn thành về Nháp thì Nhấn **Đưa về dự thảo**

### Thanh toán Nộp thuế

#### Mô tả nghiệp vụ

Thực hiện chi trả các khoản liên quan đến Thuế GTGT, Thuế TNCN, Thuế Tiêu thụ đặc biệt...phải nộp

#### *Xem video hướng dẫn*

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Module Ngân quỹ - Nộp thuế bằng tiền mặt" 
    src="https://www.youtube.com/embed/dvwFpmtpiAA?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>

#### Hướng dẫn trên phần mềm

**Bước 1**: Vào phân hệ **Ngân quỹ**, Chọn **Tiền mặt**, Chọn **Nộp thuế** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

Khai báo tab chung

- **Sổ nhật ký**: Chọn Tiền mặt
- **Ngày nộp thuế**: Nhập ngày nộp thuế

![fin_nganquy_TM_Nopthue_Tabchung](images/fin_nganquy_TM_Nopthue_Tabchung.png)

Khai báo tab chi tiết

- Số trả lần này: Nhập số tiền trả cho lần thanh toán

![fin_nganquy_TM_Nopthue_Tabchitiet](images/fin_nganquy_TM_Nopthue_Tabchitiet.png)

**Lưu ý**: Dữ liệu Tab chi tiết lấy tổng tiền dư Có - Dư nợ > 0 tính đến Ngày nộp bảo hiểm của tài khoản Phải trả thuế được tích chọn trong Danh mục Hệ thống tài khoản

Nhấn **Lưu**

![fin_nganquy_TM_Nopthue_Luu](images/fin_nganquy_TM_Nopthue_Luu.png)

**Bước 2**: Nhấn **Ghi nhận thanh toán**

![fin_nganquy_TM_Nopthue_ghinhanTT](images/fin_nganquy_TM_Nopthue_ghinhanTT.png)

Sinh bản ghi Phiếu chi tiền mặt với trạng thái **Dự thảo**

![fin_nganquy_TM_Nopthue_SinhPC](images/fin_nganquy_TM_Nopthue_SinhPC.png)

Nhấn **Xác nhận** để ghi sổ bút toán nộp thuế

![fin_nganquy_TM_Nopthue_SinhPC01-1](images/fin_nganquy_TM_Nopthue_SinhPC01-1.png)

### Thanh toán cho nhà cung cấp

#### Mô tả nghiệp vụ

Với những giao dịch chi trả đơn hàng cho nhà cung cấp bằng tiền mặt, người dùng thực hiện nghiệp vụ Chi trả tiền cho nhà cung cấp và nhập vào hệ thống để ghi nhận thông tin

#### *Xem video hướng dẫn*

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Module Ngân quỹ - Thanh toán cho nhà cung cấp bằng tiền mặt" 
    src="https://www.youtube.com/embed/CGYLfRXPUlM"
></iframe>


#### Hướng dẫn trên phần mềm

**Bước 1:** Tại phân hệ **Ngân quỹ**, Chọn **Tiền mặt**, Chọn **Thanh toán cho nhà cung cấp** (Hoặc thực hiện tìm kiếm trức tiếp chức năng trên ô tìm kiếm chung của hệ thống)

![fin_nganquy_TM_ThanhtoanNCC_Danhsach](images/fin_nganquy_TM_ThanhtoanNCC_Danhsach.png)

**Bước 2:** Tích chọn chứng từ khách hàng thanh toán tiền nợ: Nhấn **Ghi nhận thanh toán**

![fin_nganquy_TM_ThanhtoanNCC_GhinhanTT](images/fin_nganquy_TM_ThanhtoanNCC_GhinhanTT.png)

**Bước 3:** Trên thông tin Ghi nhận thanh toán Chọn/Nhập một số thông tin:

- Tại mục Sổ nhật ký: Chọn **Tiền mặt**

- Thực hiện chi trả số tiền đủ theo Hóa đơn hoặc chỉ chi trả một phần: Người dùng điều chỉnh thông tin tiền tại cột **'Số trả'**

![fin_nganquy_TM_ThanhtoanNCC_GhinhanTT01](images/fin_nganquy_TM_ThanhtoanNCC_GhinhanTT01.png)

**Bước 4:** Nhấn **Tạo Thanh toán** 

![fin_nganquy_TM_ThanhtoanNCC_GhinhanTT02](images/fin_nganquy_TM_ThanhtoanNCC_GhinhanTT02.png)

Hệ thống tạo phiếu chi tiền mặt với trạng thái **Đã vào sổ**

![fin_nganquy_TM_ThanhtoanNCC_GhinhanTT03](images/fin_nganquy_TM_ThanhtoanNCC_GhinhanTT03.png)

Nếu hóa đơn chưa được chi đủ thì cập nhật **Tình trạng thanh toán** là Đã trả 1 phần

![fin_nganquy_TM_ThanhtoanNCC_GhinhanTT04](images/fin_nganquy_TM_ThanhtoanNCC_GhinhanTT04.png)

## Kiểm kê tiền mặt

### Mô tả nghiệp vụ

Định kỳ theo quy định hoặc khi có phát sinh yêu cầu kiểm kê quỹ từ Ban lãnh đạo công ty, sẽ phát sinh một số hoạt động sau:

- Thành lập hội đồng kiểm kê gồm: Kế toán hoặc Giám đốc.
- Đếm thực tế số tiền mặt tồn quỹ theo từng loại tiền về mặt số lượng và mệnh giá.
- Đối chiếu số dư thực tế kiểm kê với sổ kế toán tiền mặt tại quỹ, nếu có sự chênh lệch thì thực hiện tìm nguyên nhân bằng cách đối chiếu sổ quỹ với sổ kế toán tiền mặt tìm ra những giao dịch thu, chi tiền mặt không khớp giữa 2 sổ.
- Sau khi tìm nguyên nhân thì Giám đốc hoặc Kế toán sẽ ra quyết định xử lý.

### *Xem video hướng dẫn*

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Module Ngân quỹ - Kiểm kê quỹ" 
    src="https://www.youtube.com/embed/40WQzopKh6g?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


### Hướng dẫn trên phần mềm

**Bước 1:** Vào phân hệ **Ngân quỹ**, Chọn **Tiền mặt**, Chọn **Kiểm kê tiền mặt** (Hoặc thực hiện Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống), Nhấn **Tạo**

![fin_nganquy_TM_KiemkeTM_Tao](images/fin_nganquy_TM_KiemkeTM_Tao.png)

**Bước 2:** Khai báo các thông tin **Kiểm kê tiền mặt**

- Tại mục **Đơn vị** : Chọn Đơn vị kiểm kê
- Tại mục **Kiểm kê đến ngày**: Chọn mốc thời gian muốn kiểm kê
- Tại mục **Sổ nhật ký**: Chọn Tiền mặt
- Tại mục **Tiền tệ**: Chọn Tiền tệ kiểm kê
- Tại mục **Ngày kiểm kê**: Chọn ngày thực hiện kiểm kê
- Tại **Mục đính**: Nhập mục đích kiểm kê

![fin_nganquy_TM_KiemkeTM_Tabchung](images/fin_nganquy_TM_KiemkeTM_Tabchung.png)



- Tại Tab **Kiểm kê** : Thực hiện nhập số lượng từng mệnh giá còn tồn trong Quỹ tại cột **Số lượng**

![fin_nganquy_TM_KiemkeTM_SLKK](images/fin_nganquy_TM_KiemkeTM_SLKK.png)

- Tại Tab **Xử lý chênh lệch** thực hiện nhập **Lý do** và **Xử lý chênh lệch** (Nếu có)

![fin_nganquy_TM_KiemkeTM_XulyCL](images/fin_nganquy_TM_KiemkeTM_XulyCL.png)

- Tại Tab **Thành viên tham gia**: Thực hiện chọn nhân viên tham gia kiểm kê

![TT88_KKQ03](images/fin_nganquy_TM_KiemkeTM_Thanhvienthamgia.PNG)

**Bước 3:** Nhấn **Xử lý chênh lệch**

- Căn cứ vào thực tế kiểm kê thừa hay thiếu, hệ thống tự động sinh ra Phiếu thu/Phiếu chi tương ứng. Cụ thể:
  - Trường hợp Số kiểm kê thực tế < Số dư trên sổ kế toán, hệ thống sẽ tự động sinh ra **Phiếu chi** để xử lý giá trị thừa.
  - Trường hợp Số kiểm kê thực tế > Số dư trên sổ kế toán, hệ thống sẽ tự động sinh ra **Phiếu thu** để xử lý giá trị thiếu.

## *Thanh toán lương cho nhân viên*

### Mô tả nghiệp vụ

**Nghiệp vụ**

Hàng tháng, sau khi Doanh nghiệp chốt thông tin lương sẽ thực hiện thanh toán tiền lương cho Nhân viên theo Bảng lương đã chốt.

Việc thanh toán được thực hiện thanh toán theo **Tiền mặt** hoặc **Tiền gửi**

### Xem video hướng dẫn

<iframe
    width="920"
    height="450"
    frameborder="0"
    allow="autoplay; encrypted-media; clipboard-write; gyroscope; picture-in-picture "
    allowfullscreen
    title="Module Ngân quỹ - Thanh toán lương cho nhân viên" 
    src="https://www.youtube.com/embed/ztlQnKkVOgg?list=PLcdARb5pnnj8jeyvyhaptnwL3sxxT_QaK"
></iframe>


### **Hướng dẫn trên phần mềm**

Đối tượng thực hiện: Người dùng phần mềm

**Bước 1**: Vào phân hệ **Ngân quỹ**, 

- Chọn **Tiền mặt**, chọn **Thanh toán lương cho nhân viên**: Nếu muốn chi trả lương bằng **Tiền mặt**

  ![](images/fin_nganquy_tienmat_Ttluong.png)

- Chọn **Tiền gửi**, chọn **Thanh toán lương cho nhân viên**: Nếu muốn chi trả lương bằng **Tiền gửi ngân hàng** 

  ![](images/fin_nganquy_tiengui_Ttluong.png)

**Bước 2**: Hệ thống hiển thị thông tin màn hình chức năng:

![](images/fin_nganquy_tiengui_tao.png)

Các trường dữ liệu trên chức năng:

- Bảng lương: Thỏa mãn là Bảng lương đã được Xác nhận hoàn thành. Trường hợp Bảng lương không có thông tin, Người dùng vào chức năng **Tổng hợp/Bảng lương/Bảng lương** để khai báo
- Thông tin Sổ nhật ký: Xác định Sổ nhật ký dùng để chi trả và lên các bút toán chi tiền lương cho nhân viên.

**Bước 3**: Thực hiện chọn và Nhập thông tin dữ liệu

- Chọn Bảng lương:

**Trường hợp:** Bảng lương được khai báo Không hạch toán theo đối tượng (Tức thông tin **Hạch toán theo đối tượng** ***<u>không được tích chọn</u>***): Trên giao diện chỉ hiển thị thông tin Tổng tiền để người dùng nhập và Thanh toán theo tổng, không lên bút toán theo từng đối tượng

![](images/fin_nganquy_tiengui_tao_khaibao-16596125206821.png)

**Trường hợp**:  Bảng lương được khai báo Hạch toán theo đối tượng (Tức thông tin **Hạch toán theo đối tượng** ***<u>được tích chọn</u>***): Trên giao diện hiển thị mặc định thông tin Nhân viên cùng Số tiền lương nhận được đã được khai báo bên Bảng lương

![](images/fin_nganquy_tiengui_tao_khaibao_TheoDoituon-16596125206842.png)

- Thông tin **Tổng số tiền phải trả**: Là thông tin Số tiền của Bảng lương còn phải trả. Nếu là lần chi trả ban đầu thông tin 'Tổng tiền phải trả' chính là thông tin Tiền của Bảng lương. Với lần trả tiếp theo: Số tiền phải trả là giá trị còn lại của Bảng lương sau khi đã thanh toán lương lần đầu
- Thông tin **Tổng tiền trả lần này**: Ghi nhận Số tiền sẽ thanh toán cho lần chi trả lương đang thực hiện
  - Với Bảng lương thanh toán không theo đối tượng thì Tổng tiền trả lần này = Số tiền được nhập thanh toán tại trường **'Số tiền'**
  - Với Bảng lương thanh toán theo Đối tượng thì Tổng tiền trả lần này = **Tổng giá trị tại cột 'Số tiền thanh toán'** của nhân viên (Thông tin cột **'Số tiền thanh toán'** ứng với từng nhân viên có thể **Sửa đổi**)

![](images/fin_nganquy_tiengui_tao_nhapthongtin_tong-16596125206843.png)

![](images/fin_nganquy_tiengui_tao_nhapthongtin-16596125206844.png)

<u>***Lưu ý:***</u> Hệ thống sẽ báo lỗi khi 'Tổng tiền trả lần này' vượt quá 'Tổng tiền phải trả' và Báo lỗi khi Số tiền còn lại trong Sổ nhật ký không đủ để thanh toán khoản tiền phải chi trả

**Bước 4**: Người dùng Nhấn nút **Xác nhận** để ghi nhận thanh toán lương theo dữ liệu đã nhập.

**Trường hợp: Thanh toán theo Số tổng**

![](images/fin_nganquy_tiengui_tao_nhapthongtin_XacNhan-16596125206855.png)

==> Sau khi Xác nhận thanh toán Hệ thống tạo 1 Phiếu chi lương tương ứng theo hình thức chi trả lương bằng **Tiền mặt hay Tiền gửi ngân hàng**

![](images/fin_nganquy_tiengui_tao_nhapthongtin_tong_xacnhan-16596125206856.png)

**Trường hợp thanh toán theo Đối tượng**

![](images/fin_nganquy_tiengui_tao_nhapthongtin_doituong_xacnhan-16596125206857.png)

==> Hệ thống tự động tạo ra các phiếu chi lương với các bút toán tương ứng với từng đối tượng

![](images/fin_nganquy_tiengui_tao_danhsachbuttoan-16596125206858.png)

Thông tin chi tiết của Phiếu chi thanh toán lương

![](images/fin_nganquy_tiengui_tao_danhsachbuttoan_chiTiet-16596125206859.png)

***Lưu ý:*** Với các Bảng lương đã được thanh toán Chi trả, hệ thống thể hiện thông tin Số lượng Phiếu chi tương ứng đã được thanh toán của Bảng lương

![](images/fin_nganquy_tiengui_bangluong-165961252068510.png)

## Dự báo dòng tiền

### Hướng dẫn trên phần mềm

**Bước 1**: Vào phân hệ **Ngân quỹ**, 

- Chọn **Tiền mặt**, chọn **Dự báo dòng tiền**: Nếu muốn theo dõi dòng **Tiền mặt**

  ![](images/fin_tienmat_Dubaodongtien_01.png)

- Chọn **Tiền gửi**, chọn **Dự báo dòng tiền**: Nếu muốn thoe dõi dòng **Tiền gửi ngân hàng** 

![](images/fin_tiengui_Dubaodongtien_01.png)

**Bước 2**: Hệ thống hiển thị màn hình danh sách các bản ghi dự bảo dòng tiền:

![](images/fin_tienmat_Dubaodongtien_02.png)

**Bước 3:**  Nhấn **Tạo** để thêm bản ghi

![](images/fin_tienmat_Dubaodongtien_tao.png)

**Bước 2:** Khai báo các thông tin tab chung 

- Tại mục **Đơn vị**: Thực hiện chọn **Đơn vị** để theo dõi dòng tiền
- Tại mục **Đến ngày**: Chọn ngày.

![](images/fin_tienmat_Dubaodongtien_03.png)

Tab Chi tiết: Hệ thống sẽ tự lấy lên các dòng liệt kê đủ các thông tin Thu Chi dự kiến trong tương lại đến thời điểm được chọn tại trường **Đến ngày** 

![](images/fin_tienmat_Dubaodongtien_04.png)

