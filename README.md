# clases didacticas de Python

El modelos de `tensores (array 3D)` que usamos surge de la necesidad de representar la marca o huella de comportamiento de transacciones que realiza un cliente en un determinado periodo `Per` (en nuestro caso cada semana), las dimensiones que representamos en nuestro tensor son:

- `Parte 1`: Qué es POO, conceptos básicos, tipos de variables y declaraciones de variables.
- `Parte 2`: Estructuras condicionales IF y ELSE y listas
- `Parte 3`: Íteración: For y While
- `Parte 4`: Métodos y Funciones.

## Details
La representacion del taller es abierta y todos pueden participar, así como proponer ejemplos:

![Match function](https://user-images.githubusercontent.com/7105645/46182744-421d5600-c293-11e8-8b30-efd93fa1395a.png)

los demas archivos y el código se encuentran aquí, solo instalate `git` o descargalo como un `.ZIP`.
```git
git clone https://github.com/johnkevinbarrera/clasespython.git
```

## References

### Parte 1 
[Enlace Aquí](https://github.com/johnkevinbarrera/clasespython/blob/master/Parte%201.ipynb)

- `Conceptos de Clases`: Qué es POO y como podemos representar Clases en Python.
- `Preparacion de nuestro entorno de Trabajo`: IDE's y herramienta en la cuales podemos Codear en  Python.
- `Tipos de Variables`: en Python es simple!, tenemos enteros, flotantes y complejos para numericos, cadenas para los textos, boleanos y algunos poco mas.
- `Operadores en Python`: Operadores Matemáticos y como funcionan en datos numéricos y no numéricos.


### Parte 2 
[Enlace Aquí](https://github.com/johnkevinbarrera/clasespython/blob/master/Parte%202.ipynb)


### Parte 3 
[Enlace Aquí](https://github.com/johnkevinbarrera/clasespython/blob/master/Parte%203.ipynb)


### Parte 4 
[Enlace Aquí](https://github.com/johnkevinbarrera/clasespython/blob/master/Parte%204.ipynb)


### Parte 5 
[Enlace Aquí](https://github.com/johnkevinbarrera/clasespython/blob/master/Parte%205.ipynb)


### Parte 6 
[Enlace Aquí](https://github.com/johnkevinbarrera/clasespython/blob/master/Parte%206.ipynb)






```git
def fibo(pos):
    if pos == 0:
        return(1)
    if pos == 1:
        return(1)

    return(fibo(pos-1) + fibo(pos-2))

print("ingrese posicion: ")
n = int(input())
print(fibo(n))
```

```git
def fibo(pos):
    f1 = 1   # alejado una posicion de pos
    f2 = 1   # alejado dos posicion de pos
    if pos<=1:
        return 1
    help = 0
    for i in range(1,pos):
        help = f1 + f2
        f2 = f1
        f1 = help
    return help

print("ingrese posicion: ")
n = int(input())
print(fibo(n))
```


