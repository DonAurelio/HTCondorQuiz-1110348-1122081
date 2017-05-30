# HtcondorQuiz-1110348-1122081
Este repositorio contiene un ejemplo practico acerca de la ejecucucion de tareas con HTCondor usando un **DAGMAN**. las tareas a ejecutar se especifican a continuacion:

* **wget.condor** Este archivo le indica a Condor que debe  descargar tres archivos fuente de un repositorio especifico. 
* **compilar.condor** Este archivo le indica a Condor que debe compilar tres archivos fuente que fueron descargados en el paso anterior. 
* **ejecutar.condor** Este archivo le indica a Condor que debe ejecutar los binarios producidos en el proceso de compílación anterior.
* **all.dag** Este archivo le indica a Condor de qué forma se deben ejecutar las tareas siendo que no se puede **compilar** antes de haber descargado los archivos y tampoco de pueden **ejecutar** los archivos antes de haberlos compilado. 
