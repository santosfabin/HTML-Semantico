### **Seções comuns / Tags semântica**

- Cabeçalho `<header>`
    - O **`<header>`** é eficaz porque fornece uma identidade visual imediata ao site, ao apresentar a logo e o menu de navegação.
    - Ele ajuda os usuários a entenderem onde estão e como podem explorar o conteúdo do site.
    - **Exemplo prático**
        - Antes
            
            ```html
            <div id="logo">Logo</div>
            <nav>
                <ul>
                    <li><a href="#">Página Inicial</a></li>
                    <li><a href="#">Sobre</a></li>
                    <li><a href="#">Contato</a></li>
                </ul>
            </nav>
            ```
            
        - Depois
            
            ```html
            <header>
                <img src="logo.png" alt="Logo">
                <nav>
                    <ul>
                        <li><a href="#">Página Inicial</a></li>
                        <li><a href="#">Sobre</a></li>
                        <li><a href="#">Contato</a></li>
                    </ul>
                </nav>
            </header>
            ```
            

---

- Navegação `<nav>`
    - O **`<nav>`** é eficaz porque agrupa os links de navegação em um local específico, facilitando para os usuários encontrar e acessar diferentes partes do site. Ele melhora a experiência do usuário ao oferecer uma estrutura clara e organizada para a navegação.
    - **Exemplo prático**
        - Antes
            
            ```html
            <div class="menu">
                <a href="#">Página Inicial</a>
                <a href="#">Sobre</a>
                <a href="#">Contato</a>
            </div>
            ```
            
        - Depois
            
            ```html
            <nav>
                <ul>
                    <li><a href="#">Página Inicial</a></li>
                    <li><a href="#">Sobre</a></li>
                    <li><a href="#">Contato</a></li>
                </ul>
            </nav>
            ```
            

---

- Conteúdo principal `<main>`
    - O **`<main>`** é eficaz porque destaca o conteúdo principal da página, tornando-o mais acessível e relevante para os usuários. Ele ajuda a direcionar o foco do usuário para o conteúdo central da página, melhorando assim a usabilidade e a legibilidade.
    - **Exemplo prático**
        - Antes
            
            ```html
            <div id="conteudo">
                <h1>Título do Artigo</h1>
                <p>Conteúdo do artigo...</p>
            </div>
            ```
            
        - Depois
            
            ```html
            <main>
                <article>
                    <h1>Título do Artigo</h1>
                    <p>Conteúdo do artigo...</p>
                </article>
            </main>
            ```
            

---

- Conteúdo relacionado `<aside>`
    - O **`<aside>`** é eficaz porque permite incluir conteúdo relacionado de forma contextual e não intrusiva. Ele complementa o conteúdo principal da página, fornecendo informações adicionais ou relacionadas que podem ser úteis para os usuários.
    - Ele normalmente se encontra ao lado do conteúdo principal (na parte lateral da página).
    - **Exemplo prático**
        - Antes
            
            ```html
            <div id="barra-lateral">
                <h3>Artigos Relacionados</h3>
                <ul>
                    <li><a href="#">Artigo 1</a></li>
                    <li><a href="#">Artigo 2</a></li>
                    <li><a href="#">Artigo 3</a></li>
                </ul>
            </div>
            ```
            
        - Depois
            
            ```html
            <aside>
                <section>
                    <h3>Artigos Relacionados</h3>
                    <ul>
                        <li><a href="#">Artigo 1</a></li>
                        <li><a href="#">Artigo 2</a></li>
                        <li><a href="#">Artigo 3</a></li>
                    </ul>
                </section>
            </aside>
            ```
            

---

- Rodapé `<footer>`
    - O **`<footer>`** é eficaz porque oferece um local para informações adicionais, como informações do autor, direitos autorais e links úteis. Ele completa a experiência do usuário ao fornecer um ponto de partida para explorar mais conteúdo ou entrar em contato com o site.
    - Onde ficam as informações da parte de baixo da página.
        - Informações do autor
        - copyright
        - contato
        - sitemap
    - **Exemplo prático**
        - Antes
            
            ```html
            <div id="rodape">
                <p>Copyright © 2024 Nome do Site. Todos os direitos reservados.</p>
                <p><a href="#">Contato</a> | <a href="#">Sitemap</a></p>
            </div>
            ```
            
        - Depois
            
            ```html
            <footer>
                <p>Copyright © 2024 Nome do Site. Todos os direitos reservados.</p>
                <nav>
                    <ul>
                        <li><a href="#">Contato</a></li>
                        <li><a href="#">Sitemap</a></li>
                    </ul>
                </nav>
            </footer>
            ```
            

---
