# BÁO CÁO BÀI TẬP LỚN A3 — WEBSITE GIỚI THIỆU LINH KIỆN MÁY TÍNH SLD PC

**Học phần:** Thiết kế web và triển khai hệ thống phần mềm (FIT4014)  
**Trường:** Trường Đại học Đại Nam (DNU)  
**Khoa:** Công nghệ Thông tin (FIT)  
**Lớp học phần:** CNTT 20-04
**Giảng viên giảng dạy:** ThS. Lê Thái Bảo  

---

## 1. THÔNG TIN SINH VIÊN THỰC HIỆN

- **Họ và tên:** Đỗ Văn Dũng
- **Mã sinh viên:** 2071020052
- **Lớp hành chính:** CNTT 20-04
- **Tên đề tài:** Xây dựng website tĩnh giới thiệu và trưng bày linh kiện máy tính SLD PC.
- **Tên website:** SLD PC – Linh kiện máy tính.


---

## 2. GIỚI THIỆU ĐỀ TÀI

Linkweb: https://soilaodai123.github.io/A3-TKW-2071020052-DoVanDung/
Link rep: https://github.com/soilaodai123/A3-TKW-2071020052-DoVanDung

SLD PC là website tĩnh giới thiệu và trưng bày các sản phẩm linh kiện máy tính, tập trung vào nhóm linh kiện đã qua sử dụng (SecondHand) và hàng lướt. Website giúp người xem tham khảo danh mục sản phẩm, hình ảnh, thông tin cấu hình cơ bản và mức giá được hiển thị trên từng sản phẩm.

Giao diện sử dụng tông màu xanh Navy kết hợp xanh dương và xanh Cyan. Các khu vực nội dung và thẻ sản phẩm được chia thành từng khối riêng biệt nhằm tạo sự rõ ràng, dễ quan sát.

### Các danh mục sản phẩm

Website hiện có 7 danh mục, mỗi danh mục đang hiển thị 3 sản phẩm mẫu:

1. **CPU – Bộ vi xử lý:** AMD Ryzen 5 5600, Intel Core i5-12400F, AMD Ryzen 5 7500F.
2. **VGA – Card đồ họa:** Radeon RX 6600 8GB, GeForce RTX 3060 12GB, GeForce GTX 1660 Super.
3. **RAM – Bộ nhớ trong:** Các sản phẩm Kingston Fury Beast và Apacer Panther.
4. **SSD – Ổ cứng:** Các sản phẩm Gigabyte, Kingston và Samsung.
5. **Mainboard – Bo mạch chủ:** Các sản phẩm ASRock, MSI và Gigabyte.
6. **PSU – Nguồn máy tính:** Các sản phẩm Huntkey, Corsair và Cooler Master.
7. **Tản nhiệt:** Các sản phẩm tản nhiệt khí và tản nhiệt nước AIO.

Ngoài khu vực sản phẩm, website còn có banner, phần giới thiệu SLD PC, biểu mẫu liên hệ và chân trang.

---

## 3. PHÂN TÍCH KIẾN THỨC VÀ KỸ THUẬT SỬ DỤNG

Phần này phân loại các kỹ thuật có trong mã nguồn theo hướng kiến thức HTML/CSS cơ bản và phần mở rộng tự tìm hiểu. Tỷ lệ 60% kiến thức đã học và 40% tự tìm hiểu là định hướng trình bày theo mẫu báo cáo; không phải kết quả đo lường tự động từ mã nguồn.

### A. Kiến thức HTML và CSS cơ bản

1. **Cấu trúc tài liệu HTML5:** Sử dụng `<!DOCTYPE html>`, `<html>`, `<head>` và `<body>` để xây dựng trang web.
2. **Các thẻ nội dung:** Sử dụng `<div>`, `<section>`, `<h2>`, `<h3>`, `<p>`, `<b>`, `<a>` và `<img>` để tổ chức nội dung.
3. **Liên kết điều hướng:** Sử dụng thẻ `<a>` với đường dẫn dạng `#san-pham`, `#gioi-thieu` và `#lien-he` để di chuyển đến các khu vực trong trang.
4. **Hình ảnh:** Sử dụng `<img>` để hiển thị banner và hình ảnh minh họa cho từng sản phẩm; thuộc tính `alt` cung cấp nội dung mô tả ảnh.
5. **Biểu mẫu:** Sử dụng `<form>`, `<label>`, `<input>`, `<textarea>` và `<button>` để tạo khu vực nhập thông tin liên hệ.
6. **CSS cơ bản:** Sử dụng các thuộc tính `color`, `background`, `font-family`, `font-size`, `margin`, `padding`, `border`, `width` và `height` để định dạng giao diện.
7. **Bố cục Flexbox:** Sử dụng `display: flex` và `flex-wrap: wrap` để sắp xếp các thẻ sản phẩm thành từng hàng.

### B. Kỹ thuật tự tìm hiểu và mở rộng

1. **CSS Variables (`:root`):** Khai báo các biến màu như `--navy-950`, `--blue-500`, `--cyan`, `--page-bg` và `--card` để quản lý màu sắc tập trung, giúp giao diện đồng nhất và thuận tiện khi chỉnh sửa.
2. **CSS Flexbox nâng cao:** Kết hợp `flex`, `flex-wrap`, `gap` và `align-items` để các thẻ sản phẩm tự sắp xếp khi không gian hiển thị thay đổi.
3. **Hiệu ứng chuyển động (`transition`):** Tạo chuyển đổi mượt khi người dùng di chuột lên liên kết, nút bấm và thẻ sản phẩm.
4. **Hiệu ứng hover (`transform`, `box-shadow`):** Sử dụng `translateY()` và `box-shadow` để tạo cảm giác thẻ sản phẩm nổi lên khi được trỏ chuột.
5. **Bộ chọn giả (`:hover`, `:focus`, `:nth-of-type()`):** Thay đổi giao diện khi tương tác và tạo màu nền xen kẽ cho các nhóm sản phẩm.
6. **Cuộn trang mượt (`scroll-behavior: smooth`):** Hỗ trợ chuyển đến các phần nội dung trong trang một cách mượt mà.
7. **Media Queries (`@media`):** Điều chỉnh chiều rộng khu vực nội dung và cách sắp xếp thẻ sản phẩm theo các kích thước màn hình tablet và điện thoại.
8. **Nền chuyển sắc (`linear-gradient`):** Kết hợp nhiều sắc độ xanh để tạo chiều sâu cho khu vực banner và nền danh mục.
9. **Thiết kế giao diện theo bảng màu:** Sử dụng tông Navy, xanh dương và Cyan để tạo sự thống nhất giữa header, banner, khu vực sản phẩm, thẻ sản phẩm và footer.

---

## 4. CẤU TRÚC THƯ MỤC DỰ ÁN

```text
SLD-PC/
├── index.html          # Trang chính: banner, danh mục sản phẩm,
│                       # giới thiệu và biểu mẫu liên hệ
├── style.css           # Định dạng giao diện, màu sắc, bố cục,
│                       # hiệu ứng và responsive
├── README.md           # Tài liệu giới thiệu và hướng dẫn dự án
└── images/
    ├── banner.png      # Banner chính của website
    ├── card/           # Hình ảnh card đồ họa (VGA)
    ├── cpu/            # Hình ảnh bộ vi xử lý
    ├── main/           # Hình ảnh bo mạch chủ
    ├── psu/            # Hình ảnh bộ nguồn
    ├── ram/            # Hình ảnh RAM
    ├── ssd/            # Hình ảnh ổ cứng SSD
    └── tan/            # Hình ảnh bộ tản nhiệt
```

Các hình ảnh sản phẩm được lưu trong thư mục con tương ứng với từng danh mục. Khi thay ảnh, cần giữ đúng đường dẫn được khai báo trong thuộc tính `src` của thẻ `<img>` trong `index.html`, hoặc cập nhật lại đường dẫn nếu đổi tên/thư mục ảnh.

---

## 5. CHỨC NĂNG VÀ CÁCH KIỂM TRA WEBSITE

### Các chức năng hiện có

- Hiển thị banner giới thiệu SLD PC.
- Hiển thị 7 nhóm linh kiện máy tính với hình ảnh, tên sản phẩm, thông tin ngắn và giá.
- Điều hướng đến khu vực sản phẩm, giới thiệu và liên hệ bằng các liên kết trên thanh menu.
- Hiển thị thông tin giới thiệu về SLD PC.
- Cung cấp biểu mẫu để người xem nhập họ tên, số điện thoại, Gmail và nội dung cần tư vấn.
- Có hiệu ứng hover trên liên kết, nút và thẻ sản phẩm.
- Điều chỉnh bố cục cho màn hình tablet và điện thoại bằng CSS Media Queries.

### Hướng dẫn mở website

1. Giải nén file ZIP dự án vào một thư mục trên máy tính.
2. Mở thư mục vừa giải nén.
3. Nhấp đúp vào file `index.html`.
4. Website sẽ được mở bằng trình duyệt như Google Chrome hoặc Microsoft Edge.
5. Kiểm tra thanh menu, banner, các nhóm sản phẩm, phần giới thiệu và biểu mẫu liên hệ.
6. Thay đổi độ rộng cửa sổ trình duyệt hoặc mở bằng điện thoại để kiểm tra cách bố trí responsive.


## 6. KẾT LUẬN

Website SLD PC là sản phẩm website tĩnh giới thiệu và trưng bày linh kiện máy tính, được xây dựng bằng HTML5 và CSS3. Qua quá trình thực hiện, sinh viên vận dụng các kiến thức về cấu trúc trang HTML, liên kết, hình ảnh, biểu mẫu, định dạng CSS và bố cục Flexbox; đồng thời tìm hiểu thêm về CSS Variables, hiệu ứng tương tác, nền chuyển sắc và thiết kế responsive.

Sản phẩm là nền tảng ban đầu để tiếp tục phát triển các chức năng nâng cao như tìm kiếm sản phẩm, lọc theo danh mục, giỏ hàng và quản lý dữ liệu sản phẩm trong những phiên bản tiếp theo.
