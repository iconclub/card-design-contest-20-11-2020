# HƯỚNG DẪN THÊM FOOTER VÀO SẢN PHẨM DỰ THI

## Bước 1. Lấy footer và hình ảnh

Trong thư mục này, các thí sinh có thể tìm được tập tin **footer.html** và ảnh logo CLB **iconLogo.png**, tập 
tin này chứa nội dung đoạn code mà cần thêm vào sản phẩm. 

*footer.html*
```html
<footer 
    style="position: absolute; bottom: 20px; right: 0; 
    display: flex; justify-content: flex-end;
    width: 100%; align-items: center;">
    <div style="text-align: right;
    line-height: 1.25; font-weight: bold;
    font-size: 18px">
        <span id="icon-name" style="display: block;">Nguyễn Thành Tiến</span>
        <span style="display: block;"></span>
    </div>
    <img style="width: 120px;
    height: auto;" src="./iconLogo.png" alt="ICON">
</footer>
```

## Bước 2. Thêm vào sản phẩm

Với đoạn code mà chúng ta đã copy ở trên, bây giờ chúng ta sẽ thêm đoạn code đó vào cuối thẻ **body** hoặc
một thẻ nào đó chứa hết sản phẩm và để ảnh logo CLB trong cùng thư mục

## Bước 3. Chỉnh sửa đoạn code

Bây giờ đối với các hình thức tham gia khác nhau mà chúng ta cần sửa lại các thẻ **span**. CLB giả định là 
CLB đang tham gia cuộc thi với lớp là 18050302 và tên đội là ICONIC.
Thể nên chúng ta cần sửa lần lượt hai thẻ **span** thành 18050302 và ICONIC.
Tương tự với cá nhân là Nguyễn Thành Tiến, 51800636

![Tập thể](./Team.png)

![Cá nhân](./Solo.png)