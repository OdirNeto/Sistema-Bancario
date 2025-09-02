# 🏦 Sistema Bancário em Python

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

Este é um projeto desenvolvido para a conclusão do Bootcamp Santander - Back-end with Python. O projeto é uma **simulação de sistema bancário em Python**, desenvolvido com foco em **orientação a objetos, boas práticas de programação e uso de padrões de projeto**.  
O sistema permite cadastrar clientes, criar contas, realizar depósitos, saques, emitir extratos e manter histórico de transações com persistência em log.


---


## 🚀 Funcionalidades

✅ Cadastro de clientes (com CPF, nome, data de nascimento e endereço)  
✅ Criação de contas correntes associadas a clientes  
✅ Depósitos e saques com regras de limite  
✅ Emissão de extrato com saldo e transações  
✅ Histórico de transações com data e hora  
✅ Registro de logs de operações em arquivo (`log.txt`)  
✅ Iterador personalizado para listar contas  


---


## 📂 Estrutura do Projeto

📦 sistema-bancario
┣ 📜 main.py # Código principal do sistema
┣ 📜 log.txt # Arquivo de logs das transações
┗ 📜 README.md # Documentação do projeto


---


## 🛠️ Tecnologias Utilizadas

- **Python 3.10+**
- Módulos padrão:
  - `abc` (classes abstratas)
  - `datetime` (datas e horas)
  - `pathlib` (manipulação de diretórios)
  - `textwrap` (formatação de texto)


---


## ▶️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-bancario.git
Acesse a pasta do projeto:

bash
Copiar código
cd sistema-bancario
Execute o projeto:

bash
Copiar código
python main.py
📖 Menu de Operações
csharp
Copiar código
=============== MENU ================
[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q] Sair





🔮 Melhorias Futuras
 Persistência de dados em banco de dados (SQLite ou PostgreSQL)

 Interface gráfica (Tkinter ou Flask/Django Web)

 Testes unitários automatizados (Pytest)

 Autenticação de clientes





📜 Licença
Este projeto está licenciado sob a MIT License.
Sinta-se livre para usar, estudar e contribuir!





👨‍💻 Desenvolvido por Odir Neto 🚀
