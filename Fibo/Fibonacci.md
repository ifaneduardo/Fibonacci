Algoritmo Serie_Fibonacci
	
    Escribir "Por favor ingrese n: "
    leer n
    a<-0
    b<-1
	
	Mientras c<=n Hacer
		Escribir c
			c<-a+b
			a<-b
			b<-c
	Fin Mientras
FinAlgoritmo