<!DOCTYPE html>

<html lang="en">
<head>
  <title>Document</title>
</head>
<body>

<html>
  <head>

 <body style="background-color:#FFFFCC;">
 
<h2>Добро пожаловать на наш сайт!</h2>
<p>Тут ви можете замовити будь-який парфум на ваш вибір </p>
<p style="font-size: 24px;">Будь ласка, запишіть свої дані для відправки парфуму</p>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Выбор пола</title>
</head>
<body>

    <label for="gender">Виберіть рід для замовлення:</label>
    <select id="gender" name="gender">
        <option value="male">Чоловікам</option>
        <option value="female">Жінкам</option>
    </select>


</body>
</html>

<form>
  <label for="fname">Прізвище:</label>
  <input type="text" id="fname" name="fname" pattern="[А-ЯЇІҐ][а-яії]{0,30}" title="Введіть українські літери"> <input type="submit" value="Перевірити"><br><br>
  
  <label for="name">Ім'я:</label>
  <input type="text" id="name" name="name" pattern="[А-ЯЇІҐ][а-яії]{0,30}" title="Введіть українські літери" required> <input type="submit" value="Перевірити"> <br><br>
  
   <label for="phone">Введіть ваш номер телефону:</label>
  <input type="phone" id="phone" name="phone" pattern="[+][0-9]{13}" title="Введіть номер у форматі +"> <input type="submit" value="Перевірити"><br><br>
 
   <label for="email">Введіть ваш email:</label>
  <input type="email" id="email" name="email"><br><br>
 
 <form>
 <label for="city">Оберіть місто:</label>
  <select id="city" name="city">
    <option value="city">Київ</option>
    <option value="city">Кривий Ріг</option>
    <option value="city" selected>Дніпро</option>
    <option value="city">Херсон</option>
    <option value="city">Харків</option>
  </select>
  </form>
  
  <p> не забудьте підтвердити замовлення, кнопка нижче </p>
  
  
  
  <html>
<head>
    <title>Кнопка підтвердження</title>
</head>
<body>

    <button onclick="confirmation()">Підтвердити замовлення</button>

    <script>
        function confirmation() {
            var result = confirm("Ви впевнені, що хочете підтвердити?");
            if (result) {
                alert("Дані підтверджені!");
               
            } else {
                alert("Відмінено.");
                
            }
        }
    </script>

</body>
</html>
  
 <p style="text-align: right;">замовлення здійснюється тільки особам старше 18 років &#128286;</p>
