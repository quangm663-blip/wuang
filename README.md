<!DOCTYPE html>
<html>
<head>
<style>

/* Nền toàn trang */
body{
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #ff9a9e, #fad0c4);
    text-align: center;
    margin: 0;
    padding: 0;
}

/* Khung chính */
.container{
    background: white;
    width: 80%;
    margin: 40px auto;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.3);
}

/* Nút đẹp */
button{
    padding: 10px 20px;
    border: none;
    border-radius: 8px;
    background: #ff6f61;
    color: white;
    font-weight: bold;
    cursor: pointer;
    margin: 5px;
    transition: 0.3s;
}

button:hover{
    background: #ff3b2e;
    transform: scale(1.1);
}

/* Ảnh */
img{
    margin: 15px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

/* Quảng cáo */
#adBox{
    margin-top: 30px;
    padding: 20px;
    background: #fff3cd;
    border-radius: 10px;
}
body.dark{
    background: #121212;
    color: white;
}

body.dark .container{
    background: #1e1e1e;
}

body.dark button{
    background: #444;
}

body.dark #adBox{
    background: #333;
}
</style>

</head>

<body>

<div class="container">
    <button onclick="document.body.classList.toggle('dark')">
🌙 / ☀ Đổi nền
</button>

<h2>Những thứ JS làm với HTML</h2>

<button onclick="document.getElementById('myImage').src='OIP.webp'">
Image 1
</button>

<button onclick="document.getElementById('myImage').src='OIP.jpg'">
Image 2
</button>

<br>

<img id="myImage" src="OIP.webp" width="200">

<div id="adBox">
    

<h3>Quảng cáo</h3>

<a href="https://surl.li/kruyyb" target="_blank">
    <img src="tho.jpg" width="300">
</a>

<br>

<button onclick="document.getElementById('adBox').style.display='none'">
Ẩn quảng cáo
</button>
<h4>trang web do nhóm 9. cụ thể là Quang và AI làm :))</h4>
</div>

</div>

</body>
</html>
