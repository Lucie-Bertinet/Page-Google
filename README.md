# Page-Google
Premier projet THP
google.html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
  <link rel="stylesheet" type="text/css" href="style.css">
  <title>Google</title>
</head>
<body>

<div class="google-logo">
  <img class="logo" src="THP-GOOGLE/image/logo-google.png" alt="logo Google">
  
</div>

<div class="box">
  <a href="" class="loupe">
    <img src="THP-GOOGLE/image/logo-loupe.png" alt="logo loupe">
  </a>

  <input class="input-box" type="text" 
  placeholder="Effectuez une recherche sur Google ou saisissez une URL">

  <a href="" class="voix">
    <img src="THP-GOOGLE/image/logo-voix.png" alt="logo micro Google">
  </a>
</div>

<div class="button">
  <input type="button" class="btn" value="Recherche Google">
  <input type="button" class="btn" value="J'ai de la chance">
</div>
</body>
</html>


style.css
body
{
  padding: 0;
  margin: 0;
}

.box
{
  border: 0,1px solid black;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  padding: 10px;
  height: 30px;
  width: 500px;
  box-shadow: 1px 1px 5px black;
  border-radius: 40px;
}

.input-box
{
  margin-left: 15px;
  width: 420px;
  height: 25px;
  outline: none;
  background: transparent;
  border: 15px;
}

.loupe
{
  float: left;
  width: 30px;
  height: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.voix
{
  float: right;
  width: 30px;
  height: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.google-logo
{
  position: absolute;
  top: 50%
  left: 50%;
}

.logo
{
  justify-content: center;
  align-items: center;
  padding: 230%;
}

.button
{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.btn
{
  margin: 150px 10px 0 0;
  font-size: 15px;
  padding: 8px 15px;
  border: none;
  color: #6e6e6e;
  border-radius: 5px;
}

.btn:hover
{
  border: 1px solid #a4a4a4;
  border-radius: 5px;
}
