Tarea 2 - Ejercicios Unidad 1
Enunciado:
Crear un programa que intercambie los valores de dos variables.
a = 5
b = 10

temp = a
a = b
b = temp

print("Nuevo valor de a:", a)
print("Nuevo valor de b:", b)
Explicación:
Se usa una variable temporal (temp) para guardar el valor de a mientras se intercambian los valores.
Enunciado 2:
Pedir al usuario cuántas horas trabajó y cuánto gana por hora. Calcular su salario.
horas = float(input("Horas trabajadas: "))
pago_hora = float(input("Pago por hora: "))

salario = horas * pago_hora

print("Su salario semanal es:", salario)
Explicación:
Multiplicamos las horas trabajadas por el valor que gana el usuario por cada hora.
Enunciado 3:
Convertir una temperatura en grados Celsius a Fahrenheit.
celsius = float(input("Temperatura en °C: "))
fahrenheit = (celsius * 9/5) + 32

print("Equivalente en °F:", fahrenheit)
Explicación:
Se usa la fórmula básica para convertir temperaturas.
Enunciado 4:
Calcular el área de un rectángulo con base y altura ingresadas por el usuario.
base = float(input("Base: "))
altura = float(input("Altura: "))

area = base * altura

print("Área del rectángulo:", area)
Explicación
se multiplica la base por la altura y aasi se obtiene el resultado
Enunciado 5:
Pedir tres números y mostrar su promedio.
n1 = float(input("Número 1: "))
n2 = float(input("Número 2: "))
n3 = float(input("Número 3: "))

promedio = (n1 + n2 + n3) / 3

print("El promedio es:", promedio)
Explicación:
Se suman los tres valores y se divide entre 3.
Enunciado 6:
determinar si un numero es par o impar
numero = int(input("Ingrese un número: "))

if numero % 2 == 0:
    print("El número es par.")
else:
    print("El número es impar.")
Explicación:
Un número es par si el residuo al dividir entre 2 es cero.
Enunciado 7:
determinar si un número es positivo, negativo o cero
num = float(input("Ingrese un número: "))

if num > 0:
    print("El número es positivo.")
elif num < 0:
    print("El número es negativo.")
else:
    print("El número es cero.")
Explicación:
Se compara el número con cero usando condicionales.
ejercicio 
calculadora básica
print("1. Sumar")
print("2. Restar")
print("3. Multiplicar")
print("4. Dividir")

op = int(input("Elija una opción: "))
a = float(input("Número 1: "))
b = float(input("Número 2: "))

if op == 1:
    print("Resultado:", a + b)
elif op == 2:
    print("Resultado:", a - b)
elif op == 3:
    print("Resultado:", a * b)
elif op == 4:
    if b != 0:
        print("Resultado:", a / b)
    else:
        print("Error: división entre cero.")
else:
    print("Opción inválida.")
Explicación:
Se usa un menú con condicionales para que se pueda hacer la operación seleccionada.
ejercicio
tabla de multiplicar 
n = int(input("Ingrese un número: "))

for i in range(1, 11):
    print(n, "x", i, "=", n * i)
Explicación:
El ciclo for imprime la tabla del 1 al 10.
ejercicio
suma de numeros del 1 al 100
suma = 0

for i in range(1, 101):
    suma += i

print("La suma del 1 al 100 es:", suma)
Explicación:
Se acumula la suma usando un ciclo for.
Referencias IA
### Referencias de IA
- ChatGPT me brindó ayuda para entender los ejercicios de la Unidad 1.
