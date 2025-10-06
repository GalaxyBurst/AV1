# Como Executar

### Pré-requisitos

  * [Node.js](https://nodejs.org/) (versão 18+)
  * [NPM](https://www.npmjs.com/)

### Passos

1.  **Clonar repositório:**

    ```bash
    git clone https://github.com/GalaxyBurst/AV1.git
    cd AV1
    ```

2.  **Instalar dependências:**

    ```bash
    npm install
    ```

3.  **Executar em modo de desenvolvimento:**
    Este comando utiliza o `tsx` para executar o código TypeScript diretamente, reiniciando automaticamente em caso de alterações.

    ```bash
    npm run dev
    ```

4.  **(Opcional) Para compilar:**
    Primeiro, compile o código TypeScript para JavaScript:

    ```bash
    npm run build
    ```

    Depois, execute o código compilado que estará na pasta `dist/`:

    ```bash
    npm start
    ```

### Exemplos de Login

  * **Administrador:**
      * **Usuário:** `admin`
      * **Senha:** `admin123`
  * **Engenheiro:**
      * **Usuário:** `eugenio`
      * **Senha:** `eng123`
  * **Operador:**
      * **Usuário:** `otavia`
      * **Senha:** `op123`
