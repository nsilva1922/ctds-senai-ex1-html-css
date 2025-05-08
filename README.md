# ctds-senai-ex1-html-css
Exercícios para colocar em prática os conteúdos já visto em HTML e CSS

# Orientações
Tipo de fonte
Externa: Poppins

Cor
**Usar variáveis
:root{
    nome_variavel: valor;
}

Background-color
Body: #f9f9f9
Header: #1f2937
.card: white
footer: # 1f2937

Color
Body: #333
Header: white
.preco: #1f2937
footer: white

Tamanho da fonte
h1: 2rem
.card h2: 1.2rem
.card p: 0.95rem

main
padding: 20px;
max-width: 1200px;
margin: auto;

.produtos
display: flex;
flex-wrap: wrap;

.card
border: 1px solid #ddd;
border-radius: 10px;
box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
width: 300px;
padding: 15px;
display: flex;
flex-direction: column;
align-items: center;
transition: transform 0.2s ease-in-out;

.card:hover
transform: scale(1.03);


Media querie
@media (max-width: 600px) {
    .card {
        width: 90%;
    }

    h1 {
        font-size: 1.5rem;
    }
}



