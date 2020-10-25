# HƯỚNG DẪN THÊM FOOTER VÀO SẢN PHẨM DỰ THI

## Bước 1. Lấy footer và hình ảnh

Thí sinh có thể lấy đoạn code footer của CLB từ tập tin **footer.html** trong thư mục này hoặc
copy đoạn code phía dưới.

*footer.html*
```html
<footer 
    style="position: absolute; bottom: 20px; right: 0; 
    display: flex; justify-content: flex-end;
    width: 100%; align-items: center;">
    <div style="text-align: right;
    line-height: 1.25; font-weight: bold;
    font-size: 18px">
        <span id="icon-name" style="display: block;">[Tên lớp || Tên cá nhân]</span>
        <span style="display: block;">[Tên đội || MSSV]</span>
    </div>
    <img style="width: 120px;
    height: auto;" src="https://iconclub.github.io/assets/iconLogo.png" alt="ICON">
</footer>
```

## Bước 2. Thêm vào sản phẩm

Với đoạn code mà chúng ta đã copy ở trên, bây giờ chúng ta sẽ thêm đoạn code đó vào cuối thẻ **body** hoặc
một thẻ nào đó chứa hết sản phẩm.

## Bước 3. Chỉnh sửa đoạn code

Bây giờ đối với các hình thức tham gia khác nhau mà chúng ta cần sửa lại các thẻ **span**. CLB giả định là 
CLB đang tham gia cuộc thi với lớp là 18050302 và tên đội là ICONIC.
Thể nên chúng ta cần sửa lần lượt hai thẻ **span** thành 18050302 và ICONIC.

![Tập thể](./Team.png)

Tương tự đối với cá nhân là Nguyễn Thành Tiến, 51800636.

![Cá nhân](./Solo.png)