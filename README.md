<!-- ========== BẮT ĐẦU TRANG ========== -->
<!DOCTYPE html>
<html> 
  <head> 
    <meta name="vietport"="with=device=width, initial-scale=1.0">
    <title>Huỳnh Hoàng Quân</title>
  </head>
  <body>
        <style> 
          /* Nền cho trang */
    body {
    font-family: Arial, sans-serif; 
        }
        /* TODO: thêm mấy hiệu ứng con bò đi */
      .container { 
        display: flex;
        justify-content: center;
        align-items: center;
        height: 150px;
        border: 1px solid black; 
        transition: all 0.5s ease;
        background-color: blue; 
        animation: blink 1s infinite;
      }
      .container:hover { 
        background-color:red;
        text-decoration: underline; 
        transform: translateX(20px)
      } 

      button:hover { 
        background-color: orange;
        cursor: pointer; 
      }
      .box { 
        background-color: #4CAF50;
        color: white; 
        padding: 20px;
        margin: 10px; 
        border-radius: 20px; 
        box-shadow: 3px 3px 10px rgba(0,0,0,0.3); 
        border: 1px solid black; 
        position: relative;
        animation: moveUpDown 1s infinite alternate; 
      } 
    @keyframes blink { 
      0%, 100% { opacity: 1;} 
      50% {opacity: 0;} 
    }
    @keyframes moveUpDown {
     0% { 
       top: 0px; 
     } 
     100% { 
       top: 100px;
     }
     }
    </style>
    <h1 style="text-align: center;">CÁCH ĐỂ COI YOUTUBE</h1>
    <div class="container">
    <div class="box"><button><a href="https://teamwater.org/">Donate</a></button></div>
    </div>
    <p style="color:red; font-size:20px;">Tôi đói lắm rồi</p> 
 <!-- form điền -->
    <form>
      <label>Họ tên:</label><br> 
      <input type="text" placeholder="Nhập họ và tên:"><br><br>
      
      <label>Email:</label><br>
      <input type="text" placeholder="Nhập địa chỉ email:"><br><br> 
      <button>Gửi</button>
    </form>
    <hr>
    <br>
    <h2 style="text-align:center">Các bước coi youtube</h2>
  <!-- liệt kê có đánh số -->
    <ol>
      <li>Bước 1: Bật máy tính</li>
      <li>Bước 2: Mở trình duyệt</li>
      <li>Bước 3: Mở youtube</li>
    </ol>
    <a href="https://www.youtube.com/">Truy cập vào youtube</a>
    <img src="https://tse1.mm.bing.net/th/id/OIP.-h_BHZiZFLjHQYT__rMqpwHaE6?rs=1&pid=ImgDetMain&o=7&rm=3" width="200">
  <hr>
  <h1 style="text-align:center">Admin website</h1>
 <!-- liệt kê không đánh số -->
    <ul> 
      <li>Minh Béo</li>
      <li>Michel Jackson</li>
      <li>Huỳnh Hoàng Quân</li>
    </ul>
    <hr>
  </body>
</html>
