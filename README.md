# Bernnardo francisco de oliveira silva 10435832

# 📌 AgendeJá – Sistema de Agendamento de Consultas Médicas  

🌟 Um pequeno resumo sobre o projeto.  

O **AgendeJá** é um sistema de agendamento de consultas médicas que permite que **pacientes marquem e gerenciem seus atendimentos** de forma rápida e eficiente, sem precisar ligar para a clínica.  

A plataforma possibilita que **médicos e recepcionistas organizem a agenda** de maneira digital, reduzindo erros e otimizando o atendimento.  

---

## 📖 Sumário  

- [1️⃣ Introdução](#1️⃣-introdução)  
- [2️⃣ Cenário de Negócio](#2️⃣-cenário-de-negócio)  
  - [2.1 Problema ou Oportunidade Percebida](#21-problema-ou-oportunidade-percebida)  
  - [2.2 Justificativa para a Demanda](#22-justificativa-para-a-demanda)  
  - [2.3 Descrição do Produto](#23-descrição-do-produto)  
  - [2.4 Clientes, Usuários e Envolvidos](#24-clientes-usuários-e-envolvidos)  
  - [2.5 Critérios de Qualidade](#25-critérios-de-qualidade)  
- [3️⃣ Modelo de Casos de Uso](#3️⃣-modelo-de-casos-de-uso)  
  - [3.1 Identificação dos Casos de Uso](#31-identificação-dos-casos-de-uso)  
  - [3.2 Descrição Resumida dos Casos de Uso](#32-descrição-resumida-dos-casos-de-uso)  
  - [3.3 Caso de Uso Crítico - Descrição Detalhada](#33-caso-de-uso-crítico---descrição-detalhada)  
- [4️⃣ Diagrama UML do Caso de Uso](#4️⃣-diagrama-uml-do-caso-de-uso)  
- [5️⃣ Conclusão](#5️⃣-conclusão)  

---

## 1️⃣ Introdução  

O **AgendeJá** é uma **plataforma digital** que permite que pacientes, médicos e clínicas organizem os atendimentos de forma eficiente.  

**Principais funcionalidades:**  
✔ **Marcação de consultas online** – Pacientes escolhem especialidade, data e horário disponíveis.  
✔ **Gestão de agenda para médicos** – Médicos visualizam e administram seus horários.  
✔ **Notificações automáticas** – Lembretes por e-mail ou SMS para evitar faltas.  
✔ **Interface intuitiva** – Fácil de usar para todos os usuários.  
✔ **Segurança de dados** – Proteção das informações dos pacientes conforme a LGPD.  

---

## 2️⃣ Cenário de Negócio  

### 2.1 Problema ou Oportunidade Percebida  
📌 O atual processo de marcação de consultas médicas apresenta desafios, tais como:  
- Longas esperas em chamadas telefônicas.  
- Possibilidade de erros no agendamento manual.  
- Falta de lembretes para pacientes, resultando em ausências.  
- Dificuldade para médicos organizarem suas agendas.  

O **AgendeJá** propõe uma solução digital para eliminar esses problemas.  

### 2.2 Justificativa para a Demanda  
**Por que esse sistema é necessário?**  
- Pacientes querem marcar consultas de forma simples e rápida.  
- Clínicas precisam de organização na gestão da agenda.  
- Médicos necessitam de uma plataforma confiável para administrar atendimentos.  
- A tecnologia pode reduzir falhas, otimizando a experiência para todos os envolvidos.  

### 2.3 Descrição do Produto  
O **AgendeJá** é um **sistema online** que permite que pacientes, médicos e clínicas organizem os atendimentos de forma eficiente.  

### 2.4 Clientes, Usuários e Envolvidos  
👥 **Usuários principais:**  
- **Pacientes:** Marcam e acompanham consultas.  
- **Médicos:** Organizam e confirmam atendimentos.  
- **Recepcionistas:** Administram os agendamentos.  

👤 **Outros envolvidos:**  
- **Clínicas/Hospitais** – Administradores do sistema.  
- **Desenvolvedores** – Responsáveis pela manutenção do software.  

### 2.5 Critérios de Qualidade  
✅ **Interface intuitiva:** Deve ser fácil de usar para pacientes e médicos.  
✅ **Segurança e conformidade com a LGPD:** Proteção dos dados dos usuários.  
✅ **Disponibilidade:** O sistema deve estar acessível 24/7.  
✅ **Lembretes automáticos:** Notificações para reduzir ausências.  
✅ **Escalabilidade:** Capacidade de crescer conforme a demanda da clínica.  

---

## 3️⃣ Modelo de Casos de Uso  

### 3.1 Identificação dos Casos de Uso  

| **Código** | **Nome do Caso de Uso** |
|------------|------------------------|
| CU01 | Paciente marca consulta |
| CU02 | Médico visualiza agenda |
| CU03 | Recepcionista gerencia consultas |
| CU04 | Sistema envia lembretes |

### 3.2 Descrição Resumida dos Casos de Uso  

| **Código** | **Nome do Caso de Uso** | **Descrição Resumida** |
|------------|------------------------|-------------------------|
| CU01 | Paciente marca consulta | O paciente acessa o sistema, escolhe a especialidade e agenda uma consulta. |
| CU02 | Médico visualiza agenda | O médico acessa o sistema para visualizar e gerenciar seus horários. |
| CU03 | Recepcionista gerencia consultas | A recepcionista pode alterar, cancelar e confirmar consultas. |
| CU04 | Sistema envia lembretes | O sistema automaticamente envia notificações para lembrar os pacientes. |

### 3.3 Caso de Uso Crítico - Descrição Detalhada  

| **Campo** | **Descrição** |
|------------|--------------|
| **Código** | CU01 |
| **Nome** | Paciente marca consulta |
| **Ator Principal** | Paciente |
| **Descrição** | O paciente acessa o sistema, escolhe a especialidade, seleciona um médico e agenda a consulta. |
| **Pré-condições** | O paciente precisa estar cadastrado e logado no sistema. |
| **Fluxo Principal** | 1. O paciente faz login.<br>2. Escolhe a especialidade.<br>3. Seleciona um médico e visualiza os horários.<br>4. Confirma a consulta.<br>5. O sistema envia um e-mail/SMS confirmando a marcação. |
| **Exceções** | 1. O paciente não está logado → O sistema pede para ele fazer login.<br>2. Não há horários disponíveis → O sistema informa e sugere outras datas. |

---

## 4️⃣ Diagrama UML do Caso de Uso  

📌 **Diagrama UML representando os casos de uso e os atores envolvidos.**  

 <img width="599" alt="Captura de Tela 2025-02-23 às 12 49 44" src="https://github.com/user-attachments/assets/39ec0e93-9daf-46b7-be3d-abe5582347b1" />


---

## 5️⃣ Conclusão  

O **AgendeJá** melhora a experiência dos pacientes e **otimiza o fluxo de trabalho das clínicas**, tornando o agendamento mais prático e eficiente.  

✔ **Elimina atrasos e erros no agendamento.**  
✔ **Melhora a experiência do paciente.**  
✔ **Facilita o gerenciamento da agenda médica.**  
✔ **Aumenta a produtividade e organização da clínica.**  

🔹 *Projeto em desenvolvimento para tornar a marcação de consultas mais simples e acessível para todos!* 🚀  
