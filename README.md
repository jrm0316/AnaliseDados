Qual o percentual e quanto as vendas online representam das vendas da empresa?
- Faturamento_Total: Sum(Vendas[Faturamento])
- Faturamento Online: Calculate para somar o Faturamento – CALCULATE(Sum(Vendas[Faturamento]) Vendas[Loja]=”Online”)
- % Faturamento Online: DIVIDE([Faturamento Online], [Faturamento_Total], “Sem faturamento”)
