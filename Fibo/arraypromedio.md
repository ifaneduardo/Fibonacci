Proceso Promedio
	
    Escribir "Ingrese la cantidad de datos:"
    Leer n
	Dimension arreglo[n];
    acum<-0
    
    Para i<-1 Hasta n Hacer
        Escribir "Ingrese el dato ",i,":"
        Leer dato
		arreglo[i]<-dato
    FinPara
	acum<-0
	Para i<-1 Hasta n Hacer
		acum<-acum+arreglo[i]
	FinPara
	
    prom<-acum/n
    
    Escribir "El promedio es: ",prom
    
FinProceso