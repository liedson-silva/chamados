# 🚀 FATAL SYSTEM – Gestão De Chamados
Projeto desenvolvido no **4º semestre de Análise e Desenvolvimento de Sistemas (ADS)**.  

---

## 📌 Desafio
O desafio consiste em criar uma aplicação web, desktop e mobile para gerenciamento de chamados.
O sistema deve permitir ao usuário criar chamados com título, descrição, categoria e prioridade, podendo revisar os dados e anexar arquivos tanto no envio quanto enquanto o chamado estiver aberto.
Antes do envio, o sistema realiza uma checagem automática dos campos obrigatórios, alertando o usuário caso haja pendências.
Também deve ser possível visualizar os chamados criados de acordo com o nível de acesso, e todas as informações devem ser armazenadas em banco de dados para consulta e histórico.

---

## 📋 Backlog do Produto
### 1. Gerenciamento de chamados
```
1.a) Criar chamado:
O sistema deve permitir que o usuário crie um novo chamado, informando título, descrição, categoria e prioridade.
O usuário deve poder revisar os dados preenchidos antes de confirmar o envio do chamado.
O sistema deve permitir anexar um ou mais arquivos ao chamado antes do envio e também após o chamado ter sido criado (enquanto estiver em aberto).

1.a.a) Checar chamado:
Antes de enviar o chamado, o sistema realiza uma primeira checagem para garantir que todos os campos obrigatórios estejam preenchidos. 
Se o sistema identificar um campo em branco, o chamado não é enviado e o funcionário é informado para preencher os dados. 
Caso a dupla checagem seja concluída com sucesso, o funcionário envia o chamado para a equipe de suporte.

1.a.b) Anexar mais arquivos:
Sistema permite anexar mais arquivos em um chamado já existente.

  
1.b) Visualizar chamado:
O sistema deve permitir que o usuário visualize os chamados criados, de acordo com o seu nível de acesso.
```

---

## 🛠️ Tecnologias
- [Astah UML](https://astah.net "Ferramenta de modelagem visual")


---
