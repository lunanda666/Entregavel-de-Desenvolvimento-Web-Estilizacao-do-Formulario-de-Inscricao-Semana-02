# 🎨 Desenvolvimento Web — Semana 02

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte do **Entregável de Desenvolvimento Web – Semana 02**, com o objetivo de finalizar a estilização do formulário de inscrição do blog.

Nesta etapa, foram aplicados conceitos de **CSS e Flexbox** para criar um formulário mais organizado, agradável visualmente e com melhor usabilidade.

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3
* Flexbox

## 📁 Estrutura do projeto

```text
Semana02/
├── index.html
├── style.css
└── README.md
```

## 🎨 Estilização do formulário

O formulário recebeu uma área própria com largura máxima, espaçamento interno e uma cor de fundo diferente do restante da página.

Foram utilizados recursos de CSS como:

* `max-width`
* `padding`
* `background-color`
* `border`
* `border-radius`
* `font-size`
* `gap`

## 📐 Uso do Flexbox

O Flexbox foi utilizado para organizar os elementos do formulário de maneira vertical e facilitar o espaçamento entre os campos.

```css
form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}
```

Também foi aplicado o Flexbox para organizar os campos de **nome e e-mail lado a lado**, como parte do bônus da atividade:

```css
.dados-pessoais {
    display: flex;
    justify-content: space-between;
    gap: 20px;
}
```

## 📝 Campos do formulário

Os elementos `<label>`, `<input>` e `<select>` receberam estilos próprios para melhorar a aparência e a usabilidade do formulário.

Os campos possuem:

* Espaçamento interno;
* Bordas;
* Cantos arredondados;
* Tamanho de fonte adequado;
* Destaque visual quando selecionados.

## 🖱️ Botão de envio

O botão de envio foi estilizado para se destacar visualmente na página.

Foram aplicadas propriedades como:

```css
button {
    background-color: #4c0059;
    color: #ffffff;
    padding: 12px 20px;
    cursor: pointer;
}
```

Também foi adicionado um efeito `:hover` para fornecer um retorno visual quando o usuário passa o cursor sobre o botão.

## 📱 Responsividade

Foi adicionada uma regra de mídia para adaptar o layout a telas menores.

Em dispositivos com largura reduzida, os campos de nome e e-mail passam a ficar um abaixo do outro, facilitando o preenchimento em dispositivos móveis.

## 🎯 Objetivos da atividade

* Praticar estilização de formulários com CSS;
* Utilizar propriedades do Flexbox;
* Organizar campos de formulário de maneira eficiente;
* Aplicar espaçamento, bordas e cores;
* Criar um botão com destaque visual e interação;
* Melhorar a usabilidade da página;
* Desenvolver uma interface mais organizada e visualmente agradável.

## 👨‍💻 Autor

**Lunanda Rebeca**

Projeto desenvolvido para a disciplina de **Desenvolvimento Web** — CEUMA, 2026.
