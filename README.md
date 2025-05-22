# 🌡️ Projeto Conversão de Temperatura

## 📘 Sobre o Projeto

O **Projeto Conversão de Temperatura** foi desenvolvido em **Node.js** com o objetivo de servir como exemplo prático para a criação de ambientes usando **containers** (como Docker).  
A aplicação realiza a conversão de temperaturas e pode ser utilizada como base para estudos ou demonstrações em ambientes de desenvolvimento containerizados.

## 🛠️ Tecnologias Utilizadas

- Node.js
- Express (para o servidor HTTP)
- Docker (para containerização)

## 🚀 Funcionalidade Principal

A aplicação permite a **conversão de temperaturas** entre diferentes escalas (Celsius, Fahrenheit e Kelvin).  
Ideal para entender a comunicação entre serviços e a exposição de portas em ambientes dockerizados.

## ⚙️ Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/projeto-conversao-temperatura.git
```

## 🧭 Como Executar o Projeto

### 📁 Acesse o diretório do projeto:

```bash
cd projeto-conversao-temperatura
```

### 🐳 Execute a aplicação com Docker:

```dockerfile
docker build -t conversao-temperatura .
docker run -p 8080:8080 conversao-temperatura
```

### 🌐 Acesse a aplicação no navegador:

```bash
http://localhost:8080
```

### 📌 Observações
A aplicação é exposta na porta 8080.

Certifique-se de que a porta 8080 esteja liberada no seu ambiente local ou na nuvem.

---

### 📂 Estrutura do Projeto

```bash
projeto-conversao-temperatura/
├── src/
│   └── index.js
├── Dockerfile
├── package.json
└── README.md
```
