
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> TRỌNG DUY </title>
    <style>
		h1{
			display: none;
			}
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #FFDAB9, #ffffff); /* Xanh dương nhạt sang trắng */
        }
        .header {
            padding: 20px;
            text-align: center;
            background-color: #FFDAB9; /* Xanh dương nhạt */
            font-size: 2em;
            font-weight: bold;
            color: #333;
        }
        .content-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }
        .text-section {
            flex: 1;
            margin: 10px;
        }
        .image-section {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        img {
            max-width: 100%;
            max-height: 300px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .footer {
            background-color:#FFDAB9; /* Xanh dương nhạt */
            padding: 20px;
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #ccc;
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #FFDAB9; /* Màu xanh dương nhạt */
        }
		p {text-indent: 30px; /* Lùi đầu dòng 30px */
            font-family: 'Patrick Hand', sans-serif; /* Sử dụng phông Patrick Hand */
            font-size: 20px;               /* Kích thước chữ */
            color: #FFA500;               /* Màu chữ hồng dễ thương */}
    </style>
</head>
<body>

    <!-- Tiêu đề trang -->
    <div class="header"> TRẦN TRỌNG DUY</div>

    <!-- Hình bên trái cùng hàng với văn bản -->
    <div class="content-container">
        <div class="image-section">
            <img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/462644434_494027767023134_9100106116697837757_n.jpg?stp=dst-jpg_s640x640_tt6&_nc_cat=109&ccb=1-7&_nc_sid=0024fc&_nc_eui2=AeHlZvgeZXWQ260vM-lBbcGw_Oa_T7KjV3r85r9PsqNXeuoqIGrbTtMB-413i0AKR8wKuiJdwFkc7F9h9IohPYPM&_nc_ohc=OyV2P4asONQQ7kNvgG9ZMfP&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent.xx&oh=03_Q7cD1gGTHbkEewh7qF63VIjBcGzCmK9rcYOimpHFrI6oF5Cciw&oe=67B5F334" alt="Hình ảnh bên trái">
        </div>
        <div class="text-section">
            <h2>Giới thiệu bản thân </h2>
            <p>
            Chào mọi người, mình là Duy. Hiện tại mình đang là 1 CBT-er, và mình đặc biệt yêu thích âm nhạc và vẽ vời, đam mê chạy bộ và thường có thời gian rảnh thì sẽ vừa chạy bộ vừa tận hưởng không khí trong lành của thiên nhiên. Ngoài ra, mình rất quan tâm đến Graphic designer, mình đang có ý định sẽ theo học ngành nghề đó trong tương lai. Hiện tại mình sẽ cố gắng hết mình để đạt được mục tiêu đầu tiên chính là vào được ngôi trường mà mình mơ ước. Trong cuộc sống, mình sẽ luôn cố gắng học hỏi, phát triển bản thân và chia sẻ những điều tích cực với mọi người xung quanh.
			 </p>
   
        </div>
    </div>
    <!-- Footer với bảng -->
    <div class="footer">
        <h2>THÔNG TIN CÁ NHÂN </h2>
        <table>
            <thead>
                <tr>
					<th>Ngày sinh</th>
                    <th>Chiều cao</th>
                    <th> Cân nặng</th>
                    <th>Số điện thoại</th>
                    <th>Email</th>
                    <th>Cung hoàng đạo</th>
                    <th>Nickname</th>
                    <th>Liên hệ facebook</th>
                </tr>
            </thead>
            <tbody>
                <!-- 2 hàng -->
                <tr>
					<td>24/07/2007 </td>
                    <td>1,73m </td>
                    <td>60 kg</td>
                    <td>0939764810</td>
                    <td>trongduyhotro2007@gmail.com</td>
                    <td>Sư Tử</td>
                    <td>YuD</td>
                    <td><a href="https://www.facebook.com/duy.trong.3975?locale=vi_VN"> Trần Trọng Duy </a></td>
                </tr>
            </tbody>
        </table>
		<footer>
    <!-- Hoặc dùng JavaScript -->
    <a href="#" onclick="history.back(); return false;">Quay về trang trước</a>
		</footer>
    </div>

</body>
</html>
