# Aplicação Full-Stack para Check-in dos alunos no Projeto Automotivo UCDB

Desenvolvida para um projeto coordenado pelo Professor Luiz Felipe Trombeta, esta aplicação full-stack foi projetada para otimizar o processo de check-in. A solução visa proporcionar uma interface aonde os alunos possam marcar seu horario de entrada/saida.

---

## 🚀 Tecnologias Utilizadas

-   **Back-end:** Node.js, Express.js
-   **Front-end:** HTML5, CSS3, JavaScript
-   **Banco de Dados:** Arquivos CSV utilizados para armazenamento de dados.

---

## 📋 Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:
-   [Node.js](https://nodejs.org/en/) (que já vem com o gerenciador de pacotes npm)

---

## ⚙️ Como Executar o Projeto

Siga os passos abaixo para inicializar a aplicação em seu ambiente local:

1.  **Clone o repositório (caso ainda não tenha):**
    ```bash
    git clone https://github.com/GustavoDimeira/Projeto-automotivo-UCDB.git
    cd Projeto-automotivo-UCDB
    ```

2.  **Instale as dependências do projeto:**
    Este comando irá instalar todas as bibliotecas necessárias para o back-end, como o Express.
    ```bash
    npm install express dotenv
    ```

3.  **Inicie o servidor back-end:**
    O servidor será iniciado e ficará escutando na porta `5000`, conforme definido no código.
    ```bash
    node back_end/index.js 
    ```

4.  **Abra o front-end:**
    A interface do usuário não precisa de um passo de compilação ou de um servidor dedicado. Basta abrir o arquivo abaixo diretamente no seu navegador:
    ```
    front_end/check_in/index.html
    ```
