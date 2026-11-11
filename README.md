# tcc-ner-clinico

Repositório de artigos científicos e trabalhos relacionados ao TCC sobre Reconhecimento de Entidades Nomeadas (NER) em textos clínicos em português.

# Artigos científicos — Fundamentação teórica e trabalhos relacionados

Esta seção reúne 10 trabalhos publicados entre 2020 e 2026, selecionados por sua relação com o reconhecimento de entidades nomeadas (NER), especialmente em contextos clínicos e biomédicos, arquiteturas de aprendizado profundo e modelos de linguagem.

A seleção prioriza pesquisas que utilizaram o SemClinBR, sem excluir trabalhos relevantes que utilizaram outros corpora.

| Nº | Ano | Artigo | Objetivo / contribuição | Relação com SemClinBR |
|---:|---:|---|---|---|
| 1 | 2026 | [Clinical Named Entity Recognition in the Portuguese Language: A Benchmark of Modern BERT Models and LLMs](https://arxiv.org/abs/2603.26510) | Compara BioBERTpt, BERTimbau, ModernBERT, mmBERT e LLMs para NER clínico em português. | Sim — utiliza nos experimentos. |
| 2 | 2025 | [Comparative Analysis of Generative LLMs for Labeling Entities in Clinical Notes](https://doi.org/10.1186/s44342-024-00036-x) | Avalia modelos generativos, incluindo Llama 2 e Mistral, na identificação de entidades clínicas. | Não identificado. |
| 3 | 2024 | [BioBBC: A Multi-feature Model That Enhances the Detection of Biomedical Entities](https://doi.org/10.1038/s41598-024-58334-x) | Propõe um modelo de aprendizado profundo baseado em BERT-BiLSTM-CRF para NER biomédico. | Não identificado. |
| 4 | 2024 | [Multilingual Clinical NER for Diseases and Medications Recognition in Cardiology Texts Using BERT Embeddings](https://ceur-ws.org/Vol-3740/paper-09.pdf) | Investiga modelos BERT monolíngues e multilíngues para identificar doenças e medicamentos em textos clínicos. | Não identificado. |
| 5 | 2024 | [Transformer-Based Disease and Drug Named Entity Recognition in Multilingual Clinical Texts: MultiCardioNER Challenge](https://ceur-ws.org/Vol-3740/paper-04.pdf) | Apresenta uma abordagem baseada em Transformers para reconhecimento de doenças e medicamentos em textos clínicos multilíngues. | Não identificado. |
| 6 | 2024 | [MMBERT: A Unified Framework for Biomedical Named Entity Recognition](https://doi.org/10.1007/s11517-023-02934-8) | Apresenta uma arquitetura baseada em BERT para reconhecimento de entidades biomédicas. | Não identificado. |
| 7 | 2023 | [A Review on Electronic Health Record Text-Mining for Biomedical Named Entity Recognition in Healthcare Domain](https://doi.org/10.3390/healthcare11091268) | Revisão de técnicas de mineração de textos clínicos e arquiteturas de NER biomédico. | Não identificado. |
| 8 | 2022 | [SemClinBr: A Multi-institutional and Multi-specialty Semantically Annotated Corpus for Portuguese Clinical NLP Tasks](https://doi.org/10.1186/s13326-022-00269-1) | Apresenta o SemClinBR, sua estrutura, anotações semânticas e aplicações em processamento de linguagem natural clínico. | Sim — artigo de apresentação do corpus. |
| 9 | 2021 | [A Multilabel Approach to Portuguese Clinical Named Entity Recognition](https://www.jhi.sbis.org.br/index.php/jhi-sbis/article/view/840) | Aplica BERT e BioBERTpt com classificação multilabel e compara os resultados com CRF. | Sim — utiliza nos experimentos. |
| 10 | 2020 | [BioBERTpt: A Portuguese Neural Language Model for Clinical Named Entity Recognition](https://aclanthology.org/2020.clinicalnlp-1.7/) | Desenvolve modelos BERT especializados em textos clínicos e biomédicos em português e avalia seu desempenho em NER. | Sim — utiliza nos experimentos. |

## Organização das leituras

Os artigos serão utilizados para:

- **Fundamentação teórica:** conceitos de NER, aprendizado profundo, embeddings e modelos de linguagem.
- **Arquiteturas:** estudo de CNN, LSTM, CRF, BERT, BioBERT e LLMs.
- **Trabalhos relacionados:** identificação de metodologias, bases de dados, métricas e resultados de pesquisas anteriores.
- **Comparação experimental:** apoio à definição das arquiteturas e dos critérios de avaliação do TCC.
- **Análise do SemClinBR:** identificação de pesquisas anteriores que utilizaram o mesmo corpus e comparação de suas metodologias.

## Observações

1. A seleção contempla publicações de 2020 a 2026.
2. Nem todos os trabalhos utilizaram o SemClinBR. Os estudos com outros corpora são importantes para ampliar a fundamentação sobre arquiteturas de NER.
3. O artigo de 2026 está disponível como preprint no arXiv, não devendo ser automaticamente tratado como publicação revisada por pares.
4. A indicação "Não identificado" significa que não foi encontrada evidência de utilização do SemClinBR na descrição consultada.
5. Os trabalhos devem ser fichados considerando objetivo, corpus, entidades, arquitetura, representação dos dados, métricas e principais resultados.

## Critérios de seleção

A prioridade foi dada a trabalhos que:

- Abordam especificamente NER ou NER clínico/biomédico.
- Investigam arquiteturas de aprendizado profundo.
- Utilizam modelos BERT, Transformers, CNN, LSTM, CRF ou LLMs.
- Trabalham com textos clínicos ou biomédicos.
- Apresentam metodologias e resultados que possam contribuir para a comparação experimental proposta neste TCC.
