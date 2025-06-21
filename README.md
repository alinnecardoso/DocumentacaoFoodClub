Claro! Aqui está o conteúdo formatado em **Markdown**:

````markdown
# 📦 Instruções para Execução do Projeto Integrador Localmente

## 🚀 Backend

1. Instale as dependências:
   ```bash
   npm install
````

2. Rode as migrações do banco de dados:

   ```bash
   npx sequelize-cli db:migrate
   ```

3. Rode os seeders:

   ```bash
   npx sequelize-cli db:seed:all
   ```

4. Inicie a aplicação:

   ```bash
   npm run start
   ```

---

## 🔐 Acesso ao Sistema (Login)

Use os e-mails e senhas abaixo para acessar o sistema com diferentes tipos de usuários:

### 👨‍🍳 Usuários do tipo `restaurant`

Senha padrão: **`restaurante123`**

| E-mail                                                    | Tipo de Usuário |
| --------------------------------------------------------- | --------------- |
| [admin@tech.com](mailto:admin@tech.com)                   | restaurant      |
| [italian@restaurant.com](mailto:italian@restaurant.com)   | restaurant      |
| [mexican@restaurant.com](mailto:mexican@restaurant.com)   | restaurant      |
| [japanese@restaurant.com](mailto:japanese@restaurant.com) | restaurant      |
| [vegan@restaurant.com](mailto:vegan@restaurant.com)       | restaurant      |
| [bbq@restaurant.com](mailto:bbq@restaurant.com)           | restaurant      |

---

### 🏢 Usuários do tipo `company`

Senha padrão: **`empresa123`**

| E-mail                                                  | Tipo de Usuário |
| ------------------------------------------------------- | --------------- |
| [company@tech.com](mailto:company@tech.com)             | company         |
| [foodlovers@company.com](mailto:foodlovers@company.com) | company         |
| [gourmet@company.com](mailto:gourmet@company.com)       | company         |

---

### 👩‍💼 Usuários do tipo `employee`

Senha padrão: **`funcionario123`**

| E-mail                                            | Tipo de Usuário |
| ------------------------------------------------- | --------------- |
| [employee@tech.com](mailto:employee@tech.com)     | employee        |
| [maria@employee.com](mailto:maria@employee.com)   | employee        |
| [carlos@employee.com](mailto:carlos@employee.com) | employee        |
| [ana@employee.com](mailto:ana@employee.com)       | employee        |
| [pedro@employee.com](mailto:pedro@employee.com)   | employee        |
| [lucia@employee.com](mailto:lucia@employee.com)   | employee        |
