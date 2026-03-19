# Evento

🚀 Projeto Django com Variáveis de Ambiente
<p align="center"> 🔐 Segurança • ⚙️ Boas práticas • 👥 Trabalho em equipe </p>
📌 Sobre o projeto

Este projeto foi desenvolvido utilizando o framework Django com o objetivo de demonstrar o uso de variáveis de ambiente para proteger informações sensíveis dentro de uma aplicação web.

🔐 Por que usar .env?

O arquivo .env é utilizado para armazenar dados sensíveis que não devem ficar expostos no código-fonte, como:

🔑 SECRET_KEY

🗄️ Configurações de banco de dados

🌐 Credenciais de APIs

👉 Isso aumenta a segurança e facilita a configuração do projeto em diferentes ambientes.

🚫 Por que o .env não deve ser versionado?

O .env contém informações críticas.

Se ele for enviado para o GitHub:

❌ Dados podem ser expostos

❌ A aplicação pode ser comprometida

❌ Hackers podem explorar vulnerabilidades

👉 Por isso, ele deve ser adicionado ao .gitignore.

📁 Função do .gitignore

O .gitignore impede que arquivos desnecessários ou sensíveis sejam enviados ao repositório.

📌 Neste projeto, ele ignora:

.env

db.sqlite3

__pycache__/

venv/

✅ Benefícios:

Projeto mais organizado

Mais segurança

Melhor colaboração em equipe

⚠️ Riscos de expor a SECRET_KEY

A SECRET_KEY no Django é essencial para a segurança.

Se for exposta:

🔓 Sessões de usuários podem ser falsificadas

🔓 Tokens podem ser manipulados

🔓 A aplicação pode ser comprometida

⚙️ Tecnologias utilizadas

🐍 Python

🌐 Django

🔐 python-dotenv