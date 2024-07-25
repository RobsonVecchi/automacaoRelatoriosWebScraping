# Automação de Web Scraping e Relatório em Python

Este projeto Python utiliza Selenium para realizar web scraping de dados de preços de produtos de um site específico. Os dados coletados são formatados e salvos em um arquivo Excel para análise posterior. O script é configurado para rodar periodicamente, automatizando a atualização dos dados.

## Funcionalidades

- **Coleta de Dados**: Utiliza Selenium para acessar e extrair dados de preços de produtos de um site.
- **Formatação de Dados**: Formata os dados extraídos para um formato específico, neste caso, formatando o preço.
- **Exportação para Excel**: Salva os dados formatados em um arquivo Excel (.xlsx) para fácil análise e relatório.
- **Automação**: Configurado para rodar periodicamente, garantindo atualizações regulares dos dados.

## Requisitos

- Python 3.x
- Bibliotecas Python: Selenium, openpyxl

## Como Usar

1. **Clone o repositório:**

   
   git clone https://github.com/RobsonVecchi/automacaoRelatoriosWebScraping/


2. **Instale as dependências:**


   pip install -r requirements.txt
   

3. **Execute o script:**

   
   python app.py
   

4. **Verifique o arquivo Excel gerado:**

   Após a execução, verifique o arquivo `product_data.xlsx` para visualizar os dados coletados.

