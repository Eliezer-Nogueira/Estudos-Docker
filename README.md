# Projeto Criado a partir do Desafio 01 da Dio 

## Caso de Uso :

Utilizar Docker Compose para executar uma aplicação HTML em um Container Apache. Você poderá ir além e fazer alterações mais robustas ao seu projeto, estilizando sua página e utilizando seus conhecimentos em (HTML, CSS e JS). Você também pode buscar outras formas para executar seu arquivo HTML em outras Linguagens de Programação.

## Objetivo Proposto

A partir do caso de uso apresentado pela DIO, resolvi utilizar o compose para subir uma aplicação em CLOUD para um repositório de Arquivos.

## Implementação do Desafio

### Conclusão do Desafio

Com base no desafio proposto, foi criado um arquivo YML que define a configuração de um servidor Apache (httpd) e um serviço de banco de dados PostgreSQL. Este projeto exemplifica a execução de uma aplicação HTML simples dentro de um container Apache, demonstrando a integração eficiente entre o servidor web e o banco de dados utilizando Docker Compose.

### Passo a Passo:

1. **Configuração do ambiente:**
   - A versão do Docker Compose utilizada foi a 3.7.
   
2. **Definição dos serviços:**
   - **Serviço cloudpessoal:** Utiliza a imagem `nextcloud:apache` para o servidor Apache.
   - **Serviço db:** Utiliza a imagem `postgres:alpine` para o banco de dados PostgreSQL.

3. **Configuração das variáveis de ambiente:**
   - Foram definidas variáveis de ambiente para ambos os serviços, incluindo host do PostgreSQL, senha, nome do banco de dados e usuário.

4. **Exposição das portas e volumes:**
   - O serviço Apache foi configurado para expor a porta 80.
   - Volumes foram definidos para persistir os dados do servidor web e do banco de dados.

5. **Subida dos serviços:**
   - Utilizando Docker Compose, os serviços foram iniciados e configurados para reiniciarem automaticamente (restart: always).

6. **Envio para o GitHub:**
   - O arquivo YML e a aplicação foram enviados para um repositório no GitHub.

### Conclusões Finais

Este projeto destacou a utilização de Docker Compose para a criação e gerenciamento de containers, facilitando a implementação de uma aplicação web simples com integração de banco de dados. Foi uma excelente oportunidade para aplicar conhecimentos em Docker, Apache e PostgreSQL, além de fortalecer o portfólio de projetos no GitHub.

