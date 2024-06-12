<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Login</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="login-container">
        <h2>Logada</h2>
        <form action="/login" method="POST">
            <input type="text" name="username" placeholder="Nome de usuário" required>
	<br>
            <input type="password" name="password" placeholder="Senha" required>
	<br>
            <input type="submit" value="Entrar">
        </form>
    </div>
</body>
</html>
