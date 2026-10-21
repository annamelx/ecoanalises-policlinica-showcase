<div align="center">

# 🩺 Ecoanálises Policlínica

### Site institucional e plataforma de agendamentos — em desenvolvimento

**Um projeto web para aproximar pacientes e clínica por meio de uma experiência simples, acessível e organizada.**

![Status](https://img.shields.io/badge/STATUS-EM_DESENVOLVIMENTO-0A7E99?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-172B4D?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-165F91?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-1C3D66?style=for-the-badge&logo=javascript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-0B827E?style=for-the-badge&logo=supabase&logoColor=white)

</div>

---

## 💙 Sobre o projeto

A **Ecoanálises Policlínica**, localizada em Bananeiras (PB), é o contexto de desenvolvimento desta aplicação. O objetivo é reunir informações institucionais, autenticação de pacientes e, futuramente, uma agenda de atendimentos administrada pela recepção.

Este repositório é uma **apresentação pública do trabalho**. O código-fonte integral do sistema está em um repositório privado, em razão dos cuidados necessários com autenticação e dados relacionados à saúde.

## ✨ Funcionalidades e progresso

| Funcionalidade | Situação |
| --- | --- |
| Site institucional responsivo | ✅ Interface desenvolvida |
| Informações dos serviços e contato da clínica | ✅ Interface desenvolvida |
| Cadastro e login com Supabase Auth | ✅ Testado em desenvolvimento |
| Área do Paciente | ✅ Interface integrada à autenticação |
| Agendamentos na Área do Paciente | 🧪 Simulação; ainda não são reservas reais |
| Banco de especialidades e profissionais | ✅ Estrutura criada no Supabase |
| Associação de múltiplas especialidades por profissional | ✅ Estrutura criada |
| Estrutura de escalas semanais | ✅ Tabelas criadas |
| Painel da recepção | 🚧 Planejado / em desenvolvimento |
| Geração automática e manual de horários | 🚧 Em desenvolvimento |
| Agendamentos reais com confirmação | 🔜 Próxima etapa |

> **Atenção:** o projeto ainda não é um sistema de agendamento disponível para uso público. As telas demonstrativas não confirmam consultas reais.

## 📅 Como será a agenda semanal

A proposta é permitir que a recepção cadastre a escala **a cada semana**, conforme a disponibilidade dos profissionais — sem depender de dias fixos.

**Duas maneiras de cadastrar horários:**

- **Automática:** escolher data, horário inicial e final e duração da consulta; o sistema gera as vagas.
- **Manual:** cadastrar horários específicos, um a um, conforme a necessidade.

O planejamento também contempla **serviços sem profissional individual selecionável**, como Laboratório e coleta, e profissionais vinculados a mais de uma especialidade.

## 🛠️ Tecnologias

- **HTML5:** estrutura das páginas.
- **CSS3:** identidade visual, layout e responsividade.
- **JavaScript:** interações, componentes e fluxo da interface.
- **Supabase Auth:** autenticação de usuários.
- **PostgreSQL / Supabase:** modelagem inicial das informações e escalas.
- **Git e GitHub:** versionamento e acompanhamento do projeto.
- **IntelliJ IDEA:** ambiente de desenvolvimento.

## 🖥️ Telas do projeto


### 🏥 Página inicial
![Página inicial da Ecoanálises](imagens/gitkeep.pagina-inicial.png)

### 💙 Área do Paciente
![Área do Paciente da Ecoanálises](imagens/gitkeep.area-paciente.png)

> Projeto em desenvolvimento. As imagens são
> demonstrativas e não contêm dados reais de pacientes.

## 🔐 Privacidade e segurança

- Nenhuma senha, chave secreta, informação clínica de paciente ou exportação do banco de dados é compartilhada aqui.
- O acesso da recepção e as permissões de agendamento estão sendo implementados e testados antes de disponibilização ao público.
- O repositório contém a documentação de apresentação, não o banco de dados nem o código completo de produção.

## 👩🏻‍💻 Desenvolvimento

**Anna Karolina**  
Licenciatura em Ciência da Computação — UFPB  
GitHub: [@annamelx](https://github.com/annamelx)

---

<div align="center">

**Ecoanálises Policlínica · Projeto em evolução 💙**

</div>
