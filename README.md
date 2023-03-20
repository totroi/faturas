# Projeto de leitura e tratamento de fatura de cartão de crédito

Este projeto em Jupyter Notebook usa Python e a biblioteca Pandas para ler um arquivo de fatura de cartão de crédito (fatura.txt), tratar os dados, criar três listas com nomes, datas e valores dos gastos do cartão, gerar um DataFrame com os dados das três listas e exportar um arquivo .csv com os dados do DataFrame.

## Pré-requisitos

- Jupyter Notebook instalado
- Pacote pandas instalado

## Como executar o projeto

1. Clone este repositório em sua máquina local.
2. Abra o arquivo `projeto_fatura.ipynb` em seu Jupyter Notebook.
3. Na célula de código, atualize o caminho do arquivo `fatura.txt` para o caminho em sua própria máquina.
4. Execute as células do notebook em ordem.

## Exportando para uma planilha do Google Sheets

Após a exportação do arquivo .csv, você pode copiar e colar os dados em uma planilha do Google Sheets. É importante que você utilize a opção "separar colunas por vírgulas" para que os dados sejam devidamente formatados na planilha.

A planilha de exemplo fornecida neste projeto classifica automaticamente os gastos em diferentes categorias, como alimentação, transporte e lazer. Além disso, ela indica quais linhas precisam ser classificadas manualmente e fornece um resumo à direita de todos os gastos por categorias.

Para utilizar a planilha de exemplo, siga os passos abaixo:

1. Acesse o link para a [planilha de exemplo](https://docs.google.com/spreadsheets/d/16t6F6dvD1AB1jmNrgl89_RsZ4jjnJeZWmxukPC1G2ns/edit?usp=sharing).
2. Na planilha, selecione a célula A5 e cole os dados da fatura de cartão de crédito que você exportou do arquivo .csv.
3. Utilize a opção "separar colunas por vírgulas" para formatar os dados corretamente.
4. A planilha irá classificar automaticamente a maioria dos gastos em diferentes categorias. Verifique se os gastos foram corretamente classificados e ajuste manualmente aqueles que não foram classificados corretamente (estarão destacados em verde).
5. Utilize a tabela de resumo à direita para ver uma visão geral de seus gastos por categorias. Caso haja discrepância entre a soma dos dados classificados e os dados totais, a planilha indicará isso com a cor amarela no valor da soma dos gastos classificados.

## Detalhes técnicos

O projeto faz uso de conceitos básicos de programação, como leitura e escrita de arquivos, manipulação de listas e dicionários, bem como o uso da biblioteca Pandas para criar um DataFrame e fórmulas intermediárias e avançadas para visualização dos dados no Google Sheets. Além disso, o projeto faz uso de recursos de data e hora do computador para nomear o arquivo .csv exportado.

## Licença

Este projeto é distribuído sob a licença MIT. Sinta-se livre para usá-lo, modificá-lo e distribuí-lo, desde que a fonte original seja atribuída e o autor não seja responsabilizado por quaisquer danos decorrentes do uso deste projeto.

## Autor

Este projeto foi criado por Daniel Costa de Castro e é distribuído sob a licença MIT.
