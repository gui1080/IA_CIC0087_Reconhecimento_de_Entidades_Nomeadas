https://marketplace.visualstudio.com/items?itemName=aprilandjan.ascii-tree-generator

# Trabalho final de "Anotação de Textos e Processamento de Linguagem Natural (CIC0087)"

Prof. Vinícius R. P. Borges

## Reconhecimento de Entidades Nomeadas

Notebook de IA para reconhecimento de entidades nomeadas no Diário Oficial do GDF. Trabalho feito em notebook no Google Colab. Arquivos disponibilizados em extensão ".ipynb". 

UnB, 2021/02

Aluno: Guilherme Braga (17/0162290)

Data de entrega: 10/05/2022

## Scripts

````
.
└── Codigo
    ├── Classificação de todas as entidades
    │   └── 1TrabalhoFinal_CIC0087.ipynb -> Testes inicais, classificando tudo com Polynomila Rolling Hash, com "one-hot label"
    └── Classificação de entidades específicas
        ├── 2TrabalhoFinal_CIC0087.ipynb -> Classificando as entidades pedidas na especificação, testes intensivos com Polynomia/ Rolling Hash, com "one-hot label"
        └── 3TrabalhoFinal_CIC0087.ipynb -> Nova tentativa, com Hashing Vectorizer, acumulando em variável, com "one-hot label"
````

#### Dificuldade maior no experimento: representação de strings em inteiros, configuração de arquitetura de rede, definição de hiperparâmetros, testagem dentro do dataset possível.

## Referências

Github da matéria -> https://github.com/viniciusrpb/cic0087_natural_language_processing/

Outro github da matéria -> https://github.com/UnB-KnEDLe/tutorial_anotacao_contratos_licitacoes

Importando CSV -> https://towardsdatascience.com/3-ways-to-load-csv-files-into-colab-7c14fcbdcb92

Uma tentativa de  Polynomial Rolling Hash -> https://www.geeksforgeeks.org/string-hashing-using-polynomial-rolling-hash-function/

Otimização de gradiente descendente -> https://ruder.io/optimizing-gradient-descent/

LSTM notebook (Matheus Stauffer) -> https://github.com/mstauffer/tcdf_text_classification/blob/main/aula_lstm_tcdf.ipynbre