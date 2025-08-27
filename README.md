# Banco API Tests

## 📌 Objetivo  
Este projeto tem como objetivo automatizar os testes da [Banco API](https://github.com/juliodelimas/banco-api), contribuindo com a qualidade e consistência das funcionalidades oferecidas pela API REST.  

---

## 🛠️ Stack Utilizada  
O projeto é desenvolvido em **JavaScript** e utiliza as seguintes bibliotecas e ferramentas:  

- [Mocha](https://mochajs.org/) – Framework de testes.  
- [Chai](https://www.chaijs.com/) – Biblioteca de asserções.  
- [Supertest](https://github.com/ladjs/supertest) – Cliente HTTP para testes de APIs.  
- [Mochawesome](https://github.com/adamgruber/mochawesome) – Gerador de relatórios em HTML.  
- [Dotenv](https://github.com/motdotla/dotenv) – Gerenciamento de variáveis de ambiente.  

---

## 📂 Estrutura de Diretórios  
```
banco-api-tests/
├── test/                # Casos de teste automatizados
│   ├── login.test.js   # Testes relacionados a login
│   ├── transferencia.test.js # Testes relacionados a transferências
├── mochawesome-report/  # Relatórios gerados em HTML
├── .env                 # Arquivo para configuração da variável BASE_URL
├── .gitignore           # Arquivo que contém os nomes de arquivos que não subirão para o repositório
├── package.json         # Dependências e scripts do projeto
└── README.md            # Documentação do projeto
```

---

## ⚙️ Configuração do Arquivo `.env`  
É necessário criar um arquivo `.env` na raiz do projeto para definir a URL base da API que será testada.  

Formato:  
```env
BASE_URL=http://localhost:3000
```

---

## ▶️ Execução dos Testes  

### Instalar as dependências  
```bash
npm install
```

### Executar os testes  
```bash
npm test
```

### Gerar relatório Mochawesome  
Após a execução dos testes, o relatório em HTML será gerado automaticamente no diretório:  
```
./mochawesome-report/mochawesome.html
```

Abra esse arquivo em um navegador para visualizar os resultados.  

---

## 📚 Documentação das Dependências  
- [Mocha](https://mochajs.org/)  
- [Chai](https://www.chaijs.com/)  
- [Supertest](https://github.com/ladjs/supertest)  
- [Mochawesome](https://github.com/adamgruber/mochawesome)  
- [Dotenv](https://github.com/motdotla/dotenv)
