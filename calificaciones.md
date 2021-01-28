
Algoritmo calculo_promedio_ponderado
	
	Escribir "hola a todos"
	
	Escribir "nota parcial 1"
	Leer p1
	
	Escribir "nota parcial 2"
	Leer p2
	
	
	Escribir "participacion"
	Leer p3
	
	Escribir "examen final"
	Leer final
	
	p1<-(p1*0.25)
	p2<-(p2*0.25)
	p3<-(p3*0.20)
	final<-(final*0.30)
	
	ponderado <-p1+p2+p3+final
	
	Escribir "El promedio ponderado es: ", ponderado
