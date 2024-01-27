```R
Algoritmo Lea_las_4_calificaciones_de_un_estdiente_y_calcule_el_promedio_ponderado_del_curso
	Definir calculo Como real
	Mostrar  ("los valores a ingressar estan para escala de 1-5")
	Escribir 'Digite su primera calificación parcial'
	  Leer Parcial_1 
	Escribir 'Digite su segunda calificación parcial'
	  Leer Parcial_2
	Escribir 'Digite su calificación de paticipación'
  	leer Parcial_3
	Escribir 'Digite su calificación de su examen final'
	  leer Parcial_4
	Escribir 'Digite el resultado de su examen final'
	      calculo_1 <-(Parcial_1)*(25/100)
	      calculo_2 <-(Parcial_2)*(25/100)
  	      calculo_3 <-(Parcial_3)*(20/100) //no entiendo por que aparece el 16 en letras al lado izquierdo.
	      calculo_4 <-(Parcial_4)*(30/100)

notaDefinitiva = (((calculo_1+calculo_2+calculo_3+calculo_4)))
	
	Escribir "el promedio ponderado de sus notas corresponde a:", " " notaDefinitiva 
	
FinAlgoritmo
