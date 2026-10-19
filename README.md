# Calculadora Básica de Consola

Juego de Adivinanzas de palabras en Java que funciona por ventanas graficas. Para dos usuarios donde usuario_1 ingresa una palabra y al iniciar el usuario_2 debe encontrar la palabra por medio del ingreso de letras hasta completarla.

## Características

- Conteo de intentos, fallos y aciertos del usuario
- Barra de progreso que incrementa con los fallos
- Fallos permitidos: 5 max
- Bucle si se desea reiniciar el Juego
- Opción clara para salir

## Requisitos

- Java 17 o superior

## Tecnologías utilizadas

- Java
- Java JFrame

## Cómo ejecutar el proyecto

1. Clona el repositorio:
```bash
git clone https://github.com/JavFloresDev/JuegoAdivinanzas
```
2. Entrar a la carpeta del proyecto:
```bash
cd JuegoAdivinanzas/dist
```
3. Ejecuta el programa: 
```bash
java -jar Ahorcado.jar
```

## Ejemplo de uso
```
Usuario_1: Ingresa la palabra en la casilla
correspondiente y hace click en el botón
"iniciar" de la derehca.

El programa devuelve la palabra en guiones.

Usuario_2: Empieza ingresando letras en la casilla
señalizada y busca con el botón si la letra existe
en la palabra el acierto incrementa y se muestra en
la palabra secreta la posicion de la letra.

Si el usuario ingresa una letra equivocada, los
fallos incrementan y el progreso crece, cuando el
progreso y los fallos lleguen a 5 el jugador pierde
y aparece la palabra que Usuario_1 ingreso,
de lo contrario si adivina, Gana.

El proceso Juego se repite haciendo click en inciar
cuando haya ingresado otra palabra.
```

## Estructura del proyecto

```
JuegoAdivinanzas/
├── src/juego/
│   └── NewJFrame.java
├── README.md
└── LICENSE
```

## Autor

JavFloresDev — Jhonny Flores

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE [blocked] para más detalles.
