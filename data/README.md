# Datasets

Os dados **não ficam neste repositório**: os notebooks baixam direto do Kaggle com `kagglehub` (funcionou no Colab sem login).

| Uso | Dataset | Arquivo | Tamanho |
|---|---|---|---|
| Notebook guiado | Titanic via `seaborn.load_dataset("titanic")` | (baixa sozinho) | 891 linhas |
| Prática solo | [Wild Rift Ranked Match](https://www.kaggle.com/datasets/berkutayasan/2026-wild-rift-ranked-match-dataset) | `ranked_match_data_kaggle.csv` | 508 linhas, 57 colunas |
| Desafio extra | [Song Longevity](https://www.kaggle.com/datasets/sergionefedov/song-longevity-why-some-hits-last) | `song_longevity.csv` + `data_dictionary_songs.csv` | 45.000 linhas, 21 colunas |

```python
import kagglehub
path = kagglehub.dataset_download("berkutayasan/2026-wild-rift-ranked-match-dataset")
```

## Antes de redistribuir
Se quiser subir os CSVs aqui (plano B caso o Kaggle falhe no dia), **confira a licença** na aba *Metadata* de cada dataset. O Song Longevity não mostra licença na página.
