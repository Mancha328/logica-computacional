# Ejercicio 1: Par o impar

## Problema
Determinar si un número entero es par o impar.

## Entrada
Un número entero.

## Proceso
INICIO
  Leer n
  residuo ← n MOD 2
  SI residuo = 0 ENTONCES
    Escribir "Par"
  SINO
    Escribir "Impar"
  FIN SI
FIN

Un número es par cuando es divisible entre 2, es decir, cuando n MOD 2 = 0.

## Salida
Indicar si el número es par o impar.

## Pruebas
| Entrada | Resultado esperado |
|---------|--------------------|
| 8 | Par |
| 7 | Impar |
| 0 | Par |
| -3 | Impar |
