<p align="center"><img src="https://i.imgur.com/XrpnuvM.jpg" width="1500" heigth="500"></p>

# _Proyecto de Visión por Computador: Descriptor de Acciones mientras se Conduce_
- Henry Peña
- Diego Medina



**Universidad Industrial De Santander** </br>
**Ingenieria de sistemas**</br>
**2019**</br>
<p align="center"><img src="http://garza.uis.edu.co/idayregreso/images/logoUIS.jpg" width="342" heigth="166"></p>

<p align="center"><img src="https://storage.googleapis.com/kaggle-competitions/kaggle/5048/media/drivers_statefarm.png" width="1500" heigth="500"></p>

# ¡Dale click para ver el video!

[![Foo](https://i.imgur.com/pCV60S7.jpg)](https://youtu.be/SEwkZdSYvYc)


# Introduccion

En Colombia en 2016 hubo accidentes 85.426 accidentes automovilísticos con heridos y 3.406 con muertos causados por conductores distraídos. Según Fesvial, Federación Española de la Seguridad Vial, el 45% de los accidentes se podrían prevenir si los conductores estuvieran siempre atentos a la carretera.

El planteamiento del proyecto consiste en crear un clasificador de acciones para un conductor de automovil, por medio del entrenamiento de redes neuronales y otras técnicas de Visión por Computador, para identificar cuando un conductor se encuentre distraído.

Para esto se Utilizará como entrenamiento un Dataset de 22400 imágenes con su respectivo label de la acción que está haciendo, 10 en total:

    c0: safe driving
    c1: texting - right
    c2: talking on the phone - right
    c3: texting - left
    c4: talking on the phone - left
    c5: operating the radio
    c6: drinking
    c7: reaching behind
    c8: hair and makeup
    c9: talking to passenger





# Objetivo

-Clasificar las Acciones de un conductor al Volante.

-Aprender acerca de los Modelos de DeepLearning que se encuentran en el estado del arte, más especificamente los que ofrece la Librería Keras usando TensorFlow como backend.

-Aplicar los métodos vistos en las clases de Visión por Computador.

# Aplicaciones posibles

-Sistema de alerta para cuando un conductor se encuentre realizando una llamada telefónica o texteando.

-Respuesta en tiempo real para cuando un conductor se quede dormido al volante.

-Activar automáticamente configuraciones salvadas como la posición del asiento.

-Reconocimiento e indexación de conductores en base a factores de riesgo.

-Refuerzo de seguridad y auditoría en el uso de maquinaria pesada.


# Referencias
Los datos del dataset fueron recogidos de un challenge de Kaggle:

-https://www.kaggle.com/c/state-farm-distracted-driver-detection/overview

-https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html

-https://towardsdatascience.com/image-recognition-with-keras-convolutional-neural-networks-e2af10a10114
