# ferdiancandrat.github.io
card profile
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Card Profile | Ferdian Candra</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="profile-card">
      <div class="card-header">
        <div class="pic">
          <img src="1 (1).JPG" alt="" />
        </div>
        <div class="name">FERDIAN CANDRA TRITAMA</div>
        <div class="desc">Freelancer | Bandung</div>
        <div class="sm">
          <a href="https://www.facebook.com/ferdiancandratritam" class="fab fa-facebook-f"></a>
          <a href="https://vt.tiktok.com/ZSd5KQjvj/" class="fab fa-tiktok"></a>
          <a href="https://www.instagram.com/ferdian.ct/" class="fab fa-instagram"></a>
          <a href="https://wa.me/+6283821547978" class="fab fa-whatsapp"></a>
        </div>
        <a href="https://forms.gle/PVHBr3i4sv9WiC669" class="contact-btn">Send Message</a>
      </div>
        </div>
      </div>
    </div>
  </body>
</html>

* {
  margin: 0;
  padding: 0;
  font-family: "Ubuntu", sans-serif;
  box-sizing: border-box;
  text-decoration: none;
}

body {
  height: 100vh;
  background: url(WhatsApp\ Image\ 2022-07-15\ at\ 21.05.19.jpeg) no-repeat center;
  background-size: cover;
  display: flex;
  align-items: center;
  justify-content: center;
}

.profile-card {
  width: 400px;
  text-align: center;
  border-radius: 8px;
  overflow: hidden;
}

.card-header {
  background: #2c3a47;
  padding: 60px 50px;
}

.pic {
  display: inline-block;
  padding: 5px;
  background: linear-gradient(50deg, #74b9ff, #e66767);
  margin: auto;
  border-radius: 10%;
  background-size: 200% 200%;
}

.pic img {
  width: 175px;
  height: 200px;
  border-radius: 10%;
}

.name {
  color: #f2f2f2;
  font-size: 20px;
  font-weight: 600;
  margin: 10px 0;
}

.desc {
  font-size: 15px;
  color: #756c6c;
}

.sm {
  display: flex;
  justify-content: center;
  margin: 20px 0;
}

.sm a {
  color: #f2f2f2;
  width: 56px;
  font-size: 22px;
  transition: 0.3s linear;
}

.sm a:hover {
  color: #e66767;
}

.contact-btn {
  display: inline-block;
  padding: 10px 50px;
  color: #ffffff;
  border: 2px solid #2fb968;
  border-radius: 6px;
  margin-top: 16px;
  transition: 0.3s linear;
}

.contact-btn:hover {
  background: #2fb968;
  color: #ffffff;
}

.card-footer {
  background: #3d486d;
  padding: 20px 10px;
}

.numbers {
  display: flex;
  align-items: center;
}

.item {
  flex: 1;
  text-transform: uppercase;
  font-size: 13px;
  color: #e66767;
}

.item span {
  display: block;
  color: #2c3a47;
  font-size: 30px;
}

.border {
  width: 1px;
  height: 30px;
  background: #b
