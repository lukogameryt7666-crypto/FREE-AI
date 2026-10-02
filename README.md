<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Naruto AI</title>

<style>
*{box-sizing:border-box;margin:0;padding:0}

body{
    min-height:100vh;
    font-family:Arial,sans-serif;
    color:white;
    background:
      radial-gradient(circle at 20% 10%,#ff7a0025,transparent 30%),
      radial-gradient(circle at 80% 80%,#ff4d0025,transparent 30%),
      #070707;
}

header{
    height:70px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:0 6%;
    background:#0b0b0b;
    border-bottom:1px solid #252525;
}

.logo{
    font-size:25px;
    font-weight:900;
    color:#ff7a00;
}

.logo span{
    color:white;
}

.owner{
    color:#999;
    font-size:14px;
}

.hero{
    text-align:center;
    padding:55px 20px 25px;
}

.badge{
    display:inline-block;
    padding:8px 15px;
    border:1px solid #ff7a00;
    border-radius:30px;
    color:#ff9d45;
    margin-bottom:18px;
    font-size:13px;
}

h1{
    font-size:clamp(45px,9vw,80px);
    margin-bottom:15px;
}

.orange{
    color:#ff7a00;
}

.hero p{
    color:#aaa;
    max-width:650px;
    margin:auto;
    line-height:1.6;
}

.chat{
    width:min(950px,94%);
    margin:30px auto;
    border:1px solid #292929;
    border-radius:22px;
    overflow:hidden;
    background:#101010;
    box-shadow:0 20px 70px #000;
}

.chatTop{
    padding:18px 22px;
    border-bottom:1px solid #292929;
    display:flex;
    align-items:center;
    gap:12px;
}

.dot{
    width:10px;
    height:10px;
    border-radius:50%;
    background:#22c55e;
    box-shadow:0 0 12px #22c55e;
}

.chatTop small{
    color:#777;
}

.messages{
    height:420px;
    overflow-y:auto;
    padding:22px;
}

.msg{
    max-width:82%;
    padding:14px 17px;
    border-radius:17px;
    margin-bottom:15px;
    line-height:1.55;
    white-space:pre-wrap;
}

.ai{
    background:#1b1b1b;
    border:1px solid #292929;
}

.user{
    margin-left:auto;
    background:linear-gradient(135deg,#ff7a00,#ff3d00);
}

.inputBox{
    display:flex;
    gap:10px;
    padding:16px;
    border-top:1px solid #292929;
}

input{
    flex:1;
    min-width:0;
    padding:15px;
    border-radius:14px;
    border:1px solid #333;
    background:#080808;
    color:white;
    outline:none;
    font-size:15px;
}

input:focus{
    border-color:#ff7a00;
}

button{
    border:0;
    border-radius:14px;
    padding:0 23px;
    background:#ff6a00;
    color:white;
    font-weight:bold;
    cursor:pointer;
}

button:hover{
    background:#ff8128;
}

.info{
    text-align:center;
    padding:
