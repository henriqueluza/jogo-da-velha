# 🎮 Jogo da Velha - React

Um jogo da velha moderno e responsivo desenvolvido com React e estilizado com Tailwind CSS.

![React](https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC?style=for-the-badge&logo=tailwind-css)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript)


## 🚀 Tecnologias Utilizadas

- **React 19.1.0**: Biblioteca para construção da interface
- **Tailwind CSS 3.x**: Framework CSS para estilização
- **Create React App**: Setup e configuração do projeto
- **React Hooks**: `useState` para gerenciamento de estado
- **PostCSS**: Processamento de CSS
- **Autoprefixer**: Compatibilidade cross-browser

## 📦 Instalação

### Pré-requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn

### Passo a passo

1. **Clone o repositório**
   ```bash
   git clone <url-do-repositorio>
   cd jogo-da-velha
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento**
   ```bash
   npm start
   ```

4. **Abra no navegador**
   
   Acesse [http://localhost:3000] para jogar!


## Estrutura do Projeto

```
jogo-da-velha/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── App.js          # Componente principal do jogo
│   ├── index.js        # Ponto de entrada da aplicação
│   └── styles.css      # Estilos com Tailwind CSS
├── tailwind.config.js  # Configuração do Tailwind
├── postcss.config.js   # Configuração do PostCSS
└── package.json
```

## 🎨 Componentes

### `Board`
- Componente principal que gerencia o estado do jogo
- Controla alternância entre jogadores
- Detecta condições de vitória
- Gerencia reset do jogo

### `Square`
- Representa cada célula do tabuleiro
- Recebe cliques do usuário
- Exibe X, O ou fica vazio

### `ResetButton`
- Botão estilizado para reiniciar o jogo
- Limpa todas as marcações do tabuleiro
- Reseta para o jogador X




