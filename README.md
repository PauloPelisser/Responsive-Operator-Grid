# 🚀 Responsive Operator Grid

Interface responsiva desenvolvida com **HTML5 e CSS3**, utilizando **CSS Grid** e **Media Queries** para adaptação em diferentes tamanhos de tela.

---

## 📖 Sobre o projeto

O **Responsive Operator Grid** simula um pequeno banco de dados visual de operadores, exibindo informações em formato de cartões (cards) com layout moderno e adaptável.

O projeto foi criado com foco no aprendizado e prática de conceitos essenciais de **desenvolvimento front-end**, principalmente responsividade.

---

## 🎯 Objetivos

- Praticar estruturação com HTML semântico  
- Aplicar CSS Grid na construção de layouts  
- Implementar responsividade com Media Queries  
- Criar uma interface simples, limpa e funcional  

---

## 🛠️ Tecnologias utilizadas

- HTML5  
- CSS3  

---

## 📱 Responsividade

O layout se adapta automaticamente conforme o tamanho da tela:

| Dispositivo | Layout |
|------------|--------|
| Mobile     | 1 coluna |
| Tablet     | 2 colunas |
| Desktop    | 3 colunas |

---

## 💡 Funcionalidades

- Grid responsivo com CSS Grid  
- Cards com efeito hover  
- Imagens fluidas  
- Layout centralizado e adaptável  

---

## 📂 Estrutura do projeto

```
📁 responsive-operator-grid
│-- index.html
│-- styles.css
```

---

## 🧩 Trecho de código (Responsividade)

```css
/* Tablet */
@media(min-width:768px){
    .grid-galeria{
        grid-template-columns: repeat(2, 1fr);
    }
}

/* Desktop */
@media(min-width: 1024px){
    .grid-galeria{
        grid-template-columns: repeat(3, 1fr);
    }
}
```

---

## 🎨 Layout

O projeto utiliza um tema escuro com destaque em verde neon, criando uma identidade visual moderna e tecnológica.

---

## 📌 Possíveis melhorias

- Integração com JavaScript  
- Consumo de API para dados dinâmicos  
- Animações mais avançadas  
- Filtro e busca de operadores  

---

## 👨‍💻 Autor

**Paulo Henrique Peres Pelisser**

---

## 📬 Contato

Se quiser trocar ideias ou colaborar em projetos, fique à vontade para se conectar comigo no LinkedIn.
