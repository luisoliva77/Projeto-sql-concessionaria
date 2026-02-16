## 🔄 Auditoria de vendas com Trigger

O projeto possui um mecanismo de **backup automático de alterações** na tabela de vendas.

Foi criada uma **trigger** que registra em uma tabela de histórico todas as operações:

- INSERT
- UPDATE
- DELETE

Isso permite:

- Rastreabilidade das alterações
- Recuperação de dados
- Auditoria de operações no banco
