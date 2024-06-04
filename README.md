# triangulo-
a = int(input("digite um numero: "))
b = int(input("digite um numero: "))
c = int(input("digite um numero: "))

if (a + b < c) or (a + c < b) or (b + c < a):
    print("os numeros não são medidas de um triangulo")
elif (a == b) and (a == c):
    print("são as medidas de um triangulo equilatero")
elif (a == b) or (a == c) or (b == c):
    print("são as medidas de um triangulo isósceles")
else:
    print("são as medidas de um triangulo escaleno")
