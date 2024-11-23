# Sprint 01: 01/08/2024 a 21/08/2024

[🎯 Objetivos da Sprint](#objetivos) | [✅ Entregas](#entregas) | [📊 Métricas do Time](#metricas) | [🔗 Links Úteis](#links)

O projeto **FoodClub** tem como objetivo criar uma plataforma que facilite a interação entre restaurantes e empresas, simplificando o processo de escolha e pedido de refeições. Na **primeira sprint**, o foco foi estabelecer as páginas de autenticação e cadastro, essenciais para o funcionamento da plataforma.

---

## 🎯 Objetivos da Sprint
Os principais requisitos desta sprint foram:  
- [RF01] **Criar Página de Cadastro:** Estruturar e implementar a interface para novos usuários se cadastrarem.
   - Critério de aceitação: A pagina deve ser acessível a partir da página inicial e permitir que o usuário insira suas informações necessárias para criação do seu perfil.
   - Tarefa: Implementar a pagina de cadastro de usuários, permitindo que os usuários criem suas contas e acessem a plataforma.
- [RF02] **Formulário de Cadastro:** Desenvolver o formulário funcional para entrada de dados no cadastro.
   - Critério de aceitação: O formulário deve estar na página de cadastro e permitir que o usuário insira seus dados.
   - Tarefa: Criar um formulario de cadastro para que o usuário cadastre as informações necessárias para a criação do perfil.
- [RF03] **Validação de Dados no Frontend:** Implementar a validação de dados diretamente no frontend para maior usabilidade.
   - Critério de aceitação: A validação deve garantir que os dados inseridos no formulário de cadastro atendam aos requisitos esperados (e.g., formato de e-mail válido, senha com critérios mínimos, campos obrigatórios preenchidos) antes do envio.
   - Tarefa: Desenvolver scripts de validação no frontend que forneçam feedback em tempo real para o usuário, garantindo maior precisão no preenchimento dos dados.
- [RF04] **Página de Login:** Construir a página de login com autenticação inicial.
   - Critério de aceitação: A página de login deve ser acessível a partir da página inicial, permitir que o usuário insira suas credenciais (e-mail e senha) e realizar a autenticação com sucesso, redirecionando o usuário para a área restrita ou exibindo mensagens de erro em caso de falha.
   - Tarefa: Implementar a interface e a lógica de autenticação para permitir que usuários existentes façam login em suas contas.
- [RF05] **Formulário de Login:** Criar o formulário funcional para entrada de credenciais.
   - Critério de aceitação: O formulário deve estar na página e permitir que o usuário insira as informações necessárias.
   - Tarefa: Criar formulário de login para a inserção das iformações necessarias para realizar o login.

---

## ✅ Entregas
As seguintes atividades foram realizadas durante esse sprint:  

### 📌 **Frontend**
1. **Página de Cadastro:**  
   - Estrutura inicial da interface com campos essenciais para registro.  
   - Validação de dados no frontend para verificar campos obrigatórios e formato correto.  
2. **Página de Login:**  
   - Desenvolvimento do formulário de login com funcionalidade básica.  
   - Estruturação da interface responsiva e atrativa.

### 📌 **Backend**
1. **Configuração de Microsserviços:**
   - Configuração inicial do ambiente backand utilizando Node.js, TypeScript, Swagger.
   - Desenvolvimento de uma API básicas para às funcionalidades de cadastro e login.
   - Estruuração de endpoints iniciais para integração com o frontend.
2. **Banco de Dados Mongo:**
   - Definição da base de dados inicial, com a criação da coleção users para armazenamento de informações de cadastro.
   - Implementação de índices para otimizar consultas, como verificação de credenciais.

### 📌 **Progresso**
As páginas desenvolvidas foram testadas e integradas ao protótipo inicial. Além disso, a equipe documentou o código no repositório para facilitar futuras manutenções e implementações.

<details>
   <summary>👨‍💻 Demonstração</summary>
   <img src="https://via.placeholder.com/800x400.png?text=Demo+do+Cadastro+e+Login" alt="Demonstração das páginas de Cadastro e Login">
</details>

---

## 📊 Métricas do Time

A equipe foi dividida entre as áreas de **frontend** e **backend**, com responsabilidades claras:  
- **Frontend:** Desenvolvimento da interface em React e integração inicial.  
- **Backend:** Configuração dos microsserviços em Node.js e estruturação do banco de dados MongoDB. 

---

## 🔗 Links Úteis
- Repositórios:  
  - Frontend: [Acesse aqui](https://github.com/Bruno-Pasqual/foodClub/tree/master/client)  
  - Documentação: [Acesse aqui](https://github.com/Bruno-Pasqual/foodClub)

→ [Voltar ao topo](#topo)
