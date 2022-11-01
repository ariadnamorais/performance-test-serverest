<h1 align="center">📈 Teste de Performance 📈</h1>

[![Badge ServeRest](https://img.shields.io/badge/API-ServeRest-green)](https://github.com/ServeRest/ServeRest/)
[![Generic badge](https://img.shields.io/badge/JMeter-v5.5-green.svg)](https://jmeter.apache.org/usermanual/get-started.html)

<h1>Requisitos do Teste</h1>

- 5 usuários simultâneos
- 5min de execução (300 segundos)

<h1>Pré-requisitos de execução</h1>

- Possuir ServeRest rodando localmente na porta 3000, conforme orientado na documentação [![Badge ServeRest](https://img.shields.io/badge/API-ServeRest-blue)](https://github.com/ServeRest/ServeRest/#teste-de-carga)
- Instalar o JMeter [![Generic badge](https://img.shields.io/badge/JMeter-v5.5-blue.svg)](https://jmeter.apache.org/usermanual/get-started.html)

<h1>Como executar o teste</h1>

1. Clone este repositório e execute o ServeRest localmente na porta 3000
2. Abrir o JMeter e clicar em File > Open
3. Navegar entre as pastas e selecionar o arquivo 'PlanoDeTeste.jmx'
4. Com o plano de teste aberto, clicar em 'CSV Data Set Config - User'
5. Em 'Filename' inserir o caminho que o arquivo 'massa.csv' está na sua máquina ou clicar em 'Browse' para navegar entre as pastas e procurar arquivo (Este arquivo está neste repósitório)
6. Para executar o teste, clique em 'Start' ou Run > Start

  - O teste poderá ser visualizado em 'View Results Tree'
  - O resultado do teste está em 'Aggregate Report'

<h1>Resultado</h1>

<img src="https://user-images.githubusercontent.com/49946466/199149174-98496c20-eba8-4914-b83d-6c05936d97e4.png" alt="drawing" width="1100"/>

<h1>Análise do teste</h1>

Análise: [Documentado aqui](https://sepia-thought-308.notion.site/Teste-de-Performance-ServeRest-958b80bf509e489dbb04cac9fda65af9)


<h1 align="center"> Autora </h1>

🥷🏼 Ariadna Morais

💼 QA Tester
🎓 Análise e Desenvolvimento de Sistemas

📲 Rede de contato:
[Linkedin](https://www.linkedin.com/in/ariadna-patricio-morais/)
