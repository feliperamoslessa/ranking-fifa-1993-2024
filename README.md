# Ranking FIFA 1993-2024

Análise exploratória do ranking histórico da FIFA (masculino), cobrindo mais de 30 anos de dados, desde a primeira publicação do ranking em agosto de 1993.

## 📊 Sobre o projeto

Este projeto explora a evolução do ranking FIFA das seleções nacionais ao longo do tempo, buscando responder perguntas como:

- Quais seleções mais ficaram em 1º lugar no ranking?
- Como a posição do Brasil evoluiu desde 1993?
- Qual confederação (UEFA, CONMEBOL, CONCACAF, etc.) tem, em média, as seleções mais bem ranqueadas?
- Qual foi a maior pontuação já registrada na história do ranking?

## 🗂️ Dataset

- **Fonte:** [FIFA International Soccer Men's Ranking (1993-now)](https://www.kaggle.com/datasets/tadhgfitzgerald/fifa-international-soccer-mens-ranking-1993now) — Kaggle
- **Período:** Agosto de 1993 até os dias atuais
- **Principais colunas:**
  | Coluna | Descrição |
  |---|---|
  | `rank` | Posição no ranking |
  | `country_full` | Nome do país |
  | `total_points` | Pontuação total |
  | `rank_change` | Variação de posição desde a atualização anterior |
  | `confederation` | Confederação (UEFA, CONMEBOL, CONCACAF, AFC, CAF, OFC) |
  | `rank_date` | Data da atualização do ranking |

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn

## 📈 Etapas da análise

1. **Leitura e limpeza dos dados** — ajuste de tipos e criação de colunas auxiliares (ano)
2. **Análise exploratória** — rankings, pontuações e comparações entre confederações
3. **Visualizações:**
   - Evolução do ranking do Brasil ao longo do tempo
   - Comparação entre seleções (Brasil, Alemanha, Argentina, França, Espanha)
   - Top 10 seleções que mais ficaram em 1º lugar
   - Média de posição por confederação (últimos 5 anos)

## 🔍 Principais insights

> Preencha esta seção após rodar o notebook, com os resultados reais obtidos (ex: seleção que mais ficou em 1º, melhor/pior posição do Brasil, confederação mais competitiva etc.)

## 🚀 Como executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/ranking-fifa-1993-2024.git

# Instale as dependências
pip install pandas matplotlib seaborn

# Rode o notebook
jupyter notebook analise_ranking_fifa.ipynb
```

## 📁 Estrutura do repositório

```
ranking-fifa-1993-2024/
├── analise_ranking_fifa.ipynb
├── README.md
└── imagens/
    ├── evolucao_brasil.png
    ├── comparacao_selecoes.png
    ├── top10_primeiro_lugar.png
    └── media_por_confederacao.png
```

## 👤 Autor

**Lessa**
Estudante de Data Science — FIAP

---

*Projeto desenvolvido para fins de estudo e portfólio.*
