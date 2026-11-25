# introai-swahili-news
Swahili news classification term project

# Swahili News Classification Term Project

MLP, RNN, Transformer를 이용한 스와힐리어 뉴스 주제 분류 과제입니다.

## Dataset attribution

- Creator: Davis David
- Dataset: Swahili : News Classification Dataset, version 0.2
- Original source: https://doi.org/10.5281/zenodo.5514203
- Download source:
  https://huggingface.co/datasets/community-datasets/swahili_news
- License: Creative Commons Attribution 4.0 International (CC BY 4.0)
- License URL: https://creativecommons.org/licenses/by/4.0/

## Modifications

- Removed empty texts and duplicate texts after normalizing
  letter case and whitespace.
- Removed training texts that also appeared in the test set.
- Sampled 8,000 training records with stratification and random seed 2026.
- Retained 7,337 cleaned test records separately.
- Exported text and label columns as UTF-8 CSV files.

## Labels

0: Finance
1: Local news
2: Sports
3: International news
4: Entertainment
5: Health
