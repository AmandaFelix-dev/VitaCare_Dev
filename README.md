<div align="center">

# 🏥 VitaCare

### Sistema Inteligente de Gestão Clínica e Prontuário Eletrônico

Plataforma web para gerenciamento de pacientes, consultas médicas, prontuário eletrônico e fluxo clínico, com autenticação baseada em perfis e controle de acesso.

---

### 👨‍💻 Equipe do Projeto

**Amanda Felix** • **Ryane Ferreira** • **Antônio Yan Cristino** • **Josué Araújo** • **Levi Nogueira**

<br>

<p align="center">
  <a href="https://vita-care-xi.vercel.app/">
    <img src="https://img.shields.io/badge/Deploy-Vercel-black?style=for-the-badge&logo=vercel" />
  </a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

🔗 **Projeto publicado:** https://vita-care-xi.vercel.app/  
📁 **Repositório:** https://github.com/AmandaFelix-dev/VitaCare_Dev

</div>

---

# 📌 Sobre o Projeto

O **VitaCare** é um sistema de gestão clínica desenvolvido para otimizar o fluxo operacional de clínicas médicas, permitindo que diferentes perfis de usuários executem ações específicas dentro do sistema com segurança e organização.

A aplicação foi construída com foco em um **MVP (Minimum Viable Product)** voltado para:

- Gerenciamento de pacientes;
- Agendamento de consultas;
- Check-in na recepção;
- Agenda médica;
- Prontuário eletrônico básico;
- Dashboard clínico de atendimentos;
- Controle de acesso baseado em perfil.

---

# 🗂️ Organização do Projeto (Sprints)

O desenvolvimento do **VitaCare** foi organizado utilizando metodologia ágil baseada em **sprints**, com gerenciamento de tarefas realizado no **ClickUp**.

O board foi estruturado para acompanhamento de:

- Backlog;
- Sprint atual;
- Histórias de usuário (User Stories);
- Pontuação por esforço;
- Status de execução;
- Critérios de conclusão.

As funcionalidades foram planejadas e entregues por meio de **User Stories (US)** priorizadas por esforço e dependência técnica.

### Processo utilizado

- Planejamento de sprint;
- Organização das tarefas no ClickUp;
- Desenvolvimento incremental do MVP;
- Critérios de aceite por funcionalidade;
- Validação por perfil de acesso;
- Controle de Definition of Done (DoD).

**Ferramenta utilizada:** ClickUp

---

# 🎯 Sprint Goal

Ao final da sprint, o sistema deve permitir que:

### Recepcionista
- Agende consultas;
- Realize check-in de pacientes;
- Cadastre e busque pacientes.

### Médico
- Visualize sua agenda diária;
- Registre prontuário eletrônico;
- Consulte histórico clínico do paciente.

### Administrador
- Acesse dashboard clínico;
- Visualize métricas operacionais da clínica.

Além disso, o sistema deve possuir **segurança validada por perfil**, garantindo permissões corretas de acesso.

---

# 📅 Restrições da Sprint

- Capacidade do time: **10–16 pontos**
- Máximo de **2 histórias grandes (G = 3 pts)** por sprint
- Dados clínicos devem respeitar segurança de acesso
- Prontuário depende de login e cadastro de paciente
- Duração simulada: **2 semanas**

---

# 📌 User Stories da Sprint

| ID | História | Status |
|---|---|---:|
| US01 | Login seguro por perfil | ✅ |
| US02 | Cadastro de pacientes | ✅ |
| US03 | Agendamento de consulta | ✅ |
| US04 | Agenda diária do médico | ✅ |
| US05 | Prontuário eletrônico básico | ✅ |
| US06 | Validação mock de CPF | ✅ |
| US07 | Notificação simulada | ✅ |
| US08 | Dashboard clínico | ✅ |
| US10 | Check-in de pacientes | ✅ |
| US11 | Histórico de consultas | ✅ |
| US12 | Integração mock de convênios | ✅ |
| US20 | Cadastro de convênios | ✅ |
| US21 | Busca rápida de paciente | ✅ |
| US26 | Módulo financeiro | ✅ |
| US09 | Cancelamento/reagendamento | 🚧 Em progresso |

---

# 🚀 MVP — Funcionalidades Implementadas

## 🔐 Autenticação e Controle de Acesso
- Login com perfis:
  - Médico
  - Recepcionista
  - Administrador
- Redirecionamento por perfil;
- Controle de permissões de acesso.

---

## 👥 Gestão de Pacientes
- Cadastro de pacientes;
- Busca de pacientes;
- Pesquisa rápida por:
  - Nome;
  - CPF;
  - Número do prontuário;
- Validação mock de CPF.

---

## 📅 Gestão de Consultas
- Agendamento de consultas;
- Seleção de:
  - Data;
  - Horário;
  - Médico;
  - Especialidade;
- Agenda diária do médico;
- Histórico de consultas por paciente;
- Check-in na recepção.

---

## 🏥 Prontuário Eletrônico
- Registro de prontuário eletrônico básico;
- Anamnese;
- Diagnóstico;
- Consulta ao histórico clínico.

---

## 💳 Convênios
- Cadastro de convênios aceitos;
- Integração mock de validação de convênios;
- Verificação de carteirinha;
- Validação de vencimento.

---

## 🔔 Comunicação
- Notificação simulada de consulta
(SMS/E-mail mockado).

---

## 📊 Dashboard Clínico
Dashboard com indicadores operacionais:

- Total de consultas do dia;
- Total semanal;
- Total mensal;
- Quantidade de pacientes;
- Consultas por médico;
- Cancelamentos;
- Médicos da clínica;
- Recepcionistas;
- Métricas operacionais.

---

## 💰 Financeiro
- Faturamento de consultas;
- Controle de convênios;
- Módulo financeiro básico.

---

# 👨‍⚕️ Perfis do Sistema

## Médico

### Funcionalidades
- Visualizar agenda médica;
- Registrar prontuário eletrônico;
- Consultar histórico clínico;
- Visualizar atendimentos do dia.

### Fluxo esperado
Após login, o médico deve acessar diretamente sua agenda diária de consultas.

---

## 🧾 Recepcionista

### Funcionalidades
- Cadastro de pacientes;
- Busca de pacientes;
- Agendamento de consultas;
- Check-in de pacientes.

### Fluxo esperado
Após login, a recepcionista deve acessar o painel de recepção com foco no de cadastro de pacientes.

---

## 📊 Administrador

### Funcionalidades
- Visualização do dashboard clínico;
- Acompanhamento de métricas operacionais.

### Métricas do dashboard
- Lista de médicos;
- Lista de recepcionistas;
- Número de faltas médicas;
- Quantidade de consultas diárias e mensais;
- Número de consultas por médico;
- Número total de pacientes;
- Número de atendimentos cancelados.

---

# 📋 Regras de Negócio

O sistema segue algumas regras fundamentais:

- O prontuário eletrônico só pode ser acessado após autenticação válida;
- O prontuário depende da existência de login e cadastro de pacientes;
- Perfis possuem permissões restritas;
- Dados sensíveis exigem controle de acesso;
- Convênios possuem validação de carteirinha e validade.

### Validação de convênio

- Carteirinhas iniciadas com **4 ou superior** → não reconhecidas;
- Convênios com validade expirada → considerados vencidos.

---

# 🧪 Dados Mockados para Demonstração

O sistema utiliza **dados mockados (simulados)** para demonstrar o funcionamento do MVP, permitindo testar autenticação, fluxo clínico, agenda médica, prontuário eletrônico, convênios, dashboard e regras de negócio.

> Todos os dados abaixo possuem finalidade exclusivamente acadêmica e demonstrativa.

---

# 🔐 Credenciais de Login

O sistema possui autenticação baseada em perfil.

| Perfil | E-mail | Senha |
|--------|--------|--------|
| 🧾 Recepcionista | `juliane@vitacare.com` | `JuliAne02249*` |
| 📊 Administrador | `admin@vitacare.com` | `AdmVita02249*` |
| 👨‍⚕️ Médico | `dr.carlos@vitacare.com` | `DrCarlos02249*` |

### Comportamento esperado

Após autenticação:

- **Recepcionista** → painel de atendimento;
- **Administrador** → dashboard clínico;
- **Médico** → agenda médica e prontuário eletrônico.

---

# 👥 Pacientes Cadastrados

Pacientes mockados disponíveis para:

- Cadastro;
- Busca;
- Histórico clínico;
- Consultas;
- Exames;
- Check-in;
- Prontuário eletrônico.

| Prontuário | Nome | CPF | Nascimento | Sexo |
|---|---|---:|---:|---:|
| MED-0001 | Ana Paula Ferreira | 529.982.247-25 | 12/03/1985 | F |
| MED-0002 | Roberto Almeida | 871.263.580-77 | 28/07/1972 | M |
| MED-0003 | Carla Souza Mendes | 046.915.723-60 | 05/11/1990 | F |
| MED-0004 | Marcos Vinicius Reis | 314.578.290-81 | 20/06/1988 | M |
| MED-0005 | Patrícia Oliveira | 753.410.862-34 | 14/09/1995 | F |

### Pesquisa rápida disponível

A busca de pacientes pode ser realizada por:

- Nome;
- CPF;
- Número do prontuário.

---

# 🏥 Médicos Disponíveis (Agendamento)

Médicos simulados utilizados no processo de:

- Agendamento de consultas;
- Agenda médica;
- Especialidades;
- Histórico clínico.

| Médico | CRM | Especialidade |
|---|---|---|
| Dr. Carlos Menezes | CRM-SP 45.821 | Clínica Geral |
| Dra. Beatriz Fontes | CRM-SP 32.104 | Cardiologia |
| Dra. Camila Torres | CRM-SP 41.290 | Dermatologia |
| Dr. André Lopes | CRM-SP 58.763 | Ortopedia |

---

# 💳 Convênios Mockados

O sistema possui validação simulada de convênios médicos.

| Plano | Prefixo da Carteirinha | Especialidades Cobertas |
|---|---|---|
| Gold | `1` (Ex: `1000-0001`) | Clínica Geral, Cardiologia, Ortopedia e Dermatologia |
| Silver | `2` (Ex: `2000-0001`) | Clínica Geral e Cardiologia |
| Basic | `3` (Ex: `3000-0001`) | Apenas Clínica Geral |

### Regras de Validação

- Carteirinhas iniciadas com **4 ou superior** → ❌ **não reconhecidas**
- Convênios com validade anterior à data atual → ❌ **convênio vencido**

---

# 📋 Histórico de Consultas e Exames

### 👩 Ana Paula Ferreira — `MED-0001`
- Consultas agendadas;
- Histórico de Clínica Geral;
- Histórico de Cardiologia;
- Hemograma → pendente;
- Glicemia → recebida.

---

### 👨 Roberto Almeida — `MED-0002`
- Consulta agendada;
- Histórico de Clínica Geral;
- Eletrocardiograma → pendente.

---

### 👩 Carla Souza Mendes — `MED-0003`
- Histórico de Dermatologia;
- Biópsia de Pele → recebida.

---

### 👨 Marcos Vinicius Reis — `MED-0004`
- Histórico de Ortopedia;
- Raio-X → recebido.

---

### 👩 Patrícia Oliveira — `MED-0005`
- TSH/T4 Livre → pendente;
- Sem consultas registradas.

---

# 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando:

- **HTML5** → estrutura da aplicação  
- **CSS3** → estilização e responsividade  
- **JavaScript (Vanilla JS)** → regras de negócio, interações e manipulação do sistema

---

# 📂 Estrutura do Projeto

```bash
VitaCare_Dev/
│
├── README.md
├── index.html
├── vitacare-admin.html
├── vitacare-recepcionista.html
├── vitacare-sistema-medico.html
└── ...

```

---

# ⚙️ Como Executar o Projeto

## 1. Clone o repositório

```bash
git clone https://github.com/AmandaFelix-dev/VitaCare_Dev.git
```

## 2. Entre na pasta

```bash
cd VitaCare_Dev
```

## 3. Execute

Abra o arquivo `index.html`

ou utilize uma extensão como:

- Live Server (VSCode)

---

# 🌐 Deploy

A aplicação está disponível online:

👉 https://vita-care-xi.vercel.app/

---

# 📈 Definition of Done (DoD)

Uma funcionalidade é considerada concluída quando:

- [x] Implementada
- [x] Testada
- [x] Validada por perfil de acesso
- [x] Sem falhas críticas
- [x] Fluxo principal funcional
- [x] Compatível com o MVP da sprint

---

# 🔮 Roadmap

### Próximas melhorias
- Persistência com banco de dados;
- API real de autenticação;
- API real para validação de CPF;
- Integração real com convênios;
- Upload de exames;
- Notificações reais por e-mail/SMS;
- Cancelamento e reagendamento completo;
- Dashboard analítico avançado;
- Controle financeiro expandido.

---

# 📄 Licença

Projeto desenvolvido para fins acadêmicos e de aprendizagem.
