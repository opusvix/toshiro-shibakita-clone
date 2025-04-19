# 🚀 Projeto Docker + Microsserviços: Clone do Toshiro Shibakita

Este repositório é uma réplica (com melhorias) do projeto original [denilsonbonatti/toshiro-shibakita](https://github.com/denilsonbonatti/toshiro-shibakita), focado no uso do Docker para estruturar microsserviços em diferentes tecnologias. O objetivo é demonstrar, na prática, como criar uma arquitetura simples e funcional baseada em containers.

---

## 🔧 Tecnologias Utilizadas

- **Docker** & **Docker Compose**
- **NGINX (HTML estático)**
- **Node.js + Express**
- **Python + Flask**

---

## 🧱 Estrutura do Projeto

```bash
toshiro-shibakita-clone/
├── app-html/         # Front-end HTML estático servido por NGINX
│   └── index.html
├── app-node/         # Microsserviço Node.js
│   ├── Dockerfile
│   ├── index.js
│   └── package.json
├── app-python/       # Microsserviço Python/Flask
│   ├── Dockerfile
│   ├── app.py
│   └── requirements.txt
├── docker-compose.yml
├── .gitignore
└── README.md
```

---

## 🐳 Como executar o projeto

1. Clone este repositório:
```
git clone https://github.com/seu-usuario/toshiro-shibakita-clone.git
cd toshiro-shibakita-clone
```

2. Suba os containers:
```
docker-compose up --build
```
---

3. Acesse no navegador:

- http://localhost:8080 – Página HTML inicial

- http://localhost:3000/node – Serviço Node.js

- http://localhost:5000/python – Serviço Python

---

📌 Objetivo Educacional

Este projeto tem como objetivo reforçar o entendimento sobre:

- Criação de containers multi-serviços com Docker

- Comunicação entre serviços via rede Docker

- Separação de responsabilidades por tecnologia

- Implantação simples de microsserviços

---

📚 Referência

Projeto base: [Toshiro Shibakita - Denilson Bonatti](https://github.com/denilsonbonatti/toshiro-shibakita)

---

🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests com melhorias ou sugestões.

---

🧠 Autor

Feito com 💙 por [Maurício Barros](https://github.com/opusvix)



















