# Controle de viagens da Saveiro

Projeto de automação de frota de Rian Nascimento Fagundes. O aplicativo original foi criado com Google Apps Script e Google Planilhas para organizar os deslocamentos de um veículo de apoio e facilitar a consulta ao histórico.

## Fluxo do aplicativo original

| Etapa | O que é registrado |
| --- | --- |
| Saída | Motorista, setor, cidade, local ou fornecedor, objetivo, hodômetro inicial, combustível e horário. |
| Retorno | Hodômetro final, combustível, horário e observações. |
| Histórico | Status da viagem, distância calculada pela diferença de hodômetro e dados consolidados em planilha. |

O acesso era feito por um link que podia ser compartilhado pelo WhatsApp. O Google Apps Script fazia a ponte entre o formulário e o histórico no Google Planilhas.

## Demonstração de portfólio

Baixe o arquivo [saveiro-demo.html](saveiro-demo.html) pelo GitHub e abra-o no navegador. Registre uma saída com valores fictícios e, em seguida, um retorno. Confira a distância e o status no histórico. Por exemplo, uma saída com 24.000 km e um retorno com 24.072 km resultam em 72 km rodados.

A demonstração foi reconstruída em HTML, CSS e JavaScript com base no fluxo original. Ela guarda os registros localmente no navegador e usa porcentagem para representar o nível de combustível. O código publicado aqui é o da demonstração.
