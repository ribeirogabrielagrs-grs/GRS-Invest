# grs-invest
Desafio de Projeto no Excel criando uma ferramenta que simula investimentos em fundos imobiliários, do aporte de cada mês aos dividendos que ele rende.

A GRS Invest é uma ferramenta de apoio ao planejamento financeiro e à simulação de investimentos em Fundos de Investimento Imobiliário (FIIs). Ela permite estimar a formação de patrimônio ao longo do tempo, calcular dividendos mensais estimados e sugerir uma distribuição dos aportes conforme o perfil de investidor escolhido.

A planilha possui duas abas principais:
-APP: área de configuração e simulação dos investimentos, com salário, aporte mensal, prazo, rentabilidade, patrimônio estimado, dividendos e distribuição por tipo de FII.
-Chave: base de dados que relaciona cada perfil investidor aos percentuais sugeridos para cada categoria de FII.

Para automatizar os cálculos foram utilizadas duas funções chaves, sendo a função VF e função PROCV.
A função VF calcula o valor futuro de uma sequência de aportes periódicos, considerando uma taxa de rendimento e um prazo determinado.
A função PROCV consulta a aba Chave para encontrar o percentual correspondente ao perfil selecionado e ao tipo de FII.

A planilha utiliza os seguintes intervalos nomeados, vinculados às células da aba APP:
Célula D14 - salario: salário informado pelo usuário;
Célula D15 - rendimento_carteira: taxa mensal de rendimento da carteira;
Célula D16 - sugestao_rendimento: sugestão de investimento equivalente a 30% do salário;
Célula D19 - aporte: valor estimado investido mensalmente;
Célula D20 - qtd_anos: prazo do investimento em anos;
Célula D21 - taxa_mensal: taxa de rendimento mensal;
Célula D22 - patrimonio: patrimônio acumulado estimado.

As mudanças em relação a ferramenta do Expert estão relacionadas a personalização dos dados e configurações visuais.
