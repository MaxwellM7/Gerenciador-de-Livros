# Gerenciador de Livros 📚

Este é um projeto de **Gerenciador de Livros** desenvolvido em **React**, que permite aos usuários adicionar, remover e categorizar livros em três seções: "Lendo", "Pretende Ler" e "Já Lido". Além disso, o projeto oferece uma funcionalidade de alternância de tema entre **modo claro** e **modo escuro**.

## Funcionalidades

### 1. **Adicionar Livro**
- O usuário pode adicionar um livro inserindo o nome e selecionando a categoria (Lendo, Pretende Ler, Já Lido).
- O livro é adicionado à categoria escolhida e exibido na lista correspondente.

### 2. **Remover Livro**
- O usuário pode remover um livro clicando em seu nome na lista correspondente. Ao clicar, o livro é removido da categoria em que foi adicionado.

### 3. **Categorias de Livros**
- **Lendo**: Mostra os livros que o usuário está atualmente lendo.
- **Pretende Ler**: Mostra os livros que o usuário planeja ler no futuro.
- **Já Lido**: Exibe os livros que o usuário já terminou de ler.

### 4. **Alternar Tema (Claro/Escuro)**
- O aplicativo permite ao usuário alternar entre o **modo claro** e o **modo escuro** através de um botão de switch.
- O tema escuro tem uma interface otimizada para reduzir o cansaço visual, especialmente em ambientes com pouca luz.

### 5. **Layout Responsivo**
- O layout do aplicativo é responsivo, adaptando-se a diferentes tamanhos de tela para proporcionar uma boa experiência de uso tanto em desktop quanto em dispositivos móveis.

### 6. **Botão de Alternância de Tema ao Lado do Título**
- O botão de alternância de tema é exibido ao lado do título "Gerenciador de Livros", alinhado à direita.

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript utilizada para construir a interface do usuário.
- **Redux**: Usado para gerenciar o estado global dos livros (adição e remoção).
- **CSS Flexbox**: Utilizado para alinhar o layout e garantir responsividade.
- **Context API**: Utilizado para alternar entre os temas claro e escuro.

## Estrutura de Arquivos

```bash
.
├── src
│   ├── App.js               # Componente principal do aplicativo
│   ├── redux
│   │   ├── livrosSlice.js    # Redux Slice para gerenciar as ações de livros
│   ├── ThemeContext.js       # Context API para alternar temas
│   ├── App.css               # Estilos do aplicativo
├── public
│   ├── index.html            # HTML base
├── package.json              # Dependências e scripts
└── README.md                 # Documentação do projeto
