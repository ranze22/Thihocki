<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hồ Sơ Phạm Quý Dương</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #d8c8a6; /* Màu be nâu nhạt */
            color: #4a4a4a;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        header {
            width: 100%;
            background-color: #d8c8a6; /* Nền màu be nâu */
            color: #4a4a4a;
            padding: 40px 0;
            text-align: center;
            font-size: 1.2rem;
            font-weight: 700;
            border-bottom: 4px solid #b69f7a; /* Màu be nâu đậm */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .container {
            width: 90%;
            max-width: 1200px;
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
            margin-top: 40px;
            padding: 30px;
            background-color: white;
            border-radius: 30px;
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.1);
        }

        .profile-info {
            flex: 1 1 40%;
            background-color: #f5f1e1; /* Nền màu be nâu nhạt hơn */
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .profile-info img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 6px solid #b69f7a; /* Viền màu be nâu đậm */
            margin-bottom: 20px;
            object-fit: cover;
        }

        .profile-info h2 {
            font-size: 1.8rem;
            color: #8c6d3d; /* Màu be nâu đậm */
            margin: 10px 0;
        }

        .info-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background-color: #f5f1e1;
            border-radius: 10px;
        }

        .info-table th, .info-table td {
            padding: 15px;
            text-align: left;
            font-size: 1.1rem;
            color: #4a4a4a;
            border-bottom: 1px solid #b69f7a;
            border-top: 1px solid #b69f7a;
        }

        .info-table th {
            background-color: #b69f7a; /* Màu be nâu đậm cho header */
            color: white;
        }

        .preferences-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background-color: #f5f1e1;
            border-radius: 10px;
        }

        .preferences-table th, .preferences-table td {
            padding: 12px;
            text-align: left;
            font-size: 1.1rem;
            color: #4a4a4a;
            border-bottom: 1px solid #b69f7a;
            border-top: 1px solid #b69f7a;
        }

        .preferences-table th {
            background-color: #b69f7a;
            color: white;
        }

        .preferences-table td {
            word-wrap: break-word;
            width: 50%;
        }

        .right-column {
            flex: 1 1 55%;
            background-color: #f5f1e1; /* Nền màu be nâu nhạt hơn */
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .right-column h2 {
            font-size: 1.6rem;
            color: #8c6d3d; /* Màu be nâu đậm */
            margin-bottom: 20px;
        }

        video {
            width: 100%;
            max-width: 700px;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            background-color: #fff;
        }

        footer {
            margin-top: 50px;
            background-color: #b69f7a; /* Nền màu be nâu đậm */
            color: white;
            padding: 20px;
            width: 100%;
            text-align: center;
            font-size: 1rem;
            border-radius: 20px 20px 0 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Phạm Quý Dương</h1>
    </header>

    <div class="container">
        <!-- Thông tin cá nhân -->
        <div class="profile-info">
            <img src="https://www.dropbox.com/scl/fi/x8z5mjnwje43m50unr3zb/IMG_1044.jpeg?rlkey=c2068dwbats40wcjotqj2aetj&st=mf3r4l3g&dl=0" alt="Ảnh Đại Diện">
            <h2>Thông Tin Cá Nhân</h2>
            <table class="info-table">
                <tr>
                    <th>Ngày Sinh</th>
                    <td>22/5/2007</td>
                </tr>
                <tr>
                    <th>Quê Quán</th>
                    <td>Đông Trung, Tiền Hải, Thái Bình</td>
                </tr>
                <tr>
                    <th>Trường</th>
                    <td>THPT Hòn Gai</td>
                </tr>
                <tr>
                    <th>Lớp</th>
                    <td>12B3</td>
                </tr>
            </table>

            <h2>Sở Thích & Sở Ghét</h2>
            <table class="preferences-table">
                <tr>
                    <th>Sở Thích</th>
                    <th>Sở Ghét</th>
                </tr>
                <tr>
                    <td>Chơi game, ngủ, đi chơi</td>
                    <td>Học, ăn các loài rau đắng hoặc nhớt</td>
                </tr>
            </table>

            <h2>Kỹ Năng</h2>
            <p>Chơi game âm nhạc</p>

            <h2>Nghề Nghiệp Tương Lai</h2>
            <p> Marketing, Digital Marketing</p>
        </div>

        <!-- Video Section -->
        <div class="right-column">
            <h2>Dưới đây là video giới thiệu</h2>
            <iframe src="https://youtu.be/sGDajJ2T4OY?si=Zvftqo-wGzvm8Tag" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>

    <footer>
        <p>Hồ sơ Phạm Quý Dương</p>
    </footer>
</body>
</html>
