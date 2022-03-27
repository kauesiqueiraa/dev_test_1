# Teste Bolsista de Desenvolvimento

Uma empresa de assinatura de energia está interessada em criar uma calculadora de economia em seu site e consultou você para desenvolver a calculadora para eles. 

Ex.: 

[Simulador - Group Energia - Desconto na conta de luz e gestão de energia](https://groupenergia.com.br/simulador/)

Na calculadora você deverá fazer a leitura da fatura e utilizar os seguintes dados:

- Média de consumo em kWh dos 3 últimos meses disponíveis na fatura
- Tipo de tarifa (Comercial, Residencial e Industrial)
- Valor da tarifa

A empresa de assinatura de energia te forneceu as seguintes premissas para o desconto:

| Consumo (Média) | Desconto (Residencial) | Desconto (Comercial) | Desconto (Industrial) |
| --- | --- | --- | --- |
| Até 10.000 kWh | 18% | 16% | 12% |
| Entre 10.000 kWh e 20.000 kWh | 22% | 18% | 15% |
| Acima de 20.000 kWh | 25% | 22% | 18% |

Alem disso, deve-se considerar os seguintes percentuais de cobertura baseado no consumo:

| Consumo (Média) - kWh | Até 10.000 kWh | Entre10.000 kWh e 20.000 kWh | Acima de 20.000 kWh |
| --- | --- | --- | --- |
| Cobertura | 90% | 95% | 99% |

Na sua saída você deverá apresentar os seguintes dados:

- Economia Anual
- Economia Mensal
- Desconto Aplicado
- Cobertura
