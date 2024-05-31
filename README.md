
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>
     
      
  </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: space-between;
            max-width: 1000px;
            width: 100%;
            padding: 20px;
        }
        .left {
            flex: 1;
            margin-right: 50px;
        }
        .right {
            flex: 1;
            background-color: white;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        h1 {
            color: #1877f2;
            font-size: 48px;
        }
        .subtitle {
            font-size: 24px;
            color: #606770;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group input {
            width: 100%;
            padding: 15px;
            margin-top: 5px;
            font-size: 16px;
            border: 1px solid #dddfe2;
            border-radius: 6px;
        }
        .form-group button {
            width: 100%;
            padding: 15px;
            background-color: #1877f2;
            border: none;
            color: white;
            font-size: 18px;
            border-radius: 6px;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #165ec7;
        }
        .footer {
            text-align: center;
            margin-top: 20px;
            font-size: 12px;
            color: #606770;
        }
        .footer a {
            color: #1877f2;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left">
            <h1>Facebook</h1>
            <p class="subtitle">Facebook te ayuda a comunicarte y compartir con las personas que forman parte de tu vida.</p>
        </div>
        <div class="right">
            <form>
                <div class="form-group">
                    <input type="text" placeholder="Correo electrónico o número de teléfono">
                </div>
                <div class="form-group">
                    <input type="password" placeholder="Contraseña">
                </div>
                <div class="form-group">
                    <button type="submit">Iniciar sesión</button>
                </div>
                <div class="footer">
                    <a href="#">¿Olvidaste tu contraseña?</a> · <a href="#">Crear cuenta nueva</a>
                </div>
            </form>
        </div>
    </div>
</body>
</html>
