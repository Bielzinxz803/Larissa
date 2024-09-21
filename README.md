# Página Romântica Interativa

Este projeto é uma página romântica interativa desenvolvida com HTML, CSS e JavaScript. A página foi criada para expressar sentimentos de amor, com transições suaves, efeitos de pétalas caindo, e mensagens reveladas gradualmente, culminando em uma surpresa com uma mensagem final.

## Funcionalidades

- **Efeitos de pétalas caindo**: Utiliza animações CSS para criar um efeito visual delicado de pétalas caindo sobre a página, tanto na primeira quanto na segunda página.
- **Revelação gradual de mensagens**: A primeira página revela, progressivamente, mensagens de carinho ao clicar em um botão, criando suspense e aumentando a curiosidade.
- **Transição para uma segunda página**: No final da sequência de mensagens, um botão leva a uma segunda página com uma mensagem especial e um efeito de cursor piscando.
- **Design Responsivo**: A página está otimizada para diferentes tamanhos de tela, garantindo uma boa experiência tanto em dispositivos móveis quanto em desktop.
  
## Estrutura do Projeto

### Arquivos Principais

1. `index.html`: Página inicial que contém a introdução romântica com revelações de texto e um botão final que leva à segunda página.
2. `surpresa.html`: Segunda página que exibe a mensagem romântica final com animações e um efeito de cursor piscando.
3. `README.md`: Este arquivo, explicando o funcionamento do projeto.

### Como Funciona

- **Animações CSS**: As pétalas caindo e as transições de opacidade para as mensagens são implementadas via CSS, utilizando keyframes para animar o movimento e a rotação.
- **Interatividade com JavaScript**: JavaScript é utilizado para controlar a exibição das mensagens na primeira página, garantindo que elas apareçam uma a uma à medida que o usuário clica no botão.
- **Transição entre páginas**: A transição entre a primeira e a segunda página é feita com um simples redirecionamento para o arquivo `surpresa.html` ao clicar no botão "Uma Surpresa Te Espera!".

## Estrutura de Pastas
📁 /projeto-romantico ├── index.html # Página inicial com revelação de mensagens ├── surpresa.html # Segunda página com mensagem romântica final └── README.md # Explicação do projeto


## Como Usar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em seu navegador.
3. Na primeira página, clique no botão para revelar as mensagens uma a uma.
4. Ao final, clique no botão "Uma Surpresa Te Espera!" para acessar a segunda página com uma mensagem especial.

## Tecnologias Utilizadas

- **HTML5**: Estruturação das páginas.
- **CSS3**: Estilos e animações.
- **JavaScript**: Manipulação de eventos e interatividade.

## Personalização

- Para modificar as mensagens reveladas, edite o conteúdo de texto dentro do arquivo `index.html`, dentro das divs de mensagem com os IDs `message1`, `message2`, etc.
- Para alterar a mensagem final, edite o arquivo `surpresa.html`.
- Para ajustar o design das pétalas ou a animação, modifique o CSS nos arquivos correspondentes.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir *issues* ou enviar *pull requests*.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
