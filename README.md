# Airbnb_Berlim_2022
O Airbnb é uma plataforma de aluguel de imóveis em que qualquer pessoa pode cadastrar seu imóvel para ficar disponível para alugar.

O objetivo desse modelo é prever diárias de Berlim - Alemanha no Airbnb  para pessoas comuns (classe média), ou seja, imóveis de alto padrão, caros e grandes são tratados como outliers. Também serve para uma pessoa que queira alugar um imóvel, calcular se o preço do imóvel que ela deseja alugar está com um valor alto, normal ou abaixo do valor justo.

A base de dados foi baixada diretamente do Airbnb, porém os dados gratuitos só são disponibilizados a cada trimestre e ficam disponíveis apenas os 4 últimos semestres. Assim, as bases usadas foram os semestres 04/2021, 01/2022, 02/2022 e 03/2022.

Link da base de dados: http://insideairbnb.com/get-the-data/

Esse modelo de previsão foi feito por Python no Jupyter Notebook. Principais bibliotecas usadas: Pandas, Numpy, Scikit-learn, Matplotlib.

Continuarei atualizando esse dataset à medida que for sendo disponibilizados mais semestres. Acredito que o modelo irá melhorar tendo mais dados para treinar o modelo.

O deploy desse modelo de previsão foi feito pelo Streamlit.

URL do modelo de previsão: https://regisbarbosa-airbnb-berlim-2022-testedeployberlim-zt87hh.streamlit.app/
