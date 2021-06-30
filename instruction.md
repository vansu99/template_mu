# Photoshop basics

- Cắt ảnh
1. Phím alt + con mắt và click chuột trái vào
2. Image -> trim
3. File -> Export -> Save for web (ctrl + shift + alt + s)
4. Hoặc chuột phải vào layer chọn "Export to PNG"

================== *** ==================

# Gulp

- Các source code trong folder App được build nó sẽ generate các file ở folder Public
- Sẽ code html lại file 'index.pug'
- Tạo class : cho vào dấu (attributes)
  VD1: h2(class="heading") This is heading title
  VD2: input(type="text" name="Email")

# Layout

- Là 1 cấu trúc chung.
- Các file html sẽ kế thừa theo cấu trúc layout này.

# Mixins

- Được sử dụng khi các phần tử html có cấu trúc html giống nhau
  VD: 1 Div sẽ có 3 phần tử Div (nhỏ) tương ứng với 3 sản phẩm

# Lưu ý khi code Pug

- Không code trực tiếp trên file index.html . Vì đây là file được build ra từ index.Pug .
- cần thống nhất là dùng Tab hay Space. Vì Pug nó không cho dùng 2 cả trong cùng một lúc.
=> Solution khi gặp lỗi : chọn Tab Size -> chọn Convert Indentation to Tabs/Spaces

# Phân tích template

- Nhìn vào 1 bảng Design cần nằm rõ các yếu tố sau:
  + Màu sắc (các màu chủ đạo, màu tiêu đề, ...)
  + Kiểu chữ
  + Khoảng cách

+ Block Header
  - header
  - header-top
  - header-content
  - header-bottom
  - responsive
  - menu
  - slick (slider)

# Học tập

- Phần hover, focus, ... : nên viết riêng, đừng viết nested.
- Không viết CSS lồng nhiều cấp => nên viết đến cấp 2 thôi.
- Chữ dính liền => dùng text-clamp để tạo ra dấu ...