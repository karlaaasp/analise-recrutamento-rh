# Análise Exploratória do Processo de Recrutamento (RH)

Projeto de People Analytics que investiga um processo seletivo a partir de três tabelas: **candidatos**, **vagas** e **processo seletivo**. O objetivo é responder perguntas de negócio do RH, como quais fontes de recrutamento convertem mais, onde o funil perde candidatos e quanto tempo leva para contratar.

 Os dados utilizados são fictícios, criados para fins de estudo.

## Ferramentas

- Python (pandas, numpy)
- Matplotlib e Seaborn para as visualizações
- Google Colab

## Etapas do projeto

1. **Estrutura dos dados:** `shape`, `info`, `describe` e `head` de cada tabela.
2. **Qualidade dos dados:** valores nulos, duplicidades, categorias escritas de formas diferentes e outliers.
3. **Limpeza:**
   - padronização de grafias (fonte de recrutamento e gênero);
   - remoção de duplicatas;
   - tratamento de idades fora do esperado e de um salário discrepante;
   - preenchimento de nulos com a mediana ou com "Não informado".
4. **Análise:** 10 perguntas de negócio, cada uma com uma conclusão e uma recomendação para o RH.
5. **Visualizações:** gráficos de barras com Seaborn.

## Perguntas respondidas

| # | Pergunta | Destaque |
|---|----------|----------|
| 5.1 | Quais fontes geram melhores candidatos? | LinkedIn lidera a conversão (16,79%), mas a diferença entre as fontes é pequena |
| 5.2 | Qual é o funil do processo seletivo? | Distribuição equilibrada entre as etapas |
| 5.3 | Quanto tempo leva para contratar? | Média de 24 dias |
| 5.4 | Quais áreas têm mais dificuldade para preencher vagas? | Operações e Marketing têm as menores taxas de conversão (cerca de 14%) |
| 5.5 | Como as vagas se distribuem por área e senioridade? | Júnior concentra a maioria das vagas |
| 5.6 | Qual o salário médio por área? | Financeiro tem a maior média; Marketing, a menor |
| 5.7 | Quais gestores têm mais vagas abertas? | Um gestor concentra 10 das 25 vagas |
| 5.8 | Qual o perfil de escolaridade por área? | Ver notebook |
| 5.9 | Como está a diversidade de gênero por área? | Ver notebook |
| 5.10 | De onde vêm os candidatos? | Maioria da região metropolitana e Baixada Fluminense |

## Estrutura do repositório

```
├── 01_analise_exploratoria.ipynb   # notebook com toda a análise
└── README.md
```

## Como executar

1. Abra o notebook no Google Colab.
2. Ajuste o caminho dos arquivos CSV (`candidatos.csv`, `vagas.csv` e `processo_seletivo.csv`) na célula de carregamento dos dados.
3. Execute as células em ordem.

## Próximos passos

- Dashboard com os principais indicadores.
- Cruzar a origem geográfica dos candidatos com dados de turnover.

## Autora

**Karla** · [GitHub](https://github.com/karlaaasp)
