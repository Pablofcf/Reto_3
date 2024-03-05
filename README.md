Aquí subo pruebas del reto 3

Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.

Diagrama de Flujo

https://www.mermaidchart.com/raw/aedcc305-eda3-4914-aa99-2830efb7bfa1?theme=light&version=v0.1&format=svg

Pseudocódigo

[variables]
n : natural
i : natural

inicio
listado de 2 hasta n+1 
listado de 2 hasta i+1

escribir [n / i]
{modulo condiconal con la pregunta ¿Únicamente tiene dos residuos de 0?}
  si modulo [n/i = a dos 0 como residuo]
  escribir [n es primo]
  si no [n/i = a más de dos 0 como residuo]
   escribir [n no es primo]
Fin 

Demostración VS Code - Python

![image](https://github.com/Pablofcf/Mi-repo/assets/159049788/c0cad6cd-fa53-4dda-8842-d5600c446ef2)
![image](https://github.com/Pablofcf/Mi-repo/assets/159049788/b3d11b5b-6fbc-439a-af43-75d82f336176)


Revise el procedimiento matemático para hallar raíces cuadradas (son divisiones y restas), plantee el algoritmo en pseudocódigo y en diagrama de flujo.

Diagrama de flujo 

https://www.mermaidchart.com/raw/6617765a-b5c3-4697-b67c-1d634f1c365d?theme=dark&version=v0.1&format=svg

Pseudocódigo

[variables]
n : raíz de un número 
x : natural
y : natural diferente de x
≈ : aproximado

inicio
escribir [Separar las cifras en pares de derecha a izquierda]
{modulo condiconal con la pregunta ¿Las parejas están completas?}
  si modulo [x * x = primera pareja]
  escribir [primera pareja ≈]
  si no [x * y = primera pareja]
   escribir [primera pareja ≈]
   
escirbir [Restar el aproximado con la primera pareja y bajar residuo]
escribir [Tomar el resultado de la primera pareja y multiplicarlo por 2]
escribir [Combinar el resultado con números del 1 al 5 y multiplicarlos por los mismos números en órden consecutivo]
escribir [Escoger el resultado más cercano al residuo]
{modulo condiconal con la pregunta ¿Al restar el residuo es exacto?}
  si modulo, escribir [Es un número natural
  si no, escribir [Es un número racional]

Fin 
