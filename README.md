# misiontic
mision tic retos de programación

RETO 1.1654
Nombre del reto:	Lector del nivel de la calidad del agua en poblaciones apartadas
Descripción de reto con su respectiva solución:
En el año 2015, los líderes mundiales adoptaron un conjunto de objetivos globales para erradicar la pobreza, proteger el planeta y asegurar la prosperidad para todos como parte de una nueva agenda de desarrollo sostenible. De aquí a 2030, se busca lograr el acceso universal y equitativo al agua potable a un precio asequible para todos. 

Algunas ONG’s se atribuyeron la tarea de poder diseñar un dispositivo para analizar la calidad del agua de poblaciones apartadas. Para comenzar, requieren que el dispositivo cuente con un lector de la calidad del agua. Después de la lectura, el dispositivo nos entrega el índice de riesgo de la calidad del agua, IRCA, y según este resultado debe indicar el nivel de riesgo. 

Clasificación IRCA (%) 	Nivel de riesgo	Entidades a notificar	Entidades a tomar acciones
80.1 - 100	INVIABLE SANITARIAMENTE	Persona prestadora, COVE, Alcaldía, Gobernación, SSPD, MPS, INS, MAVDT, Contraloría General, Procuraduría General	Persona prestadora, alcaldía, gobernación, entidades de orden territorial
35.1 - 80	ALTO	Persona prestadora, COVE, Alcaldía, Gobernación, SSPD	Persona prestadora, alcaldía, gobernación
14.1 - 35	MEDIO	Persona prestadora, COVE, Alcaldía, Gobernación	Persona prestadora
5.1 - 14	BAJO	Persona prestadora, COVE	
0 - 5	SIN RIESGO	Continuar el control y la vigilancia	Continuar vigilancia

Se requiere leer una variable de entrada que indique el porcentaje de la clasificación IRCA y devuelva como resultado el nivel de riesgo asociado a este porcentaje.  Para el caso donde el IRCA tenga una lectura entre 0 - 5, el programa debe devolver el siguiente mensaje: “Continuar el control y la vigilancia”.


Ejemplos:
Entrada esperada	Salida esperada
7.9	4
BAJO	SIN RIESGO

Nota: Las tildes y cualquier otro signo ortográfico han sido omitidos a propósito en las entradas y salidas del programa. Por favor NO use ningún signo dentro del desarrollo de su solución ya que estos pueden representar errores en la calificación automática de Codegrade.
