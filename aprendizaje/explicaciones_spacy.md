## NlP y en_core_web_sm

- spacy.load("en_core_web_sm) -> carga un modelo de spaCy que incluye un tokenizador, vocabulario, reglas de sementación de oraciones, etiquetado gramatical (POS-taggin), lematizador y parser. Es small, así que tiene limitaciones.
- así, el objeto devuelto por nlp es una función que procesa texto y devuelve un objeto con info estructurada

## Doc

Aquí doc contiene cada palabra y signo de puntuación como Token iterable:

`doc = nlp(lolly)

tokens = [token.lemma_.lower() for token in doc 
          if token.is_alpha and not token.is_stop]`

En este caso, además, hemos personalizado la lista de STOP WORDS para evitar que se nos eliminen negaciones o matizaciones, que pueden ser útiles para el análisis literario. 