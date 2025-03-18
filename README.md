# CarGo

## Descrição
O **CarGo** é uma plataforma web projetada para gerenciar o processo de aluguel de automóveis de forma eficiente e segura. O sistema permite que usuários individuais e agentes (empresas e bancos) realizem diversas operações relacionadas aos aluguéis de veículos, incluindo pedidos, cancelamentos e modificações.

## Funcionalidades Principais

### Para Clientes (Usuários Individuais)
-  Cadastro e autenticação de usuários.
-  Inserção de pedidos de aluguel.
-  Modificação e cancelamento de pedidos.
-  Consulta ao histórico de pedidos.

### Para Agentes (Empresas e Bancos)
-  Modificação e avaliação de pedidos de aluguel.
-  Análise financeira dos pedidos.
-  Aprovação ou rejeição de contratos de aluguel.

## Diagrama de Caso de uso

## Diagrama de Classes 

## Requisitos do Sistema

### Cadastro de Usuários
- O sistema exige um **cadastro prévio** para qualquer operação.
- Clientes devem fornecer informações como **RG, CPF, Nome, Endereço, Profissão, Entidade Empregadora e Renda (até 3 registros)**.

### Gerenciamento de Automóveis
- Registro de informações sobre os veículos, incluindo **matrícula, ano, marca, modelo e placa**.
- Associação do automóvel a contratos de aluguel.

### Contratos e Análise Financeira
- O aluguel pode estar vinculado a um **contrato de crédito** fornecido por um banco agente.
- Somente pedidos com parecer financeiro positivo podem ser finalizados.

### Infraestrutura do Sistema
- Servidor central conectado às máquinas locais dos clientes e agentes.
- Todas as transações e interações são realizadas via **Internet**.

## Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-------------|
| **Backend** | Java (Spring Boot)  |
| **Frontend** | HTML5 |
| **Banco de Dados** | PostgreSQL L |
| **Autenticação** | JWT |
| **Infraestrutura** | Servidores em Cloud (AWS, Azure ou Google Cloud) |