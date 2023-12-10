# Processamento de Dados do ENARE 2023

Este projeto consiste em um Jupyter Notebook desenvolvidos para processar e analisar os dados dos participantes do ENARE (Exame Nacional de Residência) de 2023. O objetivo é calcular a nota final dos participantes e gerar arquivos CSV organizados por residência médica.

## Descrição

O ENARE é o concurso unificado de residência médica. O script desenvolvido neste repositório foca na combinação de diferentes conjuntos de dados de participantes, incluindo suas notas e outros atributos relevantes, e calcula a nota final com e sem bônus, dependendo da participação em programas como PROVAB e PRMGFC.

## Características Principais

- Combinação de dados de diferentes fontes.
- Cálculo da nota final dos participantes.
- Geração de arquivos CSV por residência médica.

## Extração de Dados

Para a extração de dados dos resultados da prova escrita e da análise de currículo, foi utilizado o `pdfplumber`, uma ferramenta eficaz para extrair informações de arquivos PDF. Isso permitiu processar os dados diretamente dos documentos oficiais do ENARE, garantindo precisão e eficiência.

## Uso

O notebook principal pode ser executado com Python e requer os pdfs com as notas do exame escrito e a nota do exame final. Cada PDF pode ser baixado no site oficial do enare e deve conter informações sobre a residência e os dados dos candidatos. Os dados são então combinados, processados e salvos em arquivos CSV, um para cada residência médica.

### Dependências

- Python
- Pandas
- NumPy
- pdfplumber


# Resultados
Os resultados estão na pasta Resultados.zip e podem ser baixados. Os arquivos estão em xlms
