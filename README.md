# Mission Control AI 

## Nome da missão
Space Guardian

## Equipe
Data Stars

## Descrição do projeto

O Mission Control AI é um sistema desenvolvido em Python para simular o monitoramento inteligente de uma missão espacial.

O sistema monitora diferentes ciclos da missão, analisando informações importantes como:

- Temperatura interna
- Comunicação com a base
- Sistema de energia
- Suporte de oxigênio
- Estabilidade operacional

Com essas informações, o sistema consegue identificar riscos, gerar alertas automáticos e recomendar ações para manter a segurança da missão.

## Funcionamento

Os dados da missão são armazenados em uma matriz chamada dados_missao.

Cada ciclo possui cinco informações:

- Temperatura
- Comunicação
- Bateria
- Oxigênio
- Estabilidade

Cada informação é analisada e classificada como:

- NORMAL
- ATENÇÃO
- CRÍTICO

Cada classificação gera uma pontuação de risco:

NORMAL = 0 pontos  
ATENÇÃO = 1 ponto  
CRÍTICO = 2 pontos

## Tecnologias e ferramentas utilizadas

- Python: desenvolvimento da lógica do sistema
- Google Colab: criação, execução e testes do código
- GitHub: armazenamento e documentação do projeto

## Conceitos aplicados

- Matrizes
- Listas
- Funções
- Estruturas condicionais
- Estruturas de repetição
- Manipulação de dados

## Principais funções

- analisar_temperatura()
- analisar_comunicacao()
- analisar_bateria()
- analisar_oxigenio()
- analisar_estabilidade()
- classificar_ciclo()
- recomendacao()
- tendencia()
- area_afetada()

## Resultado do sistema

Ao final da análise, o relatório apresenta:

- Pontuação de risco dos ciclos
- Ciclo mais crítico
- Risco médio da missão
- Tendência da operação
- Área mais afetada
- Classificação final

## Conclusão

Durante a simulação, a missão Space Guardian passou por uma falha crítica no ciclo 4.

Com as recomendações automáticas geradas pelo Mission Control AI, os sistemas passaram por recuperação e no ciclo final a missão retornou para uma condição estável e segura.
