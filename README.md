<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a name="readme-top"></a>
<br />
<div align="center">
  <h2 align="center">API de Invoice em Laravel</h2>
  <p align="center">
    Uma API de faturamento simples desenvolvida em Laravel e MySQL!
    <br />
    <a href="https://github.com/DigoFernandes/larave_api"><strong>Veja o projeto »</strong></a>
    <br />
    <br />
    <a href="https://github.com/DigoFernandes/larave_api">Ver Demonstração</a>
    ·
    <a href="https://github.com/DigoFernandes/larave_api/issues">Reportar Bug</a>
    ·
    <a href="https://github.com/DigoFernandes/larave_api/issues">Solicitar Funcionalidade</a>
  </p>
</div>
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Sumário</summary>
  <ol>
    <li><a href="#sobre-o-projeto">Sobre o Projeto</a></li>
    <li><a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a></li>
    <li><a href="#começando">Começando</a></li>
    <li><a href="#uso">Uso</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contribuindo">Contribuindo</a></li>
    <li><a href="#licença">Licença</a></li>
    <li><a href="#contato">Contato</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## Sobre o Projeto

Essa API de faturamento foi desenvolvida para fornecer funcionalidades básicas de criação, atualização e exclusão de faturas. É uma ótima maneira de começar com o desenvolvimento de APIs em Laravel!

<!-- Tecnologias Utilizadas -->
## Tecnologias Utilizadas

* [![Laravel][Laravel.com]][Laravel-url]
* [![MySQL][MySQL.com]][MySQL-url]

<!-- GETTING STARTED -->
## Começando

Para executar este projeto localmente, siga estas etapas simples.

### Pré-requisitos

* PHP >= 7.3
* Composer
* MySQL

### Instalação

1. Clone o repositório
   ```sh
   git clone https://github.com/seu_usuario/seu_repositorio.git

    Instale as dependências do Composer

    sh

composer install

Configure o arquivo .env com suas credenciais do banco de dados
Execute as migrações do banco de dados

sh

php artisan migrate

Inicie o servidor de desenvolvimento

sh

    php artisan serve

<!-- USAGE EXAMPLES -->
Uso

A API fornece os seguintes endpoints:

    GET /invoices: Retorna todas as faturas
    GET /invoices/{id}: Retorna uma fatura específica
    POST /invoices: Cria uma nova fatura
    PUT /invoices/{id}: Atualiza uma fatura existente
    DELETE /invoices/{id}: Exclui uma fatura existente

Exemplo de criação de fatura:

bash

curl -X POST http://localhost:8000/invoices \
-H "Content-Type: application/json" \
-d '{"user_id": 1, "type": "P", "paid": 0, "value": 5000, "payment_date": "2024-03-14 21:09:33"}'

<!-- ROADMAP -->
Roadmap

 Adicionar endpoint para exclusão de faturas
 Adicionar autenticação de usuário

     Implementar paginação de resultados

Veja as issues abertas para uma lista completa de funcionalidades propostas (e problemas conhecidos).
<!-- CONTRIBUTING -->
Contribuindo

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer é muito bem-vinda.

    Faça um fork do projeto
    Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)
    Faça commit de suas mudanças (git commit -m 'Add some AmazingFeature')
    Faça push para a branch (git push origin feature/AmazingFeature)
    Abra um Pull Request

<!-- LICENSE -->
Licença

Distribuído sob a licença MIT. Veja LICENSE.txt para mais informações.
<!-- CONTACT -->
Contato

Rodrigo Souza

Link do Projeto: https://github.com/DigoFernandes/larave_api
