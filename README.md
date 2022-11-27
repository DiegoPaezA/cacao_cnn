# Reconocimiento del estado de madurez de la mazorca de Cacao usando CNN

## Objetivo

Diseñar un modelo de inteligencia artificial que clasifique la madurez de la mazorca del cacao utilizando imágenes fotográficas para que las separe entre maduras e inmaduras.

## Descripción

La problemática que se intenta resolver es la siguiente: La recolección de las mazorcas del cacao se realiza una vez esta logra cierto grado de madurez, el cual se ve reflejado en el color que tiene el fruto. La cosecha se realiza en las instalaciones de AGROSAVIA de forma manual y depende exclusivamente de los conocimientos y experiencia que tiene el cosechador. Este proceso debe garantizar que solo se recolecten las mazorcas del cacao que estén completamente maduras sin que se afecte la calidad de los diferentes productos obtenidos a base del grano de cacao. 

Es importante tener en cuenta que las mazorcas del cacao demuestran su madurez con diferentes colores, por lo tanto, el modelo de inteligencia artificial que se diseñe debe reconocer todos estos colores y realizar una correcta clasificación. Además, este debe tener una operabilidad sencilla, teniendo en cuenta que este modelo puede ser soporte en la toma de decisiones de los cosechadores al momento de realizar dichas tareas sin necesitar de una capacitación técnica compleja.

[Cocoa Ripeness Dataset](https://www.kaggle.com/andrewmvd/cocoa-ripeness-dataset)

<a href="https://imgbb.com/"><img src="https://i.ibb.co/JnPPPp5/descargar.png" alt="descargar" border="0"></a>

| Notebook                             |Clasificación de madurez de cacao con CNN secuencial               |
|---                                   |---                                                                |
| [cacao_cnn_seq](https://is.gd/MMIVoM)            | dataset **Cocoa_Dataset** |
| [cacao_cnn_seq_coco](https://is.gd/kshVd6)       | output sigmoid - dataset prefeched TF **Cocoa_coco** |
| [cacao_cnn_seq_coco_2x](https://is.gd/mnStTX)    | output softmax - Confusion Matrix - dataset prefeched TF **Cocoa_coco** |
| [cacao_cnn_seq_coco_3x](https://is.gd/YFYYpu)    | output softmax - Confusion Matrix - dataset manually load **Cocoa_coco** |