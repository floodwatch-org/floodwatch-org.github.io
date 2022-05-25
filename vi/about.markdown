---
layout: page
title: About FloodWatch
lang: vi
lang-ref: about
---

<div class="post">
	<h1 class="pageTitle">FloodWatch là gì?</h1>
    <h1>Một cái nhìn sâu sắc hơn</h1>
    <p class="intro">FloodWatch là một ứng dụng di động tập trung vào dự báo và cảnh báo lũ lụt tại Thành phố Hồ Chí Minh và các thành phố khác trên khắp Việt Nam. Tận dụng cả dữ liệu nghiên cứu và do người dùng cung cấp, FloodWatch có thể xác định các khu vực có nguy cơ lũ lụt cao.</p>
    <img src="{{ '../floodwatchappdesign.png' }}" alt=""><br/>
    <h2>Công nghệ được sử dụng</h2>
	<ul>
  	<li>AWS Lambda để xử lý học máy và xử lý các yêu cầu</li>
  	<li>Dịch vụ cơ sở dữ liệu quan hệ AWS (RDS) để lưu trữ các bài đọc và dự đoán lịch sử theo vị trí</li>
  	<li>React Native cho ứng dụng dành cho người tiêu dùng</li>
	<li>Mapbox để hiển thị các lớp phủ với dữ liệu lũ lụt và báo cáo của người dùng trên giao diện bản đồ</li>
  	</ul>
    <h2>Đường ống dữ liệu</h2>
    <p>Đường ống dữ liệu là một chuỗi các bước xử lý dữ liệu để chuyển đổi dữ liệu từ dạng này sang dạng khác. Mô hình hiện tại tự động hóa việc lấy dữ liệu từ HEC-RAS thông qua phiên bản ảo được chia sẻ. Sau khi tiếp nhận, dữ liệu được tải lên máy chủ Amazon và được gửi tới MapBox. MapBox sau đó kết xuất dữ liệu lên các lớp phủ bản đồ mà sau đó có thể nằm gọn trên giao diện bản đồ mặt trước của chúng tôi trong ứng dụng.</p>
	<img src="{{ '../DataPipeline.PNG' }}" alt=""><br/>
</div>
