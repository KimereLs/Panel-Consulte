# ㅤㅤㅤㅤㅤㅤㅤ ㅤ PANEL-CONSULTE v3.5

<p align="center">
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/termux-000000?style=for-the-badge&logo=termux&logoColor=white">
  <img src="https://img.shields.io/badge/status-online-brightgreen?style=for-the-badge">
</p>

---

### 📝 DESCRICAO

Interface de terminal profissional para APIs de busca. Totalmente otimizado para Termux, com sistema de logs automáticos e configuração de Token em tempo real.

---

### 🔍 CONSULTAS DISPONIVEIS

| Módulo | Descrição | Versões |
| :--- | :--- | :--- |
| **CPF** | Busca completa por documento | v1, v2, v3, v4 |
| **NOME** | Consulta por nome completo | v1 |
| **PLACA** | Dados veiculares atualizados | v1 |
| **TELEFONE** | Busca por número (DDD) | v1 |

---

### 🚀 INSTALACAO (PASSO A PASSO)

1. **Atualize os pacotes:**
```bash
pkg update && pkg upgrade -y
```

2. **Instale o Node.js:**
```bash
pkg install nodejs -y
```

3. **Instale o Git:**
```bash
pkg install git -y
```

4. **Clone o repositório:**
```bash
git clone https://github.com/KimereLs/panel-consulte.git
```

5. **Entre na pasta:**
```bash
cd panel-consulte
```

6. **Instale as dependências:**
```bash
npm install
```

7. **Inicie o painel:**
```bash
sh start.sh 
```

---

### ⚙ CONFIGURACAO DO TOKEN

Ao iniciar o painel pela primeira vez, sera solicitado o Token da API.

Caso queira alterar manualmente:

```bash
nano config.json
```

Ou utilize a opcao interna do painel:

```
[ CONFIGURAR TOKEN ]
```

---

### 📂 ESTRUTURA DO PROJETO

```
panel-consulte/
 ├── index.js
 ├── config.json
 ├── logs/
 ├── modules/
 ├── package.json
 └── README.md
```

---

### 📜 SISTEMA DE LOGS

Todos os logs sao salvos automaticamente em:

```
/logs/
```

Contendo:

- Data e hora  
- Tipo de consulta  
- Historico completo  

---

### ⚠ AVISO

Ferramenta destinada apenas para fins educacionais.  
O uso indevido e de total responsabilidade do usuario.

---

### 🏷 VERSAO

Atual: v3.5  
Status: Online
