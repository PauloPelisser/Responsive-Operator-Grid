📊 Banco de Dados Operadores (Responsive Grid)

Projeto simples em HTML + CSS com foco em layout responsivo utilizando Media Queries e CSS Grid. A aplicação exibe cartões de operadores com imagens e descrições, adaptando automaticamente o layout conforme o tamanho da tela.

🚀 Demonstração

O layout se adapta em três formatos:

📱 Mobile → 1 coluna
📱 Tablet → 2 colunas
💻 Desktop → 3 colunas
🧠 Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de praticar:

Estruturação semântica com HTML
Estilização com CSS
Uso de CSS Grid
Aplicação de Media Queries
Criação de layouts responsivos
🛠️ Tecnologias Utilizadas
HTML5
CSS3
📂 Estrutura do Projeto
📁 projeto
│-- index.html
│-- styles.css
💡 Funcionalidades
Layout em grade responsiva
Cards com efeito hover
Imagens fluidas
Design adaptável para diferentes dispositivos
🎨 Responsividade

O projeto utiliza Media Queries para adaptar o layout:

/* Tablet */
@media(min-width:768px){
    grid-template-columns: repeat(2, 1fr);
}

/* Desktop */
@media(min-width: 1024px){
    grid-template-columns: repeat(3, 1fr);
}
🖼️ Estrutura dos Cards

Cada operador é representado por um card contendo:

Imagem (gerada via Picsum)
Codinome
Descrição da especialidade

Exemplo:

<article class="card-operador">
    <img class="imagem-fluida">
    <div class="card-info">
        <h2>Condinome</h2>
        <p>Descrição</p>
    </div>
</article>
🎯 Aprendizados

Durante o desenvolvimento, foram reforçados conceitos como:

Mobile First
Organização de layout com Grid
Boas práticas de CSS (reset, responsividade, reutilização de classes)
📌 Possíveis Melhorias
Adicionar mais operadores dinamicamente
Implementar animações mais avançadas
Integrar com JavaScript
Tornar os dados dinâmicos (API ou banco de dados)
👨‍💻 Autor

Paulo Henrique Peres Pelisser
