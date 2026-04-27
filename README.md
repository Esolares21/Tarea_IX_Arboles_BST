# 🌳 Proyecto: Implementación de Árboles Binarios de Búsqueda (BST)
¡Hola! 👋 Este es un proyecto que realicé para mi curso de Programación 3. El objetivo principal es poner en práctica mis conocimientos sobre estructuras de datos no lineales, específicamente los Árboles Binarios de Búsqueda (BST), utilizando el lenguaje C++.

## 🎯 ¿Para qué sirve este sistema?
Este programa es una herramienta didáctica diseñada para visualizar cómo funciona el almacenamiento y la organización de datos en un árbol. A diferencia de una lista simple, un árbol BST nos permite organizar los números de tal forma que las búsquedas y las inserciones sean más eficientes, siguiendo la regla de:

⬅️ Valores menores a la izquierda.

➡️ Valores mayores a la derecha.

## 🛠️ ¿Cómo está construido el sistema?
El sistema está desarrollado de forma modular para que el código sea fácil de leer y entender. Aquí te explico sus partes principales:

### 1. Estructura del Nodo 🏗️
Utilicé un struct llamado Nodo que contiene el valor entero (dato) y dos punteros que actúan como las "ramas" del árbol (izquierdo y derecho).

### 2. Funciones de Control ⚙️
Creación: Una función sencilla para reservar memoria cada vez que queremos agregar un número nuevo.

Inserción Recurrente: El sistema decide automáticamente dónde colocar cada número comparándolo con la raíz actual, asegurando que se mantenga la propiedad del BST.

### 3. Los 3 Recorridos Principales 🔍
Para poder visualizar los datos, implementé los tres métodos clásicos de exploración:

InOrden: Ideal para ver los números organizados de menor a mayor.

PreOrden: Útil para entender la jerarquía y cómo se fue construyendo el árbol.

PostOrden: Comúnmente usado para procesos como liberar memoria o evaluar expresiones.

## 💻 Instrucciones de Uso
Al ejecutar el programa, te encontrarás con un menú interactivo donde podrás:

Insertar valores: Puedes ir armando tu árbol número por número.

Visualizar recorridos: Elige cualquiera de los 3 métodos o incluso ver los 3 al mismo tiempo para comparar resultados.

Validaciones: El sistema te avisará si intentas mostrar un recorrido y el árbol aún no tiene datos. ⚠️

## 🎓 Aprendizaje Personal
Este proyecto me ayudó a comprender mejor el uso de la recursividad y la importancia de la gestión de punteros en C++. Es un paso fundamental en mi camino como estudiante de ingeniería para dominar estructuras de datos más complejas en el futuro. 🚀

Desarrollado por: Erix Alejandro Solares Flores 👨‍💻
Curso: Programación 3 
