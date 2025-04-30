### Nome - Vitor Farias Ampudia
### RA - 2042471

# Cenário 

Sistema de Gerenciamento de Clínica Médica 

# Descrição do Sistema

A clínica médica deseja implementar um sistema para gerenciar consultas, médicos,
pacientes e prontuários médicos. O sistema deve permitir que os pacientes agendem
consultas online, que os médicos acessem e atualizem prontuários e que os
administradores gerenciem o cadastro de médicos e pacientes. 

# Atores

* **Paciente**: Usuário que agenda consultas e visualiza seu histórico médico.
* **Médico**: Profissional de saúde que realiza consultas, acessa e atualiza
prontuários dos pacientes.
* **Administrador**: Usuário que gerencia o cadastro de médicos e pacientes, além
de gerenciar as consultas. 

# Caso de Uso

## 1 - Acessar Prontuário

### Objetivo

Observar o histórico de saúde do paciente, além de todas as informações relevantes sobre sua saúde e tratamento

### Atores 

**Paciente:** Irá Consultar seu próprio prontuário

## 2 - Realizar Agendamento

### Objetivo

Agendar o Paciente, para uma consulta com o Médico

### Atores

**Paciente:** O paciente deve informar o motivo do agendamento da consulta, além de confirmar o dia possível para realizar o mesmo, ou então, entrar em consenso com o Administrador para o melhor dia para ambos

**Administrador:** Aquele que irá consultar a agenda do Médico, e irá confirmar com o paciente o dia da consulta

**Médico:** Indivíduo que irá confirmar com o Adiministrador a disponibilidade para consulta, e trazer especificações caso necessário para a consulta

## 3 - Cadastrar Médico

### Objetivo

Catalogar o Médico em questão no Sistema

### Atores

**Médico:** Providenciar informações pessoais para o sucesso em seu cadastro no Sistema

**Administrador:** Responsável pelo Sistema de fato, e realizará o cadastro do Médico no Sistema

## 4 - Atualizar Prontuário 

### Objetivo

