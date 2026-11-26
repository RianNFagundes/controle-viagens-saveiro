# Controle de viagens da Saveiro

Montei o aplicativo em Google Apps Script e Google Planilhas para acompanhar as saídas e os retornos de um veículo de apoio. O formulário era acessado por um link que podia ser enviado pelo WhatsApp.

| Etapa | O que fica registrado |
| --- | --- |
| Saída | Motorista, setor, cidade, local ou fornecedor, objetivo, hodômetro, combustível e horário. |
| Retorno | Hodômetro final, combustível, horário e observações. |
| Histórico | Status e distância percorrida, calculada pela diferença entre os dois hodômetros. |

## Teste no navegador

Abra [saveiro-demo.html](saveiro-demo.html) e clique em **Download raw file** (ícone de download). Depois, abra o arquivo baixado no navegador. Registre uma saída com **24.000 km** e um retorno com **24.072 km**. A viagem deve aparecer como concluída no histórico, com **72 km** percorridos.

O arquivo é uma versão em HTML, CSS e JavaScript do fluxo original. Use dados fictícios. O histórico fica no armazenamento local do navegador e o nível de combustível é informado em porcentagem.
