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

**Paciente:** Irá consultar seu próprio prontuário

## 2 - Realizar Agendamento

### Objetivo

Agendar o Paciente, para uma consulta com o Médico

### Atores

**Paciente:** O paciente deve informar o motivo do agendamento da consulta, além de confirmar o dia possível para realizar o mesmo, ou então, entrar em consenso com o Administrador para o melhor dia para ambos

## 3 - Cadastrar Médico

### Objetivo

Catalogar o Médico em questão no Sistema

### Atores

**Médico:** Providenciar informações pessoais para o sucesso em seu cadastro no Sistema

**Administrador:** Responsável pelo Sistema de fato, e realizará o cadastro do Médico no Sistema

## 4 - Atualizar Prontuário 

### Objetivo

Modificar o prontuário do Paciente

### Atores

**Médico:** Indivíduo especializado que irá alterar com responsabilidade e conhecimento o prontuário do Paciente

## 5 - Desmarcar uma Consulta

### Objetivo

Cancelar uma consulta médica, atenriormente confirmada

### Atores

**Administrador:** Aquele que irá desfazer a consulta no sistema

**Médico:** Possível indivíduo que irá requisitar o cancelamento da consulta

**Paciente:** Possível indivíduo que irá requisitar o cancelamento da consulta

### Pré-requisitos

Deve haver uma consulta anteriormente marcada, e algum dos indivíduos, deve solicitar o cancelamento da consulta

### Fluxo Principal

1 - Aministrador informa seu Usuário e Senha para acessar o Sistema

2 - O Sistema verfica se os dados fornecidos estão corretos

3 - Se validados, o Administrador recebe acesso ao Sistema

4 - O Administrador acessa a aba de Gerenciamento de Consultas, e o dia específico da consulta a ser cancelada

5 - O Administrador efetua o cancelamento da consulta
