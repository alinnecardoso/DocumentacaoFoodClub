<span id="topo">

<h1 align="center">Sprint 2: 31/10/2024 a 22/11/2024</h1>

<p align="center">
    <a href="#objetivos">🎯 Objetivos da Sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">✅ Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">📊 Métricas do Time</a> &nbsp |&nbsp &nbsp
    <a href="#links">🔗 Links Úteis</a>
</p>

---
<span id="objetivos">
  
## 🎯 Objetivos desta Sprint

Na **segunda sprint**, o objetivo é organizar a documentação completa do projeto no Github, incluindo informações sobre os integrantes, sprints, backlogs, users stories e links úteis, além de desenvolver a Página Inicial com navegação acessível para todos os usuários.

---
Os principais requisitos desta sprint foram: 
- **Documentar no Github:**
  - Criar o Readme
  - Incluir nomes dos integrantes do grupo
  - Criar os Sprints
  - Incluir as Gifs da apresentação final do sistema
  - Backlogs
  - Users Stories
  - Adicionar o link do figma dentro da parte referente ao protótipo
  - Adicionar o link para download da documentação (formato .doc e doc de IHC)
  - Links úteis como link dos sitema funcional e do repositório do Github
  - Definir a função de cada integrante do grupo
- **Acesso à pagina Inicial:**
  - Critério de aceitação: A navegação deve segiur as diretrizes de acessibilidade (WCAG), permitindo navegação por teclado e suporte a leitores de tela.
  - Tarefa: Garantir que a navegação do sistema seja acessível para todos os usuários, incluíndo aqueles que tenham alguma deficuldade e ou deficiencia.

<span id="entregas">
        
## ✅ Entregas
As seguintes atividades foram realizadas durante esse sprint:  

### 📌 **Documentação do Github**
---
1. **README Completo:**  
   - Adicionado o nome dos integrantes do grupo.
   - Documentação das sprints com objetivos e resultados.
   - Criação de backlogs e user stories com detalhes para cada etapa.
   - Inclusão de GIFs da apresentação final do sistema e links úteis (Figma, sistema funcional, repositório Github).
   - Disponibilização para download da documentação geral e de IHC (em formato .doc).

### 📌 **Frontend:**
---
1. **Página Inicial:**  
   - Desenvolvimento da página inicial com navegação estruturada e responsiva.  
   - Implementação de diretrizes de acessibilidade, como navegação por teclado e suporte para leitores de tela.

### 📌 **Progresso:**
---
A  documentação foi revisada e validada para garantir consistência e clareza. A Página Inicial foi testada com ferramentas de acessibilidade para asegurar conformidade com os padrões WCAG.

<div align="center">

![demo](./demo.gif)
</div>

Este protótipo valida a entrega dos requisitos confirmados para a sprint, onde suas descrições podem ser checadas a seguir:

### RF 01: Registro e acompanhamento de chamados

Este requisito se trata do cadastro e atualizações de chamados, passando por várias fases, como: abertura de chamado, listagem de chamados, observação dos detalhes de um chamado, reverva e atendimento de chamados pelo suport, além de opção para comentários em um chamado, definindo uma discussão em prol da resolução do problema. Este requisito, como o validado, foi desenvolvido na primeira sprint levando em consideração as principais funções para a utilidade geral do projeto, e passará por refinamento e incremento na sprint 2.

### RF 02: Cadastro e login de usuários

Este requisito se trata do cadastro e login de usuários, respeitando a regra de negócio apresentada que permite apenas ao usuário administrados o acesso a funcionalidade de cadastro de novas contas, definindo o cargo destes novos usuários. Já o login, que pode ser acessado por qualquer tipo de usuário, permite a autenticação e autorização do usuário para navegação das telas respeitando seu cargo, por exemplo:

- **usuários do tipo comum** tem em sua página inicial a listagem de todos os chamados que ele próprio já abriu, com a possibilidade de criar um novo chamado ou acessar os detalhes de um chamado da lista, adicionando algum comentário;
- para **usuários do tipo suporte** a tela inicial se configura na listagem de chamados abertos por qualquer usuário e ao acessar os detalhes de um chamado é pssível reservá-lo, adicionar algum comentário ou marcá-lo como concluído;
- já para **usuários do tipo administrador** tem a apresentação da listagem de todos os usuários em sua página inicial, com a opção de cadastrar novos usuários.

<details>
   <summary>Diagrama de classes</summary>
   <h4>Diagrama de classes mapeado do frontend</h4>
   <img src="https://user-images.githubusercontent.com/69374340/163506461-be837b99-d7ce-4c3c-86ff-c1d276fec529.png">
   <h4>Diagrama de classes mapeado do microsserviço de usuários</h4>
   <img src="https://user-images.githubusercontent.com/69374340/163507227-c7373703-3fd4-456f-8670-2e25cb177199.png">
   <h4>Diagrama de classes mapeado do microsserviço de autenticação</h4>
   <img src="https://user-images.githubusercontent.com/69374340/163507603-d0c3400d-6c1c-422b-b923-38a5e8c11304.png">
   <h4>Diagrama de classes mapeado do microsserviço de chamados</h4>
   <img src="https://user-images.githubusercontent.com/69374340/163507346-aa436b7d-1143-4b42-845b-01bb94202ff3.png">
</details>
    
→ [Voltar ao topo](#topo)

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Em prol de um melhor aproveitamento das habilidades de cada integrante, o time foi separado em duas frentes: frontend e backend, onde, na primeira sprint, o time de frontend ficou responsável pela confecção do protótipo, projeto frontend e integração de funcionalidades enquanto o time de backend ficou responsável pela criação dos microsserviços necessários e pesquisas sobre o tema do desafio. 
- O acompanhamento de atividades, de responsabilidade da Scrum Master, se encontra na imagem adiante, que contém o gráfico Burndown gerado pela equipe (onde o eixo X são os dias trabalhados na sprint e os valores do eixo Y representam as entregas e esforços realizados com o passar do tempo), incluindo as atividades desenvolvidas e seus responsáveis.
    
<div align="center">
    
![Burndown Chart](https://user-images.githubusercontent.com/69374340/163472803-4912e725-f05c-4cdc-84bc-29ae2953f401.png)
</div>
    
<span id="links">
    
## :link: Links úteis

- Site do projeto: [https://help-duck.netlify.app/](https://help-duck.netlify.app/) (usuário exemplo - email: `user@gmail.com`, senha: `1357`)
- Tags geradas em cada repositório que simbolizam o fim da 1ª sprint:
  - Repositório do site: [clique aqui para acessar "help-duck-web"](https://github.com/The-Bugger-Ducks/help-duck-web)
  - Microsserviço de autenticação: [clique aqui para acessar "help-duck-authentication"](https://github.com/The-Bugger-Ducks/help-duck-authentication)
  - Microsserviço de usuários: [clique aqui para acessar "help-duck-users-microservice"](https://github.com/The-Bugger-Ducks/help-duck-users-microservice)
  - Microsserviço de chamados: [clique aqui para acessar "help-duck-requests"](https://github.com/The-Bugger-Ducks/help-duck-requests)

→ [Voltar ao topo](#topo)