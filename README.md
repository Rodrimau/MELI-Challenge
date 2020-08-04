# MELIChallenge

|-Exploratorio
  |-Generation_discount.ipynb: Generación de Datasets partir de recursos de la API de MErcado Libre. Transformacón de ese Json a un .csv
  |-Exploration.ipynb : Analisis exploratorio de los datasets de categorías antes y despues del Hotsale de publicaciones con descuentos y analisis de features de publicaciones.

|-Modelado
  |-Generation_sold.ipynb: Generación y transformación del dataset con publicaciones para predecir la Sold_Quantity
  |-Validaciones: Carpeta con 5 experimentos realizados para encontrar el mejor modelo variando algoritmos y sampleos.
  |-Prediction.ipynb: Aplicación del mejor modelo encontrado y creación de pipeline para aplicar a publicaciones mediante el ID.

|-requirements.txt: Libreria necesarias


|- Los archivos demasiados pesados, como los .json raws y algunos .csv, se guardaron en: https://drive.google.com/drive/folders/1XsDKL_E0l3nvvWXih1c5gmR4m_dO2MBH?usp=sharing
