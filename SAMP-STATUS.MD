-- Options-- 
Part 1: Tạo Trang Index.php. 

Code HTML:
`<html> 
<head>
        <title>Your title</title>
</head>
        <h1>HTML.</h1>
        <p>Xin chào đây là trang hiển thị status của server samp</p>
       
        <form action="signature.php" method="get"> <!-- Khi bạn nhấp vào nút "Submit", thông tin này sẽ được gửi đến trang "signature.php". Nếu bạn đang sử dụng một trang php khác, bạn cần thay đổi "signature.php" thành tệp bạn đã gọi nó. -->
        Playername: <input type="text" name="player_name"><br>  <!--Đây là một Object nhỏ sẽ lấy username của server. -->
       <input type="Submit"> <!-- Đây là nút 'send'  button-->
       </form>


</body>
</html>`
