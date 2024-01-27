Algoritmo Calculo_de_volumen_y_area_del_cilindro
	Escribir 'digita una altura en cm'
	Leer altura
	Escribir 'Digita el diametro en cm'
	Leer Diametro
	AreaTotal <- (((2*pi)*((Diametro/2)))*((Diametro/2)+(altura)))
	AreaLateral <- (((2*pi)*((Diametro/2))*(altura)))
	Volumen <- ((pi)*(Diametro/2)^2)*altura
	Escribir 'el area lateral del cilindro es:', AreaLateral, 'cm²', '', 'y su area total es:', ' ', AreaTotal, 'cm² '
	Escribir 'el Volumen del cilindro es:', Volumen, 'cm³'
FinAlgoritmo

