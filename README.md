# Minicurso: Análise de Dados na Prática

Material do minicurso para estudantes de Análise e Desenvolvimento de Sistemas.
Tudo roda no **Google Colab**: ninguém precisa instalar nada.

## Ideia do minicurso
Em vez de começar pelas ferramentas, começamos por **perguntas** e investigamos os dados para respondê-las. O ciclo que usamos o tempo todo:

**pergunta → dados → limpeza → exploração → resposta → comunicação**

## Como abrir
| Notebook | Para quê | Abrir |
|---|---|---|
| `notebooks/01_titanic_guiado.ipynb` | Investigação guiada com o Titanic | [Abrir no Colab](https://colab.research.google.com/github/vhymathias/workshop-data-analysis/blob/main/notebooks/01_titanic_guiado.ipynb) |
| `notebooks/02_pratica_solo_wild_rift.ipynb` | Prática sozinho, sem dicas | [Abrir no Colab](https://colab.research.google.com/github/vhymathias/workshop-data-analysis/blob/main/notebooks/02_pratica_solo_wild_rift.ipynb) |
| `notebooks/04_desafio_extra_song_longevity.ipynb` | Desafio extra para quem terminar antes | [Abrir no Colab](https://colab.research.google.com/github/vhymathias/workshop-data-analysis/blob/main/notebooks/04_desafio_extra_song_longevity.ipynb) |

No Colab, use **Arquivo → Salvar uma cópia no Drive** para poder editar. Rode as células com `Shift + Enter`.

## Roteiro sugerido (assumindo ~3 h)
| Tempo | Etapa |
|---|---|
| 15 min | Abertura: o ciclo da análise e como abrir o Colab |
| 75 min | Titanic guiado (partes 0 a 9 do notebook), com pausas para discussão |
| 10 min | Intervalo |
| 60 min | Prática solo no segundo dataset, sem dicas |
| 20 min | Cada pessoa apresenta 3 frases "para um leigo" |

Ajuste os tempos à duração real do evento.

## Prática solo
Depois de aprender o método no Titanic, cada pessoa investiga um dataset novo, sozinha:
- **Wild Rift (principal):** 508 partidas ranqueadas, 57 colunas. Tem erros reais nos dados, que pedem limpeza.
- **Song Longevity (extra):** 45.000 faixas, 21 colunas. Pede cuidado com colunas que "entregam" a resposta (vazamento).

Os notebooks baixam os dados sozinhos com `kagglehub`, sem login, então **não é preciso subir CSVs** neste repositório.

## Checklist do ciclo (use em qualquer dataset)
- [ ] Conheci os dados: tamanho, colunas, tipos
- [ ] Olhei os valores faltantes e decidi o que fazer
- [ ] Procurei valores estranhos (outliers)
- [ ] Respondi cada pergunta com número ou gráfico
- [ ] Separei o que os dados mostram do que eles **não** provam (correlação ≠ causa)
- [ ] Resumi em 3 frases para quem não é de dados

## Estrutura do repositório
```
.
├── README.md
├── notebooks/
│   ├── 01_titanic_guiado.ipynb
│   ├── 02_pratica_solo_wild_rift.ipynb
│   └── 04_desafio_extra_song_longevity.ipynb
└── data/
    └── README.md
```
