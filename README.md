# Modelo para Recomendação de Requisitos de Cibersegurança em Histórias de Usuário Utilizando Processamento de Linguagem Natural

# Descrição dos Notebooks

## `all_user_stories.txt`

Contém o conjunto completo de histórias de usuário obtidas em [zenodo.org/records/13880060](https://zenodo.org/records/13880060). Desse total, 80% foram utilizadas na construção da base de palavras e os 20% restantes reservados para testes dos métodos aplicados.

## `extracao_palavras_historias_usuario_sprint_final.ipynb`

Notebook com o código-fonte responsável pela extração e tratamento das palavras presentes nas histórias de usuário.

## `Busca_completa_G21_base_palavras_flexionadas.ipynb`

Notebook que implementa os métodos de busca direta e com lematização, aplicados sobre as histórias presentes no arquivo `saida_palavras_flexionadas.txt`.

## `geracao_base_palavras_QEs_lematizada.ipynb`

Notebook que implementa a lematização nas bases de palavras classificadas, a fim de gerar uma nova base com todas as variações de uma palavra, não só sua forma canonica.
