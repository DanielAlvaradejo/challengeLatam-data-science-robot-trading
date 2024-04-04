# 🤖 Robot Trading Data Science Challenge

## Descripción del Proyecto
Se realizó un robot de trading para crear alertas de compra/venta de Bitcoin con el uso de un algoritmos básico, así como el uso de indices como MACD y Oscilador estocástico.

## Características
El sistema consta de dos algoritmos: uno de naturaleza básica y otro que emplea un enfoque basado en el oscilador estocástico y MACD. Ambos algoritmos operan con una frecuencia de ejecución cada 30 segundos, si bien el objetivo es ajustar esta frecuencia a un intervalo de ejecución de cada 5 minutos.

Para el algoritmo básico, se siguen las siguientes reglas:

- Si el precio actual es mayor o igual al precio promedio y la tendencia es bajista, se recomienda la acción 'Vender'.
- Si el precio actual es menor que el precio promedio y la tendencia es alcista, se recomienda la acción 'Comprar'.
- En caso de no cumplirse ninguna de las condiciones anteriores, se sugiere la acción 'Esperar'.

En cuanto al algoritmo basado en el oscilador estocástico y el MACD, este calcula el estado del mercado y del Bitcoin (BTC) para determinar si se encuentra en una situación de sobrecompra, sobreventa o en un estado neutro. Las recomendaciones del algoritmo se rigen por las siguientes pautas:

- Si la tendencia es alcista y el estado es sobrevendido, se aconseja comprar.
- Si la tendencia es bajista y el estado es sobrecomprado, se aconseja vender.
- En cualquier otro caso, se recomienda esperar.

## Instalación y Uso
Para poder hacer uso de este robot, puedes acceder a el desde google colab, o en su defecto, utilizar algún compilador de python en tu computadora, debes asegurarte de incluir:

- yfinance
- pandas
- numpy
- matplotlib
- requests
- BeautifulSoup
- smtplib
- mpl_finance
- IPython.display

## Resultados
El algoritmo combinado de Oscilador con MACD mostró ser más eficaz en algunas ocasiones, además de ayudar a entender mejor las tendecias del mercado y el estado de este. Asu vez se incluyeron varías gráficas para mejorar la visualización del movimiento del bitcoin para una futura implementación de algoritmos más avanzados


## Contacto
Linkedin: https://www.linkedin.com/in/daniel-alvaradejo/overlay/background-image/
