# RESOLUCION-DE-EJERCIOS-1---4
def ejercicio_1():
    palabra = input("Introduce una palabra: ")
    for _ in range(10):
        print(palabra)

ejercicio_1()

def ejercicio_2():
    n = int(input("Introduce un número: "))
    while n >= 0:
        print(n)
        n -= 1
    print("Despegue!")

ejercicio_2()

def ejercicio_3():
    edad = int(input("Introduce tu edad: "))
    for año in range(1, edad + 1):
        print(año)

ejercicio_3()

def ejercicio_4():
    n = int(input("Introduce un número: "))
    for i in range(1, n + 1):
        print(i ** 2)

ejercicio_4()
