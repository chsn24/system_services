Sistema de Atendimento e Pagamento
Projeto de modelagem de banco de dados desenvolvido para a disciplina de Banco de Dados no curso de Análise e Desenvolvimento de Sistemas - 2º Período (2025.1).

👨‍🎓 Alunos
Jefferson Ribeiro

Caio Henrique

📌 Objetivo
Desenvolver um sistema de banco de dados para gerenciar atendimentos, pagamentos, locações de equipamentos e prestações de serviços, garantindo integridade, segurança e rastreabilidade das informações.

📚 Entidades do Sistema
Cliente: cadastra os dados dos clientes.

Funcionário: armazena informações dos atendentes.

Atendimento: centraliza locações, serviços e pagamentos.

Locação: representa o aluguel de equipamentos.

Equipamento: objetos disponíveis para locação.

Prestação de Serviço: serviços realizados no atendimento.

Serviço: catálogo geral de serviços oferecidos.

Pagamento: registros financeiros vinculados ao atendimento.

Cartão: método de pagamento por cartão.

Pix: método de pagamento via Pix.

⚙️ Regras de Negócio
Um cliente pode ter múltiplos atendimentos.

Um atendimento é feito por um único funcionário.

Um atendimento pode incluir locações e prestações de serviço.

Pagamentos podem ser feitos por cartão ou Pix.

Um pagamento pode cobrir um ou mais atendimentos.

🔐 Requisitos Não Funcionais
Segurança dos dados dos clientes e dos pagamentos.

Acesso restrito apenas a funcionários autorizados.

Alta disponibilidade e integridade dos dados.

🛠️ Tecnologias
SQL (modelo físico com CREATE TABLE)

Ferramentas de modelagem (ex: MySQL Workbench, SQL Server ou PostgreSQL)

📄 Script de Criação
O projeto inclui um script SQL com as instruções CREATE TABLE e ALTER TABLE para todas as entidades e relacionamentos definidos no modelo lógico.
