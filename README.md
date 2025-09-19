# Desafio-Dio-Randstad-banco-de-dados-Oficina-Mecanica
## 🧰 Descrição do Projeto Lógico – Oficina Mecânica 
Este projeto apresenta o **modelo lógico de um banco de dados relacional** desenvolvido para gerenciar as operações de uma oficina mecânica. O objetivo é organizar e controlar informações relacionadas a clientes, veículos, ordens de serviço, equipes técnicas, mecânicos, serviços realizados e peças utilizadas.

O esquema foi cuidadosamente estruturado para garantir integridade referencial, rastreabilidade e flexibilidade na geração de relatórios e consultas operacionais.

## 🔗 Entidades e Relacionamentos
**Cliente:** Armazena dados pessoais e de contato dos clientes da oficina.

**Veículo:** Registra os veículos pertencentes aos clientes, com vínculo direto à tabela cliente.

**Equipe:** Representa grupos especializados de trabalho, como elétrica, motor, freios etc.

**Mecânico:** Contém os dados dos profissionais, vinculados a uma equipe específica.

**Ordem de Serviço:** Centraliza as solicitações de atendimento, vinculando cliente, veículo e equipe responsável. Inclui status e orçamento.

**Serviço:** Lista os tipos de serviços oferecidos pela oficina, com valores de mão de obra.

**Peça:** Catálogo de peças disponíveis, com descrição e valor unitário.

**os_servico:** Tabela associativa que vincula serviços às ordens de serviço.

**peca_os:** Tabela associativa que vincula peças às ordens de serviço.

**mecanico_ordem_servico:** Representa o relacionamento N:N entre mecânicos e ordens, permitindo registrar função e data de execução.

## 📊 Funcionalidades do Modelo
* Controle completo de ordens de serviço com status e previsão de entrega.

* Registro detalhado de serviços e peças aplicados em cada ordem.

* Atribuição de equipes e mecânicos com rastreabilidade por função e execução.

* Consultas otimizadas para relatórios por cliente, veículo, equipe, período e status.

## Link:
[modelo realcional Diagrama EER](https://github.com/marcelomoura85/Desafio-Dio-Randstad-banco-de-dados-Oficina-Mecanica/blob/main/Oficina_Mecanica.png)

[Script SQL](https://github.com/marcelomoura85/Desafio-Dio-Randstad-banco-de-dados-Oficina-Mecanica/blob/main/Script%20banco%20de%20dados%20Oficina%20Mecanica%20desafio%20Dio-Randstad.pdf)

[Dados para inserção no Banco de Dados](https://github.com/marcelomoura85/Desafio-Dio-Randstad-banco-de-dados-Oficina-Mecanica/blob/main/Dados%20de%20insercao%20desafio%20banco%20de%20dados%20Oficina%20Mecanica%20Dio-Randstad.pdf)
