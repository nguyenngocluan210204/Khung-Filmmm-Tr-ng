# Khung-Filmmm-Tr-ng<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Finndei Frame</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        h1 {
            text-align: center;
            font-size: 2rem;
            margin: 20px 0;
            color: #e0e0e0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #1e1e1e;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.5); /* Đổ bóng màu trắng */
        }

        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
            color: #e0e0e0;
        }

        input[type="file"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #444;
            border-radius: 5px;
            background-color: #333;
            color: #fff;
        }

        button {
            display: block;
            width: 100%;
            padding: 10px;
            background-color: #007acc;
            color: #fff;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #005f99;
        }

        .results img {
            max-width: 100%;
            margin-top: 20px;
            border-radius: 10px;
        }

        .results {
            text-align: center;
        }
    </style>
</head>
<body>
    <h1>Finndei Frame</h1>
    <div class="container">
        <label for="upload-images">Tải ảnh lên:</label>
        <input type="file" id="upload-images" accept="image/*" multiple>

        <label for="upload-frames">Tải khung lên:</label>
        <input type="file" id="upload-frames" accept="image/*" multiple>

        <button id="render-btn">Xử lý ảnh</button>

        <div class="results" id="results"></div>
    </div>
</body>
</html>
bât
