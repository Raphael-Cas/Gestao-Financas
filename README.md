# Finança Fácil

Site de educação financeira para jovens, desenvolvido como prova prática da disciplina **Laboratório de Desenvolvimento Web** (Prof.ª M.ª Suzana Sousa).

## Problema social escolhido

Muitos jovens recebem mesada ou o primeiro salário sem nunca terem aprendido a controlar gastos ou a investir. O site ensina conceitos básicos de finanças e oferece duas ferramentas práticas para o estudante testar na hora.

## Funcionalidades

- **Conteúdo educativo:** ganhos, gastos, juros compostos, regra 50/30/20, glossário e passo a passo para organizar o mês.
- **Orçamento mensal:** o usuário informa o tipo de ganho (mesada ou salário), o ganho mensal, o ganho com investimentos e o gasto total. O site calcula o saldo, a porcentagem da renda gasta e mostra uma orientação (mês no vermelho, no limite ou guardando 20% ou mais).
- **Simulador de juros compostos com CDI:** o usuário informa valor inicial, aporte mensal, CDI ao mês, percentual do CDI (por exemplo, 115%) e prazo em meses. O site mostra a taxa mensal e anual, o total investido, o rendimento, o valor final e uma tabela de evolução.
- **Integração:** o botão "Usar meu saldo como aporte" leva o saldo do orçamento para o simulador.

## Como o cálculo funciona

```
taxa mensal = (CDI ao mês / 100) x (% do CDI / 100)
saldo       = saldo x (1 + taxa mensal) + aporte      (repetido a cada mês)
```

Exemplo: CDI de 1% ao mês com rentabilidade de 115% do CDI resulta em 1,15% ao mês.

## Tecnologias

- HTML5 (estrutura semântica, tabelas, listas, `iframe` e formulários com validação)
- CSS3 com Flexbox (layout responsivo)
- JavaScript (variáveis `let` e `const`, template literals, manipulação do DOM e estruturas condicionais)

## Estrutura de arquivos

```
financa-facil/
├── index.html
├── style.css
├── script.js
├── README.md
└── images/
    ├── moedas.svg
    └── crescimento.svg
```

## Como executar

1. Baixe ou clone a pasta `financa-facil`.
2. Abra a pasta no VS Code (**Arquivo → Abrir Pasta...**).
3. Opção simples: dê dois cliques no `index.html` para abrir no navegador.
4. Opção recomendada: instale a extensão **Live Server** (Ritwick Dey), clique com o botão direito no `index.html` e escolha **Open with Live Server**.

Não é necessário instalar nenhuma dependência.

> O `iframe` (artigo da Wikipédia) e as fontes do Google precisam de conexão com a internet. Sem internet, o site continua funcionando com fontes padrão do sistema.

## Requisitos da prova atendidos

| Módulo | Onde está |
|---|---|
| HTML5 (2,0 pts) | `index.html`: tags semânticas, títulos de `h1` a `h6`, `abbr`, `cite`, `q`, `blockquote`, imagens, links com `target="_blank"`, tabelas, listas, `iframe` e formulários com `label`, `placeholder`, `required`, submit e reset |
| CSS3 e Flexbox (1,5 pts) | `style.css`: arquivo externo, seletores universal, de tag, de classe e de id, e Flexbox com `flex-direction`, `flex-wrap`, `justify-content` e `align-items` |
| JavaScript (1,5 pts) | `script.js`: `let` e `const`, captura de dados dos formulários, template literals com `innerHTML` e `console.log`, e condicionais com `===`, `!=`, `&&`, `||`, `!` e ternário |
| Defesa oral (1,0 pt) | Explicação da estrutura HTML, do Flexbox e da lógica do script |

## Aviso

Este site é apenas educativo e não constitui recomendação de investimento.

## Autor

Nome do estudante: _______________________
Disciplina: Laboratório de Desenvolvimento Web
Docente: Prof.ª M.ª Suzana Sousa
