# Arquivos:

- **pre_preocess_image.ipynb**: pega as imagens original e corta a região desejada. Salva a banda de cada região em um arquivo separado.

- **join_image_bands.ipynb**: salva as informações de cada arquivo TIF (banda) em um único arquivo 

- **pre_preocess_image_2.ipynb**: Junta os arquivos das bandas de para formar uma imagem com cores

- **main_knn_zamith.ipynb**: Classificação por KNN

- **main_rn_2.ipynb**: Classificação por RN

- pasta "bangalore_data": imagem com gabarito para o treino da rede nural
    - l5_Bangalore2011_raw.tif - imagem TIF utilizada para o treino
    - l5_Bangalore2011_builtup.tif - gabarito da imagem treino
    - l5_Hyderabad2011_raw.tif: Utilizado para testar a rede. Não é utilizada no código

# Sites/tutoriais utilizados como base para os códigos

- https://towardsdatascience.com/neural-network-for-satellite-data-classification-using-tensorflow-in-python-a13bcf38f3e1
- https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/
- https://towardsdatascience.com/land-cover-classification-in-satellite-imagery-using-python-ae39dbf2929
- (git do site acima) https://github.com/syamkakarla98/Satellite_Imagery_Analysis
- http://bigearth.net/