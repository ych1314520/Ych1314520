<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>联系 YCH</title>
<style>
  *{box-sizing:border-box}
  body{
    background:#0a0a0a;
    color:#fff;
    font-family:sans-serif;
    text-align:center;
    padding:40px 20px;
    margin:0;
    min-height:100vh;
    overflow:hidden;
  }

  h1{
    font-size:34px;
    margin-bottom:8px;
    letter-spacing:2px;
  }

  .sub{
    color:#888;
    font-size:15px;
    margin-bottom:60px;
  }

  .box{
    display:flex;
    flex-direction:column;
    align-items:center;
    gap:18px;
  }

  .btn{
    width:86%;
    max-width:360px;
    padding:22px 18px;
    border:0;
    border-radius:18px;
    font-size:20px;
    font-weight:700;
    color:#fff;
    cursor:pointer;
    opacity:0;
    transform:translateY(80px);
    animation:rise 0.8s ease forwards;
    transition:.15s;
  }

  .btn:active{
    transform:translateY(0) scale(.98);
  }

  .dy{
    background:linear-gradient(135deg,#fe2c55,#ff6a88);
    animation-delay:.25s;
  }

  .qq{
    background:linear-gradient(135deg,#12b7f5,#4fc3f7);
    animation-delay:.55s;
  }

  @keyframes rise{
    from{
      opacity:0;
      transform:translateY(80px);
    }
    to{
      opacity:1;
      transform:translateY(0);
    }
  }

  .tip{
    margin-top:36px;
    font-size:12px;
    color:#555;
    opacity:0;
    animation:fade 1s ease .9s forwards;
  }

  @keyframes fade{
    to{opacity:1}
  }
</style>
</head>
<body>

<h1>▞▛▖▜▝ ▞▙▛▖▜</h1>
<div class="sub">ych_123678 · 3797197884</div>

<div class="box">
  <button class="btn dy" onclick="openDouyin()">抖音主页</button>
  <button class="btn qq" onclick="openQQ()">QQ 资料卡</button>
</div>

<div class="tip">手机端点击自动唤起 App，未安装则跳转网页版</div>

<script>
function openDouyin(){
  location.href = 'https://v.douyin.com/SI-5KtAif4o/';
}

function openQQ(){
  location.href = 'mqq://card/show_pslcard?src_type=internal&version=1&uin=3797197884';
}
</script>

</body>
</html>
