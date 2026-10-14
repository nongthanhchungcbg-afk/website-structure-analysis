# Phân tích website tham khảo: MDN Web Docs

**Trang được xem:** [MDN Web Docs](https://developer.mozilla.org/en-US/)  
**Ảnh chụp trang tham khảo:** [mdn-homepage.png](reference/mdn-homepage.png)

## Bố cục trang

- **Header:** Phần đầu trang đặt tên MDN, khu vực tìm kiếm và lời giới thiệu “Resources for Developers, by Developers”. Nó làm rõ mục đích của trang là cung cấp tài liệu cho người phát triển web.
- **Navigation Menu:** Điều hướng chính nằm sát đầu trang, cung cấp đường tới các khu vực như công nghệ web, tài liệu, học tập và Blog. Có thể truy cập nội dung bằng các liên kết điều hướng thay vì phải tìm toàn bộ trong trang.
- **Content Section:** Nội dung bắt đầu bằng các chủ đề và bài viết nổi bật, sau đó tiếp tục với tin mới, đóng góp gần đây và nội dung cộng đồng. Các nội dung được chia nhóm và trình bày thành những khối dễ quét.
- **Footer:** Cuối trang tổng hợp các liên kết được phân theo nhóm như MDN, cộng đồng và nhà phát triển, cùng thông tin chính sách và pháp lý.

## Bố cục tái tạo

Trang `index.html` tái hiện cấu trúc tổng quát đó bằng một header giới thiệu, menu bốn mục cố định khi cuộn, phần nội dung chủ đề dạng thẻ lưới và khu vực nội dung bổ sung. Footer được chia thành hai cột. Bản thực hành dùng nội dung và hình minh họa SVG tự tạo, không sao chép nguyên văn giao diện hay nội dung MDN.

## Cấu trúc dự án

```text
index.html
style.css
ANALYSIS.md
reference/mdn-homepage.png
```
