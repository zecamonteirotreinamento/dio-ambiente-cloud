# 🚀 Configuração de Máquina Virtual e Banco de Dados no Azure

## 🖥️ Criação de Máquina Virtual

Ao criar uma máquina virtual no Azure, há diversas configurações a serem preenchidas. Dependendo da imagem (modelo escolhido), o valor pode variar bastante. No entanto, configurar cada critério individualmente, em vez de utilizar uma imagem pronta, proporciona um melhor aproveitamento dos recursos da nuvem.

## 🗄️ Criação de Banco de Dados

Na criação de um banco de dados, é necessário configurar um servidor e escolher o tipo de autenticação. Apesar de definir um nome para o servidor, você não tem acesso direto a ele, pois se trata de um modelo *PaaS* (*Platform as a Service*). 

Durante a criação, é essencial escolher o tipo de redundância, que influencia diretamente no SLA (*Service Level Agreement*). Ao selecionar o tipo de redundância, a plataforma apresenta o custo correspondente para o banco de dados.

## 💰 Cálculo de Custos

Para estimar os custos dos serviços do Azure, é possível utilizar a [Calculadora de Custos](https://azure.microsoft.com/pt-br/pricing/calculator/). Essa ferramenta permite simular diferentes configurações e obter uma previsão de gastos com base nas escolhas feitas.

