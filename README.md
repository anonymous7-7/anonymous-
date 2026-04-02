<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Anonymous</title>

<style>
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, sans-serif;
  background: linear-gradient(180deg, #0a0a0a, #111);
  color: white;
  display: flex;
  justify-content: center;
}

/* شكل الموبايل */
.phone {
  width: 360px;
  min-height: 100vh;
  position: relative;
  overflow: hidden;
}

/* الخلفية */
.bg {
  position: absolute;
  width: 100%;
  height: 60%;
  background: radial-gradient(circle, #1a1a1a, #000);
  top: 0;
}

/* البروفايل */
.profile {
  position: relative;
  text-align: center;
  padding-top: 60px;
}

/* الصورة */
.avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin: auto;
  background: #222;
  box-shadow: 0 0 15px rgba(0,150,255,0.3);
}

/* الاسم */
.name {
  margin-top: 10px;
  font-size: 18px;
}

/* اللينك */
.link {
  font-size: 13px;
  color: #aaa;
}

/* الكارت */
.card {
  background: #111;
  margin: 20px;
  padding: 20px;
  border-radius: 20px;
  box-shadow: 0 0 10px rgba(0,150,255,0.15);
}

/* textarea */
textarea {
  width: 100%;
  border: none;
  border-radius: 15px;
  padding: 12px;
  background: #0a0a0a;
  color: white;
  resize: none;
}

/* زر */
button {
  margin-top: 10px;
  width: 100%;
  padding: 12px;
  border-radius: 15px;
  border: none;
  background: #0096ff;
  color: white;
  font-size: 15px;
  cursor: pointer;
  box-shadow: 0 0 10px rgba(0,150,255,0.4);
}

/* الرسائل */
.msg {
  background: #0a0a0a;
  padding: 12px;
  border-radius: 15px;
  margin-top: 10px;
  box-shadow: 0 0 6px rgba(0,150,255,0.2);
}

/* الشريط السفلي */
.bottom-bar {
  position: fixed;
  bottom: 0;
  width: 360px;
  background: #111;
  padding: 10px;
  border-top: 1px solid #222;
  display: flex;
  justify-content: space-around;
}

/* ايقونات */
.icon {
  width: 40px;
  height: 40px;
  border-radius: 12px;
  background: #0a0a0a;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 0 8px rgba(0,150,255,0.3);
}
</style>
</head>

<body>

<div class="phone">

  <div class="bg"></div>

  <!-- البروفايل -->
  <div class="profile">
    <div class="avatar"></div>
    <div class="name">@username</div>
    <div class="link">yourlink.com/u/123</div>
  </div>

  <!-- ارسال -->
  <div class="card">
    <textarea rows="3" placeholder="ابعت رسالة مجهولة..."></textarea>
    <button>إرسال</button>
  </div>

  <!-- الرسائل -->
  <div class="card">
    <div class="msg">انت شخص محترم 👌</div>
    <div class="msg">خليك زي ما انت ❤️</div>
  </div>

  <!-- شريط تحت -->
  <div class="bottom-bar">
    <div class="icon">🏠</div>
    <div class="icon">💬</div>
    <div class="icon">👤</div>
  </div>

</div>

</body>
</html>
