# crypto-security-anal
Cybersecurity data analysis of cryptocurrency and smart contract exploits using Power BI.

# Incidentes de segurança em cripto | Power BI

As técnicas mais frequentes também concentram a maior parte do capital drenado? Este projeto explora essa pergunta a partir de 1.301 registros de incidentes envolvendo criptomoedas e contratos inteligentes.

## Como fiz a análise

1. Comparei o número de registros por ano na base completa.
2. Identifiquei as 10 técnicas mais frequentes.
3. Criei uma classificação preliminar para o Top 10 com base na técnica registrada. Usei **Bug presumido** para técnicas que sugerem falhas no sistema e **Estudo caso a caso** para as que exigem investigação individual.
4. Comparei o capital bruto drenado entre os grupos e com o total da base.

## Principais resultados

| Classificação preliminar | Registros | Capital bruto drenado |
| --- | ---: | ---: |
| Bug presumido | 333 | US$ 2,03 bilhões |
| Estudo caso a caso | 351 | US$ 5,52 bilhões |

As dez técnicas mais frequentes somaram **684 registros (52,57% da base)** e **35,83% do capital bruto drenado**. Os valores são brutos, antes de descontar eventuais recuperações.

## Prevenção e limitações

A proposta é investigar os casos de maior impacto com uma equipe de cibersegurança e revisar os controles de acesso com as equipes de desenvolvimento e segurança da plataforma. Controle de acesso inadequado foi a técnica mais frequente, com 142 registros.

A base reúne incidentes de vários projetos. Para confirmar as causas de cada caso e avaliar se as mesmas falhas afetam uma plataforma específica, seriam necessários registros internos e evidências técnicas.

## Como abrir o relatório

Baixe o [arquivo analise.pbix](reports/analise.pbix) e abra no Power BI Desktop.

**Fonte dos dados** · [Crypto & Smart Contract Hacks — Kaggle](https://www.kaggle.com/datasets/luthfimuthathohirin/crypto-smart-contract-hacks)
