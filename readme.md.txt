Trabajo realizado por Alejandro Morales Chavarri

Se trata de un extractor de términos para el castellano utilizando el modelo de XLM RoBERTa.

Para instalar se pueden utilizar tanto las librerias como los pips comentados en el fichero


El corpus se debe establecer de la siguente manera:
\Carpeta\
	\train\(txt con corpus de entrenamiento)
	\valid\(txt con corpus de validación)
	\eval\(txt con corpus de evaluación)
	\trainAnotated\traintokens.csv 
	\validAnotated\validtokens.csv
	\evalAnotated\evaltokens.csv
Siendo estos tres últimos archivos los correspondientes a los términos considerados correctos

Previo a la ejecución se debe indicar la ruta de la carpeta que posee el corpus en la variable "ruta" del archivo main
Para su ejecución se debe realizar una ejecución de cada uno de los archivos de python siendo el último de ellos __main__.py