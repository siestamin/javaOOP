# javaOOP
ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 1: QUẢN LÝ MƯỢN SÁCH THƯ VIỆN
Thông tin về Sách gồm các thuộc tính (mã sách, Tên sách, Tác giả, Chuyên ngành, Năm xuất bản,
Số lượng) – trong đó Chuyên ngành có thể là: Khoa học tự nhiên, Văn học – Nghệ thuật, Điện tử
Viễn thông, Công nghệ thông tin. Mã sách là một số nguyên có 5 chữ số, tự động tăng.
Thông tin về Bạn đọc (mã bạn đọc, Họ tên, địa chỉ, Số ĐT), mã bạn đọc là một số nguyên có 5 chữ
số, tự động tăng.
Bổ sung Bảng QL Mượn sách trong đó một bạn đọc sẽ được phép mượn không quá 5 đầu sách khác
nhau, mỗi đầu sách không mượn quá 3 cuốn. Ghi rõ tình trạng hiện thời của sách khi cho mượn.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm đầu sách mới vào file SACH.DAT. Có xử lý ngoại lệ. In ra danh sách các đầu
sách đã có trong file.
2. Nhập thêm bạn đọc vào file BD.DAT. Có xử lý ngoại lệ. In ra danh sách bạn đọc đã có trong
file.
3. Lập Bảng QL mượn sách cho từng bạn đọc bằng cách nhập các đầu sách mà bạn đọc mượn,
lưu vào file QLMS.DAT và in danh sách ra màn hình (chú ý: cùng một loại bạn đọc với một
đầu sách thì không thể xuất hiện 2 lần trong bảng này).
4. Sắp xếp danh sách Quản lý mượn sách đã lưu trong QLMS.DAT
a. Theo tên bạn đọc
b. Theo Số lượng cuốn sách được mượn (giảm dần)
5. Tìm kiếm và hiển thị danh sách mượn sách theo tên bạn đọcĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 2: QUẢN LÝ ĐĂNG KÝ HỌC THEO TÍN CHỈ
Thông tin về Môn học gồm các thuộc tính (mã môn học, Tên môn, Tổng số tiết, Loại môn học) –
trong đó Loại môn học có thể là: Đại cương, Cơ sở ngành, Chuyên ngành bắt buộc, Chuyên ngành tự
chọn. Mã môn học là một số nguyên có 3 chữ số, tự động tăng.
Thông tin về Sinh viên (mã sinh viên, Họ tên, địa chỉ, Số ĐT), mã sinh viên là một số nguyên có 5
chữ số, tự động tăng.
Bổ sung Bảng Đăng ký trong đó một sinh viên sẽ được phép đăng ký không quá 8 môn học một học
kỳ. Ghi rõ thời gian đăng ký của sinh viên.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm môn học mới vào file MH.DAT. Có xử lý ngoại lệ. In ra danh sách các môn học
đã có trong file.
2. Nhập thêm sinh viên vào file SV.DAT. Có xử lý ngoại lệ. In ra danh sách sinh viên đã có
trong file.
3. Lập Bảng Đăng ký cho từng sinh viên bằng cách nhập các môn học cho sinh viên đó và thời
gian đăng ký (lấy từ thời gian hệ thống), lưu vào file QLDK.DAT và in danh sách ra màn
hình (chú ý: cùng một sinh viên với một môn học thì không thể xuất hiện 2 lần trong bảng
này).
4. Sắp xếp danh sách Bảng đăng ký đã lưu trong QLDK.DAT
a. Theo tên sinh viên
b. Theo thời gian đăng ký
5. Lập danh sách lớp học theo danh sách đăng ký. Mỗi lớp không quá 30 sinh viên và lấy theo
thứ tự thời gian đăng ký.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 3: QUẢN LÝ BÁN HÀNG TRONG SIÊU THỊ
Thông tin về Mặt hàng gồm các thuộc tính (mã hàng, Tên hàng, Nhóm hàng, Giá bán) – trong đó
Nhóm hàng có thể là: Hàng thời trang, Hàng tiêu dùng, Hàng điện máy, Hàng gia dụng. Mã hàng là
một số nguyên có 4 chữ số, tự động tăng.
Thông tin về Khách hàng (mã KH, Họ tên, địa chỉ, Số ĐT), mã KH là một số nguyên có 5 chữ số,
tự động tăng.
Bổ sung Bảng Danh sách mua hàng trong đó với mỗi khách hàng, nhập danh sách các mặt hàng và
số lượng mà khách hàng đó mua. Giả sử mỗi khách hàng không mua quá 10 loại mặt hàng một lần.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm mặt hàng mới vào file MH.DAT. Có xử lý ngoại lệ. In ra danh sách các mặt hàng
đã có trong file.
2. Nhập thêm khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách khách hàng đã
có trong file.
3. Lập Bảng danh sách mua hàng cho từng khách hàng, lưu vào file QLBH.DAT và in danh
sách ra màn hình (chú ý: cùng một khách hàng với một mặt hàng thì không thể xuất hiện 2
lần trong bảng này).
4. Sắp xếp danh sách Bảng danh sách mua hàng đã lưu trong QLBH.DAT
a. Theo tên khách hàng
b. Theo tên mặt hàng
5. Lập hóa đơn cho mỗi khách hàng.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 4: QUẢN LÝ BÁN HÀNG TRONG SIÊU THỊ ĐIỆN MÁY
Thông tin về Mặt hàng trong kho gồm các thuộc tính (mã hàng, Tên hàng, Nhóm hàng, Giá bán,
Số lượng) – trong đó Nhóm hàng có thể là: Điện tử, Điện lạnh, Máy tính, Thiết bị văn phòng. Mã
hàng là một số nguyên có 4 chữ số, tự động tăng.
Thông tin về Nhân viên bán hàng (mã NV, Họ tên, địa chỉ, Số ĐT), mã NV là một số nguyên có 4
chữ số, tự động tăng.
Bổ sung Bảng Danh sách bán hàng (trong một ngày) trong đó với mỗi nhân viên, nhập danh sách
các mặt hàng mà nhân viên đó đã bán được. Giả sử mỗi nhân viên chỉ tham gia bán tối đa 5 mặt hàng
khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm mặt hàng mới vào file MH.DAT. Có xử lý ngoại lệ. In ra danh sách các mặt hàng
đã có trong file.
2. Nhập thêm nhân viên vào file NV.DAT. Có xử lý ngoại lệ. In ra danh sách nhân viên đã có
trong file.
3. Lập Bảng danh sách bán hàng cho từng nhân viên, lưu vào file QLBH.DAT và in danh sách
ra màn hình (chú ý: cùng một nhân viên với một mặt hàng thì không thể xuất hiện 2 lần trong
bảng này).
4. Sắp xếp danh sách Bảng danh sách bán hàng đã lưu trong QLBH.DAT
a. Theo tên nhân viên
b. Theo nhóm mặt hàng
5. Lập bảng kê doanh thu cho mỗi nhân viên.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 5: QUẢN LÝ NHÂN SỰ
Thông tin về Nhân viên gồm các thuộc tính (mã nhân viên, Họ tên, Địa chỉ, Số điện thoại, Bậc
lương) – trong đó Bậc lương là một số nguyên từ 1 đến 9. Mã nhân viên là một số nguyên có 4 chữ
số, tự động tăng.
Thông tin về Phòng ban (mã phòng, tên phòng, mô tả, Hệ số công việc), mã phòng là một số
nguyên có 3 chữ số, tự động tăng. Hệ số công việc là một số thực từ trong khoảng từ 1 đến 20, cho
biết mức đánh giá chung về các công việc thuộc phòng đó đảm nhiệm.
Bổ sung Bảng Danh sách chấm công (trong một tháng), trong đó với mỗi nhân viên cho biết phòng
ban tương ứng và số ngày làm việc trong tháng.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm nhân viên mới vào file NV.DAT. Có xử lý ngoại lệ. In ra danh sách các nhân viên
đã có trong file.
2. Nhập thêm phòng ban vào file PB.DAT. Có xử lý ngoại lệ. In ra danh sách phòng ban đã có
trong file.
3. Lập Bảng danh sách chấm công cho từng nhân viên, lưu vào file QLNS.DAT và in danh sách
ra màn hình (chú ý: cùng một nhân viên không thể làm việc ở hai phòng ban khác nhau).
4. Sắp xếp danh sách Bảng danh sách phân công đã lưu trong QLNS.DAT
a. Theo tên nhân viên
b. Theo phòng ban
5. Lập bảng kê thu nhập cho mỗi nhân viên trong tháng. Thu nhập = 850000*(2 + Bậc
lương/3)*Hệ số công việc * (số ngày làm việc/22).ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 6: QUẢN LÝ THIẾT BỊ TRONG PHÒNG HỌC
Thông tin về Thiết bị gồm các thuộc tính (mã TB, Tên, Xuất xứ, Năm sản xuất) – trong đó Xuất xứ
có thể là: Nhập khẩu, Nội địa, Liên doanh. Mã TB là một số nguyên có 5 chữ số, tự động tăng.
Thông tin về Phòng học (mã PH, tên phòng, số ghế), mã PH là một số nguyên có 5 chữ số, tự
động tăng.
Bổ sung Bảng QL Thiết bị trong đó một phòng học sẽ được nhận nhiều loại thiết bị, mỗi loại có số
lượng khác nhau và ghi rõ tình trạng hiện thời.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm thiết bị vào file TB.DAT. Có xử lý ngoại lệ. In ra danh sách thiết bị đã có trong
file.
2. Nhập thêm phòng học vào file PH.DAT. Có xử lý ngoại lệ. In ra danh sách phòng học đã có
trong file.
3. Lập Bảng QL Thiết bị cho các phòng học bằng cách nhập các loại thiết bị cho mỗi phòng
cùng số lượng và tình trạng tương ứng tương ứng; lưu vào file QLTB.DAT và in danh sách
ra màn hình (chú ý: cùng một loại thiết bị trong một phòng học thì không thể xuất hiện 2 lần).
4. Sắp xếp danh sách Quản lý thiết bị đã lưu trong QLTB.DAT
a. Theo tên phòng học
b. Theo Số lượng thiết bị mỗi loại (giảm dần)
5. Tìm kiếm và hiển thị danh sách thiết bị trong các phòng theo tên thiết bịĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 7: QUẢN LÝ DỰ ÁN
Thông tin về Dự án gồm các thuộc tính (mã dự án, Tên dự án, Kiểu dự án, Tổng kinh phí) – trong
đó kiểu dự án có thể gồm: nhỏ, trung bình hoặc lớn. Mã dự án là một số nguyên có 5 chữ số, tự động
tăng.
Thông tin về Nhân viên (mã NV, Họ tên, địa chỉ, chuyên môn), mã NV là một số nguyên có 5 chữ
số, tự động tăng.
Bổ sung Bảng phân công trong đó một nhân viên có thể được gán cho một hoặc nhiều dự án một lúc
với số ngày tham gia khác nhau và vị trí công việc khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm dự án vào file DA.DAT. Có xử lý ngoại lệ. In ra danh sách dự án đã có trong file.
2. Nhập thêm nhân viên vào file NV.DAT. Có xử lý ngoại lệ. In ra danh sách nhân viên đã có
trong file.
3. Nhập danh sách phân công dự án cho mỗi nhân viên đã có trong file NV.DAT. Lưu vào file
PHANCONG.DAT và in danh sách ra màn hình. (chú ý: cùng một nhân viên thì không thể
tham gia cùng một dự án với hai vị trí khác nhau nhưng có thể tham gia cùng lúc vào nhiều
dự án)
4. Sắp xếp danh sách phân công đã lưu trong PHANCONG.DAT
a. Theo Họ tên nhân viên
b. Theo Số ngày tham gia (giảm dần)
5. Tìm kiếm và hiển thị danh sách phân công theo tên nhân viênĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 8: QUẢN LÝ SẮP XẾP PHÒNG HỌC
Thông tin về Phòng học gồm các thuộc tính (mã phòng, Tên phòng, Số ghế, Kiểu phòng) – với kiểu
phòng có thế là: phòng hội thảo, phòng thực hành và phòng giảng lý thuyết, mã phòng là một số
nguyên có 5 chữ số, tự động tăng.
Thông tin về Lớp (mã lớp, tên lớp, số sinh viên), mã lớp là một số nguyên có 3 chữ số, tự động tăng.
Bổ sung Bảng sắp xếp trong đó một lớp được sắp xếp tại một hoặc nhiều phòng học tương ứng với
các kíp học khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm Phòng học vào file PH.DAT. Có xử lý ngoại lệ. In ra danh sách phòng học đã có
trong file.
2. Nhập thêm Lớp vào file LOP.DAT. Có xử lý ngoại lệ. In ra danh sách các lớp đã có trong
file.
3. Nhập danh sách sắp xếp phòng học cho mỗi lớp đã có trong fie LOP.DAT; lưu vào file
BANGSX.DAT và in danh sách ra màn hình. (Chú ý: các lớp không thể xếp vào phòng có số
ghế ít hơn số sinh viên của lớp)
4. Sắp xếp danh sách sắp xếp phòng học đã lưu trong BANGSX.DAT
a. Theo tên lớp học
b. Theo Kíp học
5. Tìm kiếm và hiển thị danh sách sắp xếp theo phòng họcĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 9: QUẢN LÝ TRẢ LƯƠNG CHO GIẢNG VIÊN THỈNH GIẢNG
Một trường đại học trả lương cho giáo viên thỉnh giảng theo môn học và giờ giảng dạy.
Thông tin về Môn học gồm các thuộc tính (mã môn học, Tên môn, Tổng số tiết, Số tiết lý thuyết,
mức kinh phí) – trong đó mức kinh phí là mức trả cho một tiết dạy lý thuyết, tiết thực hành sẽ được
trả bằng 70% tiết lý thuyết. Mã môn học là một số nguyên có 3 chữ số, tự động tăng.
Thông tin về Giảng viên (mã GV, Họ và tên, địa chỉ, trình độ), mã GV là một số nguyên có 3 chữ
số, tự động tăng. Trình độ bao gồm: GS-TS, PGS-TS, Giảng viên chính, Th.S.
Bổ sung Bảng Kê khai giảng dạy trong đó một giảng viên sẽ khai báo giảng dạy môn nào và bao
nhiêu lớp. Chú ý: một giảng viên có thể dạy nhiều môn. Số lớp cho mỗi môn là số nguyên dương và
không lớn hơn 3. Tổng số tiết giảng dạy của một giảng viên không được lớn hơn 200.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm môn học vào file MB.DAT. Có xử lý ngoại lệ. In ra danh sách môn học đã có
trong file.
2. Nhập thêm giảng viên vào file GV.DAT. Có xử lý ngoại lệ. In ra danh sách GV đã có trong
file.
3. Lập Bảng kê khai giảng dạy cho mỗi giảng viên; lưu vào file QLGV.DAT và in danh sách ra
màn hình.
4. Sắp xếp danh sách kê khai giảng dạy đã lưu trong QLGV.DAT
a. Theo họ tên giảng viên
b. Theo số tiết giảng dạy mỗi môn (giảm dần)
5. Tính toán và lập bảng tính tiền công cho mỗi giảng viên.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 10: QUẢN LÝ PHÂN CHIA TIỀN THƯỞNG CHO CẦU THỦ BÓNG ĐÁ
Sau khi giành chức vô địch, một đội bóng đá tính tiền thưởng cho mỗi cầu thủ dựa trên vị trí thi đấu và
số trận đã đấu.
Thông tin về Cầu thủ gồm các thuộc tính (mã cầu thủ, Họ Tên, Tuổi, Mức lương) – trong đó mức
lương là giá trị đã ký theo hợp đồng. Mã cầu thủ là một số nguyên có 3 chữ số, tự động tăng.
Thông tin về Vị trí thi đấu (mã vị trí, Tên vị trí, mức thưởng), mã vị trí là một số nguyên có 3 chữ
số, tự động tăng.
Bổ sung Bảng phân công trong đó một cầu thủ có thể được gán cho một hoặc nhiều vị trí một lúc với
số trận chơi ở vị trí đó. Chú ý, một cầu thủ không được chơi quá 3 vị trí khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm cầu thủ vào file CT.DAT. Có xử lý ngoại lệ. In ra danh sách cầu thủ đã có trong
file.
2. Nhập thêm vị trí thi đấu vào file VITRI.DAT. Có xử lý ngoại lệ. In ra danh sách vị trí đã có
trong file.
3. Nhập danh sách phân công cho mỗi cầu thủ đã có trong file CT.DAT. Lưu vào file
PCCT.DAT và in danh sách ra màn hình.
4. Sắp xếp danh sách phân công đã lưu trong PCCT.DAT
a. Theo Họ tên cầu thủ
b. Theo Số trận chơi ở một vị trí (giảm dần)
5. Tính tổng tiền thưởng của các cầu thủ và in ra màn hình (tổng tiền thưởng bằng tiền thưởng
theo vị trí trong tất cả các trận đấu + 10% mức lương)ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 11: QUẢN LÝ PHÒNG KHÁCH SẠN
Một khách sạn phân cấp các phòng theo nhiều loại và dựa trên thời gian thuê của từng khách để lập
hóa đơn tiền phòng.
Thông tin về Phòng gồm các thuộc tính (mã kiểu phòng, Kiểu phòng, Mức tiền thuê, Số phòng) –
với kiểu phòng có thế là: phòng đơn, phòng đôi và phòng VIP, mã phòng là một số nguyên có 3 chữ
số, tự động tăng.
Thông tin về Khách hàng (mã khách hàng, tên khách hàng, loại phòng cần thuê, số phòng cần
thuê), mã khách hàng là một số nguyên có 3 chữ số, tự động tăng.
Bổ sung Bảng sắp xếp trong đó một khách hàng được sắp xếp tại loại phòng phù hợp (nếu thiếu thì đề
nghị loại phòng khác) cùng với số lượng phòng loại đó và số ngày thuê.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm Phòng vào file PH.DAT. Có xử lý ngoại lệ. In ra danh sách phòng đã có trong file.
2. Nhập thêm Khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách các KH đã có
trong file.
3. Nhập danh sách sắp xếp phòng cho mỗi khách hàng đã có trong fie KH.DAT; lưu vào file
BANGSX.DAT và in danh sách ra màn hình. Chú ý kiểm tra số phòng còn lại mỗi kiểu.
4. Sắp xếp danh sách đã lưu trong BANGSX.DAT
a. Theo loại phòng
b. Theo số phòng cần thuê
5. Tính toán và lập hóa đơn cho mỗi khách hàng.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 12: QUẢN LÝ TÍNH CÔNG THEO SẢN PHẨM
Thông tin về Công nhân gồm các thuộc tính (mã CN, Họ tên, Địa chỉ, Ca sản xuất) – trong đó ca
sản xuất có thể là: ca sáng, ca chiều hoặc ca đêm, mã CN là một số nguyên có 5 chữ số, tự động
tăng.
Thông tin về Sản phẩm (mã SP, tên SP, đơn giá), mã SP là một số nguyên có 5 chữ số, tự động
tăng.
Bổ sung Bảng Tính Công trong đó một công nhân sẽ thực hiện sản xuất nhiều sản phẩm cùng loại
hoặc nhiều loại sản phẩm khác nhau. Giả sử mỗi công nhân chỉ được tham gia sản xuất tối đa 5 loại
sản phẩm khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm công nhân vào file CN.DAT. Có xử lý ngoại lệ. In ra danh sách công nhân đã có
trong file.
2. Nhập thêm sản phẩm vào file SP.DAT. Có xử lý ngoại lệ. In ra danh sách sản phẩm đã có
trong file.
3. Lập Bảng tính công cho công nhân bằng cách nhập các loại sản phẩm mà mỗi công nhân đã
có trong file CN.DAT đã sản xuất cùng số lượng tương ứng; lưu vào file TINHCONG.DAT
và in danh sách ra màn hình. (Chú ý: một công nhân với cùng một loại sản phẩm không được
phép xuất hiện quá một lần trong bảng này)
4. Sắp xếp danh sách Bảng tính công đã lưu trong TINHCONG.DAT
c. Theo Họ tên Công nhân
d. Theo Số lượng sản phẩm (giảm dần)
5. Lập bảng kê thu nhập của mỗi công nhânĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 13: QUẢN LÝ BÁN HÀNG
Thông tin về Khách hàng gồm các thuộc tính (mã KH, Họ tên, Địa chỉ, Nhóm KH) – trong đó nhóm
khách hàng có thể gồm: mua lẻ, mua buôn, mua qua mạng, mã KH là một số nguyên có 5 chữ số, tự
động tăng.
Thông tin về Mặt hàng (mã hàng, tên hàng, đơn giá), mã hàng là một số nguyên có 5 chữ số, tự
động tăng.
Bổ sung Hóa đơn trong đó một khách hàng có thể chọn mua một hoặc nhiều mặt hàng với số lượng
khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm Khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách khách hàng đã
có trong file.
2. Nhập thêm Mặt hàng vào file MATHANG.DAT. Có xử lý ngoại lệ. In ra danh sách mặt
hàng đã có trong file.
3. Nhập danh sách mua hàng cho mỗi khách hàng đã có trong file KH.DAT. Lưu vào file
HOADON.DAT và in danh sách ra màn hình .
4. Sắp xếp danh sách mua hàng đã lưu trong HOADON.DAT
a. Theo Họ tên khách hàng
b. Theo Số lượng mặt hàng (giảm dần)
5. Lập bảng kê tổng số tiền phải trả cho mỗi khách hàngĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 14: QUẢN LÝ PHÂN CÔNG LÁI XE BUÝT
Thông tin về Lái xe gồm các thuộc tính (mã LX, Họ tên, Địa chỉ, Trình độ) – với quy định trình độ
lái xe được chọn trong các mức từ Loại A đến Loại F, mã LX là một số nguyên có 5 chữ số, tự động
tăng.
Thông tin về Tuyến (mã tuyến, khoảng cách, số điểm dừng), mã tuyến là một số nguyên có 3 chữ số,
tự động tăng.
Bổ sung Bảng phân công trong đó một lái xe trong một ngày được phân công lái xe trên một hoặc
nhiều tuyến, với mỗi tuyến cần cho biết lái xe đó sẽ lái bao nhiêu lượt. Giả sử tổng số lượt trong ngày
của lái xe không vượt quá 15.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm Lái xe vào file LX.DAT. Có xử lý ngoại lệ. In ra danh sách lái xe đã có trong file.
2. Nhập thêm Tuyến vào file TUYEN.DAT. Có xử lý ngoại lệ. In ra danh sách các tuyến đã có
trong file.
3. Nhập danh sách phân công cho mỗi lái xe đã có trong file LX.DAT; lưu vào file
PHANCONG.DAT và in danh sách ra màn hình . (Chú ý: cùng một lái xe với một tuyến
không được xuất hiện quá một lần trong bảng này)
4. Sắp xếp danh sách phân công đã lưu trong PHANCONG.DAT
a. Theo Họ tên lái xe
b. Theo Số lượng tuyến đảm nhận trong ngày (giảm dần)
5. Lập bảng kê tổng khoảng cách chạy xe trong ngày của mỗi lái xeĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 15: QUẢN LÝ DỊCH VỤ VIỄN THÔNG
Thông tin về Khách hàng gồm các thuộc tính (mã KH, Họ tên, Địa chỉ, Loại KH) – với Loại khách
hàng có thể là: cá nhân, đại diện đơn vị hành chính, đại diện đơn vị kinh doanh, mã KH là một số
nguyên có 5 chữ số, tự động tăng.
Thông tin về Dịch vụ (mã DV, tên DV, giá cước, đơn vị tính) mã DV là một số nguyên có 3 chữ số,
tự động tăng.
Bổ sung Hóa đơn trong đó một khách hàng có thể sử dụng một hoặc nhiều dịch vụ. Giả sử mỗi
khách được phép sử dụng không quá 5 loại dịch vụ khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách khách hàng đã
có trong file.
2. Nhập thêm dịch vụ vào file DV.DAT. Có xử lý ngoại lệ. In ra danh sách dịch vụ đã có trong
file.
3. Nhập hóa đơn cho mỗi khách hàng đã có trong file KH.DAT, trong đó mỗi khách hàng ứng
với một dịch vụ sử dụng sẽ có số lượng sử dụng (theo đơn vị tính); lưu vào file
HOADON.DAT và in danh sách ra màn hình. (Chú ý: cùng một khách hàng với một loại dịch
vụ thì không được xuất hiện quá một lần trong bảng này)
4. Sắp xếp danh sách hóa đơn đã lưu trong HOADON.DAT
a. Theo Họ tên khách hàng
b. Theo Số lượng sử dụng (giảm dần)
5. Lập bảng kê số tiền phải trả cho mỗi khách hàngĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 16: QUẢN LÝ BÁN VÉ TÀU HỎA
Thông tin về Người mua vé gồm các thuộc tính (Mã người mua, Họ tên, Địa chỉ, Loại) – trong đó
nhóm người mua có thể là: mua lẻ, mua tập thể, mua qua mạng, mã người mua là một số nguyên có 5
chữ số, tự động tăng.
Thông tin về Vé tàu (mã vé, loại ghế, đơn giá), mã vé là một số nguyên có 5 chữ số, tự động tăng.
Bổ sung Hóa đơn, trong đó một người mua có thể một mua một hoặc nhiều vé.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm người mua vé vào file NGUOIMUA.DAT. Có xử lý ngoại lệ. In ra danh sách
người mua đã có trong file.
2. Nhập thêm loại vé vào file VE.DAT. Có xử lý ngoại lệ. In ra danh sách các loại vé đã có
trong file.
3. Nhập danh sách hóa đơn mua vé cho mỗi người mua đã có trong file NGUOIMUA.DAT;
(giả sử mỗi người mua có thể mua một hoặc nhiều loại vé nhưng không quá 4 loại, mỗi loại
có một số lượng xác định nhưng không quá 20). Lưu vào file HOADON.DAT và in danh
sách ra màn hình.
4. Sắp xếp danh sách hóa đơn đã lưu trong HOADON.DAT
a. Theo Họ tên người mua
b. Theo Số lượng vé mua (giảm dần)
5. Lập bảng kê số tiền phải tra cho mỗi người muaĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 17: QUẢN LÝ DANH SÁCH SỔ TIẾT KIỆM
Thông tin về Khách hàng gồm các thuộc tính (mã KH, Họ tên, Địa chỉ, Loại KH) - với loại
khách hàng có thể là: cá nhân, tập thể, doanh nghiệp, mã KH là một số nguyên có 5 chữ số, tự
động tăng.
Thông tin về Ngân hàng (mã NH, tên NH, lãi suất tiền gửi), mã NH là một số nguyên có 3 chữ
số, tự động tăng.
Bổ sung Số tiết kiệm trong đó một khách hàng có thể lập một hoặc nhiều số tiết kiệm với một
hoặc nhiều ngân hàng.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách khách hàng đã
có trong file.
2. Nhập thêm ngân hàng vào file NGANHANG.DAT. Có xử lý ngoại lệ. In ra danh sách ngân
hàng đã có trong file.
3. Nhập danh sách Sổ tiết kiệm cho mỗi khách hàng đã có trong file KH.DAT; (mỗi khách hàng
với một ngân hàng có thể có nhiều sổ khác nhau nhưng không quá 5 sổ, mỗi sổ sẽ có số tiền
gửi tương ứng), lưu danh sách vào file SOTK.DAT và in ra màn hình.
4. Sắp xếp danh sách Sổ tiết kiệm đã lưu trong SOTK.DAT
a. Theo Họ tên khách hàng
b. Theo Tên Số tiền gửi
5. Lập bảng kê tổng số tiền gửi cho mỗi khách hàngĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 18: QUẢN LÝ ĐIỂM SINH VIÊN
Thông tin về Sinh viên gồm (mã SV, Họ tên, Địa chỉ, Ngày sinh, Lớp). Trong đó mã sinh viên
là một số nguyên có 5 chữ số, tự động tăng. Lớp được chọn từ danh sách các lớp theo các đặt
tên tại HV CN BCVT.
Thông tin về Môn học (mã môn, tên môn, số đvht, loại môn). Trong đó, mã môn là một số
nguyên có 3 chữ số, tự động tăng. Loại môn học có thể là Đại cương, Cơ sở ngành, Chuyên
ngành.
Bổ sung Bảng điểm trong đó một sinh viên có một điểm cho mỗi môn học (0<=điếm<=10).
Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame (có thể dùng kéo thả) thực
hiện các chức năng sau:
1. Nhập thêm sinh viên vào file SV.DAT. Có xử lý ngoại lệ. In ra danh sách sinh viên đã có
trong file.
2. Nhập thêm môn học vào file MONHOC.DAT. Có xử lý ngoại lệ. In ra danh sách môn học
đã có trong file.
3. Nhập điểm cho mỗi sinh viên đã có trong file SV.DAT; lưu vào file BANGDIEM.DAT và in
danh sách ra màn hình. (Chú ý: mỗi sinh viên với một môn học chỉ được xuất hiện một lần
trong bảng này)
4. Sắp xếp danh sách Bảng điểm đã lưu trong BANGDIEM.DAT
a. Theo Họ tên sinh viên
b. Theo Tên Môn học
5. Tính điểm tổng kết chung cho mỗi sinh viên dựa trên điểm môn học và số đơn vị học trình
của môn học đó.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 19: QUẢN LÝ HỒ SƠ SINH VIÊN KÝ TÚC XÁ
Thông tin về Sinh viên gồm (mã SV, Họ tên, Địa chỉ, Ngày sinh, Lớp). Trong đó mã sinh viên
là một số nguyên có 5 chữ số, tự động tăng. Lớp được chọn từ danh sách các lớp theo các đặt
tên tại HV CN BCVT.
Thông tin về Phòng (mã phòng, tên phòng, loại phòng). Trong đó, mã phòng là một số nguyên
có 3 chữ số, tự động tăng. Loại phòng có thể là Phòng VIP, Chất lượng cao, Thường.
Bổ sung Danh sách sinh viên ký túc xá trong đó mỗi sinh viên cho biết đang ở phòng nào. Mỗi
phòng không quá 8 sinh viên.
Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame (có thể dùng kéo thả) thực
hiện các chức năng sau:
1. Nhập thêm sinh viên vào file SV.DAT. Có xử lý ngoại lệ. In ra danh sách sinh viên đã có
trong file.
2. Nhập thêm phòng vào file PHONG.DAT. Có xử lý ngoại lệ. In ra danh sách các phòng đã có
trong file.
3. Nhập danh sách sinh viên ký túc xá lưu vào file DSKTX.DAT. Mỗi sinh viên cho biết bắt
đầu ở ký túc xá từ ngày nào. Chú ý: một sinh viên có thể ở nhiều phòng khác nhau.
4. Sắp xếp danh sách sinh viên ký túc xá đã lưu trong DSKTX.DAT
a. Theo Họ tên sinh viên
b. Theo Tên phòng
5. Giả sử mức tiền thuê phòng hàng tháng theo thứ tự loại phòng lần lượt là 1000, 500 và 300
(nghìn đồng). Tính tiền thuê đến thời điểm hiện tại cho mỗi sinh viên (chú ý làm tròn tháng).ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 20: QUẢN LÝ NHÀ CHO THUÊ
Thông tin về Khách hàng gồm (mã KH, Tên khách hàng, Địa chỉ, SDT, Loại KH). Trong đó
mã khách hàng là một số nguyên có 5 chữ số, tự động tăng. Loại khách hàng được chọn từ
danh sách gồm: Sinh viên, Hộ gia đình, Doanh nghiệp.
Thông tin về Phòng (mã phòng, tên phòng, loại phòng). Trong đó, mã phòng là một số nguyên
có 3 chữ số, tự động tăng. Loại phòng có thể là Phòng VIP, Phòng chất lượng cao, Phòng
Thường.
Bổ sung Danh sách thuê phòng trong đó mỗi khách hàng cho biết đang ở phòng nào và ngày
bắt đầu thuê.
Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame (có thể dùng kéo thả) thực
hiện các chức năng sau:
1. Nhập thêm khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách khách hàng đã
có trong file.
2. Nhập thêm phòng vào file PHONG.DAT. Có xử lý ngoại lệ. In ra danh sách các phòng đã có
trong file.
3. Nhập danh sách thuê phòng lưu vào file DSTP.DAT. Chú ý: một khách hàng có thể thuê
nhiều phòng khác nhau nhưng thời gian khác nhau.
4. Sắp xếp danh sách sinh viên ký túc xá đã lưu trong DSKTX.DAT
a. Theo Họ tên sinh viên
b. Theo Tên phòng
5. Giả sử mức tiền thuê phòng hàng tháng theo thứ tự loại phòng lần lượt là 4000, 3000 và 2000
(nghìn đồng). Tính tiền thuê đến thời điểm hiện tại cho mỗi khách hàng (chú ý làm tròn tháng
và tính tất cả các phòng khách hàng đã thuê).ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 21: QUẢN LÝ LƯU TRỮ SÁCH THƯ VIỆN
Thông tin về Sách gồm các thuộc tính (mã sách, Tên sách, Tác giả, Chuyên ngành, Năm xuất
bản) – trong đó Chuyên ngành có thể là: Khoa học tự nhiên, Văn học – Nghệ thuật, Điện tử Viễn
thông, Công nghệ thông tin. Mã sách là một số nguyên có 5 chữ số, tự động tăng.
Thông tin về Kệ sách (mã kệ, Tên, loại kệ, số lượng tối đa), mã kệ sách là một số nguyên có 3 chữ
số, tự động tăng. Loại kệ sách gồm: Nhỏ, Trung bình và Lớn.
Bổ sung Bảng Quản lý sách trong đó một loại sách sẽ được đặt tại một kệ sách nào đó với số lượng
cụ thể. Ghi rõ tình trạng hiện thời của sách khi cho đặt vào kệ.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm đầu sách mới vào file SACH.DAT. Có xử lý ngoại lệ. In ra danh sách các đầu
sách đã có trong file.
2. Nhập thêm kệ sách vào file KE.DAT. Có xử lý ngoại lệ. In ra danh sách các kệ sách đã có
trong file.
3. Lập Bảng QL sách bằng cách nhập các đầu sách vào kệ tương ứng, lưu vào file QLSTV.DAT
và in danh sách ra màn hình (chú ý: một đầu sách được đặt vào kệ nếu tổng số sách không
vượt quá số chỗ trống còn lại trong kệ).
4. Sắp xếp danh sách Quản lý sách đã lưu trong QLSTV.DAT
a. Theo tên sách
b. Theo số lượng mỗi loại
5. Tìm kiếm và hiển thị danh sách các cuốn sách theo tên chuyên ngànhĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 22: QUẢN LÝ ĐĂNG KÝ GIẢNG DẠY THEO TÍN CHỈ
Thông tin về Môn học gồm các thuộc tính (mã môn học, Tên môn, Tổng số tiết, Loại môn học) –
trong đó Loại môn học có thể là: Đại cương, Cơ sở ngành, Chuyên ngành bắt buộc, Chuyên ngành tự
chọn. Mã môn học là một số nguyên có 3 chữ số, tự động tăng.
Thông tin về Giảng viên (mã GV, Họ tên, Số ĐT, Khoa), mã giảng viên là một số nguyên có 5 chữ
số, tự động tăng. Khoa có thể là: Cơ bản, Điện tử, Viễn thông, CNTT, QTKD, Kế toán.
Bổ sung Bảng Đăng ký trong đó một giảng viên sẽ được phép đăng ký không quá 3 môn học một
học kỳ, mỗi môn cho biết số lớp có thể giảng dạy. Tổng số lớp của tất cả các môn không vượt quá 6.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm môn học mới vào file MH.DAT. Có xử lý ngoại lệ. In ra danh sách các môn học
đã có trong file.
2. Nhập thêm giảng viên vào file GV.DAT. Có xử lý ngoại lệ. In ra danh sách giảng viên đã có
trong file.
3. Lập Bảng Đăng ký cho từng giảng viên bằng cách nhập các môn học đăng ký của mỗi giảng
viên, số lớp mỗi môn và thời gian đăng ký (lấy thời gian hệ thống). Lưu thông tin vào file
QLDK.DAT và in danh sách ra màn hình (chú ý: cùng một giảng viên với một môn học thì
không thể xuất hiện 2 lần trong bảng này).
4. Sắp xếp danh sách Bảng đăng ký đã lưu trong QLDK.DAT
a. Theo tên giảng viên
b. Theo thời gian đăng ký
5. Lập danh sách giáo viên giảng dạy theo danh sách đăng ký. Chú ý, mỗi môn không quá 4
giảng viên (lấy theo thứ tự thời gian).ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 23: QUẢN LÝ TÍNH CÔNG BÁN HÀNG CHO SIÊU THỊ
Thông tin về Mặt hàng gồm các thuộc tính (mã hàng, Tên hàng, Nhóm hàng, Giá mua, Giá bán)
– trong đó Nhóm hàng có thể là: Hàng thời trang, Hàng tiêu dùng, Hàng điện máy, Hàng gia dụng.
Mã hàng là một số nguyên có 4 chữ số, tự động tăng.
Thông tin về Nhân viên bán hàng (mã NV, Họ tên, địa chỉ, Số ĐT), mã NV là một số nguyên có 4
chữ số, tự động tăng.
Bổ sung Bảng Danh sách bán hàng trong đó với mỗi nhân viên, nhập danh sách các mặt hàng và số
lượng mà nhân viên đó đã bán ra trong ngày.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm mặt hàng mới vào file MH.DAT. Có xử lý ngoại lệ. In ra danh sách các mặt hàng
đã có trong file.
2. Nhập thêm nhân viên bán hàng vào file NV.DAT. Có xử lý ngoại lệ. In ra danh sách nhân
viên đã có trong file.
3. Lập Bảng danh sách bán hàng cho từng nhân viên, lưu vào file QLBH.DAT và in danh sách
ra màn hình (chú ý: cùng một nhân viên với một mặt hàng thì không thể xuất hiện 2 lần trong
bảng này).
4. Sắp xếp danh sách Bảng danh sách bán hàng đã lưu trong QLBH.DAT
a. Theo tên nhân viên
b. Theo tên mặt hàng
5. Lập bảng tính công cho mỗi nhân viên. Giá trị tiền công được tính là 2% tổng số lợi nhuận
thu được.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 24: QUẢN LÝ BÁN HÀNG TRONG SIÊU THỊ ĐIỆN MÁY
Thông tin về Mặt hàng trong kho gồm các thuộc tính (mã hàng, Tên hàng, Nhóm hàng, Giá bán,
Số lượng) – trong đó Nhóm hàng có thể là: Điện tử, Điện lạnh, Máy tính, Thiết bị văn phòng. Mã
hàng là một số nguyên có 4 chữ số, tự động tăng.
Thông tin về Khách hàng (mã KH, Họ tên, địa chỉ, Số ĐT), mã KH là một số nguyên có 4 chữ số,
tự động tăng.
Bổ sung Bảng kê bán hàng (trong một ngày) trong đó với mỗi khách hàng, nhập danh sách các mặt
hàng mà khách hàng đó đã mua số lượng tương ứng. Giả sử mỗi mặt hàng không được mua quá 5
đơn vị.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm mặt hàng mới vào file MH.DAT. Có xử lý ngoại lệ. In ra danh sách các mặt hàng
đã có trong file.
2. Nhập thêm khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách khách hàng đã
có trong file.
3. Lập Bảng kê bán hàng cho từng khách hàng, lưu vào file QLBH.DAT và in danh sách ra màn
hình (chú ý: cùng một khách hàng với một mặt hàng thì không thể xuất hiện 2 lần trong bảng
này).
4. Sắp xếp danh sách Bảng kê bán hàng đã lưu trong QLBH.DAT
c. Theo tên khách hàng
d. Theo nhóm mặt hàng
5. Lập hóa đơn cho mỗi khách hàng.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 25: QUẢN LÝ CÔNG NHÂN
Thông tin về Công nhân gồm các thuộc tính (mã công nhân, Họ tên, Địa chỉ, Số điện thoại, Bậc
thợ) – trong đó Bậc thợ là một số nguyên từ 1 đến 7. Mã công nhân là một số nguyên có 4 chữ số,
tự động tăng.
Thông tin về Xưởng sản xuất (mã xưởng, tên xưởng, mô tả, Hệ số công việc), mã xưởng là một số
nguyên có 3 chữ số, tự động tăng. Hệ số công việc là một số thực từ trong khoảng từ 1 đến 20, cho
biết mức đánh giá chung về các công việc trong xưởng đó đảm nhiệm.
Bổ sung Bảng Danh sách chấm công (trong một tháng), trong đó với mỗi công nhân cho biết đang
làm tại xưởng nào tương ứng và số ngày làm việc tương ứng. Một công nhân có thể thay đổi xưởng
sản xuất nhiều lần trong tháng nhưng tổng số ngày làm việc không vượt quá 30.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm công nhân mới vào file CN.DAT. Có xử lý ngoại lệ. In ra danh sách các công
nhân đã có trong file.
2. Nhập thêm xưởng sản xuất vào file XSX.DAT. Có xử lý ngoại lệ. In ra danh sách xưởng đã
có trong file.
3. Lập Bảng danh sách chấm công cho từng công nhân, lưu vào file QLCN.DAT và in danh
sách ra màn hình.
4. Sắp xếp danh sách Bảng danh sách phân công đã lưu trong QLNS.DAT
a. Theo tên công nhân
b. Theo xưởng
5. Lập bảng kê thu nhập cho mỗi công nhân trong tháng. Thu nhập = 450000*Bậc lương*Hệ số
công việc * (số ngày làm việc/22).ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 26: QUẢN LÝ THIẾT BỊ TRONG VĂN PHÒNG
Thông tin về Thiết bị gồm các thuộc tính (mã TB, Tên, Xuất xứ, Năm sản xuất) – trong đó Xuất xứ
có thể là: Nhập khẩu, Nội địa, Liên doanh. Mã TB là một số nguyên có 5 chữ số, tự động tăng.
Thông tin về Phòng (mã PH, tên phòng, loại phòng), mã PH là một số nguyên có 5 chữ số, tự
động tăng. Loại phòng có thể là: Phòng họp, Phòng làm việc, Phòng riêng.
Bổ sung Bảng QL Thiết bị trong đó một phòng sẽ được nhận nhiều loại thiết bị, mỗi loại có số
lượng khác nhau và ghi rõ tình trạng hiện thời.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm thiết bị vào file TB.DAT. Có xử lý ngoại lệ. In ra danh sách thiết bị đã có trong
file.
2. Nhập thêm phòng vào file PH.DAT. Có xử lý ngoại lệ. In ra danh sách phòng đã có trong
file.
3. Lập Bảng QL Thiết bị cho các phòng bằng cách nhập các loại thiết bị cho mỗi phòng cùng số
lượng và tình trạng tương ứng tương ứng; lưu vào file QLTB.DAT và in danh sách ra màn
hình (chú ý: cùng một loại thiết bị trong một phòng thì không thể xuất hiện 2 lần).
4. Sắp xếp danh sách Quản lý thiết bị đã lưu trong QLTB.DAT
a. Theo tên phòng
b. Theo Số lượng thiết bị mỗi loại (giảm dần)
5. Tìm kiếm và hiển thị danh sách thiết bị trong các phòng theo tên thiết bịĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 27: QUẢN LÝ NHÓM SINH VIÊN
Thông tin về Bài tập nhóm gồm các thuộc tính (mã bài tập, Tên bài tập, Kiểu bài tập, Tổng thời
gian) – trong đó kiểu bài tập có thể gồm: nhỏ, trung bình hoặc lớn. Mã bài tập là một số nguyên
có 3 chữ số, tự động tăng.
Thông tin về Sinh viên (mã SV, Họ tên, địa chỉ, lớp), mã SV là một số nguyên có 5 chữ số, tự
động tăng.
Bổ sung Bảng phân công trong đó một sinh viên có thể được gán cho một hoặc nhiều bài tập
nhóm một lúc với số ngày tham gia khác nhau và nội dung công việc khác nhau. Một bài tập
nhóm thì không quá 4 sinh viên tham gia.
Tự xác định các lớp cho phù hợp và viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm bài tập vào file BT.DAT. Có xử lý ngoại lệ. In ra danh sách bài tập đã có trong
file.
2. Nhập thêm sinh viên viên vào file SV.DAT. Có xử lý ngoại lệ. In ra danh sách sinh viên đã
có trong file.
3. Nhập danh sách phân công bài tập nhóm cho mỗi sinh viên đã có trong file SV.DAT. Lưu
vào file PHANCONG.DAT và in danh sách ra màn hình. (chú ý: cùng một sinh viên thì
không thể tham gia cùng một bài tập với hai vị trí công việc khác nhau nhưng có thể tham
gia cùng lúc vào nhiều bài tập)
4. Sắp xếp danh sách phân công đã lưu trong PHANCONG.DAT
a. Theo Họ tên sinh viên
b. Theo Số ngày tham gia (giảm dần)
5. Tìm kiếm và hiển thị danh sách phân công theo tên bài tậpĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 28: QUẢN LÝ SẮP XẾP PHÒNG THỰC HÀNH
Thông tin về Phòng thực hành gồm các thuộc tính (mã phòng, Tên phòng, Số máy tính, Kiểu
phòng) – với kiểu phòng có thế là: phòng thực hành mạng, phòng thực hành vi xử lý và phòng thực
hành lập trình, mã phòng là một số nguyên có 5 chữ số, tự động tăng.
Thông tin về Lớp (mã lớp, tên lớp, số sinh viên), mã lớp là một số nguyên có 3 chữ số, tự động tăng.
Bổ sung Bảng sắp xếp trong đó một lớp được sắp xếp tại một hoặc nhiều phòng thực hành tương ứng
với các kíp học khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm Phòng thực hành vào file PH.DAT. Có xử lý ngoại lệ. In ra danh sách phòng thực
hành đã có trong file.
2. Nhập thêm Lớp vào file LOP.DAT. Có xử lý ngoại lệ. In ra danh sách các lớp đã có trong
file.
3. Nhập danh sách sắp xếp phòng thực hành cho mỗi lớp đã có trong fie LOP.DAT; lưu vào file
BANGSX.DAT và in danh sách ra màn hình. (Chú ý: các lớp không thể xếp vào phòng có số
máy tính ít hơn số sinh viên của lớp)
4. Sắp xếp danh sách sắp xếp phòng thực hành đã lưu trong BANGSX.DAT
a. Theo tên lớp học
b. Theo Kíp học
5. Tìm kiếm và hiển thị danh sách sắp xếp theo từng phòngĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 29: QUẢN LÝ TRẢ LƯƠNG CHO CỘNG TÁC VIÊN
Một công ty nhỏ trả lương cho cộng tác viên theo loại công việc và số giờ làm thực tế.
Thông tin về Loại công việc gồm các thuộc tính (mã công việc, Tên công việc, Kiểu công việc,
mức kinh phí) – trong đó mức kinh phí là mức trả cho một giờ làm. Kiểu công việc có thể là: Làm
qua mạng, Part time, Full time. Mã công việc là một số nguyên có 3 chữ số, tự động tăng.
Thông tin về Cộng tác viên (mã CTV, Họ và tên, địa chỉ, trình độ), mã CTV là một số nguyên có 3
chữ số, tự động tăng. Trình độ bao gồm: Phổ thông, Cao đẳng, Đại học, Sau đại học.
Bổ sung Bảng tính công trong đó một cộng tác viên sẽ khai báo các loại công việc đã làm và bao
nhiêu giờ. Chú ý: một cộng tác viên có thể làm nhiều việc khác nhau. Tổng số giờ làm của một cộng
tác viên trong tháng không được lớn hơn 240.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm loại công việc vào file CV.DAT. Có xử lý ngoại lệ. In ra danh sách loại công việc
đã có trong file.
2. Nhập thêm cộng tác viên vào file CTV.DAT. Có xử lý ngoại lệ. In ra danh sách CTV đã có
trong file.
3. Lập Bảng tính công cho mỗi cộng tác viên; lưu vào file QLCTV.DAT và in danh sách ra màn
hình.
4. Sắp xếp danh sách tính công đã lưu trong QLCTV.DAT
a. Theo họ tên cộng tác viên
b. Theo số giờ làm (giảm dần)
5. Tính toán và lập bảng tính tiền công cho mỗi cộng tác viên.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 30: QUẢN LÝ PHÂN CHIA TIỀN THƯỞNG DỰ ÁN
Sau khi hoàn thành một dự án, trưởng nhóm dự án tính tiền thưởng cho mỗi thành viên dựa trên vị trí
công việc và số ngày làm việc.
Thông tin về Thành viên gồm các thuộc tính (mã TV, Họ Tên, Tuổi, Mức lương) – trong đó mức
lương là giá trị đã ký theo hợp đồng. Mã thành viên là một số nguyên có 3 chữ số, tự động tăng.
Thông tin về Vị trí công việc (mã vị trí, Tên vị trí, mức thưởng), mã vị trí là một số nguyên có 3 chữ
số, tự động tăng.
Bổ sung Bảng phân công trong đó một thành viên có thể được gán cho một hoặc một vài vị trí công
việc trong dự án với số ngày làm ở vị trí đó. Chú ý, một thành viên không được làm quá 3 vị trí khác
nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm thành viên vào file TV.DAT. Có xử lý ngoại lệ. In ra danh sách thành viên đã có
trong file.
2. Nhập thêm vị trí công việc vào file VITRI.DAT. Có xử lý ngoại lệ. In ra danh sách vị trí đã
có trong file.
3. Nhập danh sách phân công công việc cho mỗi thành viên đã có trong file TV.DAT. Lưu vào
file PC.DAT và in danh sách ra màn hình.
4. Sắp xếp danh sách phân công đã lưu trong PC.DAT
a. Theo Họ tên thành viên
b. Theo Số ngày đã làm (giảm dần)
5. Tính tổng tiền thưởng của các thành viên và in ra màn hình (tổng tiền thưởng bằng tiền
thưởng theo các vị trí đã làm + 10% mức lương hợp đồng)ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 31: QUẢN LÝ CHO THUÊ XE Ô TÔ
Một công ty vẫn tại chia các ô tô hiện có theo nhiều loại và dựa trên thời gian thuê của từng khách để
lập hóa đơn tính tiền.
Thông tin về Ô tô gồm các thuộc tính (mã ô tô, Kiểu xe, Mức tiền thuê, Số xe) – với kiểu xe có thế là:
xe 4 chỗ loại thường, xe 4 chỗ loại cao cấp, xe 7 chỗ, xe tải. Mã ô tô là một số nguyên có 4 chữ số, tự
động tăng.
Thông tin về Khách hàng (mã khách hàng, tên khách hàng, loại xe cần thuê, số xe cần thuê), mã
khách hàng là một số nguyên có 3 chữ số, tự động tăng.
Bổ sung Bảng sắp xếp trong đó một khách hàng được sắp xếp thuê loại xe tương ứng cùng với số
lượng xe cần thuê loại đó và số ngày thuê.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm ô tô vào file OTO.DAT. Có xử lý ngoại lệ. In ra danh sách ô tô đã có trong file.
2. Nhập thêm Khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách các KH đã có
trong file.
3. Nhập danh sách sắp xếp ô tô cho mỗi khách hàng đã có trong fie KH.DAT; lưu vào file
BANGSX.DAT và in danh sách ra màn hình. Chú ý kiểm tra số xe còn lại mỗi kiểu.
4. Sắp xếp danh sách đã lưu trong BANGSX.DAT
a. Theo loại xe
b. Theo số xe cần thuê
5. Tính toán và lập hóa đơn cho mỗi khách hàng.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 32: QUẢN LÝ TÍNH NHUẬN BÚT CHO PHÓNG VIÊN
Thông tin về Phóng viên gồm các thuộc tính (mã PV, Họ tên, Địa chỉ, Loại phóng viên) – trong đó
loại phóng viên có thể là: chuyên nghiệp, nghiệp dư, cộng tác viên. Mã PV là một số nguyên có 5
chữ số, tự động tăng.
Thông tin về Kiểu Bài viết (mã kiểu bài, tên kiểu bài, đơn giá), mã kiểu bài là một số nguyên có 3
chữ số, tự động tăng.
Bổ sung Bảng Tính Công trong đó một phóng viên sẽ có một số bài viết thuộc các kiểu khác nhau
trong tháng (có thể có nhiều bài cùng kiểu và nhiều kiểu bài khác nhau). Giả sử mỗi phóng viên chỉ
được tham gia viết tối đa 5 kiểu bài khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm phóng viên vào file PV.DAT. Có xử lý ngoại lệ. In ra danh sách phóng viên đã có
trong file.
2. Nhập thêm kiểu bài viết vào file KB.DAT. Có xử lý ngoại lệ. In ra danh sách kiểu bài đã có
trong file.
3. Lập Bảng tính công cho phóng viên bằng cách nhập các kiểu bài mà mỗi phóng viên đã có
trong file PV.DAT đã viết cùng số lượng tương ứng; lưu vào file TINHCONG.DAT và in
danh sách ra màn hình. (Chú ý: một phóng viên với cùng một kiểu bài không được phép xuất
hiện quá một lần trong bảng này)
4. Sắp xếp danh sách Bảng tính công đã lưu trong TINHCONG.DAT
a. Theo Họ tên phóng viên
b. Theo Số lượng bài viết (giảm dần)
5. Lập bảng kê thu nhập của mỗi phóng viênĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 33: QUẢN LÝ BÁN ĐIỆN THOẠI DI ĐỘNG
Thông tin về Khách hàng gồm các thuộc tính (mã KH, Họ tên, Địa chỉ, Nhóm KH) – trong đó nhóm
khách hàng có thể gồm: mua lẻ, mua buôn, mua qua mạng, mã KH là một số nguyên có 5 chữ số, tự
động tăng.
Thông tin về Điện thoại (mã sp, hãng sản xuất, model, đơn giá), mã sản phẩm là một số nguyên có 5
chữ số, tự động tăng.
Bổ sung Hóa đơn trong đó một khách hàng có thể chọn mua một hoặc nhiều điện thoại với số lượng
khác nhau.
Tự xác định các lớp cho phù hợp và viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm Khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách khách hàng đã
có trong file.
2. Nhập thêm sản phẩm Điện thoại di động mới vào file MOBI.DAT. Có xử lý ngoại lệ. In ra
danh sách sản phẩm đã có trong file.
3. Nhập danh sách mua hàng cho mỗi khách hàng đã có trong file KH.DAT. Lưu vào file
HOADON.DAT và in danh sách ra màn hình .
4. Sắp xếp danh sách mua hàng đã lưu trong HOADON.DAT
c. Theo Họ tên khách hàng
d. Theo Số lượng điện thoại đặt mua (giảm dần)
5. Lập bảng kê tổng số tiền phải trả cho mỗi khách hàngĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 34: QUẢN LÝ BÁN VÉ THÁNG XE BUÝT
Thông tin về Hành khách gồm các thuộc tính (mã HK, Họ tên, Địa chỉ, Loại khách) – với quy định
loại hành khách gồm: học sinh sinh viên, cán bộ trong ngành và khách thông thường. Mã HK là một
số nguyên có 5 chữ số, tự động tăng.
Thông tin về Loại vé (mã loại, mô tả, giá bán), mã loại vé là một số nguyên có 3 chữ số, tự động
tăng. Phần mô tả cho biết loại vé là riêng cho tuyến nào, một số tuyến cụ thể nào hoặc liên tuyến.
Bổ sung Bảng kê bán vé trong đó một hành khách được mua nhiều loại vé khác nhau nhưng mỗi loại
chỉ được mua một vé trong một tháng. Giả sử tổng số loại vé được mua của mỗi hành khách không
vượt quá 3.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm Hành khách vào file HK.DAT. Có xử lý ngoại lệ. In ra danh sách hành khách đã
có trong file.
2. Nhập thêm Loại vé vào file VE.DAT. Có xử lý ngoại lệ. In ra danh sách các loại vé đã có
trong file.
3. Nhập danh sách bán vé cho mỗi hành khách đã có trong file HK.DAT; lưu vào file
BANVE.DAT và in danh sách ra màn hình .
4. Sắp xếp danh sách bán vé đã lưu trong BANVE.DAT
a. Theo Họ tên hành khách
b. Theo Loại vé
5. Lập bảng tính tổng giá tiền phải trả của mỗi hành khách. Chú ý: Học sinh sinh viên được
giảm 50%, cán bộ trong ngành được giảm 70%.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 35: QUẢN LÝ DỊCH VỤ ADSL
Thông tin về Khách hàng gồm các thuộc tính (mã KH, Họ tên, Địa chỉ, Loại KH) – với Loại khách
hàng có thể là: cá nhân, đại diện đơn vị hành chính, đại diện đơn vị kinh doanh, mã KH là một số
nguyên có 5 chữ số, tự động tăng.
Thông tin về Loại dịch vụ (mã DV, mô tả, mức giá cước) mã DV là một số nguyên có 3 chữ số, tự
động tăng. Giả sử tất cả các loại dịch vụ đều tính cước theo dung lượng.
Bổ sung Hóa đơn trong đó một khách hàng có thể sử dụng một hoặc nhiều loại dịch vụ. Mỗi loại
cho biết tổng dung lượng đã dùng. Giả sử mỗi khách được phép sử dụng không quá 3 loại dịch vụ
khác nhau.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách khách hàng đã
có trong file.
2. Nhập thêm loại dịch vụ vào file DV.DAT. Có xử lý ngoại lệ. In ra danh sách dịch vụ đã có
trong file.
3. Nhập hóa đơn cho mỗi khách hàng đã có trong file KH.DAT, trong đó mỗi khách hàng ứng
với một dịch vụ sử dụng sẽ có số lượng sử dụng (theo dung lượng); lưu vào file
HOADON.DAT và in danh sách ra màn hình. (Chú ý: cùng một khách hàng với một loại dịch
vụ thì không được xuất hiện quá một lần trong bảng này)
4. Sắp xếp danh sách hóa đơn đã lưu trong HOADON.DAT
a. Theo Họ tên khách hàng
b. Theo Số lượng sử dụng (giảm dần)
5. Lập bảng kê số tiền phải trả cho mỗi khách hàngĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 36: QUẢN LÝ BÁN VÉ MÁY BAY
Thông tin về Người mua vé gồm các thuộc tính (Mã người mua, Họ tên, Địa chỉ, Loại) – trong đó
nhóm người mua có thể là: mua lẻ, mua tập thể, mua qua mạng, mã người mua là một số nguyên có 5
chữ số, tự động tăng.
Thông tin về Loại vé máy bay (mã vé, loại vé, đơn giá), mã vé là một số nguyên có 5 chữ số, tự động
tăng. Loại vé có thể là: doanh nhân, phổ thông, phổ thông giá rẻ, thẻ vàng, thẻ xanh, ngoại giao ..
Bổ sung Hóa đơn, trong đó một người mua có thể một mua một hoặc nhiều vé.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm người mua vé vào file NGUOIMUA.DAT. Có xử lý ngoại lệ. In ra danh sách
người mua đã có trong file.
2. Nhập thêm loại vé vào file VE.DAT. Có xử lý ngoại lệ. In ra danh sách các loại vé đã có
trong file.
3. Nhập danh sách hóa đơn mua vé cho mỗi người mua đã có trong file NGUOIMUA.DAT;
(giả sử mỗi người mua có thể mua một hoặc nhiều loại vé nhưng không quá 3 loại, mỗi loại
có một số lượng xác định nhưng không quá 10 vé một lần mua). Lưu vào file
HOADON.DAT và in danh sách ra màn hình.
4. Sắp xếp danh sách hóa đơn đã lưu trong HOADON.DAT
a. Theo Họ tên người mua
b. Theo Số lượng vé mua (giảm dần)
5. Lập bảng kê số tiền phải tra cho mỗi người muaĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 37: QUẢN LÝ MÁY TÍNH PHÒNG THỰC HÀNH
Thông tin về Máy tính gồm các thuộc tính (số hiệu, Tên, Xuất xứ, Năm nhập, Cấu hình) – trong đó
Xuất xứ có thể là: Nhập khẩu, Nội địa, Liên doanh. Số hiệu máy là một số nguyên có 5 chữ số, tự
động tăng. Cấu hình là một mô tả dạng text.
Thông tin về Phòng thực hành (mã phòng, tên phòng, số máy), mã Phòng là một số nguyên có 5
chữ số, tự động tăng.
Bổ sung Bảng QL Máy tính trong đó một phòng thực hành sẽ được nhận nhiều loại thiết bị, mỗi loại
có số lượng khác nhau và ghi rõ tình trạng hiện thời.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm thiết bị vào file MT.DAT. Có xử lý ngoại lệ. In ra danh sách thiết bị đã có trong
file.
2. Nhập thêm phòng thực hành vào file PM.DAT. Có xử lý ngoại lệ. In ra danh sách phòng
thực hành đã có trong file.
3. Lập Bảng QL máy tính cho các phòng thực hành bằng cách nhập các loại máy cho mỗi
phòng cùng số lượng và tình trạng tương ứng tương ứng; lưu vào file QLTH.DAT và in danh
sách ra màn hình (chú ý: cùng một loại máy trong một phòng thực hành thì không thể xuất
hiện 2 lần, tổng số lượng máy tính phải đúng bằng số máy cần có của phòng).
4. Sắp xếp danh sách Quản lý thiết bị đã lưu trong QLTB.DAT
a. Theo tên phòng
b. Theo Số lượng máy tính (giảm dần)
5. Tìm kiếm và hiển thị danh sách thiết bị trong các phòng theo tên thiết bịĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 38: QUẢN LÝ TOUR DU LỊCH
Một công ty du lịch xây dựng sẵn các tour và phân theo nhiều kiểu khác nhau sau đó cho khách hàng
đặt tour online.
Thông tin về Tour gồm các thuộc tính (mã tour, Kiểu tour, Thông tin tour, Đơn giá) – với kiểu tour
có thế là: 1 ngày, dưới 5 ngày, dưới 7 ngày, dài ngày. Mã tour là một số nguyên có 4 chữ số, tự động
tăng. Thông tin tour là một đoạn văn bản.
Thông tin về Khách hàng (mã khách hàng, tên khách hàng, kiểu khách hàng), mã khách hàng là
một số nguyên có 3 chữ số, tự động tăng. Kiểu khách hàng có thể là: cá nhân, tập thể.
Bổ sung Bảng đặt tour trong đó một khách hàng được chọn một tour để đặt, nhập số người đăng ký và
ngày bắt đầu. Nếu khách hàng là cá nhân thì số lượng mặc định là 1.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc JFrame
(có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm tour vào lưu vào file TOUR.DAT. Có xử lý ngoại lệ. In ra danh sách tour đã có
trong file.
2. Nhập thêm Khách hàng vào file KH.DAT. Có xử lý ngoại lệ. In ra danh sách các KH đã có
trong file.
3. Nhập danh sách đặt tour cho mỗi khách hàng đã có trong fie KH.DAT; lưu vào file
DATTOUR.DAT và in danh sách ra màn hình. Chú ý một khách hàng không đăng ký hai
tour trong cùng một thời gian.
4. Sắp xếp danh sách đã lưu trong DATTOUR.DAT
a. Theo loại tour
b. Theo loại khách hàng
5. Tính toán và lập hóa đơn cho mỗi khách hàng.ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 39: QUẢN LÝ TÍNH LƯƠNG THEO NGÀY CÔNG
Thông tin về Nhân viên gồm các thuộc tính (mã nhân viên, Họ tên, Địa chỉ, Số điện thoại, Bậc
lương) – trong đó Bậc lương là một số nguyên từ 1 đến 9. Mã nhân viên là một số nguyên có 4 chữ
số, tự động tăng.
Thông tin về Phòng ban (mã phòng, tên phòng, mô tả, Hệ số công việc), mã phòng là một số
nguyên có 3 chữ số, tự động tăng. Hệ số công việc là một số thực từ trong khoảng từ 1 đến 20, cho
biết mức đánh giá chung về các công việc thuộc phòng đó đảm nhiệm.
Bổ sung Bảng Danh sách chấm công (trong một tháng), trong đó với mỗi nhân viên cho biết phòng
ban tương ứng và số ngày làm việc trong tháng.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm nhân viên mới vào file NV.DAT. Có xử lý ngoại lệ. In ra danh sách các nhân viên
đã có trong file.
2. Nhập thêm phòng ban vào file PB.DAT. Có xử lý ngoại lệ. In ra danh sách phòng ban đã có
trong file.
3. Lập Bảng danh sách chấm công cho từng nhân viên, lưu vào file QLNS.DAT và in danh sách
ra màn hình (chú ý: cùng một nhân viên không thể làm việc ở hai phòng ban khác nhau).
4. Sắp xếp danh sách Bảng danh sách phân công đã lưu trong QLNS.DAT
c. Theo tên nhân viên
d. Theo phòng ban
5. Lập bảng kê thu nhập cho mỗi nhân viên trong tháng. Thu nhập = 1250000*(2 + Bậc
lương/3)*Hệ số công việc * (số ngày làm việc/22).ĐỀ THI LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
Thời gian: 60 phút
Một số chú ý:
 Chương trình bắt buộc phải sử dụng giao diện JFrame. Sinh viên có thể sử dụng kéo thả.
Các chức năng có lựa chọn thì phải sử dụng hộp chọn.
 Khi nhập dữ liệu ở câu 3 thì cần biết đang nhập dữ liệu cho đối tượng nào và chỉ rõ nhập
mới thông tin hay cập nhật thông tin đã có.
 Sinh viên phải xử lý đầy đủ các ngoại lệ khi nhập dữ liệu (bỏ trống không nhập, nhập sai
định dạng, nhập dữ liệu không nằm trong khoảng cho phép) và các ngoại lệ khác được yêu
cầu trong đề bài. Với hai câu 1 và 2, nếu không xử lý ngoại lệ thì không được tính điểm.
 Sinh viên tự thiết kế các lớp liên quan và phải mô tả đúng quan hệ giữa các lớp. Trong bài
làm BẮT BUỘC phải sử dụng giao tiếp (interface)
 Dữ liệu trong bài được lưu vào file dạng nhị phân sử dụng ObjectOutputStream và
ObjectInputStream
 Kết quả phải hiển thị dạng Bảng. Cho phép sửa nội dung trong Bảng và cập nhật thay đổi đó.
 Khuyến khích sinh viên thiết kế và lập trình theo kiến trúc MVC (được cộng 0.5 điểm)
ĐỀ SỐ 40: QUẢN LÝ TÍNH CÔNG THEO DOANH THU
Một công ty dịch vụ viễn thông di động thực hiện trả công cho nhân viên phòng bán hàng theo
doanh thu mà nhân viên đó mang lại trong một tháng.
Thông tin về Dịch vụ gồm các thuộc tính (mã dịch vụ, Tên dịch vụ, Nhóm dịch vụ, Chi phí, Giá
cước) – trong đó Nhóm dịch vụ có thể là: Dịch vụ thuê bao trả trước, Dịch vụ thuê bao trả sau, Dịch
vụ giá trị gia tăng. Mã dịch vụ là một số nguyên có 4 chữ số, tự động tăng.
Thông tin về Nhân viên bán hàng (mã NV, Họ tên, địa chỉ, Số ĐT), mã NV là một số nguyên có 4
chữ số, tự động tăng.
Bổ sung Bảng Danh sách bán hàng trong đó với mỗi nhân viên, nhập danh sách các dịch vụ và số
lượng mà nhân viên đó đã cung cấp trong ngày.
Tự xác định các lớp cho phù hợp và Viết chương trình trên Java sử dụng giao diện Frame hoặc
JFrame (có thể dùng kéo thả) thực hiện các chức năng sau:
1. Nhập thêm dịch vụ mới vào file DV.DAT. Có xử lý ngoại lệ. In ra danh sách các dịch vụ đã
có trong file.
2. Nhập thêm nhân viên bán hàng vào file NV.DAT. Có xử lý ngoại lệ. In ra danh sách nhân
viên đã có trong file.
3. Lập Bảng danh sách bán hàng cho từng nhân viên, lưu vào file QLBH.DAT và in danh sách
ra màn hình (chú ý: cùng một nhân viên với một dịch vụ thì không thể xuất hiện 2 lần trong
bảng này).
4. Sắp xếp danh sách Bảng danh sách bán hàng đã lưu trong QLBH.DAT
c. Theo tên nhân viên
d. Theo tên dịch vụ
5. Lập bảng tính công cho mỗi nhân viên. Giá trị tiền công được tính là 2% tổng số lợi nhuận
thu được.
