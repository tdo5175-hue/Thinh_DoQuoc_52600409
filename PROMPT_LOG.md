NHẬT KÝ PROMPT ENGINEERING (VIBE CODING LOG)
- Họ và tên: Đỗ Quốc Thịnh
- MSSV: 526000409
- Tên đề tài Website: MINI GT STORE – Website giới thiệu và bán mô hình xe MINI GT
- Công cụ AI đã sử dụng: Antigravity, ChatGPT
- Công nghệ sử dụng: HTML5, CSS3, CSS Variables, Flexbox, CSS Grid, Animate.css, AOS.css
- JavaScript: Không sử dụng

1. Yêu cầu ban đầu (System/Initial Prompt)
Tôi muốn xây dựng một website MINI GT STORE chuyên giới thiệu và bán các mô hình xe MINI GT.
Tôi cung cấp hình ảnh tham khảo để định hướng phong cách thiết kế. Hãy xây dựng một giao diện hiện đại, cao cấp, sạch sẽ và phù hợp với một website bán mô hình xe diecast.
YÊU CẦU QUAN TRỌNG:
- Tuyệt đối không sử dụng JavaScript.
- Không tạo file .js.
- Không sử dụng inline JavaScript.
- Không sử dụng thư viện hoặc framework yêu cầu JavaScript.
- Chỉ sử dụng HTML5 và CSS3.
- Được sử dụng Animate.css và AOS.css theo yêu cầu của bài.
Website phải sử dụng Semantic HTML5 đúng chuẩn, bao gồm:
- <header>
- <nav>
- <main>
- <section>
- <article>
- <aside> nếu phù hợp
- <footer>
Hạn chế tối đa việc sử dụng <div> cho những nội dung đã có thẻ semantic phù hợp.
Website cần có các khu vực:
1. Header
2. Navigation
3. Hero Banner
4. Danh mục sản phẩm
5. Sản phẩm nổi bật
6. Sản phẩm mới
7. Pre-Order
8. F1 Racing Collection
9. Box Sets
10. Chính sách / lợi ích
11. Footer
12. ...
Thiết kế theo phong cách:
- Màu đỏ làm màu nhấn.
- Xanh navy / đen cho typography.
- Nền trắng và xám rất nhạt.
- Card bo góc.
- Shadow nhẹ.
- Typography rõ ràng.
- Khoảng cách hợp lý.
- Giao diện chuyên nghiệp.
Sử dụng CSS Variables trong :root cho:
- màu sắc
- font
- kích thước chữ
- border radius
- box shadow
- spacing
Sử dụng Flexbox và CSS Grid để xây dựng layout.
Website phải responsive trên:
- Desktop
- Tablet
- Mobile
Tích hợp Animate.css và AOS.css đúng cách theo phạm vi không sử dụng JavaScript.
Thay vào đó, website tập trung vào UI/UX, Semantic HTML5, CSS và trải nghiệm người dùng.
Hãy tạo code sạch, dễ đọc, chia thành các file HTML/CSS hợp lý.
Sau khi hoàn thành hãy kiểm tra:
Semantic HTML,CSS Variables, Flexbox, CSS Grid.Responsive, Animation.

2. Quá trình tinh chỉnh & Giải quyết sự cố
-Lần 1: Kiểm tra Semantic HTML5
Prompt đã dùng:
Hãy kiểm tra lại toàn bộ cấu trúc HTML của website MINI GT STORE.
Yêu cầu website phải sử dụng đúng Semantic HTML5.
Hãy sử dụng:
<header> cho phần đầu trang.
<nav> cho thanh điều hướng.
<main> cho nội dung chính.
<section> cho từng khu vực nội dung.
<article> cho từng sản phẩm.
<footer> cho phần cuối trang.
Có thể sử dụng <aside> nếu khu vực đó phù hợp với nội dung phụ.
Hạn chế <div> khi có thể sử dụng thẻ semantic phù hợp.
Không thay đổi giao diện hiện tại.
Không sử dụng JavaScript.
-Kết quả AI tạo ra:
AI đã kiểm tra và sắp xếp lại cấu trúc HTML theo Semantic HTML5, sử dụng các thẻ <header>, <nav>, <main>, <section>, <article> và <footer> phù hợp hơn. Một số <div> không cần thiết được thay thế.
-Nhận xét & Tinh chỉnh của SV:
Sau khi kiểm tra, tôi nhận thấy cấu trúc HTML rõ ràng và dễ quản lý hơn nhưng vẫn giữ nguyên giao diện. Tôi tiếp tục yêu cầu AI kiểm tra phần CSS.

-Lần 2: Chuẩn hóa CSS Variables
Prompt đã dùng:
Hãy kiểm tra CSS của website MINI GT STORE và chuẩn hóa bằng CSS Variables trong :root.
Tạo biến cho màu sắc, font, kích thước chữ, border-radius, box-shadow và spacing. Sau đó áp dụng các biến này vào toàn bộ website.
Không thay đổi bố cục và không sử dụng JavaScript.
-Kết quả AI tạo ra:
AI tạo hệ thống CSS Variables và thay thế những giá trị CSS bị lặp lại bằng các biến tương ứng.
-Nhận xét & Tinh chỉnh của SV:
Cách tổ chức CSS trở nên rõ ràng hơn. Khi muốn thay đổi màu chủ đạo hoặc kích thước chung, tôi có thể chỉnh trực tiếp trong :root.

Lần 3: Tối ưu Flexbox & CSS Grid
Prompt đã dùng:
Hãy kiểm tra lại layout website MINI GT STORE và tối ưu bằng Flexbox và CSS Grid.
Sử dụng Flexbox cho Header, Navigation và các khu vực cần căn chỉnh. Sử dụng CSS Grid cho Product Card và các danh mục sản phẩm.
Đảm bảo layout cân đối trên Desktop, Tablet và Mobile. Không sử dụng JavaScript.
-Kết quả AI tạo ra:
AI điều chỉnh layout bằng Flexbox và Grid, đồng thời bổ sung Media Query để website responsive.
-Nhận xét & Tinh chỉnh của SV:
Sau khi kiểm tra, bố cục sản phẩm cân đối hơn và không bị tràn màn hình trên thiết bị nhỏ.
-Lần 4: Cải thiện UI/UX
Prompt đã dùng:
Hãy cải thiện UI/UX của website MINI GT STORE nhưng giữ nguyên cấu trúc và nội dung hiện tại.
Tập trung vào Product Card, Hero Banner, Button, Typography, khoảng cách và màu sắc.
Sử dụng border-radius và shadow nhẹ. Thiết kế hiện đại, sạch sẽ và không quá nhiều hiệu ứng.
Không sử dụng JavaScript.
-Kết quả AI tạo ra:
AI cải thiện Product Card, Hero Banner, button, typography và khoảng cách giữa các section.
Nhận xét & Tinh chỉnh của SV:
Giao diện sau khi chỉnh sửa có tính thống nhất hơn và phù hợp với chủ đề website bán mô hình xe.
-Lần 5: Tích hợp Animate.css và AOS.css
Prompt đã dùng:
Hãy tích hợp Animate.css và AOS.css vào website MINI GT STORE theo yêu cầu môn học.
Chỉ sử dụng trong phạm vi HTML/CSS và tuyệt đối không thêm JavaScript.
Áp dụng hiệu ứng nhẹ cho Hero, tiêu đề section, Product Card và một số thành phần nổi bật.
Không lạm dụng animation gây rối mắt.
-Kết quả AI tạo ra:
AI tích hợp các file CSS cần thiết và thêm hiệu ứng chuyển động cho một số khu vực chính của website.
Nhận xét & Tinh chỉnh của SV:
Ban đầu hiệu ứng được áp dụng hơi nhiều nên tôi yêu cầu AI giảm bớt, chỉ giữ lại những hiệu ứng cần thiết để website mượt và dễ nhìn hơn.
-Lần 6: Kiểm tra Responsive
Prompt đã dùng:
Hãy kiểm tra responsive toàn bộ website MINI GT STORE.
Kiểm tra Desktop, Tablet và Mobile.
Đảm bảo Header, Hero, Product Grid, Button, hình ảnh và Footer không bị tràn hoặc mất cân đối.
Sử dụng CSS Media Query, không sử dụng JavaScript.
-Kết quả AI tạo ra:
AI điều chỉnh lại kích thước, khoảng cách và số cột của Product Grid theo từng kích thước màn hình.
Nhận xét & Tinh chỉnh của SV:
Website hiển thị ổn định hơn trên nhiều kích thước màn hình và không xuất hiện thanh cuộn ngang.
-Lần 7: Kiểm tra và hoàn thiện
Prompt đã dùng:
Hãy kiểm tra toàn bộ website MINI GT STORE lần cuối theo các yêu cầu:
- Semantic HTML5 đúng cấu trúc.
- Hạn chế <div> không cần thiết.
- CSS Variables được sử dụng.
- Layout sử dụng Flexbox/Grid.
- Responsive trên Desktop, Tablet, Mobile.
- Animate.css và AOS.css được tích hợp.
- Animation không quá nhiều.
- Không sử dụng JavaScript.
Nếu phát hiện lỗi, hãy sửa nhưng không thay đổi thiết kế tổng thể.
Kết quả AI tạo ra:
AI kiểm tra và hoàn thiện lại các phần HTML, CSS, responsive và animation.
-Nhận xét & Tinh chỉnh của SV:
Sau lần kiểm tra cuối, website đáp ứng các yêu cầu chính của đề bài và có giao diện hoàn chỉnh hơn.

-Lần 8: Mở rộng danh mục xe mới (Liberty Walk & Secret Chase) và nâng cấp hiệu ứng Pure CSS
Prompt đã dùng:
Hãy đọc kỹ lại web, bổ sung các mẫu xe mới từ thư mục image (Minigt_S15_LBWK, Minigt_Lambo_LBWK, Minigt_Lambo_GT3, Poprace_Lambo_Secret, Poprace_Supra_Secret, TH_LamboUltraman), bổ sung thêm nhiều hiệu ứng đẹp hơn nữa (Shimmer sweep, Secret card glow, Stock meter bar, Corner ribbons, Bảng so sánh 1:64, Secret Chase club) và mở rộng bố cục nội dung đầy đủ, logic nhất mà tuyệt đối không dùng JavaScript.
-Kết quả AI tạo ra:
AI đã bổ sung toàn bộ 12 mẫu xe vào grid sản phẩm, phân loại thành 7 danh mục lọc bằng CSS Radio Hack, xây dựng 12 Modal chi tiết bằng CSS :target, bổ sung các hiệu ứng Shimmer ánh sáng lướt qua card khi hover, thẻ Secret Chase ánh kim dạ quang, thanh khan hiếm stock level bar, bảng so sánh tiêu chuẩn kỹ thuật die-cast và phần giới thiệu Secret Chase 1/24. Toàn bộ website vận hành trơn tru với 100% HTML5 & Pure CSS3, không có bất kỳ dòng lệnh JavaScript nào.
-Nhận xét & Tinh chỉnh của SV:
Giao diện trở nên vô cùng phong phú, chuyên nghiệp đúng chất website của giới sưu tầm mô hình die-cast quốc tế, các hiệu ứng thị giác mượt mà và trực quan, đạt điểm tối đa cho môn Thiết Kế Web.

3. Đánh giá cá nhân về quá trình Vibe Coding
AI đã giúp bạn tiết kiệm thời gian ở phần nào nhất?
-AI giúp tôi tiết kiệm nhiều thời gian trong việc xây dựng cấu trúc HTML, viết CSS, tạo layout bằng Flexbox/Grid và chỉnh sửa giao diện responsive. Ngoài ra, AI hỗ trợ tôi nhanh chóng tìm và sửa các lỗi trong quá trình thiết kế.
Bài học rút ra khi đặt câu hỏi cho AI?
-Tôi nhận ra rằng Prompt càng cụ thể thì kết quả càng sát với yêu cầu. Thay vì yêu cầu AI làm lại toàn bộ website, tôi chia nhỏ thành từng bước như Semantic HTML, CSS Variables, Layout, UI/UX, Animation và Responsive.
Quan trọng nhất là phải kiểm tra kết quả của AI và tiếp tục đưa ra Prompt để chỉnh sửa, thay vì hoàn toàn phụ thuộc vào kết quả ban đầu.