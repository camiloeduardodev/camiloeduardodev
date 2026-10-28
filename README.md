<h1 align="center">Camilo Eduardo</h1>

<p align="center">
  <strong>Desenvolvedor .NET</strong> · Backend em C# e ASP.NET Core · São Paulo, Brasil
</p>

<p align="center">
  <a href="https://camiloeduardo.tech"><img src="https://img.shields.io/badge/portf%C3%B3lio-camiloeduardo.tech-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfólio" /></a>
  <a href="https://www.linkedin.com/in/camilo-eduardo-986782254"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:camilocontato19@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail" /></a>
</p>

---

### Sobre

Cheguei ao código pelo caminho mais longo: comecei no **suporte técnico**, passei por **QA** e hoje construo **backend em C# e ASP.NET Core**. Essa passagem deixou uma marca — penso no que pode quebrar antes de escrever, e entrego solução pronta para produção.

No dia a dia projeto **APIs REST**, modelo dados em **SQL Server** e **PostgreSQL** com **EF Core** e cuido do ciclo inteiro, do banco ao deploy em **Docker**. Uso **Clean Architecture** e **SOLID** pelo que resolvem na prática, não como enfeite — e quando a entrega pede, viro full stack e levo a funcionalidade até a tela em **React**.

```
foco      Backend .NET · APIs REST
stack     C# · ASP.NET Core · EF Core · CQRS/MediatR
dados     PostgreSQL · SQL Server
entrega   Docker · Azure DevOps · Nginx/Traefik
também    React · TypeScript · RabbitMQ · Pix
```

---

### Desenvolvimento assistido por IA

Trabalho com **agentes de código** acoplados ao fluxo real de engenharia, não como autocomplete:

- **Claude Code / agentes especializados** — agentes por papel (backend, frontend, DBA, code review) com contexto do domínio e padrões do projeto
- **MCP (Model Context Protocol)** — integração dos agentes com banco, repositório e ferramentas internas
- **Spec-Driven Development** — especificação como fonte de verdade, o agente implementa e o gate de build/teste decide
- **Automação de ciclo** — revisão de código, geração de migrations, triagem de log e diagnóstico de produção

> O ganho não é digitar menos. É varrer um legado inteiro antes de decidir, e chegar na causa raiz com evidência em vez de palpite.

---

### Stack

**Núcleo**

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%208%20%2F%209%20%2F%2010-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-5C2D91?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square&logo=nuget&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

**Arquitetura & qualidade**

![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-1F2937?style=flat-square)
![CQRS](https://img.shields.io/badge/CQRS%20%C2%B7%20MediatR-1F2937?style=flat-square)
![FluentValidation](https://img.shields.io/badge/FluentValidation-1F2937?style=flat-square)
![xUnit](https://img.shields.io/badge/xUnit-1F2937?style=flat-square)
![JWT](https://img.shields.io/badge/JWT%20%C2%B7%20Identity-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Serilog](https://img.shields.io/badge/Serilog-1F2937?style=flat-square)

**Entrega & infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

---

### Projetos

<table>
  <tr>
    <td width="33%" valign="top">
      <h4><a href="https://grelhahub.com">GrelhaHub</a></h4>
      <sub><b>ERP para restaurantes — do pedido à brasa</b></sub>
      <p>Cardápio com link próprio, pedido sem instalar app e acompanhamento até Finalizado no painel da loja. Feito de ponta a ponta, do modelo de dados à tela.</p>
      <p>
        <code>.NET 10</code> <code>Clean Arch</code> <code>CQRS</code><br/>
        <code>EF Core 10</code> <code>PostgreSQL</code> <code>React 19</code>
      </p>
      <sub>372 testes · 90,8% de cobertura · 22 ADRs<br/>Integração contra PostgreSQL real em container.</sub>
    </td>
    <td width="33%" valign="top">
      <h4><a href="https://rifasolidaria.online">Rifa Solidária</a></h4>
      <sub><b>Rifa online com Pix</b></sub>
      <p>Plataforma para vender números por Pix e entregar cada um por e-mail assim que o pagamento cai. Nasceu para ajudar um colega de faculdade que teve o carro roubado.</p>
      <p>
        <code>.NET 9</code> <code>CQRS</code> <code>Pix</code><br/>
        <code>PostgreSQL 16</code> <code>Serilog</code> <code>React 18</code>
      </p>
      <sub>97 testes · concorrência resolvida com lock de linha no banco · webhook verificado por assinatura.</sub>
    </td>
    <td width="33%" valign="top">
      <h4><a href="https://school-manager.online">School Manager</a></h4>
      <sub><b>Gestão escolar em ASP.NET Core MVC</b></sub>
      <p>Alunos, responsáveis, professores, turmas, disciplinas e patrimônio: 15 módulos CRUD sobre 25 entidades, server-rendered em Razor.</p>
      <p>
        <code>.NET 9</code> <code>MVC + Razor</code> <code>EF Core 9</code><br/>
        <code>PostgreSQL</code> <code>Traefik</code> <code>Docker</code>
      </p>
      <sub>PBKDF2-HMAC-SHA256 (210k iterações) · rate limit por IP + bloqueio por usuário · autorização e CSRF como filtro global.</sub>
    </td>
  </tr>
</table>

---

### Experiência

**Seven Inovações** — São Paulo, Brasil · desde fev/2024

| Período | Cargo |
|---|---|
| nov/2025 — atual | Analista de Desenvolvimento de Software **Pleno** |
| ago/2025 — nov/2025 | Analista de Desenvolvimento de Software Júnior |
| out/2024 — jul/2025 | Analista de Testes / QA |
| fev/2024 — out/2024 | Atendente de Suporte Técnico N1 |

**Formação** — Análise e Desenvolvimento de Sistemas, UNICID (2026 — 2028)

---

<p align="center">
  <sub>Aberto a oportunidades, projetos e conversas técnicas.</sub><br/>
  <a href="https://camiloeduardo.tech">camiloeduardo.tech</a> ·
  <a href="https://www.linkedin.com/in/camilo-eduardo-986782254">LinkedIn</a> ·
  <a href="mailto:camilocontato19@gmail.com">camilocontato19@gmail.com</a>
</p>
