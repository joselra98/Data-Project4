# G10_DP4
## Data Project 4 - Master Data Analytics EDEM 2022

## Meet our team

- [Jose Luis Rodriguez](https://github.com/joselra98)
- [Luis Andreu](https://github.com/Luisand8)

## Descripción

Clasificación de imagenes de rayos x por medio de redes neuronales 

 
## DATOS

- train
- test
- train.csv
- sample_submission.csv


## PREPROCESAMIENTO

Transformación de las imágenes dicom, que suele ser el formato de las imágenes médicas a .jpg para poder hacer el entrenamiento de forma correcta.
Para poder transformar el train y el test, sino diispones de Colab Pro, tendrás que dividirlo en dos cuentas para que no haya problemas de espacio RAM.

- [Preprocesamiento](https://github.com/joselra98/Data-Project4/blob/main/Data_Project_4_Preprocesamiento.ipynb)

## ENTRENAMIENTO DEL MODELO
Clasificamos las imágenes de rayos x en diferentes tip: brazos, piernas...utilizando la librería FAST Ai y utilizamos el modelo DENSENET201

- Batch size 32
- Size 256
- Epochs 25

- [Modelo](https://github.com/joselra98/Data-Project4/blob/main/Copia_de_Data_Project_4_Modelo.ipynb)

## ACCURACY = 0.93902
