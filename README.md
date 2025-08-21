<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Agendar Cita</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff9e6;
      padding: 20px;
    }

    h1 {
      color: #e63946;
      font-size: 28px;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .header a {
      color: #e63946;
      text-decoration: none;
      font-weight: bold;
    }

    .perfil {
      text-align: center;
      margin-top: 10px;
    }

    .perfil img {
      width: 50px;
      border-radius: 50%;
    }

    label {
      display: block;
      margin: 15px 0 5px;
      font-weight: bold;
    }

    input {
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 6px;
      background-color: #ffee58;
      font-size: 16px;
    }

    .btn {
      background-color: #e63946;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      margin-top: 20px;
    }

    .btn:hover {
      background-color: #d62828;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>Agendar Cita</h1>
    <a href="#">Ver Historial</a>
  </div>

  <div class="perfil">
    <img src="https://img.icons8.com/ios-filled/50/ff4081/user.png" alt="Perfil">
    <p>Perfil</p>
  </div>

  <form>
    <label for="fecha">Fecha</label>
    <input type="date" id="fecha" name="fecha" placeholder="Selecciona una fecha">

    <label for="hora">Hora</label>
    <input type="time" id="hora" name="hora" placeholder="Selecciona una hora">

    <button type="submit" class="btn">Reservar</button>
  </form>
</body>
</html>
