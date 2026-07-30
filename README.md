# Projeto Social

Este é um projeto front-end simples desenvolvido com **HTML5** e **CSS3** que simula a interface de um smartphone em uma página web. O objetivo principal é exibir de forma interativa os links e perfis de redes sociais de um usuário (ou projeto) dentro de um dispositivo móvel virtual. 

## 💻 Sobre o Projeto

A interface conta com a carcaça de um "smartphone" perfeitamente centralizada na tela, com um plano de fundo estilizado. Ao lado do dispositivo, há um menu flutuante com ícones que representam diversas redes sociais. 

O grande diferencial deste projeto é a navegação: quando o usuário clica em algum dos ícones de rede social, o conteúdo exibido na tela do smartphone é alterado dinamicamente. Isso é feito sem o uso de JavaScript, utilizando apenas o atributo `target` nas tags de âncora (`<a>`), apontando para um elemento `<iframe>` integrado na tela do celular.

As telas disponíveis na aplicação incluem:
- **Home** (Tela inicial do dispositivo)
- **YouTube**
- **GitHub**
- **Instagram**
- **Twitter / X**
- **Facebook**

## 🚀 Tecnologias Usadas

O projeto foi construído inteiramente com tecnologias web fundamentais, focando em estruturação e estilização:

- **HTML5**: Utilizado para criar a marcação estrutural e semântica das páginas. O elemento `<iframe>` foi essencial para criar a navegação interna dentro do celular de forma nativa.
- **CSS3**: Responsável por todo o visual da aplicação. Foi utilizado para posicionamento absoluto/relativo, estilização de imagens, criação de efeitos de transição (hover), aplicação de sombras (`box-shadow`) nos ícones, e para integrar a imagem do mockup do smartphone como um fundo (`background-image`).

## 📂 Estrutura do Projeto

- `index.html`: Arquivo raiz da aplicação. Contém o layout principal, o layout do celular e os botões do menu.
- `pag-*.html`: Arquivos secundários (`pag-home.html`, `pag-github.html`, etc.) que representam as "telas" individuais exibidas dentro do iframe quando clicadas.
- `estilos/style.css`: Arquivo contendo todas as regras de estilização visual para unificar a identidade visual do projeto.
- `imagens/`: Diretório que armazena os recursos gráficos, incluindo o frame do iPhone, ícones das redes sociais e texturas de fundo.

## 💡 Como executar

Por se tratar de um projeto puramente estático (HTML e CSS), não é necessária nenhuma instalação ou ambiente complexo.

1. Faça o download ou clone a pasta do projeto para o seu computador.
2. Navegue até o diretório do projeto.
3. Dê um duplo clique no arquivo `index.html` para abri-lo em qualquer navegador web (Google Chrome, Firefox, Edge, etc.).
4. Clique nos ícones laterais e interaja com a interface!
