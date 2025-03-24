# Analisis de Regresion

Análisis de regresión lineal múltiple mediante matrices que permitan construir un modelo predictivo que permita pronosticar el precio de una casa a partir de diversas variables que la definen

Cargamos las librerías y módulos necesarios y los datos con los que estaremos trabajando
<br>![image](https://github.com/user-attachments/assets/ce42cf80-1e69-42ee-80e9-653ca4a29b0b)

Utilizando el metodo info obtenemos la información de las diferentes columnas y su Dtype para elegir las que estaremos utilizando para trabajar, en este caso: "Intercepto", "price", "bedrooms", "bathrooms", "sqft_living", "sqft_lot", "floors", "waterfront", "view", "condition", "grade", "sqft_above", "yr_built", "sqft_living15", "sqft_lot15"
<br>![image](https://github.com/user-attachments/assets/1782f757-d96e-4dce-8782-fd3e69f4a359)

Dividimos la información en nuestras variables independientes y la variable dependiente
<br>![image](https://github.com/user-attachments/assets/34de097c-99ab-4cee-9792-41228abcb757)

Realizamos nuestro cálculo de las betas
<br>![image](https://github.com/user-attachments/assets/331a58b4-7c64-4139-bf5e-3c478349cb58)

Realizamos nuestro calculo manual para obtener la suma total de cuadrados, la suma explicada de cuadrados y residuales al cuadrado para obtener nuestro coeficiente de determinacion R Cuadrada y R cuadrada ajustada
<br>![image](https://github.com/user-attachments/assets/9ebe34b0-4bb9-4d8d-99a8-7e9e8b125b99)

Realizamos el cálculo automatizado y comprobamos que obtenemos valores muy similares
de 65%, posiblemente normalizar la información mejore la confianza del modelo debido a los rangos utilizados y tipo de información
<br>![image](https://github.com/user-attachments/assets/b9f17287-9661-4344-b688-5f15abbb8cae)

Para concluir realizamos la aplicación sobre la base de prueba
<br>![image](https://github.com/user-attachments/assets/fe4284f1-160f-415b-87ac-e0ff0debc3e2)

Una vista rapida a la gráfica de histogramas vemos que el modelo se ajusta a una distribución normal
<br>![image](https://github.com/user-attachments/assets/870c8b40-338f-4dad-900f-abb2cd7cdb30)
