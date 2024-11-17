# index-html
Pagino de site Sabores da Terra
<!DOCTYPE html> 
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sabores da Terra</title>
    <link rel="stylesheet" href="css/css_index.css">
    <style>
        .imagem-destaque {
            width: 100%; /* Ajuste para que a imagem de destaque ocupe toda a largura disponível */
            height: auto; /* Mantém a proporção da imagem */
        }
        .prato-item img {
            width: 100%; /* Imagens dos pratos em destaque menores */
            height: auto; /* Mantém a proporção das imagens dos pratos */
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <img src="images/logo.png" alt="Logo Sabores da Terra">
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Início</a></li>
                    <li><a href="menu.html">Nossos Pratos</a></li>
                    <li><a href="reservas.html">Reservas</a></li>
                    <li><a href="contacto.html">Contacte-Nos</a></li>
                </ul>
            </nav>
            <div class="theme-toggle">
                <label for="theme-select">Tema:</label>
                <select id="theme-select">
                    <option value="light">Claro</option>
                    <option value="dark">Escuro</option>
                </select>
            </div>
        </div>
    </header>
