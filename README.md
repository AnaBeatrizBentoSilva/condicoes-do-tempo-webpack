# 🌤️ Condições do Tempo - Aplicação de Monitoramento Climático

Este repositório contém um projeto que exibe as condições do tempo em tempo real. A aplicação consome dados da API do OpenWeatherMap e apresenta informações como temperatura, cidade e um ícone representando as condições climáticas (sol, chuva, nublado, etc.).

## 🚀 Objetivo
Criar uma aplicação funcional de monitoramento do clima, implementando:
- **Consumo de API**: Integração com a API do OpenWeatherMap.
- **Exibição Dinâmica**: Mostra a temperatura e o ícone correspondente ao clima.
- **Uso do Webpack**: Empacotamento eficiente dos arquivos para otimizar a performance.
- **JavaScript/TypeScript**: Manipulação de dados e interatividade da aplicação.

## 🔒 Conceitos Abordados
- **Requisições HTTP**: Uso do `fetch` para consumir dados da API.
- **Manipulação de JSON**: Extração e exibição de informações como temperatura e clima.
- **Tratamento de Erros**: Validação da entrada do usuário e tratamento de falhas na requisição.
- **DOM Dinâmico**: Atualização da interface com os dados climáticos em tempo real.
- **Modularização com Webpack**: Organização do código em módulos para facilitar a manutenção e otimizar o carregamento da página.

## 📂 Estrutura do Repositório

```plaintext
.
├── css/
│   ├── AdministradorController.php
│   ├── ExperienciaProfissionalController.php
│   ├── FormacaoAcadController.php
│   ├── Navegacao.php
│   ├── OutrasFormacoesController.php
│   └── UsuarioController.php
├── dist
│   └── Enlatados.png
├── js/
│   ├── Administrador.php
│   ├── ConexaoBD.php
│   ├── ExperienciaProfissional.php
│   ├── FormacaoAcad.php
│   ├── outrasformacoes.php
│   └── Usuario.php
├── node_modules/
│   ├── ADMListarAdministradores.php
│   ├── ADMListarCadastrados.php
│   ├── ADMLogin.php
│   ├── ADMPrincipal.php
│   ├── ADMVisualizarCadastro.php
│   ├── atualizacaoRealizada.php
│   ├── cadastroNaoRealizado.php
│   ├── cadastroRealizado.php
│   ├── informacaoExcluida.php
│   ├── informacaoInserida.php
│   ├── login.php
│   ├── operacaoNaoRealizada.php
│   ├── primeiroAcesso.php
│   └── principal.php
├── ts/
├── index.html
├── package-lock.json
├── package.json
├── tsconfig.json
├── webpack.config.js
└── README.md
