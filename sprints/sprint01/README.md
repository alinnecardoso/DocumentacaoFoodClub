<span id="topo">

<h1 align="center">Sprint 01: 01/08/2024 a 21/08/2024</h1>


<p align="center">
    <a href="#objetivos">🎯 Objetivos da Sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">✅ Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">📊 Métricas do Time</a> &nbsp |&nbsp &nbsp
    <a href="#links">🔗 Links Úteis</a>
</p>

---
<span id="objetivos">

## 🎯 Objetivos desta Sprint
Na **primeira sprint**, o objetivo é estabelecer as funcionalidades básicas de autenticação, incluindo as páginas de cadastro e login, com integração inicial entre frontend e backend, para permitir o registro e acesso de usuários à plataforma.

---
Os principais requisitos desta sprint foram:  
- **[RF01] Criar Página de Cadastro:** Estruturar e implementar a interface para novos usuários se cadastrarem.
   - Critério de aceitação: A pagina deve ser acessível a partir da página inicial e permitir que o usuário insira suas informações necessárias para criação do seu perfil.
   - Tarefa: Implementar a pagina de cadastro de usuários, permitindo que os usuários criem suas contas e acessem a plataforma.
- **[RF02] Formulário de Cadastro:** Desenvolver o formulário funcional para entrada de dados no cadastro.
   - Critério de aceitação: O formulário deve estar na página de cadastro e permitir que o usuário insira seus dados.
   - Tarefa: Criar um formulario de cadastro para que o usuário cadastre as informações necessárias para a criação do perfil.
- **[RF03] Validação de Dados no Frontend:** Implementar a validação de dados diretamente no frontend para maior usabilidade.
   - Critério de aceitação: A validação deve garantir que os dados inseridos no formulário de cadastro atendam aos requisitos esperados (e.g., formato de e-mail válido, senha com critérios mínimos, campos obrigatórios preenchidos) antes do envio.
   - Tarefa: Desenvolver scripts de validação no frontend que forneçam feedback em tempo real para o usuário, garantindo maior precisão no preenchimento dos dados.
- **[RF04] Página de Login:** Construir a página de login com autenticação inicial.
   - Critério de aceitação: A página de login deve ser acessível a partir da página inicial, permitir que o usuário insira suas credenciais (e-mail e senha) e realizar a autenticação com sucesso, redirecionando o usuário para a área restrita ou exibindo mensagens de erro em caso de falha.
   - Tarefa: Implementar a interface e a lógica de autenticação para permitir que usuários existentes façam login em suas contas.
- **[RF05] Formulário de Login:** Criar o formulário funcional para entrada de credenciais.
   - Critério de aceitação: O formulário deve estar na página e permitir que o usuário insira as informações necessárias.
   - Tarefa: Criar formulário de login para a inserção das iformações necessarias para realizar o login.

→ [Voltar ao topo](#topo)

---

<span id="entregas">

## ✅ Entregas
As seguintes atividades foram realizadas durante esse sprint:  

### 📌 **Frontend**
---
1. **Página de Cadastro:**  
   - Estrutura inicial da interface com campos essenciais para registro.  
   - Validação de dados no frontend para verificar campos obrigatórios e formato correto.  
2. **Página de Login:**  
   - Desenvolvimento do formulário de login com funcionalidade básica.  
   - Estruturação da interface responsiva e atrativa.

### 📌 **Backend**
---
1. **Configuração de Microsserviços:**
   - Configuração inicial do ambiente backand utilizando Node.js, TypeScript, Swagger.
   - Desenvolvimento de uma API básicas para às funcionalidades de cadastro e login.
   - Estruturação de endpoints iniciais para integração com o frontend.
2. **Banco de Dados MongoDB:**
   - Definição da base de dados inicial, com a criação da coleção users para armazenamento de informações de cadastro.
   - Implementação de índices para otimizar consultas, como verificação de credenciais.
---
### 📌 **Progresso**
As páginas desenvolvidas foram testadas e integradas ao protótipo inicial. Além disso, a equipe documentou o código no repositório para facilitar futuras manutenções e implementações.

<details>
   <summary>👨‍💻 Demonstração</summary>
   <div style="display: flex; margin-top: 10px;">
       <img src="../../assets/gif/FoodClubCadastro.gif" alt="Demonstração das páginas de Cadastro" style="max-width: 400px; height: auto;">
       <br>
   </div>

   → [Voltar ao topo](#topo)
   
</details>

---

<span id="metricas">

## 📊 Métricas do Time

A equipe foi dividida entre as áreas de **frontend** e **backend**, com responsabilidades claras:  
- **Frontend:** Desenvolvimento da interface em React e integração inicial.  
- **Backend:** Configuração dos microsserviços em Node.js e estruturação do banco de dados MongoDB. 

---

<span id="links">

## 🔗 Links Úteis
- Repositórios:  
  - Frontend: [Acesse aqui](https://github.com/Bruno-Pasqual/foodClub/tree/master/client)  
  - Documentação: [Acesse aqui](https://github.com/Bruno-Pasqual/foodClub)

<span id="topo">

→ [Voltar ao topo](#topo)
