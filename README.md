# Curso de Banco de Dados com MySQL - 40 Horas

## Descrição

Este repositório documenta meu progresso no **Curso de Banco de Dados com MySQL - 40 Horas**, ministrado pelo professor Gustavo Guanabara no Curso em Vídeo. O curso ensina os fundamentos de bancos de dados relacionais utilizando o MySQL, desde a instalação até consultas avançadas com JOINs, sendo ideal para iniciantes e para quem deseja dominar SQL de forma prática.

## Requisitos para o Curso

Para acompanhar as aulas e realizar os exercícios, é necessário instalar o MySQL e, opcionalmente, ferramentas como WAMP/XAMPP e PHPMyAdmin.

1. **MySQL**  
   - Sistema de gerenciamento de banco de dados relacional gratuito e open-source.  
   - Download: Disponível no [site oficial do MySQL](https://dev.mysql.com/downloads/).

2. **WAMP ou XAMPP**  
   - Pacotes que incluem MySQL, PHP e um servidor web (Apache) para praticar localmente.  
   - Download WAMP: [wampserver.com](https://www.wampserver.com/).  
   - Download XAMPP: [apachefriends.org](https://www.apachefriends.org/).

3. **PHPMyAdmin**  
   - Ferramenta gráfica para gerenciar bancos MySQL, incluída no WAMP/XAMPP.  
   - Acesso: Após instalar WAMP/XAMPP, abra no navegador (ex.: `localhost/phpmyadmin`).

### Instruções de Instalação
- **MySQL com WAMP/XAMPP**:  
  1. Baixe e instale o WAMP ou XAMPP conforme seu sistema operacional (Windows, Linux, macOS).  
  2. Inicie o servidor MySQL no painel de controle do WAMP/XAMPP.  
  3. Teste o acesso ao MySQL via terminal ou PHPMyAdmin.  
- **MySQL Standalone**:  
  1. Baixe o instalador do site oficial.  
  2. Siga o wizard de instalação, configurando usuário root e senha.  
  3. Use o MySQL Command Line Client ou integre com WAMP/XAMPP.

## Material do Curso

- [Material do Curso](https://www.cursoemvideo.com/curso/mysql/) - Acesse o material oficial, aulas em vídeo e exercícios no site do Curso em Vídeo.

## Ferramentas Utilizadas

O curso utiliza o **MySQL** como banco de dados principal e o **PHPMyAdmin** como interface gráfica opcional. O MySQL é instalado via WAMP ou XAMPP, permitindo criar e manipular bancos de dados com comandos SQL.

- [MySQL Downloads](https://dev.mysql.com/downloads/) - Baixe o MySQL para praticar os comandos ensinados.  
- [WAMP/XAMPP](https://www.apachefriends.org/) - Use para um ambiente completo com MySQL e PHP.

### Como Utilizar o MySQL
1. Após instalar WAMP/XAMPP ou MySQL standalone, abra o terminal MySQL (ou PHPMyAdmin).  
2. Execute comandos SQL como `CREATE DATABASE` ou `SELECT` conforme as aulas.  
3. Use o PHPMyAdmin para visualizar tabelas e dados graficamente, se preferir.  
4. Teste os scripts salvos em arquivos `.sql` executando-os no terminal ou importando no PHPMyAdmin.

## Conteúdo do Curso

O curso é composto por 18 aulas teóricas e práticas, abordando desde os conceitos básicos de bancos de dados até técnicas avançadas de consultas relacionais. Veja o conteúdo detalhado:

- **Aula 1 – O que é um Banco de Dados?**  
  Introdução aos bancos de dados, sua história (arquivos, tabelas, modelos relacionais) e o papel do SQL no MySQL.  
- **Aula 2a – Instalando o MySQL com WAMP**  
  Passo a passo para instalar o WAMP e configurar o MySQL em ambiente Windows.  
- **Aula 2b – Instalando o XAMPP**  
  Instalação do XAMPP como alternativa ao WAMP, com MySQL e PHP integrados.  
- **Aula 3 – Criando o Primeiro Banco de Dados**  
  Uso dos comandos `CREATE DATABASE` e `CREATE TABLE` para iniciar um banco simples.  
- **Aula 4 – Melhorando a Estrutura do Banco de Dados**  
  Aprimoramento de tabelas com tipos de dados (INT, VARCHAR) e restrições (NOT NULL, PRIMARY KEY).  
- **Aula 5 – Inserindo Dados na Tabela (INSERT INTO)**  
  Como adicionar registros com `INSERT INTO`, incluindo múltiplas linhas de uma vez.  
- **Aula 6 – Alterando a Estrutura da Tabela (ALTER TABLE e DROP TABLE)**  
  Modificação de tabelas com `ALTER TABLE` (add, modify, drop column) e exclusão com `DROP TABLE`.  
- **Aula 7 – Manipulando Linhas (UPDATE, DELETE e TRUNCATE)**  
  Atualização de dados com `UPDATE`, exclusão com `DELETE` e limpeza total com `TRUNCATE`.  
- **Aula 8 – Gerenciando Cópias de Segurança MySQL**  
  Técnicas de backup e restauração com `mysqldump` e importação de arquivos `.sql`.  
- **Aula 9 – PHPMyAdmin (Parte 1)**  
  Introdução ao PHPMyAdmin para criar e gerenciar bancos/tabelas graficamente.  
- **Aula 10 – PHPMyAdmin (Parte 2)**  
  Uso avançado do PHPMyAdmin para consultas SQL e administração de dados.  
- **Exercício para Curso de MySQL**  
  Exercício prático para consolidar os conceitos aprendidos até o momento.  
- **Aula 11 – SELECT (Parte 1)**  
  Fundamentos do comando `SELECT` para consultar dados, com filtros básicos (`WHERE`).  
- **Aula 12 – SELECT (Parte 2)**  
  Consultas mais complexas com `ORDER BY`, `LIMIT` e operadores relacionais.  
- **Aula 13 – SELECT (Parte 3)**  
  Uso de funções agregadas (`COUNT`, `SUM`, `AVG`) e `GROUP BY` com `HAVING`.  
- **Aula 14 – Modelo Relacional**  
  Explicação do modelo relacional, chaves primárias e estrangeiras, e normalização.  
- **Aula 15 – Chaves Estrangeiras e JOIN**  
  Criação de relações com chaves estrangeiras e introdução ao `JOIN` (INNER, LEFT, RIGHT).  
- **Aula 16 – INNER JOIN com Várias Tabelas**  
  Aplicação de `INNER JOIN` para combinar múltiplas tabelas em consultas avançadas.

## Status do Curso

- [x] **Fazendo o Curso**  
- [ ] **Curso Concluído**