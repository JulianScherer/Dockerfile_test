# 🎓 API de Alunos

Projeto para praticar **Go** e **Docker**, focado em organização de infraestrutura e resiliência.

### 🛠️ Tecnologias
- **Go** (Gin Gonic)
- **PostgreSQL**
- **Docker & Docker Compose**

### 💡 O diferencial
Implementei um sistema de **Healthcheck**. A aplicação é "inteligente": ela testa a conexão com o banco de dados e só libera o uso quando tudo está 100% pronto, evitando erros de inicialização.

### 🚀 Como rodar
```bash
docker compose up --build -d

Acesse em: http://localhost:8080

📡 Status do Sistema
Verifique se a API e o Banco estão saudáveis em: http://localhost:8080/health

📌 Rotas
GET /alunos: Lista todos os alunos.

POST /alunos: Cadastra um novo aluno.

GET /health: Check de saúde do sistema.


---

### Como salvar agora:
1. Abra o arquivo `README.md` no seu editor.
2. Apague o que estiver lá e cole esse código acima.
3. Salve e mande pro GitHub:
   ```bash
   git add README.md
   git commit -m "docs: readme resumido"
   git push origin main