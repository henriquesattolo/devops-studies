# devops-studies 🚀

Repositório de estudos práticos em DevOps — pipelines CI/CD, Docker e automação.

## 🛠️ Stack

- **GitHub Actions** — CI/CD pipeline automatizado
- **Docker** — containerização da aplicação
- **Docker Hub** — registro de imagens
- **Python** — aplicação de exemplo
- **WSL2 + Ubuntu** — ambiente de desenvolvimento

## ⚙️ Pipeline CI/CD

A cada `git push` na branch `main`, o pipeline executa automaticamente:

1. Checkout do repositório
2. Exibe informações do ambiente (SO, branch, autor)
3. Verifica versões instaladas (Git, Docker, Python)
4. Gera artefato de build com data e commit hash
5. Faz build da imagem Docker
6. Publica a imagem no Docker Hub

## 🐳 Imagem Docker

```bash
docker pull henriquesattolo/devops-studies:latest
docker run -p 8080:8080 henriquesattolo/devops-studies:latest
```

Acesse em: http://localhost:8080

## 📁 Estrutura do projeto
## 👨‍💻 Autor

**Henrique Sattolo** — Profissional de TI com 12 anos de experiência em infraestrutura, em transição para DevOps.
