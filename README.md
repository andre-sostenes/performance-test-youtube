# 📊 Teste de Carga no YouTube com JMeter

## 📌 Objetivo

Realizar um teste de carga simulando múltiplos usuários acessando vídeos no YouTube, utilizando massa de dados em CSV para variar os dados das requisições.

---

## 🧪 Cenário de Teste

* Simulação de múltiplos usuários simultâneos
* Execução de requisições para acesso a vídeos
* Utilização de dados dinâmicos via arquivo CSV

---

## 🧰 Ferramentas Utilizadas

* Apache JMeter
* CSV Data Set Config
* Thread Group

---

## 📂 Estrutura do Projeto

* `tests/` → arquivos de teste do JMeter (.jmx)
* `data/` → massa de dados (CSV)
* `results/` → resultados dos testes (se aplicável)

---

## 📄 Massa de Dados (CSV)

Exemplo de estrutura utilizada:

email,video
[user1@test.com](mailto:user1@test.com),video1
[user2@test.com](mailto:user2@test.com),video2

---

## ⚙️ Como Executar

1. Abrir o Apache JMeter
2. Carregar o arquivo `.jmx` localizado na pasta `tests/`
3. Verificar o caminho do arquivo CSV no `CSV Data Set Config`
4. Executar o teste

---

## 📊 Resultados

(Preencha conforme seu teste, exemplo abaixo)

* Tempo médio de resposta: ~1.2s
* Taxa de erro: 0%
* Comportamento estável sob carga leve

---

## 🧠 Aprendizados

* Configuração de testes de carga no JMeter
* Uso de massa de dados dinâmica com CSV
* Simulação de múltiplos usuários
* Análise básica de performance

---

## 🚀 Próximos Passos

* Aumentar volume de usuários simultâneos
* Gerar relatórios mais detalhados
* Integrar testes de performance com CI/CD

---
