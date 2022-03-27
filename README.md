<h1 align="center"> Teste Bolsista de Desenvolvimento</h1>

Uma empresa de assinatura de energia está interessada em criar uma calculadora de economia em seu site e consultou você para desenvolver a calculadora para eles. Você escolheu a linguagem Python para desenvolver a aplicação. Subir o código para o Github é importante para a sua equipe de desenvolvimento te auxiliar e avaliar o que foi implementado.  

Sua aplicação receberá as seguintes entradas:

- Uma lista contendo o consumo de energia dos últimos 3 meses
- Valor da tarifa da distribuidora
- Tipo de tarifa (Comercial, Residencial e Industrial)

Os resultados da sua aplicação serão:

- Economia Anual
- Economia Mensal
- Desconto Aplicado
- Cobertura

A empresa de assinatura de energia te forneceu as seguintes premissas para o desconto:

| Consumo (Média) | Desconto (Residencial) | Desconto (Comercial) | Desconto (Industrial) |
| --- | --- | --- | --- |
| $\leq$ 10.000 kWh | 18% | 16% | 12% |
| Entre 10.000 kWh e 20.000 kWh | 22% | 18% | 15% |
| Acima de 20.000 kWh | 25% | 22% | 18% |

Alem disso, deve-se considerar os seguintes percentuais de cobertura baseado no consumo:

| Consumo (Média) - kWh | Até 10.000 kWh | Entre10.000 kWh e 20.000 kWh | Acima de 20.000 kWh |
| --- | --- | --- | --- |
| Cobertura*** | 90% | 95% | 99% |

*** Cobertura é o valor da energia que o consumidor irá receber da empresa de assinatura de energia em relação à energia consumida

Por curiosidade, segue um exemplo de uma calculadora em produção: 
[Simulador - Group Energia - Desconto na conta de luz e gestão de energia](https://groupenergia.com.br/simulador/)
