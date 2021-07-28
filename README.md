# clasificador-distilbert-custom
Primero, el modelo fue pre entrenado sobre DistilBert-Multilingual (de la libería Transformers de Huggingface) con mas de 300.000 datos hospitalarios sin etiquetar. Luego, lo fine-tunee con un dataset etiquetado para un clasificador binario: la columna text describe un caso hospitalario y la columna label indica si es un caso de accidente o de enfermedad.
