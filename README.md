Financa Facil
--------------------------------------------------------------------------------------------------------
Site de educação financeira, Laboratório de Desenvolvimento Web (Prof.ª M.ª Suzana Sousa).
--------------------------------------------------------------------------------------------------------

Problema social escolhido

Gestao de Financas para jovens
--------------------------------------------------------------------------------------------------------

Funcionalidades
Conteúdo educativo: ganhos, gastos, juros compostos, regra 50/30/20, glossário e passo a passo para organizar o mês.
Orçamento mensal: o usuário informa o tipo de ganho (mesada ou salário), o ganho mensal, o ganho com investimentos e o gasto total. O site calcula o saldo, a porcentagem da renda gasta e mostra uma orientação (mês no vermelho, no limite ou guardando 20% ou mais).
Simulador de juros compostos com CDI: o usuário informa valor inicial, aporte mensal, CDI ao mês, percentual do CDI (por exemplo, 115%) e prazo em meses. O site mostra a taxa mensal e anual, o total investido, o rendimento, o valor final e uma tabela de evolução.
Integração: o botão "Usar meu saldo como aporte" leva o saldo do orçamento para o simulador.
Como o cálculo funciona
taxa mensal = (CDI ao mês / 100) x (% do CDI / 100)
saldo       = saldo x (1 + taxa mensal) + aporte      (repetido a cada mês)

Exemplo: CDI de 1% ao mês com rentabilidade de 115% do CDI resulta em 1,15% ao mês.
--------------------------------------------------------------------------------------------------------

Tecnologias
HTML5 (estrutura semântica, tabelas, listas, iframe e formulários com validação)
CSS3 com Flexbox (layout responsivo)
JavaScript (variáveis let e const, template literals, manipulação do DOM e estruturas condicionais)
Estrutura de arquivos
financa-facil/
├── index.html
├── style.css
├── script.js
├── README.md
└── images/
    ├── moedas.svg
    └── crescimento.svg
--------------------------------------------------------------------------------------------------------

Como executar
Baixe ou clone a pasta financa-facil.
Abra a pasta no VS Code (Arquivo → Abrir Pasta...)
Recomendo: instale a extensão Live Server (Ritwick Dey), clique com o botão direito no index.html e escolha Open with Live Server.
--------------------------------------------------------------------------------------------------------

Não é necessário instalar nenhuma dependência.

Este site é apenas educativo e não constitui recomendação de investimento.
--------------------------------------------------------------------------------------------------------

Autor

Raphael de Almeida de Castro. 
--------------------------------------------------------------------------------------------------------
