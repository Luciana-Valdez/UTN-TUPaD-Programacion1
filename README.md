# UTN-TUPaD-Programacion1

TP1 - Programación I - Luciana Valdez

1)
print ("Hola mundo")

2)

nombre= input("Ingrese su nombre: ")
print (f"Hola {nombre}" "!")

3)

nombre= input("Ingrese su nombre: "),
apellido= input("Ingrese su apellido: "),
edad= input("Ingrese su edad: "),
residencia= input("Ingrese su lugar de residencia: "),
print(f"Soy {nombre} {apellido}, tengo {edad} años y vivo en {residencia}")

4)

radio= float(input("Por favor, ingrese el radio del circulo: "))
pi= 3.1416
area= pi * radio ** 2
perimetro= 2 * pi * radio
print (f"El área del círculo es {area} y el periímetro del círculo es {perimetro}")

5)

segundos= float(input("Ingrese la cantidad de segundos que desea pasar a horas: "))
horas= segundos / 3600
print (f"{segundos} segundos equivalen a {horas} hora/s.")

6)

n= int(input("Ingrese un número entero para saber su tabla: "))
if n > 0:
    for i in range(1,11):
        print (n, "x", i, " = ", n*i)
else:
    print( "El número ingresado no es correcto")

7)

a= float(input("Ingrese un número entero: "))
b= float(input("Ingrese otro número entero: "))
suma= a+b
resta= a-b
division= a/b
multiplicacion= a*b
print(f"{a} + {b} = {suma}, {a} - {b} = {resta}, {a} / {b} = {division}, {a} * {b} = {multiplicacion}")

8)

peso= float(input("Ingrese su peso (Kg): "))
altura= float(input("Ingrese su altura (mts): "))
imc= peso / (altura**2)
print("Su índice de masa corporal es", imc)

9)

c= float(input("Ingrese una temperatura en grados Celcius: "))
f= c * 1.8 + 32
print(f"{c} grados Celcius son equivalentes a {f} grados Fahrenheit")

10)

n1= float(input("Ingrese el primer número: "))
n2= float(input("Ingrese el segundo número: "))
n3= float(input("Ingrese el tercer número: "))
p= (n1 + n2 + n3) / 3
print ("El promedio de los tres numeros ingresados es: ", p)