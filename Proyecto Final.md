Algoritmo Calculadora	
	// Definir variables
	definir n1,n2,opc,sum,res,multi,divi,matriz,n,f,c,summa,resma,i,j,altura,resultado,suma1,suma2,masu,mares,matriz2 Como Real;
	Escribir "Ingrese una opción que desea realizar";
	Escribir "1. sumar";
	Escribir "2. resta";
	Escribir "3. Multiplicacion";
	Escribir "4. Division";
	Escribir "5. Sumar todos los valores de matriz ";
	Escribir "6. Restar todos los valores de matriz ";
	Escribir "7. Suma de Matrices ";
	Escribir "8. Resta de matrices ";
	Escribir "9. Triangulo con numero";
	Escribir "10.Rectangulo con asteriscos";
	Leer opc;
	Si opc >= 1 y opc <=4 Entonces
		Escribir "Ingrese primer numero";
		leer n1;
		Escribir "Ingrese segundo numero";
		leer n2;
	SiNo
		Escribir "Buena eleccion vamos a los pasos";
	Fin Si
	Segun opc Hacer
		Opcion 1:
			sum = n1 + n2;
			Escribir "La suma es ", sum;
		opcion 2:
			res = n1 - n2;
			Escribir "La resta es ", res;
		opcion 3:
			multi = n1 * n2;
			Escribir "La multiplicación es ", multi;
		Opcion 4:
			divi = n1 / n2;
			Escribir "La división es ", divi;
		Opcion 5:
			summa = 0;
			Dimension matriz[100,100];
			Escribir "Ingrese tamaño de Matriz ";
			leer n;
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir "ingrese valor de matriz ","fila ",f," ","columna ",c;
					leer matriz[f,c];
				FinPara
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir Sin Saltar matriz[f,c]," ";
				FinPara
				Escribir "";
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					summa = summa + matriz[f,c];
				FinPara
			FinPara
			Escribir "La suma de la matriz es: ",summa;
		Opcion 6:
			Dimension matriz[100,100];
			Escribir "Ingrese tamaño de Matriz ";
			leer n;
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir "ingrese valor de matriz ","fila ",f," ","columna ",c;
					leer matriz[f,c];
				FinPara
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir Sin Saltar matriz[f,c]," ";
				FinPara
				Escribir "";
			FinPara
			Para f <- 1 Hasta n con paso 1 Hacer
				para c <- 1 hasta n con paso 1 Hacer
					resma = resma - matriz(f,c);
				FinPara
			FinPara
			Escribir "La resta de la matriz es: ",resma;
		opcion 7:
			suma1 = 0;
			Dimension matriz[100,100];
			Escribir "Ingrese tamaño de Matriz 1";
			leer n;
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir "ingrese valor de matriz ","fila ",f," ","columna ",c;
					leer matriz[f,c];
				FinPara
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir Sin Saltar matriz[f,c]," ";
				FinPara
				Escribir "";
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					suma1 = suma1 + matriz[f,c];
				FinPara
			FinPara
			suma2 = 0;
			Dimension matriz2[100,100];
			Escribir "Ingrese tamaño de Matriz 2";
			leer n;
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir "ingrese valor de matriz ","fila ",f," ","columna ",c;
					leer matriz2[f,c];
				FinPara
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir Sin Saltar matriz2[f,c]," ";
				FinPara
				Escribir "";
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					suma2 = suma2 + matriz[f,c];
				FinPara
			FinPara
			masu= suma1 + suma2
			Escribir "La suma de las matrices es: ",masu;
		opcion 8:
			suma1 = 0;
			Dimension matriz[100,100];
			Escribir "Ingrese tamaño de Matriz 1";
			leer n;
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir "ingrese valor de matriz ","fila ",f," ","columna ",c;
					leer matriz[f,c];
				FinPara
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir Sin Saltar matriz[f,c]," ";
				FinPara
				Escribir "";
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					suma1 = suma1 + matriz[f,c];
				FinPara
			FinPara
			suma2 = 0;
			Dimension matriz2[100,100];
			Escribir "Ingrese tamaño de Matriz 2";
			leer n;
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir "ingrese valor de matriz ","fila ",f," ","columna ",c;
					leer matriz2[f,c];
				FinPara
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					Escribir Sin Saltar matriz2[f,c]," ";
				FinPara
				Escribir "";
			FinPara
			Para f<-1 Hasta n con paso 1 Hacer
				para c<-1 hasta n con paso 1 Hacer
					suma2 = suma2 + matriz[f,c];
				FinPara
			FinPara
			mares= suma1 - suma2
			Escribir "La suma de las matrices es: ",mares;
		Opcion 9:
			escribir "Ingrese un numero entero; ";
			Leer altura;
			para i<- 1 hasta altura con paso 1 Hacer
				resultado=(i*2)-1
				para j <- resultado hasta 1 con paso -2 Hacer
					escribir sin saltar j, " "
				FinPara
				escribir " " ;
			FinPara
		opcion 10:
			Escribir "ingrese un numero entero; ";
			Leer altura;
			Para i<- 1 hasta altura con paso 1 hacer
				escribir sin saltar "* ";
			FinPara
			escribir "";
			para i<- 2 hasta altura -1 con paso 1 Hacer
				escribir sin saltar "* "
				para j <- 2 hasta altura -1 con paso 1 Hacer
					escribir sin saltar "  ";
				FinPara
				escribir "* ";
				Escribir "";
			FinPara
			para i <-1 hasta altura con paso 1 Hacer
				escribir sin saltar "* "
			FinPara
			Escribir "";
		De Otro Modo:
			Escribir "opcion incorrecta lea bien";
	FinSegun
FinAlgoritmo


