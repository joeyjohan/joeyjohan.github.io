<!DOCTYPE html>
<html>
<head>
<title>HackAThon</title>
<style>
body {
  background-color: white;
  text-align: center;
  color: #112222;
  font-family: Arial, Helvetica, sans-serif;
}
.textbox {
	background-color: #112222;
    border: white;
    color: white;
    padding: 50px;
    border-radius: 20%;
    text-align: left;
    text-decoration: none;
    display: inline-block;
    font-size: 15px;
    margin: 4px 2px;
    cursor: pointer;
}
.button {
	background-color: none;
    border: white;
    color: white;
    padding: 15px;
    border-radius: 20%;
    text-align: center;
    text-decoration: underline;
    display: inline-block;
    font-size: 15px;
    margin: 4px 2px;
    cursor: pointer;
      }
@keyframes blinker {
  from { opacity: 1.0; }
  to { opacity: 0.0; }
}

.waitingForConnection {
  animation-name: blinker;
  animation-iteration-count: infinite;
  animation-timing-function: cubic-bezier(0.5, 0.5, 0.3, 0.3);
  animation-duration: 1.0s;
}
body {
background-image: url("https://media.istockphoto.com/photos/interrogation-room-with-chairs-and-table-picture-id497202483?k=20&m=497202483&s=612x612&w=0&h=gVTYucTpDw4JsLOKs5PSZQRz9KPzwHiuRDdnvV64f88=");
background-repeat: no-repeat;
background-size: 100%;
}
.container {
    column-width: 30;
    column-rule: 1px solid rgb(75, 70, 74);
}

</style>
</head>
<body>
<br><br><br><br>
<div class ="waitingForConnection">
	<h1>HackAThon</h1>
</div>

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<a href="First link.html" class="button">Escape?</a>

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<h2>Find the Secret Passwords</h2>
<div class = "container">
	<div class = "textbox">
	<p>Look carefully at the text. The<br>  password could be hidden among the words.</p>
    </div>
    <div class = "textbox">
	<p>The password you are looking for can <br> sometimes be found within the code itself.</p>
    </div>
    <div class = "textbox">
	<p>You might have to play a game and <br> see what you password comes out of that.</p>
    </div>
</div>
</body>
</html>
