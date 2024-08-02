<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pousada em Juazeiro do Norte</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Pousada em Juazeiro do Norte</h1>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#map">Mapa</a></li>
                <li><a href="#contact">Contato</a></li>
                <li><a href="#gallery">Galeria</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h2>Bem-vindo à nossa pousada!</h2>
        <p>Aqui você encontrará conforto e qualidade em Juazeiro do Norte.</p>
        <!-- Adicione suas imagens e informações principais aqui -->
    </section>
    
    <section id="map">
        <h2>Localização</h2>
        <div id="map-container">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d12028.417044032695!2d-39.31556754579404!3d-7.213513851210689!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7b8e409c0f88fb%3A0xbfd5e9aa44a68ff!2sJuazeiro%20do%20Norte%2C%20CE!5e0!3m2!1spt-BR!2sbr!4v1694504510162!5m2!1spt-BR!2sbr"
                width="600"
                height="450"
                style="border:0;"
                allowfullscreen=""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contato</h2>
        <form action="mailto:seuemail@exemplo.com" method="post" enctype="text/plain">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>
    
    <section id="gallery">
        <h2>Galeria</h2>
        <!-- Adicione suas imagens aqui -->
    </section>
    
    <footer>
        <p>&copy; 2024 Pousada em Juazeiro do Norte. Todos os direitos reservados.</p>
        <!-- Adiciona o Google Translate -->
        <div id="google_translate_element"></div>
        <script type="text/javascript">
            function googleTranslateElementInit() {
                new google.translate.TranslateElement({
                    pageLanguage: 'pt',
                    layout: google.translate.TranslateElement.InlineLayout.SIMPLE
                }, 'google_translate_element');
            }
        </script>
        <script type="text/javascript" src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
    </footer>
</body>
</html>
