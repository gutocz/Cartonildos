# Cartonildos

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

---

## 📜 Descrição

Uma implementação web completa e funcional do popular jogo de cartas "Cards Against Humanity". O projeto foi desenvolvido com uma arquitetura moderna, separando frontend e backend, e utiliza WebSockets para comunicação em tempo real, proporcionando uma experiência multiplayer fluida e interativa.

Esta aplicação foi totalmente refatorada a partir de uma versão inicial, com foco em boas práticas de desenvolvimento, modularidade, performance e uma interface de usuário aprimorada.

<img width="1891" height="949" alt="image" src="https://github.com/user-attachments/assets/fa61d795-b0fd-4116-a8ad-57ea2e2242df" />

---

## ✨ Funcionalidades

-   **Multiplayer em Tempo Real**: Jogue com amigos de qualquer lugar, com todas as ações sincronizadas instantaneamente via WebSockets.
-   **Sistema de Salas e Lobby**: Crie um nome de usuário e entre em uma sala para começar a jogar.
-   **Mestre da Rodada (Czar) Rotativo**: A cada rodada, um novo jogador é escolhido automaticamente como o "Mestre da Rodada".
-   **Seleção de Cartas e Vencedor**: Os jogadores escolhem suas melhores cartas de resposta, e o Mestre da Rodada seleciona a vencedora.
-   **Pontuação Automática**: O sistema de pontos é atualizado e exibido em tempo real.
-   **Chat Integrado**: Comunique-se com outros jogadores através de um chat em tempo real dentro da sala de jogo.

---

## 💻 Tecnologias Utilizadas

O projeto é dividido em dois repositórios independentes: um para o frontend (cliente) e outro para o backend (servidor).

### Backend
-   **Node.js**: Ambiente de execução para o servidor.
-   **TypeScript**: Para um código mais robusto e de fácil manutenção.
-   **WebSockets (`ws`)**: Para a comunicação bidirecional e em tempo real.
-   **Nodemon & ts-node**: Para o ambiente de desenvolvimento com live-reload.
-   **Arquitetura Modular**: Lógica de negócio separada em `Managers` (UserManager, GameManager) para melhor organização.

### Frontend
-   **React**: Para a construção da interface de usuário.
-   **Vite**: Como ferramenta de build, proporcionando um ambiente de desenvolvimento extremamente rápido.
-   **TypeScript**: Para tipagem estática e componentização segura.
-   **React Router**: Para o sistema de rotas (Lobby e Jogo).
-   **Context API**: Para um gerenciamento de estado global e centralizado da conexão WebSocket.
-   **CSS Modules**: Para estilização escopada e componentizada.

---

## 📂 Repositórios do Projeto

O código-fonte é dividido em duas partes. Acesse os repositórios individuais para ver o código detalhado de cada um:

-   ➡️ [**Repositório do Frontend**](https://github.com/gutocz/CartonildosFRONT)
-   ➡️ [**Repositório do Backend**](https://github.com/gutocz/CartonildosBACK)

---

## 🚀 Como Rodar Localmente

Para executar o projeto completo na sua máquina, você precisará clonar e rodar os dois repositórios.

### Pré-requisitos
-   [Node.js](https://nodejs.org/) (versão 18 ou superior)
-   [npm](https://www.npmjs.com/) (geralmente vem com o Node.js)

### 1. Backend

```bash
# Clone o repositório do backend
git clone https://github.com/gutocz/CartonildosBACK.git

# Navegue até a pasta
cd CartonildosBACK

# Instale as dependências
npm install

# Inicie o servidor em modo de desenvolvimento
npm run dev
```
> O servidor do backend estará rodando em `ws://localhost:8080`.

### 2. Frontend

```bash
# Em um novo terminal, clone o repositório do frontend
git clone https://github.com/gutocz/CartonildosFRONT.git

# Navegue até a pasta
cd CartonildosFRONT

# Instale as dependências
npm install

# Inicie a aplicação em modo de desenvolvimento
npm run dev
```
> A aplicação frontend estará disponível em `http://localhost:5173` (ou outra porta indicada pelo Vite). Abra este endereço no seu navegador para jogar.

---

## 👨‍💻 Autor

**Gustavo Soares**

-   GitHub: `@gutocz`
-   LinkedIn: `https://www.linkedin.com/in/gutocz/`

---
